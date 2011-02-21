#-------------------------------------------------------------------------
#
# Makefile--
#    Makefile for main
#
# IDENTIFICATION
#    src/backend/main/Makefile
#
#-------------------------------------------------------------------------

subdir = src/backend/main
top_builddir = ../../..
include $(top_builddir)/src/Makefile.global

OBJS = main.o

# If "configure --enable-cplusplus" was specified, make list of modules
# which are to be compiled as C++.  The main() function should be compiled as
# C++ to ensure proper initialization of the mixed C/C++ runtime environment.
ifeq ($(enable_cplusplus),yes)
CXXOBJS = main.o
endif

include $(top_srcdir)/src/backend/common.mk
