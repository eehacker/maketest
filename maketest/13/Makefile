OBJECTS	=$(patsubst %.c, %.o, $(wildcard *.c))	

all :  diary
diary : $(OBJECTS)
	$(CC) -o $@ $^
clean :										
	rm -rf *.o diary			
