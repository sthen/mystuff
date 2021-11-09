# $OpenBSD$

COMMENT =	wsgi_intercept installs a WSGI application in place of a

MODPY_EGG_VERSION =	1.9.2

DISTNAME =	wsgi_intercept-${MODPY_EGG_VERSION}
PKGNAME =	py-${DISTNAME}

CATEGORIES =	www

HOMEPAGE =	http://pypi.python.org/pypi/wsgi_intercept

# MIT
PERMIT_PACKAGE =	Yes

MODULES =		lang/python

MODPY_PI =		Yes
MODPY_SETUPTOOLS =	Yes

RUN_DEPENDS =		devel/py-six${MODPY_FLAVOR} \
			textproc/py-sphinx${MODPY_FLAVOR}
TEST_DEPENDS =		devel/py-test${MODPY_FLAVOR}>=2.4 \
			pypi/py-httplib2${MODPY_FLAVOR} \
			www/py-requests${MODPY_FLAVOR}>=2.0.1 \
			www/py-urllib3${MODPY_FLAVOR}>=1.11.0

FLAVORS =	python3
FLAVOR ?=	python3

.include <bsd.port.mk>
