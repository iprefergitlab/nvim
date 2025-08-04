# Rust-only Neovim Configuration

This is a focused Neovim configuration optimized specifically for Rust development.

## System Requirements

### Rust (Rustup)  
Install Rust via Rustup:  
https://rustup.rs/

### Node.js  
Required for coc.nvim functionality:  
https://nodejs.org/en/download

### Neovim (version 0.5 or higher)  
Install Neovim:  
```bash
sudo apt install neovim -y
```

### Python 3  
Required for pynvim, which supports plugins integration in Neovim:  
https://www.python.org/downloads/

### pynvim  
Python client for Neovim:  
```bash
pip3 install pynvim
```

### ripgrep  
Fast search tool, used by various plugins:  
```bash
sudo apt install ripgrep -y
```

### fd  
Modern alternative to `find`, used by plugins like Telescope:  
```bash
sudo apt install fd-find -y
```

### Nerd Font  
For rich icons in statuslines and file explorers:  
https://www.nerdfonts.com/

### xclip  
Clipboard support on Linux (X11):  
```bash
sudo apt-get install -y xclip
```

## Installation

1. Clone this repository into the `~/.config/` directory:

2. Open Neovim and install plugins:
```vim
:PlugInstall
```