export PLATFORM = msd45n
export PRODUCT = msd45n_fips
export DATE := $(shell date "+%Y%m%d")

all:
	mkdir -p $(DATE)
	cp -f ../../buildroot/output/$(PRODUCT)/images/$(PRODUCT).tar.bz2 $(DATE)/
	rm -f latest
	ln -s "$(DATE)" latest

.PHONY: all
