# Vim Setup 

Here we document how to set up the vim with all the good plugins that help make it a good editor in
general and execellent IDE. 

## Pathogen 
This is a vim plugin that manages our runtime path and is the first plugin to install for all
subsequent plugins. 
[Install Pathogen](https://github.com/tpope/vim-pathogen) 

## NERDTree 
plugin for file navigation of file system and makes working with code easy. Also creating and
closing files using NERDtree is eash using `m` and any one of `add, delete, print, move, copy or
list` the current node. 

[Install NERDTree](https://github.com/scrooloose/nerdtree#pathogenvim)


## CtrlP
plugin for fuzzy search which is very good for search files without the need for having a look at
the file on the left hand pane in NERDtree. 
[ctrlp.vim](https://github.com/ctrlpvim/ctrlp.vim) 

Steps are very simple 
* `$ cd ~/.vim` 
* `$ git clone https://github.com/ctrlpvim/ctrlp.vim.git bundle/ctrlp.vim`

add the following line in .vimrc

* `set runtimepath^=~/.vim/bundle/ctrlp.vim`

finally run the helptags to have a look at CtrlP help

* `:helptags ~/.vim/bundle/ctrlp.vim` - sets up the help tags
* `:help ctrlp.txt` 

## vim-go
pluign to allow use to prepare golang code, compile, test, build and run code.

[Install Vim-go](https://github.com/fatih/vim-go#install) 

