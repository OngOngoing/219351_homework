# This Makefile.in created by simplemake.  Do not edit

# f90/comm/Makefile.  Generated from Makefile.in by configure.

# --------------------------------------------------------------------------
all: all-redirect

SHELL           = /bin/bash
abs_builddir    = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/test/mpi/f90/comm
bindir          = ${exec_prefix}/bin
exec_prefix     = ${prefix}
prefix          = /usr/local
srcdir          = .
abs_srcdir      = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/test/mpi/f90/comm
LIBS            = -lpthread 
MAKE            = make
FC               = /usr/local/bin/mpif90
FCFLAGS         = 
FC_COMPILE      = $(FC) $(FCFLAGS) $(FCINCLUDES)
FC_LINK        = $(FC)
LDFLAGS     =    ../util/mtestf90.o 

VPATH = .

.SUFFIXES:
.SUFFIXES: .o .f90 
.f90.o:
	@if [ "x$(VERBOSE)" != "x1" -a "x$(V)" != "x1" ] ; then \
	  echo "  FC              $<" ; \
	else \
	  echo $(FC_COMPILE) -c $< ; \
	fi
	@$(FC_COMPILE) -c $<
.f90:
	$(FC_COMPILE) -o $* $< $(LDFLAGS) $(LIBS)
apply: 
	$(ACTION) $(ACTION_INPUT)
clean: 
	-@rm -f *.o ${srcdir}/*.o commerrf90 commnamef90
	-@rm -f commerrf90.exe commnamef90.exe
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
all-redirect: commnamef90 commerrf90

commerrf90: commerrf90.o    ../util/mtestf90.o
	$(FC_LINK) $(FCFLAGS) $(LDFLAGS) -o commerrf90 commerrf90.o  ${LIBS}
commnamef90: commnamef90.o    ../util/mtestf90.o
	$(FC_LINK) $(FCFLAGS) $(LDFLAGS) -o commnamef90 commnamef90.o  ${LIBS}
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
SOURCES         =  commnamef90.f90 commerrf90.f90
HEADERFILES     = $(HEADERS)
SOURCEFILES     = $(SOURCES)
# --------------------------------------------------------------------------
# This Makefile.sm generated automatically by f77tof90
# from test/mpi/f77/comm/Makefile.sm.  DO NOT EDIT


testing:
	../../runtests -srcdir=$(srcdir) -tests=testlist \
			-mpiexec=$(bindir)/mpiexec \
		   	-xmlfile=summary.xml

../util/mtestf90.o: 
	(cd ../util && $(MAKE) mtestf90.o)

.POSIX:

FORCE_TARGET:

