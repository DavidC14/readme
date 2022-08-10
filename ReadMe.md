# Introduccion a Git y Markdown

## Comandos del día

```bash
git init
git status
# creamos un archivo nuevo y después
git add .
# hasta acá NO se guardaron los cambios, para hacerlo tengo que crear un commit
git commit -m "IMPORTANTE: acá va la descripción del commit"

# hicimos algún commit más y revisamos el historial de commits
```
## Markdown y README.md

## Markdown
Markdown es una tecnologia que permite escribir texto con un formato especial y nos permite por ejemplo crear archivos de text que pueden tener titulos, codigos e imagenes (similar a HTML pero sin etiquetas)

### README.md
El archivo README.md es un archivo de Markdown (extension .md) y ese archivo es la portada de nuestro repositorio en Github.

## Gitignore
Si creamos un archivo llamado `.gitignore ` podemos avisarle a git que archivos queremos ignorar.
Dentro del archivo .gitignore podemos tener algo como eso:

```bash
contraseñas.txt
*.pdf #con esta instruccion le indico que ignore todos los archivos con extension pdf
```