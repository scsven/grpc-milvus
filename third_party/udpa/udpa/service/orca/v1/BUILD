load("//bazel:api_build_system.bzl", "udpa_proto_library", "udpa_proto_package")

licenses(["notice"])  # Apache 2

udpa_proto_library(
    name = "orca",
    srcs = ["orca.proto"],
    has_services = True,
    deps = [
        "//udpa/data/orca/v1:orca_load_report",
    ],
)

udpa_proto_package(
    has_services = True,
    deps = [
        "//udpa/data/orca/v1:pkg",
    ],
)
