## Descripción
- We found this weird message being passed around on the servers, we think we have a working decryption scheme.

Download the message [here](https://artifacts.picoctf.net/c/127/message.txt).

Take each number mod 37 and map it to the following character set: 0-25 is the alphabet (uppercase), 26-35 are the decimal digits, and 36 is an underscore.

Wrap your decrypted message in the picoCTF flag format (i.e. `picoCTF{decrypted_message}`

## Solución
- Lo que hice aqui fue descargar el texto que venia y era una serie de números, se resolvió tomando cada número módulo 37 y luego de esto se va convirtiendo el resultado usando una tabla así: 
  0-25 -> A-Z  
	26-35 -> 0-9  
	36 -> _

## Notas
- Estuvo entretenido pensé que iba a hacer un reto un poco más difícil pero no fue así

## Referencias