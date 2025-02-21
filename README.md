# `visimp` Mason Registry

This project is a [`mason.nvim`](https://github.com/williamboman/mason.nvim)
package registry by the developers of [`visimp`](https://visimp.teapot.ovh).

## Scope

The `visimp` Mason registry hosts packages that would not be accepted by the
core registry, but are required by some `visimp` layers. This might include, for
example, language servers for obscure languages requiring custom build scripts.

## Usage

This registry is active by default on all `visimp` installations, but other
Neovim users can enable it in their [`mason.nvim`
configuration](https://github.com/williamboman/mason.nvim?tab=readme-ov-file#default-configuration)
(which `visimp` users can access from their [`lsp` layer
configuration](https://visimp.teapot.ovh/docs/layers/lsp/#configuration)).
