# Guilhermitico Tweaks

Site de vendas e downloads do Guilhermitico Tweaks.

- **Site:** https://guirodriguesxz.github.io/guilhermitico-tweaks/
- **Baixar a ultima versao:** https://github.com/guirodriguesxz/guilhermitico-tweaks/releases/latest

Este repositorio e publico de proposito: ele hospeda a pagina (GitHub Pages) e os
instaladores das Releases, que precisam ser baixaveis sem login. O codigo-fonte do
aplicativo fica em um repositorio privado separado.

## Arquivos de cada Release

| Arquivo | Para que serve |
|---|---|
| `GuilhermiticoTweaks-Setup.msi` | o instalador |
| `update.json` | manifesto assinado que o app le para saber se ha versao nova |
| `revoked.json` | lista assinada de licencas bloqueadas |

Os tres sao gerados pelo `build.ps1` e pelo KeyGen, no repositorio do codigo.
