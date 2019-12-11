# Flujo de Trabajo en GIT

 GIT es un sistema de control de versiones, en otras palabras es un registrador de cambios de directorios y archivos.

<img src="/images/1.png" width="300">


#### Fase 0: TRACKED y UNTRACKED
 TRACKED : Es Registrar cambios que los archivo y directorio hagan.

 UNTRACKED: Es cuando el archivo o directorio no tienes que llevar un registro de los cambios.

![]()
#### Fase 1: Working Directory( Modificado )

  En esta fase, es donde podemos crear, eliminar y cambiar lo que deseemos.

  Ejemplo:
  Supongamos que tenemos listos nuestros archivos
  listos para registrarlos.

 ~~~
 $ git status
 ~~~
  Nos dirá los registros que se han hecho.



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
