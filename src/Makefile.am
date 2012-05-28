## Process this file with automake to produce Makefile.in

## Created by Anjuta



AM_CPPFLAGS = \
	-DPACKAGE_LOCALE_DIR=\""$(localedir)"\" \
	-DPACKAGE_SRC_DIR=\""$(srcdir)"\" \
	-DPACKAGE_DATA_DIR=\""$(pkgdatadir)"\" \
	$(HISTORY_PANEL_PROTOTYPE_CFLAGS)

AM_CFLAGS =\
	 -Wall\
	 -g

bin_PROGRAMS = history_panel_prototype

history_panel_prototype_SOURCES = \
	main.c

history_panel_prototype_LDFLAGS = \
	-Wl,--export-dynamic

history_panel_prototype_LDADD = $(HISTORY_PANEL_PROTOTYPE_LIBS)


