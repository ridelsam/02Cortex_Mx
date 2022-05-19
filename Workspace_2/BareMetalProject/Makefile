CC=arm-none-eabi-gcc
MACH = cortex-m4
CFLAGS = -c -mcpu=$(MACH) -mthumb -std=gnu11 -o0

main.o:main.c
	$(CC) $(CFLAGS) main.c -o main.o
		