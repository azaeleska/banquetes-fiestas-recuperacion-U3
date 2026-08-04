# Pruebas de validación del Login

## Caso 1: campos vacíos
- Datos: usuario vacío, contraseña vacía y rol sin seleccionar.
- Resultado esperado: el sistema muestra el mensaje “Completa usuario, contraseña y rol”.

## Caso 2: contraseña corta
- Datos: usuario “cristhian”, contraseña “123” y rol “DEV”.
- Resultado esperado: el sistema muestra el mensaje “La contraseña debe tener al menos 6 caracteres”.

## Caso 3: datos válidos
- Datos: usuario “cristhian”, contraseña “123456” y rol “DEV”.
- Resultado esperado: el sistema muestra un mensaje de acceso validado para el rol seleccionado.
