# Reserva de Horas Médicas

Proyecto DevOps integrador para servicio web de reserva de horas médicas.

## Descripción
Servicio web estático servido con Nginx mediante Docker.

## Ejecución local
docker compose up -d

Luego abrir http://localhost:8080

reserva-horas-medicas/
├── src/
│ ├── index.html # Formulario de reserva
│ └── styles.css # Estilos del formulario
├── .env.example # Plantilla de variables de entorno
├── .gitignore # Archivos ignorados por Git
├── docker-compose.yml # Orquestación del servicio
├── Dockerfile # Imagen personalizada basada en nginx:alpine
└── README.md # Este archivo

## Requisitos previos

- [Docker Desktop](https://www.docker.com/products/docker-desktop/) instalado y ejecutándose
- [Git](https://git-scm.com/downloads)
- Navegador web

## Instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/JonathanIACC/Proyecto-DevOps.git
cd Proyecto-DevOps