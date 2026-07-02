# Sistema de Gestión de Estudiantes (CRUD) — ITB

Este es un sistema de escritorio simple para la gestión y control de estudiantes, desarrollado en **Python** utilizando **Tkinter** para la interfaz gráfica de usuario (GUI) y **SQLite3** como motor de base de datos local. El sistema permite realizar de forma visual las operaciones básicas de un CRUD: Crear, Leer, Actualizar y Borrar registros.

## 🚀 Características

- **Base de datos local:** Almacenamiento automático y persistente mediante un archivo SQLite (`estudiantes.db`).
- **Interfaz intuitiva:** Visualización de los datos en tiempo real mediante un componente de tabla dinámica (`Treeview`).
- **Validación de campos:** El sistema valida que los campos no estén vacíos y asegura que las calificaciones ingresadas sean exclusivamente numéricas.
- **Interacción fluida:** Al seleccionar cualquier fila de la tabla, los datos se cargan automáticamente en los campos superiores para facilitar su edición o eliminación.

---

## 🛠️ Requisitos del Sistema

Para ejecutar esta aplicación, solo necesitas tener instalado Python en tu computadora, ya que todas las librerías utilizadas forman parte de la biblioteca estándar de Python:

- Python 3.x
- Tkinter (suele venir preinstalado con Python)
- SQLite3 (integrado de forma nativa en Python)

---

## 💻 Instalación y Uso

Sigue estos sencillos pasos para clonar y ejecutar el proyecto localmente:

1. **Clonar el repositorio:**
   ```bash
  