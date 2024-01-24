# Configuring TMUX

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
