package(default_visibility = ["//visibility:public"])

load("//tools:ts_library.bzl", "ts_library")

ts_library(
    name = "sqlx",
    srcs = glob(["**/*.ts"]),
    deps = [
        "//:modules-fix",
        "//common/errors",
        "@npm//@types/moo",
        "@npm//@types/node",
        "@npm//@types/js-beautify",
        "@npm//@types/uuid",
        "@npm//js-beautify",
        "@npm//uuid",
        "@npm//sql-formatter",
        "@npm//moo",
    ],
)
