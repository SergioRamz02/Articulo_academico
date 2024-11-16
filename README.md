# 🌐 Proyecto Final creación de un sitio web 
En este archivo se presentan los objetivos y el procedimiento en general para la creación de un sitio web, así como de su GitHub Pages. Tambien se da una pequeña descripicón del sitio web creado y una imagen del código

## 🎯 Objetivo principal
El objetivo del proyecto es crear un sitio web y enlazarlo a un repositorio en GitHub utilizando los conocimientos adquiridos a lo largo del módulo 1 del curso impartido por DEV.F que lleva como titulo Introducción a la programación.

## Características del proyecto
El contenido del proyecto debe cumplir con las siguientes características, las cuales fueron acordadas y, aceptadas por los alumnos y el sensei:
- Tema libre (nada explicito ni violento)
- Mínimo 6 secciones
- Tres enlaces a diferentes páginas o insertar 3 imágenes
- Titulo y subtítulos
- Contenido semántico
- Estructura ordenada
- Tener un buen README.md (títulos, subtítulos, lista y una imagen del código)

## 🛠️ Herramientas empleadas

- **Visual Studio Code**
- **GIT**
- **GitHub**
- **HTML** (como lenguaje de marcado para la creación del sitio web)

## Proceso de creación del sitio web y comandos empleados 
### Pasos para Crear un Repositorio en GitHub 
1. **Crea una Cuenta en GitHub** (si no tienes una):
   - Visita GitHub y regístrate.
2. **Crea un Nuevo Repositorio**:
   - Haz clic en el botón "New" o visita directamente Crear Repositorio.
   - Llena los campos:
   - Repository Name: Elige un nombre para tu repositorio (por ejemplo, mi-sitio-web).
   - Description: (Opcional) Describe brevemente tu proyecto.
   - Visibility: Elige Public o Private (en este caso public).
   - Haz clic en "Create repository".
### Pasos para Enlazar el Repositorio a tu Computadora 
1. **Crear el Repositorio Local**
   - Crea una carpeta en donde realizaras todo lo relacionado con tu sitio web, en caso de tener dos unidades (Unidad C: O Unidad D:), selecciona la unidad a emplear.
   - Inicializa tu carpeta, para ello abre tu terminal (CMD, PowerShell, Git Bash, o terminal en tu editor de código) y escribe la dirección de la carpeta en donde vas a trabajar,
    luego escribe el comando **git init** y presiona enter.
   - Abre tu terminal (CMD, PowerShell, Git Bash, o terminal en tu editor de código) y usa el siguiente comando:<br>
    *git remote add origin https://github.com/tu-usuario/mi-sitio-web.git*
2. **Verifica el Estado del Repositorio**
   - Coloca en tu terminal (CMD, PowerShell, Git Bash, o terminal en tu editor de código) **git status** y enter.
### Creación del archivo index.html 
  1. Abre VS Code, colocando el comando **code .** en tu terminal (CMD, PowerShell, Git Bash, o terminal en tu editor de código)
  2. Crea un archivo llamado **index.html** el cual es importante para que el sitio web funcione.
  3. Escribe en el editor de texto **!** y da enter, esto te generará la estructura básica de HTML
  4. Guarda el archivo.
### Comandos para guardar cambios y enviarlos a GitHub 
1. **Agrega los Archivos al Área de Staging**
   - Abre tu terminal (CMD, PowerShell, Git Bash, o terminal de VSCode)
   - Primero emplea el comando **git status**, dale enter para ver el status de tu archivo index.html
   - Agrega los cambios escribiendo **git add .** y presiona enter. El punto (.) agrega todos los archivos y cambios. También puedes agregar archivos específicos: git add archivo.html.
2. **Crea un Commit con un Mensaje Descriptivo**
   - Una vez agregado los cambio escribe el comando **git commit -m "Mensaje_descriptivo"** para guardar los cambios en un commit.
3. **Envía los Cambios al Repositorio en GitHub**
   - Para enviar los cambios al repositorio en GitHub emplea el comando **git push origin main** o **git push origin master** dependiendo del nombre de la rama.
   - Cada que realices cambios importantes en la estructura de tu archivo **index.html** repite los pasos del 1 al 3.

## Creación del archivo README.MD
1. Una vez finalizado todo el contenido del sitio web, ve a tu cuenta en GitHub.
2. Presiona el boton que dice **Add README.MD**.
3. Modifica tu archivo con la información importante que quieras dar aconocer sobre tu proyecto.
4. Una vez terminado da en el boton **Commit Changes** que se encuentra en la parte superior derecha.
5. Colocale un nombre (opcional) y guarda los cambios.
6. Envia el archivo a tu repositorio local, para ello abre tu terminal (la que más se te facilite), dirigete a la carpeta donde esta tu archivo **index.html** y coloca el comando
   **git pull origin main** o **git pull origin master** dependiendo del nombre con el que aparezca tu rama.
   
## 🌐 Crear GitHub Pages para tu Sitio Web
1. **Configura GitHub Pages**
    - Ve a la página de tu repositorio en GitHub.
    - Haz clic en "Settings" (Configuración).
    - En el menú de la izquierda, busca la sección "Pages".
    - En "Source", selecciona la rama main o master y elige la carpeta raíz (/root).
    - Haz clic en "Save".
2. **Accede a tu Sitio Web**
   - GitHub Pages generará un enlace para tu sitio web: https://tu-usuario.github.io/mi-sitio-web/.
   - Puede tardar unos minutos en estar disponible.

## Sitio web creado "Artículo Académico: Relación q/m del electrón" 
### Descripción
**Artículo Académico: Relación q/m del electrón** es un sitio web basado en un artículo realizado en el 5to semestre de la carrera en Licenciatura en Física y Matemáticas en ESFM -IPN. 
La creación del sitio corresponde a la entrega de un proyecto final de desarrollo web, pero no deja de ser un sitio educativo e informativo sobre una cantidad importante en la Física, 
que permitio definir y encontrar a una partícula fundamental la cual conocemos actualmente, como electrón.

### Estrutura
El sitio se compone de las siguientes secciones:
- *Inicio*
- *Resumen*
- *Palabras claves*
- *Introducción*
- *Marco teórico*
- *Desarrollo experimental*
- *Resultados*
- *Análisis*
- *Conclusiones*
- *Fuentes Web*

### Código
Por último se muestra una captura de pantalla de una parte del código del archivo  **index.html**

![Código del sitio web](https://i.imgur.com/AsUxxJV.png)

