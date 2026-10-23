# Black Forest Shop Dashboard — public releases

Public Windows downloads. Source stays private in [`bf-shop-dashboard`](https://github.com/BlackForestPorsche/bf-shop-dashboard).

## Download (no GitHub login)

**Primary — Setup (recommended, git auto-update):**

https://github.com/BlackForestPorsche/bf-shop-dashboard-releases/releases/latest/download/Black.Forest.Shop.Dashboard-Setup.exe

**Secondary — Portable zip:**

https://github.com/BlackForestPorsche/bf-shop-dashboard-releases/releases/latest/download/BlackForestShopDashboard-win-x64.zip

Shop target after Grok copies Setup into `blackforest-tools`:

`https://shop.blackforestautomotive.com/downloads/Black.Forest.Shop.Dashboard-Setup.exe`

## Publish

Edit `release-source.json` (tag, title, notes, assets with `path`/`url` + sha256; optional `encoding: base64` for `.b64` artifacts). Push triggers `.github/workflows/publish-release.yml`.
