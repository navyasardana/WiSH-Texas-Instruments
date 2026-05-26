CC     = gcc
CFLAGS = -Wall -Wextra -Iinc
SRCS   = src/main.c src/add.c src/subtract.c src/multiply.c src/divide.c src/menu.c
TARGET = calculator

all: $(TARGET)

$(TARGET): $(SRCS)
	$(CC) $(CFLAGS) -o $(TARGET) $(SRCS)

clean:
	rm -f $(TARGET)
