# abseil-cc-example

C++ project with abseil and bazel build

### Usage

```bash
bazel build //:hello
```

### Errors

```log
ERROR: /workspace/j_workspace/BUILD:1:10: no such package '@com_google_absl//abs/strings': BUILD file not found in directory 'abs/strings' of external repository @com_google_absl. Add a BUILD file to a directory to mark it as a package. and referenced by '//:hello'
ERROR: Analysis of target '//:hello' failed; build aborted: Analysis failed
```
