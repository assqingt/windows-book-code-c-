.PHONY:clean
CC=gcc
CPPFLAGS=-Wall -g
BIN= main
OBJS= ex-1.c  bitree.c
$(BIN):$(OBJS)
	$(CC) $(CPPFLAGS) $^ -o $@
%.o:%.c
	$(CC) $(CPPFLAGS) -c $< -o $@
clean:
	rm -f *.o $(BIN)

