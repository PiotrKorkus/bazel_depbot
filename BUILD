load("@score_tooling//:defs.bzl", "setup_starpls", "use_format_targets")
load("@score_docs_as_code//:docs.bzl", "docs")

setup_starpls(
    name = "starpls_server",
    visibility = ["//visibility:public"],
)

# Add target for formatting checks
use_format_targets()

docs(
    source_dir = "docs",
)