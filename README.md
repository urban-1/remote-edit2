# remote-edit-ni for atom.io

`master`: [![Build Status](https://travis-ci.org/newinnovations/remote-edit-ni.svg?branch=master)](https://travis-ci.org/newinnovations/remote-edit-ni) - `devel`: [![Build Status](https://travis-ci.org/newinnovations/remote-edit-ni.svg?branch=devel)](https://travis-ci.org/newinnovations/remote-edit-ni)

This branch is an attempt at integrating the work of @urban-1 and @newinnovations.

## TODO

* Serious testing
* Create a proper README
* Check keybindings. They are now in the <kbd>Alt+r</kbd> range
* Keyboard support in files-view, eg:
  * focus when opening files
  * up/down to select files
  * enter to open or enter directory
  * backspace to parent directory
  * escape to close files-view
  * mouse: single click selects file/dir
  * mouse: double click opens file/dir

## Main keyboard shortcuts

- <kbd>Alt+r b</kbd> -
Select remote host and start browsing in / or last directory (when selected in preferences).

- <kbd>Alt+r m</kbd> -
Browse remote host in directory of the current editor tab.

-   <kbd>Alt+r v</kbd> -
Show/hide remote-edit panel

- <kbd>Alt+r o</kbd> -
Show open (downloaded) remote files.

### shortcuts within _host selection_ dialog

- <kbd>Shift+a</kbd> or <kbd>Shift+s</kbd> -
Add sftp host.

- <kbd>Shift+f</kbd> -
Add ftp host.

- <kbd>Shift+e</kbd> -
Edit hosts.

- <kbd>Shift+d</kbd> -
Delete hosts or downloaded files. Usable when selecting hosts (_Browse_) or open files (_Show open remote files_).

## Credits
This is a fork of a project created by Sverre Aleksandersen (sveale). It was
created to integrate bug fixes and new features. The original project can be found at https://github.com/sveale/remote-edit
