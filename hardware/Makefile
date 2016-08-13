# Makefile to generate symbols

AUTOSYM=autosym
AUTOSYM_PATH=$(shell command -v $(AUTOSYM) 2> /dev/null)
SOURCE=share/autosym
DEST=share/symbols/build

.PHONY : sym, clean

sym:
ifeq ($(strip $(AUTOSYM_PATH)),)
	$(error Autosym not installed. Check github.com/markushutzler/autosym)
endif
	$(AUTOSYM) $(SOURCE) $(DEST)

clean:
	rm -r ./$(DEST)
