# /anuncio-google — Crear campaña para Google Ads

Crea una campaña completa lista para importar en Google Ads Editor.

## Antes de empezar

Lee `_memoria/empresa.md` y `_memoria/estrategia.md`.

## Recopilar información

Si no fue dado, pregunta:
1. "¿Qué producto o servicio quieres anunciar?"
2. "¿Cuál es el objetivo? (visitas a la web, llamadas, formularios, ventas)"
3. "¿Cuál es el presupuesto diario aproximado?"
4. "¿Cuál es el área geográfica a alcanzar?"
5. "¿Hay alguna promoción u oferta especial activa?"

## Estructura de la campaña

### Grupos de anuncios (mínimo 3)
Organizar por intención de búsqueda:
- Grupo 1: términos de compra directa ("comprar X", "precio de X")
- Grupo 2: términos de comparación ("mejor X", "X cerca de mí")
- Grupo 3: términos de problema ("cómo resolver Y", "servicio de Y")

### Para cada grupo
- 10-15 palabras clave (concordancia exacta + frase)
- 3 anuncios de búsqueda responsivos con:
  - 15 títulos variados (máx. 30 caracteres cada uno)
  - 4 descripciones (máx. 90 caracteres cada una)
- Extensiones: sitelinks, llamadas, ubicación si aplica

### Palabras clave negativas
- Lista de términos irrelevantes a excluir para evitar clics sin valor

## Output

Archivo CSV en `marketing/ads/campana-[producto].csv` compatible con Google Ads Editor.
Incluye también un resumen de la estrategia en `marketing/ads/briefing-[producto].md`.
