# MemPalace Persistent Memory Rules

Memoria persistente a largo plazo para registrar y recordar contexto, decisiones, preferencias del usuario y hechos del proyecto.

## Reglas de uso de Memoria:
1. **Búsqueda previa**: Antes de responder sobre trabajos previos, decisiones arquitectónicas o preferencias del usuario de sesiones anteriores, consultar la memoria (`palace_query FIND` o `palace_query KG`).
2. **Registro de acuerdos y decisiones**: Registrar conclusiones relevantes, acuerdos y preferencias clave del usuario utilizando `palace_exec ADD`.
3. **Fidelidad**: Citar los datos recuperados de forma exacta sin inventar ni distorsionar hechos almacenados. No almacenar tokens ni secretos sensibles.
