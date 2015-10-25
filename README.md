# Overview

This repository is a fork of
[xmonad](https://www.github.com/xmonad/xmonad) and contains patches to
provide better integration with [QubesOS](https://www.qubes-os.org/).

# Changes

- Window border colors are determined by the `qubesColors` field
  in the `XConfig` structure. The default colors can be overwritten
  by changing this field in the xmonad configuration file.
