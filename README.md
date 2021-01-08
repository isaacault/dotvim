# dotvim
My vim configuration. Uses Vim8+ package manager.

## Installation
1. Clone the repo
    ```
    git clone git://github.com/isaacault/dotvim.git ~/.vim
    ```

2. Add the symlinks
    ```
    ln -s ~/.vim/vimrc ~/.vimrc
    ln -s ~/.vim/gvimrc ~/.gvimrc
    ln -s ~/.vim/ideavimrc ~/.ideavimrc
    ```

3. Install plugins
    ```
    cd ~/.vim
    git submodule update --init --recursive
    ```

## Acknowledgements

* [erangaeb](https://github.com/erangaeb) for lots of the vimrc configuration
  - Taken from [dotvim](https://github.com/erangaeb/dotvim)
* [pushqrdx](https://github.com/pushqrdx) for ideas with lots of the plugins
  - Taken from [dotfiles](https://github.com/pushqrdx/dotfiles)
