# SPDX-License-Identifier: Apache-2.0

add_subdirectory_ifdef(CONFIG_ARCMWDT_LIBC      arcmwdt)
add_subdirectory_ifdef(CONFIG_ARMCLANG_STD_LIBC armstdc)
add_subdirectory_ifdef(CONFIG_MINIMAL_LIBC      minimal)
add_subdirectory_ifdef(CONFIG_NEWLIB_LIBC       newlib)
add_subdirectory_ifdef(CONFIG_PICOLIBC          picolibc)
