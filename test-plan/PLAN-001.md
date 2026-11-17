# PLAN-001: Plan de pruebas del módulo de login

- **Versión del documento:** 1.0
- **Responsable:** AnaLeex3

## Objetivo
Verificar que el login permite el acceso a usuarios válidos y rechaza credenciales incorrectas.

## Alcance
- **Dentro:** login con usuario y contraseña, mensajes de error.
- **Fuera:** recuperación de contraseña, registro de usuarios.

## Enfoque de pruebas
- Caja negra: partición de equivalencia y valores límite.
- Pruebas funcionales manuales.
- Regresión cuando cambie el módulo.

## Casos de prueba incluidos
- TC-LOGIN-001: Login con datos válidos
- TC-LOGIN-002: Login con contraseña incorrecta

## Entorno
Navegador Firefox, aplicación versión 1.0.

## Criterios de entrada
- La aplicación está desplegada en el entorno de pruebas.
- Los casos de prueba están revisados.

## Criterios de salida
- 100% de los casos de prioridad alta ejecutados.
- Sin defectos de severidad alta abiertos.

## Riesgos
- Datos de prueba no disponibles a tiempo.
- Cambios en los requisitos durante la ejecución.
