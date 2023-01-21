# Qué es Git?

<p align="center">
  <img src="git.png" />
</p>

Git es un sistema de control de versiones de código que permite a los desarrolladores rastrear los cambios en el código fuente a lo largo del tiempo, colaborar en un proyecto y mantener un historial completo de todas las modificaciones realizadas. Es una herramienta esencial para cualquier equipo de desarrollo de software ya que permite trabajar de manera eficiente, organizada y segura en proyectos de cualquier tamaño. Con Git, los desarrolladores pueden trabajar de manera descentralizada y no necesitan una conexión a internet para funcionar. Es una de las herramientas más populares y ampliamente utilizadas en la industria.

# ¿Qué es GitHub?

<p align="center">
  <img src="github2.jpg" />
</p>

GitHub es una plataforma web que proporciona alojamiento para proyectos de control de versiones que utilizan Git. Es una herramienta popular para desarrolladores de todo el mundo para alojar, compartir y colaborar en proyectos de código abierto y privado. Con GitHub, los desarrolladores pueden crear repositorios para alojar su código, seguir el progreso del proyecto, colaborar con otros desarrolladores y hacer contribuciones a proyectos de código abierto existentes. Además, GitHub proporciona una variedad de funciones adicionales, como la posibilidad de realizar revisiones de código, crear problemas y solucionarlos, y utilizar integraciones de terceros para mejorar el flujo de trabajo del equipo.


# Instalación de Git en Windows
1. Descarga el instalador de Git para Windows desde el sitio web oficial de Git: https://git-scm.com/download/win
2. Ejecuta el archivo descargado e instala Git siguiendo las instrucciones del asistente de instalación.
3. Abre una ventana de comandos (cmd) y verifica la instalación ejecutando el comando `git --version`. Debería mostrarte la versión de Git que acabas de instalar.

# Instalación de Git en Linux
1. Abre una terminal y ejecuta el comando `sudo apt-get install git` (para distribuciones basadas en Debian) o `sudo yum install git` (para distribuciones basadas en Red Hat).
2. Verifica la instalación ejecutando el comando `git --version`. Debería mostrarte la versión de Git que acabas de instalar.

# Configuración básica de Git
1. Configura tu nombre de usuario y correo electrónico en Git. Este paso es importante para identificar quién está realizando los cambios en el repositorio. Ejecuta los siguientes comandos en tu terminal o línea de comandos:

    `git config --global user.name "Tu nombre de usuario"`
    `git config --global user.email "tu-correo@ejemplo.com"`


2. Configura el editor de texto predeterminado que deseas utilizar con Git. Por ejemplo, si deseas utilizar el editor de texto "nano", ejecuta el siguiente comando:

    `git config --global core.editor nano`


3. (Opcional) Configura una clave ssh para conectarte a repositorios remotos de forma segura. Este paso es necesario si deseas trabajar con repositorios remotos y deseas evitar ingresar tu contraseña cada vez que realices una operación. Puedes generar una clave ssh siguiendo las instrucciones en este enlace https://docs.github.com/es/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

4. (Opcional) Configura un alias para comandos de git. Los alias son una forma de asignar un nombre corto a un comando de git para facilitar su uso. Por ejemplo, si deseas crear un alias para el comando `git log --oneline --decorate --graph --all` puedes usar el siguiente comando: 

    `git config --global alias.lg "log --oneline --decorate --graph --all"`