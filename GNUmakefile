PROJECT=sh-go-scripts
VERSION=1.0.0
PREFIX=/usr/local
all:
clean:
install:

## -- BLOCK:license --
install: install-license
install-license: 
	mkdir -p $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
	cp LICENSE  $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
## -- BLOCK:license --
## -- BLOCK:sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/go-h-cmd-getopt  $(DESTDIR)$(PREFIX)/bin
	cp bin/go-h-coverage    $(DESTDIR)$(PREFIX)/bin
	cp bin/make-h-go        $(DESTDIR)$(PREFIX)/bin
	cp bin/np--go           $(DESTDIR)$(PREFIX)/bin
	cp bin/go-h-cmd-hello   $(DESTDIR)$(PREFIX)/bin
	cp bin/find-go-files    $(DESTDIR)$(PREFIX)/bin
## -- BLOCK:sh --
