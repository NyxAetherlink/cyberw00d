# cyberw00d

> *"The future is already here — it's just not evenly distributed."*

Fill your console with neon-drenched technobabble and cyberpunk melodrama.

`cyberw00d` is a fork of [Dustin Kirkland's hollywood](https://github.com/dustinkirkland/hollywood), reborn with a synthwave soul. It splits your terminal into a grid of pulsing panes — each one dripping with cyan matrix rain, magenta hex dumps, and glitch-corrupted system logs. Perfect for netrunner cosplay, lofi coding sessions, or making your setup look like it belongs in Neo-Tokyo.

---

## Quick Start

Run from source (no installation needed):

```bash
git clone https://github.com/NyxAetherlink/cyberw00d.git
cd cyberw00d
./bin/hollywood
```

## Usage

```bash
./bin/hollywood              # run with defaults
./bin/hollywood -s 5         # limit to 5 splits
./bin/hollywood -d 30        # rearrange panes every 30 seconds
./bin/hollywood -s 8 -d 15   # combine options
```

Press `Ctrl-C` to jack out.

## Cyberpunk Theme Changes

This fork takes the original `hollywood` concept and pushes it into the neon-soaked sprawl:

- **Neon tmux borders** — active panes glow cyan, inactive pulse magenta
- **Cyan matrix rain** — `cmatrix` cycles through cyan, magenta, and electric blue
- **Hex dumps in neon** — shifted from default green to cyber-cyan
- **Monokai code highlighting** — source code rendered in dark synthwave colors
- **Dracula bat theme** — syntax-highlighted files bathed in purple and pink
- **Expanded figlet vocabulary** — 40+ cyberpunk terms: NETRUNNER, REPLICANT, FLATLINE, CHROME, ICE...
- **3 new widgets**:
  - `breach` — fake intrusion logs with randomized targets and access statuses
  - `glitch` — terminal corruption effect with cyber-term glitching
  - `fastfetch` — system info with cyan/magenta branding (if available)

## Widgets

| Widget | Description |
|--------|-------------|
| `apg` | Random password generation (cyberpunk palette) |
| `atop` | Advanced system monitor |
| `bat` | Syntax-highlighted source code (Dracula theme) |
| `bmon` | Network bandwidth monitor |
| `breach` | **NEW** Fake intrusion/breach logs |
| `cmatrix` | Matrix-style digital rain (cyan/magenta/blue) |
| `code` | Colorized source code (Monokai theme) |
| `errno` | Scrolling error code definitions |
| `fastfetch` | **NEW** System info with cyberpunk colors |
| `figlet` | Large ASCII text banners (cyberpunk vocabulary) |
| `glitch` | **NEW** Terminal glitch corruption effect |
| `hexdump` | Hex dump of binary files (cyan) |
| `htop` | Interactive process viewer |
| `jp2a` | JPEG to ASCII art conversion |
| `logs` | Colorized system log files |
| `man` | Random colorized man pages |
| `map` | World map in ASCII art |
| `mplayer` | Video to ASCII art animation |
| `pv` | Data transfer progress bars |
| `speedometer` | Network traffic graphs |
| `sshart` | SSH key fingerprint art (magenta) |
| `stat` | File and device statistics (cyan) |
| `tree` | Directory tree visualization (colorized) |

## Upstream

This fork is based on [hollywood](https://github.com/dustinkirkland/hollywood) by Dustin Kirkland. All original widgets and core logic are preserved; only colors, branding, and a few additions have been modified.

## License

Apache-2.0. See the [LICENSE](LICENSE) file or [apache.org/licenses/LICENSE-2.0](https://www.apache.org/licenses/LICENSE-2.0).
