# Background
# Simple NES program that makes a background color.

.POSIX:

all: background.nes

background.nes: background.asm
	nesasm background.asm

clean:
	rm background.nes

run: background.nes
	nestopia background.nes
