#
#  MIT License
#  
#  Copyright (c) 2022 Kara
#  
#  Permission is hereby granted, free of charge, to any person obtaining a copy
#  of this software and associated documentation files (the "Software"), to deal
#  in the Software without restriction, including without limitation the rights
#  to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
#  copies of the Software, and to permit persons to whom the Software is
#  furnished to do so, subject to the following conditions:
#  
#  The above copyright notice and this permission notice shall be included in all
#  copies or substantial portions of the Software.
#  
#  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
#  IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
#  FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
#  AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
#  LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
#  OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
#  SOFTWARE.
#

@VALGRIND_CHECK_RULES@
TESTS = test1

check_PROGRAMS = $(top_builddir)/tests/test1
__top_builddir__tests_test1_SOURCES = test1.c
__top_builddir__tests_test1_CFLAGS = -I$(abs_top_srcdir)/src -ggdb
__top_builddir__tests_test1_LDFLAGS = -L$(abs_top_builddir)/bin
__top_builddir__tests_test1_LDADD = -lkrossock -lssl -lcrypto

# TODO: Make unit tests to make sure this thing is being built properly
