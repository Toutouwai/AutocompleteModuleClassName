# Autocomplete Module Class Name

A module for ProcessWire CMS/CMF. Provides class name autocomplete suggestions for the "Add Module From Directory" field at Modules > New.

Requires ProcessWire >= v3.0.16.

## Screencast

![Screencast](https://user-images.githubusercontent.com/1538852/60233595-10562000-98f5-11e9-9888-90421a99e21c.gif)

## Installation

[Install](http://modules.processwire.com/install-uninstall/) the Autocomplete Module Class Name module.

## Configuration

* Choose the type of autocomplete options list: "Module class names from directory" or "Custom list of module class names". The latter could be useful if you regularly install some modules and would prefer a shorter list of autocomplete suggestions.
* The list of class names in the modules directory is generated when the Autocomplete Module Class Name module is installed. It doesn't update automatically (because the retrieval of the class names is quite slow), but you can use the button underneath when you want to retrieve an updated list of class names from the directory.
* The "fuzzy search" option uses custom `filter` and `item` functions for Awesomplete so that the characters you type just have to exist in the module class name and occur after preceding matches but do not need to be contiguous. Uncheck this option if you prefer the standard Awesomplete matching.
* Custom settings for Awesomplete can be entered in the "Awesomplete options" field if needed. See the [Awesomplete documentation](https://leaverou.github.io/awesomplete/) for more information.
