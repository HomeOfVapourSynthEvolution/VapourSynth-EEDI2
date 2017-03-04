warning_flags = -Wall -Wextra -Wshadow -Wno-unused-parameter
common_cflags = -O3 -ffast-math $(MFLAGS) $(warning_flags)
AM_CXXFLAGS = -std=c++11 $(common_cflags)

AM_CPPFLAGS = $(VapourSynth_CFLAGS)

lib_LTLIBRARIES = libeedi2.la

libeedi2_la_SOURCES = EEDI2/EEDI2.cpp

libeedi2_la_LDFLAGS = -no-undefined -avoid-version $(PLUGINLDFLAGS)
