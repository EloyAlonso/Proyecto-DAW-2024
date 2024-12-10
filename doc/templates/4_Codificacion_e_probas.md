# FASE DE CODIFICACIÓN Y PRUEBAS

- [FASE DE CODIFICACIÓN Y PRUEBAS](#fase-de-codificación-y-pruebas)
  - [1- Codificación](#1--codificación)
  - [2- Prototipos](#2--prototipos)
  - [3- Innovación](#3--innovación)
  - [4- Pruebas](#4--pruebas)

> Este documento explica cómo se debe realizar la fase de codificación y pruebas.

## 1- Codificación

> Crea una carpeta en tu repositorio y sube el código frecuentemente.
>
> Mientras se va codificando la aplicación, se irán encontrando problemas y habrá que ir modificando aspectos del diseño. Estos cambios también se deben recoger en la documentación.

## 2- Prototipos

> A medida que se va codificando se crearán varios prototipos, preferentemente realizados con Figma. Para cada uno indicar una descripción de las funcionalidades implementadas.
>
> Debes ir incluyendo una muestra representativa de los prototipos de la aplicación.
>
> Los prototipos ayudan en el diseño de la aplicación. Puedes emplear:
>
> - [Sketch](https://www.sketch.com/)
> - [Figma](https://www.figma.com/). Recomendado
> - [Proto.io](https://proto.io/)
>
> La mejor opción es emplear Figma ya que esta es una herramienta en línea colaborativa. 
> **Comparte el prototipo con los profesores por medio de Figma o descarga el archivo local el cual subirás a tu repositorio de GitHub**.

## 3- Innovación

En caso de utilizar tecnologías diferentes a las estudiadas en el ciclo formativo, haz una descripción de los retos asumidos y cómo se resolvieron.

### Uso de Tecnologías

Durante el desarrollo de este proyecto, he adquirido experiencia en varias tecnologías gracias a mi trabajo diario en una empresa de desarrollo de aplicaciones. A continuación, se describen algunas de estas tecnologías:

- **Docker**: Utilizado para crear contenedores que permiten empaquetar una aplicación con todas sus dependencias, asegurando que se ejecute de manera uniforme en cualquier entorno. Docker facilita la creación de entornos de desarrollo consistentes y la implementación de aplicaciones en producción.

- **CakePHP**: Un framework de desarrollo rápido para PHP que proporciona una estructura sólida para desarrollar aplicaciones web. CakePHP facilita la organización del código y la implementación de funcionalidades comunes, lo que acelera el proceso de desarrollo.

- **Bootstrap**: Un framework de CSS que permite diseñar interfaces web responsivas y modernas de manera rápida y sencilla. Bootstrap proporciona una amplia variedad de componentes predefinidos y estilos que ayudan a crear aplicaciones web atractivas y funcionales.

- **OpenStreetMaps (Leaflet)**: Utilizado para integrar mapas interactivos en aplicaciones web. Leaflet es una biblioteca de JavaScript que facilita la visualización y manipulación de mapas, permitiendo agregar marcadores, capas y otros elementos interactivos.

- **SweetAlert**: Una biblioteca de JavaScript que permite mostrar alertas personalizadas y atractivas en aplicaciones web. SweetAlert facilita la creación de diálogos modales con diferentes estilos y funcionalidades, mejorando la experiencia del usuario al interactuar con la aplicación.

- **JsBarcode**: Utilizado de manera experimental para generar códigos de barras en la aplicación. Aunque actualmente no tiene una funcionalidad real implementada, JsBarcode permite crear códigos de barras personalizados mediante JavaScript, lo que podría ser útil en futuras versiones del proyecto.

Gracias a la experiencia adquirida con estas tecnologías en mi trabajo diario, he podido aplicarlas de manera efectiva en el desarrollo de este proyecto, mejorando la calidad y funcionalidad de la aplicación.

## 4- Pruebas

Deben describirse las pruebas realizadas y conclusiones obtenidas. Describir los problemas encontrados y cómo fueron solucionados.


La configuración inicial encontró problemas con las dependencias de CakePHP y las incompatibilidades de versiones.
Estos problemas se resolvieron identificando y utilizando versiones compatibles que no causaban problemas al lanzar la aplicación.

Además, hubo problemas con la carga de solicitudes AJAX que no daban resultados.
Estos problemas se resolvieron corrigiendo errores en el código ("despistes") que ocurrieron durante el proceso de carga de datos, lo que impedía la carga final.
En algunos casos, los valores nulos de ciertas variables corrompían la solicitud.
Estos problemas se resolvieron manejando los errores de estas variables.

