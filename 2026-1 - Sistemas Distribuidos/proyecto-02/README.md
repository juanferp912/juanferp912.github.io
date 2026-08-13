# ARGUS: sistema distribuido de monitoreo con camaras

Sistema distribuido para integrar camaras, agentes Edge, una API central y MongoDB mediante Docker Compose y Kubernetes.

## Descripcion

ARGUS registra camaras, recibe heartbeats y eventos de movimiento, expone streams de video y permite operar multiples fuentes locales, USB, IP o RTSP. La API funciona como gateway entre la red central y los agentes Edge.

## Arquitectura y tecnologias

* API backend con Python y FastAPI.
* MongoDB como base de datos.
* Docker Compose para el entorno local.
* Kubernetes para el despliegue distribuido.
* Agentes Edge en Windows con scripts PowerShell.
* Tailscale, MJPEG/RTSP y vision opcional con YOLO.

## Repositorio oficial

[GustavoMejia-UEES/proyecto-sd-p2](https://github.com/GustavoMejia-UEES/proyecto-sd-p2)
