# Como contribuir

Primero que nada, ¡gracias por tu motivación!

## Aportar diretamente

Para aportar contenido directamente a la guia, debes primero
tener una cuenta de GitHub.

### Como contribuir rápidamente

TODO

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
