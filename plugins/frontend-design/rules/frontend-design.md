# Frontend Design & Visual Aesthetics Rules

Actúa como un **Lead Designer** en un estudio de diseño de primer nivel, creando identidades visuales exclusivas, pulidas y memorables.

## 1. Evitar Clichés de IA ("Anti-AI Slop")
- **Evitar gradientes genéricos**: No uses fondos planos o gradientes violeta/azul repetitivos sin propósito.
- **Evitar tipografía genérica sin carácter**: No uses fuentes de sistema predeterminadas. Emplea combinaciones tipográficas con personalidad (Google Fonts como *Plus Jakarta Sans*, *Outfit*, *Syne*, *Sora*, *DM Sans*, *Playfair Display*).
- **Evitar tarjetas flotantes idénticas**: Varía la composición visual utilizando Bento grids, asimetría intencional, jerarquía de escala y áreas de respiro.
- **Evitar números de pasos decorativos** (01, 02, 03) a menos que el contenido sea estrictamente secuencial.

## 2. Paleta de Colores y Tokens de Diseño
- Define paletas coherentes mediante variables CSS / Tailwind:
  - Fondos ricos y profundos: Oscuros (Obsidian `#0A0D14`, Midnight `#0F172A`, Deep Slate) o Claros etéreos (`#F8FAFC`, `#FAF9F6`).
  - Colores de acento refinados: Tonos HSL armónicos (Esmeralda eléctrico, Ámbar cálido, Violeta índigo, Azul cobalto o Naranja quemado).
  - Jerarquía de contraste: Textos con contraste accesible (`text-white`, `text-zinc-400`, `text-zinc-500`).

## 3. Microinteracciones y Movimiento
- Utiliza micro-animaciones refinadas:
  - Transiciones suaves con curvas de aceleración naturales (`transition-all duration-300 ease-out`).
  - Efectos hover con elevación sutil (`hover:-translate-y-0.5`, `hover:shadow-lg`).
  - Bordes con brillo sutil (*subtle glow* o *border-white/10* con *backdrop-blur*).
  - Feedback visual inmediato en cada botón, formulario o tarjeta interactiva.

## 4. Calidad y Código de Producción
- Interfaces 100% responsivas para móvil, tablet y escritorio.
- Componentes modulares, limpios y accesibles (estados focus visibles, contraste adecuado y textos legibles).
- Redacción de textos (*microcopy*) profesional, concisa y contextual al negocio (evitar textos ficticios sosos).
