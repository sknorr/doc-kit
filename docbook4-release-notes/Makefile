# This file originates from the project
# gitlab.nue.suse.com/documentation/release-notes-boilerplate.
# THIS FILE WAS MADE FOR DOWNSTREAM BOOTSTRAPPING.

BRANCH = rn_fate_doc-kit

.PHONY: all make-update

all: make-update

make-update:
	wget --no-check-certificate -O Makefile0 \
	  https://gitlab.suse.de/documentation/makefile-release-notes/raw/$(BRANCH)/Makefile && \
	  mv Makefile0 Makefile

