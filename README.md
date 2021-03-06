# togglelist.vim

A simple plugin for vim that allows you to bind a key to toggle the `Location List` and the `Quickfix List`. This plugin is currently in early development and there aren't many things besides a few options I imagine adding. Feel free to submit patches.

## Installation

### Basic Brute-Force Install

Copy `togglelist.vim` to your `~/.vim/plugin` directory.

### Pathogen

Checkout the github repository to the [Pathogen](https://github.com/tpope/vim-pathogen) directory.

    cd ~/.vim/bundle
    git clone https://github.com/milkypostman/vim-togglelist.git


## Mappings

The default mappings are:

    nmap <script> <silent> <leader>l :call ToggleLocationList()<CR>
    nmap <script> <silent> <leader>q :call ToggleQuickfixList()<CR>

You can easily unmap these and remap them if you want, both `ToggleLocationList` and `ToggleQuickfixList` are global functions. I imagine the names of the functions are self-explanatory.

After opening or closing either list, the previous window is restored so you can still use `<C-w>p`.


