# Downloadables

## gMenu / Go Menu

Is a Go based [dmenu](https://tools.suckless.org/dmenu/) inspired cross-platform GUI menu.

Download links:
- arm64: [gmenu.arm64](/dl/bin/gmenu.arm64)


## Combo Switcher

Is a window switcher and app launcher for macOS. A lightweight alternative to Alfred or Rofi if you're coming from Linux.

- This has a dependency on a `dmenu` alternative for your platform.
- No dependencies on any external indexing services including macOS's Spotlight.


Download links:
- arm64: [combo-switcher.arm64](/dl/bin/combo-switcher.arm64)

### Disclaimer

This is not fully prepared for general use and requires on the following executable to be in your path:
`cmd := exec.Command("_themenu.sh", "-p", string(lastInput), "-i")` that behaves similar to `dmenu`.
