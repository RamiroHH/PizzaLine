🍕 PizzaLine – Sistema Web de Gestión para Pizzerías

PizzaLine es una aplicación web desarrollada como proyecto integral de front-end, enfocada en simular el funcionamiento real de una pizzería moderna: visualización de menú, gestión de pedidos, autenticación básica de usuarios y panel administrativo.

Este proyecto utiliza HTML, CSS y JavaScript, realizando comunicación con MockAPI para almacenar y obtener datos como productos, usuarios y pedidos.

🚀 Características principales

🛒 Catálogo de Pizzas y Bebidas

Consumo de menú desde MockAPI.
Buscador en tiempo real.
Filtrado por categorías (pizzas / bebidas).
Render dinámico del menú.

🧾 Carrito de Compras

Agregar o quitar productos.
Cálculo automático del total.
Persistencia temporal con localStorage.

📦 Gestión de Pedidos

Envío de pedidos a MockAPI (POST).
Seguimiento del estado del pedido.
Actualización de estado (pendiente, en preparación, entregado).

🔐 Registro e Inicio de Sesión

Formulario de registro conectado a MockAPI.
Inicio de sesión básico mediante comparación de datos.
Guardado del usuario activo en localStorage.

🛠️ Panel Administrativo (Admin)

Visualización de todos los pedidos.
Actualización del estado de cada pedido.
Listado general de usuarios (opcional según implementación).

🧩 Tecnologías utilizadas

HTML5
CSS3
JavaScript Vanilla (ES6+)
MockAPI.io como backend simulado
LocalStorage para persistencia temporal

🧪 Endpoints utilizados
🥗 Productos
GET /productos

👤 Usuarios
POST /users
GET /users

🧾 Pedidos
POST /orders
GET /orders
PUT /orders/:id

🎯 Objetivo del proyecto

Este proyecto fue creado para practicar lógica de programación, consumo de APIs, manejo de estados, modularización en JS, DOM dinámico y diseño web responsivo.

Además forma parte del portfolio del desarrollador para proyectos reales orientados a sistemas de ventas, delivery y gestión comercial.


Ramiro Hernandez
Estudiante de Programación (UTN)
GitHub: [github.com/RamiroHH](https://github.com/RamiroHH)
LinkedIn: https://www.linkedin.com/in/ramiro-miguel-hernandez-945546222/
