# This Makefile.in created by simplemake.  Do not edit

# threads/comm/Makefile.  Generated from Makefile.in by configure.

# --------------------------------------------------------------------------
all: all-redirect

SHELL           = /bin/bash
abs_builddir    = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/test/mpi/threads/comm
bindir          = ${exec_prefix}/bin
exec_prefix     = ${prefix}
prefix          = /usr/local
srcdir          = .
abs_srcdir      = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/test/mpi/threads/comm
DEFS            = -DHAVE_CONFIG_H -I. -I${srcdir}
CPPFLAGS        = 
LIBS            = -lpthread 
MAKE            = make
CC              = /usr/local/bin/mpicc
CFLAGS          =   $(MPICH2_MAKE_CFLAGS)
C_COMPILE       = $(CC) $(DEFS) $(INCLUDES) $(CFLAGS) $(CPPFLAGS)
C_LINK         = $(CC)
LDFLAGS     =    ../../util/mtest.o ../util/mtestthread.o

VPATH = .
INCLUDES = -I../../include -I${srcdir}/../../include

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
	-@rm -f *.o ${srcdir}/*.o dup_leak_test ctxdup
	-@rm -f dup_leak_test.exe ctxdup.exe
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
all-redirect: ctxdup dup_leak_test

dup_leak_test: dup_leak_test.o    ../../util/mtest.o ../util/mtestthread.o
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o dup_leak_test dup_leak_test.o  ${LIBS}
ctxdup: ctxdup.o    ../../util/mtest.o ../util/mtestthread.o
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o ctxdup ctxdup.o  -lpthread  ${LIBS}
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
SOURCES         =  ctxdup.c dup_leak_test.c
HEADERFILES     = $(HEADERS)
SOURCEFILES     = $(SOURCES)
# --------------------------------------------------------------------------

# Use extra programs to list programs that should not be built by default.


../../util/mtest.o:
	(cd ../../util && $(MAKE) mtest.o)
../util/mtestthread.o:
	(cd ../util && $(MAKE) mtestthread.o)

# A special testing target to simplify running just the thread comm tests
testing:
	../../runtests -srcdir=$(srcdir) -tests=testlist \
		   -mpiexec=$(bindir)/mpiexec \
		   -xmlfile=summary.xml

.POSIX:

FORCE_TARGET:

