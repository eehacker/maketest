DIRS	= memo calendar main
OBJECTS	= memo.o calendar.o main.o
TARGET	= diary

all : objs
	$(CC) -o $(TARGET) $(OBJECTS)
objs :
	@for dir in $(DIRS); do \
	make -C $$dir || exit $?; \
	done		                     
	
clean: 
	@for dir in $(DIRS); do \
	make -C $$dir clean; \
	done
	-rm -rf $(TARGET) *.o 
