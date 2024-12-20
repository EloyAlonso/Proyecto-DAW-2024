# Proyecto fin de ciclo

- [Proyecto fin de ciclo](#proyecto-fin-de-ciclo)
  - [Tablero del proyecto](#tablero-del-proyecto)
  - [Descripción](#descripción)
  - [Instalación / Puesta en marcha](#instalación--puesta-en-marcha)
  - [Uso](#uso)
  - [Sobre el autor](#sobre-el-autor)
  - [Licencia](#licencia)
  - [Índice](#índice)
  - [Guía de contribución](#guía-de-contribución)
  - [Enlaces](#enlaces)

## Tablero del proyecto

| Estado del Proyecto |
|---------------------|
| Proyecto en versión estable |

## Descripción

El proyecto consiste en crear una plataforma de comercio online para la venta directa de productos agrícolas en España. Nuestro objetivo principal es proporcionar a los agricultores un espacio donde puedan vender sus productos sin intermediarios, obteniendo precios justos por sus cosechas. Los usuarios podrán comprar directamente a los productores, lo que reducirá los costos de intermediación y garantizará la frescura de los productos. La plataforma estará desarrollada en CakePHP, utilizando Bootstrap, JS, HTML y CSS para asegurar su funcionalidad y una interfaz accesible. Con esta plataforma, buscamos promover la agricultura local y apoyar a los agricultores en su negocio.

## Instalación / Puesta en marcha

La web está desplegada en un servidor: [AgroDirecto](https://agrodirecto.serveblog.net/).

Para el despliegue de la web en un entorno local se puede optar por dos diferentes formas: desde Windows o desde Linux (o WSL).

### Despliegue en Linux (o WSL)

Recomendamos desplegar el proyecto desde WSL (Windows Subsystem for Linux), donde se puede clonar el repositorio de la web en una distribución ya configurada con Docker instalado internamente. Para instalar Docker dentro de WSL en lugar de usar Docker Desktop, que puede ralentizar la página, se sugiere ver este vídeo tutorial: [Instalar Docker en WSL](https://www.youtube.com/watch?v=cv7Iyohhmo4).

Para el despliegue en Linux o WSL, se debe ejecutar el script `build.sh`. Si el script no tiene permisos de ejecución, se pueden otorgar con el siguiente comando:
```bash
sudo chmod +x ./build.sh
```

### Despliegue en Windows

En caso de querer tener el repositorio en el sistema operativo Windows, simplemente se debe descargar Docker Desktop. Sin embargo, tenga en cuenta que la carga de la página será más lenta.

Para el despliegue en Windows, se debe ejecutar el script `windows.ps1`. Si PowerShell no tiene habilitada la ejecución de scripts, se recomienda usar el siguiente comando:
```powershell
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
```

### Consideraciones adicionales

Si se creó un archivo llamado "loaded" y se necesita redesplegar desde cero, se recomienda borrar ese archivo.

Ambos scripts (`build.sh` para Linux y WSL, y `windows.ps1` para Windows) deben ejecutarse y en unos minutos la web estará desplegada con su base de datos importada y funcionando.

Para acceder a la web una vez todo desplegado en un entorno local se puede acceder a traves de `http://localhost` y al gestor de base de datos (adminer) `http://localhost:8080`.

### Cuenta de adminer para gestionar la base de datos

Para acceder al adminer:  
Servidor: `db`  
Usuario: `usuario`  
Contraseña: `123456`

### Cuenta de usuario para pruebas

Para manejar cuentas de usuario se puede o registrar una nueva cuenta o iniciar sesion de este usuario:

Correo: `john@example.com`
Contraseña: `123456`

### Cuenta de vendedor para pruebas

Para probar las funcionalidades de la plataforma como vendedor, puedes utilizar la siguiente cuenta de prueba:

Correo: `bob@example.com`  
Contraseña: `123456`

## Uso

La aplicación web del proyecto permite a los usuarios registrarse, buscar productos agrícolas, agregarlos al carrito de compras y realizar pagos seguros. Los agricultores pueden crear y administrar sus tiendas, agregar productos y gestionar pedidos. Los usuarios también pueden dejar reseñas y calificaciones para los productos. La interfaz es intuitiva y fácil de usar, con un diseño moderno y responsive que se adapta a diferentes dispositivos. ¡Descubre la frescura de los productos agrícolas locales y apoya a los agricultores directamente desde tu hogar!


## Sobre el autor

Soy un desarrollador web full stack con amplia experiencia en el desarrollo de aplicaciones web. Mi pasión por la tecnología y mi habilidad para resolver problemas me han llevado a especializarme en el desarrollo de plataformas de comercio online. 

Mi objetivo principal con este proyecto es aprovechar un nicho de mercado sin explotar: la venta directa de productos agrícolas. Creo firmemente en apoyar a los agricultores locales y proporcionarles una plataforma donde puedan vender sus productos sin intermediarios. 

Como desarrollador, tengo un sólido dominio de tecnologías como CakePHP, Bootstrap, JS, HTML y CSS. Estas herramientas me permiten crear aplicaciones funcionales y con una interfaz accesible para los usuarios. 

Durante el proceso de creación del proyecto, puedes contactarme de manera fiable a través de mi correo electrónico [eloypro12@gmail.com](mailto:eloypro12@gmail.com). Estoy emocionado de trabajar en este proyecto y contribuir al crecimiento de la agricultura local. 

## Licencia

### Licencia del Proyecto

Este software está licenciado bajo la Licencia Pública General de GNU, versión 3.0 (GPL-3.0).  
Para más detalles sobre los términos de la GPL-3.0, consulta el archivo completo de la licencia en el siguiente enlace:  
[https://www.gnu.org/licenses/gpl-3.0.html](https://www.gnu.org/licenses/gpl-3.0.html)

### Notas sobre bibliotecas de terceros

Este proyecto utiliza las siguientes bibliotecas de terceros, que están sujetas a sus respectivas licencias:  

1. **Bootstrap**  
   - Licencia: [MIT](https://opensource.org/licenses/MIT)  
   - Más información: [https://github.com/twbs/bootstrap/blob/main/LICENSE](https://github.com/twbs/bootstrap/blob/main/LICENSE)  

2. **jQuery**  
   - Licencia: [MIT](https://opensource.org/licenses/MIT)  
   - Más información: [https://github.com/jquery/jquery/blob/main/LICENSE.txt](https://github.com/jquery/jquery/blob/main/LICENSE.txt)  

3. **Leaflet**  
   - Licencia: [BSD de 2 cláusulas](https://opensource.org/licenses/BSD-2-Clause)  
   - Más información: [https://github.com/Leaflet/Leaflet/blob/main/LICENSE](https://github.com/Leaflet/Leaflet/blob/main/LICENSE)  

4. **CakePHP**  
   - Licencia: [MIT](https://opensource.org/licenses/MIT)  
   - Más información: [https://github.com/cakephp/cakephp/blob/5.x/LICENSE](https://github.com/cakephp/cakephp/blob/5.x/LICENSE)  

5. **JsBarcode**  
   - Licencia: [MIT](https://opensource.org/licenses/MIT)  
   - Más información: [https://github.com/lindell/JsBarcode/blob/master/MIT-LICENSE.txt](https://github.com/lindell/JsBarcode/blob/master/MIT-LICENSE.txt)  

6. **SweetAlert**  
   - Licencia: [MIT](https://opensource.org/licenses/MIT)  
   - Más información: [https://sweetalert.js.org/guides/](https://sweetalert.js.org/guides/)  

---

### Permisos y restricciones

Al utilizar este software, aceptas los términos de la Licencia Pública General de GNU (GPL-3.0) y las licencias de los componentes de terceros mencionados anteriormente.  

- Este proyecto puede ser modificado, distribuido y utilizado libremente siempre que se cumplan los términos de la GPL-3.0 y las licencias de las bibliotecas de terceros.  
- Las obras derivadas deben ser distribuidas bajo la misma licencia (GPL-3.0).  
- Asegúrate de leer y entender las licencias de cada biblioteca para cumplir con sus términos específicos.  

---

© [Eloy Alonso Martínez], [2024]. Todos los derechos reservados.

## Índice

1. [Anteproyecto](doc/templates/1_Anteproxecto.md)
2. [Análise](doc/templates/2_Analise.md)
3. [Deseño](doc/templates/3_Deseño.md)
4. [Codificación e probas](doc/templates/4_Codificacion_e_probas.md)
5. [Implantación](doc/templates/5_Implantación.md)
6. [Referencias](doc/templates/6_Referencias.md)
7. [Incidencias](doc/templates/7_Incidencias.md)

## Guía de contribución

### Cómo empezar

1. Clona el repositorio desde [GitHub](https://github.com/EloyAlonso/AgroDirecto)
2. Configura tu entorno local siguiendo las instrucciones en este archivo `README.md`.
3. Asegúrate de instalar las dependencias necesarias.

### Áreas donde puedes contribuir

#### 1. **Chat entre usuarios y vendedores**
- Implementar un sistema de mensajería en tiempo real que permita a los usuarios comunicarse con los vendedores. Esto mejorará la gestión de pedidos, resolución de dudas y negociación de precios.
- Requiere trabajar con **WebSockets** o APIs en tiempo real.

#### 2. **Mejoras estéticas**
- Rediseñar la interfaz de usuario para hacerla más atractiva y moderna.
- Propuestas de mejora de la experiencia visual (usabilidad, accesibilidad, etc.).
- Utilizar frameworks como **Bootstrap** para facilitar el diseño.

#### 3. **Funcionalidades avanzadas de búsqueda**
- Añadir filtros de búsqueda más detallados como:
  - Categorías de productos avanzado.
  - Proximidad geográfica.
  - Rango de precios.
- Optimizar la base de datos para consultas rápidas.

#### 4. **Sistema de notificaciones**
- Implementar notificaciones en tiempo real para informar a los usuarios sobre:
  - Cambios en el estado de sus pedidos.
  - Nuevos productos disponibles.
  - Ofertas y promociones.
- Usar servicios como **Firebase** o sistemas de notificaciones push.

#### 5. **Integración con redes sociales**
- Facilitar el registro y acceso a la plataforma mediante cuentas de redes sociales como:
  - Facebook.
  - Google.
  - Twitter.
- Implementar opciones para compartir productos y ofertas en redes sociales.

#### 6. **Programa de fidelización**
- Crear un sistema de puntos o recompensas para incentivar la compra recurrente y la lealtad de los usuarios.
- Desarrollar funcionalidades como:
  - Canjear puntos por descuentos.
  - Niveles de membresía según las compras realizadas.

#### 7. **Soporte multilingüe**
- Añadir soporte para múltiples idiomas:
  - Español, inglés y otros idiomas según la región.
  - Implementar traducciones en archivos específicos para facilitar la internacionalización.

#### 8. **Análisis de datos y reportes**
- Proveer a los vendedores con herramientas de análisis de datos sobre:
  - Ventas realizadas.
  - Productos más populares.
  - Comportamiento de los clientes.
- Integrar gráficos y reportes dinámicos usando **Chart.js** o bibliotecas similares.

---

### Cómo contribuir

1. **Crea un fork del repositorio** y trabaja en una rama específica para tus cambios.
2. **Haz tus cambios y realiza commits descriptivos**.
3. **Envía un pull request (PR)**:
- Explica claramente los cambios realizados.
- Incluye capturas de pantalla o GIFs si es necesario.

---

¡Gracias por colaborar en AgroDirecto y ayudar a construir una mejor plataforma!


## Links


- [AgroDirecto en Producción](https://agrodirecto.serveblog.net/) - Página web principal del proyecto.
- [Repositorio de Código Fuente](https://github.com/EloyAlonso/AgroDirecto) - Código fuente del proyecto en GitHub.
- [Documentación de CakePHP](https://book.cakephp.org/) - Documentación oficial del framework utilizado.
- [Documentación de Leaflet](https://leafletjs.com/reference.html) - Referencia para trabajar con mapas en el proyecto.
- [Documentación de Bootstrap](https://getbootstrap.com/docs/) - Documentación del framework de diseño.