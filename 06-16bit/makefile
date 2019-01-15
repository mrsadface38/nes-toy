# 16 bit math
# NES program that makes use of 16 bit values for large numbers.

.POSIX:

all: background.nes

background.nes: background.asm mario.chr
	nesasm background.asm

clean:
	rm -f background.nes background.fns

run: background.nes
	mednafen background.nes
