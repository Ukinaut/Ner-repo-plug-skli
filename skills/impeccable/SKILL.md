---
name: impeccable
description: Criterio de dirección de diseño de alta precisión (Impeccable). Pulido quirúrgico, diseño pixel-perfect, consistencia visual rigurosa y eliminación de cualquier artefacto genérico.
---

# Impeccable Design Craft

Impeccable aporta el juicio y la mirada crítica de un Director de Diseño senior a cada pantalla y componente generado.

## 1. Mandato de Calidad Quirúrgica
- **Espaciado y Ritmo Matemático**: Todo espaciado debe pertenecer a una escala consistente (4px / 8px / 12px / 16px / 24px / 32px / 48px / 64px). Cero márgenes improvisados o desalineados.
- **Micro-Detalles de Bordes y Sombras**:
  - Bordes translúcidos de alta fidelidad (`border-white/10` sobre fondos oscuros; `border-black/5` sobre fondos claros).
  - Sombras multicapa: una sombra difusa amplia más una sombra de contacto cercana para dar volumen realista.
  - Sutil *inner glow* o reflejo superior (`box-shadow: inset 0 1px 0 rgba(255,255,255,0.1)`).
- **Consistencia en Estados**: Cada componente interactivo debe tener definidos sus 5 estados:
  1. Default
  2. Hover
  3. Active / Pressed
  4. Focus visible (anillo de foco accesible sin romper la estética)
  5. Disabled

## 2. Anti-Slop Check (Criterio de Aprobación)
Antes de dar por terminado cualquier componente, verificar:
- [ ] ¿Hay suficiente contraste en todos los textos secundarios?
- [ ] ¿Los botones tienen jerarquía inequívoca (Primary, Secondary, Ghost, Destructive)?
- [ ] ¿El texto es conciso, humano y directo (sin texto genérico de relleno)?
- [ ] ¿Los inputs tienen labels claros y mensajes de error contextuales?
