# Azure Monitor

## ¿Qué es?

Servicio encargado de monitorear recursos Azure.

## Métricas

Responden:

```text
¿Cuánto?
```

Ejemplos:

```text
CPU 90%
RAM 70%
Disco 80%
```

## Logs

Responden:

```text
¿Qué ocurrió?
```

Ejemplos:

```text
VM reiniciada
Error de aplicación
Inicio de sesión
```

## Log Analytics Workspace

Repositorio central para almacenar logs y métricas.

```text
VM
Storage
Key Vault

     ↓

Workspace
```

## Diagnostic Settings

Permiten enviar:

- Logs
- Métricas

al Workspace.

## Alert Rules

Generan notificaciones automáticas.

Ejemplos:

```text
CPU > 90%

Disco > 85%

VM caída
```

## Flujo

```text
Recurso
↓
Diagnostic Settings
↓
Log Analytics Workspace
↓
Azure Monitor
↓
Alertas
```
