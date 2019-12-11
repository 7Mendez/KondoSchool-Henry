<img src="/images/1.png" width="350">

# Flujo de Trabajo en GIT

 GIT es un sistema de control de versiones, en otras palabras es un registrador de cambios de directorios y archivos.


---
#### Fase 0: Seguimiento de Archivos
 Antes que nada ten en cuenta esto, los archivos:

- Tracked: Es Registrar cambios que los archivo tengan.

- Untracked: Es cuando el archivo no tienes que llevar un registro de cambios.

#### Fase 1: Working Directory( Modificado )

  Aquí, es donde podemos crear, eliminar y cambiar los archivos que deseemos.

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
