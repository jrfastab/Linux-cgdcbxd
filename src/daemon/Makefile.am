INCLUDES = -I $(top_srcdir)/include

if WITH_DAEMON

sbin_PROGRAMS = cgrulesengd cgdcbxd
cgrulesengd_SOURCES = cgrulesengd.c cgrulesengd.h
cgrulesengd_LDADD = $(top_builddir)/src/.libs/libcgroup.la -lrt
cgrulesengd_LDFLAGS = -L$(top_builddir)/src/.libs

cgdcbxd_SOURCES = cgdcbxd.c
cgdcbxd_LDADD = $(top_builddir)/src/.libs/libcgroup.la -lrt -lmnl
cgdcbxd_LDFLAGS = -L$(top_builddir)/src/.libs

endif
