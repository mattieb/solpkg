# $Id: Makefile,v 1.3 2002/08/12 17:43:54 zigg Exp $

include ../GLOBAL/global.mk

PACKAGE_NAME=		gcc
PACKAGE_VERSION=	2.95.3

PACKAGE_DESCRIPTION=	GNU Compiler Collection
PACKAGE_CATEGORY=	utility

DIST_FILES=		${PACKAGE_NAME}-${PACKAGE_VERSION}.tar.gz

CONFIGURE_ARGS+=	--enable-shared --enable-static --enable-threads
CONFIGURE_ENV=

BUILD_MAKE_ARGS=	CFLAGS='-O' LIBCFLAGS='-g -O2' \
			LIBCXXFLAGS='-g -O2 -fno-implicit-templates'
BUILD_MAKE_ENV=
BUILD_MAKE_TARGET=	bootstrap-lean

