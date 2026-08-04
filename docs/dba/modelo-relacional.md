# Modelo Relacional - Momentos Especiales

## Tablas principales

- CLIENTE(id_cliente PK, nombre, telefono, correo)
- PAQUETE(id_paquete PK, nombre, precio)
- EVENTO(id_evento PK, id_cliente FK, id_paquete FK, fecha, tipo, ubicacion, invitados, estado)
- COTIZACION(id_cotizacion PK, id_evento FK, subtotal, anticipo, saldo)
- PROVEEDOR(id_proveedor PK, nombre, telefono, servicio)
- RECURSO(id_recurso PK, id_proveedor FK, nombre, cantidad)
- SERVICIO(id_servicio PK, id_evento FK, id_proveedor FK, nombre, costo)

## Relaciones

- Un cliente puede solicitar varios eventos.
- Cada evento pertenece a un cliente y tiene un paquete contratado.
- Cada evento puede generar una cotización.
- Un proveedor puede proporcionar varios recursos y servicios.
- Un evento puede requerir varios servicios.
