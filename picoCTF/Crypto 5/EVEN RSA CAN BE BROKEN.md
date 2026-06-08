## Descripción
- This service provides you an encrypted flag. Can you decrypt it with just N & e?

Connect to the program with netcat:

`$ nc verbal-sleep.picoctf.net 63734`

The program's source code can be downloaded [here](https://challenge-files.picoctf.net/c_verbal_sleep/c798cbe85b3e431345406f393827b9b905481b5fcd6d4b4a845527ee0602da9b/encrypt.py).

## Solución
- La solución de este reto consistió en que como el reto generaba un modulo RSA usando dos numeros primos, pero uno de ellos era 2, pues el modulo resultó ser un numero par y se pudo factorizar, así me pudo dar el valor de φ(N) y se calculó la clave privada d y así al final se descifró el ciphertext

## Notas
- El reto decía que era fácil pero a mí se me hizo difícil la vdd

## Referencias
