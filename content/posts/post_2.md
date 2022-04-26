---

title: "Github"

date: 2022-04-25

description: 'Error 403 al querer subir cambios a github y su posible solución'

---


## 🚀
## En el siguiente pequeño tutorial se hace mencion de como solucionar este error que al parecer es debido a permisos de la personal acces token.



Como sabemos la plataforma de github sigue creciendo y ha dejado de usar la contraseña de usuario de github como forma 

de autentificación a la hora subir los archivos versionados a un repositorio. Por lo que github recomienda crear una PAT(Personal Acces Token)



El primer paso es seleccionar Settings de la parte superior derecha de la pagina de github donde nos muestra unas opciones para nuestro perfil

(para esto debemos estar en nuestra cuenta o en su defecto crear una cuenta).

![developer settings](https://user-images.githubusercontent.com/99101501/165196995-658364c3-0ac5-454c-8eb7-00d267c36039.png)


Despues en la parte inferior izquierda damos click en la opción Developer Settings



Nos apareceran 3 opciones elegimos la opcion Personal Acces tokens, damos click en generate new token

![developersegttings2](https://user-images.githubusercontent.com/99101501/165197029-750a9738-24cf-4e8f-8a65-56e1d487dc85.png)


## IMPORTANTE Guarda el Token que se genera y tenlo a la mano ya que con este se haran los accesos a github desde el local y este token una vez generado se oculta
😌 Aunque puedes crear otro que sustituira al actual.



Y por ultimo en select scopes define su acceso esto tambien es importante ya que gracias a esto se pueden realizar o no distintas tareas desde hacer cambioso osubir cambios entre otros.

![laststep](https://user-images.githubusercontent.com/99101501/165197090-b9306283-e48b-4fca-9e22-7d4c1479c72e.png)


: Una vez que realizes un commit en local y quieras subir los cambios con "git push -u origin master" dentro de la opcion de password copia y pega el token generado y si todo va bien podras ver los cambios reflejados en github.
