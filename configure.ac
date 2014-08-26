# The MIT License (MIT)
# 
# Copyright (c) 2014 Charles Francoise
# 
# Permission is hereby granted, free of charge, to any person obtaining a copy
# of this software and associated documentation files (the "Software"), to deal
# in the Software without restriction, including without limitation the rights
# to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
# copies of the Software, and to permit persons to whom the Software is
# furnished to do so, subject to the following conditions:
# 
# The above copyright notice and this permission notice shall be included in
# all copies or substantial portions of the Software.
# 
# THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
# IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
# FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
# AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
# LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
# OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
# THE SOFTWARE.



# Initialize project settings
AC_INIT([boilerplate], [1.0], [bug-report@address])
AC_CONFIG_SRCDIR([src/main.c])
AM_INIT_AUTOMAKE([-Wall -Werror])

# Check for programs
AC_PROG_CC
AC_PROG_INSTALL
AM_PROG_AR

# Initialize libtool
LT_INIT

# Check for headers
AC_CHECK_HEADERS([stdio.h])

# Configure output files
AC_CONFIG_HEADER([include/config.h])
AC_CONFIG_FILES([Makefile include/Makefile lib/Makefile src/Makefile tests/Makefile])
AC_CONFIG_MACRO_DIR([m4])

# Output the files
AC_OUTPUT
