include ../../Library/GNU.mk

Title=		iftop
Name=		iftop
Version=	1.0
Site=		http://www.ex-parrot.com/pdw/iftop/
Source=		http://www.ex-parrot.com/pdw/iftop/download/$(Name)-$(Version)pre4.tar.gz
License=	GPL

UncompressedName=$(Name)-$(Version)pre4

define test_hook
$(SBinDir)/iftop -h | grep $(Version)
endef
