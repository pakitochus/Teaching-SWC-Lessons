# Git y Github para Investigación
## Yosigopublicando 16/04/2021
### Materiales y Prerrequisitos
_Francisco Jesús Martínez Murcia_

Bienvenidos al curso de [Git y Github para investigación](https://sites.google.com/go.ugr.es/yosigopublicando/los-cursos#h.w27bxfwz4bo6). El taller que daré se podrá seguir de forma práctica o simplemente como espectador. El taller es un resumen de lo que hacemos en la Software Carpentry, podéis encontrar la lección original en: 

[https://swcarpentry.github.io/git-novice/](https://swcarpentry.github.io/git-novice/)

En caso de querer seguirlo de forma práctica, os informo de los pasos a instalar. 

## Prerequisitos:
Git es el sistema de control de versiones (CVS) que vamos a utilizar, ya que es prácticamente el estándar, y interactúa de forma sencilla con github. Necesitarás: 

- Un navegador soportado (Chrome, Firefox, Safari, o Microsoft Edge entre otros)
- Para algunas partes del taller debes tener cuenta en github.com. Si tienes mucha preocupación por la privacidad, se puede mantener el email privado en las instrucciones de GitHub. 
- Un editor de texto plano. Notepad (el bloc de notas) en windows, gedit/nano/emacs en Linux, y cosas así.
- Terminal de comandos por texto y git. Esto último os lo explico aquí

## Instalación de bash y Git
### Windows
1. Descarga el [instalador de git para Windows](https://gitforwindows.org/). 
2. Sigue los pasos (siguiente, siguiente...) 
3. Algunas opciones interesantes: usar el editor que se quiera, y opción "let git decide".
4. Importante marcar: "Git from the command line and also from 3rd-party software" y "Use the native Windows Secure Channel Library" en las pantallas que aparezcan.
5. Next next... 
6. Asegúrate que en uno de los pasos está seleccionado "Git Credential Manager **Core**".
7. Si no tienes preparada tu variable de entorno "`HOME`" (o no tienes ni idea de qué significa hulio): Abre la ventana de comandos de windows (Menú inicio, y luego busca `cmd` y pulsa Enter)
8. Escribe lo siguiente exactamente: `setx HOME "%USERPROFILE%"`
9. Pulsa Enter, deberías ver `SUCCESS: Specified value was saved`.
10. Sal de la ventana de comandos escribiendo `exit` y pulsando Enter
Si necesitas más datos, aquí hay un vídeo tutorial: 
[https://www.youtube.com/watch?v=339AEqk9c-8](https://www.youtube.com/watch?v=339AEqk9c-8)


### MacOS
Para macOS, instala Git para Mac descargando y ejecutando el instalador más reciente de "mavericks" desde [esta lista](http://sourceforge.net/projects/git-osx-installer/files/). Dado que el instalador no está firmado por el desarrollador, seguramente tengas que hacer click derecho (control -click) en el paquete .pkg, darle a "Abrir" y hacer clic en "Abrir" en la ventana emergente. Tras instalar git, no habrá nada en la carpeta /Aplicaciones, dado que Git es un programa de línea de comandos. Para versiones más antiguas de OS X (10.5-10.8) utiliza el instalador más reciente con la etiqueta "snow-leopard" [disponible aquí](http://sourceforge.net/projects/git-osx-installer/files/). A continuación os pongo un videotutorial: 
[https://www.youtube.com/watch?v=9LQhwETCdwY](https://www.youtube.com/watch?v=9LQhwETCdwY)


### Linux
Si no tienes git instalado ya, instálalo desde el gestor de paquetes de tu distribución. En el caso de Debian/Ubuntu debería bastar con `sudo apt-get install git` y para Fedora `sudo dnf install git`.



