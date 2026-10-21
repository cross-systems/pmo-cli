# PMO CLI

Downloads for `pmo`, the command line for [PMO](https://docs.crossbot.io/pmo), Cross's engagement management system.

This repository holds **releases only**. The source lives in a private repository; each release here carries the programs for Windows, macOS and Linux, the two install scripts, and a `SHA256SUMS` file the scripts check before installing anything.

## Install

**Windows** (PowerShell):

```powershell
irm https://github.com/cross-systems/pmo-cli/releases/latest/download/install.ps1 | iex
```

**macOS and Linux** (Terminal):

```sh
curl -fsSL https://github.com/cross-systems/pmo-cli/releases/latest/download/install.sh | sh
```

Then sign in with your Cross account:

```sh
pmo login
```

Run the same line again to update. `pmo` does nothing until you sign in to a PMO server you have access to.

## Documentation

Everything else, including every command, is at **[docs.crossbot.io/pmo-cli](https://docs.crossbot.io/pmo-cli)**.
