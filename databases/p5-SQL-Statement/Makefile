# $OpenBSD: Makefile,v 1.18 2016/03/20 19:56:11 naddy Exp $

COMMENT =	SQL parsing and processing engine

MODULES =	cpan
PKG_ARCH =	*
DISTNAME =	SQL-Statement-1.407
CATEGORIES =	databases

MAINTAINER =	Andrew Fresh <afresh1@openbsd.org>

# perl_5
PERMIT_PACKAGE_CDROM =	Yes

RUN_DEPENDS =	devel/p5-Clone>=0.30 \
		devel/p5-Module-Runtime \
		devel/p5-Params-Util>=1.00

# An optional run dependency but makes one function work
RUN_DEPENDS +=	devel/p5-Math-Base-Convert

TEST_DEPENDS =	devel/p5-Math-Base-Convert \
		devel/p5-Test-Deep

.include <bsd.port.mk>

