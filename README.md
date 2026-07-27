# homebrew-tap

[admonstrator](https://github.com/admonstrator)'s personal [Homebrew](https://brew.sh) tap — one place for every CLI and app I distribute via `brew`.

## Usage

```sh
brew tap admonstrator/tap
brew trust admonstrator/tap
brew install <formula>
```

Or install directly without a persistent tap:

```sh
brew install admonstrator/tap/<formula>
```

## What's in here

| Formula | Description |
|---|---|
| [`lagerregal`](https://brew.admon.me/lagerregal/) | Classify, search and manage your installed Homebrew packages by category — a fast CLI and TUI with notes, snapshots and housekeeping views |
| [`manta`](https://brew.admon.me/manta/) | TUI network topology mapper ≋ — reads STP/RSTP/MSTP/PVST+, LLDP and CDP passively, enriches over SNMP, and shows a live map, traffic, doctor findings and what-if simulations. Windows builds need [Npcap](https://npcap.com) installed separately |

[![The lagerregal TUI: category sidebar, package list and details pane](site/assets/lagerregal/tui-main.webp)](https://brew.admon.me/lagerregal/)

[![The manta topology map: a spanning tree of seven switches with the root highlighted and live activity on the links](site/assets/manta/map.png)](https://brew.admon.me/manta/)

Each formula's actual source lives in its own repository; the generated `Formula/*.rb` files here are what `brew` reads. Formulae are regenerated automatically by each project's release workflow — don't hand-edit them, changes will be overwritten on the next release.

## Website

A short overview also lives at [brew.admon.me](https://brew.admon.me), built from [`site/`](site) and published via GitHub Pages.

## License

MIT
