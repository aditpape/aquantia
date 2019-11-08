#	$NetBSD$

.include "../Makefile.inc"

.PATH:	${S}/dev/pci

KMOD=	if_aq
IOCONF=	if_aq.ioconf

SRCS=	if_aq.c

CPPFLAGS+=	-DINET -DNVLAN=1

.include <bsd.kmodule.mk>
