Rol de Ansible: SSH
===================

Configuración de SSH en Debian.

Requerimientos
--------------

Puerto usado para SSH abierto.

Variables del Rol
-----------------

| Variable | Descripción |
| -------- | ----------- |
| ssh_admin | Nombre del usuario con permisos de administrador. |
| ssh_llaves_admin | Lista con las llaves permitidas para el administrador. |
| ssh_puerto | Puerto configurado para SSH. |

Dependencias
------------

* cloudcxn.usuarios

Libro de Ejemplo
----------------

```yaml
---
- hosts: servers
  roles:
    - cloudcxn.ssh
```

Licencia
--------

MIT.

Información del Autor
---------------------

El rol fue creado en noviembre del 2022 por Byron Quezada para
[Cloud CxN](https://www.cloudcxn.com).
