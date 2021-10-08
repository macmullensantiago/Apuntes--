# Apuntes--

## ForEach

    * The forEach() method calls a function once for each element in an array, in order.

     forEach() is not executed for array elements without values.

    * The forEach() method executes a provided function once for each array element.

    * Foreach (de la palabra inglesa for each = para cada uno) es un bloque constructivo de los lenguajes de programación para recorrer los elementos de una colección. Foreach        se utiliza por lo general en lugar de una norma para la declaración. A diferencia de otras construcciones de bucle, los bucles foreach por lo general no mantienen contra-        indicación explícita, que esencialmente dice "haga esto a todo en este juego" en lugar de "hacer esto x veces." Esto evita posibles errores off-by-one y hace el código más      fácil de leer. En lenguajes orientados a objetos un iterador, aunque implícito, a menudo se utiliza como medio de recorrido. Este bucle, implementado a partir de las            versiones de PHP4, nos ayuda a recorrer los valores de un array, lo cual puede resultar muy útil por ejemplo para efectuar una lectura rápida del mismo. Recordemos que un        array es una variable que guarda un conjunto de elementos (valores) catalogados por claves

## addEventListener 

    * The JavaScript addEventListener() method allows you to set up functions to be called when a specified event happens, such as when a user clicks a button.
  
  ### Events and Events Handler 
    
     *  Understanding Events and Event Handlers
        Events are actions that happen when the user or browser manipulates a page. They play an important role as they can cause elements of a web page to change dynamically.

        For example, when the browser finishes loading a document, then a load event occurred. If a user clicks a button on a page, then a click event has happened.

        Many events can happen once, multiple times, or never. You also may not know when an event will happen, especially if it is user generated.

        In these scenarios, you need an event handler to detect when an event happens. This way, you can set up code to react to events as they happen on the fly.

  ### Syntax
  
    addEventListener() Syntax
    Here's the syntax:

    target.addEventListener(event, function, useCapture)
    
    * target: the HTML element you wish to add your event handler to. This element exists as part of the Document Object Model (DOM)
    * event: a string that specifies the name of the event. We already mentioned load and click events.
    * function: specifies the function to run when the event is detected. This is the magic that can allow your web pages to change dynamically.
    
 ## querySelector
 
      * The querySelector() method returns the first child element that matches a specified CSS selector(s) of an element.
   
      * Retorna el primer elemento que cumpla con el criterio dado. Puede ser invocada sobre el document o sobre algún elemento. En caso de usarse sobre un elemento, las                 búsqueda se limita a los hijos de ese elemento. Si la búsqueda no encuentra nada, retorna null.
      
      * querySelectorAll
        Retorna todos los elementos que cumplan con el criterio dado. Al igual que querySelector puede ser invocada sobre el document o sobre algún elemento.
       
      * El método querySelector () de JavaScript le permite recuperar un elemento del DOM, o la página web, usando un selector de CSS. Este método viene con una función hermana         llamada querySelectorAll () que selecciona todos los elementos que coinciden con un selector particular del DOM.

        Estos dos métodos son increíblemente versátiles. Esto se debe a que la sintaxis del selector de CSS le permite seleccionar cualquier elemento de una página web.
        
  ### getElementById
  
      * getElementById
       Retorna el primer elemento con el id especificado, es en muchos sentidos equivalente a hacer, querySelector('#elId'). Osea que retorna null si no hay elementos con dicho        Id.
      
     * The getElementById() method retrieves an element based on its ID attribute, hence the name.
        This method is more restrictive than querySelector because you can only retrieve elements based on their particular ID.
        You would use this method if you only want to retrieve one element from the web page. This is because HTML IDs must be unique to a particular element. You cannot use an         ID to refer to two elements on the web page.
        
   ## Upload a Proyect to GitHub
    
    * https://lab.github.com/
    * https://www.freecodecamp.org/news/the-beginners-guide-to-git-github/
    * https://www.youtube.com/watch?v=MJUJ4wbFm_A
    * https://www.youtube.com/watch?v=eulnSXkhE7I
   
   ## Differences between Software Engineer, Web developer and Programmer
   
   * There are a few ways to spot the differences among software engineer, web developer, and programmer roles.
    
       + Web developers are focused on creating browser apps with a combination of client-side and server-side programming languages. Generally speaking, they are involved in            designing interactive websites and building user-facing applications.
    
       + Software engineers are more likely to work on computer systems as a whole. They develop standalone programs and apps to help users perform various activities. For the            most part, they program, document, test, and maintain software by utilizing the best practices in DevOps.
       
   * Front-End & Back-End
   
       + The only real distinction you have to make is the one between front-end and back-end programming — whether you’re designing surface-level UI and user-centric                    applications or running hidden processes inside a database server.
       
   - "At the end of the day, we're all trying to solve business problems with code."
