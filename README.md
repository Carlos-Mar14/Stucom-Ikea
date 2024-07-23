# Stucom-Ikea
# Tienda Virtual para Artículos del Hogar

Este proyecto es el resultado del curso final en Stucom, Barcelona, y tiene como objetivo desarrollar una tienda virtual básica para artículos del hogar, inspirada en modelos como IKEA. El proyecto utiliza tecnologías como Java EE, MySQL, y sigue el patrón MVC para su estructura.

## Tecnologías Utilizadas

- **Lenguaje de Programación**: Java
- **Framework**: Java EE
- **Base de Datos**: MySQL
- **Control de Versiones**: Git
- **Herramientas de Desarrollo**: Eclipse, IntelliJ IDEA
- **Gestión de Proyectos**: Trello

## Estructura del Proyecto

El proyecto se divide en tres áreas principales:

1. **Front End**: HTML, CSS, JSP para la interfaz de usuario.
2. **Back Office**: Gestión de pedidos y inventario por parte de los administradores.
3. **Back End**: Lógica de negocio, gestión de la base de datos mediante JDBC y JPA.

## Clases Principales

- **Producto**: Representa los artículos disponibles en la tienda.
- **Usuario**: Información básica de los clientes.
- **Pedido**: Gestión de pedidos realizados por los usuarios.
- **Inventario**: Control de stock de productos.
- **UsuarioAdmin**: Funcionalidades extendidas para administradores.
- **DescuentoProducto**: Aplicación de descuentos a productos específicos.
- **Transacción**: Registro de transacciones financieras.

## Configuración del Entorno de Desarrollo

Para configurar el entorno de desarrollo, sigue estos pasos:

1. **Clonar el Repositorio**: `git clone https://github.com/Tu_Usuario/Stucom-Ikea.git`
2. **Configurar la Base de Datos MySQL**: Crear una base de datos llamada `tienda_virtual` y ejecutar el script SQL proporcionado en el repositorio para crear las tablas necesarias.
3. **Importar el Proyecto en Eclipse o IntelliJ**: Abrir el IDE de tu elección e importar el proyecto como un "Proyecto Maven" o "Proyecto Gradle", dependiendo de la herramienta de construcción utilizada.
4. **Configurar Variables de Entorno**: Asegúrate de configurar las variables de entorno necesarias para la conexión con la base de datos y cualquier otra configuración específica del proyecto.

## Contribuir al Proyecto

Si deseas contribuir al proyecto, sigue estos pasos:

1. **Fork** el repositorio.
2. Crea una **nueva rama** para tu característica o corrección.
3. Realiza tus cambios y asegúrate de probarlos localmente.
4. **Push** tus cambios a tu fork.
5. Abre un **Pull Request** describiendo tus cambios y solicitando su revisión.
