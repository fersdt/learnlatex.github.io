---
title: "Trabajando con LaTeX"
---

A diferencia de muchos programas, LaTeX no es una simple aplicación que contiene
"todo" en uno. En lugar de ello, tiene programas independientes que funcionan juntos.
A estos programas, podemos dividirlos en dos cosas que usted necesitará:

- Un _systema TeX_
- Un editor de texto (a menudo específico para LaTeX)

## Distribuciones del sistema {{ site.tex }}

Lo esencial para trabajar con LaTeX es disponer de un sistema TeX. Un sistema TeX es
un conjunto de programas y ficheros "en segundo plano" necesarios al funcionamiento 
de LaTeX, pero la mayor parte del tiempo no necesitará "ejecutarlos" directamente.   

Hay dos principales distribuciones del sistema TeX disponibles hoy en día,
[MiKTeX](https://www.miktex.org) y [TeX Live](https://tug.org/texlive). Ambas
disponibles para Windows, macOs y Linux.
MikTeX tiene un gran arraigo en Windows;
en macOS, TeX Live está incluida en una colección más amplia llamada [MacTeX](http://www.tug.org/mactex/).
[Cada distribución tiene sus ventajas](https://tex.stackexchange.com/questions/20036), y puede
que quiera echar vistazo al [sitio web de LaTeX Project 
para obtener más información](https://www.latex-project.org/get/).

Al estar TeX Live disponible en todas las plataformas habituales, y presentar algunas
ventajas en cuanto a rendimiento, le recomendamos que si no sabe qué distribución instalar,
elija TeX Live.

## Editores

Los ficheros de LaTeX son simplemente ficheros de texto sin formato, con lo que pueden ser 
editados con cualquier editor de texto. Sin embargo, es más conveniente utilizar
un editor de texto concebido para trabajar con LaTeX, ya que le dispondrá de funcionalidades
útiles como compilar sus ficheros, visualizador de PDF, y resaltado de sintaxis. Una
funcionalidad verdaderamente útil en los editores de textos modernos es SyncTex: poder
hacer clic en su código e ir a la posición correspondiente en el PDF y viceversa.   

Existen muchos editores de LaTeX que podemos esperar encontrar en esta lista: 
[lista exhaustiva en StackExchange](https://tex.stackexchange.com/questions/339/latex-editors-ides).
Un editor básico, [TeXworks](https://tug.org/texworks), está incluido en las distribuciones
TeX Live y MikTeX para Windows y Linux; y en macOS [TeXShop](https://pages.uoregon.edu/koch/texshop/)
viene incluido en MacTeX.  

Sea cual sea el editor que elija, le recomentamos instalarlo _después_ de instalar el 
sistema TeX, de forma que el editor "localice" el sistema TeX y lo configure automáticamente. 

## Trabajando en línea

Hoy en día existen potentes sitios web que le permiten evitar la
instalación de un sistema TeX y de un editor de LaTeX. Estos sitios web
funcionan permitiéndole editar el fichero directamente en la página web, y 
ejecutan LaTeX en segundo plano, para el mostrándole el resultado en PDF.

Algunos de estos sitios web combinan LaTeX con otras funcionalidades similares a las
de un procesador de textos, mientras que otros se focalizan en la visualización del 
código LaTeX y se asemejan a tener una instalación local de LaTeX. 

Hay sistemas que le permiten ejecutar LaTeX sin necesidad de registrarse, y nosotros
vamos a usar uno de ellos, 
[LaTeX CGI](https://latexcgi.xyz), que le permitirá
editar y probar los ejemplos que le daremos. Para trabajos más complejos, los mejores
sistema en línea requieren que se registre antes de usarlos. Esto permite conservar
su trabajo y también permite a los sition web de evitar estar sobrecargados. Hemos configurado
unos enlaces que le permiten editar los ejemplos usando [Overleaf](https://www.overleaf.com), 
uno de los mejores sitios en línea de LaTeX. Hay otros, por supuesto:  
[Papeeria](https://papeeria.com/) es uno de ellos.

## Ejercicio

Realice la instalación local de LaTeX _o_ cree una cuenta en un servicio de 
LaTeX en línea. Si utiliza una instación local, necesitará instalar también
un editor: le recomendamos comenzar con TeXworks o TeX Shop (ver la lista 
más arriba), y luego probar otros editores hasta que sepa con cual _usted_
trabaja mejor en LaTeX.

Será posible [realizar todos nuestros ejercicios en su explorador](help), pero queremos 
ayudarle a trabajar con documentos reales, con lo que ahora es el momento ideal
para dejarlo todo preparado.