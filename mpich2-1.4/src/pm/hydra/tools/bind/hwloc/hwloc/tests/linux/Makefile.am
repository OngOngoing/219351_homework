# Copyright © 2009-2010 INRIA.  All rights reserved.
# Copyright © 2009-2011 Université Bordeaux 1
# Copyright © 2009-2010 Cisco Systems, Inc.  All rights reserved.
# See COPYING in top-level directory.

AM_CFLAGS = $(HWLOC_CFLAGS)
AM_CPPFLAGS = $(HWLOC_CPPFLAGS)
AM_LDFLAGS = $(HWLOC_LDFLAGS)

# Add your expected output file here.
# By default, it shows the output of `lstopo - -v'.
sysfs_outputs = \
		2amd64-2n.output \
		2ps3-2t.output \
		4ia64-4s.output \
		4ppc-4c.output \
		256ppc-8n8s4t.output \
		256ppc-8n8s4t-nocache.output \
		256ppc-8n8s4t-nosys.output \
		32ppc-4n4c2c.output \
		8amd64-4n2c.output  \
		8em64t-4c2t.output \
		8em64t-2s2ca2c.output \
		8em64t-2s4c-heterogeneous.output \
		8ia64-2n2s2c.output \
		8ia64-2s2c2t.output \
		8ia64-4s2c.output \
		16amd64-8n2c.output \
		16amd64-8n2c-cpusets.output \
		16amd64-8n2c-cpusets.xml.output \
		16amd64-8n2c-cpusets_noadmin.output \
		16em64t-4s2c2t.output \
		16em64t-4s2c2t-offlines.output \
		16em64t-4s2c2t-offlines.xml.output \
		16em64t-4s2c2t-offlines_noadmin.output \
		16em64t-4s2c2t_ncaches.output \
		16em64t-4s2c2t_merge.output \
		16em64t-4s2c2t.xml.output \
		16em64t-2m4c2t.output \
		16ia64-8n2s.output \
		48amd64-4d2n6c-sparse.output \
		64fake-4n2s2ca2c2t.output \
		96em64t-4n4d3ca2co.output \
		128ia64-17n4s2c.output \
		256ia64-64n2s2c.output \
		4qs22-2s2t.output \
		2s390-2c.output \
		1alpha.output

# Each output `xyz.output' must have a corresponding tarball `xyz.tar.bz2'
# or a corresponding `xyz.source' specifying which tarball to use
sysfs_tarballs = \
		2amd64-2n.tar.bz2 \
		2ps3-2t.tar.bz2 \
		4ia64-4s.tar.bz2 \
		4ppc-4c.tar.bz2 \
		256ppc-8n8s4t.tar.bz2 \
		256ppc-8n8s4t-nocache.source \
		256ppc-8n8s4t-nosys.source \
		32ppc-4n4c2c.tar.bz2 \
		8amd64-4n2c.tar.bz2  \
		8em64t-4c2t.tar.bz2 \
		8em64t-2s2ca2c.tar.bz2 \
		8em64t-2s4c-heterogeneous.tar.bz2 \
		8ia64-2n2s2c.tar.bz2 \
		8ia64-2s2c2t.tar.bz2 \
		8ia64-4s2c.tar.bz2 \
		16amd64-8n2c.tar.bz2 \
		16amd64-8n2c-cpusets.tar.bz2 \
		16amd64-8n2c-cpusets.xml.source \
		16amd64-8n2c-cpusets_noadmin.source \
		16em64t-4s2c2t.tar.bz2 \
		16em64t-4s2c2t-offlines.tar.bz2 \
		16em64t-4s2c2t-offlines.xml.source \
		16em64t-4s2c2t-offlines_noadmin.source \
		16em64t-2m4c2t.tar.bz2 \
		16em64t-4s2c2t_merge.source \
		16em64t-4s2c2t_ncaches.source \
		16em64t-4s2c2t.xml.source \
		16ia64-8n2s.tar.bz2 \
		48amd64-4d2n6c-sparse.tar.bz2 \
		64fake-4n2s2ca2c2t.tar.bz2 \
		96em64t-4n4d3ca2co.tar.bz2 \
		128ia64-17n4s2c.tar.bz2 \
		256ia64-64n2s2c.tar.bz2 \
		4qs22-2s2t.tar.bz2 \
		2s390-2c.tar.bz2 \
		1alpha.tar.bz2

# Each `xyz.output' may have a corresponding exclude `xyz.exclude'
sysfs_excludes = \
		256ppc-8n8s4t-nocache.exclude \
		256ppc-8n8s4t-nosys.exclude

# Each output `xyz.output' may have a corresponding `xyz.options'
# file modifying the behavior of lstopo
sysfs_options = \
		16amd64-8n2c-cpusets.xml.options \
		16amd64-8n2c-cpusets_noadmin.options \
		16em64t-4s2c2t-offlines.xml.options \
		16em64t-4s2c2t-offlines_noadmin.options \
		16em64t-4s2c2t_ncaches.options \
		16em64t-4s2c2t_merge.options \
		16em64t-4s2c2t.xml.options

if HWLOC_BUILD_TESTS
if HWLOC_HAVE_OPENAT
if HWLOC_HAVE_BUNZIPP
TESTS = $(sysfs_outputs)
endif HWLOC_HAVE_BUNZIPP
endif HWLOC_HAVE_OPENAT
endif HWLOC_BUILD_TESTS

EXTRA_DIST = $(sysfs_outputs) $(sysfs_tarballs) $(sysfs_excludes) $(sysfs_options)

TESTS_ENVIRONMENT = $(builddir)/test-topology.sh


bin_SCRIPTS = hwloc-gather-topology

install-exec-hook:
	$(SED) -e 's/abs_top_builddir\/utils/bindir/' -e '/abs_top_builddir/d' -i $(DESTDIR)$(bindir)/hwloc-gather-topology

SUBDIRS = gather
