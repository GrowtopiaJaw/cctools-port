# Makefile.in generated by automake 1.16.2 from Makefile.am.
# libstuff/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994-2020 Free Software Foundation, Inc.

# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.




am__is_gnu_make = { \
  if test -z '$(MAKELEVEL)'; then \
    false; \
  elif test -n '$(MAKE_HOST)'; then \
    true; \
  elif test -n '$(MAKE_VERSION)' && test -n '$(CURDIR)'; then \
    true; \
  else \
    false; \
  fi; \
}
am__make_running_with_option = \
  case $${target_option-} in \
      ?) ;; \
      *) echo "am__make_running_with_option: internal error: invalid" \
              "target option '$${target_option-}' specified" >&2; \
         exit 1;; \
  esac; \
  has_opt=no; \
  sane_makeflags=$$MAKEFLAGS; \
  if $(am__is_gnu_make); then \
    sane_makeflags=$$MFLAGS; \
  else \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        bs=\\; \
        sane_makeflags=`printf '%s\n' "$$MAKEFLAGS" \
          | sed "s/$$bs$$bs[$$bs $$bs	]*//g"`;; \
    esac; \
  fi; \
  skip_next=no; \
  strip_trailopt () \
  { \
    flg=`printf '%s\n' "$$flg" | sed "s/$$1.*$$//"`; \
  }; \
  for flg in $$sane_makeflags; do \
    test $$skip_next = yes && { skip_next=no; continue; }; \
    case $$flg in \
      *=*|--*) continue;; \
        -*I) strip_trailopt 'I'; skip_next=yes;; \
      -*I?*) strip_trailopt 'I';; \
        -*O) strip_trailopt 'O'; skip_next=yes;; \
      -*O?*) strip_trailopt 'O';; \
        -*l) strip_trailopt 'l'; skip_next=yes;; \
      -*l?*) strip_trailopt 'l';; \
      -[dEDm]) skip_next=yes;; \
      -[JT]) skip_next=yes;; \
    esac; \
    case $$flg in \
      *$$target_option*) has_opt=yes; break;; \
    esac; \
  done; \
  test $$has_opt = yes
am__make_dryrun = (target_option=n; $(am__make_running_with_option))
am__make_keepgoing = (target_option=k; $(am__make_running_with_option))
pkgdatadir = $(datadir)/cctools
pkgincludedir = $(includedir)/cctools
pkglibdir = $(libdir)/cctools
pkglibexecdir = $(libexecdir)/cctools
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_triplet = x86_64-pc-linux-gnu
host_triplet = x86_64-pc-linux-gnu
target_triplet = x86_64-pc-linux-gnu
subdir = libstuff
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/m4/libtool.m4 \
	$(top_srcdir)/m4/llvm.m4 $(top_srcdir)/m4/ltoptions.m4 \
	$(top_srcdir)/m4/ltsugar.m4 $(top_srcdir)/m4/ltversion.m4 \
	$(top_srcdir)/m4/lt~obsolete.m4 $(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
DIST_COMMON = $(srcdir)/Makefile.am $(am__DIST_COMMON)
mkinstalldirs = $(install_sh) -d
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
LTLIBRARIES = $(noinst_LTLIBRARIES)
libstuff_la_LIBADD =
am_libstuff_la_OBJECTS = libstuff_la-allocate.lo \
	libstuff_la-apple_version.lo libstuff_la-arch.lo \
	libstuff_la-arch_usage.lo libstuff_la-best_arch.lo \
	libstuff_la-breakout.lo libstuff_la-bytesex.lo \
	libstuff_la-checkout.lo libstuff_la-crc32.lo \
	libstuff_la-dylib_roots.lo libstuff_la-dylib_table.lo \
	libstuff_la-port.lo libstuff_la-errors.lo \
	libstuff_la-execute.lo libstuff_la-fatal_arch.lo \
	libstuff_la-fatals.lo libstuff_la-get_arch_from_host.lo \
	libstuff_la-get_toc_byte_sex.lo \
	libstuff_la-guess_short_name.lo libstuff_la-hash_string.lo \
	libstuff_la-hppa.lo libstuff_la-llvm.lo libstuff_la-lto.lo \
	libstuff_la-macosx_deployment_target.lo libstuff_la-ofile.lo \
	libstuff_la-ofile_error.lo libstuff_la-ofile_get_word.lo \
	libstuff_la-print.lo libstuff_la-reloc.lo libstuff_la-rnd.lo \
	libstuff_la-seg_addr_table.lo \
	libstuff_la-set_arch_flag_name.lo libstuff_la-swap_headers.lo \
	libstuff_la-symbol_list.lo libstuff_la-SymLoc.lo \
	libstuff_la-unix_standard_mode.lo \
	libstuff_la-version_number.lo libstuff_la-writeout.lo \
	libstuff_la-write64.lo libstuff_la-coff_bytesex.lo \
	libstuff_la-args.lo
libstuff_la_OBJECTS = $(am_libstuff_la_OBJECTS)
AM_V_lt = $(am__v_lt_$(V))
am__v_lt_ = $(am__v_lt_$(AM_DEFAULT_VERBOSITY))
am__v_lt_0 = --silent
am__v_lt_1 = 
libstuff_la_LINK = $(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=link $(CCLD) $(libstuff_la_CFLAGS) \
	$(CFLAGS) $(libstuff_la_LDFLAGS) $(LDFLAGS) -o $@
AM_V_P = $(am__v_P_$(V))
am__v_P_ = $(am__v_P_$(AM_DEFAULT_VERBOSITY))
am__v_P_0 = false
am__v_P_1 = :
AM_V_GEN = $(am__v_GEN_$(V))
am__v_GEN_ = $(am__v_GEN_$(AM_DEFAULT_VERBOSITY))
am__v_GEN_0 = @echo "  GEN     " $@;
am__v_GEN_1 = 
AM_V_at = $(am__v_at_$(V))
am__v_at_ = $(am__v_at_$(AM_DEFAULT_VERBOSITY))
am__v_at_0 = @
am__v_at_1 = 
DEFAULT_INCLUDES = -I.
depcomp =
am__maybe_remake_depfiles =
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
LTCOMPILE = $(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) \
	$(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) \
	$(AM_CFLAGS) $(CFLAGS)
AM_V_CC = $(am__v_CC_$(V))
am__v_CC_ = $(am__v_CC_$(AM_DEFAULT_VERBOSITY))
am__v_CC_0 = @echo "  CC      " $@;
am__v_CC_1 = 
CCLD = $(CC)
LINK = $(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=link $(CCLD) $(AM_CFLAGS) $(CFLAGS) \
	$(AM_LDFLAGS) $(LDFLAGS) -o $@
AM_V_CCLD = $(am__v_CCLD_$(V))
am__v_CCLD_ = $(am__v_CCLD_$(AM_DEFAULT_VERBOSITY))
am__v_CCLD_0 = @echo "  CCLD    " $@;
am__v_CCLD_1 = 
SOURCES = $(libstuff_la_SOURCES)
DIST_SOURCES = $(libstuff_la_SOURCES)
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
# Read a list of newline-separated strings from the standard input,
# and print each of them once, without duplicates.  Input order is
# *not* preserved.
am__uniquify_input = $(AWK) '\
  BEGIN { nonempty = 0; } \
  { items[$$0] = 1; nonempty = 1; } \
  END { if (nonempty) { for (i in items) print i; }; } \
'
# Make sure the list of sources is unique.  This is necessary because,
# e.g., the same source file might be shared among _SOURCES variables
# for different programs/libraries.
am__define_uniq_tagged_files = \
  list='$(am__tagged_files)'; \
  unique=`for i in $$list; do \
    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
  done | $(am__uniquify_input)`
ETAGS = etags
CTAGS = ctags
am__DIST_COMMON = $(srcdir)/Makefile.in
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /home/growtopiajaw/cctools-port-master/cctools/missing aclocal-1.16
AMTAR = $${TAR-tar}
AM_DEFAULT_VERBOSITY = 1
AR = ar
ASLIBEXECDIR = ${libexecdir}/as
AUTOCONF = ${SHELL} /home/growtopiajaw/cctools-port-master/cctools/missing autoconf
AUTOHEADER = ${SHELL} /home/growtopiajaw/cctools-port-master/cctools/missing autoheader
AUTOMAKE = ${SHELL} /home/growtopiajaw/cctools-port-master/cctools/missing automake-1.16
AWK = gawk
CC = clang
CCAS = clang
CCASFLAGS = -O3 -isystem /usr/local/include -isystem /usr/pkg/include  -DLD64_VERSION_NUM=530
CFLAGS = -O3 -isystem /usr/local/include -isystem /usr/pkg/include  -DLD64_VERSION_NUM=530
CPP = clang -E
CPPFLAGS = 
CXX = clang++
CXXABI_LIB = -lsupc++
CXXCPP = clang++ -E
CXXFLAGS = -O3 -std=c++0x -isystem /usr/local/include -isystem /usr/pkg/include  -DLD64_VERSION_NUM=530  -fblocks
CYGPATH_W = echo
DEFS = -DPACKAGE_NAME=\"cctools\" -DPACKAGE_TARNAME=\"cctools\" -DPACKAGE_VERSION=\"949.0.1\" -DPACKAGE_STRING=\"cctools\ 949.0.1\" -DPACKAGE_BUGREPORT=\"t.poechtrager@gmail.com\" -DPACKAGE_URL=\"\" -DSTDC_HEADERS=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_STAT_H=1 -DHAVE_STDLIB_H=1 -DHAVE_STRING_H=1 -DHAVE_MEMORY_H=1 -DHAVE_STRINGS_H=1 -DHAVE_INTTYPES_H=1 -DHAVE_STDINT_H=1 -DHAVE_UNISTD_H=1 -DHAVE_DLFCN_H=1 -DLT_OBJDIR=\".libs/\" -DEMULATED_HOST_CPU_TYPE=16777223 -DEMULATED_HOST_CPU_SUBTYPE=3 -D__STDC_LIMIT_MACROS=1 -D__STDC_CONSTANT_MACROS=1 -DHAVE_EXECINFO_H=1 -DHAVE_UUID_UUID_H=1 -DHAVE_UTIMENSAT=1 -DHAVE_BCOPY=1 -DHAVE_BCMP=1 -DHAVE_BZERO=1 -DHAVE_INDEX=1 -DHAVE_RINDEX=1 -DHAVE_STAT_ST_MTIM=1 -DHAVE_CLOCK_GETTIME=1
DLLTOOL = false
DL_LIB = -ldl
DSYMUTIL = 
DUMPBIN = 
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /bin/grep -E
ENDIAN_FLAG = -D__LITTLE_ENDIAN__=1
EXECINFO_LIB = 
EXEEXT = 
FGREP = /bin/grep -F
FTS_LIB = 
GCC_LIB = -lgcc
GREP = /bin/grep
HOST_AR = ar
HOST_RANLIB = ranlib
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
LD = /usr/bin/ld -m elf_x86_64
LDFLAGS =  -L/usr/local/lib -L/usr/pkg/lib -Wl,-rpath,/usr/lib/llvm-6.0/lib,--enable-new-dtags
LIBOBJS = 
LIBS = 
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LIPO = 
LLVM_CONFIG = /usr/bin/llvm-config
LLVM_INCLUDE_DIR = /usr/lib/llvm-6.0/include
LLVM_LIB_DIR = /usr/lib/llvm-6.0/lib
LN_S = ln -s
LTLIBOBJS = 
LTO_DEF = -DLTO_SUPPORT
LTO_LIB = -L/usr/lib/llvm-6.0/lib -lLTO
LTO_RPATH = -Wl,-rpath,/usr/lib/llvm-6.0/lib,--enable-new-dtags
LT_SYS_LIBRARY_PATH = 
MAINT = #
MAKEINFO = ${SHELL} /home/growtopiajaw/cctools-port-master/cctools/missing makeinfo
MANIFEST_TOOL = :
MATH_LIB = -lm
MKDIR_P = /bin/mkdir -p
NM = /usr/bin/nm -B
NMEDIT = 
OBJC = clang
OBJCFLAGS = -O3  -DLD64_VERSION_NUM=530
OBJCWARNINGS = -Wall -Wno-objc-root-class -Wno-deprecated-objc-isa-usage
OBJDUMP = objdump
OBJEXT = o
OTOOL = 
OTOOL64 = 
PACKAGE = cctools
PACKAGE_BUGREPORT = t.poechtrager@gmail.com
PACKAGE_NAME = cctools
PACKAGE_STRING = cctools 949.0.1
PACKAGE_TARNAME = cctools
PACKAGE_URL = 
PACKAGE_VERSION = 949.0.1
PATH_SEPARATOR = :
PROGRAM_PREFIX = 
PTHREAD_FLAGS = -pthread
RANLIB = ranlib
REALLOCF_LIB = 
SED = /bin/sed
SET_MAKE = 
SHELL = /bin/bash
STRIP = strip
TAPI_DEF = 
TAPI_LIB = 
UUID_LIB = -luuid
VERSION = 949.0.1
WARNINGS =  -Wall -Wno-long-long -Wno-import -Wno-format -Wno-deprecated -Wno-unused-variable -Wno-unused-private-field -Wno-unused-function -Wno-invalid-offsetof -Wno-int-conversion -Wno-char-subscripts -Wno-shift-negative-value
XAR_LIB = 
abs_builddir = /home/growtopiajaw/cctools-port-master/cctools/libstuff
abs_srcdir = /home/growtopiajaw/cctools-port-master/cctools/libstuff
abs_top_builddir = /home/growtopiajaw/cctools-port-master/cctools
abs_top_srcdir = /home/growtopiajaw/cctools-port-master/cctools
ac_ct_AR = ar
ac_ct_CC = clang
ac_ct_CXX = 
ac_ct_DUMPBIN = 
ac_ct_OBJC = 
am__leading_dot = .
am__tar = tar --format=ustar -chf - "$$tardir"
am__untar = tar -xf -
bindir = ${exec_prefix}/bin
build = x86_64-pc-linux-gnu
build_alias = 
build_cpu = x86_64
build_os = linux-gnu
build_vendor = pc
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host = x86_64-pc-linux-gnu
host_alias = 
host_cpu = x86_64
host_os = linux-gnu
host_vendor = pc
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /home/growtopiajaw/cctools-port-master/cctools/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = $(MKDIR_P)
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /usr/local
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = ${prefix}/etc
target = x86_64-pc-linux-gnu
target_alias = 
target_cpu = x86_64
target_os = linux-gnu
target_vendor = pc
top_build_prefix = ../
top_builddir = ..
top_srcdir = ..
noinst_LTLIBRARIES = libstuff.la
libstuff_la_CFLAGS = -I$(top_srcdir)/include -I$(top_srcdir)/include/foreign -D__DARWIN_UNIX03 $(WARNINGS) $(LTO_DEF) -DPROGRAM_PREFIX="\"$(PROGRAM_PREFIX)\"" $(ENDIAN_FLAG)
libstuff_la_LDFLAGS = $(FTS_LIB)
libstuff_la_SOURCES = \
	allocate.c  \
	apple_version.c  \
	arch.c  \
	arch_usage.c  \
	best_arch.c  \
	breakout.c  \
	bytesex.c  \
	checkout.c  \
	crc32.c  \
	dylib_roots.c  \
	dylib_table.c  \
	port.c  \
	errors.c  \
	execute.c  \
	fatal_arch.c  \
	fatals.c  \
	get_arch_from_host.c  \
	get_toc_byte_sex.c  \
	guess_short_name.c  \
	hash_string.c  \
	hppa.c  \
	llvm.c  \
	lto.c  \
	macosx_deployment_target.c  \
	ofile.c  \
	ofile_error.c  \
	ofile_get_word.c  \
	print.c  \
	reloc.c  \
	rnd.c  \
	seg_addr_table.c  \
	set_arch_flag_name.c  \
	swap_headers.c  \
	symbol_list.c  \
	SymLoc.c  \
	unix_standard_mode.c  \
	version_number.c  \
	writeout.c \
	write64.c \
	coff_bytesex.c \
	args.c

all: all-am

.SUFFIXES:
.SUFFIXES: .c .lo .o .obj
$(srcdir)/Makefile.in: # $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --gnu --ignore-deps libstuff/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --gnu --ignore-deps libstuff/Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__maybe_remake_depfiles)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__maybe_remake_depfiles);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure: # $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4): # $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):

clean-noinstLTLIBRARIES:
	-test -z "$(noinst_LTLIBRARIES)" || rm -f $(noinst_LTLIBRARIES)
	@list='$(noinst_LTLIBRARIES)'; \
	locs=`for p in $$list; do echo $$p; done | \
	      sed 's|^[^/]*$$|.|; s|/[^/]*$$||; s|$$|/so_locations|' | \
	      sort -u`; \
	test -z "$$locs" || { \
	  echo rm -f $${locs}; \
	  rm -f $${locs}; \
	}

libstuff.la: $(libstuff_la_OBJECTS) $(libstuff_la_DEPENDENCIES) $(EXTRA_libstuff_la_DEPENDENCIES) 
	$(AM_V_CCLD)$(libstuff_la_LINK)  $(libstuff_la_OBJECTS) $(libstuff_la_LIBADD) $(LIBS)

mostlyclean-compile:
	-rm -f *.$(OBJEXT)

distclean-compile:
	-rm -f *.tab.c

.c.o:
	$(AM_V_CC)$(COMPILE) -c -o $@ $<

.c.obj:
	$(AM_V_CC)$(COMPILE) -c -o $@ `$(CYGPATH_W) '$<'`

.c.lo:
	$(AM_V_CC)$(LTCOMPILE) -c -o $@ $<

libstuff_la-allocate.lo: allocate.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-allocate.lo `test -f 'allocate.c' || echo '$(srcdir)/'`allocate.c

libstuff_la-apple_version.lo: apple_version.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-apple_version.lo `test -f 'apple_version.c' || echo '$(srcdir)/'`apple_version.c

libstuff_la-arch.lo: arch.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-arch.lo `test -f 'arch.c' || echo '$(srcdir)/'`arch.c

libstuff_la-arch_usage.lo: arch_usage.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-arch_usage.lo `test -f 'arch_usage.c' || echo '$(srcdir)/'`arch_usage.c

libstuff_la-best_arch.lo: best_arch.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-best_arch.lo `test -f 'best_arch.c' || echo '$(srcdir)/'`best_arch.c

libstuff_la-breakout.lo: breakout.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-breakout.lo `test -f 'breakout.c' || echo '$(srcdir)/'`breakout.c

libstuff_la-bytesex.lo: bytesex.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-bytesex.lo `test -f 'bytesex.c' || echo '$(srcdir)/'`bytesex.c

libstuff_la-checkout.lo: checkout.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-checkout.lo `test -f 'checkout.c' || echo '$(srcdir)/'`checkout.c

libstuff_la-crc32.lo: crc32.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-crc32.lo `test -f 'crc32.c' || echo '$(srcdir)/'`crc32.c

libstuff_la-dylib_roots.lo: dylib_roots.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-dylib_roots.lo `test -f 'dylib_roots.c' || echo '$(srcdir)/'`dylib_roots.c

libstuff_la-dylib_table.lo: dylib_table.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-dylib_table.lo `test -f 'dylib_table.c' || echo '$(srcdir)/'`dylib_table.c

libstuff_la-port.lo: port.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-port.lo `test -f 'port.c' || echo '$(srcdir)/'`port.c

libstuff_la-errors.lo: errors.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-errors.lo `test -f 'errors.c' || echo '$(srcdir)/'`errors.c

libstuff_la-execute.lo: execute.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-execute.lo `test -f 'execute.c' || echo '$(srcdir)/'`execute.c

libstuff_la-fatal_arch.lo: fatal_arch.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-fatal_arch.lo `test -f 'fatal_arch.c' || echo '$(srcdir)/'`fatal_arch.c

libstuff_la-fatals.lo: fatals.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-fatals.lo `test -f 'fatals.c' || echo '$(srcdir)/'`fatals.c

libstuff_la-get_arch_from_host.lo: get_arch_from_host.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-get_arch_from_host.lo `test -f 'get_arch_from_host.c' || echo '$(srcdir)/'`get_arch_from_host.c

libstuff_la-get_toc_byte_sex.lo: get_toc_byte_sex.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-get_toc_byte_sex.lo `test -f 'get_toc_byte_sex.c' || echo '$(srcdir)/'`get_toc_byte_sex.c

libstuff_la-guess_short_name.lo: guess_short_name.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-guess_short_name.lo `test -f 'guess_short_name.c' || echo '$(srcdir)/'`guess_short_name.c

libstuff_la-hash_string.lo: hash_string.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-hash_string.lo `test -f 'hash_string.c' || echo '$(srcdir)/'`hash_string.c

libstuff_la-hppa.lo: hppa.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-hppa.lo `test -f 'hppa.c' || echo '$(srcdir)/'`hppa.c

libstuff_la-llvm.lo: llvm.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-llvm.lo `test -f 'llvm.c' || echo '$(srcdir)/'`llvm.c

libstuff_la-lto.lo: lto.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-lto.lo `test -f 'lto.c' || echo '$(srcdir)/'`lto.c

libstuff_la-macosx_deployment_target.lo: macosx_deployment_target.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-macosx_deployment_target.lo `test -f 'macosx_deployment_target.c' || echo '$(srcdir)/'`macosx_deployment_target.c

libstuff_la-ofile.lo: ofile.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-ofile.lo `test -f 'ofile.c' || echo '$(srcdir)/'`ofile.c

libstuff_la-ofile_error.lo: ofile_error.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-ofile_error.lo `test -f 'ofile_error.c' || echo '$(srcdir)/'`ofile_error.c

libstuff_la-ofile_get_word.lo: ofile_get_word.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-ofile_get_word.lo `test -f 'ofile_get_word.c' || echo '$(srcdir)/'`ofile_get_word.c

libstuff_la-print.lo: print.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-print.lo `test -f 'print.c' || echo '$(srcdir)/'`print.c

libstuff_la-reloc.lo: reloc.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-reloc.lo `test -f 'reloc.c' || echo '$(srcdir)/'`reloc.c

libstuff_la-rnd.lo: rnd.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-rnd.lo `test -f 'rnd.c' || echo '$(srcdir)/'`rnd.c

libstuff_la-seg_addr_table.lo: seg_addr_table.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-seg_addr_table.lo `test -f 'seg_addr_table.c' || echo '$(srcdir)/'`seg_addr_table.c

libstuff_la-set_arch_flag_name.lo: set_arch_flag_name.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-set_arch_flag_name.lo `test -f 'set_arch_flag_name.c' || echo '$(srcdir)/'`set_arch_flag_name.c

libstuff_la-swap_headers.lo: swap_headers.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-swap_headers.lo `test -f 'swap_headers.c' || echo '$(srcdir)/'`swap_headers.c

libstuff_la-symbol_list.lo: symbol_list.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-symbol_list.lo `test -f 'symbol_list.c' || echo '$(srcdir)/'`symbol_list.c

libstuff_la-SymLoc.lo: SymLoc.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-SymLoc.lo `test -f 'SymLoc.c' || echo '$(srcdir)/'`SymLoc.c

libstuff_la-unix_standard_mode.lo: unix_standard_mode.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-unix_standard_mode.lo `test -f 'unix_standard_mode.c' || echo '$(srcdir)/'`unix_standard_mode.c

libstuff_la-version_number.lo: version_number.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-version_number.lo `test -f 'version_number.c' || echo '$(srcdir)/'`version_number.c

libstuff_la-writeout.lo: writeout.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-writeout.lo `test -f 'writeout.c' || echo '$(srcdir)/'`writeout.c

libstuff_la-write64.lo: write64.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-write64.lo `test -f 'write64.c' || echo '$(srcdir)/'`write64.c

libstuff_la-coff_bytesex.lo: coff_bytesex.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-coff_bytesex.lo `test -f 'coff_bytesex.c' || echo '$(srcdir)/'`coff_bytesex.c

libstuff_la-args.lo: args.c
	$(AM_V_CC)$(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(libstuff_la_CFLAGS) $(CFLAGS) -c -o libstuff_la-args.lo `test -f 'args.c' || echo '$(srcdir)/'`args.c

mostlyclean-libtool:
	-rm -f *.lo

clean-libtool:
	-rm -rf .libs _libs

ID: $(am__tagged_files)
	$(am__define_uniq_tagged_files); mkid -fID $$unique
tags: tags-am
TAGS: tags

tags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	set x; \
	here=`pwd`; \
	$(am__define_uniq_tagged_files); \
	shift; \
	if test -z "$(ETAGS_ARGS)$$*$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  if test $$# -gt 0; then \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      "$$@" $$unique; \
	  else \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      $$unique; \
	  fi; \
	fi
ctags: ctags-am

CTAGS: ctags
ctags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	$(am__define_uniq_tagged_files); \
	test -z "$(CTAGS_ARGS)$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$unique

GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && $(am__cd) $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) "$$here"
cscopelist: cscopelist-am

cscopelist-am: $(am__tagged_files)
	list='$(am__tagged_files)'; \
	case "$(srcdir)" in \
	  [\\/]* | ?:[\\/]*) sdir="$(srcdir)" ;; \
	  *) sdir=$(subdir)/$(srcdir) ;; \
	esac; \
	for i in $$list; do \
	  if test -f "$$i"; then \
	    echo "$(subdir)/$$i"; \
	  else \
	    echo "$$sdir/$$i"; \
	  fi; \
	done >> $(top_builddir)/cscope.files

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags

distdir: $(BUILT_SOURCES)
	$(MAKE) $(AM_MAKEFLAGS) distdir-am

distdir-am: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-am
all-am: Makefile $(LTLIBRARIES)
installdirs:
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:

clean-generic:

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-generic clean-libtool clean-noinstLTLIBRARIES \
	mostlyclean-am

distclean: distclean-am
	-rm -f Makefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-tags

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am:

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am:

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man:

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-compile mostlyclean-generic \
	mostlyclean-libtool

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am:

.MAKE: install-am install-strip

.PHONY: CTAGS GTAGS TAGS all all-am check check-am clean clean-generic \
	clean-libtool clean-noinstLTLIBRARIES cscopelist-am ctags \
	ctags-am distclean distclean-compile distclean-generic \
	distclean-libtool distclean-tags distdir dvi dvi-am html \
	html-am info info-am install install-am install-data \
	install-data-am install-dvi install-dvi-am install-exec \
	install-exec-am install-html install-html-am install-info \
	install-info-am install-man install-pdf install-pdf-am \
	install-ps install-ps-am install-strip installcheck \
	installcheck-am installdirs maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-compile \
	mostlyclean-generic mostlyclean-libtool pdf pdf-am ps ps-am \
	tags tags-am uninstall uninstall-am

.PRECIOUS: Makefile


# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
