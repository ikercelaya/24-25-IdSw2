# Legibilidad

## Códigos

| Asignatura       | Enlace |
|------------------|--------|
| **Programación 1** | [Code1](https://github.com/ikercelaya/prg1-22-23/blob/main/retos/entregas/ikerCelaya/adivinaNumero.java) |
| **Programación 1** | [Code2](https://github.com/ikercelaya/prg1-22-23/blob/main/retos/entregas/ikerCelaya/retoCCCF/retoCCCF_Base.java) |
| **Programación 1** | [Code3](https://github.com/ikercelaya/prg1-22-23/blob/main/retos/entregas/ikerCelaya/whacAMole/whacAMole.java) |

## Errores

### Nombrado
- adivinaNumero debería ser AdivinaNumero (Usar PascalCase en nombres de clases) [Code 1](https://github.com/srgiom/prg1-22-23/blob/8136a23dc0fcb7b62ec2a82121447e97e24f9a83/retos/entregas/sergioMoreno/caracol/caracol_extendido.java#L1](https://github.com/ikercelaya/prg1-22-23/blob/7b3dcbe6d7f1396cd3ed2f04b7643144f4aa61b7/retos/entregas/ikerCelaya/adivinaNumero.java#L2))
- Nombrado poco descriptivo de las variables (r1, r2, r3, r4, r5, r6, r7) [Code 1](https://github.com/ikercelaya/prg1-22-23/blob/7b3dcbe6d7f1396cd3ed2f04b7643144f4aa61b7/retos/entregas/ikerCelaya/adivinaNumero.java#L6)

### Formato 
- En la línea nItems = (int) (cliente * (15 - 5) + 5);, el operador * y + deberían tener un espacio alrededor para mejorar la legibilidad. [Code 2](https://github.com/ikercelaya/prg1-22-23/blob/7b3dcbe6d7f1396cd3ed2f04b7643144f4aa61b7/retos/entregas/ikerCelaya/retoCCCF/retoCCCF_Base.java#L40)

### Comentarios 
- Comentarios innecesarios para las variables de las cajas [Code 2](https://github.com/ikercelaya/prg1-22-23/blob/7b3dcbe6d7f1396cd3ed2f04b7643144f4aa61b7/retos/entregas/ikerCelaya/retoCCCF/retoCCCF_Base.java#L26)

### Consistencia 
- horasLaborales, porcentajeLlegada, nCajas (Usan camelCase pero empiezan con minúscula, cuando las constantes en Java deben ir en mayúsculas separadas por _ [Code 2](https://github.com/ikercelaya/prg1-22-23/blob/7b3dcbe6d7f1396cd3ed2f04b7643144f4aa61b7/retos/entregas/ikerCelaya/retoCCCF/retoCCCF_Base.java#L20)

### Don’t Repeat Yourself (DRY)
- Código repetitivo en la asignación de cajas [Code 2](https://github.com/ikercelaya/prg1-22-23/blob/7b3dcbe6d7f1396cd3ed2f04b7643144f4aa61b7/retos/entregas/ikerCelaya/retoCCCF/retoCCCF_Base.java#L43)

### YAGNI (You Ain't Gonna Need It)
- Se define turno, pero podría eliminarse y usarse directamente en la condición del do-while [Code 3](https://github.com/ikercelaya/prg1-22-23/blob/7b3dcbe6d7f1396cd3ed2f04b7643144f4aa61b7/retos/entregas/ikerCelaya/whacAMole/whacAMole.java#L6)
