# My Tmux Configuration

This is my personal `tmux` configuration file designed for productivity, session persistence, and aesthetic customization using the [Catppuccin theme](https://github.com/catppuccin/tmux).

It includes useful plugins for session management and a beautiful status bar, all managed through TPM (Tmux Plugin Manager).

---

## Features

- **Session Persistence**: Automatically saves and restores your tmux environment.
- **Catppuccin Theme**: A modern, eye-friendly theme (using the "Frappe" variant).
- **Mouse Support**: Allows mouse interaction for pane switching and resizing.
- **Top Status Bar**: Displays useful information with customized styling.
- **Window Index Starts at 1**: Easier window tracking.
- **Custom Prefix Key (`Ctrl+Z`)**: Faster access to tmux commands.
- **Plugin Manager (TPM)**: Simple and clean way to manage tmux plugins.

---

## Plugins Used

| Plugin                               | Description                                                                 |
|--------------------------------------|-----------------------------------------------------------------------------|
| [`tmux-plugins/tpm`](https://github.com/tmux-plugins/tpm)                | Plugin manager for tmux                                                     |
| [`tmux-plugins/tmux-resurrect`](https://github.com/tmux-plugins/tmux-resurrect) | Save and restore tmux sessions                                              |
| [`tmux-plugins/tmux-continuum`](https://github.com/tmux-plugins/tmux-continuum) | Automatically save/restore tmux environment periodically                    |
| [`catppuccin/tmux`](https://github.com/catppuccin/tmux)                  | Beautiful and customizable tmux theme                                       |

---

## Installation

### 1. Install Tmux

Make sure tmux is installed. You can install it using your system package manager:

```bash
# MacOS
brew install tmux

# Arch
sudo pacman -S tmux
```

### Clone TPM
```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

### Copy the conf file
Place the provied `.tmux.conf` in your home dir:
```bash
cp tmux.conf ~/.tmux.conf
```
