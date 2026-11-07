# APKs de ROWCORP

Coloca en esta carpeta los archivos `.apk` que quieras distribuir desde la página.

Después agrega cada app al archivo `../apks.json`, por ejemplo:

```json
[
  {
    "name": "Mi aplicación",
    "version": "1.0.0",
    "description": "Versión de prueba para Android.",
    "file": "apks/mi-aplicacion.apk"
  }
]
```

El campo `file` debe coincidir exactamente con el nombre del APK que subiste. Guarda y publica ambos cambios. La página generará un botón de descarga directa en su propio dominio.

Para subirlo sin GitHub Releases: en GitHub abre el repositorio `rowcorp/ROWCORP`, entra en la carpeta `apks`, pulsa **Add file → Upload files**, selecciona el APK y confirma el cambio en la rama `main`. Luego actualiza `apks.json` con ese archivo.
