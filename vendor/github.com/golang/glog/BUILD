load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "glog.go",
        "glog_file.go",
    ],
    importmap = "github.com/kubernetes-sigs/poseidon/vendor/github.com/golang/glog",
    importpath = "github.com/golang/glog",
    visibility = ["//visibility:public"],
)
