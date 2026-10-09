# RBAC

## ¿Qué es?

Role-Based Access Control.

Sistema encargado de administrar permisos.

## Fórmula

```text
Usuario
+
Rol
+
Scope
=
Permisos
```

## Roles

### Reader

Solo lectura.

### Contributor

Puede:

- Crear
- Modificar
- Eliminar

No puede asignar permisos.

### Owner

Control total.

Incluye gestión de permisos.

## Scope

```text
Management Group
↓
Subscription
↓
Resource Group
↓
Resource
```
``
