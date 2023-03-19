# dotfiles

Repo for my dotfiles. Trying to use only shell scripts and no other tools.

The shell assumes `bash` exists.

## Usage

Put the repo at `~/.dotfiles`, either by cloning or copying the files.

### Install apps

```bash
~/.dotfiles/main set zsh [other apps]
```

In most cases, config files will be overwritten by symlinks to the repo.

Setting `zsh` will install `zsh` and `oh-my-zsh` and set it as the default shell.
This will also add an alias `dotfiles=$HOME/.dotfiles/main` to the shell.

### Add commands

```bash
dotfiles set_cmd proxy [commands]
```
