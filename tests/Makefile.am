AM_CPPFLAGS = -I$(top_srcdir)/include
LDADD = $(top_builddir)/lib/libboilerplate.la

check_PROGRAMS = test test_fail
test_SOURCES = test.c
test_fail_SOURCES = test_fail.c

TESTS = $(check_PROGRAMS)
XFAIL_TESTS = test_fail