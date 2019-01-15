# Decimal numbers
# NES program that converts from hex/bin to dec numbers.

.POSIX:

all: pong.nes

pong.nes: pong.asm mario.chr
	nesasm pong.asm

clean:
	rm -f pong.nes pong.fns

run: pong.nes
	mednafen pong.nes
