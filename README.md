ansiech - ANSI escape code helper
==================================
ansiech is an embeddable helper script for using ANSI escape code easily by the bash script.

Usage
------

    # 1. Use ansiech command directly.
    ansiech SGR fg:red; echo red text; ansiech SGR reset
    
    # 2. Use ansiech command with symbolic link.
    ln -s ansiech SGR
    SGR fg:red; echo red text; SGR reset
    
    # 3. Use ansiech command with symbolic link and command substitution.
    echo "$(SGR fg:red)red text$(SGR reset)"
    
Reference
----------
* Wikipedia / [ANSI escape code](http://en.wikipedia.org/wiki/ANSI_escape_code)
