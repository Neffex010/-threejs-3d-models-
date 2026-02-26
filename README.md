# Carga y Animación de Modelos 3D con Three.js (FBX)

## Datos Institucionales
* **Institución:** Instituto Tecnológico de Pachuca (ITP)
* **Carrera:** Ingeniería en Tecnologías de la Información y Comunicaciones (ITICS)
* **Materia:** Desarrollo en Ambientes Virtuales 
* * **Tema:** Carga y animación de modelos FBX con Three.js
* **Maestro:**  M.C. Víctor Manuel Pinedo Fernández
* **Alumno:** Luis Enrique Cabrera Garcia
* **Fecha:** 26 de febrero de 2026

---

## Descripción del Proyecto
Este repositorio contiene el código de una aplicación web 3D construida con **Three.js**. El proyecto se basa en el ejemplo oficial de carga de modelos `loader / fbx`, el cual fue analizado, modularizado y modificado para ejecutarse correctamente con dependencias locales y nuevas animaciones.

## Características y Actividades Realizadas
* **Modularización de Código:** El código fuente original se separó en una estructura de archivos más limpia, aislando el HTML (`index.html`) de la lógica de JavaScript (`js/main.js`) dentro de la carpeta `threejs-3d-models`.
* **Configuración de Dependencias Locales:** Se descargó el repositorio completo de Three.js para alojar las librerías necesarias localmente, actualizando las rutas en el código para asegurar la correcta importación de los módulos sin depender de conexiones externas.
* **Modificación de Animaciones:** Con la asistencia de Inteligencia Artificial, se modificó la lógica de animación en el archivo principal para cambiar los movimientos predeterminados del personaje cargado.
* **Despliegue Público:** El proyecto cuenta con control de versiones mediante Git y está desplegado de manera pública utilizando **GitHub Pages**.

## Estructura del Proyecto
```text
threejs-3d-models/
├── index.html          # Estructura principal y canvas
├── js/
│   └── main.js         # Lógica de Three.js, renderizado y animaciones
└── [Carpetas de Three.js con dependencias locales]

Ejecución y Visualización
Para ver la aplicación en funcionamiento en el entorno público, visita el siguiente enlace:

[🔗 Ver Proyecto en GitHub Pages](Aquí pon la URL de tu GitHub Pages)

## Para ejecutarlo de manera local:

## Clona este repositorio.

## Abre la carpeta del proyecto en tu editor de código.

## Inicia un servidor local (por ejemplo, con la extensión Live Server en VS Code) para evitar errores de políticas CORS al cargar los modelos FBX.
