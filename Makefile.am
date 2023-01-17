
SUBDIRS = src icons

desktopdir = $(datadir)/applications
desktop_DATA = gtk-widget-factory.desktop

EXTRA_DIST = $(desktop_DATA) \
	AUTHORS COPYING ChangeLog INSTALL NEWS README autogen.sh \
	gtk-widget-factory.desktop awf.spec

rpm: dist
	rpmbuild --clean -ta ${distdir}.tar.gz
