# Gravity Forms Ready Class Selector

A fork of the outdated Ready Class Selector Plugin for Gravity Forms on WordPress.

*Original Plugin: [https://wordpress.org/plugins/gravity-forms-css-ready-selector/](https://wordpress.org/plugins/gravity-forms-css-ready-selector/)*

"Ready Classes" were introduced in Gravity Forms 1.5. Using these new classes, you can easily create more advanced alternative layouts for the fields in your forms. Excellent idea, however, the problem is you always need to remember what the exact class name is. Now with the CSS Ready class selector, you don't need to remember. Simply click on a button to lauch the popup and choose the class you want to add from the list.

# Features

* Convenient button added under the advanced tab next to the "CSS Class Name" field
* Clean and simple popup that lists all the "Ready Classes"
* Add more than one "Ready Class"
* Double click a "Ready Class" to add it and auto-close the popup

# Requirements

* WordPress 3.6
* Gravity Forms 1.5

# Tested With

* WordPress 4.6.1
* Gravity Forms 2.1.1
* PHP 5.6.28
* MySQL 5.5.50

# Changelog

#### Version 2.1:
* Forked by Mike Kormendy
* Removes extraneous instantiation ('gform\_editor\_js' action hook already takes care of only loading this addon where appropriate – hint: only the gform editor page)
* Cleans up styles to be consistent with Gravity Forms admin styles
* Reformats style indenting (compressing the style code here makes it hard to read and has no extreme benefit)
* Removes accordion collapsing of options (reducing the amount of steps to perform task)

#### Version 2.0:
* Ported to GitHub Repo by Bryan Willis ([https://github.com/bryanwillis/gravityforms-ready-class-selector-revised](https://github.com/bryanwillis/gravityforms-ready-class-selector-revised))
* Fixes errors created by the plugin.
* Removes a lot of unneeded code.

#### Version 1.1:
* Fixed bug where classes were not being updated.

#### Version 1.0:
* Initial Release. First version.



