 OBJECTS  = $(patsubst %.c, %.o, $(wildcard *.c))	 

all : diary
diary : $(OBJECTS)
	$(CC) -o $@ $^
	cp -f diary $${HOME}			
						
clean :						
	rm -rf *.o diary
