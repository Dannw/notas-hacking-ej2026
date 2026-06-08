## Descripción
- In RSA, a small e value can be problematic, but what about N? Can you decrypt this?

[values](https://challenge-files.picoctf.net/c_wily_courier/8f75844947ccdb93020eecaf5eea8be97753b2075202328032bb4854ca7c6863/values)

## Solución
- Para solucionar este reto utilicé el texto que me dió el profe para poder descifrar los retos, como el modulo RSA n era muy pequeño, pudo factorizarme para obtener los números primos p y q, con esto se pudo calcular, luego finalmente se pudo descifrar el ciphertext usando la operación RSA estándar, el mensaje que se recuperó apareció invertido y esa era la flag

## Notas
- Estos retos si se me hacen más complicados, son muchos numeros y se hacen complicados pero a la vez esta bien :)
## Referencias
