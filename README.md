# Chad's Suckless Terminal (st)

This is my own build of the [suckless terminal](https://st.suckless.org/).

## Pacthes included in this build

* alpha
* externalpipe
* font2
* scrollback
* vertcenter
* xresources

## Key Bindings

**Scrollback**
* `Alt-k` and `Alt-j`
* `Alt-u` and `Alt-d` : fast scrolling
* `Shift-PageUp` and `Shift-PageDown` : fast scrolling _(comes default with scrollback patch)_

**Zooming**
* `Ctrl-Shift-k` and `Ctrl-Shift-j`
* `Ctrl-Shift-u` and `Ctrl-Shift-d` : zoom faster
* `Ctrl-Shift-Home` : reset zoom

**Misc**
* `Ctrl-Shift-c` : copy
* `Ctrl-Shift-v` : paste
* `Alt-l` : select and open any url on display _(requirements: dmenu and a script from my dotfile...)_
* `Alt-y` : select and copy any url on display _(requirements: dmenu and a script from my dotfile...)_
* `Alt-e` : opens the screen in an editor specified in the $EDITOR environment variable.

## Requirements

* Composite Manager for transparancy (e.g. xcompmgr or compton)
* In order to build st you need the Xlib header files.
* libxft-bgra : if st crashes when trying to view some emojis or other unicode characters

## Installation
    git clone https://github.com/devpro101/st.git
    cd st
    sudo make clean install
