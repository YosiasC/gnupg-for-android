# Contribuir

Gracias por contribuir. Lee estas pautas antes de abrir PRs:

1. Haz un fork y crea una rama descriptiva: `feature/mi-cambio` o `fix/descripcion`
2. Ejecuta las comprobaciones locales: usa `format-code.sh` para C si existe.
3. Abre un PR contra la rama `master` de este repo, incluye descripción y checklist.
4. No incluyas credenciales ni secretos en los commits.

Notas específicas del repo:
- Este proyecto usa scripts de compilación ant/ndk; el runner público no incluye NDK/SDK. Indica en el PR si necesitas que prepare runners especiales.

Si el proyecto está marcado como UNMAINTAINED, contacta al propietario antes de cambios mayores.
