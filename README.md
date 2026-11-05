# eNom

Register and renew domains with eNom

Official domain registrar for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS).

## Why this addon

Resellers who sell domains next to hosting and need automated register / renew.

## Features

- Availability checks against the official **eNom** API
- Register, renew and transfer domains from Pelty orders
- Nameserver and contact updates where the API allows
- TLD costs sync into Pelty pricing
- Sandboxed WASM registrar — credentials stay in the panel

## How it works

1. Install **eNom** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/registrar-enom) inside Pelty Admin → Addons.
2. Open Pelty Admin → Domains, connect eNom, sync TLDs, and sell domains like any other product.
3. Customers hit checkout / login / order flow as usual — eNom runs in the background.

## Requirements

- PeltyCMS with WASM addons enabled
- Working eNom credentials
- Outbound HTTPS from your panel

## Get it

**[eNom on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/registrar-enom)**

## Support

Bugs and questions for this addon → Issues on this repo.  
PeltyCMS core → https://github.com/MythicalLTD/PeltyCMS
