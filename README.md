# Laptop

- Follow me on [Twitter](http://www.twitter.com/nicholasjhenry)
- Connect via [LinkedIn](http://ca.linkedin.com/in/nicholasjhenry)

Laptop is a script to set up an macOS laptop for web development.

It can be run multiple times on the same machine safely. It installs, upgrades, or skips packages
based on what is already installed on the machine.

## Install:

    curl --remote-name https://raw.githubusercontent.com/nicholasjhenry/laptop/master/mac
    less mac
    sh mac 2>&1 | tee ~/laptop.log

## Post-installation laptop setup

### 1Password

- open 1Password and sign-in with credentials
- setup with CLI (step 2): https://developer.1password.com/docs/cli/get-started

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

- install plugins: `prefix (Ctrl-x) + I`
- FYI: https://github.com/tmux-plugins/tpm#installing-plugins

You're good to go!
