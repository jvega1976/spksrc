PKG_NAME = freetype
PKG_VERS = 2.9.1
PKG_EXT = tar.bz2
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = http://download.savannah.gnu.org/releases/freetype
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)

DEPENDS = cross/zlib cross/libpng cross/bzip2

HOMEPAGE = http://www.freetype.org
COMMENT  = FreeType is a freely available software library to render fonts.
LICENSE  = GPLv2

GNU_CONFIGURE = 1

CONFIGURE_ARGS = --enable-freetype-config --with-zlib=yes --with-png=yes --with-bzip2=yes

include ../../mk/spksrc.cross-cc.mk

