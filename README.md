# Dev Env Setup
just to list a list of software and deps that i use for work, gonna move this to ansible / nix in the future
currently it's from ubuntu, ansible and nix might have their own distributions

### Tools
- General
```bash
    sudo apt install git curl wget build-essential software-properties-common
```

- NodeJS
```bash
    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.1/install.sh | bash
    nvm install v20.15.1
```
- Rust Stuff (cargo etc)
```bash
    curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```


### ZSH
- from apt
```bash
    sudo apt install zsh
    # oh my zsh
    sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### Neovim
- from apt
```bash
    sudo apt install software-properties-common
    sudo add-apt-repository ppa:neovim-ppa/unstable
    sudo apt update
    sudo apt install neovim

    # for telescope from TJ(telescopic joshnson)
    sudo apt install fzf fd-find ripgrep
```

- from cargo
```bash
    # for nvim-treesitter
    cargo install tree-sitter-cli
```
