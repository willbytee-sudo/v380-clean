# V380 Pro Clean para Android

Versión modificada de V380 Pro 2.2.81 para dispositivos arm64-v8a, con firma propia.

[Descargar la versión 2.2.81-clean.220](https://github.com/willbytee-sudo/v380-clean/releases/download/clean-220/V380Pro-2.2.81-DownloadUX-220.apk) · [Cambios y comprobaciones](https://github.com/willbytee-sudo/v380-clean/releases/tag/clean-220)

## Instalación y actualizaciones

Instala el APK de esta release manualmente una vez para incorporar el actualizador. Si ya utilizas una versión Clean firmada con la misma clave, Android puede actualizarla conservando los datos. No desinstales la app previamente.

La app consulta el canal estable de GitHub al abrirse, como máximo una vez cada 24 horas. Desde Acerca de puedes buscar manualmente. La descarga empieza al aceptarla; Android pide confirmar la instalación y, si procede, autorizar esta app como origen de instalación.

Cada APK se comprueba por tamaño, SHA-256, paquete, versión y certificado propio. El canal está en `updates/stable.json`. La consulta y descarga no incluyen identificadores de cámaras, cuentas ni dispositivos.

## Limpieza de almacenamiento

El actualizador conserva como máximo un APK pendiente, en almacenamiento privado. Retira descargas incompletas, instaladores ya instalados y pendientes que hayan caducado a las 24 horas al volver a abrir la app. Los archivos que está usando el instalador quedan protegidos frente a la limpieza.

Las cachés y archivos temporales generados tienen políticas acotadas. Las grabaciones y fotos que guardes expresamente se conservan y ocupan espacio hasta que las elimines. Esta limpieza no borra cámaras, credenciales ni ajustes.

## Comprobaciones

Esta release pasó verificación local de firma, alineación, DEX y CRC, junto con pruebas de descarga, cancelación, permisos y diez ciclos simulados de actualización. Conserva los recursos, las bibliotecas nativas y el SDK de cámara del APK de referencia. La prueba física de esta release en Samsung sigue pendiente.

La modificación no equivale a una garantía de ausencia total de tráfico del SDK original: las funciones remotas de cuenta, cámara y avisos pueden seguir necesitando servidores del proveedor.

Para una actualización de Android se requiere el mismo paquete y una firma compatible: [documentación de Android](https://developer.android.com/google/play/app-updates).

## Descargas de vídeo

Selector de horas con segundos y duraciones rápidas. Pausa opcional del visor, transferencia medida y resolución real. Se evita una copia intermedia al guardar un archivo completo compatible a ×1 con audio.

La descarga conserva la resolución que grabó la cámara. Elegir HD/SD en directo no cambia el archivo guardado en MicroSD. Guardar a ×2 reduce la duración de reproducción, no los datos que debe enviar la cámara. No se ha incorporado una conversión a SD ni se promete un multiplicador de velocidad de red. La velocidad indicada es una estimación basada en el crecimiento del archivo recibido.
