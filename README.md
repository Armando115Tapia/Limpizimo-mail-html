### Descripción
Este es un proyecto creado por Carlos Mora (OptimusSocial)
<br>
Este proyecto nació de la idea de usar sendgrid para enviar correos a los usuarios de limpizimo, pero se 
<br>
las query-media lo que no es una buena idea. 
<br>
<br> 
El objetivo de este proyecto es enviar un correo sin usar query media (algunos clientes de email) no permiten estos.
<br>
Entonces se debe hacer todo en css puro, como está en este proyecto.

## El file HTML1 
Este archivo tiene en html sin estilos, solo enlazado al styles.css

## El css tiene 
Las clases que se usan

### Luego para mezclar los dos archivos
Se debe Colocar en el html1 la etiqueta style (el tag) y pasarle por el css Inlinner, que lo que hace es poner como propiedad style, luego se le quita la etiqueta style y queda Bien para enviar por correo. 