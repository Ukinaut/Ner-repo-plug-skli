---
name: frontend-design
description: Guía de diseño visual distintivo, dirección estética de alto impacto y arquitectura de UI moderna.
---

# Frontend Design Skill

Aplica este procedimiento cuando construyas, rediseñes o maquetes cualquier interfaz de usuario (páginas, componentes, landing pages o dashboards).

## Metodología en 3 Fases:

### 1. Definición de la Identidad Visual y Audiencia
- **Propósito**: Identificar el producto, la audiencia y la vibra deseada (ej. Tienda de moda urbana, dashboard analítico, e-commerce minimalista o tech moderno).
- **Tipografía**:
  - Título/Display: Tipografía distintiva con fuerza y carácter (*Syne*, *Outfit*, *Plus Jakarta Sans*, *Cinzel*, *Sora*).
  - Cuerpo/Lectura: Tipografía limpia y ultra legible (*Plus Jakarta Sans*, *Inter*, *DM Sans*).
- **Paleta de Color**:
  - Color base (Fondo y superficies: 60%)
  - Color secundario (Texto, bordes y estructuras: 30%)
  - Color de acento (Botones de acción clave, badges, highlights: 10%)

### 2. Estructura y Composición Visual
- **Hero Section**: Primera impresión memorable (tipografía de gran escala, elementos interactivos o visuales destacados).
- **Layouts Asimétricos / Bento Grids**: Distribución de tarjetas de diferentes dimensiones y pesos visuales para evitar cuadrículas monótonas.
- **Acabados Premium**:
  - Bordes translúcidos (`border border-white/10` o `border-zinc-800`).
  - Desenfoque de fondo (*Glassmorphism* con `backdrop-blur-md bg-white/5` o `bg-black/40`).
  - Sombras con profundidad y resplandor sutil.

### 3. Dinamismo y Microinteracciones
- Hover en botones, enlaces y tarjetas con feedback instantáneo.
- Animaciones de entrada escalonadas (*staggered animations*) usando Tailwind o Framer Motion.
- Estados de carga (skeleton loaders elegantes) y retroalimentación en formularios.
