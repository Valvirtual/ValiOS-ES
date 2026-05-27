# /informe-ads — Informe semanal de anuncios

Analiza los datos de las campañas y genera un informe con métricas, alertas y recomendaciones.

## Antes de empezar

Pide al usuario que pegue los datos de las campañas (export de Google Ads o resumen manual).

## Qué analizar

### Métricas principales
- Impresiones, clics, CTR (tasa de clics)
- Coste total, CPC medio (coste por clic)
- Conversiones y coste por conversión
- ROAS si e-commerce (retorno sobre inversión en anuncios)

### Comparación con la semana anterior
- Lo que subió vs. lo que bajó
- Identificar patrones (días de la semana, horarios, dispositivos)

### Alertas automáticas
Identificar y señalar:
- CTR por debajo del 2% → anuncios a revisar
- Coste por conversión por encima del objetivo → ajustar pujas o segmentación
- Palabras clave con gasto alto y cero conversiones → pausar o negativar
- Anuncios con bajo índice de calidad → mejorar relevancia

## Recomendaciones

3-5 acciones concretas ordenadas por prioridad:
- Qué hacer esta semana
- Qué probar en el próximo período
- Qué pausar o recortar

## Output

Guardar en `marketing/ads/informe-[fecha].md` con:
- Resumen ejecutivo (5 líneas)
- Tabla de métricas
- Alertas
- Plan de acción
