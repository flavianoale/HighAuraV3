# High Aura V3 — MBs de conteúdo offline (GitHub Pages + PWA)

Você pediu MBs. Entregue:
- `public/data/meals_big.json` (8.000 itens)
- `public/data/mentor_dialog_big.json` (12.000 itens)
- `public/data/knowledge_base_big.txt` (22.000 linhas)

Esses arquivos NÃO são empacotados no JS inicial. O app faz `fetch` sob demanda na aba "BIBLIOTECA".
O service worker cacheia esses assets para uso offline.

## Deploy
1) Suba no GitHub (branch `main`)
2) Settings -> Pages -> Source: GitHub Actions
3) Push na `main`

## Observação
Autoplay de áudio é bloqueado no primeiro uso por política do navegador. Use "ARMAR ÁUDIO".
