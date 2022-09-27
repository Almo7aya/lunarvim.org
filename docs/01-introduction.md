---
sidebar_position: 1
title: Introduction
---

<img src="/img/lunarvim_logo.png" alt="LunarVim Logo" />

# Introduction

LunarVim is an opinionated, extensible, and fast IDE layer for Neovim >= 0.7.0. LunarVim takes advantage of the latest Neovim features such as [Treesitter](https://tree-sitter.github.io/tree-sitter/) and [Language Server Protocol](https://en.wikipedia.org/wiki/Language_Server_Protocol) support.

## Opinionated

LunarVim ships with a sane default config for you to build on top of. Features include autocompletion, integrated terminal, file explorer, fuzzy finder, LSP, linting, formatting and debugging.

## Extensible

Just because LunarVim has an opinion doesn't mean you need to share it. Every builtin plugin can be toggled on or off in the `config.lua` file. This is the place to add your own plugins, keymaps, autocommands, leader bindings and all other custom settings.

## Fast

LunarVim lazyloads plugins wherever possible to maximize speed. Disabled plugins also will not decrease speed due to the plugin list being compiled with only the active plugins. This strategy allows LunarVim to not have to choose between features and speed.
