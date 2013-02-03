Xterminate.vim
==============
Append equivalent x256 colors to GUI only colorschemes.

e.g.

    hi Constant guifg=#000000 guibg=#FFFFFF gui=bold
    " becomes
    hi Constant guifg=#000000 guibg=#FFFFFF gui=bold ctermfg=0 ctermbg=231 cterm=bold

License
=======
Same as Vim's. See `:help license`.
