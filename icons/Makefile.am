# vim:set noet ts=4:
#
# ibus-anthy - The Anthy engine for IBus
#
# Copyright (c) 2007-2008 Peng Huang <shawn.p.huang@gmail.com>
# Copyright (c) 2010-2012 Takao Fujiwara <takao.fujiwara1@gmail.com>
# Copyright (c) 2007-2012 Red Hat, Inc.
#
# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2, or (at your option)
# any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program; if not, write to the Free Software
# Foundation, Inc., 675 Mass Ave, Cambridge, MA 02139, USA.

if HAVE_PRIVATE_PNG
pngicons_DATA = \
	ibus-anthy.png \
	$(NULL)
else
pngicons_files = \
	ibus-anthy.png \
	$(NULL)
endif

pngiconsdir = $(pkgdatadir)/icons

scalable_icons_DATA = \
	ibus-anthy.svg \
	$(NULL)

# You need to run gtk-update-icon-cache after the icons are installed.
scalable_iconsdir = $(datadir)/icons/hicolor/scalable/apps/

EXTRA_DIST = \
	$(pngicons_DATA) \
	$(pngicons_files) \
	$(scalable_icons_DATA) \
	$(NULL)
