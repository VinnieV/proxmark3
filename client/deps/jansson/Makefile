MYSRCPATHS =
MYINCLUDES = -I.
MYCFLAGS = -Wno-unused-function -Wno-cast-align -Wno-bad-function-cast -Wno-switch-enum
MYDEFS = -DHAVE_STDINT_H
MYSRCS = \
	dump.c \
	error.c \
	hashtable.c \
	hashtable_seed.c \
	load.c \
	memory.c \
	pack_unpack.c \
	strbuffer.c \
	strconv.c \
	utf.c \
	value.c

LIB_A = libjansson.a

# Transition: remove old directories and objects
MYCLEANOLDPATH = ../../jansson

include ../../../Makefile.host
