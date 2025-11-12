# Reportes en Línea (QlikView) — TELCO, 2013–2014

Plataforma de dashboards en línea para Marketing/Comercial/Operaciones: KPIs críticos (altas, desactivaciones, recargas, subsidios, tráfico, churn, rentabilidad, weekly). Modelo in-memory con QlikView (Desktop/Server/Publisher), acceso vía AccessPoint y seguridad por perfiles.

## Objetivo
Unificar la consulta de indicadores en una plataforma única, reduciendo tiempos de preparación y errores manuales.

## Arquitectura (resumen)
- QlikView Desktop → modelado QVW/QVD
- QlikView Server (QVS) + AccessPoint → acceso web
- QlikView Publisher → recarga y distribución
- Orígenes: TXT/CSV/XLS + conectores ERP/CRM/Billing

## Artefactos

📁 `/diagrams`  
- [`arquitectura-qlikview.mmd`](./diagrams/arquitectura-qlikview.mmd): arquitectura y componentes (Desktop, QVS/AccessPoint, Publisher, QVD/QVW, fuentes).

📁 `/docs`  
- [`kpis.md`](./docs/kpis.md): definiciones, periodicidad y TTGL/TTV (placeholders).  
- [`catálogo-reportes.md`](./docs/catálogo-reportes.md): dominios, KPIs, fuentes y owner.

📁 `/uat`  
- [`plan-uat.md`](./uat/plan-uat.md): validaciones de KPI vs fuente única, seguridad/perfiles y performance.  
- [`checklist-go-no-go.md`](./uat/checklist-go-no-go.md): criterios mínimos para liberar.

## Nota
Caso anonimizado; se omiten cifras y datos sensibles.
