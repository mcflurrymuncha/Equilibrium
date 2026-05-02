# Equilibrium

[![Equilibrium](https://img.shields.io/badge/Equilibrium-grey?style=flat)](https://github.com/mcflurrymuncha/Equilibrium)
is a fork of [Equibop](https://github.com/Equicord/Equibop), a modification of [Vesktop](https://github.com/Vencord/Vesktop) to allow more stability on your crappy laptop from 2011 :3

Find a bug? put it in the Discord!<br></br>

**Main features**:
- Equicord preinstalled
- Much more lightweight and faster than the official Discord app
- Much better privacy, since Discord has no access to your system

**Extra included changes**

- Tray Customization with voice detection and notification badges

- arRPC-bun with debug logging support https://github.com/Creationsss/arrpc-bun

**Not fully Supported**:
- Global Keybinds (Windows/macOS - use command-line flags on Linux instead)

## Equilibrium Arguments
> [!NOTE]
> For the full list of supported flags and how to apply them, see the
[Tips & Tricks](https://equibop.org/wiki/linux/tips/) page on the Equibop wiki!

### Quick reference

| Flag                            | Description                             |
|---------------------------------|-----------------------------------------|
| `--ozone-platform=wayland`      | Force native Wayland                    |
| `--ozone-platform=x11`          | Force XWayland                          |
| `--no-sandbox`                  | Disable Chromium sandbox (use with caution) |
| `--force_high_performance_gpu`  | Prefer discrete GPU                     |
| `--start-minimized`             | Launch minimized to tray                |
| `--toggle-mic`                  | Toggle mic (bind to shortcuts)          |
| `--toggle-deafen`               | Toggle deafen (bind to shortcuts)       |
| `--toggle-vad`                  | Toggle Voice Activity Detection (Voice Activity <-> Push To Talk) |

### Persistent flags

Add flags to `${XDG_CONFIG_HOME}/equibop-flags.conf` — one per line, lines starting with `#` are comments.

## Installing
Check the [Releases](https://github.com/Equicord/Equibop/releases) page

**You may notice that this is not finished. and you would be correct**
