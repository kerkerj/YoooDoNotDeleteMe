# YooooDoNotDeleteMe

This is my stuffs.

## Install

1. Install neovim (https://github.com/neovim/homebrew-neovim)

1. Install [spf13-vim](https://github.com/spf13/spf13-vim).

1. Install [Oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

1. [iTerm2 color schema](https://github.com/mbadolato/iTerm2-Color-Schemes), my favorite theme is Seti currently. (I copied it from [here](https://github.com/mbadolato/iTerm2-Color-Schemes/blob/master/schemes/Seti.itermcolors))

1. Clone this project.

1. Run `./install.sh`

`.vimrc.before.local`

`.vimrc.bundles.local`

`.vimrc.local`

I use [ gruvbox ](https://github.com/morhetz/gruvbox) as my vim colorschema

## Enable powerline font

clone `https://github.com/powerline/fonts`, and run `./install.sh`

Then choose fonts in iTerm2.

My personal favorites: `Meslo LG S DZ Regular for powerline`, ``

## Reload tmux configuration

```
$ tmux source-file ~/.tmux.conf
```

## Gruvbox issue (https://github.com/morhetz/gruvbox/wiki/Terminal-specific)

Use neovim will fix anything!

## Just my notes below

OSX - must use F1 to F12 as standard function keys

* `F2`  - Remove all trailing spaces
* `F5`  - Nerdtree
* `F6`  - copy selected text to OS clipboard
* `F7`  - tagbar
* `F12` - paste mode

Leader is set to `,` use `:let mapleader` to see current leader key

* `ctrl-x ctrl-o` - when in insert mode, show Omni completion
* `<leader>tt` or `F7` - to toggle tagbar
* `gcc` - comment one line
* `<leader>,` - toggle search highlight
* `<leader>p` - Toggle past mode (same as <F12>)
* `<leader>n` - to rename current file
* `<leader>g` - to generate the header guard
* `<leader>b` - to toggler buffergator
* `<C-J>`     - to auto insert snips
* `<leader>ig` - toggle indent guide
* `<leader><leader>w/b` - easymotion

## Plugin list

```
Plugin 'gmarik/vundle'
Plugin 'MarcWeber/vim-addon-mw-utils'
Plugin 'tomtom/tlib_vim'
Plugin 'mileszs/ack.vim'
Plugin 'scrooloose/nerdtree'
Plugin 'altercation/vim-colors-solarized'
Plugin 'spf13/vim-colors'
Plugin 'tpope/vim-surround'
Plugin 'tpope/vim-repeat'
Plugin 'spf13/vim-autoclose'
Plugin 'ctrlpvim/ctrlp.vim'
Plugin 'tacahiroy/ctrlp-funky'
Plugin 'kristijanhusak/vim-multiple-cursors'
Plugin 'vim-scripts/sessionman.vim'
Plugin 'matchit.zip'
Plugin 'bling/vim-airline'
Plugin 'Lokaltog/vim-easymotion'
Plugin 'jistr/vim-nerdtree-tabs'
Plugin 'flazz/vim-colorschemes'
Plugin 'mbbill/undotree'
Plugin 'nathanaelkane/vim-indent-guides'
Plugin 'vim-scripts/restore_view.vim'
Plugin 'mhinz/vim-signify'
Plugin 'osyo-manga/vim-over'
Plugin 'kana/vim-textobj-user'
Plugin 'kana/vim-textobj-indent'
Plugin 'gcmt/wildfire.vim'
Plugin 'scrooloose/syntastic'
Plugin 'tpope/vim-fugitive'
Plugin 'mattn/webapi-vim'
Plugin 'mattn/gist-vim'
Plugin 'scrooloose/nerdcommenter'
Plugin 'tpope/vim-commentary'
Plugin 'godlygeek/tabular'
Plugin 'majutsushi/tagbar'
Plugin 'Valloric/YouCompleteMe'
Plugin 'SirVer/ultisnips'
Plugin 'honza/vim-snippets'
Plugin 'elzr/vim-json'
Plugin 'pangloss/vim-javascript'
Plugin 'briancollins/vim-jst'
Plugin 'kchmck/vim-coffee-script'
Plugin 'amirh/HTML-AutoCloseTag'
Plugin 'hail2u/vim-css3-syntax'
Plugin 'gorodinskiy/vim-coloresque'
Plugin 'tpope/vim-rails'
Plugin 'fatih/vim-go'
Plugin 'mattn/emmet-vim'
Plugin 'vim-ruby/vim-ruby'
Plugin 'vim-airline/vim-airline-themes'
Plugin 'jeetsukumaran/vim-buffergator'
Plugin 'ervandew/supertab'
```

## Some notes

### Mac apps

* Alfred 2
* AppCleaner
* Atom
* Boom 2 (Not Free)
* BatteryHealth
* Burpsuite - An integrated platform for performing security testing of web applications. (https://portswigger.net/burp/)
* DaisyDisk - 檢查磁碟用量分佈 (Not Free)
* Dash - 離線查詢文件 (Not Free)
* Docker - Docker Quick start Terminal.app, Kitematic.app
* Dropbox
* Evernote
* Firefox
* Google Chrome
* HyperSwitch - Quick Switch while in command+tab mode
* iTerm
* iTerm2ColorSchema - http://iterm2colorschemes.com/
* Karabiner - A powerful and stable keyboard customizer for OS X.
* Keka - 解壓縮工具
* LimeChat - IRC gui client
* Little Snitch 3 - Check network connections (Not Free)
* LiveReload
* MacDown - markdown editor
* Memory Clean
* MPlayerX
* MySQLWorkbench - MySQL gui client
* Nally - BBS client
* pgAdmin3 - A open source postgresql gui client (http://www.pgadmin.org/)
* Postico - A Modern PostgreSQL Client for OS X. Free Version (https://eggerapps.at/postico/)
* rdm.app - redis gui client
* Robomongo - mongodb gui client
* Seil
* Skype
* Slack
* SoureTree
* Spectacle - window arrangement
* SSH Tunnel Manager
* Sublime text
* TeamViewer
* Transmission - BT client.
* Tunnelblck
* Vagrant
* VirtualBox
* Wireshark
* Xcode
* XtraFinder - Replacement of Mac Finder. (Need to disable SIP)

* zsh + oh-ny-zsh
  * zsh-syntax-highlighting (see https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md#with-oh-my-zsh)
  * autojump
  * ssh-agent
  * theme: avit

### hombrew (http://brew.sh/)

* autojump - A cd command that learns - easily navigate directories from the command line http://wiki.github.com/joelthelion/autojump/
* the_silver_searcher - ag quicker seacher
* tig - Text-mode interface for git http://jonas.nitro.dk/tig/
* tmate - Instant terminal sharing.
* tree - a recursive directory listing command.
* htop
* vim
* siege - a http load testing and benchmarking utility.
* httpie - CLI HTTP client; user-friendly cURL replacement featuring intuitive UI, JSON support, syntax highlighting, wget-like downloads, extensions, etc. http://httpie.org
* jq - json query
* ctags
* watchman - watches files and takes action when they change.
* wget
* hugo
* vegeta
* swiftenv - Swift Version Manager
* go
* python3
* neovim

## Some references

http://harrycode.logdown.com/tags/Vim

https://ruby-china.org/topics/25295

## Some fonts

* [powerline-fonts](https://github.com/powerline/fonts)
* [fantasque-sans](https://github.com/belluzj/fantasque-sans)


