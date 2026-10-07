# fromshim marketplace

[한국어](README.md)

A Claude Code plugin catalog for installing fromshim products from one place.

## Install

```
/plugin marketplace add fromshim/marketplace
/plugin install korean-tone@fromshim
/plugin install git-graph@fromshim
```

## Products

| Name | Description | Repo |
| --- | --- | --- |
| korean-tone | Polishes every Korean reply. Ships default, easy and mz modes plus a document linter hook. | [fromshim/korean-tone](https://github.com/fromshim/korean-tone) |
| git-graph | Draws the current repo's git graph live in a pane beside the terminal. | [fromshim/git-graph](https://github.com/fromshim/git-graph) |

Each product is developed in its own repo; file issues and find releases there. This repo only holds the list.

## Existing korean-tone users

Previously `fromshim/korean-tone` itself was registered as a marketplace named `fromshim`. That repo's own marketplace is now named `korean-tone`. To migrate:

```
/plugin marketplace remove fromshim
/plugin marketplace add fromshim/marketplace
```

Reinstall with `/plugin install korean-tone@fromshim` if needed.
