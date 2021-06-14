## Continued on back → 

 conda info conda update -n base conda 

 conda update anaconda 

Getting Started Verify Conda is installed, check version number Update Conda to the current version Update all packages to the latest version of Anaconda. Will install stable and compatible versions, not necessarily the very latest. 

 conda create --name ENVNAME python=3.6 "PKG1>7.6" PKG2 conda activate ENVNAME conda activate /path/to/environment-dir conda deactivate conda list conda list --name ENVNAME conda list --revisions conda list --name ENVNAME --revisions conda install --name ENVNAME --revision REV_NUMBER conda remove --name ENVNAME --all 

Make an exact copy of an environment Export an environment to a YAML file that can be read on Windows, macOS, and Linux Create an environment from YAML file Create an environment from the file named environment.yml in the current directory Export an environment with exact package versions for one OS Create an environment based on exact package versions 

 conda create --clone ENVNAME --name NEWENV conda env export --name ENVNAME > envname.yml conda env create --file envname.yml conda env create 

 conda list --explicit > pkgs.txt 

 conda create --name NEWENV --file pkgs.txt 

Sharing Environments 

Working with Environments Create a new environment named ENVNAME with specific version of Python and packages installed. Activate a named Conda environment Activate a Conda environment at a particular location on disk Deactivate current environment List all packages and versions in the active environment List all packages and versions in a named environment List all revisions made within the active environment List all revisions made in a specified environment Restore an environment to a previous revision 

Delete an entire environment TIP: Anaconda Navigator is a desktop graphical user interface to manage packages and environments with Conda. With Navigator you do not need to use a terminal to run Conda commands, Jupyter Notebooks, JupyterLab, Spyder, and other tools. Navigator is installed with Anaconda, and may be added with Miniconda. 

 Take a conda test drive at bit.ly/tryconda Windows, macOS, Linux: Same commands for all platforms. 

 For full documentation of any command, add --help to the command. EXAMPLE: conda create --help 

# CONDA 4.6 CHEAT SHEET 

---

 conda search PKGNAME --info conda clean --all conda uninstall PKGNAME --name ENVNAME conda update --all --name ENVNAME conda install --yes PKG1 PKG2 conda config --show conda config --show-sources 

Using Packages and Channels Search for a package in currently configured channels with version range >=3.1.0, <3.2" Find a package on all channels using the Anaconda Client Install package from a specific channel Install a package by exact version number (3.1.4) Install one of the listed versions (OR) Install following several constraints (AND) Add a channel to your Conda configuration 

Follow us on Twitter @anacondainc and join the #AnacondaCrew! Connect with data scientists and developers and contribute to the open source movement at anaconda.com/community 

About Anaconda 

With over 11 million users, Anaconda is the world’s most popular Python data science platform and the foundation of modern machine learning and AI. Anaconda Enterprise simplifies and automates collaboration and deployment of machine learning and AI at speed and scale, unleashing the full potential of your organization. 

Additional Useful Hints Detailed information about package versions Remove unused cached files including unused packages Remove a package from an environment Update all packages within an environment Run most commands without requiring a user prompt. Useful for scripts. Examine Conda configuration and configuration services 

More Resources 

Free Community Support Online Documentation Paid Support Options Anaconda On-Site Training Courses Anaconda Consulting Services 

 http://bit.lyconda_list https://conda.io anaconda.com/support anaconda.com/training anaconda.com/consulting 

 anaconda search FUZZYNAME conda install conda-forge::PKGNAME conda install PKGNAME==3.1.4 conda install "PKGNAME[version='3.1.2|3.1.4']" conda install "PKGNAME>2.5,<3.2" conda config --add channels CHANNELNAME 

 conda search PKGNAME=3.1 "PKGNAME [version='>=3.1.0,<3.2']" 

 anaconda.com · info@anaconda.com · 512-776-1066 · v1.2019 

