# Proyecto-IoT - Sistema de Alarmas

## Integrantes:     
- Cruz Breña Daniela Janeth
- Garay García Omar Ricardo
- Palacios Rangel María Fernanda
- Vega Montoya Rodrigo Julian
    
## Objetivo General:
Como objetivo tenemos brindar un producto que dará seguridad a una parte de la población puesto que se podrá adquirir en diferentes puntos de servicios, y brindara a su vez un estudio en tiempo real de las condiciones del ambiente, nuestro producto contará con cuatro sensores, uno de fuego, movimiento, gas y uno de sonido los cuales detectara cualquier emergencia y lo notificará al cliente a través de la aplicación. Lo anterior con el fin de mantener al usuario informado sobre las condiciones en las que se encuentra el entorno donde decida utilizar el producto ya sea hogar, negocio, etc.
   
## Objetivos específicos:
- La aplicación notificará cuando cualquier alarma del dispositivo sea encendida
- El usuario tendrá la capacidad de apagar las alarmas desde la aplicación
- El producto detectará la existencia de gases tóxicos en el ambiente y notificará al usuario a través de la aplicación, una alarma y un led rojo.
- El producto detectará la existencia de fuego en el ambiente y notificará al usuario a través de la aplicación, una alarma y un led rojo.
- El producto detectará movimiento alrededor de él y notificará al usuario a través de la aplicación y encenderá una luz al detectar movimiento
- El producto detectará sonido que se encuentre a su alrededor activando una luz para avisar que el sensor fue activado

## Tabla de Software utilizado:

| Id   | Software | Versión | Tipo     |
|------|----------|---------|----------|
| 1    | Arduino  | 2.0.0   | Gratuito |
| 2    | Python   | 3.10    | Gratuito |
| 3    | C        | C18     | Gratuito |
    
## Tabla de Hardware utilizado:
| Id  | Componente       | Descripción | Imagen | Cantidad | Costo Total        |
|-----|----------------------------|-----------|------------|----------------------------------------|--------------------|
| 1   | ESP32 | Es un microprocesador utilizado para el intercambio de información, tiene conectividad vía wi-fi y bluetooth| ![ESP32](https://user-images.githubusercontent.com/104101668/193494837-3962f38c-7024-4e79-9c3d-f8164a010101.jpeg)| 1 |$150| 
| 2   | Sensor de Gas|Los detectores de gas utilizan un sensor para cuantificar la agrupación de gases específicos en el clima. El sensor se llena como una fuente de punto de perspectiva y la escala, la entrega de un flujo eléctrico cuantificable cuando una respuesta sintética provocada por un gas en particular sucede.|![sensor de gas](https://user-images.githubusercontent.com/104101668/193495722-8122047e-cc09-4939-82b8-69c3e4102b73.jpg)|1| $70|
| 3   | Sensor de fuego|Un detector de llamas es un tipo de sensor que puede detectar y responder a la presencia de una llama|![sensor de fuego](https://user-images.githubusercontent.com/104101668/193496196-c0bcf021-7e9b-47a3-88c3-53e6ea71764b.jpg)|1|$40-$70|
| 4|Sensor PIR|Los sensores PIR son de tipo ópticos, es decir, se basan en cambios en la radiación electromagnética para sensar el entorno.|![sensor pir](https://user-images.githubusercontent.com/104101668/193496065-5aba9983-15d0-43d2-a71f-48130bce991e.jpg)|1| $70-$100|
| 5|Sensor de Sonido|El sensor de sonido es un módulo que convierte las ondas acústicas en señales eléctricas. En términos muy sencillos, los detectores de sonido funcionan en base a los cambios de capacitancia causados por la vibración de las ondas sonoras.|![sensor de sonido](https://user-images.githubusercontent.com/104101668/193496322-6b51577b-c9f5-453a-af6f-efafe31734d4.jpg)|1|$50-$70|
|6|Protoboard|Una protoboard, o breadboard, es prácticamente una PCB temporal con una forma y tamaño generalizados. Utilizada comúnmente para pruebas y prototipos temporales de circuitos.|![Protoboard](https://user-images.githubusercontent.com/104101668/193496509-3772607a-ac83-46e4-8224-c2e4f2d78cac.jpg)|1|$150-$200|
|7|Buzzer|Un 'zumbador es un transductor electroacústico que produce un sonido o zumbido continuo o intermitente de un mismo tono. Sirve como mecanismo de señalización o aviso y se utiliza en múltiples sistemas, como en automóviles o en electrodomésticos, incluidos los despertadores.|![buzzer](https://user-images.githubusercontent.com/104101668/193496659-837ea7bf-724e-4c95-b04d-2f5e2b35bede.jpg)|1|$50-$80|
|8|Led Verde|El Led verde está compuesto por GaP. Se utiliza el método de crecimiento epitaxial del cristal en fase líquida para formar la unión p-n|![led verde](https://user-images.githubusercontent.com/104101668/193497993-19642774-4a18-4d78-8f7f-3a2bbe9cd37b.jpg)|1|$2-$10|
|9|Led rojo|Es un componente optoelectrónico pasivo. Su funcionamiento está basado en el efecto de la Electro-Luminiscencia, en la cual mediante una estimulación directa de polarización permite a este dispositivo liberar energía en forma de un fotón, cuyo color está determinado por la banda de energía que haya sido estimulada.|![led rojo](https://user-images.githubusercontent.com/104101668/193497989-3a78ba55-d55e-4141-b9a1-d6462eb1fbd1.jpg)|1|$2-$10|
|10|Foco|En iluminación, un foco o proyector es un elemento óptico destinado a proyectar la luz de una lámpara hacia una región concreta o espacio determinado. Principalmente se usan para iluminar instalaciones deportivas, alumbrado ornamental de edificios emblemáticos, publicidad y seguridad|![foco](https://user-images.githubusercontent.com/104101668/193499129-55af0e96-cb2a-459f-a88f-36d9ca0b1c31.jpg)|1 o 2|$80-$120

## Épicas del proyecto
- Un usuario se encuentra fuera de su hogar y recibe una notificación de fuego en su hogar.
- Un hombre se encuentra en su centro laboral, recibe una notificación de movimiento en su hogar, finalmente se trata de un robo.
- Una mujer regresa a su hogar luego de recibir una notificación de la casa de su abuelo un  adulto de la tercera edad se encuentra en su hogar y dejó las llaves de la estufa abiertas y el sensor notificó la presencia de gases tóxicos en el ambiente
- Un hombre llega a su hogar de noche y no encuentra el apagador de la luz, pero de la nada se enciende gracias a que el usuario produjo un sonido alto que encendió las luces.

## Tabla de historia del usuario
| Id  | Historia de usuario        | Prioridad | Estimación | Como probarlo                          | Responsable        |
|-----|----------------------------|-----------|------------|----------------------------------------|--------------------|
| 1   | Funcionalidad del sensor de fuego |Alta| 3 semanas| Realizar pruebas con un encendedor.| Integrantes del Equipo|       
| 2   | Funcionalidad del sensor de gas| Alta | 3 semanas| Realizar prueas con un gas LP|Integrantes del Equipo|
| 3   | Funcionalidad del sensor de movimiento|Alta|3 semanas        | Realizar pruebas con ciertos movimientos para probar el foco|Integrantes del Equipo|
| 4   | Función del sensor de sonido| Alta| 4 semanas| Realizar pruebas con distintos tipos de sonidos para calibrar el sensor|Integrantes del Equipo|

## Prototipo Dibujo:
![boceto](https://user-images.githubusercontent.com/104101668/193502489-52f58469-e364-4894-9f7e-390cbd447590.jpeg)



