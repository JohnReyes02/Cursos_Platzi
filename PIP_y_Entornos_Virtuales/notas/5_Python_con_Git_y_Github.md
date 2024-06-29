# Python con Git y Github

## Fecha

**Fecha de la lección:** 2024-06-29

## Objetivo de la lección

- [x] Unir el proyecto dentro de un repositorio de Github y hacer seguimiento

## Creacion de Repositorio en Github

1. Ir a [github.com](https://github.com/), crear una cuenta y loguearse.
2. Crear un nuevo repositorio.
3. Seleccionar las opciones que se requieran para el repositorio (Publico, privado)
4. Dar click en crear repositorio

## Enlace con el proyecto

1. Estando en la terminal enlazamos el proyecto:

```bash
git init
```

2. Copiar el enlace que nos da GitHub para enlazar el repositorio:

```bash
git remote add origin git@github.com:JohnReyes02/curso-python-pip.git
```

3. Verificamos el enlace:

```bash
git remote -v
```

4. Agregamos los cambios que hayamos hecho:

```bash
git add *
```

5. Hacemos un commit:

```bash
git commit -m "Mi primer archivo"
```

5. Subimos los archivos al repositorio desde la linea de comandos:

```bash
git push origin main
```

## Agregar el archivo .gitignore

1. Encontrar el archivo .gitignore aduacuado para el lenguaje de programacion utilizado:

- En el enlace a la pagina [https://www.toptal.com/developers/gitignore](https://www.toptal.com/developers/gitignore) se puede realizar la busqueda.

2. Se realiza la busqueda por sistema operativo y lenguaje de programacion:

- Windows
- Linux
- macOS
- Python

3. Con los anteriores parametros seleccionados, se crea el archivo .gitignore
4. Se copia el archivo generado
5. Dentro de la carpeta del proyecto se crea el archivo .gitignore
6. Pegamos el contenido del archivo generado

## Agregar el archivo README

1. Dentro de la carpeta del proyecto creamos el archivo README.md
2. Se escriben las instrucciones para ejecutar el proyecto.

# Actualizacion del repositorio

1. Se aprueban los cambios realizados

```bash
git add *
```

2. Realiza el commit:

```bash
git commit -m "add files"
```

3. Subimos los cambios al repositorio:

```bash
git push origin main
```

Con todo lo anterior tenemos enlazado nuestro proyecto en GitHub

## Archivos de clase

-

## Lecturas recomendadas

-
