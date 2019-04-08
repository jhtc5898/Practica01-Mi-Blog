# Practica01-Mi-Blog

 	
PRÁCTICA DE LABORATORIO
CARRERA: INGENIERIA DE SISTEMAS/COMPUTACION	ASIGNATURA: HYPERMEDIAL
NRO. PRÁCTICA:	1	TÍTULO PRÁCTICA: Resolución de problemas sobre HTML5
OBJETIVO
Entender y organizar de una mejor manera los sitios de web en Internet. Crear sitios web aplicando estándares actuales.
Desarrollar aplicaciones web interactivas y amigables al usuario.

















INSTRUCCIONES	
Estructurar un sitio web estático usando HTML5. El sitio web será informativo sobre un tema que será autoría del estudiante. El sitio web deberá contar con una página principal denominada index.html y debe contener al menos cinco páginas
*.HTML más. Todas las páginas contaran con un menú de navegación que permitirá al usuario moverse entre todas las páginas HTML.

Todas las páginas *.HTML deben estar estructuradas según el siguiente formato:

 
En donde, la etiqueta <header> deberá contener una imagen (logo) relacionada al tema elegido.

Además, la etiqueta <footer> deberá tener la información del estudiante como nombres completos, organización, correo (usar hipervínculo, mailto), teléfono (usar hipervínculo, tel), además deberá tener el símbolo de copyright junto a la leyenda de “Todos los derechos reservados”. Por ejemplo, © Todos los derechos
reservados
 

	Las páginas *.html deberán tener al menos una etiqueta <section>, <article> y
<aside>.

De igual manera, se pide que al menos una de las páginas dentro del contenido de la etiqueta <article>, tengan los siguientes requisitos:

•	Una tabla con la siguiente estructura:

 
•	Un video de YouTube (ver, etiqueta <iframe>).
•	Manejar listas ordenadas o desordenadas con al menos cinco ítems.
•	Tener al menos cinco etiquetas de texto que se encuentran en la figura 1- 16 del texto guía de la asignatura.

Asimismo, se pide que todos los artículos tengan al menos una imagen cada uno. Se pide que todas las imágenes están almacenadas en una carpeta llamada “images”. Por lo tanto, se debe trabajar con rutas relativas.

Finalmente, se pide que una de las páginas tenga al menos dos secciones (<section>) con tres artículos (<article>) cada sección. Luego, cada sección debe tener un encabezado (<header>), en donde, se ubicaran enlaces que permitan
navegar entre los artículos usando id’s (ver, página 63 del texto guía).

ACTIVIDADES POR DESARROLLAR
1. Crear un repositorio en GitHub con el nombre “Practica01 – Mi Blog”
2. Realizar un commit y push por cada requerimiento de los puntos antes descritos.
3. Al finalizar la práctica se debe validar todas las páginas HTML creadas usando el W3C Validator.
4. Luego, se debe crear el archivo README del repositorio de GitHub.
5.	Generar informe de los resultados en el formato de prácticas. Debe incluir:
a.	El desarrollo de cada uno de los puntos antes descritos así como las etiquetas HTML utilizadas para resolver cada punto.
b.	La evidencia de la correcta estructuración de las páginas HTML. Para lo cuál, se puede generar fotografías instantáneas (pantallazos).
c.	La evidencia de la validación de cada página HTML.
d.	El informe debe incluir conclusiones apropiadas.
e.	En el informe se debe incluir la información de GitHub (usuario y URL del repositorio de la práctica)
f.	En el informe se debe incluir la información de GitHub (usuario y URL del repositorio del Tutorial 01
- Curbside Thai)
g.	En el informe se debe incluir la firma digital del estudiante.
 

6. En el archivo README del repositorio debe constar la misma información del informe de resultados de la
práctica que se indica en el siguiente punto.

RESULTADO(S) OBTENIDO(S):
•	Tener el conocimiento suficiente para que el estudiante pueda entender y organizar de una mejor manera los sitios de web y de negocios en Internet
CONCLUSIONES:
•	Los estudiantes podrán organizar sitios web basados en el lenguaje de etiquetado HTML
RECOMENDACIONES:
•	Probar la solución de la práctica en al menos tres navegadores web; Google Chrome, Firefox y Safari



Docente: Ing. Gabriel León Paredes, PhD.
Firma:  






























CREACION DE UNA PAGINA WEB

Utilizaremos los siguientes componentes 
*Visual Estudio Code
*Un Navegador 
*Información

Etiquetas para la creación de la Pagina  index.html

 

Agregamos las siguientes líneas 

<title>Aprendiendo A Programar</title>
<meta charset="utf-8" />

La primera línea nos permite agregar un nombre a la pestaña de nuestra pagina 
De tal forma debemos agregar información Utf-8 que nos permite agregar cualquier carácter como la ñ o diferentes letras con tilde.

Debería quedar de la siguiente manera:

 




Para realizar la navegación de la pagina índex con imágenes itulizamos las siguientes etiquetas:
<nav>
      <a href="netbeans.html"><img src="images/netbeans.png" alt="netbeans"  /></a>
      <a href="python.html"><img src="images/python.jpg" alt="Python" /></a>
      <a href="c.html"><img src="images/c.png" alt="C" /></a>
      <a href="javascript.html"><img src="images/javascript.png" alt="JavaScript" /></a>
   </nav>


Importante: Debe encontrarse en el body para su funcionamiento correcto

Debería quedar de la siguiente manera:

 

Se nos presentara una pestaña con las diferentes imágenes cargadas. 

 
 

Etiquetas para la creación de la Pagina  netbeans.html

 
Para realizar la agregación de un video en HTML 5 es necesario de la etiqueta iframe ejemplo;

    <p>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/NcY70mPFM6Q" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </p>
    

Debería de presentarse de la siguiente manera en nuestra pagina 

 

De la misma forma para agregar un video en  python.html

 
Etiqueta de video:
<iframe width="560" height="315" src="https://www.youtube.com/embed/fVNPbmVnLKQ" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>
   

Creación de tablas en HTML
Una tabla simple
La primera etiqueta que te interesa es <table> </table>. Esta es la etiqueta que define el comienzo y final de una tabla.
Es una etiqueta de bloque, así que tendrá que situarse fuera de un párrafo. Ejemplo:

<table>
   <caption>Passengers of flight 377</caption>

    <tr>
       <th>Name</th>
       <th>Age</th>
       <th>Country</th>
   </tr>

    <tr>
       <td>Carmen</td>
       <td>33 years old</td>
       <td>Spain</td>
   </tr>
   <tr>
       <td>Michelle</td>
       <td>26 years old</td>
       <td>United States</td>
   </tr>
</table>
    
 
Tabla comparativa Diseñada con <table>
Código
<table>
        
                    <caption>Tabla De Popularidad</caption>
                    <tr>
                          <th> <p>Cantidad </p></th>
                          <th colspan="3" > <p>Popularidad </p> </th>
                        </tr>
                        <tr>
                          <th> <p> Lenguajes De Programacion </p></th>
                          <td>Netbeans</td>
                          <td>C++</td>
                        </tr>
                      
                        <tr>
                          <th>  <p>Primer año  </p> </th>
                          <td>38%</td>
                          <td>21%</td>
                        </tr>
                        <tr>
                          <th> <p> Segundo año</p></th>
                          <td>40%</td>
                          <td>50%</td>
                        </tr>
                        <tr>
                                <td colspan="4">Mejor Porcetaje Netbeans</td>
                            </tr>
 </table>

Resultado

  

La utilización de colspan="3"  nos permite  unir diferentes tablas  de tal forma logramos el siguiente resultado donde unimos la Cabedera 3. De esta forma podemos unir de diferentes formas una tabla. La etiqueta rowspan no permite unir celdas de forma vertical.
 

CORRECTA ESTRUCTURA DE LAS PAGINAS WEB


Para la creación de nuestro netbeans.html utilizamos la misma estructura presentada anteriormente

  

 

Presentacion Pagina

 


 




 

Presentacion de navegacion

 

 


Para la creación de nuestro python.html utilizamos la siguiente estructura: 



   

Presentación:















Para la creación de nuestro c.html utilizamos la siguiente estructura:

  
Presentacion:
 

Etiquetas Utilizadas en las diferentes paginas 

Lista de etiquetas utilizadas en las diferentes paginas .


1*-  
 
2*- 

3*-  

4*-  

5*-   


 

Validación De Paginas HTML
Validacion Pagina Index.html
 
Validacion Pagina netbeans.html

 













Validacion Pagina javascript.html

 



Validacion Pagina python.html

 










Validacion Pagina c.html

 
Validacion Pagina Contacto.html

 


Tutorial en el GitHub
https://github.com/jhtc5898/Tutorial-01
Mi Blog en el GitHub
https://github.com/jhtc5898/Practica01-Mi-Blog

Conclusiones:

Durante esta practica comprendimos de mejor manera el uso de las etiquetas en html las cuales mejoraron nuestro conocimiento sobre tablas imágenes y vínculos todo esto permitiendo tener un conocimiento mas profundo sobre html. 
El uso de vínculos mejora nuestra forma de ver una pagina web ya que se vuelve mas interactiva mejorando la forma de visualización del usuario.


 
Firma Del Estudiante

