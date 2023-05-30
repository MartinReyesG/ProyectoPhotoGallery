# Mi Primera Aplicación con Ionic y React: Galería de Fotos

Este proyecto es un tutorial paso a paso para crear una aplicación de Galería de Fotos utilizando Ionic y React. El objetivo es desarrollar una sola base de código que pueda ejecutarse en la web, iOS y Android.

## Requisitos

Para seguir este tutorial, necesitará instalar las siguientes herramientas:

- Node.js (se recomienda la versión LTS)
- Un editor de código (recomendamos Visual Studio Code)
- Interfaz de línea de comandos/terminal (CLI)

Además, se deben instalar las siguientes herramientas de Ionic:

- Ionic CLI (`ionic`)
- `native-run` (para ejecutar binarios nativos en dispositivos y simuladores/emuladores)
- `cordova-res` (para generar iconos de aplicaciones nativas y pantallas de inicio)

## Desarrollo

La aplicación de Galería de Fotos permitirá a los usuarios tomar fotos con la cámara de su dispositivo, mostrar las fotos en una cuadrícula y almacenarlas permanentemente en el dispositivo.

El desarrollo se divide en varios pasos:

### Tomando fotos con la cámara

Se utiliza la API de la Cámara de Capacitor para permitir a la aplicación tomar fotos con la cámara del dispositivo. Esto se hace inicialmente para la web, pero con algunos ajustes, también se puede hacer para iOS y Android. Se introduce un hook de React personalizado, `usePhotoGallery`, que gestiona las fotos para la galería.

### Guardando fotos en el sistema de archivos

Para que las fotos no se pierdan cuando se cierra la aplicación, se utiliza la API del Sistema de Archivos de Capacitor para guardar las fotos en el sistema de archivos del dispositivo. Se modifican las funciones del hook `usePhotoGallery` para permitir la escritura de archivos y la conversión de rutas de imágenes a base64.

### Cargando fotos desde el sistema de archivos

Por desgracia, no se pudo acceder a los detalles de esta sección del tutorial durante la elaboración de este README.

### Añadiendo funcionalidades móviles y desplegando en dispositivos móviles

Las últimas partes del tutorial tenían como objetivo mostrar cómo añadir capacidades móviles a la aplicación y cómo desplegar la aplicación en dispositivos móviles. Sin embargo, no se pudo acceder a estas secciones del tutorial durante la elaboración de este README.

## Conclusión

Ionic proporciona un conjunto robusto de herramientas que permiten a los desarrolladores crear aplicaciones móviles con tecnologías web. Este tutorial ilustra cómo se pueden utilizar estas herramientas para crear una aplicación de fotos funcional. A pesar de los obstáculos, el resultado es una aplicación que puede tomar, mostrar y almacenar fotos tanto en la web como en plataformas móviles.
