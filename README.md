# 📅 Sistema de Gestión y Generación de Horarios Semanales

Aplicación web interactiva para la planificación, asignación y resolución de conflictos en la elaboración de **horarios institucionales y académicos por semana**, equipada con un motor algorítmico de generación de horarios, control de disponibilidad de docentes, capacidad de aulas y grupos de estudiantes.

---

## ✨ Características Principales

- 🗓️ **Generador de Horarios Inteligente (`scheduler.js`):** Algoritmo heurístico para distribución de asignaturas evitando solapamientos de profesores, choques de grupos y saturación de aulas.
- 👨‍🏫 **Gestión de Profesores y Disponibilidad:** Configuración de horas lectivas semanales y restricciones de franja horaria.
- 🏫 **Control de Aulas e Infraestructura:** Asignación de salones, laboratorios y auditorios según aforo y requerimientos técnicos.
- 📊 **Dashboard & Métricas:** Panel de control con resúmenes de horas asignadas, porcentaje de cobertura de materias y alertas de conflictos no resueltos.
- 💾 **Persistencia de Datos Modular (`store.js`):** Guardado automático en el almacenamiento local del navegador (`LocalStorage`) con posibilidad de importar y exportar datos en formato JSON.
- 🧪 **Dataset de Prueba Incluido (`datos_prueba.json`):** Conjunto de datos de muestra para validar la generación instantánea de horarios con un solo clic.

---

## 🛠️ Stack Tecnológico

- **Frontend:** Vanilla HTML5 semántico, CSS3 moderno (Flexbox, CSS Grid, variables CSS de diseño y tipografía Google Fonts *Inter*).
- **Lógica de Planificación:** JavaScript ES6+ modular (algoritmos de backtracking y restricciones).
- **Persistencia:** Web Storage API (`LocalStorage`) y serialización JSON.

---

## 📂 Estructura del Proyecto

```bash
calendario/
├── index.html            # Interfaz principal, sidebar y contenedor de vistas
├── datos_prueba.json     # Datos de prueba con profesores, materias y aulas
├── css/
│   └── styles.css        # Sistema de estilos y paleta de colores institucional
└── js/
    ├── app.js            # Inicializador de la aplicación y controladores de eventos
    ├── scheduler.js      # Motor algorítmico de asignación de horarios
    ├── store.js          # Capa de almacenamiento y estado global
    └── views/            # Módulos de renderizado para cada sección
```

---

## 🚀 Uso Rápido

No requiere instalación de dependencias pesadas ni compiladores:

1. Abrir la carpeta del proyecto:
   ```bash
   cd calendario
   ```
2. Abrir `index.html` en el navegador, o lanzar un servidor HTTP ligero:
   ```bash
   python3 -m http.server 3000
   ```
3. Acceder a `http://localhost:3000` y explorar el generador de horarios.

---

## 👤 Autor

- **Mendell Noe Parrales Molina** ([@NE0NOE](https://github.com/NE0NOE))
