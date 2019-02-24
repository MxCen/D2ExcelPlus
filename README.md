# D2Excel Plus 0.91
(C) 2019 Cjreek

An editor to edit diablo 2 textfiles.

### Features:
- Open a whole folder (workspace) with all your .txt files for easy access
- Drag&Drop files into the program to load them
- Edit multiple files at once (tabbed layout)
- Undo/Redo
- Multiselect/Multiedit
- Search functionality
- Fix the first X columns to keep track of the current row when scrolling to the right
- Alternating row colors for readability
- delete/append/insert and copy rows
- Handy shortcuts for editing:

    | Shortcut  | Functionality |
    | ----- | ---- |
    | Escape  | Cancel changes while editing a cell |
    | Delete  | Empty cell |
    | Ctrl + Delete  | Delete selected row |
    | Ctrl + +  | Increment cell value by 1 |
    | Ctrl + -  | Decrement cell value by 1 |
    | Ctrl + C  | Copy cell contents to clipboard |
    | Ctrl + X  | Copy cell contents to clipboard and empty selected cell (cut) |
    | Ctrl + V  | Paste clipboard to selected cell |
    | Ctrl + Z  | Undo |
    | Ctrl + Y  | Redo |
    | Shift + Mousewheel  | Scroll horizontally |
	
### Files
D2Excel Plus saves some settings in the following files:
```sh
%appdata%\D2ExcelPlus\settings.ini
```
%appdata% (usually) refers to the following path:
```sh
C:\Users\<Username>\AppData\Roaming
```
	
### Changes
##### 0.91
* [FEATURE] Added undo/redo functionality
* [FEATURE] Added multiselect of cells supporting copy&paste and other operations on cells
* [FIX] Fixed a bug causing files to be saved in an invalid way, causing the game to crash - resaving with the current version should fix those files.
##### 0.9a
* [FIX] Grid contents now update continuously while scrolling
##### 0.9
* Initial Release
