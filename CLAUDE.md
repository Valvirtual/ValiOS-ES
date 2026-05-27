# ValiOS — Reglas de operación

Este archivo define cómo trabaja Claude dentro del ValiOS de Valvirtual.
Lee esto antes de cualquier cosa.

---

## Antes de empezar

Al inicio de cada conversación, carga siempre:
1. `_memoria/empresa.md` — quién es este negocio
2. `_memoria/preferencias.md` — cómo le gusta trabajar
3. `_memoria/estrategia.md` — qué está en foco ahora

Para trabajo visual, consulta también `identidad/design-guide.md`.
Aplica el contexto directamente — no hace falta listar lo que leíste.

---

## Cómo ejecutar tareas

Antes de cualquier tarea, verifica si ya existe una skill en `.claude/skills/`.
Si existe, úsala. Si no existe y la tarea es repetible, pregunta al final:
> "Esta tarea podría convertirse en una skill. ¿Quieres que la cree?"

---

## Cuando el usuario corrija algo

Si das una instrucción permanente o corriges mi comportamiento, pregunto:
> "¿Lo guardo para no tener que repetirlo la próxima vez?"

Qué guardar y dónde:
- Sobre el negocio → `_memoria/empresa.md`
- Preferencias de trabajo → `_memoria/preferencias.md`
- Foco y prioridades → `_memoria/estrategia.md`
- Regla de comportamiento → aquí en `CLAUDE.md`

---

## Mantener la memoria actualizada

Cuando una sesión cambie algo importante, pregunto:
> "Esto cambió algo relevante. ¿Actualizamos la memoria?"

También puedes ejecutar `/actualizar` en cualquier momento para una revisión completa.

---

## Crear una skill nueva

1. Ver los templates disponibles en `templates/skills/`
2. Preguntar si la skill es local (solo este proyecto) o global
3. Adaptar al contexto del negocio usando `_memoria/empresa.md` y `_memoria/preferencias.md`
