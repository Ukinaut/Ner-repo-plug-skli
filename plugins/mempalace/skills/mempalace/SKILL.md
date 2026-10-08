---
name: mempalace-memory
description: Gestión y consulta de memoria a largo plazo con MemPalace (búsqueda, inserción y coordinación).
---

# MemPalace Memory Management

MemPalace proporciona memoria persistente estructurada para agentes autónomos y asistentes.

## Operaciones Principales
- **Buscar en el palacio**: Usar `palace_query` con comando `FIND` para localizar recuerdos exactos o semánticos por palabra clave o tema.
- **Guardar nuevo recuerdo**: Usar `palace_exec` con comando `ADD` indicando el ala (*wing*), sala (*room*) y contenido textual.
- **Hechos estructurados**: Usar comandos `KG` (Knowledge Graph) para registrar relaciones de entidades, estados y hechos temporales.
