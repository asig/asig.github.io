---
title: machinist
link: https://github.com/asig/machinist
---

A small QEMU launcher written in Go. It starts VMs from named TOML config files that can inherit from a parent config, so common settings live in one place and each machine only states what differs.

Configs are plain text with comments, the mapping from config to QEMU command line is deterministic, and a dry-run mode prints the final command line without starting anything. Ships as a single static binary (Linux amd64, cross-compiles to arm64) with no runtime dependencies.
