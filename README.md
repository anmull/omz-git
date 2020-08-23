# Oh My Zsh Git Library

This is a copy of the [git library](https://github.com/ohmyzsh/ohmyzsh/blob/master/lib/git.zsh) for Oh My Zsh so it can be easily used outside of OMZ.

Note that this is a direct copy so it does not include defaults for the many variables referenced in the library.

# Installation

### Plugin Managers
```
# zgen
zgen load anmull/omz-git

# zplug
zplug anmull/omz-git

# antigen
antigen bundle anmull/omz-git
```

### Manual

```
git clone https://github.com/anmull/omz-git
source "omz-git/git.plugin.zsh"
```
