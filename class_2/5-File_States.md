#### Estado de nuestros archivos

_tldr (too long; didn't read): comando para ver que hace un comando en linux, es mucho más util que el man. (Hay que instalarlo)_

Tenemos 3 estados posibles de nuestros archivos:

1. Working Tree
2. Staging
3. Remote

Si creamos un archivo nuevo, no está en track por git, está en el "working tree" por lo que utilizamos
el comando `git add file_name` para que se agregue al "staging area".

Desde el momento que un archivo esta trackeado por git, podemos utilizar todos los comandos que tiene disponibles.
