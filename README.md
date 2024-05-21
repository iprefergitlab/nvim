# This is a C / C++ / Rust Neovim config.

## System Requirements

### Clang

``sudo apt install clang
``
> See the version of clang
``clang --version
``

### Clang-format

``sudo apt install clang-format-x
``
> Replace "x" by the version of clang

> Create a link to clang-format
``sudo ln -s /usr/bin/clang-format-x /usr/bin/clang-format
``

### Clangd
``sudo apt install clangd-x
``
> Replace "x" by the version of clang

> Create a link to clang-format
``sudo ln -s /usr/bin/clangd-x /usr/bin/clangd
``

### Rust (Rustup)
``https://rustup.rs/
``

### NodeJs

``https://nodejs.org/en/download
``
### Python

``https://www.python.org/downloads/
``
### Neovim

``https://github.com/neovim/neovim/releases/tag/nightly
``

### Vim-Plug

``sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
``

### Pynvim

``pip3 install pynvim
``

### ripgrep

``sudo apt install ripgrep -y
``

### Fd

``sudo apt install fd-find -y
``
### Nerd Font

``https://www.nerdfonts.com/
``

## xclip

``sudo apt-get install -y xclip
``

### Clone this repo inside .config folder

### Open NeoVim

``:PlugInstall
``
