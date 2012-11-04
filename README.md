#Gmail Notifier (ignotifier)

###General information
To compile ignotifier project you need to have these softwares installed:
* [python](http://www.python.org/getit/)
* [nodejs](http://nodejs.org/)

Folders description:
* src: ignotifier source code
* compile: nodejs auto-compiler
* addon-sdk-*: latest version of [Mozilla addon-sdk](https://addons.mozilla.org/en-US/developers/builder)
* preview: screenshots
* template: bootstrap folder

###How to compile ignotifier
1. Open a new terminal in the root dir (directory contains src, addon-sdk-*, preview, and compile folders)
2. Run "node compile\install.js" to run cLinux in a new Firefox profile. To make xpi run "node compile\install.js --xpi"