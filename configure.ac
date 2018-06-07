AC_INIT([declaration-after-statement],[1])

AM_INIT_AUTOMAKE([1.13 foreign])

AC_USE_SYSTEM_EXTENSIONS
AC_PROG_CC_C99

AX_COMPILER_FLAGS([WARN_CFLAGS], [WARN_LDFLAGS], [], [],
                  [-Wno-declaration-after-statement])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
