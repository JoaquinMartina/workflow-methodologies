#### Instalación

- https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

#### Configuración Básica
Cuenta global de mi usuario para que en el historico de cada proyecto figure a mis datos:

- git config --global user.name "Mati Beltramone"
- git config --global user.email "mbeltramone@rooftop.dev"

Esta configuración aplica como bien dice el flag, a todos los proyectos que esten en la usuario de la computadora que estoy utilizando y esta instalado git.

Configuración de mi usuario realizada: `$ head -n 3 ~/.gitconfig`

```
[user]
name = Matias Beltramone
email = mgbeltramone@gmail.com
```

#### Configuración de un repositorio en nuestro local

Creamos una carpeta: `$ mkdir methodologies-workflow`

Inicializamos una carpeta con git para que quede versionada: `$ git init`

Visualizamos que paso sobre esa carpeta: `$ ls -la`, se creo una carpeta `.git` ( por lo que esta instalado git como versionador de nuestra carpeta)

#### Clonando Repositorios
Mostrar ejemplo de clonar un repositorio que ya exista, como es nuestro caso con todos los cursos que se darán.

`git clone git@github.com:matiasbeltramone/git-tests.git`
