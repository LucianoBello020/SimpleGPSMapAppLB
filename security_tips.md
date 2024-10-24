# Consejos de Seguridad

Depuración desactivada: Desactivar el modo de depuración en las versiones de producción de la aplicación. dejar esto activado en producción puede permitir que atacantes accedan a la información sensible y vulnerable.

Cifrado de datos: Utilizar cifrado para proteger los datos sensibles tanto en reposo de la aplicación como en tránsito, esto es importante tanto para los datos de contraseñas, tokens de autentificación y cualquier información personal

Seguridad de red: Asegurar de utilizar HTTPS para las comunicaciones de red, asi se evita utilizar redes de dudosa procedencia y evitar ataques.

Respaldo de datos: desactivar la opción de allowBackup para evitar que los datos de la aplicación puedan ser respaldados a través de ADB.

Protección de ingeniería Inversa: utilizar herramientas como ProGuard o R8 para ofuscar el código y prevenir la ingeniería inversa.

Proteger la aplicación de ataques de inyección SQL: así evitamos que accedan directamente con una consulta sql de forma imprevista a los datos de la aplicación.