
all: 
	gcc -m32 -z execstack -o a32.out call_shellcode.c

setuid:
	gcc -m32 -z execstack -o a32.out call_shellcode.c
	sudo chown root a32.out 
	sudo chmod 4755 a32.out 

clean:
	rm -f a32.out *.o

