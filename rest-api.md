# Especificación de API REST - Gestión de Tareas

Este documento detalla el contrato técnico para la creación de tareas, generado mediante asistencia de IA para la arquitectura del sistema.

## 1. Crear Nueva Tarea
Permite registrar una tarea pendiente en la base de datos centralizada.

**Endpoint:** `POST /api/v1/tasks`

**Descripción:** Crea una nueva instancia de tarea en el sistema con un estado inicial "pendiente".

### Estructura del Payload (JSON)
El cuerpo de la petición debe seguir el siguiente formato:

```json
{
  "title": "string",
  "description": "string"
}
