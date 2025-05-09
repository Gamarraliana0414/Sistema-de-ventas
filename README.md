
LimaBeauty es un sistema de ventas desarrollado en Python, diseñado para gestionar de forma eficiente los procesos básicos de una tienda de productos de belleza. La aplicación permite registrar y administrar clientes, productos y ventas de manera sencilla. Toda la información se guarda localmente utilizando una base de datos SQLite. Además, el proyecto sigue el patrón de diseño MVC (Modelo-Vista-Controlador), lo que facilita la organización del código y mejora su mantenimiento y escalabilidad.

Características Principales:

Panel principal con gráfico de rendimiento de ventas.

Registro y gestión de clientes, productos y ventas.

Visualización de métricas (cantidad total de clientes, productos y ventas).

Navegación lateral clara con botones accesibles para cada módulo.

Interfaz visual limpia y amigable usando CustomTkinter.

Base de datos local SQLite administrada mediante el ORM Peewee.

Arquitectura estructurada bajo el patrón MVC (Modelo-Vista-Controlador).

Pantalla Principal:

En la pantalla principal se visualiza:

Tres contadores que resumen:

Total de clientes registrados.

Total de productos disponibles.

Total de ventas realizadas.

Un gráfico de línea que muestra el rendimiento de ventas en diferentes períodos (ej. días o semanas).


Menú lateral para acceder rápidamente a cada módulo del sistema:


Inicio

Registrar Cliente

Registrar Producto

Registrar Venta

Ver Ventas

Tecnologías Usadas
Python 3.6+

CustomTkinter – Interfaz gráfica moderna.

Matplotlib – Gráfica de rendimiento de ventas.

Peewee – ORM para manejo de base de datos SQLite.

MVC – Organización del código por capas.

Funcionalidades:

 Registro de clientes.

 Registro y control de productos en inventario.

 Registro de ventas con cálculo automático del total.

 Visualización del historial de ventas.

 Panel principal con indicadores de actividad y gráfico de ventas.


 
