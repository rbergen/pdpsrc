#
# Makefile for building 'wget' from wget.c
#

# Choose your compiler and options. For 2.11BSD, you might just do:
CC      = cc
CFLAGS  = -O   # or -O2 if your system supports it; or just -g

# If you need special socket libs, uncomment or adjust the line below:
# LIBS   = -lsocket -lnsl

all: wget

wget: wget.c
	$(CC) $(CFLAGS) wget.c -o wget $(LIBS)

clean:
	rm -f wget

