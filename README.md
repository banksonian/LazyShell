# LazyShell

A simple script that generates reverse shells using your preferred interface and a random port, then sets up a listener using pwncat.

I reccomend giving an alias for this script in your .bashrc or .zshrc for ease of use, example: alias shell="python3 /pathtoscript/shell.py"

Dependencies:
Pwncat, Netifaces, and rlwrap

pip3 install pwncat

pip3 install netifaces

sudo apt install rlwrap
