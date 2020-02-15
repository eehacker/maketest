OBJECTS	= memo.o calendar.o main.o		

.SUFFIXES : .o .c				
					 		
%.o : %.c					
	$(CC) -DDEBUG -c -o $@ $<		

all : diary					
diary : $(OBJECTS)				
	$(CC) -o $@ $^				
