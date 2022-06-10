all: input.jed output.jed

GALasm/src/galasm:
	make -C GALasm/src galasm

%.jed:	%.pld GALasm/src/galasm
	GALasm/src/galasm $<
