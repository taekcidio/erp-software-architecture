# 5. Vista de bloques de construcción

## 5.1 Contenedores (C2)
La solución propuesta se basa en una arquitectura simple:
- **SPA Web (React)** para la interfaz de usuario.
- **API Monolítica (Spring Boot)** para la lógica de negocio y servicios.
- **Base de datos (PostgreSQL)** para persistencia.

![Diagrama de Contenedores](./images/c2_containers.png)

## 5.2 Responsabilidades
- **SPA Web:** formularios, validaciones básicas en cliente, consumo de endpoints.
- **API Monolítica:** reglas de negocio, validaciones, operaciones CRUD y orquestación.
- **Base de datos:** almacenamiento de entidades del ERP (compras e inventario).

## 5.3 Modelo de datos (Compras)
El modelo de datos simplificado representa las entidades principales para compras: Producto, Proveedor, su relación con precio, y la Orden de Compra con detalle.

![MER Compras](./images/er_compras.png)

Fuente: elaboración propia
