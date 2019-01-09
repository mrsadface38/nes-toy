# Sprites
# NES program that introduces sprites.

all: sprites.nes

sprites.nes: sprites.asm
	nesasm sprites.asm

clean:
	rm -f sprites.nes sprites.fns

run: sprites.nes
	mednafen sprites.nes
