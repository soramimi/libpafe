lib_LTLIBRARIES=libpafe.la
libpafe_la_SOURCES = pasori_command.c pasori_command.h \
		     felica_command.c felica_command.h \
		     libpafe.h

pkginclude_HEADERS = libpafe.h pasori_command.h felica_command.h 

libpafe_la_LDFLAGS = $(LIBUSB_LIBS) -version-info 0:8:0
libpafe_la_CFLAGS = $(LIBUSB_CFLAGS)

