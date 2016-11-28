About
------------
Neovim config for ruby on rails developer.

Features
------------

  - ruby async autocomplete
  - ruby linting with rubocop/reek
  - auto correct/save ruby file with `<leader>rc` using rubocom
  - generate ctags `<leader>ct`
  - search in ctags with `,.`
  - you can undo even after the editor was closed
  - file opens in the same line
  - open `devdoc.io` documentation for current string `K`
  - inline rspec execution with `<leader>R`
  - normal(not strange vim syntax) posix REGEXP with `/`
  - fast project navigation with Fzf and ctrlP
  - fast file browsing with `-` and split browsing `<Leader>e` or `<Leader>v`
  - fast [esc] with "jj"
  - fast jumping in normal mode `s` followed by 2 chars

Installation
------------

Install neovim.
To ensure that all plugins work you need neovim dependencies:

    sudo pip2 install --upgrade neovim
    sudo pip3 install --upgrade neovim
    gem install neovim rubocop reek ripper-tags

Other dependencies:

  - The silver searcher (apt-get|brew install ag) https://github.com/ggreer/the_silver_searcher

To install, run

    $ git clone git://github.com/gacha/nvim-config.git ~/.config/nvim
    $ mkdir ~/.config/nvim/swap && mkdir ~/.config/nvim/undo

Then open neovim and install plugins

    $ nvim
    :PlugInstall

To update plugins run

    $ vim
    :PlugUpdate

Debug
------------
If something doesn't work try `:messages` and `:CheckHealth`.
