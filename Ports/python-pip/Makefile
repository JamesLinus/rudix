include ../../Library/Python.mk

Title=		Python pip
Name=		python-pip
Version=	8.1.0
Site=		https://pypi.python.org/pypi/pip/
Source=		https://pypi.python.org/packages/source/p/pip/pip-$(Version).tar.gz
License=	MIT

ReadMeFile=	$(SourceDir)/README.rst
LicenseFile=	$(SourceDir)/LICENSE.txt

UncompressedName=pip-$(Version)

define test_hook
$(BinDir)/pip --version | grep $(Version)
endef
