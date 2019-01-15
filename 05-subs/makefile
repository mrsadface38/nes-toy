# Subroutines
# NES program showing how to impliment subroutines in assembly.

.POSIX:

all: pong.nes

pong.nes: pong.asm mario.chr
	nesasm pong.asm

clean:
	rm -f pong.nes pong.fns

run: pong.nes
	mednafen pong.nes
