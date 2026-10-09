# Azure Compute

## ¿Qué es?

Servicio encargado de proporcionar capacidad de procesamiento.

## Virtual Machines

Una VM es una computadora virtual ejecutándose sobre infraestructura Azure.

### Componentes

```text
VM
│
├── vCPU
├── RAM
├── Disco
├── NIC
├── VNET
└── NSG
```

## Series

### Serie B

- Laboratorios.
- Desarrollo.
- Bajo costo.

### Serie D

- Uso general.
- Aplicaciones empresariales.

### Serie E

- Optimizada para memoria.
- Bases de datos.

### Serie F

- Optimizada para CPU.
- Procesamiento intensivo.

## Escalabilidad

### Scale Up

Más potencia para una misma VM.

```text
2 vCPU
↓
8 vCPU
```

### Scale Out

Más instancias.

```text
VM1
VM2
VM3
```
