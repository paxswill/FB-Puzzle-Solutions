# I hate stupid makefiles...

all: meepmeep

main.o: meepmeep.c
	${CC} meepmeep.c -o meepmeep

tar: meepmeep.c Makefile
	tar czvf meepmeep.tar.gz Makefile meepmeep.c 

