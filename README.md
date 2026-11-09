# Mi Tabata para Android

Proyecto Android WebView que incorpora el HTML corregido v2.

## Compilacion GRATIS sin instalar nada

1. Crea un repositorio nuevo PUBLICO de GitHub, SIN README.
2. Descomprime este ZIP. **Entra en la carpeta MiTabata_ANDROID_DESDE_CERO**.
3. Selecciona TODO lo que hay dentro (incluida la carpeta `.github`) y ARRASTRALO desde el Explorador de Windows a la pagina `upload files` de GitHub. **No arrastres la carpeta contenedora**.
4. Antes de confirmar, comprueba que los archivos se van a subir como `.github/workflows/crear-apk.yml`, `app/src/main/...`, `build.gradle` y `settings.gradle`.
5. Commit changes -> Actions/Comportamiento -> Crear APK Mi Tabata -> Run workflow.
6. Una vez que la ejecucion este verde, abre la ejecucion y descarga Artifacts -> MiTabata-APK. En el ZIP generado estara `app-debug.apk`.

NO subas directamente el archivo ZIP. NO traduzcas los nombres de archivo ni carpeta.

## Notas

- El cronometro, la interfaz y los sonidos se cargan como recursos locales.
- La fotografia de fondo del HTML proviene de Unsplash y solo se vera con conexion; sin internet funcionara el fondo de color.
- El APK es una compilacion de depuracion (debug), util para instalacion personal y pruebas, no una publicacion en Play Store.
- No se ha compilado ni probado el APK en este entorno.
