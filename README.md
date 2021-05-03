# PWA-2021
Curso UTN-Full Stack. Módulo Programador Web Avanzado. 1er cuatrimestre 2021.

Murruni Pablo <murruni@gmail.com>
# Resumen
## Tecnología
+ Proyecto backend en nodejs
+ Ejecuta un servidor con api rest
+ Persiste en mysql
## Aplicación
Ni idea

# Instalación
## Requiere
* Acceso a base mysql
* Tener instalado: git npm
## Pasos
- Clonar el proyecto al equipo:
    - git clone https://github.com/murruni/PWA-2021.git nombre_carpeta
-  Descargar dependencias node:
    - cd nombre_carpeta
    - npm install
## Ejecución
+ Ejecutar app: `npm run start`
+ Ejecutar modo desarrollo: `npm run dev`
```
Revisar los modos de ejecución en el archivo package.json sección scripts.
El modo de desarrollo activa el modo debug del paquete visionmedia/debug para utilizar debug() en lugar de console.log(). 
Los mensajes debug() no se aparecen si el modo debug no está activo, así que se pueden dejar en el código.
El script de desarrollo diferencia el sistema operativo host con el paquete npm run-script-os. 
```
# Estructura del proyecto
## Carpetas y archivos
- */bin*: punto de acceso/ejecutables de la app. 
    - */bin/www.js*: carga el servidor y ejecuta el archivo app.js
- */public*: recursos accesibles que no requieren autorización. Incluye el index.html base.
    - *public/images*: imágenes
    - *public/javascripts*: archivos de funciones javascript frontend.
    - *public/stylesheets*: archivos de estilo.
    - *public/index.html*: archivo base html.
- */routes*: rutas o controladores de la app.
- */package.json*: archivo de configuración de dependecias del proyecto
- */package-lock.json*: archivo automático de configuración de versiones de las dependencias de las dependencias (bloquea la versión de las dependencias)
- */app.js*: archivo principal de la app.
- */README.md*: