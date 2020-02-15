OBJECTS	= ./memo/memo.o ./calendar/calendar.o ./main/main.o
export CC = gcc							
								

all :  MEMO \
	CALENDAR \
	MAIN \
	diary
MEMO :
	$(MAKE) -C memo

CALENDAR :
	$(MAKE) -C calendar

MAIN :
	$(MAKE) -C main

diary : $(OBJECTS)
	$(CC) -o $@ $^

clean :
	cd memo && $(MAKE) clean
	cd calendar && $(MAKE) clean
	cd main && $(MAKE) clean
	rm -rf *.o diary
