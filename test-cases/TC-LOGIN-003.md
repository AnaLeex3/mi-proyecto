# TC-LOGIN-003: Bloqueo de cuenta tras 3 intentos fallidos

- **Requisito:** REQ-LOGIN-02
- **Prioridad:** Media
- **Precondiciones:** El usuario existe, está activo y no tiene intentos fallidos previos

## Pasos
1. Abrir la página de login
2. Ingresar usuario válido y una contraseña incorrecta, y presionar "Entrar" (intento 1)
3. Repetir con una contraseña incorrecta (intento 2)
4. Repetir con una contraseña incorrecta (intento 3)
5. Ingresar usuario válido y la contraseña correcta, y presionar "Entrar" (intento 4)

## Datos de prueba
- Usuario: usuario_prueba
- Contraseña incorrecta: clave_incorrecta_123
- Contraseña correcta: (definida en el entorno de pruebas)

## Resultado esperado
Tras el tercer intento fallido, el sistema bloquea la cuenta y muestra un mensaje de bloqueo. En el cuarto intento, aun con la contraseña correcta, el sistema NO permite el acceso.

## Resultado real
(se llena al ejecutar)

## Estado
Pendiente
