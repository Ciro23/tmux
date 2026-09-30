# tmux config

Personal tmux configuration using [TPM](https://github.com/tmux-plugins/tpm) with
tmux-resurrect and tmux-continuum.

## Requirements

- tmux >= 3.1 (reads `~/.config/tmux/tmux.conf`)
- git

## Install

```sh
git clone https://github.com/Ciro23/tmux ~/.config/tmux
tmux
```

On first start TPM is cloned and all plugins are installed automatically.
To install manually, press `prefix + I` inside of `tmux`.

## Usage

- `prefix + I` — install plugins listed in `tmux.conf`
- `prefix + U` — update plugins
- `prefix + alt + u` — remove plugins no longer listed

## Machine-specific settings

Put per-machine tweaks in `~/.config/tmux/local.conf`. It is sourced if it
exists and is ignored by git.
