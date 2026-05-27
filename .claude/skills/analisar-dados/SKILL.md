# /analizar-datos — Analizar archivos y generar resumen ejecutivo

Lee archivos CSV, XLSX o PDF y transforma los datos en resúmenes accionables.

## Recibir el archivo

Pide al usuario que comparta el archivo o que pegue los datos directamente en la conversación.

Formatos aceptados: CSV, XLSX, PDF, tablas copiadas de Excel o Google Sheets.

## Qué hacer con los datos

1. Identificar el tipo de datos (ventas, visitas, redes sociales, financiero, otro)
2. Detectar automáticamente las columnas y métricas relevantes
3. Calcular totales, medias, máximos, mínimos y tendencias
4. Identificar anomalías o valores fuera del patrón
5. Cruzar datos si hay múltiples variables

## Resumen ejecutivo

Estructura del output:
- **Lo que dicen los datos** — 3 conclusiones principales en lenguaje simple
- **Lo que está funcionando** — puntos positivos destacados
- **Lo que preocupa** — alertas o caídas relevantes
- **Próximos pasos sugeridos** — 3 acciones concretas basadas en los datos

## Visualización (si es útil)

Proponer tablas simples en Markdown para comparación rápida.

## Output

Guardar en `datos/analisis-[nombre-del-archivo]-[fecha].md`.
