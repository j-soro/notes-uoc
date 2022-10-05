# Notes UOC
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

## Plugins core de Obsidian
```json
[
  "file-explorer",
  "global-search",
  "switcher",
  "graph",
  "backlink",
  "outgoing-link",
  "tag-pane",
  "page-preview",
  "daily-notes",
  "templates",
  "note-composer",
  "command-palette",
  "editor-status",
  "markdown-importer",
  "word-count",
  "workspaces",
  "file-recovery"
]
```

## Plugins de la comunidad
```json
[
  "cm-editor-syntax-highlight-obsidian",
  "obsidian-linter",
  "note-refactor-obsidian",
  "obsidian-outliner",
  "url-into-selection",
  "obsidian-reading-time",
  "recent-files-obsidian",
  "obsidian-emoji-toolbar",
  "code-block-copy",
  "obsidian-git",
  "obsidian-style-settings",
  "table-editor-obsidian",
  "obsidian-kanban",
  "calendar",
  "obsidian-spaced-repetition",
  "sliding-panes-obsidian",
  "obsidian-hider",
  "periodic-notes",
  "obsidian-icon-folder",
  "cmenu-plugin",
  "folder-note-plugin",
  "oz-image-plugin"
]
```