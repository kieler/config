# OpenKieler Configurations

This repository contains setup and configuration files for working on the OpenKieler project.

## OpenKieler.setup

Setup file to be used with Oomph, see below.

### Setting Up Your Development Environment
You will first need an Eclipse installation to hack away on OpenKieler with. Since we have a shiny Oomph setup available, this turns out to be comparatively painless (note that our setup assumes that you have a GitHub account):

1. Go to [this site](https://www.eclipse.org/downloads/index.php) and download the Eclipse Installer for your platform. You will find the links at the bottom of the "Try the Eclipse Installer" box.

2. Start the installer. Click the Hamburger button at the top right corner and select Advanced Mode. Why? Because we're computer scientists, that's why!

3. Next, we need to tell Oomph to get everything ready for OpenKieler development. Download our [Oomph setup file](https://raw.githubusercontent.com/OpenKieler/config/master/OpenKieler.setup), click the Plus button at the top right corner and add the setup file to the Github Projects catalog. Double-click the new OpenKieler entry. This will cause an item to appear in the table at the bottom of the window. Once you're done, click Next.

3. Oomph now asks you to enter some more information. You can usually leave the settings as is, except for the Installation folder name. This will be the directory under which all your Eclipse installations installed with Oomph will appear, each in a separate sub-directory. Select a proper directory and click Next.

5. If Oomph fails to clone our GitHub repository, this is probably due to Eclipse not finding your SSH key for GitHub. Fix it by going to the Eclipse preferences. You can manage your keys under General > Network Connections > SSH2. Once you have setup your SSH keys, let Oomph try again by selecting Perform Setup Tasks from the Help menu.

## de.cau.cs.kieler.openkieler.targetplatform

Target platform definition used by [DebukViz](https://github.com/OpenKieler/debukviz), [EcoreViz](https://github.com/OpenKieler/ecoreviz) and [KlassViz](https://github.com/OpenKieler/klassviz).
The contained definition file `de.cau.cs.kieler.openkieler.targetplatform.target` should be copied to the corresponding `build` directory of the three mentioned project if updated.
