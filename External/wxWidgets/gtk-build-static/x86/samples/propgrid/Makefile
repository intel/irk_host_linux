# =========================================================================
#     This makefile was generated by
#     Bakefile 0.2.9 (http://www.bakefile.org)
#     Do not modify, all changes will be overwritten!
# =========================================================================




prefix = /home/snowedin/Projects/Intel/External/wxWidgets/gtk-build-static-x86
exec_prefix = ${prefix}
datarootdir = ${prefix}/share
INSTALL = /usr/bin/install -c
EXEEXT = 
WINDRES = 
SETFILE = 
NM = nm
BK_DEPS = /home/snowedin/Projects/Intel/External/wxWidgets/gtk-build-static-x86/bk-deps
srcdir = ../../../samples/propgrid
top_srcdir = ../../..
LIBS = -lz -ldl -lm
LDFLAGS_GUI = 
CXX = g++ -m32
CXXFLAGS = -DWX_PRECOMP -pthread -O2 -fno-strict-aliasing -pthread -I/usr/include/gtk-unix-print-2.0 -I/usr/include/gtk-2.0 -I/usr/include/atk-1.0 -I/usr/include/cairo -I/usr/include/gdk-pixbuf-2.0 -I/usr/include/pango-1.0 -I/usr/lib/i386-linux-gnu/gtk-2.0/include -I/usr/include/gio-unix-2.0/ -I/usr/include/freetype2 -I/usr/include/glib-2.0 -I/usr/lib/i386-linux-gnu/glib-2.0/include -I/usr/include/pixman-1 -I/usr/include/libpng12 -I/usr/include/harfbuzz 
CPPFLAGS = -D_FILE_OFFSET_BITS=64 -I${wx_top_builddir}/lib/wx/include/gtk2-unicode-static-3.0 -I${top_srcdir}/include -pthread -I/usr/include/gtk-2.0 -I/usr/lib/i386-linux-gnu/gtk-2.0/include -I/usr/include/atk-1.0 -I/usr/include/cairo -I/usr/include/gdk-pixbuf-2.0 -I/usr/include/pango-1.0 -I/usr/include/gio-unix-2.0/ -I/usr/include/freetype2 -I/usr/include/glib-2.0 -I/usr/lib/i386-linux-gnu/glib-2.0/include -I/usr/include/pixman-1 -I/usr/include/libpng12 -I/usr/include/harfbuzz
LDFLAGS = -pthread   
WX_LIB_FLAVOUR = 
TOOLKIT = GTK
TOOLKIT_LOWERCASE = gtk
TOOLKIT_VERSION = 2
TOOLCHAIN_FULLNAME = gtk2-unicode-static-3.0
EXTRALIBS = -pthread    -lz -ldl -lm 
EXTRALIBS_XML =  -lexpat
EXTRALIBS_GUI = -pthread -lgtk-x11-2.0 -lgdk-x11-2.0 -latk-1.0 -lgio-2.0 -lpangoft2-1.0 -lpangocairo-1.0 -lgdk_pixbuf-2.0 -lcairo -lpango-1.0 -lfontconfig -lgobject-2.0 -lfreetype -lgthread-2.0 -lglib-2.0 -lX11 -lSM -lgtk-x11-2.0 -lgdk-x11-2.0 -latk-1.0 -lgio-2.0 -lpangoft2-1.0 -lpangocairo-1.0 -lgdk_pixbuf-2.0 -lcairo -lpango-1.0 -lfontconfig -lgobject-2.0 -lglib-2.0 -lfreetype -lpng -lz
EXTRALIBS_SDL = 
CXXWARNINGS = -Wall -Wundef -Wunused-parameter -Wno-ctor-dtor-privacy -Woverloaded-virtual
HOST_SUFFIX = 
SAMPLES_RPATH_FLAG = 
wx_top_builddir = /home/snowedin/Projects/Intel/External/wxWidgets/gtk-build-static-x86

### Variables: ###

DESTDIR = 
WX_RELEASE = 3.0
WX_VERSION = $(WX_RELEASE).2
LIBDIRNAME = $(wx_top_builddir)/lib
PROPGRID_CXXFLAGS = -D__WX$(TOOLKIT)__ $(__WXUNIV_DEFINE_p) \
	$(__DEBUG_DEFINE_p) $(__EXCEPTIONS_DEFINE_p) $(__RTTI_DEFINE_p) \
	$(__THREAD_DEFINE_p) -I$(srcdir) $(__DLLFLAG_p) -I$(srcdir)/../../samples \
	$(CXXWARNINGS) $(CPPFLAGS) $(CXXFLAGS)
PROPGRID_OBJECTS =  \
	$(__propgrid_os2_lib_res) \
	propgrid_propgrid.o \
	propgrid_propgrid_minimal.o \
	propgrid_sampleprops.o \
	propgrid_tests.o \
	$(__propgrid___win32rc)

### Conditionally set variables: ###

#CXXC = $(CXX)
CXXC = $(BK_DEPS) $(CXX)
PLUGIN_ADV_EXTRALIBS = $(EXTRALIBS_SDL)
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
__propgrid___mac_setfilecmd = @true
#__propgrid___mac_setfilecmd = \
#	$(SETFILE) -t APPL propgrid$(EXEEXT)
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
COND_PLATFORM_OS2_1___propgrid___os2_emxbindcmd = $(NM) propgrid$(EXEEXT) | if \
	grep -q pmwin.763 ; then emxbind -ep propgrid$(EXEEXT) ; fi
#__propgrid___os2_emxbindcmd = $(COND_PLATFORM_OS2_1___propgrid___os2_emxbindcmd)
#__RCDEFDIR_p_1 = --include-dir \
#	$(LIBDIRNAME)/wx/include/$(TOOLCHAIN_FULLNAME)
#__propgrid_os2_lib_res = \
#	$(top_srcdir)/include/wx/os2/wx.res
#__propgrid_app_Contents_PkgInfo___depname \
#	= propgrid.app/Contents/PkgInfo
#__propgrid_bundle___depname = propgrid_bundle
#____propgrid_BUNDLE_TGT_REF_DEP = \
#	$(__propgrid_app_Contents_PkgInfo___depname)
#____propgrid_BUNDLE_TGT_REF_DEP \
#	= $(__propgrid_app_Contents_PkgInfo___depname)
#____propgrid_BUNDLE_TGT_REF_DEP \
#	= $(__propgrid_app_Contents_PkgInfo___depname)
#____propgrid_BUNDLE_TGT_REF_DEP \
#	= $(__propgrid_app_Contents_PkgInfo___depname)
#____propgrid_BUNDLE_TGT_REF_DEP = \
#	$(__propgrid_app_Contents_PkgInfo___depname)
COND_MONOLITHIC_0___WXLIB_PROPGRID_p = \
	-lwx_$(PORTNAME)$(WXUNIVNAME)$(WXUNICODEFLAG)$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)_propgrid-$(WX_RELEASE)$(HOST_SUFFIX)
__WXLIB_PROPGRID_p = $(COND_MONOLITHIC_0___WXLIB_PROPGRID_p)
COND_MONOLITHIC_0___WXLIB_ADV_p = \
	-lwx_$(PORTNAME)$(WXUNIVNAME)$(WXUNICODEFLAG)$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)_adv-$(WX_RELEASE)$(HOST_SUFFIX)
__WXLIB_ADV_p = $(COND_MONOLITHIC_0___WXLIB_ADV_p)
COND_MONOLITHIC_0___WXLIB_CORE_p = \
	-lwx_$(PORTNAME)$(WXUNIVNAME)$(WXUNICODEFLAG)$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)_core-$(WX_RELEASE)$(HOST_SUFFIX)
__WXLIB_CORE_p = $(COND_MONOLITHIC_0___WXLIB_CORE_p)
COND_MONOLITHIC_0___WXLIB_BASE_p = \
	-lwx_base$(WXBASEPORT)$(WXUNICODEFLAG)$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
__WXLIB_BASE_p = $(COND_MONOLITHIC_0___WXLIB_BASE_p)
#__propgrid___win32rc = propgrid_sample_rc.o
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
#__LIB_PNG_p \
#	= \
#	-lwxpng$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
#__LIB_ZLIB_p = \
#	-lwxzlib$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
COND_wxUSE_REGEX_builtin___LIB_REGEX_p = \
	-lwxregex$(WXUNICODEFLAG)$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)
__LIB_REGEX_p = $(COND_wxUSE_REGEX_builtin___LIB_REGEX_p)
#__LIB_EXPAT_p = \
#	-lwxexpat$(WXDEBUGFLAG)$(WX_LIB_FLAVOUR)-$(WX_RELEASE)$(HOST_SUFFIX)

### Targets: ###

all: propgrid$(EXEEXT) $(__propgrid_bundle___depname)

install: 

uninstall: 

install-strip: install

clean: 
	rm -rf ./.deps ./.pch
	rm -f ./*.o
	rm -f propgrid$(EXEEXT)
	rm -rf propgrid.app

distclean: clean
	rm -f config.cache config.log config.status bk-deps bk-make-pch shared-ld-sh Makefile

propgrid$(EXEEXT): $(PROPGRID_OBJECTS) $(__propgrid___win32rc)
	$(CXX) -o $@ $(PROPGRID_OBJECTS)    -L$(LIBDIRNAME) $(LDFLAGS_GUI) $(SAMPLES_RPATH_FLAG) $(LDFLAGS)  $(__WXLIB_PROPGRID_p)  $(__WXLIB_ADV_p) $(PLUGIN_ADV_EXTRALIBS) $(__WXLIB_CORE_p)  $(__WXLIB_BASE_p)  $(__WXLIB_MONO_p) $(__LIB_SCINTILLA_IF_MONO_p) $(__LIB_TIFF_p) $(__LIB_JPEG_p) $(__LIB_PNG_p)  $(EXTRALIBS_FOR_GUI) $(__LIB_ZLIB_p) $(__LIB_REGEX_p) $(__LIB_EXPAT_p) $(EXTRALIBS_FOR_BASE) $(LIBS)
	
	$(__propgrid___mac_setfilecmd)
	$(__propgrid___os2_emxbindcmd)

#propgrid.app/Contents/PkgInfo: propgrid$(EXEEXT) $(top_srcdir)/src/osx/carbon/Info.plist.in $(top_srcdir)/src/osx/carbon/wxmac.icns
#	mkdir -p propgrid.app/Contents
#	mkdir -p propgrid.app/Contents/MacOS
#	mkdir -p propgrid.app/Contents/Resources
#	
#	
#	sed -e "s/IDENTIFIER/`echo $(srcdir) | sed -e 's,\.\./,,g' | sed -e 's,/,.,g'`/" \
#	-e "s/EXECUTABLE/propgrid/" \
#	-e "s/VERSION/$(WX_VERSION)/" \
#	$(top_srcdir)/src/osx/carbon/Info.plist.in >propgrid.app/Contents/Info.plist
#	
#	
#	/bin/echo "APPL????" >propgrid.app/Contents/PkgInfo
#	
#	
#	ln -f propgrid$(EXEEXT) propgrid.app/Contents/MacOS/propgrid
#	
#	
#	cp -f $(top_srcdir)/src/osx/carbon/wxmac.icns propgrid.app/Contents/Resources/wxmac.icns

#propgrid_bundle: $(____propgrid_BUNDLE_TGT_REF_DEP)

propgrid_propgrid.o: $(srcdir)/propgrid.cpp
	$(CXXC) -c -o $@ $(PROPGRID_CXXFLAGS) $(srcdir)/propgrid.cpp

propgrid_propgrid_minimal.o: $(srcdir)/propgrid_minimal.cpp
	$(CXXC) -c -o $@ $(PROPGRID_CXXFLAGS) $(srcdir)/propgrid_minimal.cpp

propgrid_sampleprops.o: $(srcdir)/sampleprops.cpp
	$(CXXC) -c -o $@ $(PROPGRID_CXXFLAGS) $(srcdir)/sampleprops.cpp

propgrid_tests.o: $(srcdir)/tests.cpp
	$(CXXC) -c -o $@ $(PROPGRID_CXXFLAGS) $(srcdir)/tests.cpp

propgrid_sample_rc.o: $(srcdir)/../sample.rc
	$(WINDRES) -i$< -o$@    --define __WX$(TOOLKIT)__ $(__WXUNIV_DEFINE_p_2) $(__DEBUG_DEFINE_p_2)  $(__EXCEPTIONS_DEFINE_p_2) $(__RTTI_DEFINE_p_2) $(__THREAD_DEFINE_p_2)   --include-dir $(srcdir) $(__DLLFLAG_p_2) --include-dir $(srcdir)/../../samples $(__RCDEFDIR_p_1) --include-dir $(top_srcdir)/include


# Include dependency info, if present:
-include ./.deps/*.d

.PHONY: all install uninstall clean distclean propgrid_bundle
