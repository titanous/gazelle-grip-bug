# Gazelle import error

```
$ bazel run @com_github_bmeg_grip//:grip
ERROR: /home/jonathan/.cache/bazel/_bazel_jonathan/f698fe3e5b40978113a4dda16637f179/external/com_github_bmeg_grip/gripql/BUILD.bazel:24:11: no such target '@com_github_grpc_ecosystem_grpc_gateway//runtime:runtime': target 'runtime' not declared in package 'runtime' defined by /home/jonathan/.cache/bazel/_bazel_jonathan/f698fe3e5b40978113a4dda16637f179/external/com_github_grpc_ecosystem_grpc_gateway/runtime/BUILD.bazel and referenced by '@com_github_bmeg_grip//gripql:gripql'
ERROR: /home/jonathan/.cache/bazel/_bazel_jonathan/f698fe3e5b40978113a4dda16637f179/external/com_github_bmeg_grip/gripql/BUILD.bazel:24:11: no such target '@com_github_grpc_ecosystem_grpc_gateway//utilities:utilities': target 'utilities' not declared in package 'utilities' defined by /home/jonathan/.cache/bazel/_bazel_jonathan/f698fe3e5b40978113a4dda16637f179/external/com_github_grpc_ecosystem_grpc_gateway/utilities/BUILD.bazel and referenced by '@com_github_bmeg_grip//gripql:gripql'
ERROR: Analysis of target '@com_github_bmeg_grip//:grip' failed; build aborted: Analysis failed
```
