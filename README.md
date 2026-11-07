# Resumen Diario 📰

Resumen diario de Erik Espinosa Machuca — cada mañana 8am.

- **Noticias:** Política, México, Negocios, Clima
- **Deportes:** Fútbol Liga MX
- **Cultura Pop:** Música, Memes y tendencias
- **Videojuegos:** Página completa, PlayStation y Xbox

## Estructura
```
/
├── index.html              → Portada con links a todas las ediciones
└── ediciones/
    ├── 2026-11-07/
    │   ├── index.html      → HTML de ese día (UTF-8)
    │   └── Resumen_Diario_2026-11-07.pdf
    ├── 2026-11-06/
    └── ...
```

## Cómo verlo
- **GitHub Pages:** Settings → Pages → Deploy from branch `main` → `/ (root)` → tu sitio queda en `https://TU_USUARIO.github.io/resumen-diario/`
- **Local:** descomprime el ZIP y abre `index.html` con doble clic.

## Codificación
Todos los HTML están en **UTF-8** con `<meta charset="UTF-8">`. No los abras en Bloc de notas en ANSI. Usa VS Code / Notepad++ en UTF-8 sin BOM. Si los subes a GitHub, no se corrompen porque GitHub no convierte los archivos como hace Drive con los .txt.

## Automatización diaria
Cada mañana se genera:
1. Periódico interactivo
2. PDF con página gamer completa
3. HTML + ZIP (para no corromper UTF-8)

Y se guarda en Drive por fecha + se envía por Outlook a machuca_anima@outlook.com.
