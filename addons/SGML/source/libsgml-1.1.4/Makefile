# Generated automatically from Makefile.in by configure.
all:
	cd src && make
	cd examples && make

install:
	install -m 755 -o root -g root --directory /usr/local/include/sgml	
	install -m 644 -o root -g root include/DomComment.h /usr/local/include/sgml/DomComment.h
	install -m 644 -o root -g root include/DomDocument.h /usr/local/include/sgml/DomDocument.h
	install -m 644 -o root -g root include/DomElement.h /usr/local/include/sgml/DomElement.h
	install -m 644 -o root -g root include/DomNode.h /usr/local/include/sgml/DomNode.h
	install -m 644 -o root -g root include/DomNodeList.h /usr/local/include/sgml/DomNodeList.h
	install -m 644 -o root -g root include/DomText.h /usr/local/include/sgml/DomText.h
	install -m 644 -o root -g root include/SgmlParser.h /usr/local/include/sgml/SgmlParser.h
	install -m 644 -o root -g root include/SgmlExtensionHtml.h /usr/local/include/sgml/SgmlExtensionHtml.h
	install -m 644 -o root -g root include/SgmlExtensionXml.h /usr/local/include/sgml/SgmlExtensionXml.h
	install -m 644 -o root -g root include/Variant.h /usr/local/include/sgml/Variant.h
	install -m 644 -o root -g root include/libsgml.h /usr/local/include/sgml/libsgml.h
	install -m 644 -o root -g root libsgml.a /usr/local/lib/libsgml.a
	install -m 644 -o root -g root libsgml.so /usr/local/lib/libsgml.so

uninstall:
	rm -rf /usr/local/include/sgml /usr/local/lib/libsgml.a /usr/local/lib/libsgml.so

clean:
	cd src && make clean
	cd examples && make clean

distclean:
	cd src && make distclean
	cd examples && make distclean
	rm -f config.* Makefile	
