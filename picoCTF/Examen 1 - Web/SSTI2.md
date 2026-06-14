## Descripción
- I made a cool website where you can announce whatever you want! I read about input sanitization, so now I remove any kind of characters that could be a problem :)
## Solución
- Para solucionar este reto lo primeri que hice fue ver que era vulnerable a SSTI en Jinja2 luego de ver y confirmar la inyección de plantillas, aproveche funciones internas de Python para acceder al sistema y obtener la bandera y así también ir probando varias payloads que fui probando en una pagina de onsecurity que me fue ayudando a lograr entrar poco a poco

## Notas
- Lo pude conseguir pero con muchos muchos intentos la verdad me fue muuuy lento este no lo podía lograr

## Referencias
- https://onsecurity.io/article/server-side-template-injection-with-jinja2/
