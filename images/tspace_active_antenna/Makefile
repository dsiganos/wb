export PLATFORM = wb45n
export PRODUCT = tspace_active_antenna
export DATE := $(shell date "+%Y%m%d")

all:
	mkdir -p "$(DATE)"
	$(MAKE) -f ../../common.mk -C "$(DATE)"
	ln -sf "$(DATE)/fw.txt" fw.txt
	rm -f latest
	ln -s "$(DATE)" latest

.PHONY: all
