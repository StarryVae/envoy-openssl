load("@rules_cc//cc:defs.bzl", "cc_library")

licenses(["notice"])  # Apache 2

cc_library(
    name = "openssl-lib",
    srcs = [
        "lib/libcrypto.so.1.1",
        "lib/libssl.so.1.1",
    ],
    hdrs = glob(["include/openssl/*.h"]),
    includes = ["include"],
    linkstatic = False,
    visibility = ["//visibility:public"],
)
