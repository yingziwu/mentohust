bin_PROGRAMS = mentohust

AUTOMAKE_OPTIONS = foreign subdir-objects
sysconfdir = /etc

dist_sysconf_DATA = mentohust.conf

mentohust_SOURCES = myini.c md5.c mycheck.c dlfunc.c myfunc.c mystate.c myconfig.c mentohust.c

mentohust_SOURCES += i18n.h types.h myini.h md5.h mycheck.h dlfunc.h myfunc.h mystate.h myconfig.h

mentohust_SOURCES += V3/md5forvz.c V3/ripemd.c V3/sha1.c V3/tiger.c V3/v3sub.c V3/whirlpool.c

mentohust_SOURCES += V3/md5forvz.h V3/ripemd.h V3/sha1.h V3/tiger.h V3/v3sub.h V3/whirlpool.h

mentohust_LDADD = $(LDADD)

