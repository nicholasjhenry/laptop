# Laptop

- Follow me on [Twitter](http://www.twitter.com/nicholasjhenry)
- Connect via [LinkedIn](http://ca.linkedin.com/in/nicholasjhenry)

Laptop is a script to set up a macOS laptop for software development.

It can be run multiple times on the same machine safely. It installs, upgrades, or skips packages
based on what is already installed on the machine.

## Install

    curl --remote-name https://raw.githubusercontent.com/nicholasjhenry/laptop/master/mac
    less mac
    sh mac 2>&1 | tee ~/laptop.log
    
## Slim Install

Skip the bundle of optional desktop apps (1Password, Slack, Zoom, Sourcetree, browsers, fonts-adjacent
utilities, etc.) and install only the core CLI tooling:

    LAPTOP_SLIM=true sh mac 2>&1 | tee ~/laptop.log

## Post-installation laptop setup

### 1Password

- open 1Password and sign-in with credentials
- follow the CLI setup instructions: https://developer.1password.com/docs/cli/get-started

### iTerm2

- see the default profile to use `Solarized Light` (Colors -> Color presets)
- set text: `FiraCode Nerd Font Mono` (Profile > Text > Font)
- set as default

### VSCode

- sign-in and sync settings with GitHub credentials

### Sourcetree

- General -> Fullname / Email

### GPG

- installed via the `mac` script's Brewfile
- import sec/pub file from 1Password

### Dotfiles

- prerequisite: 1Password (see above)
- see https://github.com/nicholasjhenry/dotfiles

### Git

- copy `gitconfig` from 1Password to `~/Workspaces/dotfiles-secret/.`

### Tmux

- install plugins: `prefix (Ctrl-x) + I`
- FYI: https://github.com/tmux-plugins/tpm#installing-plugins

You're good to go!
