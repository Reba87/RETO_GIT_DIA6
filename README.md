## Pasos a seguir para subir al Git.
1. Podemos crear una carpeta desde el Git Bash o indicar la ruta de la carpeta de nuestro proyecto para que asi
   se cree el repositorio.
2. Creamos un repositorio en nuestra carpeta, esto lo hacemos escribiendo GIT INIT en el Git bash
3. Para enlazar nuestro proyecto con el Git Hub, debemos creanos un nuevo repositorio en nuestra cuenta
   de Git Hub, en este caso utilice el mismo nombre
   de mi carpeta local.
4. Copiamos y pegamos en el Git Bash las indicaciones que nos da Git Hub.
5. Ya con esto tenemos enlazado nuestro repositorio local con el remoto.
4. Creo mi archivo Readme.md
6. Realizamos un Git Status para verificar si falta algun archivo por subir.
6. En mi caso aun no he subido a mi repositorio local los archivos package.json y el readme.md
7. Con GIT ADD vamos subiendo nuestros archivos al local. 
8. Hacemos un git status para ver en que punto estamos.
9. Luego de finalizar las modificaciones a nuestros archivos, realizamos un Git add, luego un Git commit
   y por ultimo un Git Push para subir todo a nuestro repositorio remoto.
___

## Explicacion .Gitignore
  1. Me he creado mi fichero .gitignore
  2. Me salta un mensaje al realizar mi git status donde me aparece mi archvio Readme y abajo de este
  un mensaje que nos indica que todos los arhivos dentro de ese fichero seran ignorados
___
## Explicacion ramas y fusionar (Merge)
   Me he creado dos ramas primero pero no tenia el archivo de mis funciones dentro por lo que no me las ha copiado,
   me he creado dos ramas mas apartes para el ejercicio (Rama 3 y Rama4), desde Rama3 he eliminado mi funcion de suma y
   lo he guardado y creado mi nueva rama en el Git Hub, luego de esto me he ido a la Rama4 para modificar la funcion
   suma para añadir otro parametro, he realizado lo mismo que antes he guardado y creaado mi nueva rama.

   Para realizar el merge de mis archivos me he ido a mi rama principal (MAIN), y desde alli he realizado un status y un branch para
   asegurarme de que estaba todo correcto y estaba en la rama principal, he realizado mi Git Merge y he visto como se realizaba el cambio
   en mi archivo del main, luego he realizado un push y listo todo subido al Git hub.

   
   ---
 ## NOTA IMPORTANTE: AL REALIZAR EL GIT COMMIT SIEMPRE DEBEMOS COLOCAR GIT COMMIT -M "NOMBRE ARCHIVO", DE LO CONTRARIO DARA ERROR