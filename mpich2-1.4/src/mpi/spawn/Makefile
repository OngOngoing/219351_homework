# This Makefile.in created by simplemake.  Do not edit

# src/mpi/spawn/Makefile.  Generated from Makefile.in by configure.

# --------------------------------------------------------------------------
all: all-redirect

SHELL           = /bin/bash
AR              = ar
AR_FLAGS        = cr
RANLIB          = ranlib
top_builddir    = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4
abs_builddir    = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpi/spawn
master_top_srcdir  = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4
srcdir          = .
abs_srcdir      = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpi/spawn
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
mpi_sources = comm_disconnect.c comm_get_parent.c comm_join.c \
 comm_spawn.c comm_spawn_multiple.c \
 lookup_name.c publish_name.c unpublish_name.c \
 open_port.c close_port.c comm_connect.c comm_accept.c 
HEADERS = namepub.h
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
	-@rm -f .libstamp0 .libstamp1 .libstamp2 .libstamp3 
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
	@if [ -n "" ] ; then \
	    ${MAKE} .libstamp2 || exit 1; \
	fi
	@if [ "none" != "none" ] ; then \
	    ${MAKE} .libstamp1 || exit 1; \
	    if [ -n "" ] ; then \
	        ${MAKE} .libstamp3 || exit 1; \
	    fi ; \
	fi

.libstamp0 ../../../lib/lib${MPILIBNAME}.a: comm_disconnect.o comm_get_parent.o comm_join.o \
	comm_spawn.o comm_spawn_multiple.o lookup_name.o publish_name.o unpublish_name.o \
	open_port.o close_port.o comm_connect.o comm_accept.o 
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
.libstamp1 ../../../lib/lib${MPILIBNAME}.la: comm_disconnect.lo comm_get_parent.lo comm_join.lo \
	comm_spawn.lo comm_spawn_multiple.lo lookup_name.lo publish_name.lo unpublish_name.lo \
	open_port.lo close_port.lo comm_connect.lo comm_accept.lo 
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  AR ${AR_FLAGS} ../../../lib/lib${MPILIBNAME}.la $?" ; \
	else \
	  echo ${AR} ${AR_FLAGS} ../../../lib/lib${MPILIBNAME}.la $? ; \
	fi
	@${AR} ${AR_FLAGS} ../../../lib/lib${MPILIBNAME}.la $?
	date > .libstamp1

# --------------------------------------------------------------------------
.libstamp2: _comm_disconnect.o _comm_get_parent.o _comm_join.o _comm_spawn.o _comm_spawn_multiple.o \
	_lookup_name.o _publish_name.o _unpublish_name.o _open_port.o _close_port.o \
	_comm_connect.o _comm_accept.o 
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  AR ${AR_FLAGS} ../../../lib/lib${PMPILIBNAME}.a $?" ; \
	else \
	  echo ${AR} ${AR_FLAGS} ../../../lib/lib${PMPILIBNAME}.a $? ; \
	fi
	@${AR} ${AR_FLAGS} ../../../lib/lib${PMPILIBNAME}.a $?
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  RANLIB          lib${PMPILIBNAME}.a" ; \
	else \
	  echo ${RANLIB} ../../../lib/lib${PMPILIBNAME}.a ; \
	fi
	@${RANLIB} ../../../lib/lib${PMPILIBNAME}.a
	date > .libstamp2
.libstamp3: _comm_disconnect.lo _comm_get_parent.lo _comm_join.lo _comm_spawn.lo _comm_spawn_multiple.lo \
	_lookup_name.lo _publish_name.lo _unpublish_name.lo _open_port.lo _close_port.lo \
	_comm_connect.lo _comm_accept.lo 
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  AR ${AR_FLAGS} ../../../lib/lib${PMPILIBNAME}.la $?" ; \
	else \
	  echo ${AR} ${AR_FLAGS} ../../../lib/lib${PMPILIBNAME}.la $? ; \
	fi
	@${AR} ${AR_FLAGS} ../../../lib/lib${PMPILIBNAME}.la $?
	date > .libstamp3
_comm_disconnect.o: comm_disconnect.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_disconnect.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_disconnect.c -o _comm_disconnect.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_disconnect.c -o _comm_disconnect.o
_comm_disconnect.lo: comm_disconnect.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_disconnect.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_disconnect.c -o _comm_disconnect.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_disconnect.c -o _comm_disconnect.lo
_comm_get_parent.o: comm_get_parent.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_get_parent.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_get_parent.c -o _comm_get_parent.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_get_parent.c -o _comm_get_parent.o
_comm_get_parent.lo: comm_get_parent.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_get_parent.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_get_parent.c -o _comm_get_parent.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_get_parent.c -o _comm_get_parent.lo
_comm_join.o: comm_join.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_join.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_join.c -o _comm_join.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_join.c -o _comm_join.o
_comm_join.lo: comm_join.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_join.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_join.c -o _comm_join.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_join.c -o _comm_join.lo
_comm_spawn.o: comm_spawn.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_spawn.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_spawn.c -o _comm_spawn.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_spawn.c -o _comm_spawn.o
_comm_spawn.lo: comm_spawn.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_spawn.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_spawn.c -o _comm_spawn.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_spawn.c -o _comm_spawn.lo
_comm_spawn_multiple.o: comm_spawn_multiple.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_spawn_multiple.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_spawn_multiple.c -o _comm_spawn_multiple.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_spawn_multiple.c -o _comm_spawn_multiple.o
_comm_spawn_multiple.lo: comm_spawn_multiple.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_spawn_multiple.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_spawn_multiple.c -o _comm_spawn_multiple.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_spawn_multiple.c -o _comm_spawn_multiple.lo
_lookup_name.o: lookup_name.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/lookup_name.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/lookup_name.c -o _lookup_name.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/lookup_name.c -o _lookup_name.o
_lookup_name.lo: lookup_name.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/lookup_name.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/lookup_name.c -o _lookup_name.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/lookup_name.c -o _lookup_name.lo
_publish_name.o: publish_name.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/publish_name.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/publish_name.c -o _publish_name.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/publish_name.c -o _publish_name.o
_publish_name.lo: publish_name.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/publish_name.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/publish_name.c -o _publish_name.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/publish_name.c -o _publish_name.lo
_unpublish_name.o: unpublish_name.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/unpublish_name.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/unpublish_name.c -o _unpublish_name.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/unpublish_name.c -o _unpublish_name.o
_unpublish_name.lo: unpublish_name.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/unpublish_name.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/unpublish_name.c -o _unpublish_name.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/unpublish_name.c -o _unpublish_name.lo
_open_port.o: open_port.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/open_port.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/open_port.c -o _open_port.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/open_port.c -o _open_port.o
_open_port.lo: open_port.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/open_port.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/open_port.c -o _open_port.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/open_port.c -o _open_port.lo
_close_port.o: close_port.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/close_port.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/close_port.c -o _close_port.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/close_port.c -o _close_port.o
_close_port.lo: close_port.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/close_port.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/close_port.c -o _close_port.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/close_port.c -o _close_port.lo
_comm_connect.o: comm_connect.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_connect.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_connect.c -o _comm_connect.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_connect.c -o _comm_connect.o
_comm_connect.lo: comm_connect.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_connect.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_connect.c -o _comm_connect.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_connect.c -o _comm_connect.lo
_comm_accept.o: comm_accept.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_accept.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_accept.c -o _comm_accept.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_accept.c -o _comm_accept.o
_comm_accept.lo: comm_accept.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_accept.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_accept.c -o _comm_accept.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_accept.c -o _comm_accept.lo
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
SOURCES         =  comm_disconnect.c comm_get_parent.c comm_join.c comm_spawn.c \
	comm_spawn_multiple.c lookup_name.c publish_name.c unpublish_name.c open_port.c \
	close_port.c comm_connect.c comm_accept.c 
HEADERFILES     = $(HEADERS)
SOURCEFILES     = $(SOURCES)
# --------------------------------------------------------------------------


 
#

.POSIX:

FORCE_TARGET:

