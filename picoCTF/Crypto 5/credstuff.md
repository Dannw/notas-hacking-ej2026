## Descripción
- We found a leak of a blackmarket website's login credentials. Can you find the password of the user `cultiris` and successfully decrypt it?

Download the leak [here](https://artifacts.picoctf.net/c/151/leak.tar).

The first user in `usernames.txt` corresponds to the first password in `passwords.txt`. The second user corresponds to the second password, and so on.

## Solución
- La solución de este reto fue que cuando se encuentre la clave en el archivo password, lo que se tiene que hacer es usar el rot 13 y nos da la bandera

## Notas
- Me gustó, no estuvo tan difícil la verdad 

## Referencias
