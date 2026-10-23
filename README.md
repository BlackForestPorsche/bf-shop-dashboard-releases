# Black Forest Shop Dashboard — public releases

Public Windows portable zip downloads. Source stays private in [`bf-shop-dashboard`](https://github.com/BlackForestPorsche/bf-shop-dashboard).

## Download (no GitHub login)

**Stable name (use this on the shop Downloads page):**

https://github.com/BlackForestPorsche/bf-shop-dashboard-releases/releases/latest/download/BlackForestShopDashboard-win-x64.zip

Shop target after Grok copies it into `blackforest-tools`:

`https://shop.blackforestautomotive.com/downloads/BlackForestShopDashboard-win-x64.zip`

## Publish

Edit `release-source.json` (tag, title, temporary public URL, sha256). Push triggers `.github/workflows/publish-zip.yml`, which downloads, verifies sha256, and creates/replaces the GitHub Release asset.
