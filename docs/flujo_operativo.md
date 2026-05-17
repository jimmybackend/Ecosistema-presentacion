# Flujo operativo del sistema

El objetivo del ecosistema es conectar procesos de punta a punta.

## Flujo principal (visión integrada)

```text
Campaña
→ Short link
→ Click
→ Landing page
→ Visita
→ Formulario
→ Submission
→ Lead CRM
→ Notificación
→ Workflow
→ Reporte
→ IA operativa
```

## Explicación

1. Una empresa crea una campaña.
2. El sistema genera o administra links inteligentes.
3. Un visitante hace click.
4. El tráfico llega a una landing page.
5. Analytics registra visitas, sesiones y eventos.
6. El visitante llena un formulario.
7. El sistema guarda la submission.
8. CRM convierte la submission en lead.
9. Notifications avisa al equipo.
10. Workflow automatiza acciones.
11. Reports muestra resultados.
12. IA ayuda a resumir, analizar o proponer acciones.

## Estado actual del flujo

La secuencia anterior muestra la **visión integrada del producto**. En operación real, cada etapa avanza por módulo y puede estar en estados distintos.

| Etapa | Módulo relacionado | Estado actual | Qué se puede demostrar | Limitación actual |
|---|---|---|---|---|
| Campaña | CRM y campañas | Parcial | Alta y seguimiento de campañas en alcance actual | Cobertura comercial aún no completa para todos los escenarios |
| Short link | URL Locator | Controlled por flags | Creación y gestión de links con seguimiento de clicks | Publicación/edición sensible sujeta a permisos y flags |
| Click | URL Locator / Browser Analytics | Read-only | Registro y consulta de interacción de clicks | La explotación operativa completa se concentra en lectura |
| Landing page | Landing Pages | Parcial | Páginas de campaña activas y formularios base | Cobertura incompleta de casos avanzados |
| Visita | Browser Analytics | Read-only | Sesiones, pageviews y eventos consultables | Sin operación administrativa completa desde el módulo |
| Formulario | Landing Pages | Parcial | Formularios funcionales para captura inicial | No todos los flujos comerciales están cerrados |
| Submission | Landing Pages / CRM | Parcial | Registro de submissions y trazabilidad base | Hay escenarios con validaciones y automatizaciones aún en evolución |
| Lead CRM | CRM y campañas | Parcial | Conversión submission → lead y seguimiento comercial | Lifecycle comercial end-to-end todavía en expansión |
| Notificación | Mail / Notifications | Dry-run | Plantillas, previews y colas visibles para demo | Parte de ejecuciones reales sigue en simulación/control |
| Workflow | Workflow | Controlled por flags | Reglas, acciones y logs operativos en alcance controlado | Acciones de impacto real dependen de permisos y flags |
| Reporte | Reports | Parcial | Reportes de embudo, leads y campañas | Cobertura y exportaciones aún no completas |
| IA operativa | IA Operativa | Controlled por flags | Asistencia IA con propuesta y supervisión humana | Sin autonomía total para acciones críticas |

> El flujo completo representa la visión integrada del ecosistema. La implementación avanza por módulos seguros: primero lectura, luego simulación, después ejecución controlada por permisos y flags.

## Resultado esperado

La empresa puede entender el recorrido completo del ecosistema, visualizar qué partes ya son demostrables hoy y distinguir con claridad qué capacidades todavía están en evolución.

## Referencias

- Definiciones de estados: [`docs/glosario_estados.md`](glosario_estados.md).
- Estado comercial por módulo: [`docs/estado_modulos.md`](estado_modulos.md).
