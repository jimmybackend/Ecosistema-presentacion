# Módulos del Ecosistema

## Base de datos canónica

La base de datos canónica define las tablas reales del sistema. Es la fuente de verdad para evitar inventar columnas, relaciones o estructuras no existentes.

## Core Admin

Es el centro administrativo del ecosistema. Desde aquí se navegan módulos, permisos, dashboards, vistas operativas, health checks y configuración.

## Auth, roles y permisos

Controla login, sesiones, usuarios, roles, permisos y acceso a rutas protegidas.

## Ecosistema Drive

Administra archivos, carpetas, buckets, versiones, logs de acceso, uso de almacenamiento, reparación, subida y descarga controlada.

## URL Locator

Gestiona short links, clicks, detalle de links, idiomas, smart links, creación/edición controlada y redirecciones públicas por flags.

## Landing Pages

Permite trabajar con páginas de campaña, formularios, visitas, submissions y conversiones.

## Browser Analytics

Mide sesiones, pageviews, eventos, atribución y rollups para entender el comportamiento digital.

## CRM y campañas

Convierte submissions en leads, relaciona campañas, da seguimiento comercial y permite ver el estado de oportunidades.

## Mail / Notifications

Administra plantillas, previews, colas de notificación y envíos controlados.

## Workflow

Orquesta reglas, acciones, ejecuciones y logs. Permite automatizar procesos entre módulos.

## SaaS Core

Organiza tenants, settings por tenant, feature flags y preparación multi-tenant.

## Billing

Gestiona planes, precios, suscripciones, uso, invoices y pagos desde una lógica controlada.

## Security / Audit / Privacy

Agrupa MFA, API keys, dispositivos confiables, auditoría, privacidad, consentimientos, solicitudes de datos y retención.

## Integrations

Permite conectar proveedores externos, cuentas, tokens protegidos, webhooks y sync logs.

## Support

Integra tickets, respuestas, asignaciones, adjuntos protegidos, historial y chat de soporte.

## Reports

Genera reportes de embudo, leads, campañas, exports y dashboards.

## Jobs / Workers

Permite observar trabajos, intentos, workers, scheduled tasks y logs operativos.

## IA Operativa

Usa knowledge packs, propuestas IA, chat, aprobación humana y asistencia controlada para apoyar decisiones sin perder gobierno humano.

## Go-live

Agrupa checklist de producción, manual operativo, cockpit de preparación y onboarding de tenants.


## Criterio de lectura de estados

Para evitar contradicciones entre documentación comercial y técnica, cada módulo debe leerse usando exclusivamente estos estados: **Disponible**, **Parcial**, **Read-only**, **Dry-run**, **Controlled** y **Roadmap**.

Referencia: [`docs/glosario_estados.md`](glosario_estados.md).
