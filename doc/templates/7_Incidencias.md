# INCIDENCIAS Y TAREAS
- [INCIDENCIAS Y TAREAS](#incidencias-y-tareas)
  - [1- Incidencias](#1--incidencias)
  - [2- Tareas](#2--tareas)

## 1- Incidencias

La configuración inicial encontró problemas con las dependencias de CakePHP y las incompatibilidades de versiones.
Estos problemas se resolvieron identificando y utilizando versiones compatibles que no causaban problemas al lanzar la aplicación.

Además, hubo problemas con la carga de solicitudes AJAX que no daban resultados.
Estos problemas se resolvieron corrigiendo errores en el código ("despistes") que ocurrieron durante el proceso de carga de datos, lo que impedía la carga final.
En algunos casos, los valores nulos de ciertas variables corrompían la solicitud.
Estos problemas se resolvieron manejando los errores de estas variables.

## 2- Tareas

1. **Desplegar web de CakePHP con Docker**: Configurar y desplegar la aplicación web utilizando Docker para asegurar un entorno de desarrollo consistente y replicable.

2. **Implementar header y footer**: Crear y diseñar el encabezado y pie de página que serán comunes en todas las páginas de la aplicación.

3. **Creación de la página principal**: Desarrollar la página de inicio que será la primera vista de los usuarios al acceder a la aplicación.

4. **Crear registro e iniciar sesión**: Implementar las funcionalidades de registro de nuevos usuarios y el inicio de sesión para usuarios existentes.

5. **Crear página del mercado con filtros y mapa de Leaflet**: Desarrollar una página de mercado que permita a los usuarios buscar productos utilizando filtros y visualizar ubicaciones en un mapa interactivo con Leaflet.

6. **Crear la vista del producto a comprar**: Desarrollar una página detallada del producto que los usuarios desean comprar, mostrando toda la información relevante del producto.

7. **Crear página de los productos del vendedor**: Crear una página dedicada a mostrar los productos que ofrece cada vendedor.

8. **Crear carrito y pagos**: Implementar la funcionalidad de carrito de compras y el proceso de pago para los usuarios.

9. **Implementar 2 tipos de perfiles (usuario y vendedor)**: Crear y gestionar dos tipos de perfiles diferentes, uno para usuarios y otro para vendedores, con funcionalidades específicas para cada uno.

10. **Crear gestión de pedidos para usuarios y vendedores**: Desarrollar un sistema que permita a los usuarios y vendedores gestionar sus pedidos, incluyendo el seguimiento y actualización del estado de los mismos.

11. **Crear gestión de productos para vendedores**: Permitir a los vendedores crear, editar y gestionar sus productos dentro de la plataforma.

12. **Crear gestión de reseñas para usuarios**: Implementar un sistema de reseñas que permita a los usuarios dejar comentarios y valoraciones sobre los productos y vendedores.

13. **Implementar las vistas de "Nosotros", "Unirse" y "Privacidad"**: Desarrollar las páginas informativas sobre la empresa, cómo unirse a la plataforma y la política de privacidad.