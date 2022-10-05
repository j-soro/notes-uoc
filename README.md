# Notas UOC
## Un sistema para el estudio y organización del grado en Ingeniería Informática (UOC)

La carpeta `UOC` es un Vault de Obsidian con plugins preconfigurados. No es necesario instalar nada, aunque se recomienda la familia tipográfica Iosevka. Más abajo hay dos listas de los plugins instalados.

## Requisitos
+ [Obsidian](https://obsidian.md)
+ Puedes utilizar cualquier editor Markdown o de texto plano, pero no funcionarán ciertas cosas ya que necesitan los plugins de Obsidian.

## Objetivo
La idea es no necesitar de la web de la UOC salvo que sea estrictamente necesario para hacer alguna tarea. De forma que la consulta de fechas, actividades, PECs pueda hacerse de manera totalmente local. Además, se trata de un sistema que facilita e integra el estudio y aprendizaje aprovechando Obsidian como editor y plataforma para gestionar notas.

Como uso secundario, este repositorio contiene todos los recursos PDF disponibles en el Campus de la UOC.

## Cómo utilizar esta herramienta
Haz un fork de este repositorio y empieza a trabajar en él, ya sea creando notas y apuntes para organizar tu estudio, o bien para consultar y modificar actividades, como simplemente para consultar los datos de las asignaturas o las fechas de entrega.

Cuando hayas realizado cambios, puedes subirlos a tu fork directamente desde Obsidian mediante el plugin obsidian-git. Presiona `CTRL+P` y escribe "push" u otro comando de Git.

Puedes tener este repositorio sincronizado con algún servicio de copias de seguridad, de forma que puedas acceder en otros dispositivos, o con la aplicación móvil de Obsidian.

## Recomendaciones
+ Instalar tipografías Iosevka, Iosevka Aile y Iosevka Etoile (https://github.com/be5invis/Iosevka/releases)
+ Advanced tables te permite crear tablas fácilmente; basta con escribir `| nombre_columna ` y pulsar `TAB` para crear una nueva columna, o `ENTER` para pasar a la fila siguiente.

## Tutorial

### Organización de las asignaturas
Cada asignatura tiene una carpeta con los siguientes apartados:

+ **Notas**: Carpeta donde irán tus notas/apuntes.
+ **Recursos**: Carpeta donde se encuentran los materiales de la asignatura.
+ **Actividades**: Tablero (kanban) donde encontrarás las actividades de la asignatura.
+ **Contenidos**: Nota que explica los contenidos de la asignatura, según el plan docente.
+ **Evaluación**: Nota que explica el sistema de evaluación, según el plan docente de la asignatura.
+ **Información**: Nota con información general sobre la asignatura, según el plan docente.

### Calendario
El calendario debe abrirse por defecto, también lo puedes encontrar en el panel izquierdo o abrirlo con CTRL+P -> Full Calendar. Es un calendario local que sólo contiene las fechas importantes de cada asignatura, basado en el calendario propio de la UOC.

### Actividades
Los tableros de actividades de cada asignatura pueden enlazar a una nota concreta en donde expandas la actividad en cuestión. También se puede enlazar a una nota-evento del calendario desde cualquier lugar.

### Workspace layouts
Puedes cambiar directamente al layout de una asignatura, o crear tus propios layouts, mediante el plugin Workspace Layouts. Lo encontrarás en el panel izquierdo o mediante CTRL+P -> Workspace layout.

### Otros plugins
En la configuración del programa puedes cambiar tanto los plugins propios de Obsidian como los de la comunidad para mejorar tu experiencia, quitar cosas innecesarias o buscar nuevas funcionalidades.

