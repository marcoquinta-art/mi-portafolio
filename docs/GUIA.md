# Guía del proyecto Git y GitHub

Esta guía explica el trabajo realizado en el Laboratorio 03 utilizando Git y GitHub para controlar y publicar los cambios de un proyecto.

## Requisitos

Para realizar este proyecto se necesita:

- Git instalado en el computador.
- Una cuenta de GitHub.
- Visual Studio Code.
- Conexión a Internet.

## Instalación y uso

Para trabajar con el proyecto se deben seguir estos pasos:

1. Crear o clonar el repositorio desde GitHub.
2. Entrar a la carpeta del proyecto.
3. Abrir el proyecto en Visual Studio Code.
4. Realizar los cambios en los archivos.
5. Guardar los cambios.
6. Publicar los cambios en GitHub.

### Flujo de trabajo

El flujo básico consiste en modificar los archivos, preparar los cambios, crear un commit y enviarlo al repositorio remoto.

Para comprobar el estado del proyecto se utiliza el comando `git status`.

```bash
git status
git add .
git commit -m "Actualiza el proyecto"
git push origin main
```

### Comandos principales

| Archivo o comando | Función                                   | Ejemplo      |
| ----------------- | ----------------------------------------- | ------------ |
| README.md         | Presenta información general del proyecto | `README.md`  |
| `git status`      | Muestra el estado de los archivos         | `git status` |
| `git add .`       | Prepara los cambios para el commit        | `git add .`  |

### Lista de tareas

- [x] Crear el repositorio en GitHub.
- [x] Crear el archivo `docs/GUIA.md`.
- [x] Documentar el proyecto.
- [ ] Verificar la guía publicada en GitHub.

### Enlace externo

Para consultar información sobre Git se puede visitar la documentación oficial de Git:

[Documentación oficial de Git](https://git-scm.com/doc)

### Imagen del proyecto

![Flujo de trabajo con Git y GitHub](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png)

### Publicación

Después de realizar los cambios, se deben preparar y publicar utilizando comandos como `git add`, `git commit` y `git push`.

La guía debe mantenerse actualizada para que otros compañeros puedan comprender el funcionamiento básico del proyecto.
