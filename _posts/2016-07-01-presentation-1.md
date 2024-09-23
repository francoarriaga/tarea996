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
      # <span style="font-size: 3em;">Sensores Ópticos</span>

     Los sensores ópticos detectan cambios en la luz (intensidad, color o posición) para generar una señal de salida. Estos dispositivos 
     son esenciales en aplicaciones de automatización, robótica y sistemas de seguridad. El funcionamiento se basa en la emisión y 
     recepción de luz.

     ## Funcionamiento
     Un sensor óptico consta de:
     - **Emisor de luz**: Puede ser un LED, láser o infrarrojo.
     - **Receptor**: Fototransistor o fotodiodo.

     El emisor envía un haz de luz hacia un objeto, y el receptor mide la cantidad de luz reflejada, interrumpida o absorbida. La 
     variación de luz se traduce en una señal eléctrica que se procesa para tomar decisiones automáticas.

 - title: Slide 3
   slide-data: This is third slide
---

{% for slide in page.slides %}
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}">
  <h1 style="font-size: 20px;">{{slide.title}}</h1>
   <div style="font-size: 10px;">
   {{ slide.slide-data | markdownify }}
  </div>
 
</section>
{% endfor %}

