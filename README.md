# Proyecto IoT - Clima con Node-RED

Este proyecto consulta datos climáticos desde un endpoint público (API REST), procesa los datos en Node-RED y los visualiza en un panel interactivo.

## Ejecutar el proyecto

1. Clonar el repositorio:
```
git clone https://github.com/TU_USUARIO/iot-clima-nodered.git
```

2. Levantar los contenedores:
```
docker-compose up -d
```

3. Acceder a Node-RED en: [http://localhost:1880](http://localhost:1880)

## Archivos incluidos
- `informe.docx`: Informe técnico del proyecto.
- `flujo-nodered.json`: Export del flujo Node-RED.
- `docker-compose.yml`: Configuración de contenedores Docker.
