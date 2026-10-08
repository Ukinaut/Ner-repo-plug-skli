---
name: figma-mcp
description: Procedimiento para inspeccionar archivos, capas, estilos y tokens de diseño en Figma y transformarlos en código React/Tailwind de alta fidelidad.
---

# Figma MCP Integration & Design-to-Code

Permite al agente conectarse a la API de Figma para extraer medidas exactas, paletas de colores, tipografías y estructura de componentes.

## Flujo de Trabajo:
1. **Configurar Token**: Asegurarse de tener un Personal Access Token configurado en `mcp_config.json` o en las variables de entorno.
2. **Inspección de Archivo**:
   - Obtener la estructura del archivo mediante su File Key (`figma.com/design/<file-key>/...`).
   - Extraer estilos y variables de diseño (colores, radios de borde, tipografía).
3. **Conversión a Código**:
   - Mapear auto-layouts de Figma directamente a Flexbox / Grid de CSS o clases de Tailwind.
   - Respetar espaciados y jerarquías idénticas a las definidas por el diseñador.
