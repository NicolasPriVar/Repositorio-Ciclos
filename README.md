# Repositorio de Pruebas en Git

## Integrantes:
- **Juan Cancelado** - Colaborador
- **Nicolás Prieto** - Owner

Se agregó esta línea.

## Preguntas

### 1. ¿Para qué sirve y cómo se usan estos comandos `git add` y `git commit -m “mensaje”`?

- `git add` se usa para incluir los cambios de los archivos en el siguiente commit.
- `git commit -m "mensaje"` se usa para guardar los cambios en el repositorio con un mensaje personalizado.

### 2. ¿Qué sucede si Owner y Colaborador editan el archivo `README.md` al mismo tiempo e intentan subir los cambios al mismo tiempo?

En este punto, al tratar de hacer cambios al mismo tiempo y guardarlos, se generó un conflicto, dado que ambos intentaban subir cambios al mismo archivo sin tener en cuenta los cambios que había hecho el otro.

### 3. ¿Hay una mejor forma de trabajar con Git para no tener conflictos?

Sí, mediante las ramas (branches) que nos permiten modificar el mismo archivo, subirlo, y que la aplicación mezcle los cambios sin generar conflictos.

### 4. ¿Qué es y cómo funciona el Pull Request?

El Pull Request es una característica usada para proponer cambios en algún archivo. Esto se usa generalmente cuando se trabaja en grupos de desarrolladores. Además, se indica a los demás desarrolladores que se hicieron cambios, los cuales pueden ser revisados, comentados y fusionados en la rama principal (main o master).

Para usarlo, primero se debe crear una rama en la que se van a hacer los cambios para no afectar la rama principal directamente. Luego, se hacen los cambios y se hace un push, lo cual genera el pull request. En este momento, se deben revisar los cambios y, de ser aprobados, se fusionan con un merge en la rama principal. Finalmente, se cierra el pull request.
