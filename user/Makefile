TARGET = redir.so

CFLAGS ?= -O2 -Wall

CC = $(CROSS_COMPILE)gcc

all: $(TARGET)

%.so: %.c
	$(CC) $(CFLAGS) -shared -fpic -o $@ $<

clean:
	rm -rf $(TARGET)