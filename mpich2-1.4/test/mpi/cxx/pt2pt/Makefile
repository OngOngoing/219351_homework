# This Makefile.in created by simplemake.  Do not edit

# cxx/pt2pt/Makefile.  Generated from Makefile.in by configure.

# --------------------------------------------------------------------------
all: all-redirect

SHELL           = /bin/bash
abs_builddir    = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/test/mpi/cxx/pt2pt
srcdir          = .
abs_srcdir      = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/test/mpi/cxx/pt2pt
DEFS            = -DHAVE_CONFIG_H -I. -I${srcdir}
CPPFLAGS        = 
LIBS            = -lpthread 
MAKE            = make
CXX             = /usr/local/bin/mpicxx
CXXFLAGS        = 
CXX_COMPILE     = $(CXX) $(DEFS) $(INCLUDES) $(CXXFLAGS) $(CPPFLAGS)
CXX_LINK       = $(CXX)
LDFLAGS     =    ../util/mtest.o 

VPATH = .
INCLUDES = -I../../include -I${srcdir}/../../include

.SUFFIXES:
.SUFFIXES: .o .cxx 
.cxx.o:
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  CXX             $<" ; \
	else \
	  echo $(CXX_COMPILE) -c $< ; \
	fi
	@$(CXX_COMPILE) -c $<
.cxx:
	$(CXX_COMPILE) -o $* $< $(LDFLAGS) $(LIBS)
apply: 
	$(ACTION) $(ACTION_INPUT)
clean: 
	-@rm -f *.o ${srcdir}/*.o sendrecvx bsend1cxx
	-@rm -f sendrecvx.exe bsend1cxx.exe
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
all-redirect: bsend1cxx sendrecvx

sendrecvx: sendrecvx.o    ../util/mtest.o
	$(CXX_LINK) $(CXXFLAGS) $(LDFLAGS) -o sendrecvx sendrecvx.o  ${LIBS}
bsend1cxx: bsend1cxx.o    ../util/mtest.o
	$(CXX_LINK) $(CXXFLAGS) $(LDFLAGS) -o bsend1cxx bsend1cxx.o  ${LIBS}
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
SOURCES         =  bsend1cxx.cxx sendrecvx.cxx
HEADERFILES     = $(HEADERS)
SOURCEFILES     = $(SOURCES)
# --------------------------------------------------------------------------


../util/mtest.o:
	cd ../util && $(MAKE) mtest.o

.POSIX:

FORCE_TARGET:

