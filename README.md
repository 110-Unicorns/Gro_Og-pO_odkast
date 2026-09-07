# Gro_Og-pO_odkast

Podcast d'en **Gro_Og** (el noi de la terra): *la veu de la terra*.

Contingut + HTML estàtic. Sense motor Python, sense shell al navegador.
CHAT ≠ CODE ≠ ACTION ≠ SHELL.

## Mapa

```
├── index.html              # cara pública (Cloudflare Pages)
├── docs/format-episodi.md  # regles d'episodi
├── episodis/
│   ├── _plantilla/         # copia això per un episodi nou
│   └── 000-pilot/
└── assets/{artwork,audio,video,midi}/
```

## Afegir un episodi

1. Copia `episodis/_plantilla/` → `episodis/NNN-slug/`
2. Omple `00-meta`, `01-guio`, `02-lletra`, `03-notes-terra`
3. Deixa àudio/artwork a `assets/` quan hi siguin

## Domini

Pensat per **hyperkubik.net** / HYPRKUBIK via Cloudflare Pages (arrel del repo).
