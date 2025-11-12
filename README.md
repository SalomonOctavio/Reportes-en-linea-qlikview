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
- `/diagrams/arquitectura-qlikview.mmd`
- `/docs/kpis.md` (definiciones/periodicidad)
- `/docs/catálogo-reportes.md` (dominios/propietarios)
- `/uat/plan-uat.md` · `/uat/checklist-go-no-go.md`

## Nota
Caso anonimizado; se omiten cifras y datos sensibles.
