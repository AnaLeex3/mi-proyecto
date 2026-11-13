# QA Testing Portfolio

Repositorio de práctica para el diseño, la organización y el *version control* de artefactos de testing. Reproduce el flujo de trabajo de un equipo de QA utilizando Git y GitHub.

## Contenido

| Carpeta | Descripción |
|---|---|
| `plan/` | Test plan (PLAN-001) |
| `casos-de-prueba/` | Test cases con precondiciones, pasos y expected result (TC-LOGIN-001, TC-LOGIN-002) |
| `defectos/` | Bug reports (BUG-001, ejemplo de práctica) |

## Técnicas y conceptos aplicados

- Diseño de test cases con black-box testing (equivalence partitioning, boundary value analysis)
- Traceability entre test cases y bugs
- Entry criteria y exit criteria en el test plan
- Version control: commits, branches, merge y resolución de push rechazado

## Convenciones

- **IDs únicos:** `PLAN-###`, `TC-MODULO-###`, `BUG-###`
- **Formato:** todos los artefactos están en Markdown
- **Commits:** mensajes breves que describen el cambio realizado, por ejemplo "Agrega caso de prueba TC-LOGIN-002"

## Alcance

Los artefactos corresponden a un módulo de login ficticio y tienen fines de práctica. El reporte BUG-001 es un ejemplo que ilustra el formato de un bug report.

## Roadmap

- [ ] Traceability matrix
- [ ] Proyecto de práctica sobre un sitio web de pruebas
- [ ] Test summary report
- [ ] Automated tests básicos

## Herramientas

Git, GitHub, Markdown, Linux (Zorin OS)
