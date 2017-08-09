dotfiles
========

Arch Linux with i3 WM config

 Forked from https://github.com/mohlerm/
Vim files are hosted in a separate repository:
[github.com/mohlerm/vimfiles](https://github.com/mohlerm/vimfiles)

# i3 Configuration

## Requirements
### general
* arch linux - basic system
* i3 - window manager
* i3status - status bar
* dunst - notifications
* rofi - Super-P launcher
* feh - setting background
* pavucontrol - sound
* scrot - screenshots
* libnotify - notifications
* ttf-font-icons - icons for statusbar

### recommended
* vim - code/text editor
* sublime - text editor
* firefox - browser
* thunderbird - mail client
* URXVT - terminal emulator

##Basic Bindings
* Super - Standard modifier
* Super+Enter - open terminal
* Super+Shift+Enter - open nautilus
* Super+Backslash - open terminal interactively
* Super+q - kill focused window
* Super+d - program launcher (rofi)
* Super+Shift+d - ssh launcher (rofi)
* Super+{h,j,k,l} - focus left, down, up, right (vim based)
* Super+{v,g} - split vertical, horizontal 
* Super+f - fullscreen
* Super+s - stacking layout
* Super+w - tabbed layout
* Super+e - toggle splitted layout
* Super+Shift+Space - toggle floating mode
* Super+Space - toggle focus floating
* Super+a - focus parent container
* Super+F2 - Rename workspace (not recommended)
* Super+{1,2,3,4,5,6,7,8,9,0} - switch workspaces
* Super+Shift+{1,2,3,4,5,6,7,8,9,0} - move container to ws
* Super+o - move workspace to next output (e.g. displayport)
* Super+p - move window to displayport (for presentations)
* Super+Shift+c - reload i3 configuration
* Super+Shift+r - restart i3, used for upgrading
* Super+Shift+e - logs out of i3
* Super+r - switch to window resize mode
* Alt+Tab - focus right window
* Alt+Shift+Tab - focus left window
* Super+Tab - workspace "back-and-forth"
* Super+PageDown - focus next workspace 
* Super+PageUp - focus previous workspace
* Super+b - start firefox
* Print - make screenshots, see below for more information
* Super+Shift+Minus - move focused window to scratchpad
* Super+Minux - show scratchpad
* Super+F1 - start pulseaudio volume control
* Super+Escape - shutdown, reboot, lock interactively

Check out the .i3/config for more details.

##Workspace Layout
* 1: term: terminal
* 2: www: browser
* 3: three: coding
* 4: four: free
* 5: five: free
* 6: six: free
* 7: seven: steam
* 8: eight: free
* 9: DP: displayport (Super+p to move window here)
* 10: com: communication

##Scrot Screenshots
* Print - make screenshot in png format
* Shift+Print - make screenshot in jpg format
* Super+Print - make screenshot of current window in png format
* Super+Shift+Print - make screenshot of current window in jpg format
* add CTRL key - delay screenshot for 5 seconds
