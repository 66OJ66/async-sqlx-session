# async-sqlx-session
## [sqlx](https://github.com/launchbadge/sqlx)-backed session store for [async-session](https://github.com/http-rs/async-session)

## ⚠️ Note: This crate is not yet published ⚠️
So most of the links in this readme will not work yet. Check out the
status of https://github.com/http-rs/async-session/pull/2 for the
latest

* [CI ![CI][ci-badge]][ci]
* [API Docs][docs] [![docs.rs docs][docs-badge]][docs]
* [Releases][releases] [![crates.io version][version-badge]][lib-rs]
* [Contributing][contributing]

[ci]: https://github.com/jbr/async-sqlx-session/actions?query=workflow%3ACI
[ci-badge]: https://github.com/jbr/async-sqlx-session/workflows/CI/badge.svg
[releases]: https://github.com/jbr/async-sqlx-session/releases
[docs]: https://docs.rs/async-sqlx-session
[contributing]: https://github.com/jbr/async-sqlx-session/blob/master/.github/CONTRIBUTING.md
[lib-rs]: https://lib.rs/async-sqlx-session
[docs-badge]: https://img.shields.io/badge/docs-latest-blue.svg?style=flat-square
[version-badge]: https://img.shields.io/crates/v/async-sqlx-session.svg?style=flat-square

## Installation
```sh
$ cargo add async-sqlx-session
```

## Safety
This crate uses ``#![deny(unsafe_code)]`` to ensure everything is implemented in
100% Safe Rust.

## License

<sup>
Licensed under either of <a href="LICENSE-APACHE">Apache License, Version
2.0</a> or <a href="LICENSE-MIT">MIT license</a> at your option.
</sup>

<br/>

<sub>
Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in this crate by you, as defined in the Apache-2.0 license, shall
be dual licensed as above, without any additional terms or conditions.
</sub>
