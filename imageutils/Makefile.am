AM_CXXFLAGS = -Wall -I../imagesource/ -I../pixbufthumbnail -I../profilemanager -I../support $(LCMS_CFLAGS) $(GTK2_CFLAGS) ${PNM_CFLAGS}

noinst_LTLIBRARIES = libimageutils.la

libimageutils_la_SOURCES =	\
	maskpixbuf.cpp	\
	maskpixbuf.h	\
	rotatepixbuf.cpp	\
	rotatepixbuf.h	\
	\
	imagesink.h \
	\
	cachedimage.cpp	\
	cachedimage.h	\
	\
	imagesaver.h	\
	jpegsaver.cpp	\
	jpegsaver.h	\
	tiffsaver.cpp	\
	tiffsaver.h

libimageutils_la_LDFLAGS = -static

