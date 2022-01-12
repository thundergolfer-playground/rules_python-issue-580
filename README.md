# rules_python-issue-580

https://github.com/bazelbuild/rules_python/issues/580

```
@thundergolfer ➜ /workspaces/rules_python-issue-580 (main ✗) $ bazel run //repro:demo
INFO: Analyzed target //repro:demo (0 packages loaded, 0 targets configured).
INFO: Found 1 target...
Target //repro:demo up-to-date:
  bazel-bin/repro/demo
INFO: Elapsed time: 0.275s, Critical Path: 0.01s
INFO: 1 process: 1 internal.
INFO: Build completed successfully, 1 total action
INFO: Build completed successfully, 1 total action

hello world
Python version: 3.8.8 (default, Mar  1 2021, 01:33:58) 
[Clang 11.0.1 ]
<module 'flask' from '/home/codespace/.cache/bazel/_bazel_codespace/743f644e19a2cb0bc948c7b15b9d5048/execroot/issue_580/bazel-out/k8-fastbuild/bin/repro/demo.runfiles/pypi/pypi__flask/flask/__init__.py'>
<module 'dataclasses' from '/home/codespace/.cache/bazel/_bazel_codespace/743f644e19a2cb0bc948c7b15b9d5048/external/python_interpreter/python/install/lib/python3.8/dataclasses.py'>
```