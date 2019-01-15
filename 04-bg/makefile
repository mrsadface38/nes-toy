# Backgrounds

all: background.nes

background.nes: background.asm
	nesasm background.asm

clean:
	rm -f background.nes background.fns

run: background.nes
	mednafen background.nes
