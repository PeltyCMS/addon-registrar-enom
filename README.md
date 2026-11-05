# eNom

Official **PeltyCMS** `registrar` WASM addon (`registrar-enom`).

## Install

1. Open Pelty Admin → Addons → Marketplace
2. Set registry URL to `https://market.mythicalsystems.org/api/pelty/addons/registry.json`
3. Download **eNom**

Marketplace: https://market.mythicalsystems.org/marketplace/product/registrar-enom  
Product ID (CI): `83`

## Develop

This repository is a git submodule of [MythicalLTD/PeltyCMS](https://github.com/MythicalLTD/PeltyCMS) at `extensions/addons/reg-enom`.

```bash
# from the PeltyCMS monorepo
cargo xtask addons reg-enom
```

## Release (Mythic Marketplace)

Same flow as [featherpanel-com/PterodactylPanelApi](https://github.com/featherpanel-com/PterodactylPanelApi):

1. Repo secrets: `MYTHIC_PRODUCT_ID`, `MYTHIC_RELEASE_TOKEN`
2. Repo variable: `ADDON_DIR=reg-enom`
3. Actions → **Release Addon** → Run workflow

Publishes the packed `registrar-enom.zip` via `MythicalLTD/.github/actions/publish-release@v1` and creates a GitHub Release.
