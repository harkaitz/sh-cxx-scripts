PROJECT=sh-cxx-scripts
VERSION=1.0.0
PREFIX=/usr/local
all:
clean:
install:

## -- BLOCK:license --
install: install-license
install-license: 
	install -D -t $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT) LICENSE
## -- BLOCK:license --
## -- BLOCK:sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/ff-ctags         $(DESTDIR)$(PREFIX)/bin
	cp bin/find-c-files     $(DESTDIR)$(PREFIX)/bin
	cp bin/ff-c-includes    $(DESTDIR)$(PREFIX)/bin
	cp bin/make-h-c         $(DESTDIR)$(PREFIX)/bin
## -- BLOCK:sh --
