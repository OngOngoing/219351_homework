# This Makefile.in created by simplemake.  Do not edit

# errors/cxx/io/Makefile.  Generated from Makefile.in by configure.

# --------------------------------------------------------------------------
all: all-redirect

SHELL           = /bin/bash
abs_builddir    = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/test/mpi/errors/cxx/io
srcdir          = .
abs_srcdir      = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/test/mpi/errors/cxx/io
DEFS            = -DHAVE_CONFIG_H -I. -I${srcdir}
CPPFLAGS        = 
LIBS            = -lpthread 
MAKE            = make
CXX             = /usr/local/bin/mpicxx
CXXFLAGS        = 
CXX_COMPILE     = $(CXX) $(DEFS) $(INCLUDES) $(CXXFLAGS) $(CPPFLAGS)
CXX_LINK       = $(CXX)
LDFLAGS     =    

VPATH = .
INCLUDES = -I../../../include -I${srcdir}/../../../include

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
clean:  clean-local
	-@rm -f *.o ${srcdir}/*.o fileerrretx errgetfilex throwtestfilex
	-@rm -f fileerrretx.exe errgetfilex.exe throwtestfilex.exe
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
all-redirect: fileerrretx errgetfilex throwtestfilex

fileerrretx: fileerrretx.o    
	$(CXX_LINK) $(CXXFLAGS) $(LDFLAGS) -o fileerrretx fileerrretx.o  ${LIBS}
errgetfilex: errgetfilex.o    
	$(CXX_LINK) $(CXXFLAGS) $(LDFLAGS) -o errgetfilex errgetfilex.o  \
	../../../cxx/util/mtest.o ${LIBS} 
throwtestfilex: throwtestfilex.o    
	$(CXX_LINK) $(CXXFLAGS) $(LDFLAGS) -o throwtestfilex throwtestfilex.o  \
	../../../cxx/util/mtest.o ${LIBS} 
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
SOURCES         =  fileerrretx.cxx errgetfilex.cxx throwtestfilex.cxx
HEADERFILES     = $(HEADERS)
SOURCEFILES     = $(SOURCES)
# --------------------------------------------------------------------------


../../../cxx/util/mtest.o: 
	(cd ../../../cxx/util && $(MAKE) mtest.o)

# A special testing target to simplify running just the pt2pt tests
testing:
	../../../runtests -srcdir=$(srcdir) -tests=testlist \
		   -mpiexec=/usr/local/bin/mpiexec \
		   -xmlfile=summary.xml
clean-local:
	-rm -f summary.xml

.POSIX:

FORCE_TARGET:

