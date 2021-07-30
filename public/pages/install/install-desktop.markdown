---
layout: page
title: Desktop application install
parent: Install
permalink: /install-desktop/
nav_order: 3
---

## [OWASP](https://www.owasp.org) Threat Dragon

[Threat Dragon](http://owasp.org/www-project-threat-dragon) comes in two variants, 
desktop application and web application.

## Desktop application install instructions
Installable versions are available for download from the [OWASP GitHub area](https://github.com/OWASP/threat-dragon/releases):

* Windows (64 bit) installer
* MacOS installer
* Linux snap, AppImage, debian and rpm installers

### Linux installer and AppImage
Packages for both Debian and Fedora Linux on AMD64 and X86-64bit platforms can be downloaded from the
[releases folder](https://github.com/OWASP/threat-dragon/releases/).
Alternatively a platform independent snap installer can be downloaded, or use the AppImage provided.

### MacOS installer
Download the .dmg MacOS installer from the
[releases folder](https://github.com/OWASP/threat-dragon-desktop/releases/).
Open the download and drag 'OWASP Threat  Dragon' to the application directory. When the copy has
finished then Threat  Dragon can be run from launchpad or Finder -> Applications.

If an error message pops up when running for the first time, along the lines of 
_'“OWASP-Threat-Dragon” can’t be opened because Apple cannot check it for malicious software'_
then follow [this FAQ](https://github.com/OWASP/threat-dragon/wiki/FAQs#why-do-i-get-apple-cannot-check-it-for-malicious-software-errors-after-installing-on-macos)
to resolve this.

There may be different error messages for older versions of Threat Dragon,
in which case try [this FAQ](https://github.com/OWASP/threat-dragon/wiki/FAQs#why-do-i-get-developer-can-not-be-verified-errors-after-installing-on-macos). 

### Windows installer
Download the Windows .exe installer from the
[releases folder](https://github.com/OWASP/threat-dragon/releases/).
Run the installer and invoke the application from the shortcut.
The current versions of the desktop application are not code-signed, so you may get a warning when installing.

### Command line using npm

For the latest versions of code between releases, `npm` can be used to install
and run Threat Dragon Desktop locally:

```
git clone https://github.com/owasp/threat-dragon
cd threat-dragon/td.desktop
npm install
npm run build
```

Then to run it:

`npm start`

There is a command line interface, run help to see what commands are available:

`npm run help`

For example to export a given threat model file to pdf :

`npm run pdf ./threat-model.json`
