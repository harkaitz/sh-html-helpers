PROJECT=sh-html-helpers
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
	cp bin/code-html-links  $(DESTDIR)$(PREFIX)/bin
	cp bin/code-html-resources $(DESTDIR)$(PREFIX)/bin
	cp bin/code-html-images $(DESTDIR)$(PREFIX)/bin
## -- BLOCK:sh --
