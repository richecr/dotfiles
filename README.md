# My Dotfiles

This is my dotfiles in arch linux with omarchy.
I'm using stow to configure.

## Move my dotfiles to system root

Inside the root of the repo

```sh
stow -t $HOME hypr
stow -t $HOME alacritty
...
stow -t $HOME zsh
```

## Move a configuration to dotfiles

Inside the root of the repo

```sh
mkdir hypr/.config # example
mv ~/.config/hypr hypr/.config
```
