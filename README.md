# Codigo 13

## Comando para GIT

```
git init 
```
- Este comando sole se hace al inicio
- Sirve para inicializar nuestro proyecto con GIT
- :eye: crea una :file_folder: carpeta oculta llamada .git

```
git status 
```
- Poder listar y ver si los archivos estan listos para subir
-  caso de que los archivos no esten listos se veran de color rojo y cuando lo esten seran de color verde

```
git add .
fit add nombre_de_archivo
```
- Se encarga de agregar los archivos a la memoria de GIT, es decir los guarda en un stash

```
git commit -m "comentario"
```
- Crea un punto en la linea de tiempo de nuestros cambios y a estos se le es posible adjuntar un comentario
- :eye: Los comentarios deben estar relacionados a los cambios realizados, esto es una recomendacion

```
git push origin main
```
- Sirve para poder subir los cambios a nuestro repositorio en la nube, en este caso GITHUB

```
git pull origin main
```
- Sirve para poder descargar los cambios de nuestro repositorio en la nube, en este caso GITHUB

```
git clone url
```
- Sirve para crea por default una carpeta con el nombre del repositorio si la reposicion es publica.

```
git branch
```
- Sirve para listar los branch que tengo localmente y me dice en cual me encuentro actualmente

```
git checkout -b nombre_del_branch
```
- Sirve para crea un nuevo branch

```
git checkout nombre_del_branch
```
- Sirve para moverse entre branch
- :eye:  Si el checkout no tiene el -b solamente es para moverse entre ramas

