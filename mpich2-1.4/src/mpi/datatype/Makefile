# This Makefile.in created by simplemake.  Do not edit

# src/mpi/datatype/Makefile.  Generated from Makefile.in by configure.

# --------------------------------------------------------------------------
all: all-redirect

SHELL           = /bin/bash
AR              = ar
AR_FLAGS        = cr
RANLIB          = ranlib
top_builddir    = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4
abs_builddir    = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpi/datatype
master_top_srcdir  = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4
srcdir          = .
abs_srcdir      = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpi/datatype
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
mpi_sources = address.c get_address.c get_count.c \
 get_elements.c pack.c unpack.c pack_size.c status_set_elements.c \
 type_get_name.c \
 type_set_name.c type_size.c type_extent.c type_vector.c type_commit.c \
 type_indexed.c type_hindexed.c type_struct.c \
 type_contiguous.c type_free.c type_hvector.c type_dup.c \
 type_get_envelope.c type_get_contents.c \
 type_ub.c type_lb.c type_get_extent.c type_get_true_extent.c \
 type_match_size.c \
 type_create_struct.c type_create_hindexed.c type_create_hvector.c \
 pack_external.c pack_external_size.c unpack_external.c \
 type_create_indexed_block.c type_create_resized.c \
 type_create_darray.c type_create_subarray.c
win_sources = register_datarep.c
HEADERS = datatype.h
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

.libstamp0 ../../../lib/lib${MPILIBNAME}.a: address.o get_address.o get_count.o get_elements.o \
	pack.o unpack.o pack_size.o status_set_elements.o type_get_name.o type_set_name.o \
	type_size.o type_extent.o type_vector.o type_commit.o type_indexed.o type_hindexed.o \
	type_struct.o type_contiguous.o type_free.o type_hvector.o type_dup.o type_get_envelope.o \
	type_get_contents.o type_ub.o type_lb.o type_get_extent.o type_get_true_extent.o \
	type_match_size.o type_create_struct.o type_create_hindexed.o type_create_hvector.o \
	pack_external.o pack_external_size.o unpack_external.o type_create_indexed_block.o \
	type_create_resized.o type_create_darray.o type_create_subarray.o typeutil.o 
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
.libstamp1 ../../../lib/lib${MPILIBNAME}.la: address.lo get_address.lo get_count.lo \
	get_elements.lo pack.lo unpack.lo pack_size.lo status_set_elements.lo type_get_name.lo \
	type_set_name.lo type_size.lo type_extent.lo type_vector.lo type_commit.lo \
	type_indexed.lo type_hindexed.lo type_struct.lo type_contiguous.lo type_free.lo \
	type_hvector.lo type_dup.lo type_get_envelope.lo type_get_contents.lo type_ub.lo \
	type_lb.lo type_get_extent.lo type_get_true_extent.lo type_match_size.lo \
	type_create_struct.lo type_create_hindexed.lo type_create_hvector.lo pack_external.lo \
	pack_external_size.lo unpack_external.lo type_create_indexed_block.lo \
	type_create_resized.lo type_create_darray.lo type_create_subarray.lo typeutil.lo 
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  AR ${AR_FLAGS} ../../../lib/lib${MPILIBNAME}.la $?" ; \
	else \
	  echo ${AR} ${AR_FLAGS} ../../../lib/lib${MPILIBNAME}.la $? ; \
	fi
	@${AR} ${AR_FLAGS} ../../../lib/lib${MPILIBNAME}.la $?
	date > .libstamp1

# --------------------------------------------------------------------------
.libstamp2: _address.o _get_address.o _get_count.o _get_elements.o _pack.o _unpack.o _pack_size.o \
	_status_set_elements.o _type_get_name.o _type_set_name.o _type_size.o _type_extent.o \
	_type_vector.o _type_commit.o _type_indexed.o _type_hindexed.o _type_struct.o \
	_type_contiguous.o _type_free.o _type_hvector.o _type_dup.o _type_get_envelope.o \
	_type_get_contents.o _type_ub.o _type_lb.o _type_get_extent.o _type_get_true_extent.o \
	_type_match_size.o _type_create_struct.o _type_create_hindexed.o _type_create_hvector.o \
	_pack_external.o _pack_external_size.o _unpack_external.o _type_create_indexed_block.o \
	_type_create_resized.o _type_create_darray.o _type_create_subarray.o 
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
.libstamp3: _address.lo _get_address.lo _get_count.lo _get_elements.lo _pack.lo _unpack.lo _pack_size.lo \
	_status_set_elements.lo _type_get_name.lo _type_set_name.lo _type_size.lo _type_extent.lo \
	_type_vector.lo _type_commit.lo _type_indexed.lo _type_hindexed.lo _type_struct.lo \
	_type_contiguous.lo _type_free.lo _type_hvector.lo _type_dup.lo _type_get_envelope.lo \
	_type_get_contents.lo _type_ub.lo _type_lb.lo _type_get_extent.lo \
	_type_get_true_extent.lo _type_match_size.lo _type_create_struct.lo \
	_type_create_hindexed.lo _type_create_hvector.lo _pack_external.lo _pack_external_size.lo \
	_unpack_external.lo _type_create_indexed_block.lo _type_create_resized.lo \
	_type_create_darray.lo _type_create_subarray.lo 
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  AR ${AR_FLAGS} ../../../lib/lib${PMPILIBNAME}.la $?" ; \
	else \
	  echo ${AR} ${AR_FLAGS} ../../../lib/lib${PMPILIBNAME}.la $? ; \
	fi
	@${AR} ${AR_FLAGS} ../../../lib/lib${PMPILIBNAME}.la $?
	date > .libstamp3
_address.o: address.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/address.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/address.c -o _address.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/address.c -o _address.o
_address.lo: address.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/address.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/address.c -o _address.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/address.c -o _address.lo
_get_address.o: get_address.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/get_address.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/get_address.c -o _get_address.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/get_address.c -o _get_address.o
_get_address.lo: get_address.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/get_address.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/get_address.c -o _get_address.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/get_address.c -o _get_address.lo
_get_count.o: get_count.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/get_count.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/get_count.c -o _get_count.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/get_count.c -o _get_count.o
_get_count.lo: get_count.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/get_count.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/get_count.c -o _get_count.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/get_count.c -o _get_count.lo
_get_elements.o: get_elements.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/get_elements.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/get_elements.c -o _get_elements.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/get_elements.c -o _get_elements.o
_get_elements.lo: get_elements.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/get_elements.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/get_elements.c -o _get_elements.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/get_elements.c -o _get_elements.lo
_pack.o: pack.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/pack.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/pack.c -o _pack.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/pack.c -o _pack.o
_pack.lo: pack.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/pack.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/pack.c -o _pack.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/pack.c -o _pack.lo
_unpack.o: unpack.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/unpack.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/unpack.c -o _unpack.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/unpack.c -o _unpack.o
_unpack.lo: unpack.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/unpack.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/unpack.c -o _unpack.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/unpack.c -o _unpack.lo
_pack_size.o: pack_size.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/pack_size.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/pack_size.c -o _pack_size.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/pack_size.c -o _pack_size.o
_pack_size.lo: pack_size.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/pack_size.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/pack_size.c -o _pack_size.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/pack_size.c -o _pack_size.lo
_status_set_elements.o: status_set_elements.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/status_set_elements.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/status_set_elements.c -o _status_set_elements.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/status_set_elements.c -o _status_set_elements.o
_status_set_elements.lo: status_set_elements.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/status_set_elements.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/status_set_elements.c -o _status_set_elements.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/status_set_elements.c -o _status_set_elements.lo
_type_get_name.o: type_get_name.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_get_name.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_get_name.c -o _type_get_name.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_get_name.c -o _type_get_name.o
_type_get_name.lo: type_get_name.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_get_name.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_get_name.c -o _type_get_name.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_get_name.c -o _type_get_name.lo
_type_set_name.o: type_set_name.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_set_name.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_set_name.c -o _type_set_name.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_set_name.c -o _type_set_name.o
_type_set_name.lo: type_set_name.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_set_name.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_set_name.c -o _type_set_name.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_set_name.c -o _type_set_name.lo
_type_size.o: type_size.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_size.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_size.c -o _type_size.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_size.c -o _type_size.o
_type_size.lo: type_size.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_size.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_size.c -o _type_size.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_size.c -o _type_size.lo
_type_extent.o: type_extent.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_extent.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_extent.c -o _type_extent.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_extent.c -o _type_extent.o
_type_extent.lo: type_extent.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_extent.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_extent.c -o _type_extent.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_extent.c -o _type_extent.lo
_type_vector.o: type_vector.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_vector.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_vector.c -o _type_vector.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_vector.c -o _type_vector.o
_type_vector.lo: type_vector.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_vector.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_vector.c -o _type_vector.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_vector.c -o _type_vector.lo
_type_commit.o: type_commit.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_commit.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_commit.c -o _type_commit.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_commit.c -o _type_commit.o
_type_commit.lo: type_commit.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_commit.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_commit.c -o _type_commit.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_commit.c -o _type_commit.lo
_type_indexed.o: type_indexed.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_indexed.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_indexed.c -o _type_indexed.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_indexed.c -o _type_indexed.o
_type_indexed.lo: type_indexed.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_indexed.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_indexed.c -o _type_indexed.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_indexed.c -o _type_indexed.lo
_type_hindexed.o: type_hindexed.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_hindexed.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_hindexed.c -o _type_hindexed.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_hindexed.c -o _type_hindexed.o
_type_hindexed.lo: type_hindexed.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_hindexed.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_hindexed.c -o _type_hindexed.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_hindexed.c -o _type_hindexed.lo
_type_struct.o: type_struct.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_struct.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_struct.c -o _type_struct.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_struct.c -o _type_struct.o
_type_struct.lo: type_struct.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_struct.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_struct.c -o _type_struct.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_struct.c -o _type_struct.lo
_type_contiguous.o: type_contiguous.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_contiguous.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_contiguous.c -o _type_contiguous.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_contiguous.c -o _type_contiguous.o
_type_contiguous.lo: type_contiguous.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_contiguous.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_contiguous.c -o _type_contiguous.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_contiguous.c -o _type_contiguous.lo
_type_free.o: type_free.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_free.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_free.c -o _type_free.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_free.c -o _type_free.o
_type_free.lo: type_free.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_free.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_free.c -o _type_free.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_free.c -o _type_free.lo
_type_hvector.o: type_hvector.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_hvector.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_hvector.c -o _type_hvector.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_hvector.c -o _type_hvector.o
_type_hvector.lo: type_hvector.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_hvector.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_hvector.c -o _type_hvector.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_hvector.c -o _type_hvector.lo
_type_dup.o: type_dup.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_dup.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_dup.c -o _type_dup.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_dup.c -o _type_dup.o
_type_dup.lo: type_dup.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_dup.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_dup.c -o _type_dup.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_dup.c -o _type_dup.lo
_type_get_envelope.o: type_get_envelope.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_get_envelope.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_get_envelope.c -o _type_get_envelope.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_get_envelope.c -o _type_get_envelope.o
_type_get_envelope.lo: type_get_envelope.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_get_envelope.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_get_envelope.c -o _type_get_envelope.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_get_envelope.c -o _type_get_envelope.lo
_type_get_contents.o: type_get_contents.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_get_contents.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_get_contents.c -o _type_get_contents.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_get_contents.c -o _type_get_contents.o
_type_get_contents.lo: type_get_contents.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_get_contents.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_get_contents.c -o _type_get_contents.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_get_contents.c -o _type_get_contents.lo
_type_ub.o: type_ub.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_ub.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_ub.c -o _type_ub.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_ub.c -o _type_ub.o
_type_ub.lo: type_ub.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_ub.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_ub.c -o _type_ub.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_ub.c -o _type_ub.lo
_type_lb.o: type_lb.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_lb.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_lb.c -o _type_lb.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_lb.c -o _type_lb.o
_type_lb.lo: type_lb.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_lb.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_lb.c -o _type_lb.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_lb.c -o _type_lb.lo
_type_get_extent.o: type_get_extent.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_get_extent.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_get_extent.c -o _type_get_extent.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_get_extent.c -o _type_get_extent.o
_type_get_extent.lo: type_get_extent.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_get_extent.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_get_extent.c -o _type_get_extent.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_get_extent.c -o _type_get_extent.lo
_type_get_true_extent.o: type_get_true_extent.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_get_true_extent.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_get_true_extent.c -o _type_get_true_extent.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_get_true_extent.c -o _type_get_true_extent.o
_type_get_true_extent.lo: type_get_true_extent.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_get_true_extent.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_get_true_extent.c -o _type_get_true_extent.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_get_true_extent.c -o _type_get_true_extent.lo
_type_match_size.o: type_match_size.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_match_size.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_match_size.c -o _type_match_size.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_match_size.c -o _type_match_size.o
_type_match_size.lo: type_match_size.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_match_size.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_match_size.c -o _type_match_size.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_match_size.c -o _type_match_size.lo
_type_create_struct.o: type_create_struct.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_create_struct.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_create_struct.c -o _type_create_struct.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_create_struct.c -o _type_create_struct.o
_type_create_struct.lo: type_create_struct.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_create_struct.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_create_struct.c -o _type_create_struct.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_create_struct.c -o _type_create_struct.lo
_type_create_hindexed.o: type_create_hindexed.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_create_hindexed.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_create_hindexed.c -o _type_create_hindexed.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_create_hindexed.c -o _type_create_hindexed.o
_type_create_hindexed.lo: type_create_hindexed.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_create_hindexed.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_create_hindexed.c -o _type_create_hindexed.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_create_hindexed.c -o _type_create_hindexed.lo
_type_create_hvector.o: type_create_hvector.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_create_hvector.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_create_hvector.c -o _type_create_hvector.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_create_hvector.c -o _type_create_hvector.o
_type_create_hvector.lo: type_create_hvector.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_create_hvector.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_create_hvector.c -o _type_create_hvector.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_create_hvector.c -o _type_create_hvector.lo
_pack_external.o: pack_external.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/pack_external.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/pack_external.c -o _pack_external.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/pack_external.c -o _pack_external.o
_pack_external.lo: pack_external.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/pack_external.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/pack_external.c -o _pack_external.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/pack_external.c -o _pack_external.lo
_pack_external_size.o: pack_external_size.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/pack_external_size.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/pack_external_size.c -o _pack_external_size.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/pack_external_size.c -o _pack_external_size.o
_pack_external_size.lo: pack_external_size.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/pack_external_size.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/pack_external_size.c -o _pack_external_size.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/pack_external_size.c -o _pack_external_size.lo
_unpack_external.o: unpack_external.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/unpack_external.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/unpack_external.c -o _unpack_external.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/unpack_external.c -o _unpack_external.o
_unpack_external.lo: unpack_external.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/unpack_external.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/unpack_external.c -o _unpack_external.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/unpack_external.c -o _unpack_external.lo
_type_create_indexed_block.o: type_create_indexed_block.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_create_indexed_block.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_create_indexed_block.c -o _type_create_indexed_block.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_create_indexed_block.c -o _type_create_indexed_block.o
_type_create_indexed_block.lo: type_create_indexed_block.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_create_indexed_block.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_create_indexed_block.c -o _type_create_indexed_block.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_create_indexed_block.c -o _type_create_indexed_block.lo
_type_create_resized.o: type_create_resized.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_create_resized.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_create_resized.c -o _type_create_resized.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_create_resized.c -o _type_create_resized.o
_type_create_resized.lo: type_create_resized.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_create_resized.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_create_resized.c -o _type_create_resized.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_create_resized.c -o _type_create_resized.lo
_type_create_darray.o: type_create_darray.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_create_darray.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_create_darray.c -o _type_create_darray.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_create_darray.c -o _type_create_darray.o
_type_create_darray.lo: type_create_darray.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_create_darray.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_create_darray.c -o _type_create_darray.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_create_darray.c -o _type_create_darray.lo
_type_create_subarray.o: type_create_subarray.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CC             -D<profiling> ${srcdir}/type_create_subarray.c" ; \
	else \
	  echo $(C_COMPILE) -c  $(srcdir)/type_create_subarray.c -o _type_create_subarray.o ; \
	fi
	@$(C_COMPILE) -c  $(srcdir)/type_create_subarray.c -o _type_create_subarray.o
_type_create_subarray.lo: type_create_subarray.c
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo " CC           -D<profiling> $(srcdir)/type_create_subarray.c" ; \
	else \
	  echo $(C_COMPILE_SHL) -c  $(srcdir)/type_create_subarray.c -o _type_create_subarray.lo ; \
	fi
	@$(C_COMPILE_SHL) -c  $(srcdir)/type_create_subarray.c -o _type_create_subarray.lo
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
SOURCES         =  address.c get_address.c get_count.c get_elements.c pack.c unpack.c pack_size.c \
	status_set_elements.c type_get_name.c type_set_name.c type_size.c type_extent.c \
	type_vector.c type_commit.c type_indexed.c type_hindexed.c type_struct.c \
	type_contiguous.c type_free.c type_hvector.c type_dup.c type_get_envelope.c \
	type_get_contents.c type_ub.c type_lb.c type_get_extent.c type_get_true_extent.c \
	type_match_size.c type_create_struct.c type_create_hindexed.c type_create_hvector.c \
	pack_external.c pack_external_size.c unpack_external.c type_create_indexed_block.c \
	type_create_resized.c type_create_darray.c type_create_subarray.c typeutil.c 
HEADERFILES     = $(HEADERS)
SOURCEFILES     = $(SOURCES)
# --------------------------------------------------------------------------

#

.POSIX:

FORCE_TARGET:

