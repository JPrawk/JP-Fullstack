# Documentación de Endpoints REST

## 1. Introducción
Este documento describe los endpoints REST del sistema, siguiendo las convenciones RESTful y buenas prácticas de arquitectura.

## 2. Recursos Principales
- Usuarios
- Productos
- Órdenes

---

## 3. Endpoints

### 3.1. Obtener lista de usuarios
**Método:** GET  
**URL:** `/api/users`  
**Descripción:** Retorna la lista completa de usuarios registrados.

**Ejemplo de respuesta:**
```json
{
  "id": 1,
  "name": "Juan Pérez",
  "email": "juan@example.com"
}
