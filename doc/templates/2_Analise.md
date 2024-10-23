# Requerimientos del sistema

- [Requerimientos del sistema](#requerimientos-del-sistema)
  - [1- Descripción General](#1--descripción-general)
  - [2- Funcionalidades](#2--funcionalidades)
  - [3- Tipos de usuarios](#3--tipos-de-usuarios)
  - [4- Entorno operacional](#4--entorno-operacional)
  - [5- Normativa](#5--normativa)
  - [6- Mejoras futuras](#6--mejoras-futuras)

## 1- Descripción General

Este proyecto consiste en crear un **marketplace de agricultura** para agricultores en España, permitiendo que vendan sus productos directamente al consumidor final. El objetivo es resolver el problema de los márgenes bajos debido a la intervención de grandes corporaciones. Los agricultores podrán gestionar sus productos, ventas y entregas, mientras que los usuarios finales podrán comprar productos frescos y locales. La plataforma estará optimizada para garantizar facilidad de uso tanto para vendedores como para compradores.

## 2- Funcionalidades

Este apartado debe describir las operaciones clave que se podrán realizar dentro del marketplace. A continuación, te dejo una tabla que define las funcionalidades principales de la plataforma:

| **Acción**                | **Descripción**                                                                                               |
|---------------------------|---------------------------------------------------------------------------------------------------------------|
| Registro de usuarios       | Los usuarios, tanto agricultores como clientes, podrán registrarse para usar la plataforma.                    |
| Alta de productos          | Los agricultores podrán dar de alta sus productos, añadiendo detalles como precio, cantidad y fotos.           |
| Modificación de productos  | Posibilidad de modificar la información de los productos (descripción, precio, cantidad, etc.).                |
| Visualización de productos | Los clientes podrán ver los productos a través de la web, organizados por categorías o filtros de búsqueda.    |
| Compra de productos        | Los clientes podrán añadir productos a un carrito de compra y proceder con el pago de forma segura.            |
| Seguimiento del pedido     | Los clientes podrán visualizar el estado de sus pedidos, ya sea en espera o enviado.                           |
| Historial de pedidos       | Los usuarios podrán ver el historial de productos comprados y el estado de sus pedidos.                        |
| Sistema de reseñas         | Los compradores podrán dejar reseñas sobre los productos y la experiencia con el agricultor.                   |

### Flujo de datos
- **Datos de entrada**: Registro de usuarios, alta de productos, actualización de inventarios, datos de pagos.
- **Datos de salida**: Confirmación de compras, estados de pedido, gestión de ingresos para agricultores, reporte de ventas.

## 3- Tipos de usuarios

Se identificarán varios tipos de usuarios que interactuarán con la plataforma, cada uno con diferentes niveles de acceso y funcionalidades:

1. **Usuario anónimo**: Puede navegar por la plataforma y ver los productos, pero necesita registrarse para comprar.
2. **Cliente registrado**: Puede comprar productos, dejar reseñas y ver su historial de pedidos.
3. **Agricultor**: Puede gestionar su tienda, agregar y modificar productos, gestionar pedidos y pagos, y acceder a estadísticas de ventas.
4. **Administrador**: Tendrá acceso completo para gestionar la plataforma, como la gestión de usuarios, productos y contenido. También verificará los pedidos en caso de algún problema y las políticas de la plataforma.

## 4- Entorno operacional

Para poder operar con la aplicación web, los **usuarios** necesitarán los siguientes recursos:

1. **Navegador web actualizado**: La plataforma será accesible desde cualquier navegador que soporte HTML5, CSS y JavaScript como Google Chrome, Mozilla Firefox, Safari o Microsoft Edge.
2. **Conexión a internet**: Necesaria para poder acceder al sitio y realizar transacciones.
3. **Dispositivos compatibles**:
   - **PC**: Para la gestión completa de los agricultores y administradores.
   - **Smartphones y tablets**: La plataforma será responsiva, por lo que los usuarios podrán comprar desde cualquier dispositivo móvil.

## 5- Normativa

El proyecto debe cumplir con las normativas legales vigentes, sobre todo porque involucra el manejo de datos personales y transacciones comerciales:

1. **Ley Orgánica de Protección de Datos (LOPDPGDD)**: Esta normativa española es crucial para la protección de datos personales. Se debe garantizar que se cumplan todos los requisitos en cuanto al tratamiento de datos personales de los usuarios.
   
2. **General Data Protection Regulation (GDPR)**: Si la plataforma expande su operación a nivel europeo, también deberá cumplir con el GDPR, que regula el tratamiento de datos personales dentro de la UE.

3. **Aviso legal, Política de privacidad y Política de cookies**:
   - **Responsable del tratamiento de datos**: La entidad responsable del tratamiento de los datos personales es la empresa responsable.
   - **Información personal recopilada**: Recopilamos información como nombre y dirección de correo electrónico.
   - **Propósito de la recolección de datos**: Utilizamos los datos personales para gestionar las cuentas de usuario, procesar pedidos, mejorar nuestros servicios, y enviar comunicaciones relacionadas con la plataforma.
   - **Derechos de privacidad**: Los usuarios tienen derecho a la rectificación, desistimiento y anulación de sus datos personales.
   - **Solicitud de derechos**: Los usuarios pueden ejercer sus derechos enviando una solicitud por correo ordinario a la sede de la empresa o completando un formulario disponible en nuestro sitio web.

4. **Comercio electrónico**: Cumplimiento de las leyes relacionadas con las transacciones electrónicas y el comercio a distancia en España, garantizando la transparencia en los términos y condiciones de uso, el derecho de devolución y protección del consumidor.

## 6- Mejoras futuras

El marketplace puede evolucionar y agregar nuevas funcionalidades para mejorar la experiencia tanto de agricultores como de compradores. Algunas mejoras futuras incluyen:

1. **Sistema de chat en tiempo real**: Implementar un chat directo entre **vendedores y clientes** para que puedan resolver dudas sobre los productos o procesos de envío de manera más rápida y directa.
   
2. **Subscripción Premium para agricultores**: Ofrecer opciones de **membresías premium** que brinden beneficios como mejores posiciones en los resultados de búsqueda, promociones o herramientas avanzadas de gestión.

3. **Sistema de recomendación de productos**: Implementar un sistema de inteligencia artificial que sugiera productos a los compradores basándose en sus preferencias y comportamiento de compra.

4. **Integración con aplicaciones móviles**: Desarrollar una aplicación móvil nativa para Android e iOS que ofrezca una experiencia más optimizada, permitiendo notificaciones push y una mejor navegación.

5. **Ampliación de métodos de pago**: Incluir más opciones de pago como criptomonedas o sistemas como PayPal.
