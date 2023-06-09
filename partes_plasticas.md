<!--
SPDX-FileCopyrightText: 2023 Tecnología de Raíz <tecnologiaderaiz@disroot.org>

SPDX-License-Identifier: CC-BY-NC-4.0
-->

#    Partes plásticas

En este material mostraremos los diseños y planos de las partes plásticas que complementan el proceso de producción de las antenas

    
La posibilidad de acceder a la impresion 3d como recurso nos habilito a poder crear nuestros propios moldes (matriceria) para facilitar el proceso de producción, así como construir insumos para las guías de ondas.

En principio, las partes plásticas surgieron de la necesidad de sustituir los regatones de plástico utilizados como tapas por tapas plásticas impresas en 3D.

Viendo el potencial de las impresiones 3D diseñamos un prototipo de portachain para sostener los cables de la antena, y también moldes para facilitar la perforacion de los caños de las guías de ondas.
    El portachain actual nos permite reemplazar procedimientos como soldadura o resinado, acortando los tiempos de producción y los costos también. El proceso hasta llegar a estos diseños y los diferentes prototipos previos están registrados <a href="/Prototipado.html">acá</a>
    Este proceso de investigación implicó familiarizarnos con las herramientas de diseño en Freecad y prácticas con la impresora. Actualmente estamos por acceder a una capacitación de la UTN (Universidad Técnica Nacional) para perfeccionar las impresiones.

<hr>
    
<h3>
    <u>
        Tapas
    </u>
</h3>



Nuestro primer <a href="https://github.com/TecnologiadeRaiz/LoPALiR/blob/main/Partes%20plasticas/Tapas/TAPA-v1.FCStd">diseño</a> nos permitió mejorar el funcionamiento de la antena, ya que los regatones plásticos que usábamos como tapa interferían en la señal de las guías de ondas.

 

![](images/1-plano_tapa.png)
![](images/2-tapa.jpg)
![](images/3-tapa.jpg)



<br>
  
<h3>
    <u>
        Molde de perforación
    </u> 
</h3>
   


![](models/MOLDEDEPERFORACIONGUIADEONDAS-v2.stl){color: #996699}

Este <a href="https://github.com/TecnologiadeRaiz/LoPALiR/tree/main/Partes%20plasticas/Molde%20de%20perforacion">diseño</a> nos aporta precisión a la hora de realizar las perforaciones en la guía de ondas, agilizando el proceso de producción.



![](images/4-molde_de_perforacion.jpg)
![](images/5-plano_molde_de_perforacion.png)



<br>


<h3>
    <u>
        Portachain
    </u>
</h3>


La posibilidad de diseñar <a href="https://github.com/TecnologiadeRaiz/LoPALiR/tree/main/Partes%20plasticas/PORTACHAIN">estas piezas</a> nos permitió optimizar la forma de sujetar los cables, que se presentaba como un desafìo en los prototipos anteriores, significando un costo y tiempos de producción más alto.
    
El primer diseño resultaba frágil, dado que el material que usábamos, filamento PLA, no era adecuado para las antenas, ya que se encuentran expuestas al sol, la lluvia y el viento.



![](images/6-portachain_v1.jpg)
![](images/7-portachain_v1.jpg)



La segunda versión de portachain fue diseñada teniendo en cuenta el aumento de espesor de la pieza para darle más solvencia, y el material, que fue reemplazado por filamento PETG.



![](images/8-portachain_v2.jpg)
![](images/9-portachain_v2.jpg)
![](images/10-portachain_v2_impresora.jpg)
![](images/11-portachain_v2_impresora.jpg)


    
Los primeros diseños no nos permitían sostener los cables de la forma esperada.

Luego descubrimos que para darle terminación y un mejor agarre, debíamos anexar al portachain un aro de caño de aluminio de 3/8 crimpeado, aportandole así la firmeza esperada para sujetar los cables.



![](images/12-portachain_v4.jpg)
![](images/13-portachain_v4.jpg)
![](images/14-aros.jpg)
![](images/15-plano_portachain_v4.png)
![](images/16-plano_portachain_v4.png)


    
<h3>
    <u>
        Pintura
    </u>
</h3>

Para darle terminación a las antenas, utilizamos pintura sintética.
Nuestra primera experiencia fue utilizando una pintura para automóviles sobre una capa de pintura antióxido.
Notamos que la misma tenía caracterísiticas como:

<ul>
    <li>
        Ser muy resistente
    </li>
    <li>
        Más espesor
    </li>
    <li>
        Mayor valor
    </li>
</ul>

Encontramos dificultades para lograr la dilusión justa para utilizarla, y no lograbamos una buena terminación.

Es por eso que decidimos probar con pintura "tres en uno" que tiene características como:

<ul>
    <li>
        Convertidor (trabaja sobre las partes oxidadas)
    </li>
    <li>
        Previene el óxido
    </li>
    <li>
        Esmalta las piezas
    </li>
</ul>


Por estas características y la facilidad para diluirse y su poder cubritivo, actualmente estamos utilizando esta pintura como revestimiento para nuestros modelos.
Para más información sobre el procedimiento, entrá <a href="/Como_hacer_una_antena.html">acá</a>.



    
<br>
    

<h3>
    <u>
        Antena terminada con sus partes plásticas
    </u>
</h3>
    
    

![](images/17-antena_pintada.jpg)
![](images/18-antena_pintada.jpg)



### Acoples para el diseño de antena direccional

Hemos desarrollado algunas partes complementarias a la guía de ondas con el fín de aumentar su directividad.
Los ultimos ensayos confirman que alcanza un promedio aproximado de 13dB en una dirección.

Los soportes de la parábola permiten añadir el reflector secundario de 16 pulgadas a la guía de ondas. La nariz también cubre el interior del tubo y sujeta el reflector primario en la zona focal de la parábola.
Solo la "nariz" tarda 5 horas en imprimirse, en total las piezas necesarias demoran casi 8 horas en materializarse.



![](images/19-portareflector.png)
![](images/20-soporte_parabaola.png)
![](images/21-waveguide_con_accesorios.png)




---

<img src="https://user-images.githubusercontent.com/104506596/191294248-aa22ad16-f991-412b-8d32-99e27614e7f2.png" alt="Logo NLnet: abstract logo of four people seen from above" height="70"><img src="https://nlnet.nl/image/logos/technologycommonstrust.svg" height="100">

<p>This project was funded through the <strong> <a href="https://nlnet.nl/useroperated/">User-Operated Internet</a> </strong> fund, a fund established by <a href="https://nlnet.nl">NLnet</a> made possible by financial support from the <a href="https://pkt.cash" rel="nofollow">PKT Community</a> <a href="https://pkt.cash/network-steward" rel="nofollow">The Network Steward</a> and stichting <a href="https://technologycommons.org">Technology Commons Trust</a>.</p> 

<p>Saludamos a les amigues de <a href="https://altermundi.net/">AlterMundi.</a></p>



