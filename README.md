# rust-crates
A list of  useful Rust crates.

## Error handling

- [thiserror](https://github.com/dtolnay/thiserror) in your lib.
- [anyhow](https://github.com/dtolnay/anyhow) in your app.

## Batteries (Not included)

- [chrono](https://github.com/chronotope/chrono) "It aims to be a feature-complete superset of the time library." If you wonder how to get something like a 'Date' or an 'Instant' from "2021-08-21" Check this crate.

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
