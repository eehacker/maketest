OBJECTS	= memo.o calendar.o main.o		

.SUFFIXES : .o .c				
.c .o :						
	$(CC) -DDEBUG -c -o $@ $<			

all : diary
diary : $(OBJECTS)
	$(CC) -o $@ $^
