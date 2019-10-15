# baRcodeR 0.1.3

Bugs and Improvements:

- major bug fix for linear barcodes that occasionally created unscannable barcodes.
- added documentation on how to create alternative formatting of labels (e.g. spaces, line breaks)
- added padding for labels which were single character or blank
- 2-page cheatsheet now available as addin 

# baRcodeR 0.1.2

New Feature:

- In response to a user request, there is now an option to print linear (code 128 set B) barcodes. 

# baRcodeR 0.1.1

Bugs and Improvements: 

- create_PDF() function will replace all underscores in text with dashes. Underscores are not specified in the encoding dictionary of `qcrode` and will throw errors.
- x_space and y_space parameters are now limited between 0 and 1 for easier use. These parameters are used to position text on the printed labels.
- Font size is no longer limited and is now measured as points. Font size is automatically reduced if text code is too long for the printed labels.

New Features:

- label_width and label_height parameters specify the width and height of the label to enable alleys (i.e. gaps) between physical labels.


-----------------


# baRcodeR 0.1.0

This is the first official release of the package.