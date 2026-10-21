# Ventra · Implementador — descargas

**[Descargar la última versión](https://github.com/sebastianGarzonSX/ventra-implementador-releases/releases/latest)**

Aquí solo vive la última versión. El código va ofuscado y sin licencia de uso
no funciona: usuario y clave te los da Sebastián Garzón y son personales.

Cada versión trae dos zips:

- `ventra-implementador-extension-<v>.zip` — la extensión de Chrome
- `ventra-implementador-python-<v>.zip` — consola, MCP y skill para Claude Code; dentro va `LEEME.md` con la instalación paso a paso

## Instalación rápida

1. **Requisitos**: Chrome 114+, Python **exactamente** la versión de `PYTHON-VERSION` (dentro del zip de Python), Node 18+, Claude Code.
2. **Extensión**: descomprime en una carpeta fija → `chrome://extensions` → Modo de desarrollador → Cargar descomprimida → inicia sesión.
3. **Consola**: descomprime en `~/ventra-implementador` → `python3 ventra_licencia.pyc login`.
4. **Tokens**: `~/.config/ventra/cuentas.env` (permisos 600) con `<ALIAS>_PIT=…` y `<ALIAS>_LOC=<locationId>`. Nunca en un chat.
5. **Puente**: `node puente/servidor.js` en una terminal abierta; pega `~/.config/ventra/puente.token` en la isla → Ajustes → Puente.
6. **Claude Code**: `bash mcp/instalar.sh` y reinicia Claude Code.

> 🔴 Practica primero en una sub-cuenta de laboratorio: los workflows salen publicados salvo `--borrador`.

Diseñado por Sebastián Garzón. © 2026. Todos los derechos reservados. Ver `LICENSE`.
