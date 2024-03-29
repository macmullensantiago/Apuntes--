# Apuntes--

# Think like a Computer Scientist

  # Linux
   * https://wildwesthackinfest.com/wp-content/uploads/2020/08/Linux_and_security_basics_hands_on_202008172248.pdf

  # HTML
    * At its heart, HTML is a language made up of elements, which can be applied to pieces of text to give them different meaning in a document (Is it a paragraph? Is it a bulleted list? Is it part of a table?), structure a document into logical sections (Does it have a header? Three columns of content? A navigation menu?), and embed content such as images and videos into a page. This module will introduce the first two of these and introduce fundamental concepts and syntax you need to know to understand HTML.
    * HTML stands for Hyper Text Markup Language
      HTML is the standard markup language for creating Web pages
      HTML describes the structure of a Web page
      HTML consists of a series of elements
      HTML elements tell the browser how to display the content
      HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.
      
      The <!DOCTYPE html> declaration defines that this document is an HTML5 document
      The <html> element is the root element of an HTML page
      The <head> element contains meta information about the HTML page
      The <title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
      The <body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
      The <h1> element defines a large heading
      The <p> element defines a paragraph

  # CSS
    * Like HTML, CSS is not a programming language. It's not a markup language either. CSS is a style sheet language. CSS is what you use to selectively style HTML elements.  
    * Cascading Style Sheets (CSS) is used to format the layout of a webpage.

    With CSS, you can control the color, font, the size of text, the spacing between elements, how elements are positioned and laid out, what background images or background colors are to be used, different displays for different devices and screen sizes, and much more!
    
    * CSS can be added to HTML documents in 3 ways:

      Inline - by using the style attribute inside HTML elements
      Internal - by using a <style> element in the <head> section
      External - by using a <link> element to link to an external CSS file
      
   * CSS Selectors
   
      CSS selectors are used to "find" (or select) the HTML elements you want to style.

      We can divide CSS selectors into five categories:

      Simple selectors (select elements based on name, id, class)
      Combinator selectors (select elements based on a specific relationship between them)
      Pseudo-class selectors (select elements based on a certain state)
      Pseudo-elements selectors (select and style a part of an element)
      Attribute selectors (select elements based on an attribute or attribute value)
      
    * https://www.lesliefranke.com/files/reference/csscheatsheet.html
    
      ### The src Attribute
          The required src attribute specifies the path (URL) to the image.
          
      ### The alt Attribute
          The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

            ## Horizontal List with CSS

          HTML lists can be styled in many different ways with CSS.

          One popular way is to style a list horizontally, to create a navigation menu:

          Example
          <!DOCTYPE html>
          <html>
          <head>
          <style>
          ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            overflow: hidden;
            background-color: #333333;
          }

          li {
            float: left;
          }

          li a {
            display: block;
            color: white;
            text-align: center;
            padding: 16px;
            text-decoration: none;
          }

          li a:hover {
            background-color: #111111;
          }
          </style>
          </head>
          <body>

          <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#news">News</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#about">About</a></li>
          </ul>

          </body>
          </html>

      ### The id attribute 
          * The id attribute is used to point to a specific style declaration in a style sheet. It is also used by JavaScript to access and manipulate the element with the specific id.
          * The id attribute is used to specify a unique id for an HTML element
            The value of the id attribute must be unique within the HTML document
            The id attribute is used by CSS and JavaScript to style/select a specific element
            The value of the id attribute is case sensitive
            The id attribute is also used to create HTML bookmarks
            JavaScript can access an element with a specific id with the getElementById() method
            
    ### Different types of selectors
            There are many different types of selectors. The examples above use element selectors, which select all elements of a given type. But we can make more specific selections as well. Here are some of the more common types of selectors:

            Selector name	What does it select	Example
            Element selector (sometimes called a tag or type selector)	All HTML elements of the specified type.	p
            selects <p>
            ID selector	The element on the page with the specified ID. On a given HTML page, each id value should be unique.	#my-id
            selects <p id="my-id"> or <a id="my-id">
            Class selector	The element(s) on the page with the specified class. Multiple instances of the same class can appear on a page.	.my-class
            selects <p class="my-class"> and <a class="my-class">
            Attribute selector	The element(s) on the page with the specified attribute.	img[src]
            selects <img src="myimage.png"> but not <img>
            Pseudo-class selector	The specified element(s), but only when in the specified state. (For example, when a cursor hovers over a link.)	a:hover
            selects <a>, but only when the mouse pointer is hovering over the link.

  # JavaScript
  
        ## JavaScript is a programming language that allows you to implement complex things on web pages. Every time a web page does more than just sit there and display static information for you to look at—displaying timely content updates, interactive maps, animated 2D/3D graphics, scrolling video jukeboxes, or more—you can bet that JavaScript is probably involved.
        
        ## Variable	Explanation	Example
          String	This is a sequence of text known as a string. To signify that the value is a string, enclose it in single quote marks.	let myVariable = 'Bob';
          Number	This is a number. Numbers don't have quotes around them.	let myVariable = 10;
          Boolean	This is a True/False value. The words true and false are special keywords that don't need quote marks.	let myVariable = true;
          Array	This is a structure that allows you to store multiple values in a single reference.	let myVariable = [1,'Bob','Steve',10];
          Refer to each member of the array like this:
          myVariable[0], myVariable[1], etc.
          Object	This can be anything. Everything in JavaScript is an object and can be stored in a variable. Keep this in mind as you learn.	let myVariable = document.querySelector('h1');
          All of the above examples too.
          
        ## Functions
            Functions are a way of packaging functionality that you wish to reuse. It's possible to define a body of code as a function that executes when you call the function name in your code. This is a good alternative to repeatedly writing the same code. You have already seen some uses of functions. 

        ## The <script> Tag
            In HTML, JavaScript code is inserted between <script> and </script> tags.

            Example
            <script>
            document.getElementById("demo").innerHTML = "My First JavaScript";
            </script>
            
        ## A JavaScript function is a block of JavaScript code, that can be executed when "called" for.

          For example, a function can be called when an event occurs, like when the user clicks a button.
          
        ##  var	        Declares a variable
            let	        Declares a block variable
            const	      Declares a block constant
            if	        Marks a block of statements to be executed on a condition
            switch	    Marks a block of statements to be executed in different cases
            for	        Marks a block of statements to be executed in a loop
            function	  Declares a function
            return	    Exits a function
            try	        Implements error handling to a block of statements
            
            * In a programming language, variables are used to store data values.
            
            * JavaScript strings are for storing and manipulating text.
            
         ##  What is this?
             In JavaScript, the this keyword refers to an object.

             Which object depends on how this is being invoked (used or called).
             
         ## Why Use Arrays?
            If you have a list of items (a list of car names, for example), storing the cars in single variables could look like this:

            let car1 = "Saab";
            let car2 = "Volvo";
            let car3 = "BMW";
            
         ## JavaScript Regular Expressions
            A regular expression is a sequence of characters that forms a search pattern.

            The search pattern can be used for text search and text replace operations.
            
        ## DOM - Document Object Model
            * The DOM (Document Object Model) is an API that represents and interacts with any HTML or XML document. The DOM is a document model loaded in the browser and representing the document as a node tree, where each node represents part of the document (e.g. an element, text string, or comment).
            * The Document Object Model (DOM) connects web pages to scripts or programming languages by representing the structure of a document—such as the HTML representing a web page—in memory. 
            * How to use JavaScript to modify a website
  
        ## What is JSON? 
            * JSON = JavaScript Object Notation

            // Object format

            const book = {
              title: "1984",
              author: "George Orwell",
              isavailable: false,
              };

            // Converted to JSON
            const bookJSON = JSON.stringify(bookObbj);
            console.log(bookJSON);
            
            ## API
              * An API (Application Programming Interface) is a set of features and rules that exist inside a software program (the application) enabling interaction with it through software - as opposed to a human user interface. The API can be seen as a simple contract (the interface) between the application offering it and other items, such as third party software or hardware.

                In Web development, an API is generally a set of code features (e.g. methods, properties, events, and URLs) that a developer can use in their apps for interacting with components of a user's web browser, or other software/hardware on the user's computer, or third party websites and services.
                
              * An application programming interface (API) is a way for two or more computer programs to communicate with each other. It is a type of software interface, offering a service to other pieces of software.[1] A document or standard that describes how to build or use such a connection or interface is called an API specification. A computer system that meets this standard is said to implement or expose an API. The term API may refer either to the specification or to the implementation.
              
              * A synchronous API call is a design pattern where the call site is blocked while waiting for the called code to finish.[41] With a asynchronous API call, however, the call site is not blocked while waiting for the called code to finish, and instead the calling thread is notified when the reply arrives.
              
            ## Object-oriented programming (OOP) 
            * Object-oriented programming (OOP) is a programming paradigm based on the concept of "objects", which can contain data and code. The data is in the form of fields (often known as attributes or properties), and the code is in the form of procedures (often known as methods).
            
            * Objects and classes
                Languages that support object-oriented programming (OOP) typically use inheritance for code reuse and extensibility in the form of either classes or prototypes. Those that use classes support two main concepts:

                Classes – the definitions for the data format and available procedures for a given type or class of object; may also contain data and procedures (known as class methods) themselves, i.e. classes contain the data members and member functions
                Objects – instances of classes
                Objects sometimes correspond to things found in the real world. For example, a graphics program may have objects such as "circle", "square", "menu". An online shopping system might have objects such as "shopping cart", "customer", and "product".[20] Sometimes objects represent more abstract entities, like an object that represents an open file, or an object that provides the service of translating measurements from U.S. customary to metric.

                Each object is said to be an instance of a particular class (for example, an object with its name field set to "Mary" might be an instance of class Employee). Procedures in object-oriented programming are known as methods; variables are also known as fields, members, attributes, or properties. This leads to the following terms:

                Class variables – belong to the class as a whole; there is only one copy of each one
                Instance variables or attributes – data that belongs to individual objects; every object has its own copy of each one
                Member variables – refers to both the class and instance variables that are defined by a particular class
                Class methods – belong to the class as a whole and have access to only class variables and inputs from the procedure call
                Instance methods – belong to individual objects, and have access to instance variables for the specific object they are called on, inputs, and class variables
                Objects are accessed somewhat like variables with complex internal structure, and in many languages are effectively pointers, serving as actual references to a single instance of said object in memory within a heap or stack. They provide a layer of abstraction which can be used to separate internal from external code. External code can use an object by calling a specific instance method with a certain set of input parameters, read an instance variable, or write to an instance variable. Objects are created by calling a special type of method in the class known as a constructor. A program may create many instances of the same class as it runs, which operate independently. This is an easy way for the same procedures to be used on different sets of data.

                Object-oriented programming that uses classes is sometimes called class-based programming, while prototype-based programming does not typically use classes. As a result, significantly different yet analogous terminology is used to define the concepts of object and instance.
            
            ## Data Structures
                * Data structures 
                     Data Structures are basically just that - they are structures which can hold some data together. In other words, they are used to store a collection of related data.

                There are four built-in data structures in Python - list, tuple, dictionary and set. We will see how to use each of them and how they make life easier for us.

              * List
                  A list is a data structure that holds an ordered collection of items i.e. you can store a sequence of items in a list. This is easy to imagine if you can think of a shopping list where you have a list of items to buy, except that you probably have each item on a separate line in your shopping list whereas in Python you put commas in between them.

                  The list of items should be enclosed in square brackets so that Python understands that you are specifying a list. Once you have created a list, you can add, remove or search for items in the list. Since we can add and remove items, we say that a list is a mutable data type i.e. this type can be altered.
                  
                * Objects And Classes
                    Although I've been generally delaying the discussion of objects and classes till now, a little explanation is needed right now so that you can understand lists better. We will explore this topic in detail in a later chapter.

                    A list is an example of usage of objects and classes. When we use a variable i and assign a value to it, say integer 5 to it, you can think of it as creating an object (i.e. instance) i of class (i.e. type) int. In fact, you can read help(int) to understand this better.

                    A class can also have methods i.e. functions defined for use with respect to that class only. You can use these pieces of functionality only when you have an object of that class. For example, Python provides an append method for the list class which allows you to add an item to the end of the list. For example, mylist.append('an item') will add that string to the list mylist. Note the use of dotted notation for accessing methods of the objects.

                    A class can also have fields which are nothing but variables defined for use with respect to that class only. You can use these variables/names only when you have an object of that class. Fields are also accessed by the dotted notation, for example, mylist.field.

               * Tuple
                    Tuples are used to hold together multiple objects. Think of them as similar to lists, but without the extensive functionality that the list class gives you. One major feature of tuples is that they are immutable like strings i.e. you cannot modify tuples.

                    Tuples are defined by specifying items separated by commas within an optional pair of parentheses.

                    Tuples are usually used in cases where a statement or a user-defined function can safely assume that the collection of values (i.e. the tuple of values used) will not change.
                  
               * Dictionary
                    A dictionary is like an address-book where you can find the address or contact details of a person by knowing only his/her name i.e. we associate keys (name) with values (details). Note that the key must be unique just like you cannot find out the correct information if you have two persons with the exact same name.

                    Note that you can use only immutable objects (like strings) for the keys of a dictionary but you can use either immutable or mutable objects for the values of the dictionary. This basically translates to say that you should use only simple objects for keys.

                    Pairs of keys and values are specified in a dictionary by using the notation d = {key1 : value1, key2 : value2 }. Notice that the key-value pairs are separated by a colon and the pairs are separated themselves by commas and all this is enclosed in a pair of curly braces.

                    Remember that key-value pairs in a dictionary are not ordered in any manner. If you want a particular order, then you will have to sort them yourself before using it.

                    The dictionaries that you will be using are instances/objects of the dict class.
                    
               * Sequence
                    Lists, tuples and strings are examples of sequences, but what are sequences and what is so special about them?

                    The major features are membership tests, (i.e. the in and not in expressions) and indexing operations, which allow us to fetch a particular item in the sequence directly.

                    The three types of sequences mentioned above - lists, tuples and strings, also have a slicing operation which allows us to retrieve a slice of the sequence i.e. a part of the sequence.
               * Set
                    Sets are unordered collections of simple objects. These are used when the existence of an object in a collection is more important than the order or how many times it occurs.

                    Using sets, you can test for membership, whether it is a subset of another set, find the intersection between two sets, and so on.
               * References
                    When you create an object and assign it to a variable, the variable only refers to the object and does not represent the object itself! That is, the variable name points to that part of your computer's memory where the object is stored. This is called binding the name to the object.

                    Generally, you don't need to be worried about this, but there is a subtle effect due to references which you need to be aware of:
              * Strings
                    We have already discussed strings in detail earlier. What more can there be to know? Well, did you know that strings are also objects and have methods which do everything from checking part of a string to stripping spaces? In fact, you've already been using a string method... the format method!

                    The strings that you use in programs are all objects of the class str. Some useful methods of this class are demonstrated in the next example. For a complete list of such methods, see help(str).
                    
            ## Object Oriented Programming
                  In all the programs we wrote till now, we have designed our program around functions i.e. blocks of statements which manipulate data. This is called the procedure-oriented way of programming. There is another way of organizing your program which is to combine data and functionality and wrap it inside something called an object. This is called the object oriented programming paradigm. Most of the time you can use procedural programming, but when writing large programs or have a problem that is better suited to this method, you can use object oriented programming techniques.

                  Classes and objects are the two main aspects of object oriented programming. A class creates a new type where objects are instances of the class. An analogy is that you can have variables of type int which translates to saying that variables that store integers are variables which are instances (objects) of the int class.
                  Objects can store data using ordinary variables that belong to the object. Variables that belong to an object or class are referred to as fields. Objects can also have functionality by using functions that belong to a class. Such functions are called methods of the class. This terminology is important because it helps us to differentiate between functions and variables which are independent and those which belong to a class or object. Collectively, the fields and methods can be referred to as the attributes of that class.

Fields are of two types - they can belong to each instance/object of the class or they can belong to the class itself. They are called instance variables and class variables respectively.

A class is created using the class keyword. The fields and methods of the class are listed in an indented block.

            ### Classes
                The simplest class possible is shown in the following example (save as oop_simplestclass.py).

                class Person:
                    pass  # An empty block

                p = Person()
                print(p)
                
            ### Methods
                  We have already discussed that classes/objects can have methods just like functions except that we have an extra self variable. We will now see an example (save as oop_method.py).

                  class Person:
                      def say_hi(self):
                          print('Hello, how are you?')

                  p = Person()
                  p.say_hi()
                  # The previous 2 lines can also be written as
                  # Person().say_hi()
                  
            ### Inheritance
                  One of the major benefits of object oriented programming is reuse of code and one of the ways this is achieved is through the inheritance mechanism. Inheritance can be best imagined as implementing a type and subtype relationship between classes.

                  Suppose you want to write a program which has to keep track of the teachers and students in a college. They have some common characteristics such as name, age and address. They also have specific characteristics such as salary, courses and leaves for teachers and, marks and fees for students.

                  You can create two independent classes for each type and process them but adding a new common characteristic would mean adding to both of these independent classes. This quickly becomes unwieldy.

                  A better way would be to create a common class called SchoolMember and then have the teacher and student classes inherit from this class, i.e. they will become sub-types of this type (class) and then we can add specific characteristics to these sub-types.

                  There are many advantages to this approach. If we add/change any functionality in SchoolMember, this is automatically reflected in the subtypes as well. For example, you can add a new ID card field for both teachers and students by simply adding it to the SchoolMember class. However, changes in the subtypes do not affect other subtypes. Another advantage is that you can refer to a teacher or student object as a SchoolMember object which could be useful in some situations such as counting of the number of school members. This is called polymorphism where a sub-type can be substituted in any situation where a parent type is expected, i.e. the object can be treated as an instance of the parent class.

                  Also observe that we reuse the code of the parent class and we do not need to repeat it in the different classes as we would have had to in case we had used independent classes.

                  The SchoolMember class in this situation is known as the base class or the superclass. The Teacher and Student classes are called the derived classes or subclasses.

                  We will now see this example as a program (save as oop_subclass.py):

                  class SchoolMember:
                      '''Represents any school member.'''
                      def __init__(self, name, age):
                          self.name = name
                          self.age = age
                          print('(Initialized SchoolMember: {})'.format(self.name))

                      def tell(self):
                          '''Tell my details.'''
                          print('Name:"{}" Age:"{}"'.format(self.name, self.age), end=" ")


                  class Teacher(SchoolMember):
                      '''Represents a teacher.'''
                      def __init__(self, name, age, salary):
                          SchoolMember.__init__(self, name, age)
                          self.salary = salary
                          print('(Initialized Teacher: {})'.format(self.name))

                      def tell(self):
                          SchoolMember.tell(self)
                          print('Salary: "{:d}"'.format(self.salary))


                  class Student(SchoolMember):
                      '''Represents a student.'''
                      def __init__(self, name, age, marks):
                          SchoolMember.__init__(self, name, age)
                          self.marks = marks
                          print('(Initialized Student: {})'.format(self.name))

                      def tell(self):
                          SchoolMember.tell(self)
                          print('Marks: "{:d}"'.format(self.marks))

                  t = Teacher('Mrs. Shrividya', 40, 30000)
                  s = Student('Swaroop', 25, 75)

                  # prints a blank line
                  print()

                  members = [t, s]
                  for member in members:
                      # Works for both Teachers and Students
                      member.tell()
                      
            ### The if statement
                The if statement is used to check a condition: if the condition is true, we run a block of statements (called the if-block), else we process another block of statements (called the else-block). The else clause is optional.
                
            ### The while Statement
                The while statement allows you to repeatedly execute a block of statements as long as a condition is true. A while statement is an example of what is called a looping statement. A while statement can have an optional else clause.
                
            ### The for loop
                The for..in statement is another looping statement which iterates over a sequence of objects i.e. go through each item in a sequence. We will see more about sequences in detail in later chapters. What you need to know right now is that a sequence is just an ordered collection of items.
                
            ### The break Statement
                The break statement is used to break out of a loop statement i.e. stop the execution of a looping statement, even if the loop condition has not become False or the sequence of items has not been completely iterated over.

                An important note is that if you break out of a for or while loop, any corresponding loop else block is not executed.
                
            ### Data Types
                Variables can hold values of different types called data types. The basic types are numbers and strings, which we have already discussed. In later chapters, we will see how to create our own types using classes.
                
            ## Data Structure and Algorithms in JavaScript    
            
            
            
                 /* Stacks! */ 

                 // functions: push, pop, peek, length, 

                 var letter = []; // this is our stack

                 var word = "racecar";

                 var rword = "";

                 // put letter of word into stack
                 for (var i = 0; i < word.length; i++) {
                  letters.push(word[i]);
                  }

                  // pop off the stack in reverse order
                  for (var i = 0; i < word.length; i++) {
                    letters.push(words[i]);
                    }

                    if (rword === word) {
                      console.log(word + " is a palindrome.");
                      } 
                      else {
                      console.log(word + " is not a palindrome.");

                      var Stack = function() {
                      this.count = 0;
                      this.storage = {};

                      // this.push = function(value) {
                            this.storage[this.count] = value;
                            this.count++;
                            }

                            this.pop = function() {
                              if(this.count === 0) {
                                return undefined;
                                }

                                this.count--;
                                var result = this.storage[this.count];
                                delete this.storage[this.count];
                                return result;
                                }

                                this.size = function() {
                                  return this.count;
                                  }

                                  this.peek = function(value) {
                                    return this.storage[this.count-1];
                                    }
                                   }

                                   var myStack = new Stack();

                                   myStack.push(1);
                                   myStack.push(2);
                                   console.log(myStack.peek());
                                   console.log(myStack.pop());
                                   console.log(myStack.peek());
                                   myStack.push("freeCodeCamp");
                                   console.log(myStack.size());
                                   console.log(myStack.peek());
                                   console.log(myStack.pop());
                                   console.log(myStack.peek());      


                       function mySet() {
                        var collection = [];
                        this.has = function(element) {
                          return (collection.indexOf(element) !== -1);
                          };

                         this.values = function() {
                          return collection;
                          };

                          this.add = function(element) {
                            if(!this.has(element)) {
                              collection.push(element);
                              return true;
                              }
                            return false;
                            };

                            this.remove = function(element) {
                              if(this.has(element) {
                                index = collection.indexOf(element) {
                                collection.splice(index, 1);
                                return true;
                                return false;
                                }

             ### querySelectors

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

               ## Bucles

                      * Un bucle o ciclo, en programación, es una secuencia de instrucciones de código que se ejecuta repetidas veces, hasta que la condición asignada a dicho bucle deja de             cumplirse. Los tres bucles más utilizados en programación son el bucle while, el bucle for y el bucle do-while.

                  * For

                      * El bucle for es una estructura de control en programación en la que se puede indicar de antemano el número máximo de iteraciones.

                  * Elementos del bucle

                      * Variable de control: prácticamente un mandato impuesto por el uso habitual es utilizar la letra i Iterador como variable de control, o bien sus sucesoras en caso de bucles anidados. El uso de esta letra críptica quizás a primera vista es sin embargo una excelente forma de aportar agilidad de lectura al código por su uso tan extensivo. Como raras veces los bucles anidados superan las tres dimensiones (por una sencilla cuestión de explosión exponencial), las letras i, j y k suelen ser las únicas relacionadas con este uso. En C se define en el primer parámetro de la instrucción junto con la inicialización (opcional).
                      * Inicialización de la variable de control: en pseudolenguaje se pide explicitarlo (es la sección := ValorInicial), sin embargo, otros lenguajes más permisivos como C no lo requieren de forma obligatoria. De todos modos, la práctica de utilizar variables de control que no se inicializan en el bucle no es recomendada para la           legibilidad del código. En C se define en el primer parámetro del bucle junto con la variable de control.
                      * Condición de control: en pseudolenguaje se ve representado por el valor final que puede tomar la variable de control (la sección A ValorFinal). En C es el segundo parámetro y puede ser cualquier condición (ni siquiera es obligación que esté la variable de control, aunque una vez más, esto no se considera una buena práctica).
                      * Incremento: en pseudolenguaje se toma por defecto el valor 1, aunque puede explicitarse por medio de la sentencia PASO = ValorPaso cualquier número entero (léase) bien entero, o sea que técnicamente podemos decrementar). En C es el último parámetro.
                      * Cuerpo: es lo que se hará en cada iteración, pueden ser una o más instrucciones. En pseudolenguaje pesa la restricción de no poder alterar el valor de la variable de control; esto no es requerido en C, pero no se considera una buena práctica.

                    * While

                      * El bucle while o bucle mientras es un ciclo repetitivo basado en los resultados de una expresión lógica; se encuentra en la mayoría de los lenguajes de programación              estructurados. El propósito es repetir un bloque de código mientras una condición se mantenga verdadera.

                      * La condición ha de ser una sentencia que devuelva un valor booleano, y esta puede ser el valor booleano sí, verdadero (true) si la condición se cumple, o falso si                esta no se cumple (false). También puede contener el nombre de una variable booleana, y el valor de la expresión dependerá de su contenido. Se debe tener en cuenta              que además de las variables también puede haber llamadas a funciones que devuelvan un valor.

                    * Do-While

                        * El bucle repetir comprueba la condición de finalización al final del cuerpo del bucle, y si ésta es cierta continua con el resto del programa, a veces esto resulta               más adecuado. La instrucción se ejecutará al menos una vez.

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

            # Callback
                * Example:
                  function endpointHandler(request, response) {
                    User.findById(request.userID, function(err, user) {
                    if (err) {
                       response.send(err);
                      } else {
                        Task.findById(user.tasksId, function(err, tasks) {
                          if(err) {
                            return response.send(err);
                        } else {
                             task.completed = true;
                             task.save(function, err) {
                                if(err) {
                                  return.response.send(err);
                                 } else {
                                    response.send("Task completed");
                                     }
                                  });
                                 }
                             });
                             }
                          });

            # Promise 
                * Example
                  function endpointHandler(request, response) {
                    User.findById(request.userId) 
                      .then(function(user) {
                        return Tasks.findIdByUser(user.tasksId);
                       })
                       .then(function(tasks) {
                        tasks.completed = true;
                        return tasks.save();
                       })
                       .then(function () {
                        response.send("Task completed");
                        })
                        .catch(function(errors) {
                        response.send(err);
                        });
                        }

            # Async/Await 
                 * Example  
                  async function endPoint Handler(request, response) {
                    try {
                      var user = await User.findById(request.userId);
                      var task = await Task.findById(user.taskId);
                      task.completed = true;
                      await tasks.save();
                      response.send("Task completed");
                    } catch {
                      response.send(err);
                      }
                     }

 # React
    * rafce creates an r function like
    
    
    
      impor React from 'react'
      
      const testing = () => {
       return (
       <div>
       
       </div>
       )
      }
      
      export default testing
      
    ## This keyword
      * this is an interesting thing (reserved keyword) in the JS world. It is simple and does what says - when you call a function it tries to know who is this trying to call me?  
     
     * example: 
      const Dog = {
        food: 'Pedigree',
        eat: function() {
          return `I am eating my ${this.food}`;
      }
    }

console.log(Dog.food) // Pedigree
console.log(Dog.eat) // [λ: eat]​​​​​
console.log(Dog.eat()) // I am eating my Pedigree​​​​​

    ## Constructor
      * A constructor is a method that is called automatically when we created an object from that class. It can manage initial initialization tasks such as defaulting certain object properties or sanity testing the arguments passed in. Simply placed, the constructor is a method that helps in the creation of objects.

    ## Arrow Function =>
      * One of the approaches to solving such issues is the usage of Arrow Function introduced in ES6. These functions have a default binding to this.
      
    ## Render() method
      * https://reactjs.org/docs/rendering-elements.html
      * the render() method is the only required and most important method of all in-built life-cycle hooks/methods.
      
    ## React - create-react-app 
      * https://es.stackoverflow.com/questions/337379/error-al-instalar-create-react-app-globalmente
  
 # Python 
 
    * What is Python?
        Python is a popular programming language. It was created by Guido van Rossum, and released in 1991.

        It is used for:

        web development (server-side),
        software development,
        mathematics,
        system scripting.
        What can Python do?
        Python can be used on a server to create web applications.
        Python can be used alongside software to create workflows.
        Python can connect to database systems. It can also read and modify files.
        Python can be used to handle big data and perform complex mathematics.
        Python can be used for rapid prototyping, or for production-ready software development.
        
    * Variable
        variable can have a short name (like x and y) or a more descriptive name (age, carname, total_volume). Rules for Python variables:
        A variable name must start with a letter or the underscore character
        A variable name cannot start with a number
        A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
        Variable names are case-sensitive (age, Age and AGE are three different variables)
    * In programming, data type is an important concept.

      Variables can store data of different types, and different types can do different things.

    * What is an Array?
        An array is a special variable, which can hold more than one value at a time.

        If you have a list of items (a list of car names, for example), storing the cars in single variables could look like this:

        car1 = "Ford"
        car2 = "Volvo"
        car3 = "BMW"
 
    * Python Classes/Objects
        Python is an object oriented programming language.

        Almost everything in Python is an object, with its properties and methods.

        A Class is like an object constructor, or a "blueprint" for creating objects.
        
    * Object Methods
        Objects can also contain methods. Methods in objects are functions that belong to the object.

        Let us create a method in the Person class:

        Example
        Insert a function that prints a greeting, and execute it on the p1 object:

        class Person:
          def __init__(self, name, age):
            self.name = name
            self.age = age

          def myfunc(self):
            print("Hello my name is " + self.name)

        p1 = Person("John", 36)
        p1.myfunc()
        
    * Python Inheritance
        Inheritance allows us to define a class that inherits all the methods and properties from another class.

        Parent class is the class being inherited from, also called base class.

        Child class is the class that inherits from another class, also called derived class.

    * def combines operations into a procedure and binds a name to it
    * lists provide flexible and hierarchical structure for data
    * variables associates names with data
    * classes associates data (attributes) and procedures (methods)
    
                                  Procedures                  Data
    Primitives                    +, *, ==, !=                numbers, booleans, strings
    Combination                   if, while, f(g(x))          lists, dictionaries, objects
    Abstraction                   def                         classes
    Patterns                      higher-order procedures     super-classes, sub-classes
  
  
    def selfComposition(somefunction)
      def returnFunction(*args):
        return someFunction()
          someFunction(*args)
            return returnFunction
            
    >class Accumulator(SM):
      def __init__ (self, initial vlaue):
        selfstartState = initialValue
      def getNextValues(self, state, inp):
        return (state+inp, state+inp)
        
    * Search Minimum
        searchMinFromList(L,n)
          minValue = L[1]
          counter = 2
          while(counter <= n)
            v = L[counter}
            if( v < minValue)
              minValue = v
               else
                  pass
               endIF
               endWhile
               return MinValue
           endSearchMinFromList
              
    https://training.talkpython.fm/courses/explore_python_jumpstart/python-language-jumpstart-building-10-apps
 
    https://training.talkpython.fm/courses/explore_mongodb_for_python_developers_course/mongodb-for-python-for-developers-featuring-orm-odm-mongoengine
    
  ### Search Algorithms in Python 

    def search(initialState, goalTest, actions, succesor):
      if goalTest(initialState):
        return [{None, initialState}]
      agenda = [SearchNode(None, initialState, None)]
      
    def search(initialState, goalTest, actions, succesor):
      return [(None, initialState)]
    agenda = [searchNode(None, initialState, None)]
    while not empty(agenda):
      parent = getElement(agenda)
      for a in actions:
        newS = successor(parent.state, a)
        newN = SearchNode(a, newS, parent)
        if goalTest(newS):
          return newN.path()
        else:
          add(newN, agenda)
        return None
    
# DJANGO
    * https://www.dj4e.com/
      

    
   
  # Data Structures & Algorithms
      * A data structure is a way to store and organize data in a computer so that it can be used efficiently
    
             ## Data Types and Variables
                * /* Data types: 
                undefined, null, boolean, string, symbol, number, and object */
                Data is meaningful for the computer 
                Var stands for variable

                var myName = "Beau"

                var is going to be able to be used to throught your whole program


                myName = 8

                let ourName - "freeCodeCamp"

                let will be only be used within the scope of where you declare that

                const pi = 3.14

                const is variable that should never change

                // Declarations
                  * var StUdLyCapVar;
                  * var properCamelCase;
                  * var TitleCaseOver;

                // Assignments
                  * studlyCapVar = 40;
                  * properCamelCase = "A String";
                  * titleCaseOver = 9000;

                / ******
                CODE OUTPUT
                \' single quote
                \" double quote
                \\ backslash
                \n newline
                \r carriage return
                \t tab
                \b backspace
                \f form feed
                ****** /

                var myStr = "FirstLine\n\t\\SecondLine\nThirdLine"

                // Example
                var outStr = "I come first. " + "I come second.";

                // Only change the code below
                var myStr = "This is the start." + "This is the end."
                console.log(myStr);

                // Example 
                var ourStr = "I come first.";
                ourStr += "I come second.";

                // Only change the code below
                var myStr = "This is the first sentence";
                myStr += "This is the second sentence";

                console.log(myStr);

                // Declare your variable here
                var myGlobal = 10;

                function fun1() {
                  // Assign 5 to oopsGlobal Here


                  }


                  // Only change code above this line
                  function fun2() {
                    var output = "";
                    if (typeof myGlobal != "undefined") {
                      output += "myGlobal: " + myGlobal;
                      }

                    if (typeof oopsGlobal != "undefined") {
                      output += " oopsGloba: " + oopsGlobal;
                      }
                      console.log(output);
                      }

                      fun1();
                      fun2();

                // Assign 5 to oopsGlobal
                oopsGLobal = 5;
                }

                // Objects
                var ourDog = {
                  "name": "Camper",
                  "legs": "4,
                  "tails": 1,
                  "friends": ["everything!"]
                  };

                  var myDog = {
                    "name": "Quincy"
                    "legs": 3,
                    "tails": 2,
                    "friends": []
                    };

                  var testObj = {
                    "hat": "ballcap",
                    "shirt": "jersey",
                    "shoes": "cleats",
                    };

                    var hatValue = testObj.hat;
                    var shirtValue = testObj.shirt;

                    var testObj = {
                      "an entree": "hamburger",
                      "my side": "veggies",
                      "the drink": "water",
                      };

                      var entreeValue = testObj{"an entree"];
                      var drinkValue = testObj['The drink'];

                    function phoneticLookUp(val) {
                      var result = "";


                      var lookup {
                        "alpha": "Adams",
                        "bravo": "Boston",
                        "charlie": "Chicago",
                        "delta": "Denver",
                        "echo": "Easy",
                        "foxtrot": "frank",
                        };
                        result = lookup[val];
                      switch(val) {
                        case "alpha":   
                          result = "Adams";
                          break;
                        case "bravo":
                          result = "Boston";
                          break;
                        case "charlie":
                          result = "Chicago";
                          break;
                        case "delta": 
                          result = "Denver";
                          break;
                        case "echo":
                          result = "Easy";
                          break;
                        case "foxtrot":
                          result = "Frank"
                          break;

                      var myObj = {
                        gift: "pony";
                        pet: "kitten";
                        bed: "sleigh";
                        };

                        function checkObj(checkProp) {
                          if (myObj.hasOwnProperty(checkProp)) {
                            return myObj[checkProp];
                          } else {
                            return "Not Found";
                          return "Change Me!";
                          }
                        }

                  var myMusic = [
                    {
                      "artist": "Billy Joel",
                      "title": "Piano Man",
                      "release_year": 1973,
                      "formats": [
                        "CD",
                        "8T",
                        "LP",
                      ],

                     "gold": true,
                 }
                  "artist": "Beau Carnes",
                  "title": "Cereal Man",
                  "release_year": 2003,
                  "formats": [
                    "Youtube video"

                  ]

                  var myStorage = {
                    "car": {
                      "inside": {
                        "glove inbox": "maps";
                        "passenger seat": "crumbs"
                        },

                        "outside": {
                          "trunk": "jack"
                          }
                         }
                        };

                      var globeBoxContext = myStorage.car.inside["glove box];

                      console.log(gloveBoxContext);

                      var myPlants = [
                        {
                        type: "flowers",
                        list: [
                          "rose",
                          "tulip",
                          "dandelion"
                            ]
                          },
                          {
                          type: "trees",
                          list: [
                            "fir",
                            "pine",
                            "birch"
                            ]
                           }
                          ];

                        var secondTree = myPlants[1].list[1];

                        var collection = {
                          "2548": {
                            "album": "Slippery when wet",
                            "artist": "Bon Jovi",
                            "tracks": [
                              "Let it Rock",
                              "You give Love a Band Game",
                              ]
                             },
                             "2468": {
                              "album": "1999",
                              "artist": "Prince",
                              "tracks": [
                              "1999",
                              "Little Red Corvette"
                              ]
                             },

                             "1245": {
                              "artist": "Robert Palmer",
                              "tracks": []
                              },

                            "5436": {
                            "album": "ABBA Gold"
                            }
                            ];

                            var collectionCopy = JSON.parse(JSON.stringify(collection));
                              if (value === "") {
                                delete collection[id][prop];
                              } else if (prop === "track") {
                                collection[id][prop] = collection[id][prop] || [];
                                collection[id][prop].push(value);
                              } else {
                                collection[id][prop] = value;

                                }

                                return collection;
                                }

                            function updateRecords(id, prop, value) {

                            return collection;
                            }

                            var myArray = [];

                            var i = 0;
                            while (i < 5) {
                              myArray.push(i);
                              i++;
                              }

                              var ourArray = [];

                              for (var i = 0; i < 5; i++);
                                ourArray.push(i);
                                }

                                var myArray = [];

                                for (var = i; i < 6; i++) {
                                  myArray.push(i);
                                 }

                                 for (var = 1; i < 10; i += 2) {
                                  myArray.push(i);
                                  }

                                 var myArr = [2,3,4,5,6];

                                 for (var i = 0; i < myArr.length; i++) {
                                  total += myArr[i];
                                  }

                                  console.log(total);

                                  var multiplyAll(arr) {
                                  var product = 1;

                                  return product;
                                  }

                                  var product = multiplyAll([[1,2],[3,4], [5,6,7]]);

                                  console.log(product);

                                  for (var i = 0; i < arr.length; i++) {
                                    for (var j = 0; j < arr[i].length; j++) {
                                      product *= arr[i][j];
                                    }
                                   } 
                                    return product;
                                    }

                                  var myArrar = [];
                                  var i = 10;

                                    do {
                                    myArray.push(i);
                                    i++;
                                    } while (i < 5)

                                    console.log(i, myArray);

                                   var contacts = [
                                    { 
                                      "firstName": "Akira",
                                      "lastName": "Laine",
                                      "numer": "054232548",
                                      "likes": ["Pizza", "Coding", "Brownie Points"]
                                      },
                                      {

                                      "firstName": "Harry",
                                      "lastName": "Potter",
                                      "number": "32354222",
                                      "likes": ["Hogwarts", "Magic", "Hagrid"]
                                      },
                                      {

                                      "firstName": "Sherlock",
                                      "lastName": "Potter",
                                      "number": "2235323323",
                                      "likes": ["Intriguing Cases", "Violin"]
                                      },
                                      {

                                      function lookUpProfile(name, prop) {

                                       }

                                       if(contacts[i].firstName === name) {
                                        return contacts[i][prop] || "No such property";
                                       }
                                       return "no such contact";

                                      }
                                     }

                                     var data = lookUpProfile("Akira", "likes");
                                     console.log(data);

                                     function converToIntenger(str) {
                                      return parseInt(str, 2)
                                      }

                                      convertToIntenger("10011");

                                     function checkEqual(a, b) {
                                      if(a === b) {
                                        return true;
                                        }
                                        else {
                                        return false;
                                        }
                                       }

                                      checkEqual(1, 2);

                                      function checkEqual(a, b) {
                                        if a === b ? true : false;

                                        return a === b;
                                        }

                                       function checkSign(num) {
                                        return num > 0 ? "positive" : num < 0 ? "negative" : "zero"

                                       }

                                       chekcSign(10);

                                       let catName = "Quincy";
                                       let quote;

                                       var catName = "Beau";

                                       function catTalk() {
                                        "use stric";

                                        catName = "Oliver";
                                        quote = catName + "says Meow!";
                                        }

                                        catTalk();

                                        function checkScope();
                                         "use strict";
                                         let i = "function scope";
                                         if (true) {
                                          let i = "block scope";
                                          console.log("Block scope i is: ", i);
                                          }
                                          console.log("Function scope i is: ", i);
                                          return i;
                                          }

                                          checkScope();

                                          function printManyTimes(str) {
                                          "use stric";

                                          var sentence = str + " is cool!";

                                          sentence = str + "is amazing!"

                                          for (var i = 0; i < str.length; i += 2) {
                                          console.log(sentence);
                                          }

                                          }

                                          printManyTimes("freeCodeCamp");

                                          const s = [5, 7, 2];
                                          function editInPlace() {
                                            "use strict";

                                            s[0] = 2;
                                            s[1] = 5;
                                            s[2] = 7;


                                            }

                                            editInPlace();

                                       function freezeObj() {
                                        "use strict";
                                        const MATH_CONSTANTS = {
                                        PI: 3.14
                                        };

                                        Object.freeze(MATH_CONSTANTS);

                                        try {
                                          MATH_CONSTANTS.PI = 99;
                                         } catch( ex ) {
                                         console.log(ex);
                                         }
                                         return MATH_CONSTANTS.PI;
                                         }

                                         const PI= freezeObj();

                                         console.log(PI);

                                         const realNumberArray = [4, 5.6, -9.8, 3.14, 42, 6, 8.34, -2];

                                         const squareList = (arr) => {
                                          const squareIntegers  = arr.filter(num => Number.isInteger(num) && num;
                                          const squaredIntegers;
                                          };

                                          const squaredIntegers = squareList(realNumberArray);
                                          console.log(squaredIntegers);

            ## Data Structures - Types and Values
                        A data type is a classification of data which tells the compiler or interpreter how the programmer intends to use the data. Most programming languages support various types of data, including integer, real, character or string, and Boolean.
                      * Numbers
                        - Intergers
                        - Floats - floating points
                      * Strings -  Strings are strings
                      * Booleans

                      * Numbers
                       - 3 - interger
                       - 3.14 - floating point
                      * Strings
                       -'abc'
                       
          ## Data Structures
              * Arrays                                                        * Sorting, searching, and binary search
              * Linked list                                                   * Divide and conquer
              * Stacks                                                        * Dynamic programming and memorization
              * Queues                                                        * Greedy Algorithms
              * Sets                                                          * Recursion
              * Maps                                                          * Graph traversal, breath and depth-first
              * Binary Trees
              * Heaps
              * Graph
              
      ## Binary Search
                          
           public static int binarySearch(int[], A, int left, int rigth, int x) {
               if(left > right) {
                return -1;
             }
            int mid = (left + right) / 2;
              
            if (x === A[mid]) {
              return mid;
  
            if ( x < A[mid] {
               return binarySearch(A, left, mid -1, x);
               }
                           
            return binarySearch(A, mid + 1, right, x);
              }
                           
           public static int binarySearch(int[] A, int left, int right, int x) {
                if (left > right) {
                  return -1;
              }
            int mid = (left + right) / 2;
              
            if( x == A[mid]) {
              return binarySearch(A, left, mid - 1, x);
                 }
  
              return binarySearch(A, mid + 1, right, x);
                }
              
             public static void void mer(int[] data, int start, int mid, int end) {
                // build temp array to avoid modifying the original contents
                int[] temp = new[end - start + 1];
                  
                int i = start, j = mid + 1, k = 0;
                
                // while both sub-array have values, then try and merge them in sorted order
                while (i <= mid && j <= end) {
                  if(data[i] <= data[j]) {
                     temp[k] = data[i];
                     i++;
                     k++;
                    } else {
                      temp[k++] = data[j++];
                      }
                    }
                   while (i <= mid) {
                    temp[k] = data[i];
                    k++; i++;
  
                 }
                while (j <= end) {
                  temp[k] = data[j];
                  k++; j++;
                               
              }
                               
              for ( i = start; i <= end; i++) {
                  data[i] = temp[i - start];
              
            }
           }
        }
  
      ## Linked List 

        public static ListNode reverseList(ListNode head) {
            if (head == null || head.next == null) return head;
            listNode p = reverseList(head.next);
            head.next.next = head;
            head.next = null;
            return p;
            }

      ## Merge two sorted linked list 

        public Node SortedMerge(Node A, Node B) {
            if(A == null) return B;
            if(B == null) return A;

            if(A.data < B.data) {
              A.next = SortedMerge(A.next, B);
              return A;
            } else {
              B.next = SortedMerge(A, B.next);
              return B;
            }
           }
                          
       ### What is an algorithm?
        * An algortihm is a function, it takes inputs to outputs

        for Birthdayproblem: -maintain record
                             -interview students in some order
                                -check if birthday is record
                                    -if so return pair
                                -add new students to record
                             -return None
          * Correctness
            Inductive hypothesis: if first k students contain match 
                                      alg returns a match before interview student
            Base case k = 0
            Assume IH true for k = k' { if k' contains match -> alredy returned by induction
                                        else if k'+i contains match 
                                        alg k' + i against all students


          * Efficiency 
            It means not only how fast it run but how fast it compares to other possibles ways of approaching this problem.
            Don't measure time, instead count ops
            Expect performance to depend in size of out input
            O notation (upper bands)  OMEGA (lower bands)  THETA (both)

       ## Algorithms
          * Global or class scope variables
            n = number of nodes in the graph
            g = adjacency list representing graph
            visited = [false, ..., false] # size n

            function dfs (at):
              if visited[at]: return
              visited[at] = true

            neighbours = graph[at]
            for next in neightbours:
              dfs(next)

          * Start DFS at node zero
            start_node = 0
            dfs(start_node)

           function findComponent():
              for (i = 0; i < n; i++):
                 if !visited[i]:
                   count++
                   dfs(i)
                 return (count, components)

           function dfs(at):
              visited[at] = true
              components[at] = count
              for (next : g[at]):
                if !visited[next]:
                 dfs(next)

            function solve(s):
               q = queue data structures data structure with enqueue and dequeue
               q.enqueue(s)

               visited = [false, ..., false] # size n
               visited[s] = true

               prev = [null, ..., null] # size n
               while !q.isEmpty():
                node = q.dequeue()
                neighbours = g.get(node)

                for(next : neightbours):
                   if !visited[next]:
                      q.enqueue(next)
                      visited[next] = true
                      prev[next] = node
                   return prev

                function reconstructPath(s, e, prev):

                   # Reconstruct path going backwards from e
                       path = []
                       for(at = e; at != null; at = prev[at]);
                          path.add(at)

                           path.reverse()

                    # If s and e are connected return the path 
                        if path[0] == s:
                          return path
                        return []

                    function solve(): 
                       rq.enqueue
                       cq.enqueue
                       visited[sr][sc] = true
                       while rq.size() > 0: #or cq.size() > 0
                          r = rq.dequeue()
                          c = dequeue() 
                        if m[r][c] = 'E':
                          reached_end = true
                          break
                        explore_neighbours(r, c)
                        nodes_left_in_layer--
                        if nodes_left_in_layer == 0:
                          nodes_left_in_layer = nodes_in_next_layer
                          nodes_left_in_next_layer = 0
                          move_count++
                        if reached_end:
                          return move_count
                         return -1

 ### What is the difference between computer science, computer engineering, software engineering, programming, and coding?
  CS/CE/SE vs Programming/Coding

          * Computer science (CS), computer engineering (CE), software engineering (SE), programming, and coding are all terms that are interrelated yet subtly different from each other, often making it difficult for beginners to tell them apart.

          The first distinction you should make is to distinguish between CS/CE/SE and programming/coding. CS, CE, and SE are all fields of study. Saying "I'm studying computer science" would be similar to saying "I'm studying chemistry" or "I'm studying literature". In contrast, programming and coding are activities -- they're things you do. To use a metaphor, studying CS/CE/SE would be like studying musical theory, while learning programming/coding would be like learning how to play a particular instrument.

          Theoretically, you could learn one and not learn the other, but your experience will be much more enriched if you learn both.

          Another difference is that while CS/CE/SE are things that you can study, learning to program is something that only comes through practice. And in fact, what most universities and schools will do is formally teach one language to teach the basics of coding, then will focus on teaching CS, CE, and SE and leave you to learn how to program through practicing and completing homework.

          * CS vs CE vs SE

          The next distinction you should make is between CS, CE, and SE. In a nutshell, though there's a lot of overlap, "computer science" has little to do with either computers or science and is more of a field of applied math that studies the concept of computability. Computer engineering is similar to CS, but tends to focus more on lower-level hardware -- it's like a cross between computer science and electrical engineering. And finally, software engineering is more about how to build large and complex programs while preventing them from collapsing under their own weight -- it's like CS and CE, but with less theory.

          You can find a more detailed overview here: http://www.reddit.com/r/learnprogramming/comments/2k569h/eli5_computer_science_vs_software_engineering_vs/

          * Programming vs Coding

          And finally, you have programming vs coding. The difference between these two terms are very small -- many people use them interchangeably. In general, the term "programming" seems to have slightly more positive connotations then "coding". If you say "I'm a programmer", it implies a certain level of professionalism -- it indicates that you can not only write code, but also have a firm grasp on the fundamentals and theory, know how to communicate with clients and work with others, etc.

          In contrast, if you say "I'm a coder", it usually implies that your focus is exclusively on writing code, and less so on the other things.

          However, again, the different connotations are very small here -- you can use the two terms interchangeably in the vast majority of cases.

  # Coding
    * Translating one language to another
    
  # Scripting
    * Coding in a scripting language
    * Use to perform a single or limited task
    
  # Programming
    * Coding in a programming language
    
   ## Programming languages
        * Special languages that software developers use to write instructions for computers to execute
      
   ## What is OOP? 
      * Conceptos fundamentales
          La POO es una forma de programar que trata de encontrar una solución a estos problemas. Introduce nuevos conceptos, que superan y amplían conceptos antiguos ya conocidos. Entre ellos destacan los siguientes:

         * Clase
          Una clase es una especie de "plantilla" en la que se definen los atributos y métodos predeterminados de un tipo de objeto. Esta plantilla se crea para poder crear objetos fácilmente. Al método de crear nuevos objetos mediante la lectura y recuperación de los atributos y métodos de una clase se le conoce como instanciación.
         * Herencia
          Por ejemplo, herencia de la clase C a la clase D, es la facilidad mediante la cual la clase D hereda en ella cada uno de los atributos y operaciones de C, como si esos atributos y operaciones hubiesen sido definidos por la misma D. Por lo tanto, puede usar los mismos métodos y variables registrados como "públicos" (public) en C. Los componentes registrados como "privados" (private) también se heredan pero se mantienen escondidos al programador y solo pueden ser accedidos a través de otros métodos públicos. Para poder acceder a un atributo u operación de una clase en cualquiera de sus subclases pero mantenerla oculta para otras clases es necesario registrar los componentes como "protegidos" (protected), de esta manera serán visibles en C y en D pero no en otras clases.
         * Objeto
          Instancia de una clase. Entidad provista de un conjunto de propiedades o atributos (datos) y de comportamiento o funcionalidad (métodos), los mismos que consecuentemente reaccionan a eventos. Se corresponden con los objetos reales del mundo que nos rodea, o con objetos internos del sistema (del programa).
         * Método
          Algoritmo asociado a un objeto (o a una clase de objetos), cuya ejecución se desencadena tras la recepción de un "mensaje". Desde el punto de vista del comportamiento, es lo que el objeto puede hacer. Un método puede producir un cambio en las propiedades del objeto, o la generación de un "evento" con un nuevo mensaje para otro objeto del sistema.
         * Evento
          Es un suceso en el sistema (tal como una interacción del usuario con la máquina, o un mensaje enviado por un objeto). El sistema maneja el evento enviando el mensaje adecuado al objeto pertinente. También se puede definir como evento la reacción que puede desencadenar un objeto; es decir, la acción que genera.
        *  Atributos
          Características que tiene la clase.
        *  Mensaje
          Una comunicación dirigida a un objeto, que le ordena que ejecute uno de sus métodos con ciertos parámetros asociados al evento que lo generó.
          Propiedad o atributo
          Contenedor de un tipo de dato asociado a un objeto (o a una clase de objetos), que hace los datos visibles desde fuera del objeto y esto se define como sus características predeterminadas, y cuyo valor puede ser alterado por la ejecución de algún método.
        * Estado interno
          Es una variable que se declara privada, que puede ser únicamente accedida y alterada por un método del objeto, y que se utiliza para indicar distintas situaciones posibles para el objeto (o clase de objetos). No es visible al programador que maneja una instancia de la clase.
        *  Miembros de un objeto
          Atributos, identidad, relaciones y métodos.
        *  Identificación de un objeto
          Un objeto se representa por medio de una tabla o entidad que esté compuesta por sus atributos y funciones correspondientes.
          En comparación con un lenguaje imperativo, una "variable" no es más que un contenedor interno del atributo del objeto o de un estado interno, así como la "función" es un procedimiento interno del método del objeto.
          
  # What is software?
    * Software is anything that humans interact with on a computer, such as the internet browsers or programs.
    
   ## Application Software 
        * Any software used created to fulfill a specific need, like a text editor, web browser, or graphic editor

   ## Software System
        * Softwawre used to keep our core system running, like operating system tools and utilities

   ## Firmware
        * Software that's permanently stored on a computer component
      
  # What does it means to do computation?
    * Computers only do what you tell them to do, they are not magical.
    * Computers don't know anything.
    
  # What is a computer program?
    * a file
   
  # What's a file?
    * a string of characters
  
  # What's a character?
    * a string of bits
    
  # What's a program?
    * a finite string of bits
    
  # Shell
    * a program that interprets text commands and sends them to the OS to execute
    
   ### What is knowledge?
     * Declarative and Imperative
     
      * Imperative - It tells you how you might test something but it doesn't tells you how to.
     
     Imperative knowledge is a description of how to deduce something.
     
     It's a sequence of specific instructions that I do in order. Along the way I have some tests and depending on the value of that test, I may change where I am in that            sequence of instructions. 
     
      * Declarative - 
      
  ### What is package?
     * A package is a reusable bundle of code and/or assets
     * NPM - world largest software registry
     * The npm init command allows to create a package.json file
     
     
  ### Program is a recipe
     * Given a set fixed of primitives a good programmer can program anything.
     * Our goal is to take problems a break them into these computational steps, these sequence of instructions that allow us to take capture that process.
     
  ### What is a recipe?
    * Sequence of simple steps
    * Flow of control process that specifies when each step is executed
    * A means of determining when to stop
    
  ### What is a problem?
    Inputs
    *
    *
    *
    *
    Outputs
    *
    *
    *
    *
 
  ### What is terminal? What we want to use it?
    * PWD - Full path name to current working directory
    * ls - list of directories
    * Mkdir - Create a directory/folder
    * cd - change directory
    * cd .. - navigate to parent, one level up
    * clear - clear console
    * arrow key up/down - Previous Commands
    
  ### NPM Commands
    * NPM init - creates package JSON
    * NPM install <package name> --save     - install package locally and add to packge JSON
    * NPM install <package name> -g         - install package globally
    * NPM install <package name> --save-dev - use it only in development
                            
  ### Basic Primitives                     
    * Move left
    * Move right
    * Read
    * Write
    * Scan 
    * Do nothing
    
  ### List of Primitives
    * Intergers
    * Floats
    * Booleans
    * Strings
    
  ### What is an Array?
    * List, or collection of values(arrays can contain many different values of different data types
    * Each value has an index (an index is a unique numerical value that represents the value in the array)
    * Array Length (after an array is created, you can check its length at anytime with arrayName.length)
  
  ### What is a Function?
    * A block code that executes a routine task using a series of instructions
    * Examples 
      - function printThanks() {
          console.log("Thanks for shopping");
          console.log("Discounts expire Dec 1!");
          }
          
       - function computerPrice(cost, discount) {
            let reduction = cost*discount;
            console.log("you have saved $"+reduction);
            return cost-reduction;
            }
           
       - Function Syntax
            function isCountingDown(var1, var2) {
              if (var1 > var2) 
                return true;
              return false;
              }
        - if no return statement is defined, the retrun result is undefined
        
  ## What are Objects?
  
  * Representation of real world objects like books

        const book = {
          title: "1984",
          author: "George Orwell",
          isAvailable: false,

        checkIn: function() {
          this.isAvailable = true;
          },

        checkOut: function() {
          this.isAvailable = false;
          }
        };

        console.log(typeof book);

        const book = new Object():
        book.title = "1984";,
        book.isAvailable = false;

        book.checkIn = function() {
          this.isAvailable =  true;
          };
          book.checkOut: function() {
          this.isAvailable = false;
          };

          console.log(typeof book);
          
  ### How the internet works?
  
  The Internet started as ARPANET in the 1960s with the goal of a decentralized computer network.
  
Physically, the Internet is a collection of computers moving bits to each other over wires, cables, and radio signals.
Like many complex engineering projects, the Internet is broken up into various layers, each concerned with solving only a smaller problem. These layers connect to each other in well-defined interfaces.
There are many protocols that define how the Internet and its applications should work at the different layers: HTTP, IMAP, SSH, TCP, UDP, IP, etc. In this sense, the Internet is as much a collection of rules for how computers and programs should behave as it is a physical network of computers.
With the growth of the Internet, advent of WIFI, and e-commerce needs, SSL/TLS was developed to address security concerns.
          
  ### TCP/IP: 
      Transmission Control Protocol and Internet Protocol are communication protocols that define how data should travel across the internet. This is like the transport mechanisms that let you place an order, go to the shop, and buy your goods. In our example, this is like a car or a bike (or however else you might get around).
      What do these protocols do? At their most basic level, these protocols establish the rules for how information passes through the Internet.
      
  ### DNS: 
      Domain Name System is like an address book for websites. When you type a web address in your browser, the browser looks at the DNS to find the website's IP address before it can retrieve the website. The browser needs to find out which server the website lives on, so it can send HTTP messages to the right place (see below). This is like looking up the address of the shop so you can access it.
      
  ### What is SSL/TLS?
      SSL stands for Secured Sockets Layer. TLS stands for Transport Layer Security. SSL was first developed by Netscape in 1994 but a later more secure version was devised and renamed TLS. We will refer to them together as SSL/TLS.

      SSL/TLS is an optional layer that sits between the Transport Layer and the Application Layer. It allows secure Internet communication of sensitive information through encryption and authentication.
      
      Authentication means the client can trust that the server is who it claims to be.
      
      When the browser requests a web site using the https protocol instead of http, it’s telling the web server it wants an SSL encrypted connection. 
        
  ### HTTP - HyperText Transfer Protocol
  
    * Application layer protocol
    * Built on top of TCP/IP protocol
    * Rules for transforming resources
    * Every HTTP Request is executed independently without the knowledge of requests that came before
    * HTTP is stateless 
    * TCP/IP is not stateless
    
    HTTP Verbs            CRUD
    * GET                 * READ
    * POST                * CREATE
    * PUT                 * UPDATE
    * PATCH               * UPDATE
    * DELETE              * DELETE
    
  	HTTP Verbs are also known as methods. Just resources are nouns, the HTTP verbs have semantic meaning also. It is easy to understand
    
    * GET
    GET requests are the most common and widely used methods in APIs and websites. Simply put, the GET method is used to retreive data from a server at the specified     resource. For example, say you have an API with a /users endpoint. Making a GET request to that endpoint should return a list of all available users.
    Since a GET request is only requesting data and not modifying any resources, it's considered a safe and idempotent method.
    
    * POST
    In web services, POST requests are used to send data to the API server to create or update a resource. The data sent to the server is stored in the request body       of the HTTP request.

    The simplest example is a contact form on a website. When you fill out the inputs in a form and hit Send, that data is put in the response body of the request and    sent to the server. This may be JSON, XML, or query parameters (there's plenty of other formats, but these are the most common).

    It's worth noting that a POST request is non-idempotent. It mutates data on the backend server (by creating or updating a resource), as opposed to a GET request      which does not change any data. Here is a great explanation of idempotentcy.
    
    * PUT
    Simlar to POST, PUT requests are used to send data to the API to update or create a resource. The difference is that PUT requests are idempotent. That is, calling     the same PUT request multiple times will always produce the same result. In contrast, calling a POST request repeatedly make have side effects of creating the         same resource multiple times.

    Generally, when a PUT request creates a resource the server will respond with a 201 (Created), and if the request modifies existing resource the server will           return a 200 (OK) or 204 (No Content).
    
    * PATCH
    A PATCH request is one of the lesser-known HTTP methods, but I'm including it this high in the list since it is similar to POST and PUT. The difference with PATCH     is that you only apply partial modifications to the resource.

    The difference between PATCH and PUT, is that a PATCH request is non-idempotent (like a POST request).

    To expand on partial modification, say you're API has a /users/{{userid}} endpoint, and a user has a username. With a PATCH request, you may only need to send the     updated username in the request body - as opposed to POST and PUT which require the full user entity.
    
    * DELETE
    The DELETE method is exactly as it sounds: delete the resource at the specified URL. This method is one of the more common in RESTful APIs so it's good to know       how it works.

    If a new user is created with a POST request to /users, and it can be retrieved with a GET request to /users/{{userid}}, then making a DELETE request to               /users/{{userid}} will completely remove that user.
    
    * HEAD
    The HEAD method is almost identical to GET, except without the response body. In other words, if GET /users returns a list of users, then HEAD /users will make       the same request but won't get back the list of users.

    HEAD requests are useful for checking what a GET request will return before actually making a GET request -- like before downloading a large file or response         body. Learn more about HEAD requests on MDN.

    It's worth pointing out that not every endpoint that supports GET will support HEAD - it completely depends on the API you're testing.
    
    * OPTIONS
    Last but not least we have OPTIONS requests. OPTIONS requests are one of my favorites, though not as widely used as the other HTTP methods. In a nutshell, an         OPTIONS request should return data describing what other methods and operations the server supports at the given URL.

    OPTIONS requests are more loosely defined and used than the others, making them a good candidate to test for fatal API errors. If an API isn't expecting an           OPTIONS request, it's good to put a test case in place that verifies failing behavior.
    
    * POST vs PUT vs PATCHPermalink
    POST, PUT and PATCH all modify the state, therefore sometimes can be confusion which one to use.
    
    * Developer DocumentationPermalink
    Having great documentation is first step of having a great developer experience.

    API documentation and developer experience
    Design good static REST API documentation
    API documentation guidelines
    Google’s developer documentation style guide
    The guide from ReadTheDocs team
    Alternatives to Swagger for documenting REST APIs
    Swagger - The most popular documentation tool for RESTful APIs.
    A tutorial and guide to swagger.
    Best pratices for documentation REST APIs
    
   ## JAM StackPermalink
    JAM Stack stands for Javascript API and Markup. Usually it involves using static site generators (SSGs) to create the static Markup and Javascript and APIs to         provide the dynamic content. Since most of the Markup is statically generated, if the website is primarily content driven (like a magazine or blog) it can become     extremely scalable. Of course, APIs are key that makes this happen as well.

    JAMStack.org
    Using static site generators at scale
    Smashing magazine moving to JAMS


  ### What is REST? Representational State Pattern
    * Architectural Pattern with design guides
    * HTTP is usually the underlying protocol
    * Use HTTP methods explicitly
    * Every RESTful resource has a unique ID
    * Client state is not persisted between request
    * Catching policy for responses
    * Separation of concerns between clients and servers
    * Layered system
    
  ### What is an API? Aplication Programming Interface
    * Defines server-side functions
    * Where requests should be made
    * Format of the request and response 
    * No standard way of writing API's
    * REST provides guidelines
    * CRUD operations
    * Create / Read / Update / Delete
    
  ### Algebra
    * https://lindagreen.web.unc.edu/wp-content/uploads/sites/5262/2020/08/classNotes_m110_2018F.pdf
           
  ### What is a Class?
  
    * Blueprints for creating bundles of data and code that are related
    * A "Car" class can have attributes that describe its brand, model, color, miles, and anything else descriptive; these are also know as "fields".
    * A "Car" class can also have "methods" that define its behavior, such as "accelerate", "turn", "honk", and more, wich take the form of functions.
    * La Clase es la "forma" y atributos que tendran los datos (Objetos) 

      * Class Car
          attributes fuel
                     maxspeed

          methods    refuel()
                     getFuel()
                     setSpeed()
                     drive()
                     
   ### Class 
   
    * A template for creating instances of an object
    * A template for an abstract data type
    * Is used to make instances, meaning particular versions of that structure
    * Provide a convinient way to aggregate procedures and data in a single estructure
      
      class Student:
        school = 'MIT'
        def calculateFinalGrade(self):
              return theFinalGrade
              
    * classes can include attributes (data) and methods (procedures).
    
      #### Superclass - Person
      #### Subclass - MITPerson           // Inheritance

    
 
  ### Instances 
    * Will have some internal attributes
    * Inside instances we have a set of attributes
    * Inherit the methods and attributes of their class
    * Can also contain new attributes and methods
    
  ### Inheritance
    * Dog <- Retriever <- Golden
    
    class Dog():
      cry = "Bark"
      def __init__(self, name):
        self.name = name
        
        def greetings(self):
          return "I'm" + self.name + ", " + self.cry
          
          Lassie = Dog("Lassie")
          Lassie.name
          
     class Retriever(Dog):
          pass
     Benji = Retriever ("Benji")
     Benji.greeting()
     
     class Golden(Retriever):
        def greeting(self):
        return "OHAI!"
        
        Retriever.greetings(self)
        Sydney = Golden ("Sidney")
        Sydney.greetings()
        
     class wallFinder(sm.SM):
        startState = None
        def getNextValues(self, state, inp):
          desireDistance = 0.5
          currentDistance = inp.sonars[3]
          return (state, io.Action(fvel=?, rvel = 0) )
          
      class Linked_List_Node:
        def __init__(self, x):
          self.item = x
          self.next = None
          
        def later_node(self, i):
          if i == 0: return self
          assert self.next
          return self.next.later_node(i - 1)
          
       class Linked_List_Seq:
          def __init__(self):
          self.head = None
          self.size = 0
          
       def permutation_sort(A):
          '''Sort A'''
          for B in permutations(A):
            if is_sorted(B):
              return B
              
        def prefix_max(A):
          '''Return index of maximum in A[:i + 1]'''
          if i > 0:
            j = prefix_max(A, i - 1)
            if A[i] < A[j]:
              return j
            return i
              
  ## Event Class
    * Contains the data when the event happened, the name of the machine where it happened, the user involved, and the event type.
        
  ### Methods
    * Can access the value of the specific instance
   
    ### __init__
      * Creates an instance

    ### __str__
      * It converts things into a string type. It tells us how we want to have it printed out.

    ### __cmp__ 
      * Comparison

    ### __eq__
      * Same

  ### Data Hiding
    * One can only access instances values through defined methods. (Python doesn't do this)
    
  ### Conditional Distributions
    * Conditional distributions are represented as procedures
      
      def TESTgivenAIDS(AIDS):
        if AIDS == 'true':
          return dist.DDist({'positive': 0.985946, 'negative': 0.014054)}
        else:
          return dist.DDist({'positive': 0.023000, 'negative': 0.977000})  
        
   #### Stack class
          class Stack:
            def __init__ (self):
              self.data = []
            def push(self, item):
              self.data.append(item)
            def pop(self):
              return self.data.pop()
            def empty(self):
              return self.data is []
              
            class PQ:
              def __init__(self):
                self.data = []
              def push(self, items, cost):
                self.data.append((cost, item))
              def pop(self):
                (index, cost) = util.argmaxIndex(self.data, lamda (c, x): -c)
                 return self.data.pop(index)[1] = just return the data item
              def empty(self):
                 return len(self.data) == 0
                 
   #### Search Node
            class SearchNode:
              def __init__ (self, action, state, parent, actionCost):
                self.state = state
                self.action = action
                self.parent = parent
                if self.parent:
                  self.cost = self.parent.cost + actionCost
                else:
                  self.cost = actionCost
              def path(self):
                  if self.parent == None:
                    return [(self.action, self.state)]
              def inPath(self, s):
                  if s == self.state:
                     return True
                  elif self.parent == None:
                     return False
                  else:
                     return self.parent.inPath(s)
                  
                    
          
### Programming Styles for Managing Complexity
    Structure of program has significant effect on its modularity
    
    Imperative (procedural) programming
      * Focus on step-by-step instructions to accomplis task
      * Organize program using structured conditionals and loops
    
    Functional Programming
      * Focus on procedures that mimic mathematical functions, producing outputs from inputs without side effects
      * Functions are first-class objects used in data structures, arguments to procedure, and can be returned by procedures
      
    Object-oriented Programming
      * Focus on collections of related procedures and data
      * Organize programs as hierarchies of related classes and instances
        
## Where things go wrong?
 
 ## Syntax
    
  ### What is Syntax?
  
    * Syntax says what are the legal expressions in this language.
    * The rules for how a sentence is constructed
  
    addEventListener() Syntax
    
    Here's the syntax:

    target.addEventListener(event, function, useCapture)
    
    * target: the HTML element you wish to add your event handler to. This element exists as part of the Document Object Model (DOM)
    * event: a string that specifies the name of the event. We already mentioned load and click events.
    * function: specifies the function to run when the event is detected. This is the magic that can allow your web pages to change dynamically.
    
  ## Semantics 
  
     * The actual meaning of statements
     
  ### Static semantics
  
     * Which expressions makes sense.
     Semantics - What the meaning of this piece of code is?
     
  ### Statements
  
    * Legal commands that Python can interpret
      - Print, assignment
   
  ### Expressions 
  
    * Operands  
      - In computing, an operand is the part of a computer instruction which specifies what data is to be manipulated or operated on, while at the same time representing the data itself.
    * Operators 
     - In computer programming, operators are constructs defined within programming languages which behave generally like functions, but which differ syntactically or semantically.
     
   ### Interface(API/ADT)            vs             Data Structure
     -Specification                                   -Representation
     -What data can store                             -How to store data
     -What operations are supported & what they mean  -Algorithms to support operations
     -Problem                                         -Solution
     
     
  Data                      Operations                            Commands
  Number                        +,*                               assignment
  Strings                                                         input/output
  Booleans                    and, or                             conditionals, loop mechanisms(while)
  
  ### Iterative programs
  
    - Choose variable that counts
    - Initiliaze outside the loop
    - Set up end test (variable)
    - Construct block
    - Change the variable
    - What to do when done
    
  For <var> in <some collection>
          |
          |block of code
          |
          |
          |
  
  Tuple - ordered sequence of elements (inmutable)
  
  foo = (1, 2, 3, 4)
  Selection foo[0]
  Slicing foo[1;3]
  
    
 ### Languages
        We have
          * Assignment
          * Conditionals
          * Input/Output
          * Looping constructs (for/while)
        We don't have
          * Decomposition
          * Abstraction
  
  ### Functions 
  
    The idea of function is I wanna capture a common pattern of computation
       * Break up into modules
       * Supress detailed
       * Create "new primites"
  
      * Def (definition or define) - keyword
        - Name(x) --> formal parameters
        - return - keyword (when you get to this point in the computation, stop the computation.
        - None - special value
    Invoke a function by passing in values for the parameters
      Example sqrt(16)
        This binds x to 16
  
   ### Recursion
  
       The idea of recursion is that i'm gonna take a problem and beak it down to a simpler version of the same problem plus some steps I can execute.
          - Base case - simplest possible solution
          - Inductive step - break the problem into a simpler version of the same problem and some other steps.
          Example: If you're born in the United States you're by definition a natural born US citizen. 
                   if you're not born in the United States, you may still be, under definition, a natural born US Citizen if you're born outside the United States, both of 
                   your parents are citizens of the United States and at least one parent has lived in the United States.
  
  ### Fibonacci 
         Pairs(0) = 1
         Pairs(1) = 1
         Pairs(n) = (n - 1) + (n - 2) 
  
     
  If <some test>
          |
          |Block of instructions
          |
  else:
          |
          |Block of instructions
          |
     
  
  Boolean combination or iteration or loops
  

  ### What is programming?
  
     * It's about making software.
      
  ### What is software?
  
     * It's what runs in our hardware, runs in our computer.
     * Software is the files that you can open up in your computer and you can interact with.
     * It's what is written using programming code.
      
  ### What is code?
  
     * Code is just a technical implementation of algorithms, wich are step-by-step instructions for solving problems.
      
 ### What share in common computer programs?
  
     * Functions: A function is a block of code that performs a task.
     * Loops: A loop is used to execute a group of instructions or a block of code multiple times, without writing it repeatedly.
     * Conditions: Conditional statements check whether a programmer-specified Boolean condition is true or false. 
     * Boolean Expressions: A Boolean expression is an expression used in programming languages that produces a Boolean value when evaluated. A Boolean value is either true or false.
     * Variables: A variable is a container for a particular set of bits or type of data (like integer, float, String etc...). A variable can eventually be associated with or identified by a memory address.
     * Threads: A thread of execution is the smallest sequence of programmed instructions that can be managed independently by a scheduler, which is typically a part of the operating system.
     * Events: An event is an action or occurrence recognized by software, often originating asynchronously from the external environment, that may be handled by the software. Computer events can be generated or triggered by the system, by the user, or in other ways. Typically, events are handled synchronously with the program flow; that is, the software may have one or more dedicated places where events are handled, frequently an event loop.
      
      List of programming languages
      * Bash
      * C
      * C++
      * C#
      * Clojure
      * Erlang
      * F#
      * Go
      * Haskell
      * Java
      * JavaScript
      * Objective-C
      * OCaml
      * PHP
      * Python
      * R
      * Ruby
      * Scala
      * Scheme
      * SQL
      * Swift
      
## Front End - Client Side
     * HTML, CSS, JavaScript
     * Angular, Ember, Meteor, React, Vue
     * Bootstrap, Foundation, Semantic UI
      
## Framework - 
      * A way of doing things. 
      
## Back End - Server Side
      * Go, Java, JavaScript, .NET, PHP, Python, Ruby, Scala, Django, Flask, Laravel, Node.js...
      
## Database
      * SQL, NoSQL, MariaDB, MySQL, Oracle, PostgreSQL, SQL Server, Bigtable, Cassandra, HBase, MongoDB...
      
      What does a data base?
         Support these opperations
            * Create        // C
            * Read         //  R
            * Upload      //   U
            * Deleat     //    D
            
            SQL - Stores data in rows and columns
            NoSQL - Stores data all together in a hierarchical structure
        
  ## What is a Database?
    * Store           | 
    * Manipulate      | Data
    * Retrieve        |
    
    * https://gitlab.com/gitlab-course-public/freecodecamp-gitlab-ci/-/blob/main/docs/course-notes.md
  
  
   ## SQL
      * SQL is a standard language for storing, manipulating and retrieving data in databases.
      * What is SQL?
          SQL stands for Structured Query Language
          SQL lets you access and manipulate databases
      * What Can SQL do?
          SQL can execute queries against a database
          SQL can retrieve data from a database
          SQL can insert records in a database
          SQL can update records in a database
          SQL can delete records from a database
          SQL can create new databases
          SQL can create new tables in a database
          SQL can create stored procedures in a database
          SQL can create views in a database
          SQL can set permissions on tables, procedures, and views
       * Some of The Most Important SQL Commands
          SELECT - extracts data from a database
          UPDATE - updates data in a database
          DELETE - deletes data from a database
          INSERT INTO - inserts new data into a database
          CREATE DATABASE - creates a new database
          ALTER DATABASE - modifies a database
          CREATE TABLE - creates a new table
          ALTER TABLE - modifies a table
          DROP TABLE - deletes a table
          CREATE INDEX - creates an index (search key)
          DROP INDEX - deletes an index
        * SQL Keywords
            Keyword	Description
            ADD	Adds a column in an existing table
            ADD CONSTRAINT	Adds a constraint after a table is already created
            ALL	Returns true if all of the subquery values meet the condition
            ALTER	Adds, deletes, or modifies columns in a table, or changes the data type of a column in a table
            ALTER COLUMN	Changes the data type of a column in a table
            ALTER TABLE	Adds, deletes, or modifies columns in a table
            AND	Only includes rows where both conditions is true
            ANY	Returns true if any of the subquery values meet the condition
            AS	Renames a column or table with an alias
            ASC	Sorts the result set in ascending order
            BACKUP DATABASE	Creates a back up of an existing database
            BETWEEN	Selects values within a given range
            CASE	Creates different outputs based on conditions
            CHECK	A constraint that limits the value that can be placed in a column
            COLUMN	Changes the data type of a column or deletes a column in a table
            CONSTRAINT	Adds or deletes a constraint
            CREATE	Creates a database, index, view, table, or procedure
            CREATE DATABASE	Creates a new SQL database
            CREATE INDEX	Creates an index on a table (allows duplicate values)
            CREATE OR REPLACE VIEW	Updates a view
            CREATE TABLE	Creates a new table in the database
            CREATE PROCEDURE	Creates a stored procedure
            CREATE UNIQUE INDEX	Creates a unique index on a table (no duplicate values)
            CREATE VIEW	Creates a view based on the result set of a SELECT statement
            DATABASE	Creates or deletes an SQL database
            DEFAULT	A constraint that provides a default value for a column
            DELETE	Deletes rows from a table
            DESC	Sorts the result set in descending order
            DISTINCT	Selects only distinct (different) values
            DROP	Deletes a column, constraint, database, index, table, or view
            DROP COLUMN	Deletes a column in a table
            DROP CONSTRAINT	Deletes a UNIQUE, PRIMARY KEY, FOREIGN KEY, or CHECK constraint
            DROP DATABASE	Deletes an existing SQL database
            DROP DEFAULT	Deletes a DEFAULT constraint
            DROP INDEX	Deletes an index in a table
            DROP TABLE	Deletes an existing table in the database
            DROP VIEW	Deletes a view
            EXEC	Executes a stored procedure
            EXISTS	Tests for the existence of any record in a subquery
            FOREIGN KEY	A constraint that is a key used to link two tables together
            FROM	Specifies which table to select or delete data from
            FULL OUTER JOIN	Returns all rows when there is a match in either left table or right table
            GROUP BY	Groups the result set (used with aggregate functions: COUNT, MAX, MIN, SUM, AVG)
            HAVING	Used instead of WHERE with aggregate functions
            IN	Allows you to specify multiple values in a WHERE clause
            INDEX	Creates or deletes an index in a table
            INNER JOIN	Returns rows that have matching values in both tables
            INSERT INTO	Inserts new rows in a table
            INSERT INTO SELECT	Copies data from one table into another table
            IS NULL	Tests for empty values
            IS NOT NULL	Tests for non-empty values
            JOIN	Joins tables
            LEFT JOIN	Returns all rows from the left table, and the matching rows from the right table
            LIKE	Searches for a specified pattern in a column
            LIMIT	Specifies the number of records to return in the result set
            NOT	Only includes rows where a condition is not true
            NOT NULL	A constraint that enforces a column to not accept NULL values
            OR	Includes rows where either condition is true
            ORDER BY	Sorts the result set in ascending or descending order
            OUTER JOIN	Returns all rows when there is a match in either left table or right table
            PRIMARY KEY	A constraint that uniquely identifies each record in a database table
            PROCEDURE	A stored procedure
            RIGHT JOIN	Returns all rows from the right table, and the matching rows from the left table
            ROWNUM	Specifies the number of records to return in the result set
            SELECT	Selects data from a database
            SELECT DISTINCT	Selects only distinct (different) values
            SELECT INTO	Copies data from one table into a new table
            SELECT TOP	Specifies the number of records to return in the result set
            SET	Specifies which columns and values that should be updated in a table
            TABLE	Creates a table, or adds, deletes, or modifies columns in a table, or deletes a table or data inside a table
            TOP	Specifies the number of records to return in the result set
            TRUNCATE TABLE	Deletes the data inside a table, but not the table itself
            UNION	Combines the result set of two or more SELECT statements (only distinct values)
            UNION ALL	Combines the result set of two or more SELECT statements (allows duplicate values)
            UNIQUE	A constraint that ensures that all values in a column are unique
            UPDATE	Updates existing rows in a table
            VALUES	Specifies the values of an INSERT INTO statement
            VIEW	Creates, updates, or deletes a view
            WHERE	Filters a result set to include only records that fulfill a specified condition
   ## MySQL 
        Docs: https://docs.google.com/document/d/1tDPgLoE1SakXJlwBF283nG12iUaBVy-OngmFaC4KHbI/edit
        
      * INT
        DECIMAL(M, N)
        VARCHAR(l)
        BLOB
        DATE
        TIMESTAMP
      
      * CREATE TABLE student(
          student_id INT PRIMARY KEY,
          name VARCHAR(1000)
          major VARCHAR(20)
          PRIMARY KEY(student_id)
          
        );
        
        SELECT * FROM student;
        
        DESCRIBE student;
        
        DROP TABLE student;
        
        ALTER TABLE student ADD gpa DECIMAL(3,2);
        
        ALTER TABLE student DROP COLUMN gpa;
        
        INSERT INTO student VALUES(1, 'Jack', 'Biology'); 
        
 ## MongoDB
     * MongoDB stores data in JSON-like documents, which makes the database very flexible and scalable.

            
## The Cloud
        * Basically is using someone else's server to put your data.
         
        * It makes much easier for people and smaller companies to scale automatically.
         
        * DNS (Domain Name System) -  Es un sistema de nomenclatura jerárquico descentralizado para dispositivos conectados a redes IP como Internet o una red privada. Este sistema asocia información variada con nombres de dominio asignados a cada uno de los participantes. Su función más importante es "traducir" nombres inteligibles para las personas en identificadores binarios asociados con los equipos conectados a la red, esto con el propósito de poder localizar y direccionar estos equipos mundialmente.
        * El servidor DNS utiliza una base de datos distribuida y jerárquica que almacena información asociada a nombres de dominio en redes como Internet. Aunque como base de datos el DNS es capaz de asociar diferentes tipos de información a cada nombre, los usos más comunes son la asignación de nombres de dominio a direcciones IP y la localización de los servidores de correo electrónico de cada dominio.

        * IP - Los dispositivos se conectan entre sí mediante sus respectivas direcciones IP. Sin embargo, para las personas es más fácil recordar un nombre de dominio que los números de la dirección IP. Los servidores de nombres de dominio DNS, "traducen" el nombre de dominio en una dirección IP. Si la dirección IP dinámica cambia, es suficiente actualizar la información en el servidor DNS. El resto de las personas seguirán accediendo al dispositivo por el nombre de dominio.
 
        * PaaS - Platform as Service. Example: Heroku. It makes it easier for you to run your applications in the cloud.
        
        * SaaS - Software as Service. Example: Gmail.com. Web-based email service.
        
        * https://bush-socks-586.notion.site/Curso-de-Introducci-n-a-la-Nube-con-Azure-902361fc98974378874c7ce1943cd5e4
  
  ## Cloud CS50
        * https://www.youtube.com/watch?v=twMcvPSuDnk
            
  # Git - GitHub
  
     ## What is Git?
      * Free an open source version control system

     ## What is Version Control?
      * The management of changes to documents, computer programs, large web sites, and other collection of information.
  
   Terms
  
    * Directory -> Folder
    * Terminal or Command Line -> Interface for text commands
    * CLI -> Command Line Interface
    * cd -> Change Directory
    * Code Editor -> Word processor for Writing Code
    * Repository -> Project, or the folder/place where your project is 
    * Github -> A website to host your repositories online 
  
  
  ## Recursion 
  
        Public class sumOfNaturalNumber {
          public static int recursivesummation(int inputNumber) { inputNUmber = 2
            if (inputNumber <= 1) 
                return inputNumber;
              return inputNumber + recursiveSummation(inputNumber - 1); inputNumber = 2;
                 }
               }                 

         public static void main(String[] args) {
            int result = recursiveSummation(5);
            int result2 = recursiveSummation(10);
            System.out.printIn(result);
            System.out.printIn(result2);
                }
              }
                      
  
  ## Git commands
                           
    * Clone -> Bring a repository that is hosted somewhere like Github into a folder on your local machine
    * add -> Track your files and change in Git 
    * commit -> Save your files in Git
    * Push -> Upload Git commits to a remote repo, like Github
    * Pull -> Download changes from a remote repo to your local machine, the opposite of push
  
  ## What is forking?
  
    * A way of creating a copy of the given repository so that it belongs to our user
  
  ## What is a pull request?
  
    * A commit or series of commits that you send to the owner of the repository so that thet incorporate it into their tree
  
        
   ## Upload a Proyect to GitHub
    
    * https://lab.github.com/
    * https://www.freecodecamp.org/news/the-beginners-guide-to-git-github/
    * https://www.youtube.com/watch?v=MJUJ4wbFm_A
    * https://www.youtube.com/watch?v=eulnSXkhE7I
    * https://www.kyocode.com/2018/05/subir-codigo-a-github-con-visual-studio-code/
    * https://eagledev.hashnode.dev/how-to-upload-an-existing-project-to-github-using-vsc-visual-studio-code
    * https://dev.to/codebeast/how-to-publish-a-new-project-to-github-with-vs-code-47hb
    * https://www.youtube.com/watch?v=qsTthZi23VE
    
   ## What’s a version control system?
  
         A version control system, or VCS, tracks the history of changes as people and teams collaborate on projects together. As the project evolves, teams can run tests, fix bugs, and contribute new code with the confidence that any version can be recovered at any time. Developers can review project history to find out:

         Which changes were made?
         Who made the changes?
         When were the changes made?
         Why were changes needed?
        
   ## What’s a distributed version control system?
         
         Git is an example of a distributed version control system (DVCS) commonly used for open source and commercial software development. DVCSs allow full access to every file, branch, and iteration of a project, and allows every user access to a full and self-contained history of all changes. Unlike once popular centralized version control systems, DVCSs like Git don’t need a constant connection to a central repository. Developers can work anywhere and collaborate asynchronously from any time zone.

         Without version control, team members are subject to redundant tasks, slower timelines, and multiple copies of a single project. To eliminate unnecessary work, Git and other VCSs give each contributor a unified and consistent view of a project, surfacing work that’s already in progress. Seeing a transparent history of changes, who made them, and how they contribute to the development of a project helps team members stay aligned while working independently.
  
  ## Basic Git commands
  
      To use Git, developers use specific commands to copy, create, change, and combine code. These commands can be executed directly from the command line or by using an application like GitHub Desktop or Git Kraken. Here are some common commands for using Git:

         * git init initializes a brand new Git repository and begins tracking an existing directory. It adds a hidden subfolder within the existing directory that houses the internal data structure required for version control.

         * git clone creates a local copy of a project that already exists remotely. The clone includes all the project’s files, history, and branches.

         * git add stages a change. Git tracks changes to a developer’s codebase, but it’s necessary to stage and take a snapshot of the changes to include them in the project’s history. This command performs staging, the first part of that two-step process. Any changes that are staged will become a part of the next snapshot and a part of the project’s history. Staging and committing separately gives developers complete control over the history of their project without changing how they code and work.

         * git commit saves the snapshot to the project history and completes the change-tracking process. In short, a commit functions like taking a photo. Anything that’s been staged with git add will become a part of the snapshot with git commit.

         * git status shows the status of changes as untracked, modified, or staged.

         * git branch shows the branches being worked on locally.

         * git merge merges lines of development together. This command is typically used to combine changes made on two distinct branches. For example, a developer would merge when they want to combine changes from a feature branch into the main branch for deployment.

         * git pull updates the local line of development with updates from its remote counterpart. Developers use this command if a teammate has made commits to a branch on a remote, and they would like to reflect those changes in their local environment.

         * git push updates the remote repository with any commits made locally to a branch.
         
   ## How GitHub works
   
      GitHub builds collaboration directly into the development process. Work is organized into repositories, where developers can outline requirements or direction and set expectations for team members. Then, using the GitHub flow, developers simply create a branch to work on updates, commit changes to save them, open a pull request to propose and discuss changes, and merge pull requests once everyone is on the same page.
      
 # Learn Enough Git to be Dangerous    
      
   ## Initializing the repo
   
      Now it’s time to start creating a project and put it under version control with Git.
      We’ll be making a simple website consisting of two pages, a Home page and an
      About page.7 We’ll begin by making a directory with the generic name website
      inside a directory called repos:
      
      [~]$ mkdir -p repos/website
      
      Here we’ve used the “make directory” command mkdir covered in Learn
      Enough™ Command Line to Be Dangerous, together with the -p option, which
      arranges for mkdir to create intermediate directories as required (in this case,
      repos). Note also that I’ve included the current directory in the prompt (in this
      case, [~]) as arranged by the configuration in Listing 33.
      After making the directory, we can cd into it as follows:
      
      [~]$ cd repos/website/
      
      [website]$

      All Git commands consist of the command-line program git followed by the name
      of the command, so the full command to initialize a repository is git init, as
      shown in Listing 2.
      
      Listing 2: Initializing a Git repository.
      [website]$ git init
      Initialized empty Git repository in /Users/mhartl/repos/website/.git/
      [website (master)]$
      
      The way to create a new repository with Git is with the init command (short for “initialize”),
      which creates a special hidden directory where Git stores the information it needs
      to track our project’s changes.
      
   ## Our first commit
      
      Git won’t let us complete the initialization of the repository while it’s empty, so we
      need to make a change to the current directory. We’ll make a more substantive
      change in a moment, but for now we’ll follow a common convention and simply
      use touch to create an empty file (as mentioned in Learn Enough™ Command
      Line to Be Dangerous). In this case, we’re making a simple website, and the nearuniversal
      convention is to call the main page index.html:
      
      [website (master)]$ touch index.html
      Having created this first file, we can use the git status command to see the
      result:
      
      [website (master)]$ git status
      On branch master
      Initial commit
      Untracked files:
      (use "git add <file>..." to include in what will be committed)
      index.html
      nothing added to commit but untracked files present (use "git add" to track)
      
      We see here that the index.html file is “untracked”, which means Git doesn’t yet
      know about it. We can add it using the git add command:
      [website (master)]$ git add -A
      
      As implied by the word “unstage”, the status of the file has been promoted from
      untracked to staged, which means the file is ready to be added to the repository.
      Untracked/unstaged and staged are two of the four states commonly used by Git,
      as shown in Figure 4.
      
      (...)after putting changes in the staging area we can make them
      part of the local repository by committing them using git commit.
      
      Most uses of git commit
      
      use the command-line option -m to include a message indicating the purpose of the
      commit (Box 4). In this case, the purpose is to initialize the new repository, which
      we can indicate as follows:
      
      [website (master)]$ git commit -m "Initialize repository"
      [master (root-commit) 879392a] Initialize repository
      1 file changed, 0 insertions(+), 0 deletions(-)
      create mode 100644 index.html
      
   ## Committing to Git
      
      By design, Git requires every commit to include a commit message describing
      the purpose of the commit. Typically, this takes the form of a single line,
      usually limited to around 72 characters, with an optional longer message if
      desired (Section 4.2.3). Although conventions for commit messages vary
      (Figure 5),8 the style adopted in this tutorial is to write commit messages in the
      present tense using the imperative mood, as in “Initialize repository” rather than
      “Initializes repository” or “Initialized repository”. The reason for this
      convention is that Git models commits as a series of text transformations, and in
      this context it makes sense to describe what each commit does instead of what it
      did. Moreover, this usage agrees with the convention followed by the commit
      messages generated by Git commands themselves (e.g., “merge” rather than
      “merges” or “merged”).
      
      At this point, we can use git log to see a record of our commit:
      [website (master)]$ git log
      commit 879392a6bd8dd505f21876869de99d73f40299cc
      Author: Michael Hartl <michael@michaelhartl.com>
      Date: Thu Dec 17 20:00:34 2015 -0800
      Initialize repository
      The commit is identified by a hash, which is a unique string of letters and numbers
      that Git uses to label the commit and which lets Git retrieve the commit’s changes.
      In my case, the hash appears as
      879392a6bd8dd505f21876869de99d73f40299cc
      
      Git has a similar function, git diff, which by default just shows the difference
      between the last commit and unstaged changes in the current project:
      [website (master)]$ git diff
      diff --git a/index.html b/index.html
      index e69de29..4b5fa63 100644
      --- a/index.html
      +++ b/index.html
      @@ -0,0 +1 @@
      +hello, world
      Because the content added in Section 1.3 was empty, here the diff appears simply
      as an addition:
      +hello, world
      We can commit this change by passing the -a option (for “all”) to git commit,
      which arranges to commit all the changes in currently existing files
      
      We can confirm that the change went through by
      running git log:
      [website (master)]$ git log
      commit 03aff34ec4f9690228e057a4252bcca169a868b4
      Author: Michael Hartl <michael@michaelhartl.com>
      Date: Thu Dec 17 20:03:33 2015 -0800
      Add content to index.html
      commit 879392a6bd8dd505f21876869de99d73f40299cc
      Author: Michael Hartl <michael@michaelhartl.com>
      Date: Thu Dec 17 20:00:34 2015 -0800
      Initialize repository
      
  ## Opening a file to work on it
      
      (...) As in previous sections, we’ll be working on the main index.html file. Let’s start
      by opening this file in both a text editor and in a web browser. My preferred
      method for doing this is at the command line using the atom and open commands
      (though the latter works only on Macintosh OS X):
      [website (master)]$ atom index.html
      [website (master)]$ open index.html
      
      As before, we’ll run git status and git diff to learn more about what we’re
      going to commit to Git, though with experience you’ll come to run these
      commands only when necessary. The status simply indicates that index.html has
      been modified:
      [website (master)]$ git status
      On branch master
      Changes not staged for commit:
      (use "git add <file>..." to update what will be committed)
      (use "git checkout -- <file>..." to discard changes in working directory)
      modified: index.html
      no changes added to commit (use "git add" and/or "git commit -a")
      
      Important commands from this section are summarized in Table 1.
      
      Command         |   Description                           |    Example
            
      git help          Get help on a command                     $ git help push
      git config        Configure Git                             $ git config --
                                                                   global …
                                                                  $ source
      source            Activate Bash changes                      ~/.bash_profile
      <file>
                        
      mkdir -p          Make intermediate directories             $ mkdir -p
                        as necessary                              repos/website 

      git status        Show the status of the                    $ git status
                        repository

      touch <name>      Create empty file $ touch foo             $ touch foo
      git add           -A Add all files or directories to
                        staging area
      $ git add -A      Add given file or directory to            $ git add foo
                        staging area
      git add
      <name>

      git commit -m     Commit staged changes with a              $ git commit -m "Addthing"                       
                        message

      git commit -am    Stage and commit changes with a message   $ git commit -am
                                                                    "Add thing"
      git diff          Show diffs between commits,               $ git diff
                        branches, etc.

      git commit -      -amend Amend the last commit              $ git commit --amend
      git show
      <SHA>             Show diff vs. the SHA                     $ git show fb738e…
      
  ## Backing up and sharing
   
      With the changes made in Section 1, we’re now ready to push a copy of our project
      to a remote repository. This will serve as a backup of our project and its history,
      and will also make it easier for collaborators to work with us on our site.
      We’ll start by pushing our project up to GitHub, a site designed to facilitate
      collaboration with Git repositories. For repositories that are publicly available,
      GitHub is free, so we’ll plan to make our website’s repo public to take advantage
      of this.
      
      Over time, releasing projects publicly on GitHub serves to build up
      a portfolio, which is one good reason to make as much work public as possible.
      
  ## Remote repo
   
      After signing up for a GitHub account, the next step is to create a remote
      repository.
      After clicking the green “Create repository” button seen in Figure 18, you should
      see a page like Figure 19 containing instructions for how to push your local
      repository up to GitHub. The exact commands will be tailored to your personal
      account name; the template looks like Listing 9. (It is not important to understand
      these commands at this time.)
      Listing 9: A template for the first push to GitHub.
      [website (master)]$ git remote add origin https://github.com/<name>/website.git
      [website (master)]$ git push -u origin master

      Of course, you should replace <name> with your actual username. For example,
      the commands for my username, which is mhartl, look like this (which you can
      also see in Figure 19):
      [website (master)]$ git remote add origin https://github.com/mhartl/website.git
      [website (master)]$ git push -u origin master
      
      The two commands in Listing 9 first set GitHub as the remote origin and then push
      the full repository.
      
      After executing the first git push as shown in Listing 9, you should reload the
      current page (using, e.g., ⌘R or the icon shown in Figure 20). The result should
      look something like Figure 21. If it does, you have officially shipped your first Git
      repository!
      
  ## Adding a README
   
      Now that we’ve pushed up our repository, let’s add a second file and practice the
      add, commit, and push sequence shown in Figure 4. You may have noticed in
      Figure 21 that GitHub encourages the presence of a README file via the note
      “Help people interested in this repository understand your project by adding a
      README.”
      
      Now that we’ve created the README.md file, we’re ready to add it to our Git
      repository and push it up. We can’t just run git commit -am because README.md
      isn’t currently in the repository, so we have to add it first:
      [website (master)]$ git add -A
      
      Then we commit as usual:
      [website (master)]$ git commit -m "Add README file"
      
      Having added the file to the repository and made a commit, we’re now ready to
      push up to GitHub.
      
      [website (master)]$ git push
      
      Important commands from this section are summarized in Table 2.
      
      Command                    Description                            Example
      
      git remote add              Add remote repo                        $ git remote add
                                                                          origin
      git push -u <loc>           Push to branch to                     $ git push -u origin
      <br>                        remote                                  master
      git push                    Push to default                       $ git push
                                  remote        
      
  ## Branching and merging
   
      One of the most powerful features of Git is its ability to make branches, which are
      effectively complete self-contained copies of the project source, together with the
      ability to merge one branch into another, thereby incorporating the changes into the
      original branch. The best thing about a branch is that you can make your changes
      to the project in isolation from the master copy of the code, and then merge your
      changes in only when they’re done. This is especially helpful when collaborating
      with other users (Section 4); having a separate branch lets you make changes
      independently from other developers, reducing the risk of accidental conflicts.
     
      Our plan is to make a series of changes on the about-page
      branch, and then incorporate the changes back into the master branch using git
      merge.
      
      [website (about-page)]$ git add -A && git commit -m "Add About page"
      
      Having finished with the changes to index.html, we can make a commit as usual
      with git commit -am:
      [website (about-page)]$ git commit -am "Add a link to the About page"
      
      Having merged in the changes, we can sync up the local master branch with the
      version at GitHub (called origin/master) as usual:
      [website (master)]$ git push
      
 ##  Recovering from errors
   
      One of the most useful features of Git is its ability to let us recover from errors that
      would otherwise be catastrophic. The error-recovery techniques themselves can be
      dangerous, though, so they should always be implemented with care.
      Let’s consider a common scenario where we make an unintentional change to a
      project and want to get back to the state of the repository as of the most recent
      commit (a state known as HEAD).
      
   	 Command                 Description                                  Example
   
      .gitignore           Tell Git which things to ignore              $ echo .DS_store >>
                                                                        .gitignore
      git checkout
      <br>                 Check out a branch                          $ git checkout
                                                                        master
      git checkout
      -b <br>              Check out & create a branch                  $ git checkout -b
      about-page
      git branch           Display local branches                       $ git branch
      git merge
      <br>                 Merge in a branch                            $ git merge aboutpage
      git rebase           Do something possibly weird &                See figure 2 & 3
                           confusing
      
      git branch -
      d <br>               Delete branch (if merged)                    $ git branch -d
                                                                        about-page
      git branch -         Delete branch (even if
      D <br>               unmerged) (dangerous)                        $ git branch -D
                                                                          other-branch
      git checkout         Force checkout, discarding                   $ git add -A && git
      -f                   changes (dangerous)                            checkout -f
     
  ## Collaborating
   
      Now that we’ve covered some of the tools needed to use Git effectively on solo
      projects, it’s time to learn about what is perhaps Git’s greatest strength: making it
      easier to collaborate with other people. This is especially the case when using
      repository hosts like GitHub or Bitbucket, but it is also possible to host Git
      repositories on private servers (sometimes using software like GitLab to get many
      GitHub-like benefits).                      

      Command                             Description                                  Example
      
      git clone                           Copy repo (incl. full history) to            $ git clone
      <URL>                               local disk                                   https://ex.co/repo.git  
      git pull                            Pull in changes from remote                  $ git pull
                                          repository
      git branch                          -a List all branches $ git branch -a         $ git checkout fix
      git checkout                        Check out remote branch and                  trademark
      <br>                                configure for push                           $ git push -u origin
                                                                 
      gh-pages                            Branch name for production                     gh-pages
                                          website
                                          
 
   ## The GitHub flow
   
      The GitHub flow is a lightweight, branch-based workflow built around core Git commands used by teams around the globe—including ours.

      The GitHub flow has six steps, each with distinct benefits when implemented:

      * Create a branch: Topic branches created from the canonical deployment branch (usually main) allow teams to contribute to many parallel efforts. Short-lived topic branches, in particular, keep teams focused and results in quick ships.
      * Add commits: Snapshots of development efforts within a branch create safe, revertible points in the project’s history.
      * Open a pull request: Pull requests publicize a project’s ongoing efforts and set the tone for a transparent development process.
      * Discuss and review code: Teams participate in code reviews by commenting, testing, and reviewing open pull requests. Code review is at the core of an open and participatory culture.
      * Merge: Upon clicking merge, GitHub automatically performs the equivalent of a local ‘git merge’ operation. GitHub also keeps the entire branch development history on the merged pull request.
      * Deploy: Teams can choose the best release cycles or incorporate continuous integration tools and operate with the assurance that code on the deployment branch has gone through a robust workflow.
   
   ## GitHub and the command line
   
      For developers new to the command line, the GitHub Training team has put together a series of tutorials on Git commands to guide the way. Sometimes, a series of commands can paint a picture of how to use Git:

     ### Example: Contribute to an existing repository

        # download a repository on GitHub.com to our machine
        git clone https://github.com/me/repo.git

        # change into the `repo` directory
        cd repo

        # create a new branch to store any new changes
        git branch my-branch

        # switch to that branch (line of development)
        git checkout my-branch

        # make changes, for example, edit `file1.md` and `file2.md` using the text editor

        # stage the changed files
        git add file1.md file2.md

        # take a snapshot of the staging area (anything that's been added)
        git commit -m "my snapshot"

        # push changes to github
        git push --set-upstream origin my-branch

     ### Example: Start a new repository and publish it to GitHub

        First, you will need to create a new repository on GitHub. You can learn how to create a new repository in our Hello World guide. Do not initialize the repository with a README, .gitignore or License. This empty repository will await your code.

        # create a new directory, and initialize it with git-specific functions
        git init my-repo

        # change into the `my-repo` directory
        cd my-repo

        # create the first file in the project
        touch README.md

        # git isn't aware of the file, stage it
        git add README.md

        # take a snapshot of the staging area
        git commit -m "add README to initial commit"

        # provide the path for the repository you created on github
        git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git

        # push changes to github
        git push --set-upstream origin main
        Example: contribute to an existing branch on GitHub
        # assumption: a project called `repo` already exists on the machine, and a new branch has been pushed to GitHub.com since the last time changes were made locally

        # change into the `repo` directory
        cd repo

        # update all remote tracking branches, and the currently checked out branch
        git pull

        # change into the existing branch called `feature-a`
        git checkout feature-a

        # make changes, for example, edit `file1.md` using the text editor

        # stage the changed file
        git add file1.md

        # take a snapshot of the staging area
        git commit -m "edit file1"

        # push changes to github
        git push

   ## Make the move - Moving your local project to GitHub
   
      Having a project already stored locally enables you to move it to GitHub rather quickly. The following activity provides instructions to move your local project to GitHub using various tools. Select the tool you are most comfortable with and get importing 😄.

   Moving your local project 
      
      In the Code tab of this repository, copy the URL shown under Quick Setup.
      Follow the instructions below based on what tool you'd like to use locally.
      
         * Using the command line
            
                 * In your command line, navigate to your project directory. Type git init to initialize the directory as a Git repository.
                 * Type git remote add origin https://github.com/macmullensantiago/github-upload.git
                 * Type git add .
                 * Type git commit -m "initializing repository"
                 * Type git push -u origin main to push the files you have locally to the remote on GitHub. (You may be asked to log in.)
                  Note: You can also use a password protected SSH key to connect to GitHub. See Connecting to GitHub with SSH in our documentation to learn more.

         
         * Using GitHub Desktop
            
                  GitHub Desktop doesn't allow you to add a new remote for an existing directory, so instead we'll copy the contents of your existing folder to our repo. If you'd like to keep your existing folder, you may want to use the command line or one of the other tools.

                  * In GitHub Desktop, click on File and Clone a repository.
                  * Click on the URL tab.
                  * Paste the URL from this repository.
                  * Move the contents of your local repository to this directory.
                  * Create a commit by entering a commit message and then clicking on Commit to main
                  * Click Publish branch in the top right corner to push your repository to GitHub.
                  
         * Using Visual Studio Code
         
                  * In Visual Studio Code, open the folder for your project.
                  * Click the icon on the left for Source Control.
                  * On the top of the Source Control panel, click the Git icon.
                  * If the files you see match the repository you want to create, click Initialize Repository.
                  * Next to the word CHANGES, click the symbol of the plus sign to stage all of the changes.
                  * This is part of the two stage commit. You can use this staging function to create meaningful commits throughout the development process.
                  * In the box in the Source Control panel, type a commit message. Something like "initial commit - moving project" could work.
                  * Click the checkmark at the top of the Source Control panel.
                  * Open the integrated terminal found under View > Integrated Terminal.
                  * In your command line, type git remote add origin https://github.com/macmullensantiago/github-upload
                  * In the Source Control Panel, click the expandable three dots that open a menu of options.
                  * When asked if you'd like to publish the branch, click Okay.

         
         * Using Atom
         
                  * In Atom, open the folder for your project
                  * At the top of your screen, click Packages. Select GitHub, and then toggle the Git Tab from the drop-down menu.
                  * Select Create Repository within the Git tab on the right-hand size of your screen.
                  * Select Init to accept the default prompt of the pop up window
                  * In the Git tab, you can see that your files are ready for staging. It should be accounted for, but double check to make sure that none of your binaries or files that you listed in the .gitignore are listed in this dialog menu.
                  - If they are, double check your .gitignore file to make sure they're included or remove them from your directory.
                  Select Stage All
                  - This is part of the two stage commit. You can use this staging function to create meaningful commits throughout the development process.
                  * In the box at the bottom of the Git panel, type a commit message. Something like "initial commit - moving project" could work.
                  * Select Commit
                  * Close Atom
                  * In your command line, navigate to your project directory.
                  * Type git remote add origin https://github.com/macmullensantiago/github-upload
                  * Return to Atom, and select the Up/Down arrow icon at the bottom of your Git Tab
                  * Click Push, above the noted dialog.
                  * Return to your repository, and note a successful push by finding your files on GitHub's code tab.
         
         * Using Eclipse
         
            * In Eclipse, from the Eclipse Marketplace, install the eGit GitHub plugin.
            * Open your existing project.
            * Display the Git Repositories window by selecting Window > Show View > Other > Git > Git Repositories.
            * Click the Create a Git Repository button on the Git Repositories pane.
            * Make changes to your project and create a commit.
            * Push the changes to your default branch.
            * When asked for a remote, paste the URL you copied earlier.
            * Click next, and enter the branch name.
            
            * https://stackoverflow.com/questions/12799719/how-to-upload-a-project-to-github

   ## GitHub Pages
        
            Once you have an account at GitHub (and have verified your emailed address),
            you can use a free feature called GitHub Pages that allows you to host simple
            HTML sites for free on GitHub’s infrastructure.
            This is a major advance compared to the bad old days of the early Web. For
            example, if this were 1999, you’d not only have to pay money for the hosting, but
            you’d also be on the hook for the cost of transferring the data to the people visiting
            your site. For sites with even moderate traffic, the bills could add up fast.
            Nowadays, we have many better options, GitHub Pages among them. Not
            only is GitHub Pages free, but it is incredibly easy to use. When you host a repo at
            GitHub, any valid HTML stored on the gh-pages branch of the repo is available
            online (nearly) instantly. 
            All you need to do is commit your changes on the branch
            and push the commit to GitHub. GitHub Pages takes care of the rest.
            
            We’ll get started by making a directory and an initial repository for our
            sample website. First, open a terminal window and make a directory called
            sample_website:
            
            $ mkdir -p repos/sample_website
            
            Next, cd into the directory and touch the file for the main page of the site,
            which should be called index.html:
            
            $ cd repos/sample_website
            $ touch index.html
            Then initialize the repository:
            $ git init
            $ git add -A
            $ git commit -m "Initialize repository"
            
            The reason we created a file using touch is because Git won’t initialize an
            empty repository.5 The reason we’ve called it index.html is because that’s
            the default filename for “home” pages on theWeb, and most sites will automat-
            ically serve up index.html when you hit the bare domain.
         
            With the repo initialized, we’re now ready to push our (nearly) empty repo
            up to GitHub. As in Learn Enough Git to Be Dangerous, you should go to
            github.com, log in if necessary, and then create a new repository using the name
            sample_website and the description
            
            After creating the remote repo, you should set the remote origin as the main
            URL for the repo, which you can find as shown in Figure 8:
            $ git remote add origin <repo url>
            
            At this point, you would ordinarily follow the instructions at GitHub by
            pushing up the default master branch, but recall that GitHub Pages uses the
            special gh-pages branch (Box 3) in place of master. As a result, before
            proceeding we’ll create the gh-pages branch using the -b option to git
            checkout7 and then push it to GitHub:
            
            $ git checkout -b gh-pages
            $ git push -u origin gh-pages
            
            Note that the “URL” in this Figure 14 will be a local file, like this:
            file:///Users/mhartl/repos/sample_website/index.html
            This is because the index page is on our local system, and hasn’t yet been
            deployed to the live Web.
            We know how to remedy this, though—commit our changes to the local Git
            repository and push up to GitHub Pages:
            
            $ git commit -am "Add a short paragraph"
            $ git push
            Upon refreshing
            
            With that, we’re ready to commit our changes and push the results to Git-
            Hub Pages:
            $ git commit -am "Convert index page to fully valid HTML"
            $ git push
            
            In order to link the kitten image, we could link directly to the source of
            Figure 33 from the live Web, like this:
            <img src="http://example.com/images/kitten.jpg" alt="An adorable kitten">
            This practice, called hotlinking, is generally considered bad form, for reasons
            we’ll explain in Section 2.4.1. Instead, we’ll copy the image to the local com
            puter, which will then be uploaded automatically when we deploy to GitHub
            pages.
            To do this, first create a directory called images:
            $ mkdir images
            Creating a separate images directory isn’t strictly necessary, but it’s useful for
            keeping our main project directory tidy. Next, download the image to the local
            disk using curl:12
            $ curl -o images/kitten.jpg -OL cdn.learnenough.com/kitten.jpg
            
            With that, our sample website’s index page has (nearly) taken its final form,
            so now is a good time to commit the changes and push to the live server at
            GitHub Pages:
            
            $ git add -A
            $ git commit -m "Add some images"
            $ git push
            
            Congratulations! You know know enough HTML to be dangerous. All that’s
            left is to commit and deploy the final sample website:
            $ git commit -am "Finish the sample website"
            $ git
            
            Tag                         Name                          Purpose
            h1–h6                       headings                      include a heading (levels 1–6)
            p                           paragraph                     include a paragraph of text
            table                       table                         include a table
            tr                          table                         row include a row of data
            th                          table                         header make a table header
            td                          table data                    include a table data cell
            div                         division                      define block-level section in document
            header                      header                        label the page header
            ol                          ordered list                  list elements in numerical order
            ul                          unordered list                list elements whose order doesn’t matter
            li                          list item                     include a list item (ordered or unordered)
            blockquote                  block quotation               show formatted quotation
            br                          break                         enter line break
            
            

            Tag               Name                 Purpose                 Example                          Result
            em                emphasized           make emphasized         <em>technical                    technical sophis-
                                                   text                    sophistication</em>              tication
            strong            strong               make strong text        <strong>at                       at least a billion
                                                                                                            people
                                                                            least a
                                                                            billion
                                                                            people</strong>                       
           a                   anchor               make hyperlink          <a                              Learn Enough
                                                                            href="#">                    
                                                                            Learn
                                                                            Enough</a>
           img                image                 include an image        <img
                                                                            src="mhartl.jpg"
                                                                            alt="Michael
                                                                            Hartl">
           code               code                   format as source       <code>table</code>              table
                                                     code
           span                span                  define inline sec-    <span>Call                       Call me Ishmael.
                                                     tion in document       me
                                                                            Ishmael.</span>         
                                                      
   
   ## GitHub Learning Resources
      
      * https://guides.github.com/
      * https://www.youtube.com/githubguides
      * One helpful command for learning Git is git help, which by itself gives
      general guidelines on Git usage, and when applied to a specific command gives
      further information on that command. For example, git help add shows
      details about the git add command.
      * https://riskledger.com/blog/git-basics-at-risk-ledger/
      * https://docs.github.com/es/github/importing-your-projects-to-github/importing-source-code-to-github/adding-an-existing-project-to-github-using-the-command-line
      
   ## Stanford Git Resources
   
      * Using Git
         Written by Li Deng, with modifications by Nick Troccoli

         Disclaimer: Most students won't even notice or interact much with git during CS107. But for those of you who are curious to know more, here is an introduction to git.

         You probably have seen the ubiquitous logo of github below(left), while rarely seeing the logo of git (right). Actually git is the workhorse behind the scene! git is a power tool in your arsenal as a software developer that lets you manage versions of your work.

         Github
         
         Git

         The use of git in CS107
         Version control is a tool used by developers to manage the source code in a project and git is one of the most popular version control systems in use today.

         CS107 uses git to distribute starter code to you and receive your submissions for grading. Most of the interaction with git is hidden away within our tools. This means you won't have to tackle learning the system now and will need only to learn a few simple commands for the quarter. However, you will eventually want to gain some mastery, so now could be your chance to practice with these tools in preparation for future need.

         Your one git command
         The one git command that you must know for CS107: git clone

         Try running:

         git clone /afs/ir/class/cs107/repos/assign0/$USER assign0
         There is a remote repo already prepared for you at /afs/ir/class/cs107/repos/assign0/$USER, and you are fetching a local copy of that repo and putting it in a directory named assign0 in your current working directory.

         The general format of the command is:

         git clone <repo> <dirname>
         and here is a specific instance to clone the lab1 starter:

         git clone /afs/ir/class/cs107/repos/lab1/shared mylab1
         This is the way that you will get starter code for every assignment and lab throughout this course.

         When you are ready to submit, you will use our submit command:

         tools/submit
         This command submits your work to be graded; it uses git behind the scenes to copy your finished work into your class repo.

         That's it! If you are comfortable having our tools take care of you, you can stop reading right here and sleep easy knowing that version control is working behind the scenes for you.

         Going further with version control (optional)
         You won't need to learn more for CS107, but if you are curious, below is an overview version control and introduction to a few basic git commands.

         A version control system broadly does two things:

         It tracks all changes made to each file (which you can review to see your progress or undo if some changes turned out to be a bad idea)
         It can merge different versions (so team members can work independently and easily join their work together)
         Version control allows you to explore changes while maintaining the option to undo them if they don't work. Saved versions (along with regular testing) makes it easy to pinpoint what code changes are responsible for a new bug so you can focus your attention on fixing the right code. And if you accidentally delete a critical file or munge an important code passage, it can save the day and retrieve the old version. Without version control, you could attempt to manually track your project history by saving copies of files along the way but this is tedious and error-prone. Instead you can have a complete history from which you can snapshot/view/retrieve versions.

         Git is one of most flexible and powerful version control systems in use, but its industrial-strength nature makes it less nice for novices. It can be easy to mess up the repo if not careful enough, so for now, it is best to stick to these simple and safe commands:

         git status: After cloning, and cding into the repo, First try running git status, you should see:

         On branch master
         Your branch is up-to-date with 'origin/master'.

         nothing to commit, working directory clean
         If you edit a file, say readme.txt, and run git status again:

         Changes not staged for commit:
           (use "git add <file>..." to update what will be committed)
           (use "git checkout -- <file>..." to discard changes in working directory)

             modified:   readme.txt
         which means that your change on the file has been detected by git, but not staged/added to git internal index.

         git diff: as can be told from the command itself, it allows you to inspect what changes have been made from the last staged state. You may also diff on a single file, like git diff readme.txt, and you should see something like this:

         --- a/readme.txt
         +++ b/readme.txt
          ----------------------
          File: readme.txt
          Assignment: assign0
         -Author: YOUR NAME HERE
         +Author: My Name
          ----------------------
         git add: this command adds/stages the change you have made on certain files. Try running git add readme.txt, and you should see:

         Changes to be committed:
           (use "git reset HEAD <file>..." to unstage)

             modified:   readme.txt
         Which means that your update on readme.txt has been added to the git index. Now it's time to set a milestone!

         git commit: A commit sets a milestone in the version history, a place you revisit later. Try running git commit -m "add name to readme.txt", and you will see:

         [master 5dd152e] add name to readme.txt
          1 file changed, 1 insertion(+), 1 deletion(-)
         Here what's after -m is whatever message you'd like to comment for this commit. You may also just use git commit, after which you may prepare a more verbose commit message in your editor. (Important aside: commit only sets a milestone in your local repo. You still must submit your code to CS107 for grading using the submit tool! )

         git log: This is the command to view your the commit history:

         commit 5dd152eff15d52598d990f775f9b5742fcf6d729
         Author: dengl11 <dengl11@stanford.edu>
         Date:   Mon Sep 25 20:59:51 2017 -0700

             add name to readme.txt

         commit 6c09c2c89f1471e6204ce1bf64bcad2981770704
         Author: CS107 tools <cs107@cs.stanford.edu>
         Date:   Thu Sep 21 15:31:03 2017 -0700

             Created starter 17-1 assign0 dengl11

         commit 1399dc47471f304b0eef98aea1d119389f0ccfb0
         Author: CS107 tools <cs107@cs.stanford.edu>
         Date:   Thu Sep 21 15:31:03 2017 -0700

         Init empty repo
         For a tutorial on git, also check out the guided online tutorial from Try Git.

         Common questions
         What is the hidden .git directory and .gitignore file?
         Sharp eyes! Every git repo has a .git hidden directory which stores the repo housekeeping, configuration settings, and complete version history. Do not delete this directory! It contains critical data for the repo.

         The .gitignore file is lists files thare are intentionally excluded from being tracked. For example, .o files and executable programs are made when you compile (make). Those files can be quite large in size and there is no point in tracking their versions, since we can always rebuild from the original source code. To keep our git repo as light as possible, we exclude those files.

         I don't like the default editor popped up after I type git commit. Can I use my favorite editor, like Vim?
         Yes! The following command configures which editor to use with git. (replace vim as emacs if you prefer):

             git config --global core.editor vim
         One last thought: git has an enormous set of features and the indiscriminate use of various commands can easily hose your repo. If you want to play around, be sure to do your experimentation on some throwaway repo, not your important assignment work, please!
         
   ## University of Washington Git resources      
        * https://courses.cs.washington.edu/courses/cse154/20sp/resources/assets/vscode-git-tutorial/windows/index.html
        
   ## MIT The Missing Semester of your CS Education GIT
        * https://missing.csail.mit.edu/2020/version-control/

      
   ## Differences between Software Engineer, Web developer and Programmer
   
      * There are a few ways to spot the differences among software engineer, web developer, and programmer roles.
    
         + Web developers are focused on creating browser apps with a combination of client-side and server-side programming languages. Generally speaking, they are involved in            designing interactive websites and building user-facing applications.
    
          + Software engineers are more likely to work on computer systems as a whole. They develop standalone programs and apps to help users perform various activities. For the            most part, they program, document, test, and maintain software by utilizing the best practices in DevOps.
       
    * Front-End & Back-End
   
         + The only real distinction you have to make is the one between front-end and back-end programming — whether you’re designing surface-level UI and user-centric                    applications or running hidden processes inside a database server.
       
      - "At the end of the day, we're all trying to solve business problems with code."
      
      
  ## Public vs Private
   Public	                                                                                                                  Private
All the class members declared under public will be available to everyone.	                                                   The class members declared as private can be                                                                                                                                     accessed only by the functions inside the class.
The data members and member functions declared public can be accessed by other classes too.	                                 Only the member functions or the friend functions                                                                                                                               are allowed to access the private data members of                                                                                                                               a class.
The public members of a class can be accessed from anywhere in the program using the direct member access operator 
(.) with the object of that class.	                                                                                         They are not allowed to be accessed directly by any                                                                                                                              object or function outside the class.


   ## Interger (INT)
      An integer, in the context of computer programming, is a data type used to represent real numbers that do not have fractional values.

      Different types of integer data types are stored on machines in different ways. For example, a short integer in many common programming languages is limited to a range of       between 32,767 and -32,768. These limited ranges reveal the relationship between a numerical value as interpreted by humans, and how these values are stored in computer memory.

   ## Static
      Las variables declaradas como estáticas (static) son, esencialmente, variables globales. Cuando se declara un objeto, no se realiza una copia de una variable estática. En       cambio, todas las instancias de la clase comparten la misma variable estática. Aquí hay un ejemplo que muestra las diferencias entre una variable estática y una variable        de instancia:  

  ## Void
      El tipo void se utiliza para indicar que algo no tiene tipo. Por ejemplo, para indicar que un método no devuelve un resultado se le indica que devuelve void.
      
  ## C++ documentation
      * https://www.isocpp.org/
      * https://stroustrup.com/
      * https://www.youtube.com/watch?v=Q7HcwDE3lsU
      * https://www.youtube.com/watch?v=fX2W3nNjJIo
      * https://www.youtube.com/watch?v=HddFGPTAmtU
      * https://www.youtube.com/watch?v=uTxRF5ag27A&t=1s
      * https://cplusplus.com/doc/tutorial/
       
 ## Resume writing
      * https://www.workitdaily.com/basic-resume-writing-tips
      
 ## Ideas de Proyectos
      * http://better-dpt-roll.github.io/
      
 ## Zen of Python
      Beautiful is better than ugly.
      Explicit is better than implicit.
      Simple is better than complex.
      Complex is better than complicated.
      Flat is better than nested.
      Sparse is better than dense.
      Readability counts.
      Special cases aren't special enough to break the rules.
      Although practicality beats purity.
      Errors should never pass silently.
      Unless explicitly silenced.
      In the face of ambiguity, refuse the temptation to guess.
      There should be one– and preferably only one –obvious way to do it.[a]
      Although that way may not be obvious at first unless you're Dutch.
      Now is better than never.
      Although never is often better than right now.[b]
      If the implementation is hard to explain, it's a bad idea.
      If the implementation is easy to explain, it may be a good idea.
      Namespaces are one honking great idea – let's do more of those!
      
   ## Important publications in Computer Science
      * https://en.wikipedia.org/wiki/List_of_important_publications_in_computer_science
      
   ## Deploy
      * https://dev.to/gedgonz/haciendo-deploy-de-una-app-en-react-a-github-pages-95p
      * https://platzi.com/tutoriales/1111-vuejs-2017/3441-como-hacer-deploy-de-una-aplicacion-de-vuejs-hacia-github-pages-usando-vue-cli-3/
      * https://www.freecodecamp.org/espanol/news/dos-maneras-de-desplegar-un-sitio-publico-de-github-pages-desde-un-repositorio-privado-de-hugo/
      * https://www.saulsolorzano.com/usando-git-deploy/
      * https://www.hostingplus.com.ar/blog/deploy-en-que-consiste-y-como-hacerlo/
      * https://www.linuxito.com/programacion/880-como-implementar-deploy-automatico-en-git
      * https://bit.ly/2vY88Kr
        
   ## DevOps
      * https://lab.github.com/githubtraining/devops-with-github-actions
      * https://www.udemy.com/course/learn-complete-devops-with-python-docker-kubernetes-git/?ranMID=39197&ranEAID=d2gvurItCFk&ranSiteID=d2gvurItCFk-Kt48PBRlNPRSvA_u04C3kQ&LSNPUBID=d2gvurItCFk&utm_source=aff-campaign&utm_medium=udemyads
      * https://www.udemy.com/course/docker-devops/?ranMID=39197&ranEAID=d2gvurItCFk&ranSiteID=d2gvurItCFk-Fj7_9HEpJG_Ut7eph9_cQg&LSNPUBID=d2gvurItCFk&utm_source=aff-campaign&utm_medium=udemyads
   
   ## Kurbernets, Docker
    * https://iximiuz.com/en/posts/container-learning-path/
    * https://iximiuz.com/en/posts/containers-vs-pods/
    * https://www.freecodecamp.org/news/how-to-become-a-certified-kubernetes-application-developer/
    * https://anthonynsimon.com/blog/kubernetes-cluster-raspberry-pi/
    * https://www.infoq.com/news/2021/11/kubernetes-cluster-api/
    * https://techchannel.com/SMB/06/2019/kubernetes-management-aix
    * https://bootstrap-it.com/docker-images/
    
   ## Azure
    * https://docs.google.com/document/d/1nT6lvqlRPhlPCy1a-Xknp-aPwBjm5gKHqk5QW2CLj6s/edit
    
   ## SEO
   
     * https://boringseo.org/
    
   ## Jira, Docker, Travis CI
   
   ## AWS
    
     * https://aws.amazon.com/es/blogs/aws/new-aws-scholarship-program-helps-underrepresented-and-underserved-students-prep-for-careers-in-ai-and-ml/
     
   ## Artificial Intelligence
       * Many digital engineers believe, Kurzweil among them, that as machines
        are programmed to become more and more “intelligent,” in the sense of
        capable of learning and modifying their output on the basis of their input
        (“experience”), machines themselves rather than people will design the next
        generations of machines.
        
   ## Machine Learning
        Machine Learning is making the computer learn from studying data and statistics.

        Machine Learning is a step into the direction of artificial intelligence (AI).

        Machine Learning is a program that analyses data and learns to predict the outcome.

   ## Continuos Integration System (CI)
        * Will build and test our code every time there's a change
        * Once we our code automatically built and tested, the next automatation step is continous deployment, which is sometimes called continous delivery (CD)
          
          - Tools
            * Jenkins
            * Travis
            * GitLab
        
       * Pipelines 
          - Specify the steps that need to run to get the result you want 
        * Artifacts
          - The name used to describe any files that are generated as part of the pipeline
        
     ## CI/CD
          * "CI" siempre se refiere a la integración continua, que es un proceso de automatización para los desarrolladores. El éxito de la CI implica que se diseñen, prueben y combinen los cambios nuevos en el código de una aplicación con regularidad en un repositorio compartido. Supone una solución al problema de que se desarrollen demasiadas divisiones de una aplicación al mismo tiempo, que luego podrían entrar en conflicto entre sí.

          * La sigla "CD" se refiere a la distribución o la implementación continuas, y se trata de conceptos relacionados que suelen usarse indistintamente. Ambos se refieren a la automatización de las etapas posteriores del proceso, pero a veces se usan por separado para explicar hasta dónde llega la automatización.

   ## I/O
      * In computing, input/output (I/O, or informally io or IO) is the communication between an information processing system, such as a computer, and the outside world, possibly a human or another information processing system. Inputs are the signals or data received by the system and outputs are the signals or data sent from it. The term can also be used as part of an action; to "perform I/O" is to perform an input or output operation.
        I/O devices are the pieces of hardware used by a human (or other system) to communicate with a computer. For instance, a keyboard or computer mouse is an input device for a computer, while monitors and printers are output devices.
   ## Specialize
      * https://amaca.substack.com/p/how-i-got-wealthy-without-working
   ## Code Review
      * Code Review
      Code review is careful, systematic study of source code by people who are not the original author of the code. It’s analogous to proofreading a term paper.

      Code review really has two purposes:

      Improving the code. Finding bugs, anticipating possible bugs, checking the clarity of the code, and checking for consistency with the project’s style standards.
      Improving the programmer. Code review is an important way that programmers learn and teach each other, about new language features, changes in the design of the project or its coding standards, and new techniques. In open source projects, particularly, much conversation happens in the context of code reviews.
      
   ## Interview
      * https://www.acefrontend.com/
      * PRACTICE PLATFORMS: LeetCode, HackerRank, Pramp, ExpertMitra, interviewing.io, HackerEarth, AlgoExpert
      * INTERVIEW GUIDES: Tech Interview Handbook, Coding Interview University, “How to ace coding interviews”, Interviews.school
      * https://www.educative.io/blog/crack-amazon-coding-interview-questions // Amazon
      * https://lanie.dev/tech/interviewing/
      * https://www.reddit.com/r/berkeley/comments/ly5bce/i_made_a_chrome_extension_that_autofills_job_apps/ // Job filling application
        
   ## Para cuando no puedo pushear un proyecto a github
      * https://stackoverflow.com/questions/4181861/message-src-refspec-master-does-not-match-any-when-pushing-commits-in-git
        

  
