# Infraestructura n8n + Traefik

Este entorno contiene la configuración para desplegar n8n con Traefik como proxy inverso y certificados TLS automáticos vía Let's Encrypt.

## Requisitos
- Docker
- Docker Compose
- Puerto 80 y 443 libres (Apache debe estar detenido)

## Comandos básicos

```bash
docker compose up -d
docker compose logs -f
