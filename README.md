# ⚡ Antigravity Skills & Plugins Suite

Colección integral de **Skills**, **Plugins** y **Rules** de alta gama para **Google Antigravity IDE (AGY)**.

Diseñados para elevar la ingeniería de software, dirección de diseño de interfaces de usuario (UI/UX), interacción con movimiento fluido, navegación automatizada y optimización de contexto.

---

## 📦 Contenido del Repositorio

### 🎨 1. Skills de Diseño & UX
Ubicados en `/skills/`:

| Skill | Descripción |
| :--- | :--- |
| **`emil-kowalski`** | Principios de diseño de interacción, física de resortes (`spring physics`), micro-animaciones fluidas con Framer Motion y layout transitions interrumpibles. |
| **`taste`** | Criterio y juicio estético editorial. Rechazo activo a la homogeneidad genérica de IA, uso de tipografías distintivas (*Syne, Space Grotesk, Clash Display*) y paletas con tensión y carácter. |
| **`impeccable`** | Pulido visual de alta precisión y calidad quirúrgica. Espaciado matemático estricto en escala de 8px, bordes translúcidos de alta fidelidad, sombras multicapa y checklist anti-slop. |

---

### 🧩 2. Plugins & MCP Tools
Ubicados en `/plugins/`:

| Plugin | Tipo / MCP | Descripción |
| :--- | :--- | :--- |
| **`frontend-design`** | Dirección Visual | Guía y reglas de arquitectura visual distintiva, balance de paletas y maquetación de alto impacto. |
| **`playwright`** | Browser MCP | Navegación e inspección web automatizada end-to-end con Playwright para pruebas y QA visual. |
| **`figma`** | Figma MCP | Inspección de capas, estilos, tokens de diseño y transformación directa a React y Tailwind CSS. |
| **`headroom`** | Token Optimizer | Estrategias de optimización de tokens y compresión contextual mediante Content-Cognitive Reduction (CCR). |
| **`mempalace`** | Memoria Persistente | Sistema de memoria a largo plazo para registrar contexto, decisiones y arquitectura entre sesiones. |

---

### 📜 3. Rules (Reglas de Conducta)
Ubicadas en `/rules/`:
- **`frontend-design.md`**: Pautas obligatorias de diseño visual, jerarquía y accesibilidad.
- **`mempalace.md`**: Procedimientos de coordinación y persistencia de memoria.

---

## 🚀 Instalación en Antigravity IDE

Para instalar estas personalizaciones en tu entorno de Antigravity:

### Opción A: Configuración Global (Recomendada)
Copia las carpetas a tu directorio de configuración global de Gemini/Antigravity:
```bash
# Windows PowerShell
Copy-Item -Path "skills" -Destination "$env:USERPROFILE\.gemini\config\skills" -Recurse -Force
Copy-Item -Path "plugins" -Destination "$env:USERPROFILE\.gemini\config\plugins" -Recurse -Force
Copy-Item -Path "rules" -Destination "$env:USERPROFILE\.gemini\config\rules" -Recurse -Force
```

### Opción B: A nivel de Proyecto (Workspace)
Copia las carpetas dentro del directorio `.agents/` en la raíz de cualquier repositorio:
```text
mi-proyecto/
├── .agents/
│   ├── skills/
│   ├── plugins/
│   └── rules/
└── src/
```

---

## 👤 Autor & Licencia
- **Usuario**: [Ukinaut](https://github.com/Ukinaut)
- **Licencia**: MIT
