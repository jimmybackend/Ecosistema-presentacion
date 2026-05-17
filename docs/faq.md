# Preguntas frecuentes

## ¿Este repositorio contiene el código del producto?

No. Este repositorio es informativo y comercial. No debe contener código productivo privado ni secretos.

## ¿El sistema ya está terminado?

El repositorio describe la visión completa del producto y su línea de desarrollo modular. Cada módulo puede tener distintos niveles de avance.
Para estado real por módulo (sin sobrepromesas), consulta la matriz pública en [`docs/estado_modulos.md`](estado_modulos.md).

## ¿Qué significan los estados públicos?

Los estados oficiales son: **Disponible**, **Parcial**, **Read-only**, **Dry-run**, **Controlled** y **Roadmap**.

- **Disponible**: capacidad operativa en alcance validado.
- **Parcial**: cobertura incompleta del escenario final.
- **Read-only**: consulta sin escritura.
- **Dry-run**: simulación sin impacto real.
- **Controlled**: ejecución real con permisos, validaciones y flags.
- **Roadmap**: en diseño o planeación, sin disponibilidad operativa confirmada.

Referencia principal: [`docs/glosario_estados.md`](glosario_estados.md).

## ¿Es SaaS o sistema interno?

Puede evolucionar como sistema interno privado, SaaS multi-tenant o modelo híbrido.

## ¿La IA ejecuta acciones sola?

No debería. La IA debe apoyar, resumir y proponer. Las acciones importantes requieren aprobación humana y control por permisos.

## ¿Se incluyen datos reales?

No. Este repositorio no debe incluir datos reales de clientes, credenciales, dumps completos ni información sensible.

## ¿Dónde está el guion recomendado de demo?

Consulta [`docs/demo_guion.md`](demo_guion.md), que separa visión, avance real, límites operativos y roadmap para una presentación honesta de 10–15 minutos.
