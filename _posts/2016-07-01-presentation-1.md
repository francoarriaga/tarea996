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

---

{% for slide in page.slides %}
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}">
  <h1 style="font-size: 30px;">{{slide.title}}</h1>
   <div style="font-size: 20px;">
     {{ slide.slide-data | markdownify }}
   </div>
</section>

{% endfor %}

