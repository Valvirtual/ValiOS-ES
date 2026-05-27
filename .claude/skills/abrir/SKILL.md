# /abrir — Iniciar sesión de trabajo

Carga el contexto del negocio y prepara a Claude para trabajar.

## Qué hacer

Lee estos archivos en orden:
1. `_memoria/empresa.md`
2. `_memoria/preferencias.md`
3. `_memoria/estrategia.md`
4. `identidad/design-guide.md` (solo si es probable trabajo visual)

## Verificación

Si los primeros tres archivos están vacíos o con texto de ejemplo → responder:
> "Los archivos de memoria están vacíos. Ejecuta /instalar primero para configurar tu negocio."

## Respuesta cuando todo está configurado

Formato máximo de 5 líneas en el terminal:
- Nombre del negocio + descripción corta (5-8 palabras)
- Foco estratégico actual
- Tono de comunicación (3-4 palabras)
- Pregunta: "¿Qué hacemos hoy?"

## Reglas

- No listar los archivos leídos
- No confirmar "leí el archivo X"
- Respuesta directa y lista para trabajar
