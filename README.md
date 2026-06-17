 MobiCaribe

Aplicación móvil multiplataforma para la gestión de transporte terrestre local en Waspam, Río Coco (RACCN, Nicaragua).

![Estado](https://img.shields.io/badge/estado-en%20desarrollo-yellow)
![MVP](https://img.shields.io/badge/fase-MVP-blue)

## 📋 Descripción del proyecto

En el municipio de Waspam, Río Coco (RACCN), la movilidad de la población depende de servicios informales de transporte: taxis, caponeras, vehículos de acarreo, transporte interurbano y delivery. La información sobre horarios, disponibilidad, rutas y contactos de los conductores se encuentra dispersa y se comparte mediante llamadas telefónicas, recomendaciones personales o redes sociales, lo que genera incertidumbre, pérdida de tiempo y dificultades de comunicación entre usuarios y proveedores de transporte.

Existe un antecedente local (la app *Rutas Waspam*, de EMZ LAB) que demostró que la población valora una herramienta digital de este tipo, pero su información se volvió obsoleta porque no permitía que los propios conductores actualizaran sus datos.

**MobiCaribe** propone resolver esto: un prototipo de aplicación móvil que centraliza la información de los servicios de transporte terrestre disponibles en Waspam, permitiendo a los conductores mantener actualizada su disponibilidad, horarios y rutas, y a los usuarios consultar esa información y reservar asientos fácilmente desde una sola plataforma.

## 🎯 Alcance del MVP

Funciones principales (sin las cuales el sistema no podría existir):

1. **Registro y autenticación de usuarios** con dos roles: Conductor y Cliente.
2. **Gestión de disponibilidad y rutas** por parte del conductor: el conductor publica/actualiza horarios, rutas, asientos disponibles y datos de contacto.
3. **Consulta y reserva de viaje** por parte del cliente: el cliente busca rutas/transporte disponible, ve la información del conductor y reserva un asiento.

## 🧩 Módulos del sistema

| Módulo | Descripción |
|---|---|
| **Autenticación** | Registro/inicio de sesión (Supabase Auth) |
| **Conductor (Panel de gestión)** | Alta/edición de rutas, horarios, vehículo y disponibilidad de asientos |
| **Cliente (Búsqueda y Reserva)** | Listado de rutas activas, filtro por destino, reserva de asiento y datos de contacto del conductor |

## 👥 Roles de usuario

| Rol | Permisos |
|---|---|
| **Conductor** | Crea y actualiza información de rutas, horarios, disponibilidad de asientos y datos de contacto |
| **Cliente** | Consulta rutas y disponibilidad, y realiza reservas de asientos |

## 🛠️ Ecosistema tecnológico

- **Diseño de interfaz:** [Figma](https://figma.com) (proyecto compartido entre los 3 integrantes)
- **Base de datos / autenticación:** [Supabase](https://supabase.com) (cuenta grupal)
- **Control de versiones:** GitHub – repositorio público con los 3 integrantes como colaboradores

## 👨‍👩‍👧 Equipo

| Integrante | Rol |
|---|---|
| **Ivan Zavala Blandón** | Líder de equipo / Desarrollador (Backend & conexión a base de datos) |
| **Glen López Jhorquin** | Diseño de Interfaz (UI/UX – Figma) |
| **Ana Jackson** | Documentación y Gestión del Proyecto |

## 🏫 Información académica

- **Universidad:** Bluefields Indian and Caribbean University (BICU)
- **Área:** Área de Conocimiento de Ciencias y Tecnología (ACCT)
- **Escuela:** Informática – Ingeniería de Sistemas de Información
- **Curso:** Proyecto Final de Semestre — Producto Mínimo Viable (MVP)
- **Tutor de referencia (Seminario Monográfico I):** Ing. Glenda Aragón
- **Lugar:** Bilwi, Puerto Cabezas, RACCN, Nicaragua — Junio 2026

## 📁 Estructura del repositorio

```
MobiCaribe-MVP/
├── docs/              # Documentación del proyecto (entregables, actas, etc.)
├── design/            # Enlaces y exportes de Figma
├── src/                # Código fuente de la aplicación
├── database/          # Esquema y scripts de Supabase
└── README.md
```

## 🔗 Enlaces del proyecto

- **Diseño (Figma):** _pendiente de agregar_
- **Base de datos (Supabase):** _pendiente de agregar_

## 📌 Estado actual

- [x] Entregable 1 — Documento inicial (Semana 1)
- [ ] Estructura de pantallas en Figma
- [ ] Esquema de base de datos en Supabase
- [ ] Módulo de autenticación
- [ ] Módulo de Conductor
- [ ] Módulo de Cliente

---
*Proyecto desarrollado como parte del Proyecto Final de Semestre, BICU — Escuela de Informática.*
