## Descripción
 - In the last challenge, you mastered octal (base 8), decimal (base 10), and hexadecimal (base 16) numbers, but this vault door uses a different change of base as well as URL encoding!

	The source code for this vault is here: [VaultDoor5.java](https://challenge-files.picoctf.net/c_fickle_tempest/a8fa4d19d7d2445ee8152987624b46c1ff4eeeab9319ab48c513f66f5b903ef8/VaultDoor5.java)

## Solución
- La solución de este reto fue decodificar Base64 al string, luego cada %xx es un HEX y así seguimos el proceso hasta que nos da la bandera
## Notas
- Este si se me complicó un poco más ya que no soy muy bueno reconociendo los distintos tipos de sistemas de codificación
## Referencias
