# ForceRGB
Force RGB mode for external monitors for MacOS that defaults to YPbPr.
## Installation

```sh
brew install jq
fisher install hrabryi/force-rgb
```

## Usage

```sh
# dry-run
force-rgb

# apply changes
yes | force-rgb

# reboot your mac, if it doesn't have effect, shutdown and boot again.
```
