// GreenMove: Movilidad Sustentable Universitaria

GreenMove es una aplicación web diseñada para fomentar el uso de *Carpooling* (transporte compartido) dentro de comunidades universitarias. El objetivo principal es reducir la huella de carbono (<span class="math">CO<sub>2</sub></span>) y optimizar los traslados diarios de los estudiantes, otorgando incentivos mediante un sistema de puntos.

// Características Principales
--Gestión de Usuarios:** Registro y autenticación segura de cuentas.
* *Carpooling Inteligente:* Publicación y reserva de asientos para viajes compartidos.
* *Cálculo de Impacto Ecológico:* Algoritmo integrado que calcula la mitigación de <span class="math">CO<sub>2</sub></span> según la distancia del trayecto.
* *Sistema de Recompensas:* Acumulación de "Puntos Verdes" por cada viaje realizado.
* *Dashboard Estadístico:* Visualización en tiempo real del impacto personal acumulado.

## Tecnologías Utilizadas
* *Backend:* Python con Flask.
* *Base de Datos:* SQLite (ligera y embebida).
* *Frontend:* HTML5, CSS3 (Diseño responsivo).
* *Seguridad:* Werkzeug (Hashing de contraseñas).

## Estructura del Proyecto
```text
greenmove_project/
├── app.py                  # Lógica del servidor y rutas
├── greenmove.db            # Base de datos local
└── templates/              # Interfaz de usuario (HTML)
    ├── login.html
    └── dashboard.html
