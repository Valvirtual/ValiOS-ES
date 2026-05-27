# ValiOS — Sistema operativo del negocio

Tu empresa corre sobre este archivo. Aquí están las reglas de operación
de ValiOS — cómo Claude lee el contexto, aprende de correcciones, mantiene
todo actualizado y crea skills nuevas.

---

## Contexto del negocio

Al inicio de cada conversación, leer:
1. `_memoria/empresa.md`
2. `_memoria/preferencias.md`
3. `_memoria/estrategia.md`

Para tareas visuales, consultar `identidad/design-guide.md`.
Usar el contexto de forma natural, sin listar lo leído.

---

## Flujo de trabajo

Verificar si existe skill en `.claude/skills/` antes de ejecutar cualquier tarea.
Al completar tarea repetible, preguntar:
> "Esto puede convertirse en una skill. ¿Quieres que la cree?"

---

## Aprender de correcciones

Cuando el usuario corrija algo o dé instrucción permanente, preguntar:
> "¿Quieres que lo guarde para no tener que repetirlo?"

Guardar en:
- Negocio → `_memoria/empresa.md`
- Preferencias → `_memoria/preferencias.md`
- Prioridades → `_memoria/estrategia.md`
- Regla general → `CLAUDE.md`

---

## Mantener contexto actualizado

Al terminar tarea que cambió algo relevante, preguntar:
> "Esto cambió algo en tu contexto. ¿Quieres que actualice la memoria?"

Ejecuta `/actualizar` para escaneo completo.

---

## Creación de skills

1. Verificar templates en `templates/skills/`
2. Preguntar si es local o global
3. Calibrar con `_memoria/empresa.md` y `_memoria/preferencias.md`
