# C/C++ Scripts

Helper scripts for C/C++ development.

## Help

ff-c-includes

    Usage: ff-c-includes < FILE-LIST
    
    Lists includes of the input files.
    
    -c HEADERS   : Use previous output.
    -d DIRECTORY : Delete files found in directory.
    -D DIRECTORY : Search includes in directory.

ff-ctags

    Usage: ff-ctags < FILES

find-c-files

    Usage: find-c-files [DIRS...]
    
    Find C/C++ files (sources, binaries, ...)
    
        -H : Search headers. (Default -HS)
        -S : Search source.
        -X : Search executables.
        -L : Search static libraries.
        -D : Search dynamic libraries.

make-h-c

    Usage: make-h-c ...
    
    ... makefile  : Print 'Makefile'.
    ... gitignore : Print '.gitignore'.

np--c

    Usage: np--c : Initialize C project.
    
    Requires make-h(1) from sh-organizing-tools.

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
