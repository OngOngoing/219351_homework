# This Makefile.in created by simplemake.  Do not edit

# topo/Makefile.  Generated from Makefile.in by configure.

# --------------------------------------------------------------------------
all: all-redirect

SHELL           = /bin/bash
abs_builddir    = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/test/mpi/topo
srcdir          = .
abs_srcdir      = /home/kumamon/Documents/paruj/219351_Webapp_homework/mpich2-1.4/test/mpi/topo
DEFS            = -DHAVE_CONFIG_H -I. -I${srcdir}
CPPFLAGS        = 
LIBS            = -lpthread 
MAKE            = make
CC              = /usr/local/bin/mpicc
CFLAGS          =   $(MPICH2_MAKE_CFLAGS)
C_COMPILE       = $(CC) $(DEFS) $(INCLUDES) $(CFLAGS) $(CPPFLAGS)
C_LINK         = $(CC)
LDFLAGS     =    ../util/mtest.o 

VPATH = .
INCLUDES = -I../include -I${srcdir}/../include

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
	-@rm -f *.o ${srcdir}/*.o cartzero graphcr topodup graphcr2 cartsuball cartmap1 graphmap1 dims2 cartshift1 cartcreates topotest distgraph1 dims1 dgraph_unwgt
	-@rm -f cartzero.exe graphcr.exe topodup.exe graphcr2.exe cartsuball.exe cartmap1.exe graphmap1.exe dims2.exe cartshift1.exe cartcreates.exe topotest.exe distgraph1.exe dims1.exe dgraph_unwgt.exe
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
all-redirect: cartmap1 cartzero cartshift1 cartsuball cartcreates dims1 dims2 graphmap1 topotest\
	 topodup graphcr graphcr2 distgraph1 dgraph_unwgt

cartzero: cartzero.o    ../util/mtest.o
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o cartzero cartzero.o  ${LIBS}
graphcr: graphcr.o    ../util/mtest.o
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o graphcr graphcr.o  ${LIBS}
topodup: topodup.o    ../util/mtest.o
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o topodup topodup.o  ${LIBS}
graphcr2: graphcr2.o    ../util/mtest.o
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o graphcr2 graphcr2.o  ${LIBS}
cartsuball: cartsuball.o    ../util/mtest.o
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o cartsuball cartsuball.o  ${LIBS}
cartmap1: cartmap1.o    ../util/mtest.o
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o cartmap1 cartmap1.o  ${LIBS}
graphmap1: graphmap1.o    ../util/mtest.o
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o graphmap1 graphmap1.o  ${LIBS}
dims2: dims2.o    ../util/mtest.o
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o dims2 dims2.o  ${LIBS}
cartshift1: cartshift1.o    ../util/mtest.o
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o cartshift1 cartshift1.o  ${LIBS}
cartcreates: cartcreates.o    ../util/mtest.o
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o cartcreates cartcreates.o  ${LIBS}
topotest: topotest.o    ../util/mtest.o
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o topotest topotest.o  ${LIBS}
distgraph1: distgraph1.o    ../util/mtest.o
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o distgraph1 distgraph1.o  ${LIBS}
dims1: dims1.o    ../util/mtest.o
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o dims1 dims1.o  ${LIBS}
dgraph_unwgt: dgraph_unwgt.o    ../util/mtest.o
	$(C_LINK) $(CFLAGS) $(LDFLAGS) -o dgraph_unwgt dgraph_unwgt.o  ${LIBS}
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
# --------------------------------------------------------------------------
SOURCES         =  cartmap1.c cartzero.c cartshift1.c cartsuball.c cartcreates.c dims1.c dims2.c \
	graphmap1.c topotest.c topodup.c graphcr.c graphcr2.c distgraph1.c dgraph_unwgt.c 
HEADERFILES     = $(HEADERS)
SOURCEFILES     = $(SOURCES)
# --------------------------------------------------------------------------


../util/mtest.o: 
	(cd ../util && make mtest.o)

testing:
	../runtests -srcdir=$(srcdir) -tests=testlist \
			-mpiexec=/usr/local/bin/mpiexec \
		   	-xmlfile=summary.xml

.POSIX:

FORCE_TARGET:

