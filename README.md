# Administración Idewa

Workspace sin ramas (solo `main`), sincronizado entre los dos PCs de Antonio.
Al iniciar cada sesión de Claude se sube lo que haya en local y se baja lo remoto
(`~/.claude/scripts/sync-workspaces.sh`).

## Estructura
- `facturas/AAAA/Tn/emitidas/` y `facturas/AAAA/Tn/recibidas/`: facturas por trimestre.
- `documentacion/`: contratos, certificados y documentos de la empresa.
- `entregas-asesor/AAAA-Tn/`: lo que se envía al asesor cada trimestre.

## Nombres
`AAAA-MM-DD_<emisor-o-cliente>_<numero>.pdf`, por ejemplo `2026-11-04_onetelecom_F-2026-118.pdf`.

## Reglas
- Nada de contraseñas ni credenciales aquí.
- No se renombra ni borra una factura ya entregada al asesor.
