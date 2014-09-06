CC=arm-none-linux-gnueabi-gcc

susan: susan.c Makefile
	arm-none-linux-gnueabi-gcc -static -O4 -o susan susan.c -lm 

clean:
	rm -rf susan output*
