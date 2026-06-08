## Descripción
- How about we take you on an adventure on exploring certificate signing requests

Take a look at this CSR file [here](https://artifacts.picoctf.net/c/420/readmycert.csr).

## Solución
- La solución de este reto consistió en en descargar el archivo csr que venia en el reto, que es un certificado, no fue necesario que tuviera que decodificarlo, ya que al momento de aplicar un **openssl req -in readmycert.csr -text -noout** me dió toda la información más aparte me dió la bandera directamente

## Notas
- Fue muy fácil, no tuve tantas complicaciones con un solo comando se me facilitó sacar la bandera

## Referencias
