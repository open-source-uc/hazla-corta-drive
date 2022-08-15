# Como contribuir

!!! danger "¡Todavía no esta completo!"


Primero que nada, ¡gracias por tu motivación!

## Aportar directamente

Para aportar contenido directamente a la guía,
debes primero tener una cuenta de GitHub.

### Como contribuir rápidamente

#### Editar una página existente

Arriba a la derecha de cada página, encontrarás un ícono con un lápiz.
Haz clic en este y edita loc cambios en el archivo de Markdown.
Una vez que hayas terminado, añade un título al commit
y selecciona crear nueva rama.

#### Crear una nueva página


### Como contribuir localmente

Antes de todo, instala Git, Python y Poetry.

Clona el repositorio con:

TODO

Luego, instala las dependencias con:

```sh
poetry install
# Y entra
```

Además, instala los git hooks con:

```sh
pre-commit install
```

Ahora, puedes correr el servidor de pruebas con:

```sh
mkdocs serve
```

Para subir los cambios, crea una rama nueva y sube los cambios con:

```sh
git switch -c <nombre-de-la-rama>
git add .
git commit -m "<mensaje>"
git push origin <nombre-de-la-rama>
```

## Cambiar la configuración del sitio

TODO
