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
        <h1 style="font-size: 50px;">Sensores Ópticos</h1>
        <div style="display: flex; justify-content: space-between; align-items: flex-start;">

        <!-- Sección de texto a la izquierda -->
        <div style="width: 60%; padding-right: 20px;">
          
          <p>
            Los sensores ópticos detectan cambios en la luz (intensidad, color o posición) para generar una señal de salida. Estos dispositivos
            son esenciales en aplicaciones de automatización, robótica y sistemas de seguridad. El funcionamiento se basa en la emisión y
            recepción de luz.
          </p>
          <h3>Funcionamiento</h3>
          <p>Un sensor óptico consta de:</p>
          <ul>
            <li><strong>Emisor de luz</strong>: Puede ser un LED, láser o infrarrojo.</li>
            <li><strong>Receptor</strong>: Fototransistor o fotodiodo.</li>
          </ul>
          <p>
            El emisor envía un haz de luz hacia un objeto, y el receptor mide la cantidad de luz reflejada, interrumpida o absorbida. La
            variación de luz se traduce en una señal eléctrica que se procesa para tomar decisiones automáticas.
          </p>
        </div>

        <!-- Sección de imágenes a la derecha -->
        <div style="width: 35%; display: flex; flex-direction: column; align-items: center;">
          <img src="../images/emisordeluz.jpg" alt="Emisor de luz" style="width: 100%; margin-bottom: 20px;">
          <img src="../images/receptordeluz.webp" alt="Receptor de luz" style="width: 100%;">
        </div>

        </div> 




 - title: 
   background: "../images/fondolineas.png"
   slide-data: |
      <h2>Funcionamiento general </h2>
      <div style="width: 100%;">
        <p>
          El principio básico de funcionamiento de los <strong>sensores ópticos</strong> es la emisión de luz (ya sea <strong>infrarroja</strong>, 
          <strong>visible</strong> o <strong>láser</strong>) y la detección de cómo esta luz interactúa con el entorno. Dependiendo del tipo 
          de sensor, pueden medir diferentes propiedades: si la luz es bloqueada, reflejada, absorbida o desviada.
        </p>
        
        <!-- Imagen debajo del texto -->
        <div style="display: flex; justify-content: center; margin-top: 20px;">
          <img src="../images/infrarojo.jpg" alt="Funcionamiento de los sensores ópticos" style="width: 60%;">
        </div>
      </div>

   
 - title: 
 - background: "../images/fondolineas.png"
   slide-data: | 
     <div style="width: 100%;">

      <h2>Características principales</h2>
      <ul>
        <li><strong>Precisión</strong>: Los sensores ópticos pueden detectar cambios muy pequeños en su entorno.</li>
        <li><strong>Velocidad de respuesta</strong>: La mayoría de los sensores ópticos son muy rápidos, lo que los hace adecuados para aplicaciones de alta velocidad.</li>
        <li><strong>Tamaño compacto</strong>: Pueden ser pequeños, lo que facilita su integración en sistemas electrónicos.</li>
        <li><strong>Inmunidad a interferencias electromagnéticas</strong>: Al utilizar luz, no se ven afectados por campos electromagnéticos.</li>
        <li><strong>Alcance</strong>: Los sensores pueden trabajar a diferentes distancias, dependiendo de su tipo (algunos hasta varios kilómetros, como los <strong>LIDAR</strong>).</li>
      </ul>

     </div>


 - title: 
 - background: "../images/fondolineas.png"
   slide-data: |
    <h2>Modos de comunicación</h2>
    <div style="display: flex; justify-content: space-between; align-items: flex-start;">

      <!-- Columna 1: Señal Analógica -->
      <div style="width: 30%; padding-right: 10px;">
        <h3>Señal Analógica</h3>
        <p>
          Donde la salida es una variación continua que corresponde a la intensidad de la luz recibida. Este tipo de señal permite
          una medición precisa de los cambios en la luz.
        </p>
      </div>

      <!-- Columna 2: Señal Digital -->
      <div style="width: 30%; padding-right: 10px;">
        <h3>Señal Digital</h3>
        <p>
          Representa condiciones específicas como "presencia" o "ausencia" de un objeto. Este tipo de señal es común en aplicaciones
          que requieren detección binaria simple.
        </p>
      </div>

      <!-- Columna 3: Protocolos de Comunicación -->
      <div style="width: 30%;">
        <h3>Protocolos de Comunicación</h3>
        <p>
          Sensores más avanzados pueden usar buses de comunicación como <strong>I2C</strong>, <strong>RS-485</strong>, o tecnologías 
          inalámbricas como <strong>Bluetooth</strong> o <strong>Wi-Fi</strong> para transmitir información en sistemas más complejos.
        </p>
      </div>

    </div>


 - title: 
 - background: "../images/fondoverde.jpg"
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
   background: "../images/fondoverde.jpg"
   slide-data: |
     <div style="display: flex; justify-content: space-between; align-items: flex-start;">

      <!-- Sección de texto a la izquierda -->
      <div style="width: 60%; padding-right: 20px;">
        <p>
          El principio básico de funcionamiento de los <strong>sensores ópticos</strong> es la emisión de luz (ya sea <strong>infrarroja</strong>, 
          <strong>visible</strong> o <strong>láser</strong>) y la detección de cómo esta luz interactúa con el entorno. Dependiendo del tipo de 
          sensor, pueden medir diferentes propiedades: si la luz es bloqueada, reflejada, absorbida o desviada.
        </p>
      </div>

      <!-- Imagen a la derecha -->
      <div style="width: 35%; display: flex; justify-content: center;">
        <img src="../images/sensorluz2.png" alt="Funcionamiento de los sensores de temperatura" style="width: 100%;">
      </div>

     </div>

   
 - title: 
 - background: "../images/fondoverde.jpg"
   slide-data: |
      <h2>Características de los sensores de temperatura</h2>
    
      <table style="width: 100%; border-collapse: collapse;">
        <tr>
          <th style="text-align: left; padding: 8px; border: 1px solid #ddd;"><strong>Característica</strong></th>
          <th style="text-align: left; padding: 8px; border: 1px solid #ddd;"><strong>Descripción</strong></th>
        </tr>
        <tr>
          <td style="padding: 8px; border: 1px solid #ddd;"><strong>Precisión</strong></td>
          <td style="padding: 8px; border: 1px solid #ddd;">Los sensores ópticos pueden detectar cambios muy pequeños en su entorno.</td>
        </tr>
        <tr>
          <td style="padding: 8px; border: 1px solid #ddd;"><strong>Velocidad de respuesta</strong></td>
          <td style="padding: 8px; border: 1px solid #ddd;">La mayoría de los sensores ópticos son muy rápidos, lo que los hace adecuados para aplicaciones de alta velocidad.</td>
        </tr>
        <tr>
          <td style="padding: 8px; border: 1px solid #ddd;"><strong>Tamaño compacto</strong></td>
          <td style="padding: 8px; border: 1px solid #ddd;">Pueden ser pequeños, lo que facilita su integración en sistemas electrónicos.</td>
        </tr>
        <tr>
          <td style="padding: 8px; border: 1px solid #ddd;"><strong>Inmunidad a interferencias electromagnéticas</strong></td>
          <td style="padding: 8px; border: 1px solid #ddd;">Al utilizar luz, no se ven afectados por campos electromagnéticos.</td>
        </tr>
        <tr>
          <td style="padding: 8px; border: 1px solid #ddd;"><strong>Alcance</strong></td>
          <td style="padding: 8px; border: 1px solid #ddd;">Los sensores pueden trabajar a diferentes distancias, dependiendo de su tipo (algunos hasta varios kilómetros, como los <strong>LIDAR</strong>).</td>
        </tr>
      </table>

 - title: 
   background: "../images/fondoverde.jpg"
   slide-data: |
      <h2>Modo de comunicación de los sensores de temperatura</h2>
      <p>
        Los <strong>sensores de temperatura</strong> pueden comunicar su medición de diferentes maneras:
      </p>
      <ul>
        <li>
          <strong>Señal analógica</strong>: La mayoría de los sensores más simples (termopares, RTD, termistores) generan una señal analógica 
          proporcional al cambio de temperatura. Esta señal necesita ser convertida para su interpretación.
        </li>
        <li>
          <strong>Señal digital</strong>: Sensores más modernos, como los de semiconductores, envían directamente señales digitales, a menudo 
          utilizando buses de comunicación como <strong>I2C</strong>, <strong>SPI</strong> o <strong>1-Wire</strong>.
        </li>
        <li>
          <strong>Protocolo de comunicación inalámbrica</strong>: Algunos sensores de temperatura infrarrojos y semiconductores más avanzados 
          pueden comunicarse a través de <strong>Wi-Fi</strong>, <strong>Bluetooth</strong> o <strong>Zigbee</strong> para aplicaciones como 
          monitoreo remoto.
        </li>
      </ul>


 - title: 
 - background: "../images/fondomorado.png"
   slide-data: |
      <h1 style="font-size: 50px;">Sensor de presión</h1>
      <p>
        Los <strong>sensores de presión</strong> son dispositivos que miden la presión de un fluido (líquido o gas) y la convierten en una señal 
        eléctrica. Son ampliamente utilizados en aplicaciones industriales, automotrices, médicas y en sistemas de control.
      </p>

      <h3>Tipos de sensores de presión</h3>

      <table style="width: 100%; border-collapse: collapse;">
        <tr>
          <th style="text-align: left; padding: 8px; border: 1px solid #ddd;"><strong>Tipo de Sensor</strong></th>
          <th style="text-align: left; padding: 8px; border: 1px solid #ddd;"><strong>Descripción</strong></th>
        </tr>
        <tr>
          <td style="padding: 8px; border: 1px solid #ddd;"><strong>Sensores de presión absoluta</strong></td>
          <td style="padding: 8px; border: 1px solid #ddd;">
            Miden la presión con respecto a un vacío perfecto (0 Pa). Están calibrados para medir la presión absoluta, sin referencia a la 
            presión atmosférica.
          </td>
        </tr>
        <tr>
          <td style="padding: 8px; border: 1px solid #ddd;"><strong>Sensores de presión manométrica</strong></td>
          <td style="padding: 8px; border: 1px solid #ddd;">
            Miden la presión relativa con respecto a la presión atmosférica. Se utilizan para medir presiones superiores o inferiores a la 
            presión ambiental.
          </td>
        </tr>
        <tr>
          <td style="padding: 8px; border: 1px solid #ddd;"><strong>Sensores de presión diferencial</strong></td>
          <td style="padding: 8px; border: 1px solid #ddd;">
            Miden la diferencia entre dos puntos de presión. Son útiles para aplicaciones en las que se necesita comparar presiones en 
            distintos puntos de un sistema.
          </td>
        </tr>
        <tr>
          <td style="padding: 8px; border: 1px solid #ddd;"><strong>Sensores de presión piezoeléctricos</strong></td>
          <td style="padding: 8px; border: 1px solid #ddd;">
            Utilizan materiales piezoeléctricos que generan una carga eléctrica cuando se someten a una fuerza o presión.
          </td>
        </tr>
        <tr>
          <td style="padding: 8px; border: 1px solid #ddd;"><strong>Sensores de presión capacitivos</strong></td>
          <td style="padding: 8px; border: 1px solid #ddd;">
            La presión cambia la distancia entre dos placas de un condensador, lo que varía su capacitancia. Este cambio se traduce en una 
            señal eléctrica.
          </td>
        </tr>
        <tr>
          <td style="padding: 8px; border: 1px solid #ddd;"><strong>Sensores de presión piezorresistivos</strong></td>
          <td style="padding: 8px; border: 1px solid #ddd;">
            Cambian su resistencia en función de la presión aplicada a un material semiconductor.
          </td>
        </tr>
      </table>



 - background: "../images/fondomorado.png"
   slide-data: |
      <h2>Funcionamiento del sensor de presión</h2>
      <p>
      La mayoría de los <strong>sensores de presión</strong> convierten la fuerza ejercida por un fluido en una señal eléctrica, ya sea a 
      través de principios como la <strong>piezorresistencia</strong>, la <strong>capacitancia</strong>, la <strong>piezoelectricidad</strong> 
      o el <strong>desplazamiento de un diafragma</strong>. La señal obtenida se interpreta como presión y puede estar en unidades como 
      pascales (Pa), libras por pulgada cuadrada (psi) o bares (bar).
      </p>

 - background: "../images/fondomorado.png"
   slide-data: |
      <h2>Características del sensor de presión</h2>
      <ul>
      <li><strong>Precisión</strong>: Algunos sensores, como los piezorresistivos y capacitivos, ofrecen alta precisión en sus mediciones.</li>
      <li><strong>Rango de presión</strong>: Varía según el tipo. Los sensores de presión absoluta pueden medir presiones desde el vacío absoluto hasta miles de pascales. Los sensores industriales suelen medir desde milibares hasta varios cientos de bares.</li>
      <li><strong>Durabilidad</strong>: Sensores piezoeléctricos y piezorresistivos son robustos y adecuados para aplicaciones en condiciones extremas de temperatura y presión.</li>
      <li><strong>Sensibilidad</strong>: Los sensores piezoeléctricos son altamente sensibles a los cambios rápidos de presión, mientras que los sensores capacitivos son más adecuados para mediciones estables y precisas.</li>
      <li><strong>Tamaño</strong>: Algunos sensores, como los capacitivos y piezorresistivos, pueden ser muy compactos, lo que permite su integración en dispositivos pequeños.</li>
       </ul>


 - background: "../images/fondomorado.png"
   slide-data: |
      <div style="display: flex; justify-content: space-between; align-items: flex-start;">

        <!-- Sección de texto a la izquierda -->
            <div style="width: 60%; padding-right: 20px;">
          <h2>Modo de comunicación del sensor de presión</h2>
          <p>
            Los <strong>sensores de presión</strong> tienen diferentes formas de transmitir la información de presión que miden, entre ellas:
          </p>
          <ul>
            <li><strong>Señal analógica</strong>: La mayoría de los sensores simples emiten una señal analógica en forma de voltaje (mV/V, 0-10V, 0-5V) o corriente (4-20 mA), que puede ser procesada directamente por controladores o convertida en digital.</li>
            <li><strong>Señal digital</strong>: Sensores más avanzados convierten la señal a formato digital y pueden comunicarse a través de protocolos estándar como <strong>I2C</strong>, <strong>SPI</strong>, <strong>RS-485</strong>, o <strong>Modbus</strong>.</li>
            <li><strong>Comunicación inalámbrica</strong>: Sensores más modernos pueden transmitir datos de presión mediante <strong>Wi-Fi</strong>, <strong>Bluetooth</strong>, o <strong>Zigbee</strong>, especialmente en aplicaciones de monitoreo remoto.</li>
          </ul>
          </div>

          <!-- Imagen a la derecha -->
          <div style="width: 35%; display: flex; justify-content: center;">
            <img src="../images/analogicodigital.png" alt="Sensor de presión" style="width: 100%;">
          </div>

      </div>

        
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

