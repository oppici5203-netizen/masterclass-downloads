# Masterclass 1.5.0

Esta versión mejora la instalación y la recuperación de conexión. Conserva los partidos, carretes, fotos y perfiles de la app.

- Firma propia para las siguientes actualizaciones.
- Si se corta internet al abrir una cuenta, muestra el error y permite reintentar sin cambiar a la demo.
- Corrige la primera entrada por invitación para completarla con una sola pulsación.
- Protege las respuestas pendientes al cambiar de cuenta y evita canjear dos veces la misma invitación.

## Instalar

Requiere Android 9 o posterior y un teléfono ARM de 64 bits. Versión 1.5.0, código 7, paquete `cl.masterclass.fantasy`.

**Primera instalación:** descarga y abre `Masterclass-Android.apk`.

**Si ya tenías una versión de prueba 1.4 o anterior:** instala `Masterclass-Actualizar.apk`, ábrela y toca **Descargar Masterclass**. Después instala el principal encima. Es un paso único para conservar los datos al cambiar la firma. No desinstales la app para forzar la actualización.

Los dos archivos se comprueban con `SHA256SUMS`. El certificado público del principal es:

`27BFF4B1BDE82E1B84B2741E7F70243F644C779CDF367464247EE581D3FBF64E`

## Qué se comprobó y qué falta

La actualización conservó datos y sesión en emuladores Android 12; también se comprobó el reintento sin internet y una invitación válida entre dos emuladores. La instalación física todavía debe probarse. Las pruebas no garantizan ausencia total de errores.

La app instalada no necesita un PC encendido ni compartir Wi-Fi con él. El grupo privado sí necesita internet y permisos de acceso. El servicio gratuito puede pausar por inactividad.

iPhone sigue pendiente de firma Apple y prueba en un dispositivo real. No hay una IPA ni TestFlight disponibles en esta entrega. Expo Go es una vista previa distinta.

El acceso público al instalador no permite entrar al grupo ni ver sus fotos. No se publican código privado, credenciales ni recuerdos de los amigos.
