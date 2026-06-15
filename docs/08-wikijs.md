# Wiki.js

## Objetivo

Aprender:

- Docker Compose
- PostgreSQL
- Redes Docker
- Persistencia de datos
- Reverse Proxy
- HTTPS

## Estado

- [ ] Preparación
- [ ] Docker Compose
- [ ] PostgreSQL
- [ ] Wiki.js
- [ ] Reverse Proxy
- [ ] Acceso web

## Arquitectura

Wiki.js utiliza dos contenedores:

- Wiki.js
- PostgreSQL

La persistencia de datos se almacena en un volumen Docker.

Los contenedores se comunican mediante una red Docker creada automáticamente por Docker Compose.

## Conceptos aprendidos

### Redes Docker

Docker Compose crea automáticamente una red privada para cada proyecto.

Ejemplo:

- wikijs_default
- uptime-kuma_default
- nginx-proxy-manager_default

Esto permite que los contenedores se comuniquen utilizando sus nombres de servicio.

### Volúmenes Docker

Los volúmenes almacenan datos persistentes fuera del contenedor.

Ejemplos:

- portainer_data
- uptime-kuma_uptime-kuma
- wikijs_wikijs_db_data

Gracias a los volúmenes, los datos sobreviven aunque se eliminen o recrean los contenedores.
