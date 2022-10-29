# dotfiles-solus-config

Personal config/setup files for Solus

> Manually add `maxdevjs ALL = NOPASSWD: /usr/bin/eopkg, /usr/bin/solus-sc` to `/etc/sudoers`

> Manually install `Symbols Nerd Font` for icons

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

> ☢️ WIP
>
> ☢️ Warning: I strive to commit only working versions, but 💩 can happen

## TODO

- [ ] 🤪 add used tools to README (?)
- [ ] 😌 add structure to README (!)

~~`setup-packages`~~
`setup-system-packages`

- [x] 🧠 rename to `setup-system-packages`
- [ ] 🤪 fix setup `regex` for very short program names
- [ ] 🛰️ add vpn (working, must plug it in config)

`setup-utilities`

- [x] 🗑️ add general `bin` (ideally to `$HOME/.local/bin`) scripts
- [ ] 🤪 add specific to [Solus](https://getsol.us/home/) `bin` (ideally to `$HOME/.local/bin`) scripts

`setup-dev-tools`

- [ ] 🧠 possibly `DRY` refactor

- [ ] ⚙️ test `fly`
- [ ] ⚙️ test `heroku`
- [ ] ⚙️ test `nvm` (see [Guix](#guix) and [Nix](#nix) sections)
- [ ] ⚙️ check and install latest `nvm`
- [ ] ⚙️ test `nvm` integration with [Fish](https://fishshell.com/)
- [ ] ⚙️ [nvm.fish](https://github.com/jorgebucaran/nvm.fish)
- [ ] ⚙️ [fish-nvm](https://github.com/FabioAntunes/fish-nvm)
- [ ] ⚙️ test `nvm`
- [ ] ⚙️ test `vercel`

`setup-fonts`

- [x] add system fonts
- [ ] 🤔 put back system fonts in `setup-system-packages`
- [ ] 🤔 add external fonts

`setup-yadm`

- [ ] 🧠 check version (as per `direnv`)

`guix`

- [x] install and test
- [ ] clean the 💩

`nix`

- [x] install and test
- [ ] clean the 💩

## Additional 🤪

> The following should be interesting alternatives for development.
>
> Also, as alternatives to Flatpak/Snap.

### Guix

...

### Nix

[maxdevjs/dev-nix-shells](https://github.com/maxdevjs/dev-nix-shells)

