# dotfiles

## Step
1. Copy config file on this folder to their places.

1. Install [homebrew](https://brew.sh/)

1. Install [iTerm2](https://iterm2.com/)

1. Install [tmux](https://github.com/tmux/tmux/wiki)

1. Install [neovim](https://neovim.io/)

1. Install ack `brew install ack`

1. Install ctags `brew install ctags`

1. Install [amix/vimrc](https://github.com/amix/vimrc) (awesome version)

1. Install [asdf](https://asdf-vm.com)

1. Install [asdf-nodejs](https://github.com/asdf-vm/asdf-nodejs)

1. Install nodejs 16.14.0
    ```sh
    asdf install nodejs 16.14.0
    ```

1. Make that version of nodejs global
    ```sh
    asdf global nodejs 16.14.0
    ```

1. Install [coc.nvim](https://github.com/neoclide/coc.nvim)
    ```sh
    npm install --global yarn
    cd ~/.vim_runtime/my_plugins/coc.nvim
    yarn install
    ```

1. Install solargraph
    ```
    gem install solargraph
    ```

1. [migrate-vim-to-nvim](https://neovim.io/doc/user/nvim.html#nvim-from-vim)

1. Open nvim, execute
    ```sh
    :PlugInstall
    :CocInstall coc-json coc-tsserver coc-go coc-jedi
    ```

1. Install and config [vim-tmux-navigator](https://github.com/christoomey/vim-tmux-navigator)

1. Install [TPM](https://github.com/tmux-plugins/tpm)
    ```sh
    git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
    tmux source ~/.tmux.conf
    ```
    Press prefix + I (capital i, as in Install) to fetch the plugin.

1. Config [tmux vim-binding](https://www.rushiagr.com/blog/2016/06/16/everything-you-need-to-know-about-tmux-copy-pasting/)

1. [Optional] Setup [git gpg](https://gist.github.com/Beneboe/3183a8a9eb53439dbee07c90b344c77e)

1. [Git Delta](https://github.com/dandavison/delta)
