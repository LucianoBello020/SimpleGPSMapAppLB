# Vulnerabilidades

Estado: peligroso
información : buscar ubicación GPS
Descripción: Las aplicaciones maliciosas pueden utilizar el permiso de ubicación para saber nuestra ubicación en tiempo real y además puede consumir energía adicional de la batería.

Estado: Peligroso
información: Ubicación aproximada basada en red
Descripción: Acceder a fuentes de ubicación aproximada, como la base de datos de la red móvil, para determinar una ubicación aproximada del teléfono, cuando esté disponible. Las aplicaciones maliciosas pueden usar esto para determinar aproximadamente dónde se encuentra

Estado: Normal
Información: Ver el estado de red
Descripción: Permite a una aplicación ver el estado de todas las redes.

Estado: Normal
Información: Acceso completo a internet.
Descripción: Permite a una aplicación crear sockets de red.


#Analisis de certificados

titulo: Firma de aplicación
severidad: información
Información: la aplicación esta firmada con un certificado de firma de código.

titulo: Aplicación firmada con certificado de depuración.
severidad: Alta
Información: Aplicación firmada con un certificado de depuración, La aplicación de producción no debe enviarse con un certificado de depuración.
 

# Análisis de Manifiesto

Emitir: La aplicación se puede instalar en una versión de Android con parche vulnerable Android 7.0 minSDK=24
Severidad: Alta
descripción: Esta aplicación se puede instalar en una versión de Android que tenga múltiples vulnerabilidades sin corregir. estos dispositivos no recibirán actualizaciones de seguridad.

Emitir: Depuración habilitada para la aplicación.
Severidad: Alta
descripción: La depuración se habilito en la aplicación, lo que facilita que la ingeniería inversa enlace la depuración a esto. esto permite volcar un seguimiento y acceder a clases auxiliares de depuración.

Emitir: Se puede hacer una copia de los datos de la aplicación.
Severidad: Alerta
descripción: permite a cualquier persona hacer una copia de seguridad de los datos de su aplicación a través de adb. Permite a los usuarios que habilitaron la depuración USB copien datos de aplicaciones fuera del dispositivo.

