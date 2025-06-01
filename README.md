# Neovim Configuration for C/C++, Rust and Solidity:

## System Requirements

### Clang

```bash
sudo apt install clang
```
_Check your Clang version:_
```bash
clang --version
```

### Clang-format

_Replace `x` with your Clang version:_
```bash
sudo apt install clang-format-x
sudo ln -s /usr/bin/clang-format-x /usr/bin/clang-format
```

### Clangd

_Replace `x` with your Clang version:_
```bash
sudo apt install clangd-x
sudo ln -s /usr/bin/clangd-x /usr/bin/clangd
```

### Rust (Rustup)

Install Rust using Rustup:  
[https://rustup.rs/](https://rustup.rs/)

### Node.js

Download and install Node.js:  
[https://nodejs.org/en/download](https://nodejs.org/en/download)

### Python

Download and install Python:  
[https://www.python.org/downloads/](https://www.python.org/downloads/)

### Neovim

```bash
sudo apt install neovim -y
```

### Pynvim

```bash
pip3 install pynvim
```

### ripgrep

```bash
sudo apt install ripgrep -y
```

### fd

```bash
sudo apt install fd-find -y
```

### Nerd Font

Download and install a Nerd Font for better icon support:  
[https://www.nerdfonts.com/](https://www.nerdfonts.com/)

### xclip

```bash
sudo apt-get install -y xclip
```

## Setup Instructions

1. **Clone this repository** inside your `~/.config` folder.

2. **Open Neovim**:
   ```bash
   nvim
   ```

3. **Run**:

```vim
:CocInstall @nomicfoundation/coc-solidity
:CocInstall coc-prettier
```

To set the Solidity compiler version (if necessary), run this in your terminal:

```bash
solc-select use <version - ex: 0.8.24> --always-install
```

4. **Install the plugins** by running:
   ```vim
   :PlugInstall
   ```
