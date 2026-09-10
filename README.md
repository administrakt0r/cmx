# CMX — Compressius Maximus

CMX is a local context-compression gateway for coding agents, with a terminal interface and usage dashboard.

## Install

Linux and macOS, on Intel/AMD 64-bit or ARM64:

```sh
curl -sSfL https://raw.githubusercontent.com/administrakt0r/cmx/main/install.sh | sh
```

Run `cmx login` to pair your CMX account, then use CONFIG to select your coding agent and provider. Your coding agent manages its own provider credentials.

Downloads and checksums are available on the [releases page](https://github.com/administrakt0r/cmx/releases). Documentation and your dashboard are at [compressi.us](https://compressi.us).

This repository distributes the installer and compiled releases. Application source and build tooling are maintained separately. Only `install.sh`, `install-nightly.sh`, and `README.md` belong in its Git tree.
