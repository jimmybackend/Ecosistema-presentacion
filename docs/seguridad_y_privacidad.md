# Seguridad y privacidad

La plataforma se diseña con una regla central: proteger datos antes de activar funciones peligrosas.

## Principios

- No exponer secretos.
- No mostrar contraseñas, tokens, hashes ni API keys.
- No mostrar PII completa sin permisos.
- No aceptar `tenant_id` desde request.
- Usar permisos por módulo.
- Usar CSRF en acciones POST.
- Separar lectura, simulación y ejecución real.
- Activar funciones peligrosas sólo por flags.
- Auditar acciones importantes.

## Estados operativos

### Read-only

Permite consultar información sin escribir en base de datos.

### Dry-run

Permite simular una acción y ver qué ocurriría sin modificar datos.

### Controlled

Permite ejecutar acciones reales sólo con permisos, validaciones y flags activas.

## Privacidad

El sistema debe proteger:

- Emails.
- Teléfonos.
- IPs.
- User agents.
- URLs completas.
- Coordenadas.
- Archivos internos.
- Tokens.
- Configuraciones privadas.
- Mensajes.
- Metadata sensible.

## IA responsable

La IA debe funcionar con contexto filtrado, auditoría y aprobación humana cuando proponga acciones.
