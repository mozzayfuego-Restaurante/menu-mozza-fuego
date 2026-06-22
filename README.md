# Mozza & Fuego - Catálogo web 3.0

## Archivos
- `index.html`: sitio completo con CSS y JavaScript integrado.
- `hero.png`: banner principal editable.
- `logo.png`: logo visible en el header.
- `logo_dark.png`: respaldo del logo.

## Estructura recomendada para Google Sheets
Usa encabezados claros en la primera fila:
Producto | Categoria | Precio | Descripcion | Ingredientes | Imagen | Disponible

Notas:
- `Disponible`: deja vacío o escribe “Sí” para mostrar. Escribe “Agotado”, “Oculto” o “No” para ocultar.
- El sitio lee el CSV publicado y actualiza cada 60 segundos.

## Publicar en GitHub Pages
1. Crea un repositorio en GitHub.
2. Sube estos archivos en la raíz: `index.html`, `hero.png`, `logo.png`, `logo_dark.png`.
3. Entra a Settings > Pages.
4. En Source selecciona `Deploy from a branch`.
5. Branch: `main` y carpeta `/root`.
6. Guarda y espera 1 a 3 minutos.
7. Abre el enlace público que entrega GitHub Pages.

## Cambiar banner o colores
- Para cambiar banner, reemplaza `hero.png` por otra imagen con el mismo nombre.
- Para cambiar colores, abre `index.html` y edita la sección `:root`.
- El código tiene comentarios visibles en la sección del banner.

## Conexión Google Sheets
El archivo ya usa este CSV:
https://docs.google.com/spreadsheets/d/e/2PACX-1vRlB6HeY5fgQmJ8vsjy8-ZIQp8YI58TNZjt0il-dOQLn9X8kXcIoSoRrkNg_VMVp_-OvhuWk2wIHQll/pub?gid=164815629&single=true&output=csv

Para mantenerlo funcionando, la hoja debe seguir publicada en Archivo > Compartir > Publicar en la web > CSV.
