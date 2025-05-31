# Sistema de Gestión de Aparcamiento - Proyecto Web

## Descripción General

Este proyecto consiste en una **aplicación web** para la gestión de aparcamientos en una universidad o institución. La plataforma permite visualizar los estacionamientos disponibles, realizar reservas, eliminarlas y gestionar el sistema mediante un panel intuitivo.

## Objetivo

Crear un sistema funcional y adaptable que permita a los usuarios:
- Reservar espacios de aparcamiento.
- Visualizar espacios disponibles.
- Eliminar reservas.
- Gestionar el sistema desde una interfaz moderna y accesible.

## Tecnologías Utilizadas

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js con Express
- **Base de Datos:** MongoDB (NoSQL)
- **Metodología:** Ágil (Scrum)

---

## Estructura del Sistema

### Módulos principales

1. **Inicio de Sesión**
   - Validación de usuario
   - Redirección al panel principal

2. **Pantalla de Inicio**
   - Muestra opciones principales (como en la plataforma EMMA)
   - Acceso a módulos como prácticas, becas, procesos, consultas, etc.

3. **Módulo de Estacionamiento**
   - Visualización general de todos los espacios
   - Opciones disponibles:
     - Agregar nuevo estacionamiento
     - Reservar espacio
     - Eliminar espacio o reserva

---

## Modelo de Navegación

```plaintext
[Login]
   |
   v
[Pantalla de Inicio]
   |
   ├── Prácticas
   ├── Becas
   ├── Procesos Académicos
   ├── ...
   └── Estacionamientos
              |
              ├── Agregar Estacionamiento
              ├── Ver todos los espacios
              ├── Reservar espacio
              └── Eliminar reserva
