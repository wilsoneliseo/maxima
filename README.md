#+TITLE:     Paquetes Para Maxima
* Descripción
Contiene varios paquetes con funciones para [[http://maxima.sourceforge.net/index.html][Maxima]]

Los paquetes en Maxima consisten en archivos terminados en ~.mac~,
~mac~, ~mc~, ~demo~, ~dem~ y otros. Contienen código fuente de
Maxima. Estos paquetes se cargan con la funcion ~load~.

Este repositorio contiene paquetes mayormente para métodos
numéricos. 

Los algoritmos han sido extraidos de [[https://www.amazon.com/Numerical-Analysis-Richard-L-Burden/dp/0538733519/ref%3Dpd_lpo_sbs_14_img_0/130-8412694-8766005?_encoding%3DUTF8&psc%3D1&refRID%3D4W546GVT1Z0X0CW72BCG][Numerical Analisis]]. 
  
* Uso
La funcion ~load~ carga código Maxima contenido en un archivo con la
extension ~.mac~ (paquetes). Por ejemplo, supongamos que tenemos un
archivo con código Maxima llamada /funcion.mac/ ubicada en el
escritorio en una computadora GNU/Linux. Ejecute para cargar:

#+BEGIN_EXAMPLE
load("/home/wegt/Desktop/funcion.mac");
#+END_EXAMPLE

Luego ya tendriamos, las funciones o instrucciones, a nuestra
disposición, y utilizarlos en Maxima, para el propósito que fueron
programados.

Asi de fácil se cargar archivos ~.mac~. Observe que tiene que escribir
la ruta completa del archivo.

Consulte como anexar una carpeta para que sea reconocido por Maxima al
iniciar. Esto permite escribir la instruccion anterior de una forma
mas cómoda:

#+BEGIN_EXAMPLE
load(funcion);
#+END_EXAMPLE

Sin añadir la ruta completa.

* Créditos
  Wilson S. Tubín.
