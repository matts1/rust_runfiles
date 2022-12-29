Bazel runfiles support for cargo.

The source code is just copied directly from rules_rust/tools/runfiles/runfiles.rs. Tests are not expected to work. This is mainly useful for:
* Bootstrapping cargo_universe.
* Allowing things depending on runfiles to be built with cargo.
* Allow requesting dependiencies on runfiles in cargo.toml.
* Support IDE code completion.
