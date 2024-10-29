# Github Actions

Hey de demostración de CI/CD con github actions

## Sesión 1

En esta sesión aprenderemos:
  - Github Actions: Qué son, para qué sirven y cómo configuralas.
  - Creación y configuración de ramas.
  - Gestión de Pull requests.
  - Introducción a Rulesets (Requerir pull-requests para merges sobre develop y main)

**Tarea 1:**

Crea un repositorio con tu cuenta Github que contenga el contenido de este, que puedes descargar como .zip desde la interfaz.

En ese repositorio, realiza la siguiente configuración:

 - Crea una nueva rama develop y súbela al repositorio.
 - Copia el contenido descargado previamente a dicha rama develop.
 - Configura el repositorio para que no se pueda subir contenido directamente a develop y/o main -> Pull Request
 - Intenta realizar ahora un cambio directamente sobre develop. ¿Qué ocurre? 


**Tarea 2:**

Crea un flujo de trabajo nuevo "Hola Mundo" que saque este mensaje en consola y muestre el contenido del repositorio con un pequeño script Bash.

 - Estando en la rama develop, crea una nueva, por ejemplo feature/nuevo-flujo-holamundo
 - Crea y edita el flujo en el directorio .github/workflows empleando la ayuda disponible en Github.
 - Sube el contenido de la nueva rama y activa el flujo creando una pull request de la rama sobre develop.
 - Verifica el funcionamiento del flujo.
 - Fin!

**Prerequisitos:**

  - Cuenta Github + creación de repositorios + uso básico (commit, push).
  - Ubuntu 20.04 con permisos de administrador.
  - Instalación de dependencias.

**Dependencias:**

Para las sesiones futuras, es conveniente ir instalando las utilidades detalladas en INSTALL.txt  