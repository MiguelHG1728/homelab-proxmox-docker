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
