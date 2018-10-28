CC = gcc
CFLAGS = -W
TARGET = main.out
OBJECTS = main.o

all : $(TARGET)

$(TARGET): $(OBJECTS)
	$(CC) $(CFLAGS) -o $@ $^

clean:
	rm *.o $(TARGET)
