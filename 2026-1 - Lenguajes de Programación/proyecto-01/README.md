# PRO-BOT: Sistema Web de Consulta de Reglas e Inyección Dinámica de Datos basado en Programación Lógica

Ecosistema web integral que comunica el paradigma orientado a objetos/estructurado con el paradigma declarativo, creando un agente conversacional (Chatbot) interactivo para un entorno de juego RPG.

## 📝 Descripción del Proyecto
El núcleo del proyecto consiste en resolver el desafío técnico de la comunicación bidireccional entre tecnologías web modernas y un motor de programación lógica pura. A través de una interfaz de chat en tiempo real, los usuarios interactúan con un "oráculo" que valida restricciones del juego (viabilidad de misiones, niveles de experiencia) y ejecuta simulaciones de combate matemático procesando variables dinámicas en caliente.

## 🛠️ Arquitectura y Tecnologías
El sistema se diseñó bajo una arquitectura desacoplada de microservicios:

* **Motor Lógico (SWI-Prolog):** Núcleo analítico y base de conocimientos relacional. Expone endpoints JSON mediante un servidor HTTP nativo (`library(http/thread_httpd)`) y muta la memoria en caliente utilizando predicados dinámicos (`:- dynamic`).
* **Backend de Control (Laravel / PHP):** Capa middleware encargada de capturar las entradas de usuario, sanitizar datos, detectar intenciones mediante expresiones regulares (`preg_match`) y despachar peticiones HTTP asíncronas hacia el servicio lógico.
* **Frontend (Tailwind CSS & JS Asíncrono):** Interfaz SPA (Single Page Application) responsiva con soporte para modo oscuro que gestiona la manipulación dinámica del DOM en tiempo real.
* **Infraestructura (Docker & Docker Compose):** Contenerización multi-servicio en entornos aislados (`laravel_app` y `prolog_service`), garantizando la portabilidad absoluta del sistema.

## 🚀 Funcionalidades Clave
1. **Inyección Dinámica de Hechos (Runtime Mutation):** Inserción de nuevas entidades (jugadores/enemigos) en la memoria volátil de Prolog a través de comandos de lenguaje natural.
2. **Motor de Inferencia para Combates:** Resolución lógica que evalúa el inventario del personaje, selecciona el arma disponible y calcula la reducción de puntos de salud del oponente mediante unificación.
3. **Evaluación Clausular de Misiones:** Procesamiento de reglas complejas para verificar de forma relacional si un héroe cumple con los requisitos mínimos de nivel y objetos.

## 🎯 Logros Técnicos Demostrados
* **Integración de Sistemas Heterogéneos:** Comunicación efectiva de paradigmas opuestos mediante APIs REST utilizando JSON como puente de datos.
* **Aplicación Práctica de Programación Declarativa:** Uso real de conceptos teóricos como *backtracking* y unificación lógica en un entorno de producción web.
* **Prácticas de DevOps:** Orquestación multi-contenedor para aislar los entornos de ejecución y eliminar conflictos de dependencias en local.

---
🔗 *Nota: Este proyecto forma parte del portafolio académico para la materia de Lenguajes de Programación (Periodo 2026-1).*