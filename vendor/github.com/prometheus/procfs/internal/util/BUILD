load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["parse.go"],
    importmap = "github.com/kubernetes-sigs/poseidon/vendor/github.com/prometheus/procfs/internal/util",
    importpath = "github.com/prometheus/procfs/internal/util",
    visibility = ["//vendor/github.com/prometheus/procfs:__subpackages__"],
)
