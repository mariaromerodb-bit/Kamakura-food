# 🍣 Kamakura Food 🍱
Una aplicacion web interactiva de pedidos de comida japonesa


## 🚀 Requisitos Funcionales
- La página DEBE imprimir en pantalla los platos del menú con la información proporcionada en el archivo de data.js
- DEBE imprimir en pantalla los filtros de las categorías del menú con la información proporcionada en el archivo de data.js
- DEBE poder filtrar los platos por categoría.
- DEBE permitir abrir y cerrar un menú lateral que contiene el carrito de compras.
- DEBE añadir el plato seleccionado al carrito de compras.
- no DEBE añadir dos veces el mismo plato al carrito de compras.
- DEBE poder eliminar el plato que se encuentra en el carrito de compras.
- DEBE poder aumentar la cantidad del mismo plato en el carrito de compras.
- no DEBE poder disminuir la cantidad en valores negativos.
- DEBE eliminarse el plato del carrito de compras cuando llegue a la cantidad 0.
- DEBE sumar el subtotal mientras se cambie la cantidad de cada plato.
- DEBE mostrar el total de todos los subtotales.
- DEBE mostrar el recibo al proceder con el pago, que contendrá todos los platos escogidos con sus cantidades, subtotal y total.


## 🛠️ Arquitectura y Estructura del Proyecto
```text
kamakura-food/
├── index.html                  # Estructura base de la aplicación SPA
├── assets/
│   ├── data/
│   │   └── data.js             # Base de datos local (Filtros y objetos de Productos)
│   └── img/
│       └── close.svg           # Recursos visuales e íconos de la interfaz
├── styles/
│   └── main.css                # Estilos responsive del menú, carrito y recibo
└── src/
    ├── cart.js                 # Lógica de estados del carrito (cantidades, totales y borrado)
    ├── menu.js                 # Renderizado dinámico de tarjetas de platos y botones de filtro
    ├── receipt.js              # Procesamiento de datos y conmutación visual de la factura de pago
    ├── searcher.js             # Motor de filtrado puro por categorías
    └── events.js               # Orquestador central y escuchador de eventos globales (Punto de entrada)


## 🛠️ Tecnologías Utilizadas
HTML5
CSS3
JavaScript


## 🔗 Enlaces del Proyecto
notion: https://www.notion.so/mariaromerodb/Kamakura-Food-366c6a61737b80b18f75f8bdfbfae0e4


## ✍️ Autora
María de Benito
