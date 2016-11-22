# Task_Lan_Markup_UT_02
##Tarea 2ª unidad - LMSGI - ASIX 1º - Lunar landing  

###Notas sobre diseño  
   Para la imagen de fondo se ha seleccionado una imagen vectorial (_.svg_) convertida a formato _.gif_,  
de poco 'peso' (menos de 3KB), ya que conforma a modo de mosaico el fondo de la página.  
   La imagen al pie se ha formado manipulando una fotografía, en formato _.jpg_, de la superficie lunar  
(_sonda LRO - [NASA](www.nasa.gov/multimedia/imagegallery/index.html)_), en origen con la curva natural del satélite, para convertirla en plana y no tener problemas de transparencia con el fondo, a la que se añade el selenita/alien, este en _.svg_, formato elegido también para la nave espacial, ambas de [Open Clipart](openclipart.org).  

1. Página principal (pág. base)  
    Para el contenido HTML, un único contenedor '_DIV_',  comprende:  
   * Panel de información
       * Una tabla de 2 x 5 elementos: 
          * Columna derecha: Nombre de dato
          * Columna izquierda: Valor
   * Nave espacial
   * Panel de enlaces/opciones
      * Una lista de los enlaces relacionados con el juego  
  
       La forma de presentación del contenido se especifica como _block_, de modo que ocupan el ancho que necesita  
       cada elemento, repartiendolos según necesita cada elemento, fijados, de momento, en posición estatica dentro  
       de la página.  
2. Página _Como jugar_
    Se mantiene el formato de la principal, con la excepción de la nave, que desaparece, para aprovechar el espacio  
    donde detallar en que consiste y como interactuar con el juego (futuro proyecto).
3. Página _About_
    También mantenemos el formato, con la excepción del panel de datos, que desaparece. Como es habitual, se dan  
    detalles sobre la autoría, recursos, datos de contacto, etc., del proyecto.
    

###Composición  

1. Página _index_:
 * Un fondo estrellado (espacio exterior).  
 * La superficide lunar (zona de alunizaje), con espectador incluido, al pie.  
 * Nave espacial simulando llegada a la luna.  
 * Panel de datos de vuelo:
     * Posición
     * Altitud
     * Velocidad
     * Fuel (combustible)
     * Time (hora o tiempo de descenso)
 * Menú de enlaces:
     * Home (enlace a pág. principal)
     * Inicio Juego (donde comienza de cero)-inactiva-
     * Pausar Juego (detiene momentaneamente)-inactiva-
     * Como Jugar (instrucciones)
     * About (detalles de creacion y diseño)  

2. Página _Como jugar_:
  * Brebe descripción del escenario de juego
  * Espacio para incorporar futuras instrucciones  

3. Página _About_:
  * Información breve sobre diseño y recursos
  * Contacto
  * Sin panel de opciones
