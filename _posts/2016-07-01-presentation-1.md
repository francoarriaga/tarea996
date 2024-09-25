---
title: Presentation 1
layout: post
permalink: /presentation-1/
background: '#0a5'
slides:
 - title: Unidad 1
   slide-data: This is first slide
     
 - title: Sensores Ópticos
   slide-data: |
     ## Sensores Ópticos

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

 - title: Sensores de temperatura
   slide-data: |
     ### Sensores de Temperatura
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

  
---

{% for slide in page.slides %}
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}">
  <h1 style="font-size: 30px;">{{slide.title}}</h1>
   <div style="font-size: 20px;">
     {{ slide.slide-data | markdownify }}
   </div>
</section>

{% endfor %}

