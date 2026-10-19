# repokeeper-demo-rust

[![ci](https://github.com/vannt-dev/repokeeper-demo-rust/actions/workflows/ci.yml/badge.svg)](https://github.com/vannt-dev/repokeeper-demo-rust/actions/workflows/ci.yml) [![release](https://img.shields.io/github/v/release/vannt-dev/repokeeper-demo-rust)](https://github.com/vannt-dev/repokeeper-demo-rust/releases) [![repokeeper standard](https://img.shields.io/badge/dynamic/yaml?url=https%3A%2F%2Fraw.githubusercontent.com%2Fvannt-dev%2Frepokeeper-demo-rust%2Fmain%2F.repokeeper.yml&query=%24.standard&label=repokeeper%20standard)](https://github.com/vannt-dev/repokeeper)

A minimal rust project used to pilot [repokeeper](https://github.com/vannt-dev/repokeeper) on the rust stack.

## What repokeeper did here

The CI, the releases and the dependency updates of this repository are set up by
[repokeeper](https://github.com/vannt-dev/repokeeper), and each step went through a pull request:

- [#1](https://github.com/vannt-dev/repokeeper-demo-rust/pull/1): `repokeeper init` applied standard 1.3.0: CI, releases, dependency updates, hooks and the community files
- [#2](https://github.com/vannt-dev/repokeeper-demo-rust/pull/2): the release pull request release-please opened; merging it tagged `v0.1.0` and published the release with its changelog
- [#3](https://github.com/vannt-dev/repokeeper-demo-rust/pull/3): `repokeeper update` moved the repository to standard 1.4.1

The settings are in [`.repokeeper.yml`](.repokeeper.yml); [all pull requests](https://github.com/vannt-dev/repokeeper-demo-rust/pulls?q=is%3Apr) and
[releases](https://github.com/vannt-dev/repokeeper-demo-rust/releases) show the rest.

