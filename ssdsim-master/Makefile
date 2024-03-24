all:ssd 
	
clean:
	del ssd.o avlTree.o flash.o initialize.o pagemap.o ssd.exe

ssd: ssd.o avlTree.o flash.o initialize.o pagemap.o     
	gcc ssd.o avlTree.o flash.o initialize.o pagemap.o -o ssd
ssd.o: ssd.c
	gcc -c -g ssd.c
flash.o: flash.c
	gcc -c -g flash.c
initialize.o: initialize.c
	gcc -c -g initialize.c
pagemap.o: pagemap.c
	gcc -c -g pagemap.c
avlTree.o: avlTree.c
	gcc -c -g avlTree.c

