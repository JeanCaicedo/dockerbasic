# dockerbasic

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

Notas personales de los **primeros pasos con Docker** durante un bootcamp. El repo es un registro de comandos básicos ejecutados desde la terminal (PowerShell) mientras aprendía el flujo de imágenes y contenedores.

No es un proyecto ejecutable: es una chuleta de comandos y salidas reales capturadas durante el aprendizaje.

## Contenido

```
dockerbasic/
├── docker-config.json   # Log de comandos ejecutados y sus salidas
├── pruebas-docker/      # Carpeta de pruebas
└── README.md
```

## Comandos documentados

### Imágenes y contenedores

```bash
# Ejecutar un contenedor y mostrar "Hello World"
docker run ubuntu echo "Hello World"

# Listar contenedores activos
docker ps

# Listar todos los contenedores (incluyendo detenidos)
docker ps -a

# Descargar una imagen
docker pull busybox

# Listar imágenes locales
docker image ls
```

### Información del sistema

```bash
# Ver versión del cliente y el servidor
docker version

# Información general del daemon
docker info
```

## Entorno

- Docker Desktop 4.19.0 sobre Windows
- Docker Engine 23.0.5
- Ejecutado desde PowerShell

## Notas

- Repo de aprendizaje, conservado como memoria del primer contacto con Docker.
- El archivo `docker-config.json` contiene salidas crudas de terminal (no es JSON estructurado).

## Autor

Jean Caicedo — [@JeanCaicedo](https://github.com/JeanCaicedo)
