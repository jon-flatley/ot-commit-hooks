# Opentitan pre-commit hooks

A set of useful pre-commit hooks for running quality checks in the Opentitan
repo. Running these should be enough to avoid linter errors in CI.

## Hooks
- buildifier-fix: Runs `buildifier-fix` on bazel files.
- rustfmt: Runs `rustfmt` on rust files.
- clang-format: Runs `clang-format -i` on C and C++ files.
