# RECSA — Dashboard Integral P&L

Dashboard unificado de Pérdidas & Ganancias que integra las 3 herramientas de gestión financiera de RECSA en una sola aplicación.

## Acceso
https://isamarketing.github.io/recsa-dashboard-pl/

## Herramientas integradas

### P&L (7 tabs)
- **Resumen Ejecutivo** — KPIs, top ganadores/perdedores, P&L por línea
- **Por Línea** — revenue, CMG, EBITDA por familia de producto
- **Por Producto** — detalle completo con filtros y búsqueda
- **Pricing Estratégico** — breakeven, +10%, +20% por producto
- **Alertas** — productos con costo > precio, EBITDA negativo
- **Simulador** — ajuste precios y vea el impacto en EBITDA
- **Vista Unitaria** — waterfall de costos USD/kg

### 📦 Inventario (integrado)
- Costo financiero por producto basado en stock standard
- Lead time y stock de seguridad editables → actualiza P&L automáticamente

### 💼 Asignación de Gastos (integrado)
- Carga Excel de gastos operativos
- Asignación RECSA/VIVALCE con sliders
- Output (GF y MOD USD/kg) → actualiza P&L automáticamente

## Actualización
1. **Costos MP / Precios / Volúmenes** → Cargar Excel Master (botón 📂)
2. **Gastos operativos** → Tab "Asig. Gastos" → cargar Excel → se recalcula P&L
3. **Inventario** → Tab "Inventario" → ajustar lead times → se recalcula P&L
