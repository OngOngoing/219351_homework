# This Makefile.in created by simplemake.  Do not edit

# src/mpi/comm/Makefile.  Generated from Makefile.in by configure.

# --------------------------------------------------------------------------
all: all-redirect

SHELL           = /bin/bash
AR              = ar
AR_FLAGS        = cr
RANLIB          = ranlib
top_builddir    = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4
abs_builddir    = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpi/comm
master_top_srcdir  = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4
srcdir          = .
abs_srcdir      = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpi/comm
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
mpi_sources = comm_compare.c comm_create.c comm_dup.c comm_free.c \
 comm_get_name.c comm_group.c \
 comm_rank.c comm_size.c comm_remote_group.c comm_remote_size.c \
 comm_set_name.c comm_split.c comm_test_inter.c \
 intercomm_create.c intercomm_merge.c 
HEADERS = mpicomm.h
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

.libstamp0 ../../../lib/lib${MPILIBNAME}.a: comm_compare.o comm_create.o comm_dup.o comm_free.o \
	comm_get_name.o comm_group.o comm_rank.o comm_size.o comm_remote_group.o \
	comm_remote_size.o comm_set_name.o comm_split.o comm_test_inter.o intercomm_create.o \
	intercomm_merge.o commutil.o 
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
.libstamp1 ../../../lib/lib${MPILIBNAME}.la: comm_compare.lo comm_create.lo comm_dup.lo \
	comm_free.lo comm_get_name.lo comm_group.lo comm_rank.lo comm_size.lo \
	comm_remote_group.lo comm_remote_size.lo comm_set_name.lo comm_split.lo \
	comm_test_inter.lo intercomm_create.lo intercomm_merge.lo commutil.lo 
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  AR ${AR_FLAGS} ../../../lib/lib${MPILIBNAME}.la $?" ; \
	else \
	  echo ${AR} ${AR_FLAGS} ../../../lib/lib${MPILIBNAME}.la $? ; \
	fi
	@${AR} ${AR_FLAGS} ../../../lib/lib${MPILIBNAME}.la $?
	date > .libstamp1

# --------------------------------------------------------------------------
.libstamp2: _comm_compare.o _comm_create.o _comm_dup.o _comm_free.o _comm_get_name.o _comm_group.o \
	_comm_rank.o _comm_size.o _comm_remote_group.o _comm_remote_size.o _comm_set_name.o \
	_comm_split.o _comm_test_inter.o _intercomm_create.o _intercomm_merge.o 
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
.libstamp3: _comm_compare.lo _comm_create.lo _comm_dup.lo _comm_free.lo _comm_get_name.lo _comm_group.lo \
	_comm_rank.lo _comm_size.lo _comm_remote_group.lo _comm_remote_size.lo _comm_set_name.lo \
	_comm_split.lo _comm_test_inter.lo _intercomm_create.lo _intercomm_merge.lo 
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  AR ${AR_FLAGS} ../../../lib/lib${PMPILIBNAME}.la $?" ; \
	else \
	  echo ${AR} ${AR_FLAGS} ../../../lib/lib${PMPILIBNAME}.la $? ; \
	fi
	@${AR} ${AR_FLAGS} ../../../lib/lib${PMPILIBNAME}.la $?
	date > .libstamp3
_comm_compare.o: comm_compare.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_compare.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_compare.c -o _comm_compare.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_compare.c -o _comm_compare.o
_comm_compare.lo: comm_compare.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_compare.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_compare.c -o _comm_compare.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_compare.c -o _comm_compare.lo
_comm_create.o: comm_create.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_create.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_create.c -o _comm_create.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_create.c -o _comm_create.o
_comm_create.lo: comm_create.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_create.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_create.c -o _comm_create.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_create.c -o _comm_create.lo
_comm_dup.o: comm_dup.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_dup.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_dup.c -o _comm_dup.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_dup.c -o _comm_dup.o
_comm_dup.lo: comm_dup.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_dup.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_dup.c -o _comm_dup.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_dup.c -o _comm_dup.lo
_comm_free.o: comm_free.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_free.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_free.c -o _comm_free.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_free.c -o _comm_free.o
_comm_free.lo: comm_free.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_free.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_free.c -o _comm_free.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_free.c -o _comm_free.lo
_comm_get_name.o: comm_get_name.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_get_name.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_get_name.c -o _comm_get_name.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_get_name.c -o _comm_get_name.o
_comm_get_name.lo: comm_get_name.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_get_name.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_get_name.c -o _comm_get_name.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_get_name.c -o _comm_get_name.lo
_comm_group.o: comm_group.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_group.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_group.c -o _comm_group.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_group.c -o _comm_group.o
_comm_group.lo: comm_group.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_group.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_group.c -o _comm_group.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_group.c -o _comm_group.lo
_comm_rank.o: comm_rank.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_rank.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_rank.c -o _comm_rank.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_rank.c -o _comm_rank.o
_comm_rank.lo: comm_rank.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_rank.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_rank.c -o _comm_rank.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_rank.c -o _comm_rank.lo
_comm_size.o: comm_size.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_size.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_size.c -o _comm_size.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_size.c -o _comm_size.o
_comm_size.lo: comm_size.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_size.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_size.c -o _comm_size.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_size.c -o _comm_size.lo
_comm_remote_group.o: comm_remote_group.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_remote_group.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_remote_group.c -o _comm_remote_group.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_remote_group.c -o _comm_remote_group.o
_comm_remote_group.lo: comm_remote_group.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_remote_group.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_remote_group.c -o _comm_remote_group.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_remote_group.c -o _comm_remote_group.lo
_comm_remote_size.o: comm_remote_size.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_remote_size.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_remote_size.c -o _comm_remote_size.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_remote_size.c -o _comm_remote_size.o
_comm_remote_size.lo: comm_remote_size.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_remote_size.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_remote_size.c -o _comm_remote_size.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_remote_size.c -o _comm_remote_size.lo
_comm_set_name.o: comm_set_name.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_set_name.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_set_name.c -o _comm_set_name.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_set_name.c -o _comm_set_name.o
_comm_set_name.lo: comm_set_name.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_set_name.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_set_name.c -o _comm_set_name.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_set_name.c -o _comm_set_name.lo
_comm_split.o: comm_split.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_split.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_split.c -o _comm_split.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_split.c -o _comm_split.o
_comm_split.lo: comm_split.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_split.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_split.c -o _comm_split.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_split.c -o _comm_split.lo
_comm_test_inter.o: comm_test_inter.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/comm_test_inter.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/comm_test_inter.c -o _comm_test_inter.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/comm_test_inter.c -o _comm_test_inter.o
_comm_test_inter.lo: comm_test_inter.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/comm_test_inter.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/comm_test_inter.c -o _comm_test_inter.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/comm_test_inter.c -o _comm_test_inter.lo
_intercomm_create.o: intercomm_create.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/intercomm_create.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/intercomm_create.c -o _intercomm_create.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/intercomm_create.c -o _intercomm_create.o
_intercomm_create.lo: intercomm_create.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/intercomm_create.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/intercomm_create.c -o _intercomm_create.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/intercomm_create.c -o _intercomm_create.lo
_intercomm_merge.o: intercomm_merge.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/intercomm_merge.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/intercomm_merge.c -o _intercomm_merge.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/intercomm_merge.c -o _intercomm_merge.o
_intercomm_merge.lo: intercomm_merge.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/intercomm_merge.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/intercomm_merge.c -o _intercomm_merge.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/intercomm_merge.c -o _intercomm_merge.lo
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
SOURCES         =  comm_compare.c comm_create.c comm_dup.c comm_free.c comm_get_name.c \
	comm_group.c comm_rank.c comm_size.c comm_remote_group.c comm_remote_size.c \
	comm_set_name.c comm_split.c comm_test_inter.c intercomm_create.c intercomm_merge.c \
	commutil.c 
HEADERFILES     = $(HEADERS)
SOURCEFILES     = $(SOURCES)
# --------------------------------------------------------------------------




.POSIX:

FORCE_TARGET:

