# =========================================================================
#     This makefile was generated by
#     Bakefile 0.2.9 (http://www.bakefile.org)
#     Do not modify, all changes will be overwritten!
# =========================================================================




prefix = /usr/local
exec_prefix = ${prefix}
datarootdir = ${prefix}/share
INSTALL = /usr/bin/install -c
EXEEXT = 
WINDRES = 
SETFILE = 
NM = nm
BK_DEPS = /home/liam/Desktop/wxWidgets-3.0.2customfontpatch/gtk-build-staticC/bk-deps
srcdir = ../../../demos/fractal
top_srcdir = ../../..
LIBS = -ldl -lm
LDFLAGS_GUI = 
CXX = g++
CXXFLAGS = -DWX_PRECOMP -pthread -g -O0 -pthread -I/usr/include/gtk-unix-print-2.0 -I/usr/include/gtk-2.0 -I/usr/include/atk-1.0 -I/usr/include/cairo -I/usr/include/gdk-pixbuf-2.0 -I/usr/include/pango-1.0 -I/usr/lib/x86_64-linux-gnu/gtk-2.0/include -I/usr/include/gio-unix-2.0/ -I/usr/include/freetype2 -I/usr/include/glib-2.0 -I/usr/lib/x86_64-linux-gnu/glib-2.0/include -I/usr/include/pixman-1 -I/usr/include/libpng12 -I/usr/include/harfbuzz 
CPPFLAGS = -D_FILE_OFFSET_BITS=64 -I${wx_top_builddir}/lib/wx/include/gtk2-unicode-static-3.0 -I${top_srcdir}/include -pthread -I/usr/include/gtk-2.0 -I/usr/lib/x86_64-linux-gnu/gtk-2.0/include -I/usr/include/atk-1.0 -I/usr/include/cairo -I/usr/include/gdk-pixbuf-2.0 -I/usr/include/pango-1.0 -I/usr/include/gio-unix-2.0/ -I/usr/include/freetype2 -I/usr/include/glib-2.0 -I/usr/lib/x86_64-linux-gnu/glib-2.0/include -I/usr/include/pixman-1 -I/usr/include/libpng12 -I/usr/include/harfbuzz
LDFLAGS = -pthread   
WX_LIB_FLAVOUR = 
TOOLKIT = GTK
TOOLKIT_LOWERCASE = gtk
TOOLKIT_VERSION = 2
TOOLCHAIN_FULLNAME = gtk2-unicode-static-3.0
EXTRALIBS = -pthread    -ldl -lm 
EXTRALIBS_XML = 
EXTRALIBS_GUI = -pthread -lgtk-x11-2.0 -lgdk-x11-2.0 -latk-1.0 -lgio-2.0 -lpangoft2-1.0 -lpangocairo-1.0 -lgdk_pixbuf-2.0 -lcairo -lpango-1.0 -lfontconfig -lgobject-2.0 -lfreetype -lgthread-2.0 -lglib-2.0 -lX11 -lSM -lgtk-x11-2.0 -lgdk-x11-2.0 -latk-1.0 -lgio-2.0 -lpangoft2-1.0 -lpangocairo-1.0 -lgdk_pixbuf-2.0 -lcairo -lpango-1.0 -lfontconfig -lgobject-2.0 -lglib-2.0 -lfreetype
CXXWARNINGS = -Wall -Wundef -Wunused-parameter -Wno-ctor-dtor-privacy -Woverloaded-virtual
HOST_SUFFIX = 
SAMPLES_RPATH_FLAG = 
wx_top_builddir = /home/liam/Desktop/wxWidgets-3.0.2customfontpatch/gtk-build-staticC

### Variables: ###

DESTDIR = 
WX_RELEASE = 3.0
WX_VERSION = $(WX_RELEASE).2
LIBDIRNAME = $(wx_top_builddir)/lib
FRACTAL_CXXFLAGS = -D__WX$(TOOLKIT)__ $(__WXUNIV_DEFINE_p) $(__DEBUG_DEFINE_p) \
	$(__EXCEPTIONS_DEFINE_p) $(__RTTI_DEFINE_p) $(__THREAD_DEFINE_p) \
	-I$(srcdir) $(__DLLFLAG_p) -I$(srcdir)/../../samples $(CXXWARNINGS) \
	$(CPPFLAGS) $(CXXFLAGS)
FRACTAL_OBJECTS =  \
	$(__fractal_os2_lib_res) \
	fractal_fractal.o \
	$(__fractal___win32rc)

### Conditionally set variables: ###

#CXXC = $(CXX)
CXXC = $(BK_DEPS) $(CXX)
#PORTNAME = base
PORTNAME = $(TOOLKIT_LOWERCASE)$(TOOLKIT_VERSION)
#WXBASEPORT = _carbon
#WXDEBUGFLAG = d
WXUNICODEFLAG = u
#WXUNIVNAME = univ
EXTRALIBS_FOR_BASE = $(EXTRALIBS)
#EXTRALIBS_FOR_BASE = $(EXTRALIBS) \
#	$(EXTRALIBS_XML) $(EXTRALIBS_GUI)
EXTRALIBS_FOR_GUI = $(EXTRALIBS_GUI)
#EXTRALIBS_FOR_GUI = 
__fractal___mac_setfilecmd = @true
#__fractal___mac_setfilecmd = \
#	$(SETFILE) -t APPL fractal$(EXEEXT)
#__WXUNIV_DEFINE_p = -D__WXUNIVERSAL__
#__WXUNIV_DEFINE_p_2 = --define __WXUNIVERSAL__
#__DEBUG_DEFINE_p = -DwxDEBUG_LEVEL=0
#__DEBUG_DEFINE_p_2 = --define wxDEBUG_LEVEL=0
#__EXCEPTIONS_DEFINE_p = -DwxNO_EXCEPTIONS
#__EXCEPTIONS_DEFINE_p_2 = --define wxNO_EXCEPTIONS
#__RTTI_DEFINE_p = -DwxNO_RTTI
#__RTTI_DEFINE_p_2 = --define wxNO_RTTI
#__THREAD_DEFINE_p = -DwxNO_THREADS
#__THREAD_DEFINE_p_2 = --define wxNO_THREADS
#__DLLFLAG_p = -DWXUSINGDLL
#__DLLFLAG_p_2 = --define WXUSINGDLL
COND_PLATFORM_OS2_1___fractal___os2_emxbindcmd = $(NM) fractal$(EXEEXT) | if \
	grep -q pmwin.763 ; then emxbind -ep fractal$(EXEEXT) ; fi
#__fractal___os2_emxbindcmd = $(COND_PLATFORM_OS2_1___fractal___os2_emxbindcmd)
#__RCDEFDIR_p_1 = --include-dir \
#	$(LIBDIRNAME)/wx/include/$(TOOLCHAIN_FULLNAME)
#__fractal_os2_lib_res = \
#	$(top_srcdir)/include/wx/os2/wx.res
#__fractal_app_Contents_PkgInfo___depname \
#	= fractal.app/Contents/PkgInfo
#__fractal_bundle___depname = fractal_bundle
#____fractal_BUNDLE_TGT_REF_DEP = \
#	$(__fractal_app_Contents_PkgInfo___depname)
#____fractal_BUNDLE_TGT_REF_DEP \
#	= $(__fractal_app_Contents_PkgInfo___depname)
#____fractal_BUNDLE_TGT_REF_DEP \
#	= $(__fractal_app_Contents_PkgInfo___depname)
#____fractal_BUNDLE_TGT_REF_DEP \
#	= $(__fractal_app_Contents_PkgInfo___depname)
#____fractal_BUNDLE_TGT_REF_DEP = \
#	$(__fractal_app_Contents_PkgInfo___depname)
COND_MONOLITHIC_0___WXLIB_CORE_p = \
	-lwx_$(PORTNAME)$(WXUNIVNAME)$(WXUNICODEFLAG)$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)_core-$(WX_RELEASE)$(HOST_SUFFIX)
__WXLIB_CORE_p = $(COND_MONOLITHIC_0___WXLIB_CORE_p)
COND_MONOLITHIC_0___WXLIB_BASE_p = \
	-lwx_base$(WXBASEPORT)$(WXUNICODEFLAG)$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
__WXLIB_BASE_p = $(COND_MONOLITHIC_0___WXLIB_BASE_p)
#__fractal___win32rc = fractal_fractal_rc.o
COND_MONOLITHIC_1___WXLIB_MONO_p = \
	-lwx_$(PORTNAME)$(WXUNIVNAME)$(WXUNICODEFLAG)$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
#__WXLIB_MONO_p = $(COND_MONOLITHIC_1___WXLIB_MONO_p)
#__LIB_SCINTILLA_IF_MONO_p \
#	= \
#	-lwxscintilla$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
__LIB_TIFF_p \
	= \
	-lwxtiff$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
__LIB_JPEG_p \
	= \
	-lwxjpeg$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
__LIB_PNG_p \
	= \
	-lwxpng$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
__LIB_ZLIB_p = \
	-lwxzlib$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
COND_wxUSE_REGEX_builtin___LIB_REGEX_p = \
	-lwxregex$(WXUNICODEFLAG)$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
__LIB_REGEX_p = $(COND_wxUSE_REGEX_builtin___LIB_REGEX_p)
__LIB_EXPAT_p = \
	-lwxexpat$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)

### Targets: ###

all: fractal$(EXEEXT) $(__fractal_bundle___depname)

install: 

uninstall: 

install-strip: install

clean: 
	rm -rf ./.deps ./.pch
	rm -f ./*.o
	rm -f fractal$(EXEEXT)
	rm -rf fractal.app

distclean: clean
	rm -f config.cache config.log config.status bk-deps bk-make-pch shared-ld-sh Makefile

fractal$(EXEEXT): $(FRACTAL_OBJECTS) $(__fractal___win32rc)
	$(CXX) -o $@ $(FRACTAL_OBJECTS)    -L$(LIBDIRNAME) $(LDFLAGS_GUI) $(SAMPLES_RPATH_FLAG) $(LDFLAGS)  $(__WXLIB_CORE_p)  $(__WXLIB_BASE_p)  $(__WXLIB_MONO_p) $(__LIB_SCINTILLA_IF_MONO_p) $(__LIB_TIFF_p) $(__LIB_JPEG_p) $(__LIB_PNG_p)  $(EXTRALIBS_FOR_GUI) $(__LIB_ZLIB_p) $(__LIB_REGEX_p) $(__LIB_EXPAT_p) $(EXTRALIBS_FOR_BASE) $(LIBS)
	
	$(__fractal___mac_setfilecmd)
	$(__fractal___os2_emxbindcmd)

#fractal.app/Contents/PkgInfo: fractal$(EXEEXT) $(top_srcdir)/src/osx/carbon/Info.plist.in $(top_srcdir)/src/osx/carbon/wxmac.icns
#	mkdir -p fractal.app/Contents
#	mkdir -p fractal.app/Contents/MacOS
#	mkdir -p fractal.app/Contents/Resources
#	
#	
#	sed -e "s/IDENTIFIER/`echo $(srcdir) | sed -e 's,\.\./,,g' | sed -e 's,/,.,g'`/" \
#	-e "s/EXECUTABLE/fractal/" \
#	-e "s/VERSION/$(WX_VERSION)/" \
#	$(top_srcdir)/src/osx/carbon/Info.plist.in >fractal.app/Contents/Info.plist
#	
#	
#	/bin/echo "APPL????" >fractal.app/Contents/PkgInfo
#	
#	
#	ln -f fractal$(EXEEXT) fractal.app/Contents/MacOS/fractal
#	
#	
#	cp -f $(top_srcdir)/src/osx/carbon/wxmac.icns fractal.app/Contents/Resources/wxmac.icns

#fractal_bundle: $(____fractal_BUNDLE_TGT_REF_DEP)

fractal_fractal.o: $(srcdir)/fractal.cpp
	$(CXXC) -c -o $@ $(FRACTAL_CXXFLAGS) $(srcdir)/fractal.cpp

fractal_fractal_rc.o: $(srcdir)/fractal.rc
	$(WINDRES) -i$< -o$@    --define __WX$(TOOLKIT)__ $(__WXUNIV_DEFINE_p_2) $(__DEBUG_DEFINE_p_2)  $(__EXCEPTIONS_DEFINE_p_2) $(__RTTI_DEFINE_p_2) $(__THREAD_DEFINE_p_2)   --include-dir $(srcdir) $(__DLLFLAG_p_2) --include-dir $(srcdir)/../../samples $(__RCDEFDIR_p_1) --include-dir $(top_srcdir)/include


# Include dependency info, if present:
-include ./.deps/*.d

.PHONY: all install uninstall clean distclean fractal_bundle
