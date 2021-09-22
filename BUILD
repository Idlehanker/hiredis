licenses(["notice"])  # 3-clause BSD

package(default_visibility = ["//visibility:public"])

load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
    name = "hiredis",
    srcs = [
        "dict.c",
        "alloc.c",
        "async.c",
        "hiredis.c",
        "net.c",
        "read.c",
        "sds.c"
        ],
        # hdrs = glob(["*.h"]) + ["dict.c"],
    hdrs = [
        "async.h",
        "sds.h",
        "alloc.h",
        "dict.h",
        "read.h",
        "sockcompat.h",
        "net.h",
        "hiredis.h",
        "sdsalloc.h",
        "hiredis_ssl.h",
        "win32.h",
        "async_private.h",
        "adapters/macosx.h",
        "adapters/ivykis.h",
        "adapters/libevent.h",
        "adapters/libev.h",
        "adapters/qt.h",
        "adapters/glib.h",
        "adapters/libuv.h",
        "adapters/ae.h",
        "fmacros.h",
        "dict.c",
    ],
)