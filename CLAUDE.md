# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Estado actual del repositorio

Repositorio recién creado: contiene únicamente `README.md` (solo el título `# curso-claude`) y un commit
`Initial commit` en la rama `main`. Todavía **no hay** código fuente, gestor de paquetes, toolchain,
tests ni configuración de build.

Consecuencia práctica: no existen comandos de build, lint o test que ejecutar. En cuanto se defina el
stack, añade aquí las secciones «Comandos» y «Arquitectura» (incluyendo cómo correr un único test) en
lugar de dejar que se descubran leyendo archivos.

## Entorno de desarrollo

- Windows 11; el shell principal es **Windows PowerShell 5.1**, donde `&&` y `||` no existen: usa
  `comando; if ($?) { siguiente }` para encadenar condicionalmente.
- La ruta del proyecto contiene un espacio (`...\Nueva carpeta\curso-claude`). Cita siempre las rutas
  en los comandos, o fallarán al partirse por el espacio.

## Idioma

El usuario escribe en español; responde en español. El código y los identificadores pueden ir en inglés
salvo que el usuario indique lo contrario.
