### Below are the instructions for installing [YouCompleteMe](https://github.com/Valloric/YouCompleteMe) on Mac OS X

#### Prerequisites 

* [brew](http://brew.sh/)
* [pathogen](https://github.com/tpope/vim-pathogen) or [vundle](https://github.com/gmarik/vundle),
* [vim](http://www.vim.org/) (>= 7.3.584)

#### Instructions

1. `brew install cmake`
2. `cd ~/.vim/bundle`
3. `git clone https://github.com/Valloric/YouCompleteMe.git`
4. `git submodule update --init --recursive`
5. `cmake -G "Unix Makefiles" . ~/.vim/bundle/YouCompleteMe/third_party/ycmd/cpp/`
6. `make ycm_core`
7. Restart Vim
8. Enjoy
