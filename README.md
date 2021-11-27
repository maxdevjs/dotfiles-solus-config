# dotfiles-solus-config

Personal config/setup files for Solus

## What is this?

A `dynamic` script that provides the inital setup for a new [Solus](https://getsol.us/home/) installation. 

## How does it work?

- I create scripts that install my favorite specific kind of programs
- and setup some dev toolchains

I **strive** (reminder to myself) to maintain the scripts updated (adding newly installed programs).

### Maintenance

I generally do not install through the graphical `Software Center` (with a
current exception for a bug in the [regex](#todo)).

I instead add the new program to a specific script.

Consequently, I should achieve a minimal reproducibility.

### Setup Flow

- I clone this repo
- run `./setup`
- it should then offer a configured and ready to be used system

## TODO

- [ ] fix setup `regex` for very short program names

- [ ] add used tools to README
- [ ] add general `bin` (ideally to `$HOME/.local/bin`) scripts
- [ ] add specific to [Solus](https://getsol.us/home/) `bin` (ideally to `$HOME/.local/bin`) scripts
- [ ] add vpn
- [ ] ...

