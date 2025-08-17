# Sistema Operativo — Instalación y configuración inicial

## Opción A: Proxmox VE
- Crear USB booteable.
- Instalar y asignar IP estática para administración.
- Crear almacenamiento local (ZFS, LVM o directory).
- Crear puentes de red (vmbr0, etc.).

## Opción B: Linux (ej. Debian/Ubuntu Server)
- Particionado y formato.
- Usuario administrador y SSH.
- IP estática y hostname.
- Servicios base: NTP, firewall, fail2ban.

## Endurecimiento mínimo
- Actualizaciones automáticas.
- SSH con claves.
- Usuarios/grupos.
- Registro de cambios en esta sección.