# EdVim: A Fork of Carlhuda's vim Distribution

This is a basic distribution of vim plugins and tools intended to be run
on top of the latest MacVIM snapshot.

## Installation

0. `for i in ~/.vim ~/.vimrc ~/.gvimrc; do [ -e $i ] && mv $i $i.old;
   done`
1. `git clone git://github.com/edusahione/EdVim.git ~/.vim`
2. `cd ~/.vim`
3. `rake`

or

  `curl https://github.com/edusahione/edvim/raw/master/bootstrap.sh -o - | sh`
