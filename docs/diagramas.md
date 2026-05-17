# Diagramas base (material visual mínimo)

Este documento reúne diagramas **conceptuales** para demo comercial y técnica sin exponer datos reales.

> Alcance: no incluye PDFs, no usa capturas de producción y no contiene PII, credenciales ni URLs privadas.

## 1) Flujo operativo ideal

```mermaid
flowchart LR
    A[Adquisición de lead] --> B[Landing / Form público]
    B --> C[Validación inicial]
    C --> D[CRM / Core Admin]
    D --> E[Clasificación y prioridad]
    E --> F[Automatizaciones y notificaciones]
    F --> G[Seguimiento comercial]
    G --> H[Conversión / cierre]
    H --> I[Onboarding]
    I --> J[Analítica y mejora continua]
```

## 2) Capas del ecosistema

```mermaid
graph TD
    P[Capa de Presentación<br/>Sitios, landings, formularios] --> O[Capa Operativa<br/>Core Admin, CRM, workflows]
    O --> D[Capa de Datos<br/>Base canónica, reportes, trazabilidad]
    O --> S[Capa de Seguridad<br/>Roles, permisos, auditoría, privacidad]
    O --> I[Capa de Integración<br/>Webhooks, conectores, mensajería]
    O --> A[Capa de Asistencia IA<br/>Copilotos con supervisión humana]
```

## 3) Estados de módulo (madurez)

```mermaid
stateDiagram-v2
    [*] --> ReadOnly
    ReadOnly --> DryRun: Validación controlada
    DryRun --> Controlled: Activación por alcance
    Controlled --> Productivo: Operación estable
```

## 4) Relación: Presentación, Core Admin y Base canónica

```mermaid
flowchart TB
    PR[Presentación<br/>Web pública / Demo] -->|Entradas controladas| CA[Core Admin]
    CA -->|Persistencia validada| BC[Base canónica]
    BC -->|Vistas agregadas| RP[Reportes públicos permitidos]
    CA -->|Gobernanza| AU[Auditoría / Trazabilidad]
```

## Uso recomendado en demo

- Mostrar primero el flujo operativo ideal para contexto de negocio.
- Luego explicar capas para ubicar responsabilidades técnicas.
- Alinear expectativas con estados de madurez antes de prometer alcance.
- Cerrar con la relación Presentación–Core Admin–Base canónica para reforzar control y trazabilidad.
