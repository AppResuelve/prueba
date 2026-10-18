# Invitación – Sello Verde Raíz Nativa · El Potrero

Sitio estático (HTML + CSS), sin build. Se publica la carpeta `public/`.

## Estructura
```
public/
  index.html
  images/        ← poner acá los logos
vercel.json
package.json
```

## Logos (carpeta `public/images/`)
| Archivo | Dónde aparece |
|---|---|
| `raiznativa.png` | Franja gris, debajo de "Para consultas" |
| `LogoPotreroReserva-verde.png` | Franja gris, junto a Raíz Nativa |
| `LOGO FONDO TRANSPARENTE-62.png` | Auspiciantes (Como era Antes) |
| `texom.png` | Auspiciantes (Texom) |

## Probar en local
```bash
npm run dev
```

## Deploy en Vercel
1. Subí el repo a GitHub.
2. En Vercel: Add New → Project → importá el repo.
3. Framework Preset: **Other**. No cambies nada más (`vercel.json` ya define `public` como salida).
4. Deploy.

Con la CLI: `npx vercel --prod`.

## Editar
- Link del formulario: buscá `docs.google.com/forms` en `public/index.html` (aparece 2 veces).
- Fecha: buscá `25 de Septiembre de 2026` (aparece 2 veces).
