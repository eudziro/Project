# :%s/Waldo/Wizard Whitebeard/g		/* Just quick remainder */

src_path = ../src/src/
program = zmeika.cc
module1 = zmeika_md1.cc
obj = zmeika_md1.o
binary1 = program1
binary_zmeika = zmeika
cflags = -lglfw -lGLESv2 -lm

program : $(src_path)$(program) $(modules)
	clang++ $(src_path)$(program) -o $(binary_zmeika) $(cflags) \
		&& ./$(binary_zmeika)

modules : $(src_path)$(module1) $(src_path)$(obj)
	clang++ $(src_path)$(module1) -c $(cflags)    
