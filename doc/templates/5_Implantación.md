# FASE DE IMPLANTACIÓN

- [FASE DE IMPLANTACIÓN](#fase-de-implantación)
  - [1- Manual técnico](#1--manual-técnico)
    - [1.1- Instalación](#11--instalación)
    - [1.2- Administración del sistema](#12--administración-del-sistema)
  - [2- Manual de usuario](#2--manual-de-usuario)
  - [3- Mejoras futuras](#3--mejoras-futuras)

## 1- Manual técnico

### 1.1- Instalación

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


### 1.2- Administración del sistema

El script hace ya todo. No hace falta implementar nada, pero en caso de algún posible fallo revisar la importación de la base de datos:

Revisar que en app/config/.env los datos de DATABASE_URL sean las credenciales correctas, se puede corroborar con app/config/env.example y compose.yml donde está usuario, contraseña contenedor de BD, etc.

Una vez asegurado que va acudiremos al adminer con el puerto 8080, donde podemos iniciar sesion con estas credenciales y acceder a la base de datos para importar el archivo sql de la base de datos (agrodirecto.sql).

## 2- Manual de usuario

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

- **Chat entre usuarios y vendedores**: Implementar un sistema de mensajería en tiempo real para que los usuarios puedan comunicarse directamente con los vendedores para gestionar pedidos, resolver dudas y negociar precios.
- **Mejoras estéticas**: Rediseñar la interfaz de usuario para hacerla más atractiva y moderna, mejorando la experiencia visual y la usabilidad.
- **Funcionalidades avanzadas de búsqueda**: Añadir filtros de búsqueda más detallados.
- **Sistema de notificaciones**: Implementar notificaciones en tiempo real para informar a los usuarios sobre el estado de sus pedidos, nuevos productos disponibles, y ofertas especiales.
- **Integración con redes sociales**: Facilitar el registro y acceso a la plataforma mediante cuentas de redes sociales, y permitir compartir productos y ofertas en dichas redes.
- **Programa de fidelización**: Crear un sistema de puntos o recompensas para incentivar la compra recurrente y la lealtad de los usuarios.
- **Soporte multilingüe**: Añadir soporte para múltiples idiomas, permitiendo a usuarios de diferentes regiones utilizar la plataforma en su idioma nativo.
- **Análisis de datos y reportes**: Proveer a los vendedores con herramientas de análisis de datos y reportes sobre sus ventas, productos más populares, y comportamiento de los clientes.
