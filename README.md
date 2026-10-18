# karabiner-config

Karabiner-Elements configuration for macOS, with Hyper keys and desktop shortcuts.

- Caps Lock sends Hyper on the HHKB (vendor 1278, product 33), and Control on other devices. Hyper means Control+Option+Shift+Command.
- Escape sends Hyper while held and Escape when tapped. Left Shift and Right Shift together toggle Caps Lock.
- Hyper+[ / ] sends Control+Left / Right; Hyper+1–9 sends Control+1–9. Enable the matching Mission Control shortcuts in macOS for desktop switching.
- Hyper+F1/F2 controls keyboard backlight. Hyper+comma, period and slash are swallowed to block the macOS sysdiagnose combinations.
- Includes a `mouse_motion_to_scroll` rule with speed 100.

Requires Karabiner-Elements. Back up your current config, then run from this repo:

```sh
mkdir -p ~/.config/karabiner
cp karabiner.json ~/.config/karabiner/
```

Karabiner reads `~/.config/karabiner/karabiner.json` and reloads it on save. The included profile is `Default profile`.

Tags `v0.1.0`–`v0.9.0` preserve changed automatic-backup snapshots, oldest first; `v0.10.0` marks this configuration. Consecutive identical snapshots are skipped.

MIT. See [LICENSE](LICENSE).
