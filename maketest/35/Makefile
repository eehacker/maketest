 SRCS	=$(wildcard *.c)		
OBJECTS	=$(SRCS:.c=.o)				

all : diary
diary : $(OBJECTS)
	$(CC) -o $@ $^
	
clean :
	rm -rf *.o diary
