# somosum-catalog

Catálogo oficial de packs do [SOMOSUM](https://github.com/RabbitVisual/SOMOSUM): plugins, hinários e mídia.

## Manifests (branch `main`)

| Tipo | URL raw |
|------|---------|
| Plugins | https://raw.githubusercontent.com/RabbitVisual/somosum-catalog/main/catalog/plugins/manifest.json |
| Hinários | https://raw.githubusercontent.com/RabbitVisual/somosum-catalog/main/catalog/hinarios/manifest.json |
| Mídia | https://raw.githubusercontent.com/RabbitVisual/somosum-catalog/main/catalog/media/manifest.json |

## Release com ZIPs

**[packs-8.7.8](https://github.com/RabbitVisual/somosum-catalog/releases/tag/packs-8.7.8)** — 16 arquivos (~97 MB):

- 8 plugins (`culto-*.zip`)
- 5 hinários (`CC.zip`, `HC.zip`, `HCC.zip`, `HE.zip`, `HNC.zip`)
- 3 packs de mídia (`media-pack-1/2/3.zip`)

CDN base: `https://github.com/RabbitVisual/somosum-catalog/releases/download/packs-8.7.8`

## Publicar nova versão

No repositório principal SOMOSUM:

```bash
node scripts/publish-pack-catalog.mjs
# copiar catalog/publish/ → somosum-catalog/catalog/
# anexar catalog/dist/packs-X.Y.Z/*.zip em nova release
```

Veja `catalog/PUBLICAR.md` no repo SOMOSUM.
