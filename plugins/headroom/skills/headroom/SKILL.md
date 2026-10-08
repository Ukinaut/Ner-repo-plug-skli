---
name: headroom-optimization
description: Estrategias y herramientas de optimización de tokens y compresión de contexto con Headroom (CCR).
---

# Optimización de Tokens con Headroom

Headroom es una capa de optimización que implementa **Compress-Cache-Retrieve (CCR)** para reducir significativamente el consumo de tokens (entre 60% y 95%) en flujos de trabajo con agentes.

## Flujo de Trabajo
1. **Compresión reversible**: Las salidas voluminosas de herramientas, logs o listados extensos se resumen y se almacenan en caché local.
2. **Recuperación bajo demanda (`headroom_retrieve`)**: Si se requieren detalles específicos de un fragmento comprimido, se solicita el contenido original usando el hash o marcador correspondiente.
3. **Métricas (`headroom_stats`)**: Monitoreo de ahorro de tokens y eficiencia de contexto en la sesión.
