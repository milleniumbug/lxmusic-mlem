desktop_in_files=lxmusic.desktop.in
desktop_DATA = $(desktop_in_files:.desktop.in=.desktop)
@INTLTOOL_DESKTOP_RULE@
desktopdir=$(datadir)/applications

icon_DATA=lxmusic.png
icondir=$(datadir)/pixmaps

man_MANS = lxmusic.1

uidir=$(datadir)/lxmusic
# GtkBuilder UI definition files
ui_DATA= \
	lxmusic.ui.glade \
	pref-dlg.ui.glade \
	track-info.ui.glade

EXTRA_DIST = \
	$(desktop_DATA) \
	$(desktop_in_files) \
	$(icon_DATA) \
	$(ui_DATA) \
	$(man_MANS)
