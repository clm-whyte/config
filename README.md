# Config
## Prerequisites
### Git 
#### MacOS
`brew install git`
#### Fedora
`sudo dnf install git`

### Tmux
#### MacOS
`brew install tmux`
#### Fedora
`sudo dnf install tmux`

### Tmux Package Manager
`git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm`

### Alacritty
#### MacOS
`brew install alacritty`
#### Fedora
`sudo dnf install alacritty`

### Neovim
#### MacOS
`brew install neovim`
#### Fedora
`sudo dnf install neovim`

### NvChad
#### MacOS

### NerdFonts
#### MacOS
`brew tap homebrew/cask-fonts`
`brew install --cask font-jetbrains-mono`
#### Fedora
1. `sudo mkdir /usr/share/fonts/JetBrainsMono`
1. `sudo curl --fail --location --continue-at - https://github.com/ryanoasis/nerd-fonts/releases/download/v3.1.1/JetBrainsMono.zip --output ~/Downloads/JetBrainsMono.zip`
1. `sudo unzip ~/Downloads/JetBrainsMono.zip -d /usr/share/fonts/JetBrainsMono/`

or 

1. `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/JetBrains/JetBrainsMono/master/install_manual.sh)"`

### Node
####

## Commands
All `git` command prefixes should use the alias `config` instead of `git`.

For example, instead of:

`git status`, `git commit`, or `git push`

use:

`config status`, `config commit`, or `config push`

## Resources
- [DistroTube Guide to Dotfiles in Git Bare Repo](https://youtu.be/tBoLDpTWVOM?si=LXsgvM1a_a_HO99E)
- [Atlassian Guide to Dotfiles in Git Bare Repo](https://www.atlassian.com/git/tutorials/dotfiles)
