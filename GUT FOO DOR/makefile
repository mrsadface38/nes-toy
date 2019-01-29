# Controllers
# NES program that uses controllers.

all: controller.nes

controller.nes: controller.asm
	nesasm controller.asm

clean:
	rm -f controller.nes controller.fns

run: controller.nes
	mednafen controller.nes
