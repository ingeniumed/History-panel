## Process this file with automake to produce Makefile.in
## Created by Anjuta

SUBDIRS = src po

history_panel_prototypedocdir = ${prefix}/doc/history_panel_prototype
history_panel_prototypedoc_DATA = \
	README\
	COPYING\
	AUTHORS\
	ChangeLog\
	INSTALL\
	NEWS


INTLTOOL_FILES = intltool-extract.in \
	intltool-merge.in \
	intltool-update.in

EXTRA_DIST = $(history_panel_prototypedoc_DATA) \
	$(INTLTOOL_FILES)

DISTCLEANFILES = intltool-extract \
	intltool-merge \
	intltool-update \
	po/.intltool-merge-cache


# Remove doc directory on uninstall
uninstall-local:
	-rm -r $(history_panel_prototypedocdir)
