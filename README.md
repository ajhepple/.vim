# .vim
My personal vim configuration.

## Requirements
This repository contains my preferred Vim plugins but not my `.vimrc` file.
Plugins are managed by [Pathogen](https://github.com/tpope/vim-pathogen)
but Pathogen is treated as a plugin itself for the purpose of this reposity,
therefore the `~/.vimrc` file requires the entries

    runtime bundle/vim-pathogen/autoload/pathogen.vim
    ...
    execute pathogen#infect()

See [Pathogen FAQs](https://github.com/tpope/vim-pathogen/blob/master/README.markdown#faq)
for more details.

A link that points `~/.vim` to the working copy of this repository.

## To install further plugins

    $ cd ~/workspace/.vim
    $ git submodule add https://github.com/user/plugin-name.git bundle/plugin-name
    $ git submodule init

## To update a plugin

    $ cd ~/.vim/bundle/plugin-name
    $ git pull
