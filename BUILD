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
        hdrs = glob(["*.h"]) + ["dict.c"],
    # hdrs = [
    #     "alloc.h",
    #     "async.h",
    #     "dict.h",
    #     "hiredis.h",
    #     "net.h",
    #     "read.h",
    #     "sds.h",
    #     "fmacros.h",
    #     "sockcompat.h",
    #     "win32.h"
    # ],
)