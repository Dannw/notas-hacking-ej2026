## Descripción
- What does asm2(0xc,0x1d) return? Submit the flag as a hexadecimal value (starting with '0x'). NOTE: Your submission for this question will NOT be in the normal flag format.
## Solución
Para resolver este reto descargué el archivo source y lo analicé en una herramienta de ensamblador online.
Identifiqué que los parámetros se almacenan en variables locales dentro del stack.
Después observé un loop donde dos variables se incrementan en cada iteración: una en +1 y otra en +0xe4.
luego sque cuántas veces se ejecuta el ciclo hasta que la condición deja de cumplirse (cmp contra 0xf5cf).
Con ese número de iteraciones calculé el valor final de eax, que es el valor de retorno.
## Notas
- Este reto fue uno de los que mas se complicó hacer de los tres pero a la vez es entretenido aprender a hacer nuevas cosas y lograr nuevos retos!
## Referencias
