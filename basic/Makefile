# Background
# Simple NES program that makes a background color.

.POSIX:

all: background.nes

background.nes: background.asm mario.chr
	nesasm background.asm

clean:
	rm -f background.nes background.fns

run: background.nes
	mednafen background.nes
