CC          = gcc
AR          = ar cr
RANLIB      = ranlib
LIBNAME     = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/lib/libmpich.a
srcdir      = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpi/romio/adio/ad_bglockless
CC_SHL      = true
SHLIBNAME   = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/lib/libmpich

INCLUDES    = -I. -I${srcdir}/../include -I../include -I../../include  -I${srcdir}/../../../../include -I../../../../include
CFLAGS      =  -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpl/include -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpl/include -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/openpa/src -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/openpa/src -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/ch3/include -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/ch3/include -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/common/datatype -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/common/datatype -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/common/locks -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/common/locks -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/ch3/channels/nemesis/include -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/ch3/channels/nemesis/include -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/ch3/channels/nemesis/nemesis/include -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/ch3/channels/nemesis/nemesis/include -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/ch3/channels/nemesis/nemesis/utils/monitor -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/mpid/ch3/channels/nemesis/nemesis/utils/monitor -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/util/wrappers -I/home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/src/util/wrappers    -O2  -D_LARGEFILE64_SOURCE -D_FILE_OFFSET_BITS=64 -DHAVE_ROMIOCONF_H -D_LARGEFILE64_SOURCE -D_FILE_OFFSET_BITS=64 $(INCLUDES)

top_builddir  = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4
LIBTOOL       = 
C_COMPILE_SHL = $(CC_SHL) 

VPATH=.:${srcdir}

AD_BGLOCKLESS_OBJECTS = ad_bglockless.o ad_bglockless_features.o


default: $(LIBNAME)
	@if [ "none" != "none" ] ; then \
	    $(MAKE) $(SHLIBNAME).la ;\
	fi

.SUFFIXES: $(SUFFIXES) .p .lo

.c.o:
	$(CC) $(CFLAGS) -c $<
.c.lo:
	$(C_COMPILE_SHL) $(CFLAGS) -c $< -o _s$*.o
	@mv -f _s$*.o $*.lo

$(LIBNAME): $(AD_BGLOCKLESS_OBJECTS)
	$(AR) $(LIBNAME) $(AD_BGLOCKLESS_OBJECTS)
	$(RANLIB) $(LIBNAME) 

AD_BGLOCKLESS_LOOBJECTS=$(AD_BGLOCKLESS_OBJECTS:.o=.lo)
$(SHLIBNAME).la: $(AD_BGLOCKLESS_LOOBJECTS)
	$(AR) $(SHLIBNAME).la $(AD_BGLOCKLESS_LOOBJECTS)

coverage:
	-@for file in  ${AD_BGLOCKLESS_OBJECTS:.o=.c} ; do \
		gcov -b -f $$file ; done

clean:
	@rm -f *.o *.lo *.gcno *.gcda *.bb *.bbg
	@rm -f ${srcdir}/*.gcno ${srcdir}/*.gcda 
	@rm -f ${srcdir}/*.bb ${srcdir}/*.bbg
