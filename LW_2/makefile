CC=mpicc
CFLAGS=-std=c99 -Werror -pedantic -Wall -Wextra -O3
LDFLAGS=
LIBS=-lm
SOURCES=LW_2.c
OBJECTS=$(SOURCES:.c=.o)
EXECUTABLE=LW_2

all: $(EXECUTABLE)

$(EXECUTABLE): %: %.c
	$(CC) $(CFLAGS) $< -o $@ $(LIBS)

clean:
	rm -frd $(EXECUTABLE) $(OBJECTS)
