# Proyecto Shark: videojuego 2D de supervivencia submarina

Videojuego 2D desarrollado en Unity donde el jugador controla un tiburon que se desplaza por escenarios submarinos, usa turbo, evita peligros, enfrenta enemigos y acumula puntos.

## Descripcion del proyecto

El proyecto consiste en una experiencia jugable con menu principal y dos niveles de dificultad. El tiburon puede moverse dentro y fuera del agua, saltar, activar un turbo temporal, comer enemigos comestibles, recibir dano y obtener puntos mientras avanza por el nivel.

## Arquitectura y tecnologias

* **Motor y lenguaje:** Unity 6, version `6000.0.79f1`, con C#.
* **Renderizado:** Universal Render Pipeline (URP) 2D.
* **Entrada e interfaz:** Unity Input System, Unity UI y TextMesh Pro.
* **Diseno:** escenas, prefabs, animaciones, audio, spawners y scripts separados por responsabilidades.

## Funcionalidades clave

1. **Movimiento acuatico y aereo:** control horizontal/vertical en el agua y fisica con gravedad al salir a la superficie.
2. **Turbo:** aceleracion temporal con duracion y recarga visibles en la interfaz.
3. **Supervivencia y puntuacion:** sistema de vida, dano, enemigos, objetos y vidas extra otorgadas por puntos.
4. **Progresion jugable:** menu principal y niveles facil/dificil con orcas, medusas, minas, arpones y buzos.

## Logros tecnicos demostrados

* Programacion orientada a componentes mediante scripts de C# y componentes de Unity.
* Controladores independientes para jugador, salud, puntuacion, audio, camara, enemigos, spawners y UI.
* Integracion audiovisual con animaciones, efectos, musica y sonidos.

---

Repositorio oficial: [ProyectoSharkJFP_JAM](https://github.com/juanferp912/ProyectoSharkJFP_JAM)

*Nota: este proyecto corresponde al Proyecto 03 de la materia de Lenguajes de Programacion (Periodo 2026-1).*
