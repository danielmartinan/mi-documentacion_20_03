# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## Comandos necesarios para instalar MkDocs

```bash

# Crear la carpeta de trabajo
mkdir mi-documentacion_v2

# Ingresar a la carpeta de trabajo
cd mi-documentacion_v2

# Crear el entorno virtual
python -m venv venv

# Activar el entorno virtual
venv\Scripts\activate

# Instalar MkDocs
pip install mkdocs mkdocs-material

# Crear la documentación
mkdocs new .

# Iniciar el servidor
mkdocs serve

# Compilar la documentación
mkdocs build

# Desplegar la documentación
mkdocs gh-deploy
```
