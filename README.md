# vang dotfiles

## Setup

```sh
git clone https://github.com/venusang/dotfiles.git ~/.dotfiles
cd ~/.dotfiles

brew bundle

# Setup dotfiles. Use --no for no action
stow git jrnl ruby tmux vim zsh --verbose

# run install script to install oh-my-zsh & vundle/vim plugins
scripts/install
```

This will symlink the appropriate files in `.dotfiles` to your home
directory.

Everything is configured and tweaked within `~/.dotfiles`.

## External Programs

* [GNU Stow](https://www.gnu.org/software/stow/)
* [Jrnl](https://maebert.github.io/jrnl/)
