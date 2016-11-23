# Task_Lan_Markup_UT_02
##Tarea 2ª unidad - LMSGI - ASIX 1º - Lunar landing 2

###Notas sobre diseño  
   Partiendo del diseño primero (_Lunar Landing 1_), se han realizado diversas modificaciones, atendiendo a las futuras posibilidades de creación de un juego.
   La mayor y principal, tratando de convertir las páginas en formato flexible o _**responsive**_, ha sido añadir en el encabezamiento de estas una etiqueta: '_**meta name="viewport" content="width=device−width, initial−scale=1.0**_', con la que re-escalamos el contenido, una solución recogida, tras mucho tutorial y ejemplos vistos, de [CSS Blog.es](http://www.cssblog.es/crear-diseno-responsive-en-3-pasos/) y estudiado después en [w3schools](http://www.w3schools.com/css/css_rwd_viewport.asp).
   Se trata de un método iniciado en HTML 5, que consite en aplicar un zoom al contenido, adaptándolo al ancho (_width_) del dispositivo, ya sea teléfono mobil, tableta, laptop, etc.  
   _**No se consige una respuesta todo lo correcta que quisieramos -alguna parte del contenido no re-escala convenientemente-**_ pero no queda más tiempo para profundizar...en adelante, mejorará.  
  
  
   Se mantiene la imagen al pie de la superficie lunar (_sonda LRO - [NASA](www.nasa.gov/multimedia/imagegallery/index.html)_), en origen con la curva natural del satélite, para convertirla en plana y no tener problemas de transparencia con el fondo, a la que se añade el selenita/alien, este en _.svg_, formato elegido también para la nave espacial, ambas de [Open Clipart](openclipart.org).  

Los cambios, respecto a la primera versión, se explican a continuación:  

1. Página principal (pág. base)  
    Para el contenido HTML, dos contenedores '_DIV_' (antes sólo uno), con el fin de mejorar el posicionamiento de las parts contenidas:  
   * Panel de información (_**se mantiene**_)  
       * Una tabla de 2 x 5 elementos: 
          * Columna izquierda: Nombre de dato
          * Columna derecha: Valor
   * Nave espacial (_**se mantiene**_)
   * Panel de enlaces/opciones es ahora de acciones (_**cambia**_ para futuras acciones)  
      * Una tabla de 2 x 5 elementos: 
          * Columna izquierda: Acción a realizar
          * Columna derecha: Botón que la realiza  
  
       La forma de presentación del contenido se especifica como _block_ en su contenedor '_DIV_'.  
       
2. Página _Como jugar_ (_**se mantiene**_)  
    Se mantiene el formato de la principal, con la excepción de la nave, que desaparece, para aprovechar el espacio  
    donde detallar en que consiste y como interactuar con el juego (futuro proyecto).  
3. Página _About_ (_**cambia**_)  
    También mantenemos el formato, desaparecen tanto del panel de datos como el anterior de enlaces/opciones (_ahora de acciones_), aprovechando todo el espacio para los detalles sobre la autoría, recursos, datos de contacto, etc., del proyecto.
4. **Menú de enlaces/opciones**  
   Aparece como barra de menú horizotal en la parte superior en todas las páginas. Es evidente que parece más acertado.
    

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
 * Panel de acciones:
     * Acción y botón que la inicia (_x 5_)
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
  * Sin panel de datos ni de acciones. Desaparece también la nave.

Cabe añadir a lo citado al inicio que, además de la etiqueta '_**meta name="viewport"**_', se ha modificado el atributo width (_**width: auto**_) en los elementos que se necesitaba, para ajustarlos a los cambios de tamaño. También se añade codigo para fijar las imágenes de pie de página (_**bottom: 0;  left: 0;**_) y nave espacial (_**top: 5%; left: 0;**_).  
Código **VALIDADO**, tanto HTML como CSS.
