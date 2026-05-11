## Descripción
- What does asm1(0x3fa) return? Submit the flag as a hexadecimal value (starting with '0x'). NOTE: Your submission for this question will NOT be in the normal flag format.
## Solución
- Para este reto lo que hice fue analizar el código en ensamblador línea por línea, identificando primero los valores que se comparaban con cmp  y los saltos condicionales (jg, jne).
- Convertí el valor de entrada 0x3fa a decimal para entender mejor el flujo.
- Luego seguí manualmente las ramas del programa hasta llegar a la instrucción final donde se modifica eax, luego al final  obtuve el resultado sumando  0x3fa + 0x15, ya que el flujo del programa lleva a esa operación sin desviaciones adicionales
## Notas 
- Este reto fue fácil pero a la vez me tardé bastante en poder descubrir como se hacia bien
## Referencias
