# La Bolonería: Sistema de Gestión Automatizado y Análisis de Datos

Ecosistema de microservicios contenerizados diseñado para automatizar el control de inventarios, costos y proyecciones de demanda para un negocio gastronómico especializado.

## 📝 Descripción del Proyecto
El núcleo del proyecto consiste en resolver el desafío de integrar múltiples servicios autónomos para centralizar y optimizar la operación de backend. A través de flujos lógicos asíncronos y procesamiento de lenguaje natural en tiempo real, el sistema monitorea niveles críticos de stock, calcula la rentabilidad del menú y genera predicciones inteligentes basadas en el historial de consumo de la bolonería.

## 🛠️ Arquitectura y Tecnologías
El sistema se diseñó bajo una arquitectura distribuida y modular:

* **Orquestación de Procesos (n8n):** Automatización asíncrona mediante webhooks seguros que conectan las capas del sistema y gestionan el formateo dinámico de datos.
* **Base de Datos Relacional (PostgreSQL):** Almacenamiento consistente de transacciones, recetas e insumos, optimizado con consultas SQL avanzadas para calcular costos y márgenes en caliente.
* **Inteligencia Artificial (Mistral AI):** Consumo de LLMs para procesar analíticas predictivas sobre la demanda de ingredientes y generar alertas inteligentes estructuradas.
* **Contenerización (Docker & Docker Compose):** Aislamiento de servicios para garantizar portabilidad absoluta y despliegues reproducibles sin fricción.

## 🚀 Funcionalidades Clave
1. **Flujos Lógicos Automatizados:** Orquestación de eventos asíncronos que conectan la base de datos con los servicios de inteligencia artificial.
2. **Cálculo Financiero y Operativo:** Consultas SQL avanzadas para estimar costos de producción de bolones y automatizar la identificación de puntos de reorden de insumos.
3. **Predicción Inteligente de Stock:** Generación automática de semáforos de riesgo y proyecciones de consumo a 7 días en formato estructurado JSON.

## 🎯 Logros Técnicos Demostrados
* **Integración y Consistencia de Datos:** Diseño de esquemas relacionales eficientes y consultas SQL analíticas en bases distribuidas.
* **Procesamiento Predictivo con LLMs:** Configuración de prompts de analítica avanzada para obligar respuestas en formato JSON limpio para su uso directo en la aplicación.
* **Infraestructura Replicable:** Despliegue multi-contenedor modularizado que facilita el desarrollo local y entornos productivos estables.

---
🔗 *Nota: Este proyecto forma parte del portafolio académico para la materia de Sistemas Distribuidos (Periodo 2026-1).*
