# This Makefile.in created by simplemake.  Do not edit

# test/basic/Makefile.  Generated from Makefile.in by configure.

# --------------------------------------------------------------------------
all: all-redirect

SHELL           = /bin/bash
abs_builddir    = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/test/basic
srcdir          = .
abs_srcdir      = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/test/basic
DEFS            = -DHAVE_CONFIG_H -I. -I${srcdir}
INCLUDES        = 
LIBS            = -lrt -lpthread  
MAKE            = make
CFLAGS          =    -O2 $(MPICH2_MAKE_CFLAGS)
C_COMPILE       = $(CC) $(DEFS) $(INCLUDES) $(CFLAGS) $(CPPFLAGS)
C_LINK         = $(CC)
CC_SHL          = true
C_COMPILE_SHL   = $(CC_SHL) $(DEFS) $(INCLUDES) $(CFLAGS) $(CPPFLAGS)
LDFLAGS     =    

VPATH = .
prefix          = /usr/local
exec_prefix     = ${prefix}
bindir          = ${exec_prefix}/bin
CC              = $(bindir)/mpicc
CPPFLAGS        = 

.SUFFIXES:
.SUFFIXES: .o .lo .c 
.c.o:
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC              $<" ; \
	else \
	  echo $(C_COMPILE) -c $< ; \
	fi
	@$(C_COMPILE) -c $<
.c.lo:
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC              $<" ; \
	else \
	  echo $(C_COMPILE_SHL) -c $< -o _s$*.o ; \
	echo mv -f _s$*.o $*.lo ; \
	fi
	@$(C_COMPILE_SHL) -c $< -o _s$*.o
	@mv -f _s$*.o $*.lo
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
	-@rm -f *.o ${srcdir}/*.o sr1 srvec sendrecvt srbtest sr
	-@rm -f sr1.exe srvec.exe sendrecvt.exe srbtest.exe sr.exe
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
all-redirect: srbtest sr srvec sendrecvt sr1

sr1: sr1.o   
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o sr1 sr1.o  ${LIBS}
srvec: srvec.o   
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o srvec srvec.o  ${LIBS}
sendrecvt: sendrecvt.o   
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o sendrecvt sendrecvt.o  ${LIBS}
srbtest: srbtest.o   
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o srbtest srbtest.o  ${LIBS}
sr: sr.o   
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o sr sr.o  ${LIBS}
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
SOURCES         =  srbtest.c sr.c srvec.c sendrecvt.c sr1.c
HEADERFILES     = $(HEADERS)
SOURCEFILES     = $(SOURCES)
# --------------------------------------------------------------------------
#
# Replace the value of CC

.POSIX:

FORCE_TARGET:

