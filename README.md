#vim-kpl

Vim syntax highlighting for Kernel Programming Language. 

Includes line ending fix by cameronbwhite. 

## Installation
Install via vundle by adding `Plugin 'hfkang/kpl.vim'` to your `.vimrc` file

If you have all of your kpl source files in a common directory eg `~/blitz`, then 
you can add the line `autocmd BufRead,BufNewFile ~/blitz/*.c set syntax=kpl` to your 
`.vimrc` file and have syntax highlighting automatically enabled in that directory. 

