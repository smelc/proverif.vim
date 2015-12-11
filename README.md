proverif.vim
=======

A vim mode for proverif's .pv files (http://prosecco.gforge.inria.fr/personal/bblanche/proverif/)

To use it, copy proverif.vim to ~/.vim/syntax/

Set the following into your .vimrc for the mode to be applied automatically to files with the .pv extension:

```
" au BufRead,BufNewFile *.pv setfiletype proverif
```

Use this to get the colors right (if your terminal does not support 256 colors, install ncurses-term on ubuntu):

```
" set t_Co=256
```
