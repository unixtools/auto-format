# auto-format
simple wrapper for various code formatting intended to be used from editor macro

Example for command line use:

	/usr/bin/auto-format --inplace /path/to/file1.pl

Example for /etc/vim/vimrc:

    map <F3> :%!/usr/bin/auto-format --hint '%'<C-M>
    map <F4> :%!/usr/bin/auto-format --force --hint '%'<C-M>

