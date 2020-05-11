TARGET = IrrlichtHelloWorld
OBJS = main.o

LIBS = -lIrrlicht -lSDL -lSDL_gfx -lglut -lGLU -lGL -lpsprtc -lpspgu -lpspgum -lpspvfpu -lpsppower -lpspaudio -lpsphprm -lstdc++ -lm \
	-lSDL_image -lSDL_mixer -lfreetype \
	-lvorbisidec -lvorbis -logg -ljpeg -lpng -lz \

INCDIR =
CFLAGS = -O2 -G0 -Wall -Is7/ -D__PSP__ -Werror=implicit-function-declaration $(LIBS)
CXXFLAGS = $(CFLAGS) -fno-exceptions -fno-rtti
ASFLAGS = $(CFLAGS)

LIBDIR =
LDFLAGS =

EXTRA_TARGETS = EBOOT.PBP
PSP_EBOOT_TITLE = IrrlichtHelloWorld
PSP_FW_VERSION=500

PSPSDK=$(shell psp-config --pspsdk-path)
include $(PSPSDK)/lib/build.mak
