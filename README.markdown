SystemVerilog with UVM
==

Cloned from https://github.com/vim-scripts/verilog_systemverilog.vim
Which was a mirror of http://www.vim.org/scripts/script.php?script_id=1586

This script extends Verilog syntax highlighting, which comes along with Vim 6.3, 
and adds SystemVerilog stuff to it. It will recognize Verilog and SystemVerilog syntax
in *.v, *.vh and *.sv files. The new syntax is named as "verilog_systemverilog". 

If your scripts are loaded correctly, you should see this syntax name when you execute
the Vim command ":set syntax?" in your Verilog/SystemVerilog files.

Installation
--

###With [Pathogen](https://github.com/tpope/vim-pathogen)

Check out from github

    ## where ~/.vim is your vim files location
    cd ~/.vim/bundle
    git clone git://github.com/morganp/vim-SystemVerilog.git

Add as git submodule

    ## where ~/.vim is your vim files location
    cd ~/.vim
    git submodule add http://github.com/morganp/vim-SystemVerilog.git bundle/systemverilog
    git add .
    git commit -m "Install systemverilog.vim bundle as a submodule."

