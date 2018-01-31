<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#sec-1">1. Descripción</a></li>
<li><a href="#sec-2">2. Uso</a></li>
<li><a href="#sec-3">3. Créditos</a></li>
</ul>
</div>
</div>


# Descripción<a id="sec-1" name="sec-1"></a>

Contiene varios paquetes con funciones para [Maxima](http://maxima.sourceforge.net/index.html)

Los paquetes en Maxima consisten en archivos terminados en `.mac`,
`mac`, `mc`, `demo`, `dem` y otros. Contienen código fuente de
Maxima. Estos paquetes se cargan con la funcion `load`.

Este repositorio contiene paquetes mayormente para métodos
numéricos. 

Los algoritmos han sido extraidos de [Numerical Analisis](https://www.amazon.com/Numerical-Analysis-Richard-L-Burden/dp/0538733519/ref%3Dpd_lpo_sbs_14_img_0/130-8412694-8766005?_encoding%3DUTF8&psc%3D1&refRID%3D4W546GVT1Z0X0CW72BCG). 

# Uso<a id="sec-2" name="sec-2"></a>

La funcion `load` carga código Maxima contenido en un archivo con la
extension `.mac` (paquetes). Por ejemplo, supongamos que tenemos un
archivo con código Maxima llamada *funcion.mac* ubicada en el
escritorio en una computadora GNU/Linux. Ejecute para cargar:

    load("/home/wegt/Desktop/funcion.mac");

Luego ya tendriamos, las funciones o instrucciones, a nuestra
disposición, y utilizarlos en Maxima, para el propósito que fueron
programados.

Asi de fácil se cargar archivos `.mac`. Observe que tiene que escribir
la ruta completa del archivo.

Consulte como [anexar una carpeta](https://github.com/wilsoneliseo/maxima/wiki/Anexar) para que sea reconocido por Maxima al
iniciar. Esto permite escribir la instruccion anterior de una forma
mas cómoda:

    load(funcion);

Sin añadir la ruta completa.

# Créditos<a id="sec-3" name="sec-3"></a>

Wilson S. Tubín.
