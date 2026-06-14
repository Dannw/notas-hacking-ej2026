## Descripción
- Welcome to the challenge! In this challenge, you will explore a web application and find an endpoint that exposes a file containing a hidden flag.

The application is a simple blog website where you can read articles about various topics, including an article about API Documentation. Your goal is to explore the application and find the endpoint that generates files holding the server’s memory, where a secret flag is hidden.

The website is running [picoCTF News](http://verbal-sleep.picoctf.net:62640/).
## Solución
- Para solucionar este reto lo que tuve que hacer fue entrar a la website, luego abrí el inspect y vi el código fuente de la pagina, entré buscando un archivo js en el que me diera más información de la pagina, supe que tenía que entrar a heapdump, después de entrar aquí me dió para descargar un archivo muy pesado, cuando lo abrí en la terminal eran una infinidad de datos, lo que hice fue hacerle un grep picocf para que me diera la bandera
## Notas
- fue muy complicado, más porque tuve que lidiar con un montón de datos de una pagina web

## Referencias
- 
