# Curso básico git

## Iniciar repositorio: El comando init inicializa el repositorio  creando una carpeta oculta 'git'

```
$ git init
```

## Agregar archivos: Se utiliza el comando add para agregar archivos al repositorio.

``` shell 
$ git add <archivo>

$ git .
``` 

## Agregar cambios: Se utiliza el comando commit.

```
$ git commit -m "comentario"
```

## Borrar repositorio local
``` shell
$ rm -rf .git
```  

## Configurar repositorio remoto

```
git remote add origin <url>

## Aplicar cambios

```
git push -u origin main
```

## Creación de ramas

```
git brach -M [nombre]

```

## Log de cambios

## Comando dff