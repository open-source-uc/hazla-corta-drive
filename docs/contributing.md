# Como contribuir

Primero que nada, ¡gracias por tu motivación! 🥳

!!! attention "Requerimientos"
    Para aportar contenido directamente a la guía, debes primero
    tener una cuenta de [GitHub](https://github.com/signup)


## Como contribuir rápidamente en GitHub

### Editar una página existente

Arriba a la derecha de cada página, encontrarás un ícono con un lápiz.
Haz clic en este y edita los cambios en el archivo de Markdown.

Una vez que hayas terminado, añade un título al commit
y selecciona crear un fork (o una rama).

Deberás tener la opción de crear una Pull Request (PR), que es para
enviar la solucitud de cambios directamente.

!!! info "¿Tienes problemas con lo anterior?"
    No dudes en contactarnos a traves de Instagram
    o Telegram si tienes una duda


## Como contribuir localmente

Antes de todo, instala Git, Python y Poetry.

Crea un fork del repositorio:

=== "Usando la página de GitHub y Git"

    1. [Crea un fork del repositorio aquí](https://github.com/open-source-uc/hazla-corta-drive/fork)
    2. Clona el repositorio con:
        ```bash
        git clone <url>  # puedes obtener el url en la página del fork
        ```

=== "GH CLI"
    [Puedes instalar el CLI aquí](https://cli.github.com/)
    ```bash
    gh repo fork open-source-uc/hazla-corta-drive
    ```


```bash
# Entra al directorio del repositorio
cd hazla-corta-drive

# Luego, instala las dependencias con:
poetry install

# Además, instala los git hooks con
pre-commit install
```

Puedes correr el servidor de pruebas con:

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

La configuración del sitio vive en el archivo `mkdocs.yml`.
Puedes editar este archivo directamente, pero es necesario que pruebes
localmente para ver si los cambios se aplican correctamente.


### Crear una nueva página

Para crear una página, sube un archivo de markdown en la carpeta docs.
El path final en el URI será el path relativo desde docs.

Luego, deberás añadir el archivo a la configuración de navegación (`nav`)
en `mkdocs.yml`, añadiendo como llave el nombre de la parte y como valor el path.
