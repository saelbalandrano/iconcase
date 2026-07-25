# Icon Case — Landing (sitio estático)

Sitio estático. No requiere build: Vercel lo publica tal cual.

## Estructura
```
index.html                 la landing completa (HTML + CSS + JS en un solo archivo)
assets/icon-case-logo.jpg  logo
images/                    fotos de producto (reemplazar por las reales)
```

## Fotos pendientes
Sube archivos con EXACTAMENTE estos nombres a `images/` (JPG, fondo claro, mínimo 1200px de ancho):

| Archivo | Dónde aparece |
|---|---|
| `hero-principal.jpg` | Foto grande del hero (fundas) |
| `hero-cargadores.jpg` | Foto secundaria del hero |
| `hero-audifonos.jpg` | Foto pequeña del hero |
| `cat-fundas.jpg` | Categoría Fundas |
| `cat-cargadores.jpg` | Categoría Cargadores |
| `cat-hidrogel.jpg` | Categoría Hidrogel |
| `cat-cables.jpg` | Categoría Cables |
| `cat-audifonos.jpg` | Categoría Audífonos |
| `cat-bocinas.jpg` | Categoría Bocinas |
| `cat-powerbanks.jpg` | Categoría Powerbanks |

Mientras no existan, esos espacios se ven como bloques grises: el resto de la página funciona normal.

## Deploy en Vercel
El proyecto ya está conectado a este repo: cada push a la rama principal redeploya automáticamente.
Si Vercel pide configuración: Framework Preset = **Other**, Build Command = vacío, Output Directory = raíz del repo.

## Contacto / CTAs
Todos los botones apuntan a WhatsApp:
`https://api.whatsapp.com/send/?phone=528712759598&text=Quiero+ser+distribuidor+IconCase`
Para cambiar el número, buscar y reemplazar `528712759598` en `index.html`.
