<!--
SPDX-FileCopyrightText: 2023 Tecnología de Raíz <tecnologiaderaiz@disroot.org>

SPDX-License-Identifier: CC-BY-NC-4.0
-->

# Prototipo de guía de ondas


<p>
En este material mostraremos los diferentes modelos de antenas que fuimos desarrollando hasta llegar al prototipo actual.
Describiremos algunas caracteristicas de cada antena, y un grafico de sus testeos realizado con un <a href="https://github.com/TecnologiadeRaiz/LoPALiR/tree/main/Mediciones">programa</a> diseñado para tal fin en una distancia de 1,1 km.

Nuestro escenario de pruebas se encuentra entre un pino muy alto en la localidad de Casa Grande y la parte alta de una casa en la localidad de Molinari.
</p>



![](images/1-mapa.jpeg)<br>
![](images/2-menu_con_informacion.png)



<h2>
    <u>
        Prototipo 1
    </u>
</h2>

<h3>
    Version 1:
</h3>

<p>
En la busqueda de una antena tipo guía de ondas, desarrollamos este prototipo; uno de los aspectos en los que trabajamos es la creación de un soporte para la antena y el montaje de los cable sobre la guía.
</p>

<p>
<b>
   Un primer intento de soporte fue este:
</b>
</p> 
 


![](images/3-cañonica.jpeg)



<p>
<b>
   Aprovechando un soporte existente, soldamos la guía de ondas al mismo.
</b>

   En este caso utilizamos un caño de 38mm de diámetro.
</p>

<br>

<ul>
    <li>
        Ventajas:
    </li>
</ul> 

<p>
La forma de sostener los cables en este prototipo era realizar una ranura en la guía de ondas y con ese material, sumando un caño de cobre, sostener el cable. Lo cual simplifica el montaje.
</p>
    
<ul>
    <li>
        Inconvenientes:
    </li>
</ul>

<p>
Por las caracteristicas del material, su peso y su forma, encontramos poco funcional este diseño de soporte; esto nos llevo a repensar como usar el material y la forma del soporte.

La ranura genera pérdida de radiación.

El diámetro del caño "corta" el paso de las frecuencias más bajas.
</p>



![](images/4-medicion_cañonica.png)



<hr>

<h3>
    Versión 2:
</h3>


<p>
<b>
   Probamos modificar la longitud de la guía de ondas, con un caño más largo.
</b>
</p>



![](images/5-cañonica_v2.jpeg)



<p>
   Modificamos en esta versión la forma de sujetar los cables, soldando a la guía de ondas un caño de cobre, crimpeandolo, y sellandolo con termocontraible.
</p>

<ul>
    <li>
        Ventajas:
	</li>
</ul>

<p>
   Robustez en el agarre
precisión en la posición final de los iluminadores.
</p>

<ul>
    <li>
        Inconvenientes:
    </li>
</ul>

<p>
   Utilizamos una soldadora autógena (oxígeno y acetileno) lo que aumenta la complejidad del taller y la dificultad para la soldadura.

También se agrega la posibilidad de generar "tensiones de juntura" entre los materiales, que podrían afectar el desempeño de la antena.
    
</p>
    


![](images/6-mediciones_cañonica-v2.png)



<hr>

<h2>
    <u>
       Prototipo 2 Cónica:
    </u>
</h2>


<h3>
    Versión 1:
</h3>

<p>
    <b>
        En esta versión, volvimos a sujetar los cables como en la versión anterior, soldando a la guía de ondas un caño de cobre, crimpeandolo, y sellandolo con termocontraible.
    </b>
   
</p>



![](images/7-Conica.jpeg)



<ul>
    <li>
        Ventajas:
    </li>
</ul>
<p>
    Notamos que agregarle el suplemento cónico mejora su rendimiento.
</p>

<ul>
    <li>
        Inconvenientes:
    </li>
</ul>
<p>
    Para este prototipo, utilizamos el soporte grande, que es muy pesado. Lo consideramos poco funcional.
</p>



![](images/8-mediciones_conica.png)

 

<h3>
    Versión 2:
</h3>

<p>
   <b>
       En este prototipo, acortamos el largo del caño, de 42 mm de diámetro interno, sumandole una terminación cónica realizada con chapa y soldada.

</b>
    
Para sostener los cables, diseñamos un agarre tipo "puente" con chapa soldado a la guía de ondas. 
</p>



![](images/9-conica_v2.jpeg)![](images/10-conica_v2.jpeg)



<ul>
    <li>
        Ventajas:
    </li>
</ul> 
<p>

   En relación al soporte al ser más liviano y compacto permite trasladarlo con más facilidad, siendo además más económico por tener menos material.
    
A esa versión de soporte, le hicimos perforaciones para aprovechar las medidas de las "u roscadas" que se consiguen con facilidad en ferreterías creando un soporte adaptable a dos medidas de caño. Esto le aporta accesibilidad al producto.
    
</p>
<p>
   Con este diseño, estamos utilizando el soporte como tapa de la guía de ondas.El primer prototipo de soporte soldado como tapa de la antena, tenía 10 cm de largo. 

Luego elegimos dejar lugar sólo para dos medidas de "u roscada", dando así la posibilidad de completar el soporte de acuerdo al caño donde se agarre.
    
</p>

<ul>
    <li>
        Inconvenientes:
    </li>
</ul> 

<p>
   En este prototipo, encontramos muchas dificultades para soldar los cables a la guía de ondas. Puede observarse el la gráfica de mediciones como el chain 2 (en verde) con fallas en la soldadura de la malla, tiene menor ganancia.
</p>



![](images/11-soportes.jpeg)
![](images/12-midiendo_u_roscada.jpeg)

![](images/13-mediciones_conica_v2.png)



<hr>

<h2>
    <u>
       Prototipo 3
    </u>
</h2>

<p>
    <b>
        En esta versión, volvimos a probar sujetar los cables con el modelo "puente" de chapa doblada, en un prototipo de guía de ondas más corto, con diámetro interno de 44mm, sin cono.
    </b>
   
</p>



![](images/14-puentecita.jpeg)
![](images/15-puentecita.jpeg)



<p>
   A pesar de obtener muy buenos resultados en el rendimiento de la antena, seguimos en la búsqueda de una forma de sujetar los cables más sencilla, conservando la longitud de la guía de ondas en el siguiente prototipo.
</p>


    
![](images/16-mediciones_puentecita.png)



<ul>
    <li>
        Ventajas:
    </li>
</ul>
<p>
    Obtuvimos buenos resultados en el rendimiento.
</p>
<ul>
    <li>
        Inconvenientes:
    </li>
</ul>
<p>
   Dificultad para soldar la malla de los cables al caño 
</p>

<h2>
    <u>
       Prototipo 4 Resina
    </u>
</h2>

<p>
    <b>
        En este prototipo, probamos sujetar los cables con una manguera de ø=1/8 de pulgada , transparente, rellena con resina epoxi. 
    </b>
 
</p>



![](images/17-resina.jpg)



<ul>
    <li>
        Ventajas:
    </li>
</ul>
<p>
    Los resultados en el rendimiento de la antena fueron buenos.
    
</p>

<ul>
    <li>
        Inconvenientes:
    </li>
</ul>

<p>
   Fragilidad en la unión de los cables con la guía de ondas. Algunas pruebas se despegaron, quedando inutilizables.
    
Dificultad para remover los restos de resina en caso de necesitar reparación.
    
Toxicidad del proceso y los residuos resultantes.
</p>



![](images/18-mediciones_resina.png)



<hr>

<h2>
    <u>
       Prototipo 5 Acople de partes plasticas
    </u>
</h2>

<p>
    <b>
        A través del <a href="https://github.com/TecnologiadeRaiz/LoPALiR/tree/main/Partes%20plasticas">diseño</a> en <a href="https://www.freecadweb.org/">Freecad</a>, logramos imprimir en 3d partes plásticas que permiten, acoplándose, sostener los cables de forma eficiente, rápida y duradera.
    </b>
    
</p>
    


![](images/19-waveguide_v4.jpg)
![](images/20-mediciones_waveguide_v4.png)



<ul>
    <li>
        Ventajas:
    </li>
</ul>

<p>
   Simpleza de montaje.
    
Robustez y precisión en el agarre de los cables.
</p>

<ul>
    <li>
        Inconvenientes:
    </li>
</ul>

<p>
   Acceso a impresiones 3D.
    
Necesidad de desarrollar impermeabilización en la unión de las partes plásticas.
</p>
