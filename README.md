# Dotfiles Neovim

Dotfiles for my Neovim config. Mostly based on `ThePrimeagen` intro Video for Neovim which can be found [here]('https://youtube.com/watch?v=w7i4amO_zaE').

## Needed Packages
* ripgrep package for grep string search instally by running `sudo pacman -S ripgrep`
* Make sure npm is properly installed

## Install Packer
First of all make sure packer is installed by executing the following command:
```bash
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

## Installing Packages
* Go into the `packer.lua` File
* Type `:so`
* Type `:PackerSync`
