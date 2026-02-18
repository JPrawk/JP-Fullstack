# Definición de Esquema GraphQL - Núcleo del Sistema

Este documento describe el esquema de datos para la consulta y manipulación de tareas, asegurando un contrato de datos tipado y eficiente.

## 1. Tipos de Datos (Types)

El objeto principal del sistema es la `Task`, que representa una unidad de trabajo.

```graphql
type Task {
  id: ID!          # Identificador único (No nulo)
  title: String!   # Título descriptivo de la tarea
  completed: Boolean! # Estado de finalización
}
