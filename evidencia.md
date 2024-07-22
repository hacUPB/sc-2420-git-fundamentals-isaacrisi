# Conceptos en Desarrollo de Software: Control de Versiones y Git

## 1. Sistema de Control de Versión

Un sistema de control de versión es una herramienta que permite gestionar cambios en el código fuente y otros archivos de un proyecto a lo largo del tiempo. Permite registrar modificaciones, facilitar la colaboración entre desarrolladores y revertir cambios si es necesario. Es fundamental en el desarrollo de software porque proporciona un historial completo de todas las versiones del código, asegurando la integridad del proyecto y permitiendo a los equipos trabajar de manera eficiente y coordinada sin temor a perder trabajo o sobrescribir cambios importantes.

## 2. Comandos Usados desde la Consola para la Gestión de Repositorios

En el contexto de Git, los comandos básicos que se utilizan para la gestión de repositorios incluyen:

- `git init`: Inicializa un nuevo repositorio Git en el directorio actual.
- `git clone <url>`: Clona un repositorio remoto existente en el directorio local.
- `git add <archivo>`: Añade cambios de archivo al área de preparación (staging area) para ser incluidos en el próximo commit.
- `git commit -m "mensaje"`: Registra los cambios preparados en el repositorio, con un mensaje descriptivo que resume los cambios realizados.
- `git push`: Sube los commits locales a un repositorio remoto.
- `git pull`: Descarga y fusiona los cambios del repositorio remoto al repositorio local.
- `git status`: Muestra el estado actual del repositorio, incluyendo archivos modificados, agregados y sin seguimiento.

Estos comandos son fundamentales para el ciclo básico de trabajo con Git, que incluye la preparación de cambios, la realización de commits y la sincronización con un repositorio remoto.

## 3. ¿Qué es un Repositorio y Cuál es su Uso?

En Git y GitHub, un repositorio es un espacio donde se almacenan los archivos de un proyecto junto con el historial completo de cambios. Un repositorio puede ser local (en tu máquina) o remoto (en un servidor como GitHub). Su propósito principal es facilitar el desarrollo colaborativo permitiendo a múltiples desarrolladores trabajar en el mismo proyecto, compartir código, revisar cambios y mantener un registro detallado de todas las modificaciones realizadas a lo largo del tiempo. Además, los repositorios remotos como GitHub ofrecen funcionalidades adicionales como el seguimiento de problemas, solicitudes de extracción y la integración continua, que son esenciales para el desarrollo de software en equipos grandes y distribuidos.

---
