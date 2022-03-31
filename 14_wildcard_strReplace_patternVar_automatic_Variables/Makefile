lib1_SRCs := $(wildcard lib1/*.c)
lib2_SRCs := $(wildcard lib2/*.c)

# replace ".c" with ".o" :

lib1_OBJs := $(lib1_SRCs:.c=.o)
lib2_OBJs := $(lib2_SRCs:.c=.o)

# replace ".c" with "" :

lib3_OBJs := $(lib2_SRCs:.c=)


.PHONY: all
all: $(lib1_OBJs) $(lib2_OBJs)

%.o:%.c

	gcc $< -o $@


clean:

	rm $(lib1_OBJs) $(lib2_OBJs)
