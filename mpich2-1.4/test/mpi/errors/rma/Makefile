# This Makefile.in created by simplemake.  Do not edit

# errors/rma/Makefile.  Generated from Makefile.in by configure.

# --------------------------------------------------------------------------
all: all-redirect

SHELL           = /bin/bash
abs_builddir    = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/test/mpi/errors/rma
bindir          = ${exec_prefix}/bin
exec_prefix     = ${prefix}
prefix          = /usr/local
srcdir          = .
abs_srcdir      = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/test/mpi/errors/rma
top_srcdir      = ../..
DEFS            = -DHAVE_CONFIG_H -I. -I${srcdir}
CPPFLAGS        = 
LIBS            = -lpthread 
MAKE            = make
CC              = /usr/local/bin/mpicc
CFLAGS          =   $(MPICH2_MAKE_CFLAGS)
C_COMPILE       = $(CC) $(DEFS) $(INCLUDES) $(CFLAGS) $(CPPFLAGS)
C_LINK         = $(CC)
LDFLAGS     =    ../../util/mtest.o 

VPATH = .
INCLUDES = -I../../include -I${top_srcdir}/include

.SUFFIXES:
.SUFFIXES: .o .c 
.c.o:
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC              $<" ; \
	else \
	  echo $(C_COMPILE) -c $< ; \
	fi
	@$(C_COMPILE) -c $<
.c:
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC              $<" ; \
	else \
	  echo $(C_COMPILE) -o $* $< $(LDFLAGS) $(LIBS) ; \
	fi
	@$(C_COMPILE) -o $* $< $(LDFLAGS) $(LIBS)
apply: 
	$(ACTION) $(ACTION_INPUT)
clean: 
	-@rm -f *.o ${srcdir}/*.o winerr winerr2
	-@rm -f winerr.exe winerr2.exe
	-@rm -f core core.[0-9]*
	-@rm -f *.lo ${srcdir}/*.lo
	-@rm -f *.irlog*
distclean:  clean distclean-xxx remove-makefile
distclean-xxx:
	-@rm -f Makefile
	-@rm -rf autom4te*.cache
	-@rm -rf $(DEPS_DIR)
	-@rm -f TAGS
remove-makefile:
	rm -f Makefile
remove-genmakefiles:
	rm -f  Makefile
all-redirect: winerr winerr2

winerr: winerr.o    ../../util/mtest.o
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o winerr winerr.o  ${LIBS}
winerr2: winerr2.o    ../../util/mtest.o
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o winerr2 winerr2.o  ${LIBS}
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
SOURCES         =  winerr.c winerr2.c
HEADERFILES     = $(HEADERS)
SOURCEFILES     = $(SOURCES)
# --------------------------------------------------------------------------


../../util/mtest.o: 
	(cd ../../util && make mtest.o)

testing:
	../../runtests -srcdir=$(srcdir) -tests=testlist \
			-mpiexec=$(bindir)/mpiexec \
		   	-xmlfile=summary.xml

.POSIX:

FORCE_TARGET:

