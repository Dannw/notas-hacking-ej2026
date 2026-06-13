## Descripción
- Can you abuse the banner?

The server has been leaking some crucial information on `tethys.picoctf.net 59284`. Use the leaked information to get to the server.

To connect to the running application use `nc tethys.picoctf.net 63827`. From the above information abuse the machine and find the flag in the /root directory.

## Solución
- Para completar este reto del examen lo que tuve que hacer fue entrar al primer puerto y ahí me dió la contraseña, después de eso lo que hice fue responder varias preguntas hasta que puse todas correctas, despues tuve que hacer un ls -l para ver el archivo banner, ese lo borré y lo remplacé, cuando lo remplacé lo que hice fue salir e ingresar de nuevo al servidor y así me dió la bandera en la parte de arriba

## Notas
- estuvo interesante entrar a los archivos y modificarlos para que me diera la bandera que buscaba

## Referencias
