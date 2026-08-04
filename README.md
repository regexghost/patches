# patches

Patches I have made for various other programs

Note: Doesn't include suckless programs as I have seperate repos for my builds of those

## Lemonbar-xft

https://github.com/silentz/lemonbar-xft

Adds font offset support per-font

Patch from https://github.com/drscream/lemonbar-xft slightly modified

## oksh

https://github.com/ibara/oksh

Case insensitive auto-complete, and removing certain commands from history file

New patch for adding ctrl-backspace and ctrl-delete to emacs mode (default mode)

## nano

https://www.nano-editor.org/

Added a new keybinding, `copysystem`, which copies marked/selected text to the system clipboard

## pipe-viewer

https://github.com/trizen/pipe-viewer

:copy=i command to copy links to clipboard

## less

https://github.com/gwsw/less

bsu and esu sync signals, not perfectly implemented but it works

## JWM

https://github.com/joewing/jwm

Swap order of window hiding/unhiding on desktop change, and don't use border colour for window background, reduces flicker without compositor

Disable caps lock line to fix a bug where keyboard shortcuts don't work if you have caps lock and escape swapped

Similar to dwm, don't map/unmap windows when changing desktop, just move off screen

Apply tiled to windows, only if centered not also specified. Allows me to use tiled for all windows except those in a centered group
