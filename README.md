# tse/shortcut #

A defined type to manage .lnk shortcuts on Windows.

Limitations:

* Can only manage .lnk, does not manage .url
* Doesn't seem to work when targeting folders

Example:

    shortcut { 'C:/myshortcut.lnk':
      target => 'C:/Windows/system32/cmd.exe',
    }

Parameters:

* target
* path
* arguments
* icon\_location
* working\_directory
* description
