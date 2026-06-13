# Sistema de Gestión de Torneos y Motor de Predicciones Deportivas (Mundial)

Aplicación web interactiva que implementa un módulo administrativo completo (CRUD) para la gestión de selecciones nacionales y un sistema dinámico para el cálculo y procesamiento de predicciones de partidos en tiempo real.

## 📝 Descripción del Proyecto
El objetivo de este proyecto es construir una plataforma interactiva donde los administradores puedan gestionar la información de un torneo global (países participantes, fixtures y resultados de partidos). Paralelamente, el sistema cuenta con un motor de predicciones que permite a los usuarios registrar sus pronósticos y calcula automáticamente los aciertos y puntajes basados en los resultados reales ingresados por el administrador.

## 🛠️ Arquitectura y Tecnologías
* **Backend / Lógica del Sistema:** [Indica aquí el lenguaje/framework usado, ej: PHP/Laravel, Node.js, Python/Flask, etc.] encargado del enrutamiento, control de sesiones, validación de formularios y ejecución del algoritmo de puntuación de predicciones.
* **Base de Datos:** [Indica aquí la base de datos, ej: MySQL, PostgreSQL, SQLite] para el almacenamiento relacional de selecciones, usuarios, partidos y registros de apuestas.
* **Interfaz de Usuario:** [Indica aquí si usaste Bootstrap, Tailwind, CSS puro, etc.] estructurada para ofrecer un panel de control limpio para el administrador y una vista intuitiva de apuestas para el usuario final.

## 🚀 Funcionalidades Clave
1. **Módulo CRUD Administrativo:** Control total (Crear, Leer, Actualizar, Eliminar) sobre el catálogo de países participantes, estadios y fases del mundial.
2. **Gestor de Fixture y Marcadores:** Panel dedicado para que el administrador registre partidos y actualice los resultados finales en caliente.
3. **Motor de Predicciones Dinámicas:** Algoritmo que evalúa los pronósticos de los usuarios versus los resultados reales, asignando puntajes según el nivel de acierto (ej: acertar ganador, marcador exacto, etc.).

## 🎯 Logros Técnicos Demostrados
* **Persistencia y Manipulación de Datos:** Diseño de un modelo de datos relacional con integridad referencial (llaves foráneas) para ligar usuarios, partidos y predicciones.
* **Arquitectura de Software Basada en Roles:** Separación clara de privilegios entre el rol de Administrador (gestión de datos globales) y el rol de Usuario (ingreso de predicciones personales).
* **Validación y Seguridad:** Sanitización de entradas del lado del servidor para evitar registros corruptos o inconsistencias en los marcadores de los partidos.

---
🔗 *Nota: Este proyecto forma parte del portafolio académico para la materia de Lenguajes de Programación (Periodo 2026-1).*