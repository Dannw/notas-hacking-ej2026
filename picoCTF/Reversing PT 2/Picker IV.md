## Descripción
- Can you figure out how this program works to get the flag?

Connect to the program with netcat:

`$ nc saturn.picoctf.net 63559`

The program's source code can be downloaded [here](https://artifacts.picoctf.net/c/528/picker-IV.c). The binary can be downloaded [here](https://artifacts.picoctf.net/c/528/picker-IV).
## Solución
- Lo que hice aquí fue descargar el archivo pickle y lo mande a una pagina llamada dogbolt.org, luego de esto entré a la sección de hex-rays y tomé los numeros 40129E y los puse en el servidor y me dió la bandera
## Notas
- Fue verdaderamente muy fácil 
## Referencias
- https://dogbolt.org/?id=547a0af6-2d2f-4986-9199-14045ab5a2fd#Hex-Rays=229
