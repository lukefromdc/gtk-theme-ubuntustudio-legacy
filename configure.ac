AC_PREREQ(2.53)

AC_INIT([gtk-theme-ubuntustudio-legacy], [3.22.30], [https://github.com/lukefromdc])

AM_INIT_AUTOMAKE([1.11 no-dist-gzip dist-xz tar-ustar check-news])

# Enable silent build rules by default, requires at least
# Automake-1.11. Disable by either passing --disable-silent-rules to
# configure or passing V=1 to make
m4_ifdef([AM_SILENT_RULES], [AM_SILENT_RULES([yes])])

PKG_PROG_PKG_CONFIG([0.19])

# Workaround to make aclocal get the right flags
AC_SUBST(ACLOCAL_AMFLAGS, "\${ACLOCAL_FLAGS}")

AC_CONFIG_FILES([
Makefile
UbuntuStudio_Legacy/Makefile
UbuntuStudio_Legacy/gtk-2.0/Makefile
UbuntuStudio_Legacy/gtk-2.0/assets/Makefile
UbuntuStudio_Legacy/gtk-2.0/panel/Makefile
UbuntuStudio_Legacy/gtk-3.0/Makefile
UbuntuStudio_Legacy/gtk-3.0/apps/Makefile
UbuntuStudio_Legacy/gtk-3.0/assets/Makefile
UbuntuStudio_Legacy/gtk-3.18/Makefile
UbuntuStudio_Legacy/gtk-3.18/apps/Makefile
UbuntuStudio_Legacy/gtk-3.18/assets/Makefile
UbuntuStudio_Legacy/gtk-3.20/Makefile
UbuntuStudio_Legacy/gtk-3.20/apps/Makefile
UbuntuStudio_Legacy/gtk-3.20/assets/Makefile
UbuntuStudio_Legacy/gtk-3.20/window-controls/Makefile
UbuntuStudio_Legacy/gtk-4.0/Makefile
UbuntuStudio_Legacy/gtk-4.0/apps/Makefile
UbuntuStudio_Legacy/gtk-4.0/assets/Makefile
UbuntuStudio_Legacy/gtk-4.0/window-controls/Makefile
UbuntuStudio_Legacy/metacity-1/Makefile
])

AC_OUTPUT

dnl ==========================================================================
echo "
	gtk-theme-ubuntustudio-legacy-$VERSION:

	Installation prefix:                    ${prefix}

	configuration successfully, now type make
"
