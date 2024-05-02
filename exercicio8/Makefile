obj-m+=questao8.o

all:
	make -C /lib/modules/$(shell uname -r)/build/ M=$(PWD) CFLAGS="-lpthread" modules
clean:
	make -C /lib/modules/$(shell uname -r)/build/ M=$(PWD) clean
