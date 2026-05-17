# Glosario de estados

Este glosario define los estados públicos para describir módulos y capacidades del ecosistema de forma consistente entre documentación comercial y técnica.

## Disponible

Capacidad operativa y utilizable dentro del alcance validado actualmente.

## Parcial

Capacidad implementada de forma incompleta. Cubre solo una parte del escenario funcional final.

## Read-only

Capacidad disponible únicamente para consulta. No permite escritura ni cambios persistentes.

## Dry-run

Capacidad de simulación. Ejecuta validaciones o previsualizaciones sin impactar datos ni integraciones reales.

## Controlled

Capacidad de ejecución real, habilitada bajo gobierno operativo: permisos, validaciones, feature flags y trazabilidad.

## Roadmap

Capacidad en diseño o planeación. No debe interpretarse como disponibilidad operativa confirmada.

## Notas de uso

- Estos términos deben escribirse exactamente como aparecen en este documento.
- Un módulo puede combinar estados por subcapacidad (por ejemplo: consulta en **Disponible** y escritura en **Controlled**).
- Ante duda, prevalece el estado más restrictivo para comunicación pública.
