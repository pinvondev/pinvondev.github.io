OBJS=main.o f.o
C=-c
main:$(OBJS)
	gcc $(OBJS) -o main
main.o:main.c f.h
	gcc $(C) main.c
f.o:f.c f.h
	gcc $(C) f.c
clean:
	rm -f main *.o
