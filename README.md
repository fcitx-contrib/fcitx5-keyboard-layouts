# Fcitx5 keyboard layouts

JSON definition of keyboard layouts for
[fcitx5-ios](https://github.com/fcitx-contrib/fcitx5-ios)
and [fcitx5-harmony](https://github.com/fcitx-contrib/fcitx5-harmony).

This is NOT meant to be edited manually by end users.

## Symbols

Each file in `symbol/` defines one symbol category. The file name without the `.json` extension is the category key. Its `name` object maps locales to translated display names, and `symbols` contains the symbols in display order.

The optional `halfWidth` and `fullWidth` arrays identify symbols that should display the corresponding width badge. Symbols not listed in either array do not display a badge.
