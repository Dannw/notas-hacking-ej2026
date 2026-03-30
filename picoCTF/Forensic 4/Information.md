## Descripción
- Files can always be changed in a secret way. Can you find the flag?
## Solución
- Lo que hice fue descargar la imagen con wget en mi kali linux, luego de esto utilicé exiftool para abrir la imagen y ver todos sus metadatos, tome el texto que venía en "license" y lo mande a cyberchef y ahí me dio la llave
## Notas
Es interesante como en las imagenes se encuentran textos ocultos
## Referencias
- https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true,false)&input=Y0dsamIwTlVSbnQwYUdWZmJUTjBZV1JoZEdGZk1YTmZiVzlrYVdacFpXUjk