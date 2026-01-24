# Práctica 1 - Git
### Programación de Aplicaciones Telemáticas - 3ºB GITT-BA
#### José Manuel Fernández Freige

En este documento se exponen los pasos seguidos para la realización de la primera práctica de la asignatura así como la preparación del entorno de trabajo en el equipo personal.

## Git y GitHub
Para comenzar la práctica se demuestra el conocimiento de Git y sus **comandos básicos**.

Para ello, se hace un **"fork"** del repositorio aportado en el enunciado de la práctica (https://github.com/gitt-3-pat/p1) y se prueban sobre él los comandos básicos:
* git clone
* git status
* git add
* git commit
* git push
* git checkout

### Git clone: 
Sirve para clonar un repositorio del cual se pasa su URL por parámetro. Clonar quiere decir hacer una copia del repositorio remoto al ordenador local o el codespace en el que se está trabajando. 
Realizando el "fork" se está obteniendo una copia en la nube del repositorio "gitt-3-pat/p1" y sobre el que se pueden realizar cambios. Al abrir un codespace para probar los comandos git, Github crea una copia en local sobre la que se podrá trabajar en el repositorio. Esta copia es equivalente a lo que se logra mediante el comando **git clone**.

Por tanto, para pode probar el comando se realiza el clonado del repositorio en un directorio temporal al que se accede mediante el comando `cd /tmp`.
Dentro de este directorio se ejecuta el comando indicado:
`git clone https://github.com/jmfernandezfreige/p1`.

**Log tras la ejecución**:
```bash
Cloning into 'p1'...
remote: Enumerating objects: 26, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (10/10), done.
remote: Total 26 (delta 2), reused 0 (delta 0), pack-reused 16 (from 2)
Receiving objects: 100% (26/26), 125.40 KiB | 41.80 MiB/s, done.
Resolving deltas: 100% (2/2), done.```

### Git status:
Sirve para comprobar el estado de la rama actual dentro del repositorio. Git status da tres tipos de información:
* La rama actual
* Cómo de sincronizado está con la copia del repositorio remoto: "X" commits por delante o por detrás.
* Estado de los archivos y cambios: pueden ser nuevos y no añadidos a git (Untracked), modificados sin confirmación (Modified), preparados para confirmar (staged).

**Log ejemplo**:
> On branch main

> Your branch is up to date with 'origin/main'.

> nothing to commit, working tree clean


### Git add:
**Log ejemplo**:

### git commit: 
Sirve para confirmar un conjunto de cambios que ya se han preparado y añadido a la rama de Staging.
**Log ejemplo**:

### git push:
Sirve para subir los cambios confirmados por commits al repositorio remoto.
**Log ejemplo**:

#### git checkout: 
Permite el cambio entre ramas para moverse de espacio de trabajo. Además, permite moverse a una rama nueva, creándola y posteriormente situándose en ella ('git checkout -b nueva_rama').
**Log ejemplo**:

## Entorno de desarrollo Java
Se deben instalar en el equipo Java 17 (o posterior), Maven, editor de código fuente (IntelliJ + VSCode). A continuación se muestra la evidencia de tener los distintos programas instalados en el equipo.

#### Java: 
![Prueba de la versión "23.0.1" de Java en el equipo personal](assets/images/version_java.png)

#### Maven:
![Prueba de la versión "23.0.1" de Java en el equipo personal](assets/images/maven_version.png)

#### VSCode
![Prueba de la versión "23.0.1" de Java en el equipo personal](assets/images/vscode_version.png)

#### IntelliJ
![Prueba de la versión "23.0.1" de Java en el equipo personal](assets/images/intelliJ_version.png)
