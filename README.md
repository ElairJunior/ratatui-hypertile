![demo](assets/demo.gif)

[![CI](https://github.com/nikolic-milos/ratatui-hypertile/actions/workflows/ci.yml/badge.svg)](https://github.com/nikolic-milos/ratatui-hypertile/actions/workflows/ci.yml)
[![Crates.io](https://img.shields.io/crates/v/ratatui-hypertile.svg)](https://crates.io/crates/ratatui-hypertile)
[![Docs.rs](https://docs.rs/ratatui-hypertile/badge.svg)](https://docs.rs/ratatui-hypertile)

Hyprland-inspired BSP tiling engine for Ratatui.

Cook up delicious TUIs with layouts you can split, move, resize, tweak at
runtime, and persist.

## Crates

- **ratatui-hypertile** - core engine with full control
- **[ratatui-hypertile-extras](https://crates.io/crates/ratatui-hypertile-extras)** - runtime helpers with plugins, palette, keymaps, and tabs

## Core vs Extras

Most apps will probably want
[`ratatui-hypertile-extras`](https://crates.io/crates/ratatui-hypertile-extras).
It is the more batteries-included version, with plugins, command palette,
keymaps, and tabs.
