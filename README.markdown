My Vim .vimrc IDE Setup
=======================
* cp .vimrc to /home/user
* git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
* start vim
* run ":PlugInInstall" to install all plugins


Instruction Source
####[Vim_IDE](https://realpython.com/blog/python/vim-and-python-a-match-made-in-heaven/)

Plugins:
####[Vundle](https://github.com/VundleVim/Vundle.vim)
####[SimpylFold](https://github.com/tmhedberg/SimpylFold)
####[indentpython](https://github.com/vim-scripts/indentpython.vim)

####[YouCompleteMe](https://github.com/Valloric/YouCompleteMe)
    CTRL+Space

####[syntastic](https://github.com/vim-syntastic/syntastic)
####[nerdtree](https://github.com/scrooloose/nerdtree)
    CTRL+n
    open in window hit "s", open in tab hit "t"

####[ctrlp](https://github.com/kien/ctrlp.vim)
    CTRL+p

####[powerline](https://github.com/powerline/powerline)

####[conque](https://github.com/wkentaro/conque.vim)
Usage
=====
Type :ConqueTerm <command> to run your command in vim, for example:
    
    :ConqueTerm bash
    :ConqueTerm mysql -h localhost -u joe -p sock_collection
    :ConqueTerm Powershell.exe
    :ConqueTerm C:\Python27\python.exe

To open ConqueTerm in a new horizontal or vertical buffer use:
    
    :ConqueTermSplit <command>
    :ConqueTermVSplit <command>
    :ConqueTermTab <command>

All text typed in insert mode will be sent to your shell.
Use the ``<F9>`` key to send a visual selection from any buffer to the shell.

For more help type :help ConqueTerm
