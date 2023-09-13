# keynav.av
AV's personal [configuration file](https://github.com/Vazirified/keynav.av/blob/main/configuration-rc/keynav.av) for _keynav_.

---

The _keynav_ application software is an excellent piece of code living at [Jordan Sissel's keynav repository on GitHub](https://github.com/jordansissel/keynav). The purpose of this software application which works on nearly all Linux distributions running X11 is to use the keyboard for whatever the mouse does. I strongly encourage you to take a look at the [project website](https://www.semicomplete.com/projects/keynav/) or the project repository on [GitHub](https://github.com/jordansissel/keynav) and give it a try if you are not already using it! You can find the usage and configuration instructions in the well-written [documentation](https://github.com/jordansissel/keynav/blob/master/keynav.pod). The documentation is especially important to understand how to address your configuration file and set up the application for use. You can also find the [copyright notice](https://github.com/jordansissel/keynav/blob/master/COPYRIGHT) in the GitHub repository.

After about two years of being an avid user of _keynav_, I have changed the configuration to meet my needs and I am publishing my [configuration (as keynav.av located in configuration-rc directory)](https://github.com/Vazirified/keynav.av/blob/main/configuration-rc/keynav.av) here in this repository, so that others with the same taste and workflow as myself may be able to pick up to the speed easier and faster.

This configuration file is also compatible with [_keynavish_ by Les De Ridder](https://github.com/lesderid/keynavish) which is a rewrite of keynav for MS-Windows.

---

The configuration file "keynav.av" is self-explanatory, but as a short, more human-readable introduction to the way keynav will work after being configured with it, please read on...

## Home row functionality:

I have not changed much about the main usage form from the home row, only keybindings for moving the grid have changed a bit and I have used the IJKL approach instead of HJKL binding which is more familiar for VIM users:
- "__Ctrl + ;__" starts the 4x4 grid.
- "__i__" cuts the grid up.
- "__k__" cuts the grid down.
- "__j__" cuts the grid left.
- "__l__" cuts the grid right.
- "__u__" cuts up and left.
- "__o__" cuts up and right.
- "__m__" cuts down and left.
- "__.__" cuts down and right.
- "__Tab__" restarts.
- "__Escape__" or "__Ctrl + \[__" exits.
- "__Space__" left-clicks and ends.
- "__;__" moves the pointer to the centre of the grid and exits.
- "__a__" left-clicks the centre of the grid.
- "__s__" middle-clicks the centre of the grid.
- "__d__" right-clicks the centre of the grid.
- "__f__" scrolls up on the centre of the grid.
- "__v__" scrolls down on the centre of the grid.
- "__Alt + j__" moves the grid to the left.
- "__Alt + k__" moves the grid down.
- "__Alt + i__" moves the grid up.
- "__Alt + l__" moves the grid to the right.
- "__Alt + u__" moves left and up.
- "__Alt + o__" move right and up.
- "__Alt + m__" moves left and down.
- "__Alt + .__" moves right and down.

## Numeric keypad functionality:

Please note that "KP" stands for KeyPad in this guide and for example "KP0" means the zero key on the numeric keypad.
- "__Ctrl + KP0__" starts a 3x3 grid.
- "__KP1__" selects the lower left cell and divides it into a new 3x3.
- "__KP2__" selects the lower centre cell and divides it into a new 3x3.
- "__KP3__" selects the lower right cell and divides it into a new 3x3.
- "__KP4__" selects the middle left cell and divides it into a new 3x3.
- "__KP5__" selects the middle centre cell and divides it into a new 3x3.
- "__KP6__" selects the middle right cell and divides it into a new 3x3.
- "__KP7__" selects the upper left cell and divides it into a new 3x3.
- "__KP8__" selects the upper centre cell and divides it into a new 3x3.
- "__KP9__" selects the upper right cell and divides it into a new 3x3.
- "__KP-Enter__" left-clicks on the centre of the grid and exits.
- "__KP+__" double clicks on the centre of the grid and exits.
- "__KP.__" drags from the centre of the grid (clicks and holds) but may not work on some platforms.
- "__KP/__" left-clicks on the centre of the grid.
- "__KP*__" middle-clicks on the centre of the grid.
- "__KP-__" right-clicks on the centre of the grid.

## Miscellaneous functionalities:

When the grid is activated,
- "__w__" takes the grid to the active window.
- "__c__" takes the grid to a 100px * 100px area, centered on the pointer location.
- "__Ctrl+h__" cuts the grid to the left.
- "__Ctrl+j__" cuts down the grid.
- "__Ctrl+k__" cuts up the grid.
- "__Ctrl+l__" cuts the grid to the right.
- "__Ctrl+y__" cuts the grid left and up.
- "__Ctrl+u__" cuts the grid right and up.
- "__Ctrl+b__" cuts the grid left and down.
- "__Ctrl+n__" cuts the grid right and down.

---

Please note that I do not use capital letters for my keybindings. You may find _keynav_ unresponsive if you use it with CapsLock on or holding the Shift key, which may seem to be obvious but can easiy be forgotten!
