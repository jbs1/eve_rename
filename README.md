# EVE rename

helper to rename bookmarks to EUni's format

Does not work for wormholes because the program can't know where you are in the chain and also not for combat sig's, because who needs that in W-space.

## 2 Versions
#### "Ban-save" version:
This version __does not do__ the <kbd>Ctrl</kbd>+<kbd>C</kbd> and <kbd>Ctrl</kbd>+<kbd>V</kbd> for you because that may or may not be illegal according to CCP's rules.

[save version](https://github.com/jbs1/eve_rename/raw/master/eve_rename_save.exe)

###### How it works:
* Start the program.
* Rightclick->_Save Location_... on the scanned signature in the probe window.
* Press <kbd>Ctrl</kbd>+<kbd>C</kbd>
* BM will be processed.
* Press <kbd>Ctrl</kbd>+<kbd>V</kbd>
* Click _Submit_.
* After the specified delay, you clipboard will be reformatted again to have a String that can be pasted into mapper.
* If enabled, it will give you an audio cue, when the mapper-compatible string is ready.



#### Maybe, Probably "Ban-save" version:
This version __does do__ <kbd>Ctrl</kbd>+<kbd>C</kbd> and <kbd>Ctrl</kbd>+<kbd>V</kbd> for you but that may or may not be illegal according to CCP's rules, so use at your own risk.

[maybe save version](https://github.com/jbs1/eve_rename/raw/master/eve_rename.exe)

###### How it works:
* Start the program.
* Chose a hotkey. Default is _#_.
* Rightclick->_Save Location_... on the scanned signature in the probe window.
* Press chosen hotkey.
* BM name is now properly formatted.
* Click _Submit_.
* It will keep a mapper-compatible string in the clipboard to easily be pasted to mapper.

![How_it_works_gif](https://i.imgur.com/QZMdmUa.gif)
