<h1 align="center">ModioX</h1>

<h3 align="center">Browse, Download and Install Mods to the PlayStation 3</h3>
<div align="center">
</div>
<br />

A federated desktop application for browsing a regularly updated library of mods, homebrew and themes. Populated by myself and a few friends so that they're verified and tested to work. The core purpose is to provide users with an efficient method for browsing, downloading and installing game mods directly to their console, without the need for searching modding forums or using file managers - this does it all for you.

![ModioX](https://github.com/ohhsoash/ModioX/blob/master/Images/Screenshot1.png?raw=true) 

## Main Features
* Browse games, categories and favorites
* Discover game mods, apps and resources
* Complete details, creator, version and other info
* Filter mods by firmware or type
* Supports every type of mods and files
* Download archives to computer
* Install files directly to console
* Uninstall files from console
* Automatically detect game region, or manually
* Built-in ftp client features, with directory listings 
* Add and save multiple console profiles

## Usage

### Requirements
* An internet connection
* .NET Framework 4.6.2
* PlayStation 3 with CFW

### Getting Started
At the top go to **Settings** > **Edit Consoles** so you can add and save your console. Your address can be found under **System Information** from playstation console.

### Connecting to Console
Either select your console from the dropdown menu or type it manually in the textbox, then hit the **Connect** button.

### Browsing Mods
Finding mods is extremely simple too. Start by choosing something from the ongoing list of game titles or categories. 

Mods that are available on our database will be loaded into the gridview, including the name, version, creator, etc. You can also filter these results for your preferred console and mod type. 

Further details that you'll need to know will be displayed when selecting an item from the list, important information such as firmware, configuration, description and more. 

### Installing Mods
Before install any files, make sure that your console is either at the XMB menu or with Rebug Toolbox open. Otherwise installing could cause issues such as console freezing or game crashing. It's not recommended. 

A compressed archive containing the modded files and a set of installation paths are included by default with each, so the **Install** process will be to the appropriate paths to work as instructed/intended.

### Uninstalling Mods
The **Uninstall** option is still being worked on to allow for original files to be backed up. But for now it will remove the specified installation files. Ones that are installed into your game folders are not deleted as it could cause issues with playing the game, these can include the _EBOOT.BIN_, _patch_mp.ff_, etc. You may be able to find the original/default files from the database, install those after uninstalling the game mods. 

### Downloading Mods
You're also able to **Download** the compressed archive to somewhere on your computer. This will create and write a readme file containing the kids information too. Ideal for sending to friends or installing manually.

### Reporting
It's encouraged to submit reports of any issues that may occur with mods or files, whether that's with ingame or installing. It will be looked into by someone and fixed as soon as possible.

### File Explorer
This includes a simple ftp client that allows easily navigating both computer and console file systems. Go through your computer folders and choose the desired file, do the same to your console folders to where you'd like to upload the file then hit **Upload**, otherwise you can download or delete files from your console too. Maybe more coming soon. 

## ModioX Installation
Download and run the latest version of the Windows installer, "ModioX.Installer.Windows.exe" from the [releases](https://github.com/ohhsoash/ModioX/releases/latest) page.

## Contributing to Project
Please supply as much information about the problem you are experiencing as possible. Your issue has a much greater chance of being resolved if logs are supplied so that we can see what is going on, which will be found the application startup directory. You're also welcome to submit any pull requests with fixes and suggestions, like additional features for making this project even more great. But, please open an issue so we can discuss things before going further so maybe we can work on this together!

## Requesting Mods
I understand that currently not all mods will be available, so I welcome you to please use the **Request Mods** to open an issue with the details and they will be submitted by someone on your behalf.

## Credits / Libraries
- Appropriate Authors of the Mods
- DarkUI for WinForms
- Newtonsoft.Json

## Disclaimer
I can accept no responsibility for any damage you cause to your system by using this tool. Follow the instructions so you shouldn't have any issues.
