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

## Recomendaciones basadas en **Design Thinking** para abordar el Proyecto de Carrito de Compras

Aplicando el enfoque de **Design Thinking**, podemos estructurar las fases del proyecto para obtener un producto final que responda mejor a las necesidades del usuario, dentro de las restricciones de **tiempo**, **alcance** y **costo**.

### 1. **Empatizar** (Entender al Usuario)
Antes de comenzar con el diseño y la implementación, es fundamental **comprender las necesidades y frustraciones** de los usuarios finales. Se recomienda llevar a cabo entrevistas o encuestas con una muestra representativa de clientes para identificar:
- Qué funcionalidades son más valoradas en un carrito de compras (como opciones de pago, facilidad para encontrar productos, etc.).
- Qué problemas enfrentan los usuarios al realizar compras en línea (problemas con el proceso de pago, dificultades para navegar por el sitio, etc.).
  
**Recomendación**: Utilizar las encuestas que ya se generaron como base para obtener datos de los usuarios.

**Tiempo estimado**: 2 semanas (1 semana para recolectar datos, 1 semana para análisis).

### 2. **Definir** (Sintetizar la Información)
Una vez recolectada la información de los usuarios, el siguiente paso es **definir los problemas clave** que deben ser resueltos. Esto implica identificar las necesidades críticas y las prioridades de los usuarios, y cómo estas pueden abordarse con los recursos disponibles.

**Recomendación**: Establecer un conjunto de **funcionalidades mínimas viables (MVP)** que se alineen con los objetivos del negocio, asegurando que se entreguen las características más valiosas primero.

**Tiempo estimado**: 1 semana.

### 3. **Idear** (Generar Soluciones)
En esta fase, es importante generar múltiples **soluciones creativas** para abordar los problemas definidos. Las sesiones de brainstorming pueden ser útiles para explorar diferentes enfoques para:
- Mejorar la navegación del sitio.
- Simplificar el proceso de pago.
- Optimizar la visualización del carrito y los productos.

**Recomendación**: Priorizar las soluciones que sean **fáciles de implementar** en el tiempo disponible, y que generen un alto impacto en la experiencia del usuario.

**Tiempo estimado**: 1 semana.

### 4. **Prototipar** (Crear Modelos de Solución)
El prototipo es una representación visual de las ideas seleccionadas en la fase anterior. Estos pueden ser **básicos**, pero deben reflejar cómo las soluciones propuestas podrían funcionar en el producto final. Se pueden crear prototipos en papel o herramientas digitales como Figma o Sketch para simular la experiencia del usuario.

**Recomendación**: Crear prototipos de alta fidelidad para las funciones críticas, como el proceso de pago y la visualización del carrito de compras.

**Tiempo estimado**: 2 semanas.

### 5. **Testear** (Evaluar las Soluciones)
El siguiente paso es **probar** los prototipos con usuarios reales para recoger **retroalimentación**. En esta fase, es posible identificar posibles fallos o áreas de mejora antes de desarrollar el sistema completo.

**Recomendación**: Realizar pruebas con al menos 5 usuarios representativos para obtener retroalimentación significativa.

**Tiempo estimado**: 1 semana.

---

## Consideraciones de la Triple Restricción (Tiempo, Alcance y Costo)

### **Tiempo (3 meses)**
Con un plazo de 3 meses, el proyecto debe seguir un enfoque ágil. Las tareas clave deben dividirse en sprints semanales, priorizando las funcionalidades más importantes. Es esencial evitar desviarse del enfoque inicial y respetar los plazos establecidos para cada fase del proyecto.

**Recomendación**: Utilizar metodologías ágiles para gestionar el tiempo y asegurarse de que el desarrollo se mantenga enfocado en las funcionalidades mínimas viables (MVP).

### **Alcance (8.000.000 de presupuesto)**
Con un presupuesto de 8.000.000, se deben priorizar las funcionalidades que realmente resuelvan las necesidades de los usuarios, y evitar sobrecargar el proyecto con características secundarias que no contribuyan directamente al valor final.

**Recomendación**: Utilizar el presupuesto para implementar las funciones más esenciales y asegurar que el desarrollo sea eficiente, evitando costos innecesarios en tareas que no sean prioritarias.

### **Costo**
Mantener el presupuesto dentro de los límites establecidos es esencial para la viabilidad del proyecto. Las soluciones deben ser costeables, y el equipo debe trabajar de manera eficiente para evitar gastos adicionales.

**Recomendación**: Contratar un equipo de desarrollo pequeño pero especializado, y utilizar herramientas de desarrollo que sean eficientes en términos de costo, como plataformas de código abierto.

---

Estas recomendaciones basadas en **Design Thinking** y la **triple restricción** (tiempo, alcance y costo) permitirán llevar a cabo un proyecto exitoso, garantizando una experiencia de usuario óptima dentro de los plazos y el presupuesto establecidos.
