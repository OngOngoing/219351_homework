# examples/f90/Makefile.  Generated from Makefile.in by configure.
all: all-redirect

SHELL           = /bin/bash
top_srcdir      = ../..
srcdir          = .
LIBS            = -lrt -lpthread  
MPILIBNAME      = mpich

MPICHDIR    = ../..
FC          = $(MPICHDIR)/bin/mpif90
# Both FCFLAGS and LDFLAGS have been included in mpif90, set them to NULL here.
FCFLAGS     =
LDFLAGS     =
FC_COMPILE  = $(FC) $(FCFLAGS)
FC_LINK     = $(FC_COMPILE) $(LDFLAGS)

VPATH = .
.SUFFIXES:
.SUFFIXES: .o .f90 .txt 
.f90.o:
	$(FC_COMPILE) -c $<
.f90:
	$(FC_LINK) -o $* $< $(LIBS)

Makefile: ${srcdir}/Makefile.in
	-cd ../../../ && \
	if [ -x config.status ] ; then CONFIG_FILES=examples/f90/Makefile CONFIG_HEADERS= ${SHELL} ./config.status ; fi
clean:
	-rm -f *.o ${srcdir}/*.o pi3f90
	-rm -f pi3f90.exe
	-rm -f *.lo ${srcdir}/*.lo
	-rm -f ${srcdir}/*.bb ${srcdir}/*.bbg ${srcdir}/*.da
distclean: clean
	rm -rf .deps
	-rm -f TAGS
maintainerclean:

all-redirect: pi3f90
pi3f90: pi3f90.o  ../../lib/lib$(MPILIBNAME).a
	$(FC_LINK) -o pi3f90 pi3f90.o $(LIBS)
htmldoc:
mandoc:
latexdoc:
# Dependencies
dependencies:
# End of Dependencies
SOURCES =  pi3f90.f90
tags: TAGS
TAGS:${HEADERS} ${SOURCES}

