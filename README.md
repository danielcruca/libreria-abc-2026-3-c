# Sistema online para Libreia ABC

Este proyecto consiste en la creación de una **API con MongoDB** para una **librería**, junto con un **frontend** que permite la gestión de usuarios, libros y ventas. El sistema completo ofrece operaciones básicas como inserción, actualización, eliminación y consultas avanzadas a través de una interfaz web.

## 📚 Colecciones y Ejemplos

### 👤 Usuarios
```json
{
  "username": "juanperez",
  "email": "juan@example.com",
  "password": "supersegura123",
  "rol": "cliente",
  "fecha_creacion": "2025-05-14T00:13:32.275Z"
}
```

### 📘 Libros
```json
{
  "titulo": "Rayuela",
  "autor": {
    "nombre": "Julio",
    "apellido": "Cortázar",
    "nacionalidad": "Argentina"
  },
  "precio": 18,
  "cantidad_stock": 12
}
```

### 🧾 Ventas
```json
{
  "libro": {
    "titulo": "El Aleph"
  },
  "fecha_venta": "2025-05-11T00:00:00.000Z",
  "cantidad": 3,
  "total": 37.5,
  "usuario": {
    "username": "librera99"
  }
}
```

---


## 👥 Integrantes del Proyecto

- Juan Rafael Mora Porras
- Pancha Carrasco