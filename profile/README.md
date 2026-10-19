<p align="center">
  <img src="https://raw.githubusercontent.com/xfetch-cli/assets/main/logo/banner/xfetch.svg" width="60%" alt="XFetch" />
</p>

<h1 align="center">XFetch</h1>

<p align="center">
  A fast, cross-platform system information fetch for the terminal, written in Rust.
</p>

XFetch keeps the default output clean and readable, then opens up when you want
more: themes, layouts, plugins, intro effects, config extensions, daemon mode,
and WebAssembly support for sandboxed plugins.

## Install

**Linux and macOS**

```bash
curl -fsSL https://raw.githubusercontent.com/xfetch-cli/xfetch/main/install.sh | bash
```

**Windows (PowerShell)**

```powershell
irm https://raw.githubusercontent.com/xfetch-cli/xfetch/main/install-prebuilt.ps1 | iex
```

**Package managers**

```bash
cargo install xfetch-cli                          # crates.io
brew tap xfetch-cli/tap && brew install xfetch    # macOS
yay -S xfetch-core-bin                            # Arch Linux (AUR)
```

## Core repositories

| Repository | What it contains |
| --- | --- |
| [xfetch](https://github.com/xfetch-cli/xfetch) | Core binary: modules, layouts, daemon mode, themes, and the WASM runtime. |
| [plugins](https://github.com/xfetch-cli/plugins) | Official and community plugins: animated logos, system stats, weather, media, and package managers. |
| [themes](https://github.com/xfetch-cli/themes) | Official theme registry with 80+ color palettes. |
| [configs](https://github.com/xfetch-cli/configs) | Ready-to-use presets, layouts, and plugin configurations. |

## Ecosystem

| Repository | What it contains |
| --- | --- |
| [effects](https://github.com/xfetch-cli/effects) | Installable intro animations over the information lines. |
| [extensions](https://github.com/xfetch-cli/extensions) | Config-level lifecycle extensions that can rewrite the resolved config before rendering. |
| [api](https://github.com/xfetch-cli/api) | SDK crates and WIT contracts for plugin, effect, and extension authors. |
| [logos](https://github.com/xfetch-cli/logos) | ASCII logo catalog for Linux distributions, macOS, and Windows. |
| [web](https://github.com/xfetch-cli/web) | Website and documentation. |
| [homebrew-tap](https://github.com/xfetch-cli/homebrew-tap) | Homebrew formula for macOS. |
| [assets](https://github.com/xfetch-cli/assets) | Brand assets, banners, and social preview artwork. |

## Documentation

- Website: https://xfetch-cli.github.io/web/
- Installation: https://github.com/xfetch-cli/xfetch/blob/main/docs/INSTALLATION.md
- Configuration: https://github.com/xfetch-cli/xfetch/blob/main/docs/CONFIGURATION.md
- Plugins: https://github.com/xfetch-cli/xfetch/blob/main/docs/PLUGINS.md

## Contributing

Issues, feature requests, and pull requests are welcome in the
[main repository](https://github.com/xfetch-cli/xfetch). Plugin and theme
contributions belong in their respective repositories.

If XFetch is useful to you, a star on the core repository helps more people
find it.

## License

MIT. See [LICENSE](https://github.com/xfetch-cli/xfetch/blob/main/LICENSE).
