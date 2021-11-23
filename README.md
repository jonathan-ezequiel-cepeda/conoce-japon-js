# CONOCE JAPON (JS)

Página web sobre viajes a japon aplicando JS

Proyecto final del curso de JS de coderhouse. ¡Ojalá sea de su agrado!

En la misma se utilizaron distintas técnicas aprendidas a lo largo del curso. Les dejo un pequeño resumen de lo que se puede hacer en la página:

En la sección de back office, se pueden crear paquetes turísticos dinámicamente utilizando values de inputs, y eventos. Los mismos se muestran luego en la sección de servicios a través de un array de objetos que creamos en el local storage.
(Cabe mencionar que para que puedan comprobar la funcionalidad dinámica del array de una manera más amena, cuando se agrega un primer paquete, se agregan también otros 5 que están creados de manera predeterminada. Esto fue una decisión propia para que sea más fácil apreciar el mensaje de cuando no hay servicios,  y a su vez se pueda comprobar el dinamismo en cuanto a la información de los objetos del array agregando un solo paquete). 
Dentro del back office, también hay un botón que te permite borrar todos los paquetes creados.

En la sección de servicios, como ya se indicó, se imprimen dinámicamente los paquetes creados en el back office y almacenados en el local storage. Al hacerles click se pueden leer los datos individuales y dinámicos de cada uno de ellos (nombre, precio, y cantidad de días). y también tienen la funcionalidad de ser agregados al carrito de compras.

Dentro del carrito de compras tenemos la posibilidad de finalizar la compra de los paquetes agregados desde la sección de servicios. El mismo se actualiza y vacía una vez que finalizamos la compra.

La página también cuenta con un botón en forma de pétalo, que al hacerle click activa y desactiva las animaciones de los pétalos cayendo (Que están creadas con css puro).

En la página se utilizó tanto JS vanilla como también Jquery. Entre otras cosas Jquery fue usado para consumir una api que imprime los distintos valores del dólar en la parte de cotizaciones.

Gracias por tomarse el tiempo de leer. Y espero que disfruten de la página!
