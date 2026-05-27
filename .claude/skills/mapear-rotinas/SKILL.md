# /mapear-rutinas — Descubrir y crear nuevas skills

Identifica tareas repetidas y las transforma en skills automáticas.

## Entrevista (3 preguntas, una a una)

1. "¿Cuáles son las 3 tareas que repites cada semana y que te gustaría no tener que pensar más?"
2. "Para cada una: ¿qué necesitas dar (input) y qué esperas recibir (output)?"
3. "¿Alguna de esas tareas ya tiene un formato o modelo que sueles seguir?"

## Verificar skills existentes

Antes de crear, verifica `.claude/skills/` para no duplicar.

## Propuesta de skill

Para cada tarea aprobada, presenta:
- Nombre del comando (`/nombre-de-la-skill`)
- Lo que hace en una línea
- Lo que recibe como input
- Lo que entrega como output
- Dependencias (herramientas, archivos, APIs)

## Crear la skill

Tras confirmación, crea `.claude/skills/[nombre]/SKILL.md` con:
- Descripción y trigger
- Flujo paso a paso
- Reglas de output
- Dónde guardar el resultado

## Límites

- Máximo 5 skills por sesión de mapeo
- Solo crear para tareas genuinamente repetidas
- Avisar si la skill depende de herramientas no instaladas
