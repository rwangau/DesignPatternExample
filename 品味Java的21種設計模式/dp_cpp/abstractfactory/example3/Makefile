#############################################################################
# Makefile for building: example3
# Generated by qmake (1.07a) (Qt 3.3.8b) on: Sat Sep  7 01:49:05 2013
# Project:  example3.pro
# Template: app
# Command: $(QMAKE) -o Makefile example3.pro
#############################################################################

####### Compiler, tools and options

CC       = gcc
CXX      = g++
LEX      = flex
YACC     = yacc
CFLAGS   =  -g -Wall -W -O2 
CXXFLAGS =  -g -Wall -W -O2 
LEXFLAGS = 
YACCFLAGS= -d
INCPATH  = 
LINK     = g++
LFLAGS   = 
LIBS     = 
AR       = ar cqs
RANLIB   = 
MOC      = 
UIC      = /usr/share/qt3/bin/uic
QMAKE    = qmake
TAR      = tar -cf
GZIP     = gzip -9f
COPY     = cp -f
COPY_FILE= $(COPY)
COPY_DIR = $(COPY) -r
INSTALL_FILE= $(COPY_FILE)
INSTALL_DIR = $(COPY_DIR)
DEL_FILE = rm -f
SYMLINK  = ln -sf
DEL_DIR  = rmdir
MOVE     = mv -f
CHK_DIR_EXISTS= test -d
MKDIR    = mkdir -p

####### Output directory

OBJECTS_DIR = ./

####### Files

HEADERS = AbstractFactory.h \
		AMDCPU.h \
		Client.h \
		ComputerEngineer.h \
		CPUApi.h \
		GAMainboard.h \
		IntelCPU.h \
		MainboardApi.h \
		MSIMainboard.h \
		Schema1.h \
		Schema2.h
SOURCES = AbstractFactory.cpp \
		AMDCPU.cpp \
		Client.cpp \
		ComputerEngineer.cpp \
		CPUApi.cpp \
		GAMainboard.cpp \
		IntelCPU.cpp \
		MainboardApi.cpp \
		MSIMainboard.cpp \
		Schema1.cpp \
		Schema2.cpp
OBJECTS = AbstractFactory.o \
		AMDCPU.o \
		Client.o \
		ComputerEngineer.o \
		CPUApi.o \
		GAMainboard.o \
		IntelCPU.o \
		MainboardApi.o \
		MSIMainboard.o \
		Schema1.o \
		Schema2.o
FORMS = 
UICDECLS = 
UICIMPLS = 
SRCMOC   = 
OBJMOC = 
DIST	   = example3.pro
QMAKE_TARGET = example3
DESTDIR  = 
TARGET   = example3

first: all
####### Implicit rules

.SUFFIXES: .c .o .cpp .cc .cxx .C

.cpp.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o $@ $<

.cc.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o $@ $<

.cxx.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o $@ $<

.C.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o $@ $<

.c.o:
	$(CC) -c $(CFLAGS) $(INCPATH) -o $@ $<

####### Build rules

all: Makefile $(TARGET)

$(TARGET):  $(UICDECLS) $(OBJECTS) $(OBJMOC)  
	$(LINK) $(LFLAGS) -o $(TARGET) $(OBJECTS) $(OBJMOC) $(OBJCOMP) $(LIBS)

mocables: $(SRCMOC)
uicables: $(UICDECLS) $(UICIMPLS)

$(MOC): 
	( cd $(QTDIR)/src/moc && $(MAKE) )

Makefile: example3.pro  /usr/share/qt3/mkspecs/default/qmake.conf /usr/share/qt3/lib/libqt-mt.prl
	$(QMAKE) -o Makefile example3.pro
qmake: 
	@$(QMAKE) -o Makefile example3.pro

dist: 
	@mkdir -p .tmp/example3 && $(COPY_FILE) --parents $(SOURCES) $(HEADERS) $(FORMS) $(DIST) .tmp/example3/ && ( cd `dirname .tmp/example3` && $(TAR) example3.tar example3 && $(GZIP) example3.tar ) && $(MOVE) `dirname .tmp/example3`/example3.tar.gz . && $(DEL_FILE) -r .tmp/example3

mocclean:

uiclean:

yaccclean:
lexclean:
clean:
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) $(TARGET)


FORCE:

####### Compile

AbstractFactory.o: AbstractFactory.cpp AbstractFactory.h \
		CPUApi.h \
		MainboardApi.h

AMDCPU.o: AMDCPU.cpp AMDCPU.h \
		CPUApi.h

Client.o: Client.cpp Client.h \
		ComputerEngineer.h \
		AbstractFactory.h \
		Schema1.h \
		CPUApi.h \
		MainboardApi.h \
		IntelCPU.h \
		GAMainboard.h

ComputerEngineer.o: ComputerEngineer.cpp ComputerEngineer.h \
		CPUApi.h \
		MainboardApi.h \
		AbstractFactory.h

CPUApi.o: CPUApi.cpp CPUApi.h

GAMainboard.o: GAMainboard.cpp GAMainboard.h \
		MainboardApi.h

IntelCPU.o: IntelCPU.cpp IntelCPU.h \
		CPUApi.h

MainboardApi.o: MainboardApi.cpp MainboardApi.h

MSIMainboard.o: MSIMainboard.cpp MSIMainboard.h \
		MainboardApi.h

Schema1.o: Schema1.cpp Schema1.h \
		AbstractFactory.h \
		CPUApi.h \
		IntelCPU.h \
		MainboardApi.h \
		GAMainboard.h

Schema2.o: Schema2.cpp Schema2.h \
		AbstractFactory.h \
		CPUApi.h \
		AMDCPU.h \
		MainboardApi.h \
		MSIMainboard.h

####### Install

install:  

uninstall:  

