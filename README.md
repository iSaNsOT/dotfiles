# 💤 LazyVim 😴

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

### Usage (Notes for my future self)

1. Install the dependencies

    * Neovim >= 0.9.0 ➡️ Easier with [Homebrew](https://brew.sh/)
      ```shell
         brew install neovim
      ```

    * Git >= 2.19.0 ➡️ Normally installed by default, if not, [Homebrew](https://brew.sh/)
      ```shell
         brew install git
      ```

    * [Nerd Font](https://www.nerdfonts.com/)

    * A C compiler

    * Unzip (not really necessary, but some LSP require it (and other dependencies like cargo, go, npm...))

    * [LazyGit](https://github.com/jesseduffield/lazygit) (optional) ➡️ Easier with [Homebrew](https://brew.sh/) (❗Better with tap formula)
      ```shell
         brew install jesseduffield/lazygit/lazygit
      ```

    * For telescope (optional)
        * [ripgrep](https://github.com/BurntSushi/ripgrep) ➡️ Easier with [Homebrew](https://brew.sh/) `brew install ripgrep`
          ```shell
            brew install ripgrep
          ```

        * [fd](https://github.com/sharkdp/fd) ➡️ Easier with [Homebrew](https://brew.sh/)
          ```shell
            brew install fd
          ```


2. Clone the repository inside `~/.config/nvim/`.

```shell
git clone https://github.com/iSaNsOT/dotfiles.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```
