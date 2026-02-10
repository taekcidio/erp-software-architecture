# 1. Introducción y objetivos

## 1.1 Propósito del sistema
El Sistema ERP tiene como objetivo soportar procesos principales de una empresa (compras, inventario, facturación, etc.). En este taller se documenta el alcance inicial del **Módulo de Compras**, incluyendo backlog, arquitectura de alto nivel con C4 y diseño detallado con UML, consolidado en arc42.

## 1.2 Objetivos (drivers)
- Mantener un catálogo de productos actualizado para el proceso de compras.
- Gestionar proveedores y sus precios por producto.
- Crear órdenes de compra con trazabilidad y estados.
- Registrar recepciones de productos contra órdenes de compra.

## 1.3 Requisitos de negocio más importantes (Módulo de Compras)
- Registrar productos con validaciones (campos obligatorios y unicidad).
- Registrar proveedores con datos de contacto.
- Asociar productos a proveedores con precio unitario.
- Crear órdenes de compra con proveedor y detalle de productos.
- Registrar recepciones parciales o completas.

Fuente: elaboración propia
