# Manage Attachments Plugin #

## Description ##

The plugin provides a page that lists attachments and allows you to delete those that are no longer used.
The page is added to the System menu.

## Installation ##

### Dependencies ###

Requires php version 5.2 or later.

Requires the Common Plugin to be installed. 

See <https://github.com/bramley/phplist-plugin-common>

### Set the plugin directory ###
You can use a directory outside of the web root by changing the definition of `PLUGIN_ROOTDIR` in config.php.
The benefit of this is that plugins will not be affected when you upgrade phplist.

### Install through phplist ###
Install on the Plugins page (menu Config > Plugins) using the package URL `https://github.com/bramley/phplist-plugin-attachment/archive/master.zip`.

In phplist releases 3.0.5 and earlier there is a bug that can cause a plugin to be incompletely installed on some configurations (<https://mantis.phplist.com/view.php?id=16865>). 
Check that these files are in the plugin directory. If not then you will need to install manually. The bug has been fixed in release 3.0.6.

* the file AttachmentPlugin.php
* the directory AttachmentPlugin

### Install manually ###
Download the plugin zip file from <https://github.com/bramley/phplist-plugin-attachment/archive/master.zip>

Expand the zip file, then copy the contents of the plugins directory to your phplist plugins directory.
This should contain

* the file AttachmentPlugin.php
* the directory AttachmentPlugin

## Donation ##

This plugin is free but if you install and find it useful then a donation to support further development is greatly appreciated.

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=W5GLX53WDM7T4)

## Version history ##

    version     Description
    2013-10-25  Added to GitHub
    2013-10-18  Initial version for phplist 3.0 converted from 2.10 version
