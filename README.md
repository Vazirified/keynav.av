# keynav.av
AV's personal configuration for _keynav_.

---

The _keynav_ application software is an excellent piece of code living at [Jordan Sissel's keynav repository on GitHub](https://github.com/jordansissel/keynav). The purpose of this software application which works on nearly all Linux distributions running X11 is to use the keyboard for whatever the mouse does. I strongly encourage you to take a look at the [project website](https://www.semicomplete.com/projects/keynav/) or the project repository on [GitHub](https://github.com/jordansissel/keynav) and give it a try if you are not already using it! You can find the usage and configuration instructions in the well-written [documentation](https://github.com/jordansissel/keynav/blob/master/keynav.pod). The documentation is especially important to understand how to address your configuration file and set up the application for use. You can also find the [copyright notice](https://github.com/jordansissel/keynav/blob/master/COPYRIGHT) in the GitHub repository.

After about two years of being an avid user of _keynav_, I have changed the configuration to meet my needs and I am publishing my configuration here in this repository, so that others with the same taste and workflow as myself may be able to pick up to the speed easier and faster.

---

The configuration file "keynav.av" is self-explanatory, but as a short, more human-readable introduction to the way keynav will work after being configured with it, please read on...

## Home row functionality:

I have not changed much about the main usage form from the home row, only keybindings for moving the grid have changed a bit and I have used the IJKL approach instead of HJKL binding which is more familiar for VIM users:
- "Ctrl + ;" starts the 4x4 grid.
- "i" cuts the grid up.
- "k" cuts the grid down.
- "j" cuts the grid left.
- "l" cuts the grid right.
- "u" cuts up and left.
- "o" cuts up and right.
- "m" cuts down and left.
- "." cuts down and right.
- "Tab" restarts.
- "Escape" or "Ctrl + \[" exits.
- "Space" left-clicks and ends.
- ";" moves the pointer to the centre of the grid and exits.
- "a" left-clicks the centre of the grid.
- "s" middle-clicks the centre of the grid.
- "d" right-clicks the centre of the grid.
- "f" scrolls up on the centre of the grid.
- "v" scrolls down on the centre of the grid.
- "Alt + j" moves the grid to the left.
- "Alt + k" moves the grid down.
- "Alt + i" moves the grid up.
- "Alt + l" moves the grid to the right.
- "Alt + u" moves left and up.
- "Alt + o" move right and up.
- "Alt + m" moves left and down.
- "Alt + ." moves right and down.

## Numeric keypad functionality:

Please note that "KP" stands for KeyPad in this guide and for example "KP_0" means the zero key on the numeric keypad.
- "Ctrl + KP0" starts a 3x3 grid.
- "KP_1" selects the lower left cell and divides it into a new 3x3.
- "KP_2" selects the lower centre cell and divides it into a new 3x3.
- "KP_3" selects the lower right cell and divides it into a new 3x3.
- "KP_4" selects the middle left cell and divides it into a new 3x3.
- "KP_5" selects the middle centre cell and divides it into a new 3x3.
- "KP_6" selects the middle right cell and divides it into a new 3x3.
- "KP_7" selects the upper left cell and divides it into a new 3x3.
- "KP_8" selects the upper centre cell and divides it into a new 3x3.
- "KP_9" selects the upper right cell and divides it into a new 3x3.
- "KP_Enter" left-clicks on the centre of the grid and exits.
- "KP_+" double clicks on the centre of the grid and exits.
- "KP_." drags from the centre of the grid (clicks and holds) but may not work on some platforms.
- "KP_/" left-clicks on the centre of the grid.
- "KP_*" middle-clicks on the centre of the grid.
- "KP_-" right-clicks on the centre of the grid.

## Miscellaneous functionalities:

When the grid is activated,
- "w" takes the grid to the active window.
- "c" takes the grid to a 100px * 100px area, centered on the pointer location.
- "Ctrl+h" cuts the grid to the left.
- "Ctrl+j" cuts down the grid.
- "Ctrl+k" cuts up the grid.
- "Ctrl+l" cuts the grid to the right.
- "Ctrl+y" cuts the grid left and up.
- "Ctrl+u" cuts the grid right and up.
- "Ctrl+b" cuts the grid left and down.
- "Ctrl+n" cuts the grid right and down.
