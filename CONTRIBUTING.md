# Contributing

Gracias por contribuir. Por favor sigue estas pautas básicas antes de enviar un pull request:

1. No subir secretos ni credenciales
   - No añadas claves API, contraseñas, tokens o archivos de configuración con datos sensibles al repositorio.
   - Usa GitHub Actions Secrets para almacenar claves necesarias para CI/CD.

2. Formato y pruebas
   - Ejecuta las pruebas y linters disponibles localmente antes de abrir PRs.
   - Añade descripciones claras y pasos de verificación en el PR.

3. Configuraciones del editor
   - Evita imponer preferencias personales (p. ej. tamaño de fuente) en archivos versionados.
   - Si necesitas compartir settings útiles para el equipo, asegúrate de que no contienen datos sensibles.

4. Revisión de seguridad
   - Revisa tus cambios para detectar secretos antes de push.
   - Si detectas un secreto ya subido, notifícalo inmediatamente y rotalo (revoca la clave) — no lo publiques en comentarios.

5. CI y despliegue
   - Añade sólo los pasos necesarios para construir/empacar la aplicación en CI. No incluyas credenciales en los archivos del repositorio.

Gracias por ayudar a mantener este repositorio seguro y saludable.
