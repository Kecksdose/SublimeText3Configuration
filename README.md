# Sublime Text 3 Configuration

As a semi-professional programmer, Sublime Text (ST) became my favourite text editor while programming Python and C++ code. Even though it comes with many cool features, you can install some packages to improve your coding comfort _even more_.

This ST3 configuration in based on a [blog entry](https://dbader.org/blog/setting-up-sublime-text-for-python-development) from Daniel Bader. I tested this setup using the most recent build of ST3, which is 3083. Although it is still in beta status, many small improvements were added in contrast to ST2. You can [download](http://www.sublimetext.com/3) ST3 for free. It works on many different operation systems like OS X, Windows and Ubuntu (I am using OS X El Capitan (10.11) right now). Here we go!

### Main Packages (You don't want to live without them):
- [Package Control](https://packagecontrol.io/installation)
    - This one is the most fundamental package in ST3. It manages all the installations of the following packages. After its own installation (which you have to do via command line), just hit `cmd`+`shift`+`p` and type `installation`. After confirming with `enter`, one can see a list of all packages available for ST3. Search for the name, hit `enter` again - and you are done!
- [SideBarEnhancements](https://github.com/titoBouzout/SideBarEnhancements)
    - Unfortunately, opening/renaming/moving files inside of ST3 if quite nasty. This package takes care to all of these operations, integrated perfectly in the ST3 UI.
- [All Autocomplete](https://github.com/alienhard/SublimeAllAutocomplete)
    - Innately, ST3 knows about all the variables/classes/functions you declared and supports autocomplete for all of them - if the are defined in the current file. With All Autocomplete ST3 searches not only in this one file, but all files you store in the current ST project.
- [SublimeCodeIntel](https://github.com/Kronuz/SublimeCodeIntel)
    - While All Autocomplete is only looking for words, SublimeCodeIntel understands the code structure of many programming languages (like Python and JavaScript) and navigates you directly to the declaration of some variable or function. 

### Themes
- [Soda Reloaded](https://packagecontrol.io/packages/Theme%20-%20SoDaReloaded)
   - 

### Color Themes:
- [Tomorrow Color Schemes](https://github.com/theymaybecoders/sublime-tomorrow-theme)

### Git:
- [GitGutter](https://github.com/jisaacks/GitGutter)

### Python:
- [Python Flake8 Lint](https://github.com/dreadatour/Flake8Lint)

### Just for fun:
- [SublimeREPL](https://github.com/wuub/SublimeREPL), python shell IN sublime!
