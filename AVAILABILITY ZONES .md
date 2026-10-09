# Availability Zones

## ¿Qué son?

Son centros de datos independientes dentro de una misma Region.

```text
East US

├── AZ1
├── AZ2
└── AZ3
```

## Beneficios

- Alta disponibilidad.
- Tolerancia a fallos.
- Continuidad operativa.

## Ejemplo

```text
AZ1
└── VM01

AZ2
└── VM02
```

Si AZ1 falla:

```text
AZ1 ❌

AZ2 ✅
```

## Concepto clave

```text
Region = Ciudad

AZ = Edificios distintos dentro de la ciudad
```
