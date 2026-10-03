# Proyecto de Versionamiento

Proyecto ficticio utilizado para demostrar un flujo de trabajo con Git,
GitHub y GitHub Actions.

## Herramientas

- Git
- GitHub
- GitHub Actions

## Flujo de trabajo

Se utilizarán las siguientes ramas:

- main: versión estable del proyecto.
- develop: integración de cambios.
- feature/*: desarrollo de nuevas funciones.

Los cambios se integrarán mediante Pull Requests.

## Política de commits

Los mensajes de commit serán claros y utilizarán una convención sencilla:

- feat: nueva función
- fix: corrección
- docs: documentación
- test: pruebas
- chore: configuración o mantenimiento

Ejemplos:

feat: agregar página principal
fix: corregir título
docs: actualizar README

## Despliegue

Se utilizará integración y despliegue continuo mediante GitHub Actions.

Cuando un cambio sea integrado en la rama main, GitHub Actions ejecutará
automáticamente el proceso definido en el workflow.