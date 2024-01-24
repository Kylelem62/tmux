# Configuring TMUX

Before going any further, make sure that `XDG_CONFIG_HOME` is set to `~/.config` in your shell's configuration file. This is the default value for most shells, but it's worth checking. If not, you'll be polluting your home directory. You can easily ensure this is set by adding `export XDG_CONFIG_HOME=$HOME/.config` in your `~/.bashrc` file.


## Installation

Install tmux on Arch Linux:

```bash
sudo pacman -S tmux
```
### Tmux Plugin Manager

On any system with git and tmux 

```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm/
```

## Installation Issues/tips

### Missing fonts for catppuccin theme

Install the following font group:

```bash
sudo pacman -S nerd-fonts
```

### Reloading tmux plugins

From tmux, press `prefix` + <kbd>I</kbd> (capital I, as in **I**nstall) to fetch the plugin.
