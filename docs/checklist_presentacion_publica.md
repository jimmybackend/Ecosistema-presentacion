# Checklist final de presentación pública

Este checklist valida que la presentación pública refleje el estado real del ecosistema, sin sobrepromesas comerciales ni exposición de información sensible.

## Estado de módulos

- [ ] Existe matriz de estado por módulo.
- [ ] Billing no se presenta como terminado si está en roadmap.
- [ ] Integrations no se presenta como terminado si está en roadmap.
- [ ] Support no se presenta como terminado si está en roadmap.
- [ ] Jobs/Workers no se presenta como productivo si aún no lo es.
- [ ] Privacy/Compliance está explicado como parcial o roadmap según corresponda.

Referencias sugeridas de validación:
- `docs/estado_modulos.md`
- `docs/modulos.md`
- `docs/glosario_estados.md`
- `docs/roadmap.md`

## Lenguaje comercial

- [ ] El flujo operativo distingue visión y estado actual.
- [ ] Se evita lenguaje absoluto ("listo", "completo", "100% operativo") en módulos parciales.
- [ ] Se usa terminología de estados (`Disponible`, `Parcial`, `Read-only`, `Dry-run`, `Controlled`, `Roadmap`).

Referencias sugeridas de validación:
- `docs/flujo_operativo.md`
- `docs/uso_empresarial.md`
- `docs/faq.md`

## Contacto público

- [ ] Contacto público fue revisado.
- [ ] Los canales publicados están confirmados como oficiales.
- [ ] Existe consistencia entre `contacto.md` y la política de contacto.

Referencias sugeridas de validación:
- `contacto.md`
- `docs/politica_contacto_publico.md`

## Privacidad y datos sensibles

- [ ] No hay secretos ni dumps.
- [ ] No hay PII en imágenes o docs.
- [ ] La documentación no expone credenciales, tokens o datos internos.

Referencias sugeridas de validación:
- `docs/revision_seguridad_publica.md`
- `docs/seguridad_y_privacidad.md`

## Material visual

- [ ] Hay diagramas base.
- [ ] El material visual usa datos sintéticos o anonimización.
- [ ] Los assets mantienen lineamientos de publicación pública.

Referencias sugeridas de validación:
- `docs/diagramas.md`
- `docs/material_visual.md`
- `assets/README.md`

## Demo

- [ ] Hay guion de demo.
- [ ] La demo evita afirmar capacidades fuera de estado documentado.
- [ ] La narrativa de demo distingue claramente "visión" vs "hoy disponible".

Referencias sugeridas de validación:
- `docs/demo_guion.md`
- `docs/estado_modulos.md`

## Criterio Go / No-Go

### Go

- documentos alineados;
- estado real claro;
- sin secretos;
- sin promesas falsas.

### No-Go

- módulos parciales presentados como terminados;
- contacto no aprobado;
- capturas con datos reales;
- README desactualizado.
