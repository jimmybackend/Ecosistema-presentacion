# Matriz comercial de estado por módulo

Esta matriz pública resume el avance real por módulo para evitar sobrepromesas. La visión del producto se mantiene, pero la disponibilidad debe leerse con criterio operativo real.

> Referencia de categorías: [`docs/glosario_estados.md`](glosario_estados.md).

| Módulo | Estado comercial | Estado técnico | Qué ya se puede mostrar | Qué está limitado | Próximo paso |
|---|---|---|---|---|---|
| Core Admin | Parcial | UI base y navegación operativa; cobertura funcional no completa para todos los módulos | Menú principal, dashboards base, health checks y configuración general | No consolida aún operación completa de todos los dominios (p. ej. Billing, Integrations, Support, Privacy y Jobs/Workers) | Completar vistas funcionales por dominio dentro de Core Admin y cerrar brechas de operación end-to-end |
| Auth, roles y permisos | Disponible | Control de acceso y sesiones operativo en alcance validado | Login, sesiones, usuarios, roles y rutas protegidas | Endurecimiento continuo de políticas avanzadas según entorno | Endurecer controles avanzados y validación continua por tenant |
| Ecosistema Drive | Controlled | Gestión de archivos y operaciones sensibles bajo permisos/flags | Subida/descarga controlada, carpetas, logs de acceso y versiones | Operaciones críticas sujetas a permisos y feature flags | Ampliar cobertura operativa y observabilidad por tenant |
| URL Locator | Controlled | Gestión de links con redirección pública condicionada por flags | Short links, clicks, detalle de links e idiomas | Publicación/edición sensible condicionada a control operativo | Robustecer gobierno de publicación y analítica de rendimiento |
| Landing Pages | Parcial | Flujo de páginas/formularios funcional en alcance acotado | Páginas de campaña, formularios, visitas y submissions | Cobertura incompleta frente a todos los escenarios de operación comercial | Completar flujos avanzados y estandarizar plantillas operativas |
| Browser Analytics | Read-only | Captura y consulta analítica priorizada sobre escritura | Sesiones, pageviews, eventos, atribución y rollups consultables | Sin operación de escritura administrativa completa desde este módulo | Incorporar controles de configuración y acciones operativas graduales |
| CRM y campañas | Parcial | Pipeline de leads y seguimiento operativo en expansión | Conversión de submissions a leads, seguimiento comercial y estado de oportunidades | Faltan capacidades para cubrir módulo comercial completo en todos los casos | Cerrar brechas de lifecycle comercial y automatizaciones asociadas |
| Mail / Notifications | Dry-run | Flujos de notificación con soporte de pruebas/simulación y control de envío | Plantillas, previews y colas visibles para demostración | Parte de ejecuciones se mantiene en simulación o bajo control estricto | Pasar de simulación a ejecución productiva por etapas y con métricas |
| Workflow | Controlled | Orquestación de reglas/acciones con ejecución gobernada | Reglas, acciones, ejecuciones y logs operativos | Acciones de impacto real dependen de permisos y flags activas | Incrementar cobertura de casos y endurecer validaciones de seguridad |
| SaaS Core | Parcial | Base multi-tenant y feature flags disponible en evolución | Tenants, settings por tenant y flags base | Preparación multi-tenant aún no cerrada para todos los módulos | Completar aislamiento operativo y estandarizar provisioning |
| Billing | Roadmap | Diseño y piezas parciales sin módulo funcional completo en Core Admin | Narrativa de planes/precios y lineamientos de cobro | No debe presentarse como módulo terminado ni como operación completa | Implementar UI funcional en Core Admin y cerrar ciclo de suscripción/cobro |
| Security / Audit / Privacy | Parcial | Seguridad/auditoría con cobertura superior a privacidad/compliance integral | MFA, auditoría base y controles de acceso | Privacy/Compliance no está completo como operación integral demostrable | Completar consentimientos, solicitudes de datos y retención con operación verificable |
| Integrations | Roadmap | Conectividad externa en implementación gradual, no consolidada | Diseño de conectores, webhooks y sync logs a nivel de propuesta/avance parcial | No hay módulo plenamente operativo de punta a punta para mostrarse como terminado | Priorizar conectores clave y habilitar operación controlada en Core Admin |
| Support | Roadmap | Capacidades en definición/avance parcial, sin módulo completo validado | Visión de tickets y flujo objetivo de atención | No debe mostrarse como operación de soporte totalmente implementada | Construir MVP operativo de tickets/asignaciones con trazabilidad |
| Reports | Parcial | Reportería funcional en parte del embudo operativo | Reportes de embudo, leads, campañas y dashboards base | Exportaciones y cobertura analítica total no completamente cerradas | Ampliar cobertura de reportes y calidad de datos por módulo |
| Jobs / Workers | Roadmap | Observabilidad y operación de jobs/workers aún no consolidada como módulo completo | Visión de trabajos e intentos a nivel de propuesta/avance parcial | No debe comunicarse como capacidad plenamente productiva | Implementar tablero operativo y controles de ejecución/reintento |
| IA Operativa | Controlled | Asistencia IA con supervisión humana y gobernanza de permisos | Knowledge packs, propuestas IA, chat y aprobación humana | Sin autonomía total para acciones críticas; requiere control humano | Mejorar trazabilidad de decisiones y controles de aprobación |
| Go-live | Parcial | Checklist y preparación operativa disponibles en evolución | Checklist de producción, manual operativo y onboarding base | Cobertura de playbooks aún no uniforme para todos los escenarios | Completar runbooks y validaciones finales por tenant/entorno |

## Lectura recomendada

1. Revisar visión modular en [`docs/modulos.md`](modulos.md).
2. Validar definiciones de estado en [`docs/glosario_estados.md`](glosario_estados.md).
3. Contrastar expectativas de lanzamiento con [`docs/roadmap.md`](roadmap.md).
