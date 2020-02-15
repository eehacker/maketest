
OBJECTS  = memo.o calendar.o main.o

all : memo.o calendar.o main.o diary

memo.o :
	cd memo && make			
						 
calendar.o :
	cd calendar && make			
main.o :
	cd main && make

diary : $(OBJECTS)			 
	$(CC) -o $@ $^			

clean :
	cd memo && make clean
	cd calendar && make clean
	cd main && make clean
	-rm -rf *.o diary
