# This Makefile.in created by simplemake.  Do not edit

# src/mpix/comm/Makefile.  Generated from Makefile.in by configure.

# --------------------------------------------------------------------------
all: all-redirect

SHELL           = /bin/bash
AR              = ar
AR_FLAGS        = cr
RANLIB          = ranlib
top_builddir    = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4
abs_builddir    = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpix/comm
master_top_srcdir  = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4
srcdir          = .
abs_srcdir      = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpix/comm
top_srcdir      = ../../..
DEFS            = -DHAVE_CONFIG_H -I. -I${srcdir}
CPPFLAGS        =  -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpl/include -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpl/include -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/openpa/src -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/openpa/src -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/ch3/include -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/ch3/include -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/common/datatype -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/common/datatype -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/common/locks -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/common/locks -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/ch3/channels/nemesis/include -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/ch3/channels/nemesis/include -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/ch3/channels/nemesis/nemesis/include -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/ch3/channels/nemesis/nemesis/include -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/ch3/channels/nemesis/nemesis/utils/monitor -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/ch3/channels/nemesis/nemesis/utils/monitor -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/util/wrappers -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/util/wrappers
MAKE            = make
MPILIBNAME      = mpich
PMPILIBNAME     = pmpich

CC              = gcc
CFLAGS          =    -O2 $(MPICH2_MAKE_CFLAGS)
C_COMPILE       = $(CC) $(DEFS) $(INCLUDES) $(CFLAGS) $(CPPFLAGS)
LIBTOOL         = 
CC_SHL          = true
C_COMPILE_SHL   = $(CC_SHL) $(DEFS) $(INCLUDES) $(CFLAGS) $(CPPFLAGS)

VPATH = .
mpi_sources = group_comm.c
INCLUDES = -I../../include -I${top_srcdir}/src/include

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
	-@rm -f *.o ${srcdir}/*.o 
	-@rm -f .libstamp0 .libstamp1 
	-@rm -f *.lo ${srcdir}/*.lo
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
all-redirect: .libstamp0 ../../../lib/lib${MPILIBNAME}.a
	@if [ "none" != "none" ] ; then \
	    ${MAKE} .libstamp1 || exit 1; \
	fi

.libstamp0 ../../../lib/lib${MPILIBNAME}.a: group_comm.o 
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  AR ${AR_FLAGS} ../../../lib/lib${MPILIBNAME}.a $?" ; \
	else \
	  echo ${AR} ${AR_FLAGS} ../../../lib/lib${MPILIBNAME}.a $? ; \
	fi
	@${AR} ${AR_FLAGS} ../../../lib/lib${MPILIBNAME}.a $?
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  RANLIB          lib${MPILIBNAME}.a" ; \
	else \
	  echo ${RANLIB} ../../../lib/lib${MPILIBNAME}.a ; \
	fi
	@${RANLIB} ../../../lib/lib${MPILIBNAME}.a
	date > .libstamp0
.libstamp1 ../../../lib/lib${MPILIBNAME}.la: group_comm.lo 
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  AR ${AR_FLAGS} ../../../lib/lib${MPILIBNAME}.la $?" ; \
	else \
	  echo ${AR} ${AR_FLAGS} ../../../lib/lib${MPILIBNAME}.la $? ; \
	fi
	@${AR} ${AR_FLAGS} ../../../lib/lib${MPILIBNAME}.la $?
	date > .libstamp1
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
SOURCES         =  group_comm.c
HEADERFILES     = $(HEADERS)
SOURCEFILES     = $(SOURCES)
# --------------------------------------------------------------------------




.POSIX:

FORCE_TARGET:

