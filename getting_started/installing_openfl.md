# Installing OpenFL

## Haxe

First, you will need to install Haxe and Neko. OpenFL uses Haxe to power the build process, and Neko to run the command-line tools. Both are included in the following installers, one for each platform:

 * [Windows](http://haxe.org/website-content/downloads/3.2.1/downloads/haxe-3.2.1-win.exe)
 * [Mac](http://haxe.org/website-content/downloads/3.2.1/downloads/haxe-3.2.1-osx-installer.pkg)
 * [Linux](http://haxe.org/download/linux)

## OpenFL

With the latest versions of Haxe and Neko installed, open a command-prompt (Windows) or terminal (Mac/Linux) and run these commands:

    haxelib install openfl
    haxelib run openfl setup

To confirm that OpenFL is installed and working properly, try running the "openfl" command:

    openfl
