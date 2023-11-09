GO SCRIPTS
============

Helper shell script collection for Go development.

## Help

find-go-files

    Usage: find-go-files [DIRS...]

frontend-h-favicon

    Usage: frontend-h-favicon -l | NAME
    
    Create "img/favicon.png" file to add in a website with the
    following tag:
    
      <link rel="icon" type="image/x-icon" href="/img/favicon.png" />
    
    Environment variables: LOGO_DIRECTORY

frontend-h-htmx

    Usage: frontend-h-htmx
    
    Download "htmx.min.js" to "js".

go-h-cmd-getopt

    Usage: go-h-cmd-getopt NAME
    
    Create a command line utility with getopt(1) command line
    arguments in "cmd/NAME/main.go".

go-h-cmd-gin1

    Usage: go-h-cmd-gin1 LAUNCHER-NAME PACKAGE-NAME
    
    Create a skeleton of a go/htmx project. This command will
    create a launcher in "cmd/LAUNCHER/main.go" and a website
    in "routes.go" and "public/".
    
    If the files exist only "public/js/htmx.min.js" will be
    updated.

go-h-cmd-hello

    Usage: go-h-cmd-hello NAME
    
    Create a simple hello world program in "cmd/NAME/main.go".

go-h-coverage

    Usage: go-h-coverage ...
    
    Helper script for launching intetration tests in Go and gather
    coverture information.
    
      -l        : List "tests/tNN-*" scripts (if any).
      -b        : Run "make all GO_CONF=-cover".
      -r [TEST] : Execute tests and save data to "/tmp/cov". 
                  
    (i) It will put "./build" in path for you.

go-h-mod

    Usage: go-h-mod ...
    
    -i URL : Create a "go.mod" and git repo ".git" if needed.
    -c     : Check a "go.mod" exists.
    -m     : Print current module's URL.
    

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
