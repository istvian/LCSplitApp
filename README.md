# **LCSplitApp**
#### **Información general**
Esta aplicación de consola es una herramienta para cortar los textos biblicos desde los videos en señas (Soporta varios idiomas).
#### **Instalación**
- Descarga la versión más actualizada de LCSplit.rar en [Releases](https://github.com/istvian/LCSplitApp/releases/download/1.0.2/LCSplit1.0.2.rar)
- Descomprime el archivo .rar en la ubicación que quieras.
- Ejecuta el archivo _LCSplit.exe_ 

#### **Modo de uso**
##### Cortado de textos
- Descarga el texto requerido desde la aplicación naranja
- En la barra superior de la consola encontraras las opciones actuales, con estas opciones el programa buscara el archivo de video para luego cortarlos, fijate que coincidan con el archivo de video. (La ruta del archivo de video generalmente es _C:\Users\TuNombreDeUsuario\Videos\JWLibrary\nwt_xxx_). 

**Configuración Inicial**

- **Configuración por defecto**
- La aplicación esta configurada por defecto para buscar archivos de tipo mp4, en idioma SCH, Calidad 720 y guardarlos en formato mp4.

- Si no tienes los videos descargados en 720 puedes utilizar el comando /calidad y escribir la calidad que tengas descargadas (Ej: 240, 360, 480, 720).

- Si deseas buscar textos en otro idioma utiliza el comando /idioma para cambiar el idioma.

- Si la aplicación no encuentra los textos fijate que el formato coincida, por defecto la aplicación busca textos con formato mp4, pero algunos idiomas tienen formato m4v u otros, para cambiar esto escribe /formato. Este comando te permitira fijar el formato de textos que la aplicación buscara y el formato de salida.

- **¿De donde saco esos datos?**
- Busca la ruta de descarga de la aplicación naranja _C:\Users\TuNombreDeUsuario\Videos\JWLibrary\nwt_xxx_ y busca un archivo de video de la Biblia. Debiese llamarse algo parecido a esto: **nwt_40_Mt_SCH_01_r720P.mp4**
Donde: 
- SCH es el idioma
- 720 es la calidad
- mp4 es el Formato (**No formato de salida**)
(Si deseas cambiar todas estas opciones escribe /set y sigue los pasos).

Cuando tengas las opciones correctas puedes buscar el texto que necesites:
- _Ejemplos:_
- _Mateo 24:14_
- _Mateo 24:13-14_
- _Mat 24:1,14_

#### Comandos
A continuación una lista de todos los comandos que puedes usar.
Para usarlos solo escribelos (incluido el /) y presiona la tecla Enter).

- /calidad = Cambia la calidad del archivo de video que va a buscar (El archivo que tienes descargado por la aplicación).
- /clear = Limpia la consola
- /debug = Activa/Desactiva el modo debug
- /formato = Te permite cambiar el formato del archivo buscado (El archivo que tienes descargado por la aplicación) y el formato de salida del video (El archivo que vas a guardar).
- /getlink = Abre con el navegador el link para descargar la versión siguiente.
- /help = Muestra este archivo de ayuda desde el [sitio](https://github.com/istvian/LCSplitApp) de LCSplitApp.
- /idioma = Cambia la sigla del archivo de video buscado (Si quieres cambiar de idioma debes usar este comando).
- /set = Te permite cambiar todas las configuraciones. (Idioma, Calidad, Formato y Formato de Salida)
- /update = Abre en el navegador las [versiones](https://github.com/istvian/LCSplitApp/releases) disponibles para descargar
- /exit = Sale de la consola


