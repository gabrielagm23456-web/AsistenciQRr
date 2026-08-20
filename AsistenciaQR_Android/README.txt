ASISTENCIA QR - PROYECTO ANDROID

1. Instala Android Studio.
2. Abre la carpeta AsistenciaQR_Android.
3. Espera a que Gradle termine de sincronizar.
4. En el menú: Build > Build App Bundle(s) / APK(s) > Build APK(s).
5. El APK se genera normalmente en:
   app/build/outputs/apk/debug/app-debug.apk
6. Copia app-debug.apk a tu teléfono Android e instálalo.

La app solicita permiso de cámara, abre el sistema localmente dentro de la APK,
y conserva el inicio de sesión y los datos mediante el almacenamiento del WebView.
Para cargar Excel usa el selector de archivos del teléfono.
Para exportar Excel, el archivo se guarda en Descargas.

Credenciales actuales del sistema HTML:
Usuario: admin
Contraseña: 1234

Para cambiar estas credenciales, edita:
app/src/main/assets/index.html
Busca USUARIO_SISTEMA y CLAVE_SISTEMA.
