# Efecto de reloj digital

## Resumen

Con un controlador deslizante vamos a mostrar un reloj digital que avance hasta la hora que se marque.

## Instrucciones

1. Añadir un texto.

2. Añadir un control deslizante.

3. Añadir una expresion a la fuente de texto.
  1. Crear una variable, `slider` y ligarla al efecto deslizante.
  2. Crear una función para dar el formato de la hora.
`function fnCero(n){
  if(n<10) return "0" + n else return n;
  }`
  3. Para calcular los segundos usamos modular: `seg = slider%60;`
  4. Calculamos los minutos y los redondeamos al hacía abajo: `min = Math.floor(slider/60);`
  5. Mostramos la hora: `fnCero(min) + ":" + fnCero(seg)`

## Con animación
Para animar el recuerda redondear el numero del controlador deslizante antes de obtener los segundos y minutos.
`tiempo = Math.floor(slider);`

## Referencias
[Tutorial](https://www.youtube.com/watch?v=14N1JQr5RrU)
