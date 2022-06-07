# d-is-for-delete
vim- easy mapping to make 'd' delete (not cut), and 'leader d' cut.

Installation
============

There are 2 flavors to use this key mapping, either with a shared clipboard configuration or using the default unnamed register (.i.e '"' register).

1)Shared Clipboard:
-----------------

curl -sS https://raw.githubusercontent.com/pazams/d-is-for-delete/master/d-is-for-delete-shared-clipboard >> ~/.vimrc 

2)Default Register:
-----------------

curl -sS https://raw.githubusercontent.com/pazams/d-is-for-delete/master/d-is-for-delete-unnamed-register >> ~/.vimrc


VS code
============

To configure VS code Vim Emulator (VSCodeVim), see suggested settings at https://github.com/pazams/d-is-for-delete/blob/master/vscode.settings.json


Notes
=====

It is a nice practice to have the "leader" key set to comma, e.g:

let mapleader = ","

let g:mapleader = ","

This will make ",d" be your new cut command. 
