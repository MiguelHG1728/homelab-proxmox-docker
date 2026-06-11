# Hardware

## Equipo reutilizado

El homelab está montado sobre un ordenador de sobremesa reutilizado.

### Especificaciones

| Componente | Valor |
|------------|--------|
| CPU | Intel Core i5-9600K |
| RAM | 16 GB |
| SSD | Kingston A400 480 GB |
| HDD | Toshiba HDWD110 1 TB |
| Red | Ethernet |
| BIOS | UEFI |

## Objetivo

Utilizar hardware existente para aprender:

- Proxmox
- Virtualización
- Linux
- Docker
- Monitorización
- Backups
- Reverse Proxy
- Automatización

## Arquitectura física

```text
Servidor físico
├── SSD Kingston 480 GB
│   ├── Proxmox
│   └── Máquinas virtuales
│
└── HDD Toshiba 1 TB
    └── Backups
```
