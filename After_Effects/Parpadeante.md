# Efecto Parpadeante

## Resumen
Usaremos una variable y la opacidad para mostrar o no una capa.

## Instrucciones

1. Añadir en una capa lo que va a parpaderar.

2. Añadir una capa de ajustes.

3. Añadir el efecto de (efecto -> control de expresiones) control desliante. Con este controlaremos la cantidad de veces que parpadea en el tiempo que dura.

4. Añadiremos una Expresion a opacidad.

5. Crearemos una nueva variable: `blinkingSpeed = ` y la ligaremos al efecto de control, usando la aspiral junto al símbolo de `=`.

6. Agregamos la siguiente línea `n=Math.sin(time*blinkingSpeed);`

7. Finalmente añadimos: `if(n<0) 0 else 100;`

## Referencias
[Fuente](https://www.youtube.com/watch?v=Gfgv59JqDDI&t=8s)
