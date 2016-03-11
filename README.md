# Lucario

A Vim (and NeoVim) plugin manager friendly version of
[Lucario](https://github.com/raphamorim/lucario) color scheme created by
[raphamorim](https://github.com/raphamorim). Supporting vim-plug,
Vundle, and Pathogen.

The folder structure of the original Lucario Github repo breaks support
for plugin managers. So I repackaged it and added copypasta snippets
below.

### Usage

#### Step 1: Install colorscheme to Vim/NeoVim

Add 't1mxg0d/vim-lucario' to your `.vimrc` or `init.vim`:

**[vim-plug](https://github.com/junegunn/vim-plu://github.com/junegunn/vim-plug)**

    Plug 't1mxg0d/vim-lucario' :PlugInstall

**[Vundle](https://github.com/VundleVim/Vundle.vim)**

    Plugin 't1mxg0d/vim-lucario' :PluginInstall

**[Pathogen](https://github.com/tpope/vim-pathogen)**

    cd ~/.vim git submodule add
    https://github.com/t1mxg0d/vim-lucario.git bundle/colorschemes
    # Repeat above for NeoVim
    cd ~/.config/nvim && !-1 <return>

**[Manually](http://vignette1.wikia.nocookie.net/uncyclopedia/images/5/5c/Old_computer.jpg/revision/latest?cb=20120915052526)**

    git clone https://github.com/t1mxg0d/vim-lucario.git
    cd vim-lucario/
    cp colors/lucario.vim ~/.vim/colors/lucario.vim # Vim
    cp colors/lucario.vim ~/.config/nvim/colors/lucario.vim # NeoVim

#### Step 2: Update your .vimrc

    syntax enable
    set number
    colorscheme lucario

## About

All credit is due to the **original creator**
[raphamorim](https://github.com/raphamorim), I've only repackaged it and
added documention for plugin manager support and my own convience.
