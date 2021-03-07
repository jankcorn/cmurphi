
TOPDIR := $(dir $(realpath $(lastword $(MAKEFILE_LIST))))

MU := $(TOPDIR)/bin/mu

.m.C:
	${MU} ${MURPHILOCALOPT} ${MURPHIOPT} $<
