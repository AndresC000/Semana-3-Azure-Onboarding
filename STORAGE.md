# Azure Storage

## ¿Qué es?

Servicio encargado de almacenar información.

## Storage Account

Contenedor principal de almacenamiento.

```text
Storage Account
│
└── Datos
```

## Tipos

### Blob Storage

- PDF
- Imágenes
- Videos
- Backups

### Azure Files

Carpetas compartidas.

### Queue Storage

Mensajes entre aplicaciones.

### Table Storage

Datos NoSQL.

## Redundancia

### LRS

```text
Mismo Datacenter
```

### ZRS

```text
Availability Zones
```

### GRS

```text
Regiones
```

### RA-GRS

```text
GRS + Lectura de réplica
```

### GZRS

```text
ZRS + GRS
```

## Resumen

```text
LRS = Datacenter

ZRS = Zonas

GRS = Regiones

RA-GRS = Lectura

GZRS = Zonas + Regiones
```
