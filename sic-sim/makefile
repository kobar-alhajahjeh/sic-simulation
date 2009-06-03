TARGET = sic-sim
OBJS = main.o

all : $(TARGET)

clean :
	rm $(OBJS)

$(TARGET) : $(OBJS)
	gcc -o sic-sim $(OBJS)
	
main.o : main.c
	gcc -c main.c