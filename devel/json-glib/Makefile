# $OpenBSD: Makefile,v 1.35 2016/08/11 07:34:30 jasper Exp $

COMMENT=		JSON parser for GLib-based libraries and applications

GNOME_PROJECT=		json-glib
GNOME_VERSION=		1.2.2

SHARED_LIBS +=  json-glib-1.0        5.4      # 200.0

CATEGORIES=		devel

MAINTAINER=		Jasper Lievisse Adriaanse <jasper@openbsd.org>, \
			Antoine Jacoutot <ajacoutot@openbsd.org>

# LGPLv2.1
PERMIT_PACKAGE_CDROM=	Yes

WANTLIB += c ffi gio-2.0 glib-2.0 gmodule-2.0 gobject-2.0 iconv
WANTLIB += intl pcre pthread z

MODULES=		x11/gnome

LIB_DEPENDS=		devel/glib2

MODGNOME_TOOLS += docbook gobject-introspection

CONFIGURE_STYLE=	gnu

.include <bsd.port.mk>
