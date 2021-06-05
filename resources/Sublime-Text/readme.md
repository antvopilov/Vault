# Sublime Text

## Download

- [Sublime Text - Text Editing, Done Right](http://www.sublimetext.com/)
- [Sublime Merge | Git client from the makers of Sublime Text](https://www.sublimemerge.com/)


## Launch Sublime Text from the Terminal

[Launch Sublime Text from the Terminal](https://www.youtube.com/watch?v=4wMKGs2fe4s&list=PL-osiE80TeTtHH8BZngXEsLPGotQxZa6z&index=6)

```shell
ln -s /Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl /usr/local/bin/subl
```

```shell
ls -la /usr/local/bin/ | grep subl
```

## Package Control

[Package Control - the Sublime Text package manager](https://packagecontrol.io/)

## Markdown

- [MarkdownPreview: Markdown preview and build plugin](https://github.com/facelessuser/MarkdownPreview)
- [MarkdownEditing: Powerful Markdown package](https://github.com/SublimeText-Markdown/MarkdownEditing)

## Python
[Setting up a Python Development Environment in Sublime Text](https://www.youtube.com/watch?v=xFciV6Ew5r4&t=3s)

[Anaconda, the Python IDE for Sublime Text 3](http://damnwidget.github.io/anaconda/)

## Another Packages
- AdvancedNewFile - File creation plugin.
- Emmet
- Git Gutter - display changed/added lines in the margin of the editor window.
- jsFormat - Javascript formatting.
- LiveReload - LiveReload plugin.
- Side Bar Enhancments - Enhancements to Sublime Text sidebar. Files and folders.
- Sublime Git - Git Integration for Sublime.
- Sublime Linter - Interactive code linting.
- TrailingSpaces - Highlight trailing spaces and delete them in a flash.

## Sublime Settings Preferences
  
```json
{
    "bold_folder_labels": true,
    "caret_extra_width": 1,
    "caret_style": "phase",
    "close_windows_when_empty": false,
    "color_scheme": "Packages/Predawn/predawn.tmTheme",
    "copy_with_empty_selection": false,
    "drag_text": false,
    "draw_minimap_border": true,
    "draw_white_space": "none",
    "enable_tab_scrolling": false,
    "ensure_newline_at_eof_on_save": true,
    "file_exclude_patterns":
    [
        "*.pyc",
        "*.pyo",
        "*.exe",
        "*.dll",
        "*.obj",
        "*.o",
        "*.a",
        "*.lib",
        "*.so",
        "*.dylib",
        "*.ncb",
        "*.sdf",
        "*.suo",
        "*.pdb",
        "*.idb",
        ".DS_Store",
        "*.class",
        "*.psd",
        "*.sublime-workspace"
    ],
    "font_face": "Source Code Pro",
    "font_options":
    [
        "no_round"
    ],
    "font_size": 20,
    "highlight_line": true,
    "highlight_modified_tabs": true,
    "ignored_packages":
    [
        "ActionScript",
        "AppleScript",
        "ASP",
        "D",
        "Diff",
        "Erlang",
        "Graphviz",
        "Groovy",
        "HTML-CSS-JS Prettify",
        "Lisp",
        "Lua",
        "Objective-C",
        "OCaml",
        "Rails",
        "Ruby",
        "Vintage"
    ],
    "installed_packages":[
        "Anaconda",
        "BracketHighlighter",
        "Material Theme",
        "Predawn",
        "SideBarEnhancements"
    ],
    "line_padding_bottom": 1,
    "line_padding_top": 1,
    "match_brackets_content": false,
    "match_selection": false,
    "match_tags": false,
    "material_theme_accent_graphite": true,
    "material_theme_compact_sidebar": true,
    "mini_diff": false,
    "open_files_in_new_window": false,
    "overlay_scroll_bars": "enabled",
    "preview_on_click": false,
    "scroll_past_end": true,
    "scroll_speed": 5.0,
    "show_definitions": false,
    "show_encoding": true,
    "show_errors_inline": false,
    "show_full_path": false,
    "sidebar_default": true,
    "swallow_startup_errors": true,
    "theme": "Material-Theme-Darker.sublime-theme",
    "translate_tabs_to_spaces": true,
    "trim_trailing_white_space_on_save": true,
    "use_simple_full_screen": true,
    "word_wrap": false
}
```

## Python-3.sublime-build 

```json
{
    "cmd": ["/usr/local/bin/python3", "-u", "$file"],
    "file_regex": "^[ ]*File \"(...*?)\", line ([0-9]*)",
    "quiet": true
}
```

## Sublime Settings Anaconda

```json
{
    "auto_formatting": true,
    "autoformat_ignore":
    [
    ],
    "pep8_ignore":
    [
        "E501"
    ],
    "anaconda_linter_underlines": false,
    "anaconda_linter_mark_style": "none",
    "display_signatures": false,
    "disable_anaconda_completion": true,
    "python_interpreter": "/usr/local/bin/python3"
}
```

## Sublime Settings Conda

```json
{
    "executable": "/Users/antonvopilov/opt/anaconda3/bin/python3",
    "environment_directory": "/Users/antonvopilov/opt/anaconda3/envs",
    "configuration": "/Users/antonvopilov/.condarc",
}
```

## Sublime Packages

```json
{
	"bootstrapped": true,
	"in_process_packages":
	[
	],
	"installed_packages":
	[
		"Anaconda",
		"BracketHighlighter",
		"Conda",
		"LiveReload",
		"MarkdownEditing",
		"MarkdownPreview",
		"Package Control",
		"SideBarEnhancements",
		"SublimePythonIDE",
		"Terminal",
	],
}

```