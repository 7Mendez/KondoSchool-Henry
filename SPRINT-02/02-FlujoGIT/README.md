<img src="/images/1.png" width="250">

# Flujo de Trabajo en GIT

 GIT es un sistema de control de versiones, en otras palabras es un registrador de cambios de directorios y archivos.


---
#### Fase 0: Seguimiento de Archivos

- Untracked: Archivo original que no tiene ningún Seguimiento.

- Tracked: Archivos que tienen un registro de cambios.


#### Fase 1: Working Directory( Modificado )

  > En esta fase, es donde podemos crear, eliminar y cambiar los archivos que deseemos. Tenemos nuestros archivos listos para trackear.

<img src="/images/4.png" width="350">

  > Para ver los cambios realizados en nuestro repositorio, usamos:
 ~~~
 $ git status
 ~~~

<img src="/images/5.png" width="350">



#### Fase 2: Staging Area ( Preparado )

> Para registrar los cambios hechos, usamos:
~~~
$ git add .
~~~
<img src="/images/6.png" width="350">

 >Si queremos un archivo en especifico, entonces :
~~~
$ git add <nombredelarchivo>
~~~  


>Como ves, use git status para verificar el estado de mis archivos.

- Fase 3: "Git Repository". (Confirmado)


Dependiendo el branch que deseemos usar, yo usaré develop.

~~~
$ git push origin <rama>
~~~  
