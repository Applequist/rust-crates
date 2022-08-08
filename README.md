# rust-crates
A list of  useful Rust crates.

## Error handling

- [thiserror](https://github.com/dtolnay/thiserror) in your lib.
- [anyhow](https://github.com/dtolnay/anyhow) in your app.

## Batteries (Not included)

- [config](https://github.com/mehcode/config-rs) Hierarchical configuration from multiple sources: json, yaml, environment...
- [chrono](https://github.com/chronotope/chrono) "It aims to be a feature-complete superset of the time library." If you wonder how to get something like a 'Date' or an 'Instant' from "2021-08-21" Check this crate.
- [secrecy](https://github.com/iqlusioninc/crates/tree/main/secrecy) "Wrapper types and traits for secret management which help ensure they aren't accidentally copied, logged, or otherwise exposed (as much as possible)"
- [validator](https://github.com/Keats/validator) "Common validation functions (email, url, length, ...) and trait - to be used with `validator_derive`"

## CLI

For argument parsing:
- [clap](https://github.com/clap-rs/clap) helps parsing command line arguments but also generate help message and man pages.
- [structopt](https://github.com/TeXitoi/structopt) "Parse command line arguments by defining a struct. It combines clap with custom derive."
  Although, it looks like clap v3 will deprecate structopt.

To indicate progress:
- [indicatif](https://github.com/mitsuhiko/indicatif)

For command line output:
- [atty]() determines whether a program is "talking" to a tty (for human) or not (for a machine) and allows to format its output accordingly.
- [ansi-term](https://github.com/ogham/rust-ansi-term) to style tty output.

For full blown TUI:
- [tui-rs](https://github.com/fdehau/tui-rs)

## Test

- [assert_cmd](https://github.com/assert-rs/assert_cmd) To test CLI application
- [claim](https://github.com/svartalf/rust-claim) Missing assertion macros
- [quickcheck](https://github.com/BurntSushi/quickcheck) Property-based testing
- [fake](https://github.com/cksac/fake-rs) Easily generate test data (name, date, email...) for testing. Use with quickcheck.
- [wiremock](https://github.com/lukemathwalker/wiremock-rs) HTTP Mocking library
- [httpmock](https://github.com/alexliesenfeld/httpmock) HTTP Mocking library (feature comparable to wiremock)


