---
title: HOL Guard
homepage: https://github.com/hashgraph-online/hol-guard
tagline: |
  HOL Guard: Inspect and control AI-agent actions
---

This installer provides the official standalone `hol-guard` CLI for Linux x86-64
with glibc. Version 3.54.0 requires glibc 2.35 or newer. macOS, Windows and
musl-based systems are not included in this installer.

To update or switch versions, run `webi hol-guard@stable`.

### Files

The installer creates or updates:

```text
~/.config/envman/PATH.env
~/.local/opt/hol-guard-v<version>/
~/.local/bin/hol-guard
```

## Cheat Sheet

Check the installed version and available commands:

```sh
hol-guard --version
hol-guard --help
```

Installing the CLI does not activate protection or change AI-tool hooks. Review
the [official documentation](https://github.com/hashgraph-online/hol-guard)
before choosing a setup or enforcement command.
