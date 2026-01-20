SpeedFast - Semana 2 (POO)

Este proyecto corresponde a la actividad “Definiendo una clase abstracta y su jerarquía”.
Se implementa una clase abstracta llamada Pedido, que contiene atributos y métodos comunes para distintos tipos de pedidos, aplicando herencia y polimorfismo.

1. Clases implementadas:
- Pedido (abstracta)
- Atributos: idPedido, direccionEntrega, distanciaKm

2. Métodos:
- mostrarResumen()
- calcularTiempoEntrega() (método abstracto)

3. PedidoComida
- Tiempo estimado = 15 minutos + 2 minutos por cada kilómetro.

4. PedidoEncomienda
- Tiempo estimado = 20 minutos + 1.5 minutos por kilómetro (redondeado a entero).

5. PedidoExpress
- Tiempo base = 10 minutos.
- Si la distancia es mayor a 5 km, se agregan 5 minutos extra.

Estructura del proyecto (Packages)
cl.speedfast.model → Contiene las clases Pedido y sus subclases.
cl.speedfast.app → Contiene la clase Main para ejecutar el programa.

Ejecución del programa
Para ejecutar el sistema se debe correr la clase Main.java.
El programa crea un objeto de cada tipo de pedido, muestra un resumen y luego imprime el tiempo estimado de entrega en consola.
