<img src="/images/1.png" width="250">

# Flujo de Trabajo en GIT

 GIT es un sistema de control de versiones, en otras palabras es un registrador de cambios de directorios y archivos.


---
#### Fase 0: Seguimiento de Archivos

- Untracked: Archivo original el no tiene ningún Seguimiento.

- Tracked: Archivos que tienen un registro de cambios.


#### Fase 1: Working Directory( Modificado )

  Aquí, es donde podemos crear, eliminar y cambiar los archivos que deseemos.

  >Tenemos nuestros archivos listos para trackear.
  ><img src="/images/4.png" width="350">

 ~~~
 $ git status
 ~~~

  > Nos dirá los registros que se han hecho.
  <img src="/images/5.png" width="350">



  para confirmar registrar nuestros archivos usamos:
  ~~~
  $ git add .
  ~~~

  Si queremos un archivo en especifico, entonces :
  ~~~
  $ git add <nombredelarchivo>
  ~~~  

  Dependiendo el branch que deseemos usar, yo usaré develop.

  ~~~
  $ git push origin <rama>
  ~~~  





#### Fase 2: Staging Area ( Preparado )

- Fase 3: "Git Repository". (Confirmado)
