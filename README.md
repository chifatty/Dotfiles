# Dotfiles

## Installation

First, clone this repo onto your system:

    git clone https://github.com/chifatty/Dotfiles.git .dotfiles && cd .dotfiles
    git submodule init
    git submodule update
    chsh -s /bin/zsh

Then, you should create symlinks in your home directory to point to the actual dotfile files:

    ln -s `pwd`/vim/vimrc ~/.vimrc
    ln -s `pwd`/vim/vim ~/.vim
    ln -s `pwd`/git/gitconfig ~/.gitconfig
    ln -s `pwd`/git/gitignore ~/.gitignore
    ln -s `pwd`/screen/screenrc ~/.screenrc
	ln -s `pwd`/zsh/zshrc ~/.zshrc
    ln -s `pwd`/powerlevel9k `pwd`/oh-my-zsh/custom/themes/powerlevel9k 

## Environment

To have full features of those dotfiles, you need to install the following packages/softwares:

* git
* zsh


### Vim Plugins

* NeoBundle.vim: <https://github.com/Shougo/neobundle.vim>
* NeoComplCache: <https://github.com/Shougo/neocomplcache>
* vim-flake8: <https://github.com/nvie/vim-flake8>
