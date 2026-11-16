# Licensing policy

This organization uses a consistent, per-component policy:

- The `xfetch` core is licensed under **GPL-3.0-only**. The additional
  permission for third-party addons is included in the core
  [`LICENSE`](https://github.com/xfetch-cli/xfetch/blob/main/LICENSE).
- The `api` SDK crates are licensed under **GPL-3.0-only**, with an
  additional permission in the API
  [`LICENSE`](https://github.com/xfetch-cli/api/blob/main/LICENSE)
  so addons may keep their own licenses.
- First-party addon code in `plugins`, `effects`, `extensions` and `commands`
  is **GPL-3.0-only**.
- Third-party addons that are not authored by xscriptor may be distributed
  under **any license their authors choose**. A license compatible with
  GPL-3.0-only is recommended so combined distributions remain
  redistributable.
- Documentation, configuration examples, themes, logo art and brand assets
  are **MIT** unless a repository states otherwise. `context` is
  **CC BY-SA 4.0**.
- Third-party dependencies keep their own licenses. This project's licenses
  do not relicense dependency code.
- Distributed binaries and packages must comply with every bundled dependency
  license. Preserve copyright notices and any required `NOTICE` files.
- Attribution to xscriptor is required when redistributing the xfetch code or
  substantially copying it. Addon authors keep their own copyright and
  attribution for their addons.

## Repositories

- `xfetch`: GPL-3.0-only, plus the addon exception.
- `api`: GPL-3.0-only, plus the API addon exception.
- `plugins`, `effects`, `extensions`, `commands`: GPL-3.0-only.
- `web`, `configs`, `themes`, `logos`, `assets`, `homebrew-tap` and `.github`:
  MIT unless the repository states otherwise.
- `context`: CC BY-SA 4.0.

## Addons

An addon (plugin, extension, effect or command) that uses the public xfetch
API, SDK or documented protocol may be distributed under its author's chosen
license when it is authored by a third party. First-party addons in the
xfetch-cli addon repositories are GPL-3.0-only. The addon exception does not
change the license of the xfetch core and does not grant trademark rights.

## Third-party notices

When a repository needs dependency notices, add a `THIRD_PARTY_LICENSES.md` or
a `NOTICE` file and generate it with `cargo-license` or `cargo-deny`.
Do not claim that third-party code is MIT or GPL-3.0-only.

## Contributions

Contributions are accepted under each repository's license (inbound =
outbound): GPL-3.0-only for the core, the API and first-party addon code,
MIT for the web, data and template repositories, and CC BY-SA 4.0 for
`context`.
Third-party addon authors keep the license they choose for their addon;
contributions to xscriptor-authored code are accepted under that code's
license unless a separate agreement states otherwise. Contributors should
certify the Developer Certificate of Origin with a `Signed-off-by` trailer. A CLA is not required unless a
separate commercial licensing arrangement is introduced.

## Trademarks

The licenses do not grant permission to use the X or xfetch names or logos as
trademarks. See `TRADEMARKS.md`.
