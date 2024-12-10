# FASE DE IMPLANTACIÓN

- [FASE DE IMPLANTACIÓN](#fase-de-implantación)
  - [1- Manual técnico](#1--manual-técnico)
    - [1.1- Instalación](#11--instalación)
    - [1.2- Administración del sistema](#12--administración-del-sistema)
  - [2- Manual de usuario](#2--manual-de-usuario)
  - [3- Mejoras futuras](#3--mejoras-futuras)

## 1- Manual técnico

### 1.1- Instalación

> *EXPLICACIÓN:* En este apartado se describirán todos los pasos necesarios para que cualquier persona pueda descargar el código del proyecto y continuar su desarrollo.
>
> Como:
> 
> - Requisitos de hardware, servidores en la nube, etc.
> - Software necesario: servidores (Ejemplo servidor Web), software externo con el que interactúa nuestra aplicación, contenedores, etc.
> - Carga inicial de datos en la base de datos. Migración de datos ya existentes en otros formatos.
> - Usuarios de la aplicación.
> - Diagrama final de despliegue (si hay variaciones con respecto a lo realizado en la fase anterior).

Para el despliegue de la web se puede optar por 2 diferentes formas: Desde Windows o desde Linux (o WSL).

Yo personalmente despliego el proyecto desde WSL (Windows Subsystem for Linux) donde meto el repositorio de la web en mi distro ya configurada con Docker ya instalado internamente.
Recomiendo ver este vídeo si quieres instalar Docker dentro de WSL en vez de usar Docker Desktop ya que ralentizará mucho la página:
[Instalar Docker en WSL](https://www.youtube.com/watch?v=cv7Iyohhmo4)

En el caso de que quieras tener el repositorio en el sistema operativo Windows simplemente tienes que descargar Docker Desktop, pero la carga de la página será mucho más lenta.

Para el despliegue hay 2 scripts dependiendo del sistema operativo desde el que se quiera lanzar: build.sh (para Linux y WSL) y windows.ps1

Tan solo hay que ejecutarlos y en unos minutos estará desplegada la web con su base de datos importada y funcionando.

Tener en cuenta que a lo mejor build.sh no tiene permisos para ser ejecutable así que en caso de que no se pueda ejecutar hay que darle permisos de ejecución "chmod +x ./build.sh"

Y en cuanto al script de Windows puede suceder que PowerShell no tenga habilitada la ejecución de scripts así que recomiendo usar este comando: 
```powershell
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
```


### 1.2- Administración del sistema

> *EXPLICACIÓN:* En este apartado se indicará información relativa a la administración del sistema, es decir, tareas que se deberán realizar una vez que el sistema esté funcionando.
>
> Como:
> 
> - Copias de seguridad del sistema.
> - Copias de seguridad de la base de datos.
> - Gestión de usuarios.
> - Gestión de seguridad.
> - Gestión de incidencias, que pueden ser de dos tipos: de sistema (accesos no autorizados a la BD, etc.) o de fallos en el software.
>
> En caso de que sean necesarias.

El script hace ya todo. No hace falta implementar nada, pero en caso de algún posible fallo revisar la importación de la base de datos:

Revisar que en app/config/.env los datos de DATABASE_URL sean las credenciales correctas, se puede corroborar con app/config/env.example y compose.yml donde está usuario, contraseña contenedor de BD, etc.

Una vez asegurado que va acudiremos al adminer con el puerto 8080, donde podemos iniciar sesion con estas credenciales y acceder a la base de datos para importar el archivo sql de la base de datos (agrodirecto.sql).

## 2- Manual de usuario

> *EXPLICACIÓN:* En este apartado se indicará si será necesario formar a los usuarios. En caso afirmativo, planificar.
>
> - Manual de usuario, FAQ u otro método que sea el más adecuado para que los usuarios sepan usar nuestra aplicación informática.
>
> Todo esto si la aplicación requiere de manual de usuario.

A continuación, se describen las principales funcionalidades para un usuario:

- **Mercado**: En este apartado, puedes utilizar los filtros disponibles para buscar productos. Debajo del mapa de los vendedores, puedes seleccionar los productos y acceder a sus detalles.
- **Mercado de vendedor**: En este apartado, los usuarios pueden filtrar los productos que han puesto a la venta un vendedor especifico. Esto les permite visualizar únicamente los productos de ese vendedor de manera eficiente.
- **Compra de productos**: Puedes elegir la cantidad de productos y optar por comprarlos directamente o añadirlos al carrito.
- **Carrito de compras**: Esta opción solo está disponible si te registras como usuario. Una vez registrado, puedes modificar la cantidad de productos en el carrito y realizar la compra.
- **Perfil de usuario**: En tu perfil, puedes ver tus pedidos, su estado, cancelarlos, marcarlos como recibidos y valorar los productos que ya llegaron.

Estas funcionalidades aseguran una experiencia de usuario intuitiva y eficiente.

Para un vendedor, las funcionalidades son las siguientes:

- **Mercado**: El vendedor puede ver los productos disponibles en el mercado, pero no tiene acceso al carrito de compras.
- **Gestión de productos y pedidos**: En su perfil, el vendedor puede gestionar sus productos, añadiendo nuevos productos o actualizando los existentes. Además, puede ver los pedidos que debe enviar, gestionando el estado de cada pedido y asegurándose de que los productos lleguen a los compradores.

Estas funcionalidades permiten a los vendedores administrar eficientemente sus productos y pedidos.


## 3- Mejoras futuras

> *EXPLICACIÓN:* En este apartado se incluirán las posibilidades de mejora de la aplicación en el futuro.

- **Chat entre usuarios y vendedores**: Implementar un sistema de mensajería en tiempo real para que los usuarios puedan comunicarse directamente con los vendedores para gestionar pedidos, resolver dudas y negociar precios.
- **Mejoras estéticas**: Rediseñar la interfaz de usuario para hacerla más atractiva y moderna, mejorando la experiencia visual y la usabilidad.
- **Funcionalidades avanzadas de búsqueda**: Añadir filtros de búsqueda más detallados.
- **Sistema de notificaciones**: Implementar notificaciones en tiempo real para informar a los usuarios sobre el estado de sus pedidos, nuevos productos disponibles, y ofertas especiales.
- **Integración con redes sociales**: Facilitar el registro y acceso a la plataforma mediante cuentas de redes sociales, y permitir compartir productos y ofertas en dichas redes.
- **Programa de fidelización**: Crear un sistema de puntos o recompensas para incentivar la compra recurrente y la lealtad de los usuarios.
- **Soporte multilingüe**: Añadir soporte para múltiples idiomas, permitiendo a usuarios de diferentes regiones utilizar la plataforma en su idioma nativo.
- **Análisis de datos y reportes**: Proveer a los vendedores con herramientas de análisis de datos y reportes sobre sus ventas, productos más populares, y comportamiento de los clientes.
