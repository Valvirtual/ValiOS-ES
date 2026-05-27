# /guardar — Guardar trabajo en GitHub

Hace commit y push del trabajo actual a GitHub.

## Primera vez (repositorio no configurado)

Detecta con `git rev-parse --is-inside-work-tree`. Si falla, pregunta:
> "¿Tienes un repositorio GitHub para este proyecto? (1) Sí, tengo el enlace, (2) Quiero crear uno nuevo"

**Con repositorio existente:** inicializa localmente, commit inicial, añade remote, push.

**Repositorio nuevo:** verifica si `gh` CLI está instalado. Si sí, usa `gh repo create --private`. Si no, orienta a https://cli.github.com/ o a crear manualmente en GitHub.

## Commits normales

1. Ejecuta `git status` y muestra el resumen de cambios
2. Pide el mensaje del commit o genera uno automáticamente basado en los cambios
3. Ejecuta: `git add .` → `git commit -m "mensaje"` → `git push`
4. Confirma con la URL del repositorio

## Reglas de seguridad

- Nunca hacer force push sin petición explícita
- Nunca ejecutar `reset --hard` sin confirmación clara
- Si hay conflicto, ofrecer `git pull --rebase` antes de forzar
- Configurar `user.name` y `user.email` si es la primera vez
