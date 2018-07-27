# Personal Laptop Installation

- Co-founder and Business Application Developer at [CivilCode Inc.](http://www.civilcode.io)
- Follow me on [Twitter](http://www.twitter.com/nicholasjhenry)
- Connect via [LinkedIn](http://ca.linkedin.com/in/nicholasjhenry)

## Pre-installation setup:

Before running CivilCode's [laptop](https://github.com/civilcode/laptop):

    cd ~/Development
    git clone https://github.com/nicholasjhenry/laptop.git laptop.local
    ln -s ~/Development/laptop.local/mac ~/.laptop.local

## Post-installation setup:

### Dotfiles

- see https://github.com/nicholasjhenry/dotfiles

### Vim

- install fonts in ./fonts
- under vim execute `PlugInstall`

### iTerm

- see the default profile to use `Solarized Light` (Colors -> Color presets)
- set as default

### 1Password

- open 1Password
- setup via iCloud

### GPG

- assuming `brew cask install gpg-suite`
- import sec/pub file from 1Password

### Git

- copy `gitconfig` from 1Password to `~/Development/dotfiles-secret/.`

### Source Tree

- `mkdir ~/Development/bin && ln -s /usr/local/MacGPG2/bin ~/Development/bin/MacGPG2`
- Advanced -> `~/Development/bin/MacGPG2`
- General -> Fullname / Email

You're good to go!
