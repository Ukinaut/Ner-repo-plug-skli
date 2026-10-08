---
name: emil-kowalski
description: Principios de diseño de interacción, micro-animaciones y física de movimiento de Emil Kowalski (Framer Motion, animaciones interrumpibles, layout animations y detalles de alta gama).
---

# Emil Kowalski - Design Engineering & Motion Craft

Esta habilidad incorpora los principios de ingeniería de diseño y animación de Emil Kowalski (autor de animations.dev).

## 1. Filosofía de Movimiento
- **Animaciones Intencionales**: Cada animación debe responder a un propósito claro: indicar causa/efecto, guiar el foco de atención o dar feedback táctil. Si no agrega valor, no se anima.
- **Física de Resortes (Spring Physics)**:
  - Evitar curvas lineales o `ease-in-out` estándar para componentes interactivos dinámicos.
  - Usar resortes con amortiguación natural:
    - *Rápido y ágil (botones, tooltips)*: `stiffness: 400, damping: 30`
    - *Suave y elegante (modales, drawers)*: `stiffness: 300, damping: 32`
    - *Orgánico (cards expandibles)*: `stiffness: 260, damping: 25`
- **Animaciones Interrumpibles**: Si el usuario cancela o hace clic rápido, la animación nunca debe saltar bruscamente; debe transicionar fluidamente desde su estado actual.

## 2. Técnicas Clave en Framer Motion & CSS
- **`layout` y `layoutId`**: Usar animaciones compartidas de layout para pestañas seleccionadas, carritos desplegables o transformaciones de elementos (shared element transitions).
- **Entradas y Salidas coordinadas**: Usar `AnimatePresence` con `mode="wait"` o `mode="popLayout"` para transiciones sin saltos de altura o posición.
- **Microinteracciones en Hover y Tap**:
  - `whileHover={{ scale: 1.02 }}`
  - `whileTap={{ scale: 0.98 }}`
- **Rendimiento**: Animar exclusivamente `transform` y `opacity` con aceleración por GPU.
- **Accesibilidad**: Respetar siempre `prefers-reduced-motion`.
