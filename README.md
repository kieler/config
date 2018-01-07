# OpenKieler Configurations

This repository contains setup and configuration files for working on OpenKieler projects. Follow these steps to install an IDE ready for OpenKieler development:

1. Go to [this site](https://www.eclipse.org/downloads/index.php) and download the Eclipse Installer for your platform, unless you already have it.

1. Start the installer. Click the Hamburger button at the top right corner and select Advanced Mode. Why? Because we're computer scientists, that's why!

1. On the _Product_ page, select _Eclipse Modeling Tools_ as the base on which to install everything required for OpenKieler development. Click _Next_.

1. Unless you already have the _OpenKieler_ project in the projects list, click the green plus button at the top right corner. Choose the _Github Projects_ catalog and use the following as the resource URI: `https://raw.githubusercontent.com/OpenKieler/config/master/OpenKieler.setup` Hit _OK_.

1. Make sure that the _OpenKieler_ project is selected and hit _Next_.

1. Oomph now asks you to enter some more information. You can usually leave the settings as is, except for the Installation folder name. This will be the directory under which all your Eclipse installations installed with Oomph will appear, each in a separate sub-directory. Select a proper directory and click _Next_.

1. If Oomph fails to clone our GitHub repository, this is probably due to Eclipse not finding your SSH key for GitHub. Fix it by going to the Eclipse preferences. You can manage your keys under General > Network Connections > SSH2. Once you have setup your SSH keys, let Oomph try again by selecting Perform Setup Tasks from the Help menu.
