# Notas sobre configuraciones del editor

Este repositorio incluye un archivo opcional de configuración de editor en `.vscode/settings.json` para conveniencia del equipo.

Por favor, ten en cuenta lo siguiente:

- No incluyas credenciales, claves API ni secretos en ningún archivo del repositorio. Usa los secretos de GitHub Actions o variables de entorno en CI para información sensible.
- Estas configuraciones son valores por defecto de workspace; pueden contener preferencias del autor. Si quieres usar tus propias preferencias, configúralas en tu configuración de usuario local (User Settings) o en un archivo de workspace local no versionado.
- Si el archivo `.vscode/settings.json` no te conviene, simplemente crea una configuración local y elimina/ignora los cambios en tu entorno.

Si detectas que el repo contiene configuraciones personales no deseadas, por favor propon un cambio (PR) para sanearlas.

## Seguridad y buenas prácticas

- Asegúrate de que no hay secretos en el repositorio: evita subir archivos como `.env`, `ibmcloud_api_key.txt` o archivos con extensiones `.key/.pem`.
- Usa GitHub Secrets para claves de API y datos sensibles cuando configures workflows (Settings → Secrets → Actions).
- Antes de abrir un PR, revisa los cambios para comprobar que no se incluyen credenciales accidentalmente.
- Considera añadir herramientas de detección de secretos (por ejemplo: git-secrets, truffleHog o el escáner de GitHub) en la CI para prevenir filtraciones.

