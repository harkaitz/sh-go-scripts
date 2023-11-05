GO SCRIPTS
============

Helper shell script collection for Go development.

## Help

find-go-files

    Usage: find-go-files [DIRS...]

go-h-cmd-getopt

    Usage: go-h-cmd-getopt NAME

go-h-cmd-hello

    Usage: go-h-cmd-hello NAME

go-h-coverage

    Usage: go-h-coverage ...
    
    Helper script for launching intetration tests in Go and gather
    coverture information.
    
      -l        : List "tests/tNN-*" scripts (if any).
      -b        : Run "make all GO_CONF=-cover".
      -r [TEST] : Execute tests and save data to "/tmp/cov". 
                  
    (i) It will put "./build" in path for you.

make-h-go

    Usage: make-h-go ...
    
    ... cmds        : List defined programs.
    ... makefile    : Print 'Makefile'.
    ... gitignore   : Print '.gitignore'.

np--go

    Usage: np--go : Initialize go project.

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
