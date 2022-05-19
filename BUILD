load("@rules_python//python:pip.bzl", "compile_pip_requirements")
load("@rules_python//python:defs.bzl", "py_library")

compile_pip_requirements(
    name = "requirements",
)


py_library(
    name = "lib",
    srcs = [
        "a.py"
    ],
    deps = [
    "@my_deps_testcontainers//:pkg",
  ],
)