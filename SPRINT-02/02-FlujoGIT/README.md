<img src="/images/1.png" width="250">

# Flujo de Trabajo en GIT

 GIT es un sistema de control de versiones, en otras palabras es un registrador de cambios de archivos.


---
#### Fase 0: Seguimiento de Archivos

- Untracked: Archivo original que no tiene ningún Seguimiento.

- Tracked: Archivos que tienen un registro de cambios.

---

#### Fase 1: Working Directory( Modificado )

  > En esta fase creamos o modificamos nuestros archivos pero sin comprometer nuestro repositorio. Tenemos nuestros archivos listos para trackea. Ejecutamos el comando git status, nos mostrará qué archivos han sido modificados (o creados).

 ~~~
 $ git status
 ~~~

<img src="/images/5.png" width="600">

> Una vez que hemos hecho los cambios necesarios, registramos los cambios hechos,usando:
~~~
$ git add .
~~~

 >Si queremos un archivo en especifico, usamos :
~~~
$ git add <nombredelarchivo>
~~~  

<img src="/images/6.png" width="600" >

>Como ves, usé git status para verificar el estado de mis archivos.

---

#### Fase 2: Staging Area ( Preparado )


---
#### Fase 3: "Git Repository". (Confirmado)

> Aquí es donde confirmamos el guardado de nuestros cambios, con un comentario para identificarlo en nuestra línea del tiempo o el historial de cambios en el repositorio. Para subir o enviar nuestros cambios,usamos:

~~~
$ git push origin <rama>
~~~  
<img src="/images/7.png" width="600">

---

>En resumen, primero hacemos cambios, siguiente los registramos y los subimos al repositorio a esto se le llama flujo de trabajo en git .
<img src="/images/flow.png" width="600">
