# 

# 

# 

# 

# **UD07. Elaboración de documentación técnica y uso de aplicaciones de propósito general** {#ud07.-elaboración-de-documentación-técnica-y-uso-de-aplicaciones-de-propósito-general}

Juan Luis Nuñez Garcia   
Desarrollo de aplicaciones multiplataforma  
				15/05/2026

**ÍNDICE** 

[**UD07. Elaboración de documentación técnica y uso de aplicaciones de propósito general	1**](#ud07.-elaboración-de-documentación-técnica-y-uso-de-aplicaciones-de-propósito-general)

1 Analisis de necesidades 

Solucion Propuesta:   
Para resolver estos fallos se ha diseñado y hecho una solucion que esta basada en apache guacamole mediante la tecnologia de los contenedores de docker compose, esta arquitectura no es solo una mejora de software si no tambien un cambio en la seguridad de la empresa  
Deben centrarse en:   
Centralizacion del Acceso   
Aislamiento   
Cliente sin instalacion

"2. Estimación de Costes de Infraestructura".

<img width="1096" height="288" alt="image" src="https://github.com/user-attachments/assets/b7c7694f-a0bf-4dc0-83d1-d606619a12e4" />

 "3. Estrategia de Despliegue y Comunicación".
Para mover la aplicacion del servidor de produccion se descarta el uso de FTP normal debido a que transmite las credenciales y los datos en texto plano, y queda expuesto a ataques de interceptacion de tráfico 
En vez de usar ese, usariamos el SFTP y se ejecutaria sobre el puerto 22. Este sistema garantiza que tanto la autenticacion como la transferencia de archivos viajen completamente cifradas mediante algoritmos como AES, el flujo se automatizara desde el repositorio local hacia el servidor cloud usando claves criptograficas SSH en lugar de contraseñas manuales, lo que asi agiliza el despliegue y evita errores de personas y asegura tambien la integridad del codigo 
Mensajeria: 
Para poder hablar entre nosotros podemos usar Discord. Creamos unos canales especificos para organizar las tareas y asi avisar si hay algun problema tecnico 
Para no tener que estar mirando el servidor todo el dia configuraremos Webhooks. Esto sirve para que si el servidor se cae o se queda sin memoria, envie un mensaje directamente a nuestro canal de Discord, asi nos podemos enterar al momento y arreglarlo rapidamente 
