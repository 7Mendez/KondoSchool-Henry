# Flujo de Trabajo en GIT

 Los archivos pueden ser TRACKED o UNTRACKED, esto es
 que llevan un registro de los cambios o no.

 Si son registrados se guardan en un repositorio,en este caso usamos GIT.

![](1.png)
#### Fase 1: “Working Directory”. ( Modificado )

  En esta fase, es donde podemos crear, eliminar y cambiar lo que deseemos.

  Ejemplo:
  Supongamos que tenemos listos nuestros archivos
  listos para registrarlos.

 ~~~
 $ git status
 ~~~
  Nos dirá los registros que se han hecho.

  imagen---

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





#### Fase 2: “Staging Area”. ( Preparado )

- Fase 3: "Git Repository". (Confirmado)
