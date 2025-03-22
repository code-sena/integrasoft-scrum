# Requerimientos Funcionales del Proyecto de Carrito de Compras

Este documento describe los requerimientos funcionales del proyecto de carrito de compras, que se dividirán en varios módulos para facilitar su comprensión y ejecución.

## 1. **Módulo de Inventario**

### Servicios:
1. **Gestión de productos**: El sistema debe permitir añadir, editar y eliminar productos del inventario de manera sencilla y rápida.
2. **Control de stock**: El sistema debe verificar la disponibilidad de productos en tiempo real y mostrar la cantidad disponible en la tienda.
3. **Notificación de agotados**: Cuando un producto esté agotado, se enviará una notificación al administrador para que lo reponga.
4. **Visualización de productos**: Los usuarios deben poder ver todos los productos disponibles en categorías claras y accesibles.
5. **Filtrado de productos**: Los usuarios podrán filtrar los productos por categorías, precios, marcas y características.

## 2. **Módulo de Registro de Clientes**

### Servicios:
6. **Creación de cuenta**: Los usuarios podrán registrarse en el sistema proporcionando su nombre, dirección de correo electrónico y una contraseña.
7. **Autenticación de usuarios**: Los usuarios deben poder iniciar sesión con su correo electrónico y contraseña para acceder a su cuenta.
8. **Recuperación de contraseña**: El sistema debe permitir a los usuarios recuperar su contraseña a través de un enlace enviado a su correo electrónico.
9. **Gestión de datos de usuario**: Los usuarios podrán editar sus datos personales, como dirección de envío y preferencias de pago.
10. **Visualización de historial de compras**: Los usuarios deben poder consultar el historial completo de sus compras anteriores, con detalles de productos, fechas y precios.

## 3. **Módulo de Carrito de Compras**

### Servicios:
11. **Añadir productos al carrito**: Los usuarios podrán añadir productos al carrito con un solo clic.
12. **Modificar carrito**: Los usuarios podrán aumentar o disminuir la cantidad de productos en su carrito, o eliminarlos.
13. **Verificación de stock**: Antes de finalizar la compra, el sistema verificará que los productos en el carrito estén disponibles en el inventario.
14. **Resumen del carrito**: El sistema mostrará un resumen detallado del carrito, incluyendo los productos, el precio total y los gastos de envío antes de realizar el pago.

## 4. **Módulo de Notificaciones**

### Servicios:
15. **Notificación de estado del pedido**: El sistema enviará notificaciones por correo electrónico o mensaje dentro de la página cuando el estado del pedido cambie (ej. "En proceso", "En tránsito", "Entregado").
16. **Notificación de disponibilidad de productos**: Los usuarios recibirán notificaciones cuando un producto previamente agotado vuelva a estar disponible.
17. **Notificación de promociones**: Los usuarios podrán recibir notificaciones de ofertas, descuentos y promociones especiales disponibles en la tienda.

## 5. **Módulo de Pasarela de Pago**

### Servicios:
18. **Opciones de pago**: El sistema debe permitir a los usuarios elegir entre varias opciones de pago, como tarjeta de crédito/débito, PayPal, y pago contra entrega.
19. **Confirmación de pago**: Después de realizar el pago, el sistema debe enviar una confirmación de pago a los usuarios y procesar la transacción de manera segura.
20. **Seguridad de pagos**: El sistema debe contar con un protocolo de seguridad de pagos, como cifrado SSL, para proteger la información financiera de los usuarios.

---

Estos son los requerimientos funcionales clave de nuestro sistema de carrito de compras. Cada módulo está diseñado para mejorar la experiencia del usuario y optimizar las operaciones de la tienda en línea, asegurando una gestión eficaz y segura tanto para los clientes como para los administradores del sistema.
