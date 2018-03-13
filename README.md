# docker-circleci-amazonlinux-rust [![Build Status][travis.svg]][travis] [![Docker Status][docker.svg]][docker]

A Rust development environment on Amazon Linux. Useful for Lambda build contexts.

Available on Docker Hub at [`naftulikay/circleci-amazonlinux-rust`][docker].

Of special note is the `lambda` version
tag, which corresponds here to the `lambda` branch. This release is pinned to the latest Amazon Linux image for Lambda
functions.

## License

Licensed at your discretion under either:

 - MIT (`./LICENSE-MIT`)
 - Apache License, Version 2.0 (`./LICENSE-APACHE`)

 [docker]: https://hub.docker.com/r/naftulikay/circleci-amazonlinux-rust/
 [docker.svg]: https://img.shields.io/docker/automated/naftulikay/circleci-amazonlinux-rust.svg?maxAge=2592000
 [travis]: https://travis-ci.org/naftulikay/docker-circleci-amazonlinux-rust
 [travis.svg]: https://travis-ci.org/naftulikay/docker-circleci-amazonlinux-rust.svg
