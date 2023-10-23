# Personal Laptop Installation

- Co-founder and Business Application Developer at [CivilCode Inc.](http://www.civilcode.io)
- Follow me on [Twitter](http://www.twitter.com/nicholasjhenry)
- Connect via [LinkedIn](http://ca.linkedin.com/in/nicholasjhenry)

## Pre-installation setup:

Before running CivilCode's [laptop](https://github.com/civilcode/laptop):

    cd ~/Development
    git clone https://github.com/nicholasjhenry/laptop.git laptop.local
    ln -s ~/Development/laptop.local/mac ~/.laptop.local

## Post-installation laptop setup

### 1Password

- open 1Password and sign-in with credentials

### iTerm

- see the default profile to use `Solarized Light` (Colors -> Color presets)
- set text: `Fira Mono for Powerline` (Profile > Text > Font)
- set as default

### VSCode

- sign-in and sync settings with GitHub credentials

### Source Tree

- Advanced -> `~/Development/bin/MacGPG2`
- General -> Fullname / Email

### GPG

- assuming `brew cask install gpg-suite-no-mail`
- import sec/pub file from 1Password

### Dotfiles

- see https://github.com/nicholasjhenry/dotfiles

### Git

- copy `gitconfig` from 1Password to `~/Development/dotfiles-secret/.`

### Tmux

- install plugins (prefix + I)
- https://github.com/tmux-plugins/tpm#installing-plugins

You're good to go!
