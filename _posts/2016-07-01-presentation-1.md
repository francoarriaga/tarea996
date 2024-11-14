---
title: Unidad 1
layout: post
permalink: /presentation-1/

slides:
 - title: 
   background: "../images/fondogris.jpg"
   slide-data: |
    <h1 style="font-size: 50px; color:black">INSTITUTO TECNOLOGICO DE CANCUN </h1>
    <ul style="font-size: 30px; color:black">
       <li>NOMBRE DEL ALUMNO: ARRIAGA PECH FRANCO MARTHELY.</li>
       <li>NOMBRE DEL DOCENTE: DR. ISMAEL JIMÉNEZ SÁNCHEZ.</li>
       <li>NOMBRE DE LA MATERIA: SISTEMAS PROGRAMABLES.</li>
       <li>TAREA: “REALIZAR UNA PRESENTACIÓN DE LA UNIDAD 1, CON MARKDOWN, USANDO https://slides.webjeda.com/ EN SU PROPIO REPOSITORIO 
            DE SLIDES”.
       </li>
       <li>NOMBRE DE LA CARRERA: INGENIERÍA EN SISTEMAS COMPUTACIONALES.</li>
       <li>GRADO: NOVENO SEMESTRE.</li>
     </ul>
     
 - title:
   background: "../images/fondolineas.png"
   slide-data: |
     <h1 style="font-size: 50px;">Sensores Ópticos </h1>

     Los sensores ópticos detectan cambios en la luz (intensidad, color o posición) para generar una señal de salida. Estos dispositivos 
     son esenciales en aplicaciones de automatización, robótica y sistemas de seguridad. El funcionamiento se basa en la emisión y 
     recepción de luz.

     ### Funcionamiento
     Un sensor óptico consta de:
     - **Emisor de luz**: Puede ser un LED, láser o infrarrojo.
     - **Receptor**: Fototransistor o fotodiodo. 

     El emisor envía un haz de luz hacia un objeto, y el receptor mide la cantidad de luz reflejada, interrumpida o absorbida. La 
     variación de luz se traduce en una señal eléctrica que se procesa para tomar decisiones automáticas.

 - title: Funcionamiento general
   slide-data: |
     El principio básico de funcionamiento de los **sensores ópticos** es la emisión de luz (ya sea **infrarroja**, **visible** o 
     **láser**) y la detección de cómo esta luz interactúa con el entorno. Dependiendo del tipo de sensor, pueden medir diferentes 
     propiedades: si la luz es bloqueada, reflejada, absorbida o desviada.
   
 - title: Características principales
   slide-data: | 
     - **Precisión**: Los sensores ópticos pueden detectar cambios muy pequeños en su entorno.
     - **Velocidad de respuesta**: La mayoría de los sensores ópticos son muy rápidos, lo que los hace adecuados para aplicaciones de 
     alta velocidad.
     - **Tamaño compacto**: Pueden ser pequeños, lo que facilita su integración en sistemas electrónicos.
     - **Inmunidad a interferencias electromagnéticas**: Al utilizar luz, no se ven afectados por campos electromagnéticos.
     - **Alcance**: Los sensores pueden trabajar a diferentes distancias, dependiendo de su tipo (algunos hasta varios kilómetros, como 
     los **LIDAR**).

 - title: Modos de comunicación
   slide-data: |
     Los sensores ópticos pueden utilizar diferentes métodos para transmitir su señal, incluyendo:
     - **Señal analógica**: Donde la salida es una variación continua que corresponde a la intensidad de la luz recibida.
     - **Señal digital**: Que representa condiciones específicas como "presencia" o "ausencia" de un objeto.
     - **Protocolos de comunicación**: Sensores más avanzados pueden usar buses de comunicación como **I2C**, **RS-485**, o incluso 
     tecnologías inalámbricas como **Bluetooth** o **Wi-Fi** para transmitir información en sistemas más complejos.

 - title: 
   slide-data: |
     <h1 style="font-size: 50px;">Sensores de temperatura </h1>
     Los **sensores de temperatura** son dispositivos utilizados para medir la temperatura en diferentes ambientes y procesos. Existen 
     varios tipos de sensores de temperatura, cada uno con principios de funcionamiento y aplicaciones específicas. A continuación se 
     detallan los tipos más comunes:
     - **Termopares**: Generan una pequeña corriente eléctrica cuando se unen dos metales diferentes y están sometidos a temperaturas 
     distintas. La diferencia de temperatura crea un voltaje, que se mide y traduce a una lectura de temperatura.
     - **Termistores**: Son resistencias que cambian su valor en función de la temperatura. Pueden ser **NTC** (Coeficiente de 
     Temperatura Negativo) o **PTC** (Coeficiente de Temperatura Positivo).
     - **RTD (Detector de Temperatura por Resistencia)**: Utilizan metales, comúnmente platino, cuya resistencia eléctrica cambia con la 
     temperatura.
     - **Sensores de temperatura de semiconductores**: Basados en diodos o transistores que cambian su corriente de salida según la 
     temperatura.
     - **Sensores Infrarrojos (IR)**: Miden la radiación térmica emitida por un objeto y calculan la temperatura sin contacto físico.
 - title: Funcionamiento de los sensores de temperatura
   slide-data: |
     El principio básico de funcionamiento de los **sensores ópticos** es la emisión de luz (ya sea **infrarroja**, **visible** o 
     **láser**) y la detección de cómo esta luz interactúa con el entorno. Dependiendo del tipo de sensor, pueden medir diferentes 
     propiedades: si la luz es bloqueada, reflejada, absorbida o desviada.
   
 - title: Características de los sensores de temperatura
   slide-data: |
     - **Precisión**: Los sensores ópticos pueden detectar cambios muy pequeños en su entorno.
     - **Velocidad de respuesta**: La mayoría de los sensores ópticos son muy rápidos, lo que los hace adecuados para aplicaciones de   
     alta velocidad.
     - **Tamaño compacto**: Pueden ser pequeños, lo que facilita su integración en sistemas electrónicos.
     - **Inmunidad a interferencias electromagnéticas**: Al utilizar luz, no se ven afectados por campos electromagnéticos.
     - **Alcance**: Los sensores pueden trabajar a diferentes distancias, dependiendo de su tipo (algunos hasta varios kilómetros, como        los **LIDAR**).

 - title: Modo de comunicación de los sensores de temperatura
   slide-data: |
      Los **sensores de temperatura** pueden comunicar su medición de diferentes maneras:
      - **Señal analógica**: La mayoría de los sensores más simples (termopares, RTD, termistores) generan una señal analógica 
      proporcional al cambio de temperatura. Esta señal necesita ser convertida para su interpretación.
      - **Señal digital**: Sensores más modernos, como los de semiconductores, envían directamente señales digitales, a menudo 
      utilizando buses de comunicación como **I2C**, **SPI** o **1-Wire**.
      - **Protocolo de comunicación inalámbrica**: Algunos sensores de temperatura infrarrojos y semiconductores más avanzados pueden 
      comunicarse a través de **Wi-Fi**, **Bluetooth** o **Zigbee** para aplicaciones como monitoreo remoto.

 - title: 
   slide-data: |
      <h1 style="font-size: 50px;">Sensor de presión </h1>
      Los **sensores de presión** son dispositivos que miden la presión de un fluido (líquido o gas) y la convierten en una señal 
      eléctrica. Son ampliamente utilizados en aplicaciones industriales, automotrices, médicas y en sistemas de control.

      ### Tipos de sensores de presión

      - **Sensores de presión absoluta**: Miden la presión con respecto a un vacío perfecto (0 Pa). Están calibrados para medir la 
      presión absoluta, sin referencia a la presión atmosférica.
  
      - **Sensores de presión manométrica**: Miden la presión relativa con respecto a la presión atmosférica. Se utilizan para medir 
      presiones superiores o inferiores a la presión ambiental.
  
      - **Sensores de presión diferencial**: Miden la diferencia entre dos puntos de presión. Son útiles para aplicaciones en las que se 
      necesita comparar presiones en distintos puntos de un sistema.
  
      - **Sensores de presión piezoeléctricos**: Utilizan materiales piezoeléctricos que generan una carga eléctrica cuando se someten a 
      una fuerza o presión.
  
      - **Sensores de presión capacitivos**: La presión cambia la distancia entre dos placas de un condensador, lo que varía su 
      capacitancia. Este cambio se traduce en una señal eléctrica.
  
      - **Sensores de presión piezorresistivos**: Cambian su resistencia en función de la presión aplicada a un material semiconductor.

 - title: Funcionamiento del sensor de presión
   slide-data: |
      La mayoría de los **sensores de presión** convierten la fuerza ejercida por un fluido en una señal eléctrica, ya sea a través de 
      principios como la **piezorresistencia**, la **capacitancia**, la **piezoelectricidad** o el **desplazamiento de un diafragma**. 
      La señal obtenida se interpreta como presión y puede estar en unidades como pascales (Pa), libras por pulgada cuadrada (psi) o 
      bares (bar).
 - title: Características del sensor de presión
   slide-data: |
      - **Precisión**: Algunos sensores, como los piezorresistivos y capacitivos, ofrecen alta precisión en sus mediciones.
      - **Rango de presión**: Varía según el tipo. Los sensores de presión absoluta pueden medir presiones desde el vacío absoluto hasta 
      miles de pascales. Los sensores industriales suelen medir desde milibares hasta varios cientos de bares.
      - **Durabilidad**: Sensores piezoeléctricos y piezorresistivos son robustos y adecuados para aplicaciones en condiciones extremas 
      de temperatura y presión.
      - **Sensibilidad**: Los sensores piezoeléctricos son altamente sensibles a los cambios rápidos de presión, mientras que los 
      sensores capacitivos son más adecuados para mediciones estables y precisas.
      - **Tamaño**: Algunos sensores, como los capacitivos y piezorresistivos, pueden ser muy compactos, lo que permite su integración 
      en dispositivos pequeños.

 - title: Modo de comunicación del sensor de presión
   slide-data: |
      Los sensores de proximidad son dispositivos que detectan la presencia o ausencia de un objeto dentro de su rango de operación sin 
      necesidad de contacto físico. Son ampliamente utilizados en automatización industrial, robótica, vehículos y aplicaciones de 
      seguridad. A continuación se describen los tipos, funcionamiento, características y modos de comunicación de estos sensores.
      Los **sensores de presión** tienen diferentes formas de transmitir la información de presión que miden, entre ellas:
      - **Señal analógica**: La mayoría de los sensores simples emiten una señal analógica en forma de voltaje (mV/V, 0-10V, 0-5V) o 
      corriente (4-20 mA), que puede ser procesada directamente por controladores o convertida en digital.
  
      - **Señal digital**: Sensores más avanzados convierten la señal a formato digital y pueden comunicarse a través de protocolos 
      estándar como **I2C**, **SPI**, **RS-485**, o **Modbus**.
  
      - **Comunicación inalámbrica**: Sensores más modernos pueden transmitir datos de presión mediante **Wi-Fi**, **Bluetooth**, o 
      **Zigbee**, especialmente en aplicaciones de monitoreo remoto.
        
 - title: 
   slide-data: |
      <h1 style="font-size: 50px;">Sensores de proximidad</h1>
      Los **sensores de proximidad** son dispositivos que detectan la presencia o ausencia de un objeto dentro de su rango de operación 
      sin necesidad de contacto físico. Son ampliamente utilizados en automatización industrial, robótica, vehículos y aplicaciones de 
      seguridad. 

      #### 1. Tipos de Sensores de Proximidad

      ##### a) Sensores Inductivos
      - **Funcionamiento**: Utilizan un campo electromagnético para detectar objetos metálicos. Cuando un objeto metálico se acerca al 
      sensor, altera el campo electromagnético, lo que provoca un cambio en la señal de salida.

      ##### b) Sensores Capacitivos
      - **Funcionamiento**: Miden cambios en la capacitancia causados por la proximidad de un objeto, ya sea metálico o no metálico 
      (como plásticos, líquidos o madera). Funcionan creando un campo eléctrico que se ve afectado por la presencia del objeto.

      ##### c) Sensores Ópticos
      - **Funcionamiento**: Utilizan luz (normalmente infrarroja) para detectar la presencia de objetos. Pueden ser sensores de 
      reflexión (el emisor y el receptor están en el mismo dispositivo) o de barrera (emisor y receptor separados).

      ##### d) Sensores Ultrasónicos
      - **Funcionamiento**: Emplean ondas ultrasónicas para detectar la distancia a un objeto. El sensor emite un pulso de sonido y mide 
      el tiempo que tarda en regresar después de rebotar en el objeto.

 - title: Funcionamiento de los sensores de proximidad
   slide-data: |
      Los **sensores de proximidad** funcionan creando un campo físico (magnético, eléctrico, acústico o luminoso) y detectando cambios 
      en este campo provocados por la presencia de un objeto. Esta alteración genera una señal que es procesada y convertida en una 
      salida (normalmente digital), que indica la presencia o ausencia del objeto.
   
 - title: Caracteristicas de los sensores de proximidad
   slide-data: |
      - **Rango de detección**: Varía según el tipo de sensor, desde unos pocos milímetros hasta varios metros.
      - **Durabilidad**: La mayoría son robustos y pueden trabajar en condiciones difíciles.
      - **Sensibilidad**: Algunos sensores, como los ópticos y ultrasónicos, son muy sensibles y pueden detectar objetos en movimiento.
      - **Inmunidad a interferencias**: Los sensores inductivos y capacitivos pueden ser afectados por condiciones ambientales, mientras 
      que los ópticos son sensibles a la luz ambiental.
 - title: Modo de comunicación de los sensores de proximidad
   slide-data: |
      Los **sensores de proximidad** pueden tener diferentes formas de comunicar sus señales:

      - **Salida digital**: La mayoría de los sensores proporcionan una señal de encendido/apagado (ON/OFF) cuando se detecta un objeto. 
      Esta es la forma más común de salida.
  
      - **Salida analógica**: Algunos sensores pueden proporcionar una señal analógica proporcional a la distancia o la proximidad del 
      objeto.
  
      - **Protocolos de comunicación**: Los sensores más avanzados pueden utilizar protocolos de comunicación como **I2C**, **RS-485**, 
      o **Modbus** para transmitir datos a sistemas de control.

---

{% for slide in page.slides %}
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}">
  <h1 style="font-size: 30px;">{{slide.title}}</h1>
   <div style="font-size: 20px;">
     {{ slide.slide-data | markdownify }}
   </div>
</section>

{% endfor %}

