# trabajaconnosotros

Réplicas de las páginas **"Trabaja con Nosotros"** de la división Real Estate &
Golf de Piñero (Tulum Country Club, Playa Nueva Romana, PGA Riviera Maya, PGA
Ocean's 4), como base para las modificaciones internas.

## Estructura

```
/
├── index.html                     ← índice (enlaza a cada marca)
├── assets/
│   └── logos/                     ← todos los SVG oficiales (planos) + PNG provisionales
└── tulum-country-club/
    ├── index.html                 ← réplica de la página
    └── images/                    ← fotos de la página (ver README de la carpeta)
```

- **Logos**: `assets/logos/` con los SVG por marca y variante
  (`tcc hor neg.svg`, `tcc hor pos.svg`, `pnr …`, `pga …`).
  La cabecera de Tulum usa `tcc hor neg.svg` (caja marrón + sol dorado + texto blanco).
- **Imágenes**: se colocan en `tulum-country-club/images/` con los nombres del
  README de esa carpeta; el HTML las carga automáticamente en cuanto existan.

## Ver online (GitHub Pages)

1. Repo **público**: *Settings → General → Change visibility → Public*.
2. *Settings → Pages → Build and deployment → Source: **Deploy from a branch***.
3. Branch: **`main`** · carpeta `/ (root)` → **Save**.
4. En ~1 minuto:
   - Índice: `https://jorgedelarbrel.github.io/trabajaconnosotros/`
   - Tulum:  `https://jorgedelarbrel.github.io/trabajaconnosotros/tulum-country-club/`

## Tipografías y colores

- Fuentes reales: **Arsenal** + **Montserrat** (Google Fonts).
- Paleta: marrón `#6d5d4d` / marrón oscuro `#4b3f33` / dorado `#bfa15c` / crema `#f2f0ec`.
