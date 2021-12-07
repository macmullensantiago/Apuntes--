# Apuntes--

# Think like a Computer Scientist

  # What does it means to do computation?
  
  
    
   ### What is knowledge?
   
     * Declarative and Imperative
     
     Imperative - It tells you how you might test something but it doesn't tells you how to.
     
     Imperative knowledge is a description of how to deduce something.
     
     It's a sequence of specific instructions that I do in order. Along the way I have some tests and depending on the value of that test, I may change where I am in that            sequence of instructions. 
     
  ### Program is a recipe
     * Given a set fixed of primitives a good programmer can program anything.
     * Our goal is to take problems a break them into these computational steps, these sequence of instructions that allow us to take capture that process.
     
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
    
  ### Data Structures - Types and Values
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
  
  ###  Fibonacci 
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
      
  ### Framework - 
      * A way of doing things. 
      
## Back End - Server Side
      * Go, Java, JavaScript, .NET, PHP, Python, Ruby, Scala, Django, Flask, Laravel, Node.js...
      
   ### Database
      * SQL, NoSQL, MariaDB, MySQL, Oracle, PostgreSQL, SQL Server, Bigtable, Cassandra, HBase, MongoDB...
      
      What does a data base?
         Support these opperations
            * Create        // C
            * Read         //  R
            * Upload      //   U
            * Deleat     //    D
            
            SQL - Stores data in rows and columns
            NoSQL - Stores data all together in a hierarchical structure
            
 ## The Cloud
            
        * Basically is using someone else's server to put your data.
         
        * It makes much easier for people and smaller companies to scale automatically.
         
        * DNS (Domain Name System) -  Es un sistema de nomenclatura jerárquico descentralizado para dispositivos conectados a redes IP como Internet o una red privada. Este sistema asocia información variada con nombres de dominio asignados a cada uno de los participantes. Su función más importante es "traducir" nombres inteligibles para las personas en identificadores binarios asociados con los equipos conectados a la red, esto con el propósito de poder localizar y direccionar estos equipos mundialmente.
        * El servidor DNS utiliza una base de datos distribuida y jerárquica que almacena información asociada a nombres de dominio en redes como Internet. Aunque como base de datos el DNS es capaz de asociar diferentes tipos de información a cada nombre, los usos más comunes son la asignación de nombres de dominio a direcciones IP y la localización de los servidores de correo electrónico de cada dominio.

        * IP - Los dispositivos se conectan entre sí mediante sus respectivas direcciones IP. Sin embargo, para las personas es más fácil recordar un nombre de dominio que los números de la dirección IP. Los servidores de nombres de dominio DNS, "traducen" el nombre de dominio en una dirección IP. Si la dirección IP dinámica cambia, es suficiente actualizar la información en el servidor DNS. El resto de las personas seguirán accediendo al dispositivo por el nombre de dominio.
 
        * PaaS - Platform as Service. Example: Heroku. It makes it easier for you to run your applications in the cloud.
        
        * SaaS - Software as Service. Example: Gmail.com. Web-based email service.
        
        * https://bush-socks-586.notion.site/Curso-de-Introducci-n-a-la-Nube-con-Azure-902361fc98974378874c7ce1943cd5e4
        
## Data Structures and Algorithms
    * Arrays                                                        * Sorting, searching, and binary search
    * Linked list                                                   * Divide and conquer
    * Stacks                                                        * Dynamic programming and memorization
    * Queues                                                        * Greedy Algorithms
    * Sets                                                          * Recursion
    * Maps                                                          * Graph traversal, breath and depth-first
    * Binary Trees
    * Heaps
    * Graphs

  ## Syntax
    
  ### What is Syntax?
  
    * Syntax says what are the legal expressions in this language.
  
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
        
   ## Bucles
      
          * Un bucle o ciclo, en programación, es una secuencia de instrucciones de código que se ejecuta repetidas veces, hasta que la condición asignada a dicho bucle deja de             cumplirse. Los tres bucles más utilizados en programación son el bucle while, el bucle for y el bucle do-while.
      
      * ### For
      
          * El bucle for es una estructura de control en programación en la que se puede indicar de antemano el número máximo de iteraciones.
        
      * #### Elementos del bucle
      
          * Variable de control: prácticamente un mandato impuesto por el uso habitual es utilizar la letra i Iterador como variable de control, o bien sus sucesoras en caso de bucles anidados. El uso de esta letra críptica quizás a primera vista es sin embargo una excelente forma de aportar agilidad de lectura al código por su uso tan extensivo. Como raras veces los bucles anidados superan las tres dimensiones (por una sencilla cuestión de explosión exponencial), las letras i, j y k suelen ser las únicas relacionadas con este uso. En C se define en el primer parámetro de la instrucción junto con la inicialización (opcional).
          * Inicialización de la variable de control: en pseudolenguaje se pide explicitarlo (es la sección := ValorInicial), sin embargo, otros lenguajes más permisivos como C no lo requieren de forma obligatoria. De todos modos, la práctica de utilizar variables de control que no se inicializan en el bucle no es recomendada para la           legibilidad del código. En C se define en el primer parámetro del bucle junto con la variable de control.
          * Condición de control: en pseudolenguaje se ve representado por el valor final que puede tomar la variable de control (la sección A ValorFinal). En C es el segundo parámetro y puede ser cualquier condición (ni siquiera es obligación que esté la variable de control, aunque una vez más, esto no se considera una buena práctica).
          * Incremento: en pseudolenguaje se toma por defecto el valor 1, aunque puede explicitarse por medio de la sentencia PASO = ValorPaso cualquier número entero (léase) bien entero, o sea que técnicamente podemos decrementar). En C es el último parámetro.
          * Cuerpo: es lo que se hará en cada iteración, pueden ser una o más instrucciones. En pseudolenguaje pesa la restricción de no poder alterar el valor de la variable de control; esto no es requerido en C, pero no se considera una buena práctica.
   
        * ### While
     
          * El bucle while o bucle mientras es un ciclo repetitivo basado en los resultados de una expresión lógica; se encuentra en la mayoría de los lenguajes de programación              estructurados. El propósito es repetir un bloque de código mientras una condición se mantenga verdadera.
   
          * La condición ha de ser una sentencia que devuelva un valor booleano, y esta puede ser el valor booleano sí, verdadero (true) si la condición se cumple, o falso si                esta no se cumple (false). También puede contener el nombre de una variable booleana, y el valor de la expresión dependerá de su contenido. Se debe tener en cuenta              que además de las variables también puede haber llamadas a funciones que devuelvan un valor.
   
        * ### Do-While
   
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
            
   # Git - GitHub
        
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
        
   ## Quotes
      * You live in illusions and the appearance of things.
        There is a Reality, you are that Reality.
        When you recognize this you will realize that you are nothing,
        and being nothing, you are everything. That is all.

        KALU RINPOCHE, TIBETAN LAMA
        
        In its truest expression, meditation goes beyond notions
        of success and failure.
        
        When the dharma is really taking care of the problems of life, it is
        true dharma.
        
        A child may try to help a butterfly to emerge by breaking open
        its chrysalis.
        
        It is far better to trust in your intuition
        and your own authority, even if you make some “mistakes” along
        the way, than always to look outside yourself for guidance.
        
        The answer is that once you start meditating, breathing is no 
        longer just breathing. When we start paying attention to our 
        breathing on a regular basis, our relationship to it changes 
        dramatically. 
        
        Time past and time future
        Allow but a little consciousness.
        To be conscious is not to be in time …
        
        Think locally, act globally.
   ## Mindfulness
      * www.umassmed.edu/cfm Center for Mindfulness, UMass Medical School
        www.mindandlife.org Mind and Life Institute
        www.dharma.org Vipassana retreat centers and schedules
        Oxford University Mindfulness Centre
        http://oxfordmindfulness.org
        University of Massachusetts Medical School
        Worcester, Massachusetts
        http://www.umassmed.edu/cfm/index.aspx
        University of California Center for Mindfulness
        San Diego, California
        http://health.ucsd.edu/specialties/mindfulness/Pages/default.a
        spx
        Open Ground Mindfulness Training
        Sydney, Australia
        http://www.openground.com.au
        Mindful Psychology
        Auckland, New Zealand
        http://www.mindfulpsychology.co.nz/trainers.html
        
   ## Yoga
      * Yoga is also good exercise because it is a type of full-body
        conditioning. It improves strength, balance, and flexibility in the
        entire body. It’s like swimming, in that every part of your body is
        involved and bene􀉹ts. It can even have cardiovascular bene􀉹ts
        when done vigorously.
        
   ## Synchronicity
       Del libro Sincronicidad
      * 'On Synchronicity' (1951) (CW 8)1
        It might seem appropriate to begin my exposition by defining the concept
        with which it deals. But I would rather approach the subject the other way
        and first give you a brief description of the facts which the concept of
        synchronicity is intended to cover. As its etyn1ology shows, this term has
        something to do with time or, to be more accurate, with a kind of
        simultaneity. Instead of simultaneity we could also use the concept of a
        meaningful coincidence of two or more events, where something other than
        the probability of chance is involved.
        
        On April 1, 1949, I made a note in the morning of an inscription
        containing a figu re that was half man and half fish. There was fish for
        lunch. Somebody mentioned the custom of making an 'April fish' of
        someone. In the afternoon, a forn1er patient of mine, whom I had not seen
        for months, showed me some impressive pictures of fish. Tn the evening,
        I was shown a piece of embroidery with sea monsters and fishes in it. The
        next morning, l saw a former patient, who was visiting me for the fi rst
        tin1e in ten years. She had dreamed of a large fish the night before. A few
        months later, when I was using this series for a larger work and had just
        finished writing it down, I walked over to a spot by the lake in front of the
        house, where l had already been several times that morning. This time a
        fish a foot long Jay on the sea-wall. Since no one else was present, I have
        no idea how the fish could have got there.
        
        The sentiment du deja-vu is based, as I have found in a number of cases,
        on a foreknowledge in dreams, but we saw that this foreknowledge can
        also occur in the waking state. In such cases mere chance becomes highly
        improbable because the coincidence is known in advance. It thus loses its
        chance character not only psychologically and subjectively, but objectively
        too, since the accumulation of details that coincide immeasurably
        increases the improbability of chance as a determining factor.
        
        Well, I was sitting opposite her one day, with my
        back to the window, listening to her flow of rhetoric. She had had an
        impressive drea1n the night before, in which someone had given her a
        golden scarab - a costly piece of jewellery. While she was still telling me
        this dream, I heard so1nething behind me gently tapping on the window. I
        turned round and saw that it was a fairly large flying insect that was
        knocking against the window-pane from outside in the obvious effort to
        get into the dark room. This seemed to me very strange. I opened the
        window immediately and caught the insect in the air as it flew in. It was
        a scarabaeid beetle, or common rose-chafer ( Cetonia aura ta), whose goldgreen
        colour most nearly resembles that of a golden scarab. I handed the
        beetle to my patient with the words, 'Here is your scarab.' This experience
        punctured the desired hole in her rationalism and broke the ice of her
        intellectual resistance. The treatment could now be continued with satisfactory
        results.
        
        All the phenomena(clairvoyance, telepathy, etc.,) I have mentioned can be grouped under three
        categories:
        1 The coincidence of a psychic state in the observer with a simultaneous,
        objective, external event that corresponds to the psychic state or content
        (e.g., the scarab), where there is no evidence of a causal connection
        between the psychic state and the external event, and where, considering
        the psychic relativity of space and time, such a connection is not even
        conceivable.
        2 The coincidence of a psychic state with a corresponding (more or less
        simultaneous) external event taking place outside the observer's field of
        perception, i.e., at a distance, and only verifiable afterward (e.g., the
        Stockholm fire).
        3 The coincidence of a psychic state with a corresponding, not yet existent
        future event that is distant in time and can likewise on ly be verified
        afterward.
        
        Consequently. we are no
        longer justified in describing astrology as a mantic method. Astrology is
        in the process of becoming a science.
        
        (...) a meaningful coincidence, that is. as synchronicity.
        
        Causality is the way we explain
        the link between two successive events. Synchronicity designates the
        parallelism of time and meaning between psychic and psychophysical
        events, which scientific knowledge so far has been unable to reduce to a
        common principle. The term explains nothing, it si,nply formulates the
        occurrence of meaningful coincidences which, in themselves. are chance
        happenings, but are so improbable that we must assume them to be based
        on some kind of principle, or on some property of the empirical world. No
        reciprocal causal connection can be shown to obtain between parallel
        events, which is just what gives them their chance character. The only
        recognizable and demonstrable link between them is a common meaning,
        or equivalence. The old theory of correspondence was based on the
        experience of such connections - a theory that reached its culminating
        point and also its provisional end in Leibniz' idea of pre-established
        harmony, and was then replaced by causality. Synchronicity is a modern
        differentiation of the obsolete concept of correspondence, sympathy, and
        harmony. Tt is based not on philosophical assumptions but on empirical
        experience and experimentation.
        
        This paper was inevitable.
        Having come to the conclusion that the observed is also a disturbance by the
        observer, the consistent investigator of the unknown interior of the atom
        could not help seeing that the nature of the observing process becon1es
        perceptible in the disturbance caused by the observation. To put it more
        simply, if you look long enough into a dark hole you perceive what is looking
        in.
        This is also the principle of cognition in yoga, which derives all cognition
        from the absolute emptiness of consciousness. This method of cognition
        is thus a special instance of the introspective investigation of the psyche
        in general.
        
        lt may be said in passing that Chinese science is based on
        the principle of synchronicity.
        
        The use of the term libido in the newer medical psychology has surprising affinities
        with the primitive mana.
        
        Visions
        Then the whole sea turned to blood.
        
        There was no longer anything I wanted or desired. I existed
        in an objective form; I was what I had been and lived. At first the sense of
        annihilation predominated, of having been stripped or pillaged; but suddenly
        that became of no consequence. Everything seemed to be past; what remained
        was afait accompli, without any reference back to what had been. There was
        no longer any regret that something had dropped away or been taken away.
        On the contrary: I had everything that I was, and that was everything.
        
        'Why does he always pretend he doesn't know he is a basileus of Kos?
        
        I felt as though I were floating in space, as
        though I were safe in the womb of the universe - in a tremendous void, but
        filled with the highest possible feeling of happiness. 'This is eternal bliss', I
        thought. 'This cannot be described; it is far too wonderful!'

        I would never have imagined that any such experience was possible. It was
        not a product of imagination. The visions and experiences were utterly real;
        there was nothing subjective about them; they all had a quality of absolute
        objectivity.
        
        We shy away fron1 the word 'eternal', but I can describe the experience
        only as the ecstasy of a non-temporal state in which present, past, and future
        are one. Everything that happens in time had been brought together into a
        concrete whole. Nothing was distributed over time, nothing could be measured
        by temporal concepts. The experience might best be defined as a state
        of feeling, but one which cannot be produced by itnagination. How can I
        imagine that I exist sin1ultaneously the day before yesterday, to-day and the
        day after to-morrow? There would be things which would not yet have begun,
        other things which would be indubitably present, and others again which
        would already be finished - and yet all this would be one. The only thing that
        feeling could grasp would be a sum, an iridescent whole, containing all at
        once expectation of a beginning, surprise at what is now happening, and
        satisfaction or disappointment with the result of what happened. One is
        interwoven into an indescribable whole and yet observes it with complete
        objectivity.
        
        I got out at Erlenbach and walked home, still troubled by this memory. My
        second daughter's children were in the garden. The family was living with
        us, having returned to Switzerland from Paris because of the war. The
        children stood looking rather upset, and when J asked, 'Why, what is the
        matter?' they told me that Adrian, then the youngest of the boys, had fallen
        into the water in the boathouse. It is quite deep there, and since he could not
        really swim he had almost drowned. His older brother had fished him out.
        This had taken place at exactly the time 1 had been assailed by that memory
        in the train. The unconscious had given me a hint. Why should it not be able
        to inform me of other things also?
        
        Naturally, one can contend from the start that myths and dreams concerning
        continuity of life after death are merely compensating fantasies which are
        inherent in our natures - all life desires eternity. The only argument I can
        adduce in answer to this is the myth itself.
        However. there are indications that at least a part of the psyche is not
        subject to the laws of space and time. Scientific proof of that has been
        provided by the well-known J.B. Rhine experiments.2 Along with numerous
        cases of spontaneous foreknowledge, non-spatial perceptions, and so on - of
        which I have given a number of examples from my own life - these
        experiments prove that the psyche at times functions outside of the spatiotemporal
        law of causality. This indicates that our conceptions of space and
        ti1ne, and therefore of causality also, are incomplete. A complete picture of
        the world would require the addition of still another dimension; only then
        could the totality of phenomena be given a unified explanation.
        
        In himself he is an important god - a Mercury
        or Hermes, as the Romans correctly realized, a nature spirit who returned to
        life again in the Merlin of the Grail legend and became, as the spiritus
        Mercurialis, the sought-after arcanum of the alche1uists.
        
        To these two causal relationships
        we must add a third possibility, namely, that of a 'synchronistic',
        i.e., acausal, meaningful coincidence - a problem that has occupied men's
        minds ever since the time of Geulincx, Le ibniz and Schopenhauer.
        
        In the latter case one could
        assume that synchronicity is a property of energy, but in so far as energy is
        equal 10 matter it is a seconda ry effect of the primary coincidence of mental
        and physical events (as in the Fibonacci series). The hridge seems to be
        formed by the numbers.~ Numbers are just as much invented as they are
        discovered as natural facts, like all true archetypes. As far as I know,
        archetypes arc perhaps the most important basis for synchronistic events.
        
        Man created mathematics, but God created whole
        numbers: o 0Eo<; &pL0μ:r11£~EL.
        
        The mandala symbolizes, by its central point, the ultimate unity of all
        archetypes as well as of the multiplicity of the phenomenal world, and is
        therefore the empirical equivalent of the metaphysical concept of a unus
        mundus. The alchemical equivalent is the lapis and its synonyms, in
        particular the Microcosm.
        
        The essential thing about
        these phenomena is that an objective event coincides meaningfully with a
        psychic process; that is to say. a physical event and an endopsychic one have
        a common meaning.
        
        Unconscious synchronicities
        are, as we know from experience, altogether possible, since in many
        cases we are unconscious of their happening, or have to have our attention
        drawn to the coincidence by an outsider.
        
        Del libro Syncrhronicity an accausal connecting principle
        To Jung, synchronicity is a meaningful coincidence in time, a psychic factor
        which is independent of space and time. This revolutionary concept of
        synchronicity both challenges and complements the physicist’s classical view of
        causality. It also forces us to a basic reconsideration of the meaning of change,
        probability, coincidence and the singular events in our lives.
        
        The suspicion that this must be a case of meaningful coincidence, i.e., an
        acausal connection, is very natural.
        
        Schopenhauer believed in
        the absolute determinism of the natural process and furthermore in a first cause.
        
        I defined synchronicity as a psychically
        conditioned relativity of space and time.
        
        Synchronicity therefore means the simultaneous occurrence of a certain
        psychic state with one or more external events which appear as meaningful
        parallels to the momentary subjective state—and, in certain cases, vice versa. My
        two examples illustrate this in different ways. In the case of the scarab the
        simultaneity is immediately obvious, but not in the second example. It is true that
        the flock of birds occasioned a vague fear, but that can be explained causally. The
        wife of my patient was certainly not conscious beforehand of any fear that could
        be compared with my own apprehensions, for the symptoms (pains in the throat)
        were not of a kind to make the layman suspect anything bad. The unconscious,
        however, often knows more than the conscious, and it seems to me possible that
        the woman’s unconscious had already got wind of the danger.
        
        Synchronistic events rest on the simultaneous occurrence of two different
        psychic states. One of them is the normal, probable state (i.e., the one that is
        causally explicable), and the other, the critical experience, is the one that cannot
        be derived causally from the first. In the case of sudden death the critical
        experience cannot be recognized immediately as “extra-sensory perception” but
        can only be verified as such afterwards. Yet even in the case of the “scarab” what
        is immediately experienced is a psychic state or psychic image which differs from
        the dream image only because it can be verified immediately.
        
        The scarab dream is a conscious representation arising
        from an unconscious, already existing image of the situation that will occur on
        the following day, i.e., the recounting of the dream and the appearance of the
        rose-chafer.
        
        Synchronicity therefore consists of two factors: a) An unconscious image comes
        into consciousness either directly (i.e., literally) or indirectly (symbolized or
        suggested) in the form of a dream, idea, or premonition. b) An objective situation
        coincides with this content. The one is as puzzling as the other. How does the
        unconscious image arise, and how the coincidence? I understand only too well
        why people prefer to doubt the reality of these things. Here I will only pose the
        question. Later in the course of this study I will try to give an answer.
        
        Goethe thinks of synchronistic events in the same “magical” way.
        Thus he says, in his conversations with Eckermann: “We all have certain electric
        and magnetic powers within us and ourselves exercise an attractive and repelling
        force, according as we come into touch with something like or unlike.”
        
        The method, like all divinatory or intuitive techniques, is based on an acausal
        or synchronistic connective principle.
        
        Number has invariably been used to describe some numinous
        object, and all numbers from 1 to 9 are “sacred,” just as 10, 12, 13, 14, 28, 32, and
        40 have a special significance. The most elementary quality about an object is
        whether it is one or many. Number helps more than anything else to bring order
        into the chaos of appearances. It is the predestined instrument for creating order,
        or for apprehending an already existing, but still unknown, regular arrangement
        or “orderedness.” It may well be the most primitive element of order in the
        human mind, seeing that the numbers 1 to 4 occur with the greatest frequency
        and have the widest incidence. In other words, primitive patterns of order are
        mostly triads or tetrads. That numbers have an archetypal foundation is not, by
        the way, a conjecture of mine but of certain mathematicians, as we shall see in
        due course.
        
        Hence it is not such an audacious conclusion after all if we define
        number psychologically as an archetype of order which has become conscious.68
        Remarkably enough, the psychic pictures of wholeness which are spontaneously
        produced by the unconscious, the symbols of the self in mandala form, also have
        a mathematical structure. They are as a rule quaternities (or their multiples).69
        These structures not only express order, they also create it. That is why they
        generally appear in times of psychic disorientation in order to compensate a
        chaotic state or as formulations of numinous experiences. It must be emphasized
        yet again that they are not inventions of the conscious mind but are spontaneous
        products of the unconscious, as has been sufficiently shown by experience.
        
        The causality principle asserts that the connection between cause and effect is a
        necessary one. The synchronicity principle asserts that the terms of a meaningful
        coincidence are connected by simultaneity and meaning.
        
        In Chinese philosophy one of the oldest and most central ideas is that of Tao,
        which the Jesuits translated as “God.” But that is correct only for the Western
        way of thinking. Other translations, such as “Providence” and the like, are mere
        makeshifts. Richard Wilhelm brilliantly interprets it as “meaning.”2 The concept
        of Tao pervades the whole philosophical thought of China.
        
        Lao-tzu gives the following description of Tao in his celebrated Tao Teh
        Ching:3
        There is something formless yet complete
        That existed before heaven and earth. How still how empty!
        Dependent on nothing, unchanging,
        All pervading, unfailing.
        One may think of it as the mother of all things under heaven.
        I do not know its name,
        But I call it “Meaning.”
        If I had to give it a name, I should call it “The Great.”
        
        Tao “covers the ten thousand things like a garment but does not claim to be
        master over them”.
        
        Tao never does;
        Yet through it all things are done.
        
        On the primitive level, of course, synchronicity does not
        appear as an idea by itself, but as “magical” causality. This is an early form of our
        classical idea of causality, while the development of Chinese philosophy
        produced from the connotation of the magical the “concept” of Tao, of
        meaningful coincidence, but no causality-based science.
        
        synchronicity is a phenomenon that
        seems to be primarily connected with psychic conditions, that is to say with
        processes in the unconscious. Synchronistic phenomena are found to occur—
        experimentally—with some degree of regularity and frequency in the intuitive,
        “magical” procedures, where they are subjectively convincing but are extremely
        difficult to verify objectively and cannot be statistically evaluated (at least at
        present).
        
        Synchronicity is not a philosophical view but an empirical concept which
        postulates an intellectually necessary principle. This cannot be called either
        materialism or metaphysics. No serious investigator would assert that the nature
        of what is observed to exist, and of that which observes, namely the psyche, are
        known and recognized quantities. If the latest conclusions of science are coming
        nearer and nearer to a unitary idea of being, characterized by space and time on
        the one hand and by causality and synchronicity on the other, that has nothing to
        do with materialism. Rather it seems to show that there is some possibility of
        getting rid of the incommensurability between the observed and the observer.
        
        ACAUSALITY. If natural law were an absolute truth, then of course there
        could not possibly be any processes that deviate from it. But since causality is a
        statistical truth, it holds good only on average and thus leaves room for
        exceptions which must somehow be experienceable, that is to say, real. I try to
        regard synchronistic events as acausal exceptions of this kind. They prove to be
        relatively independent of space and time; they relativize space and time in so far
        as space presents in principle no obstacle to their passage and the sequence of
        events in time is inverted, so that it looks as if an event which has not yet
        occurred were causing a perception in the present. But if space and time are
        relative, then causality too loses its validity, since the sequence of cause and
        effect is either relativized or abolished.
        
        SYNCHRONICITY. Despite my express warning I see that this concept has
        already been confused by the critics with synchronism. By synchronicity I mean
        the occurrence of a meaningful coincidence in time. It can take three forms:
        a) The coincidence of a certain psychic content with a corresponding objective
        process which is perceived to take place simultaneously.
        b) The coincidence of a subjective psychic state with a phantasm (dream or
        vision) which later turns out to be a more or less faithful reflection of a
        “synchronistic,” objective event that took place more or less simultaneously,
        but at a distance.
        c) The same, except that the event perceived takes place in the future and is
        represented in the present only by a phantasm that corresponds to it.
        Whereas in the first case an objective event coincides with a subjective content,
        the synchronicity in the other two cases can only be verified subsequently,
        though the synchronistic event as such is formed by the coincidence of a
        neutral psychic state with a phantasm (dream or vision).
        
        Las leyes naturales son verdades estadísticas, esto es, sólo son completamente
        válidas donde se trata de magnitudes macrofísicas,
        mientras que en el ámbito de las magnitudes ínfimas el pronóstico
        se vuelve incierto o imposible, por cuanto las magnitudes ínfimas
        no se conducen conforme a las leyes naturales conocidas.
        
        El principio filosófico en el cual se basa nuestra concepción
        de la legalidad natural es el de causalidad. Pero si el nexo entre
        causa y efecto posee una validez únicamente estadística, o sea,
        una verdad relativa, entonces también el mismo principio de
        causalidad tiene, en último término, una aplicación sólo relativa
        para la explicación de los procesos naturales, y supone, en
        consecuencia, la existencia de uno o varios otros factores, necesarios
        para una explicación adecuada. Lo que viene a significar que
        el nexo vigente entre ciertos sucesos puede ser en determinadas
        circunstancias de índole no causal, o sea, que exige otro principio
        explicativo.
        
        Ahora bien, hay en nuestra experiencia un campo de inmensa
        amplitud, cuya extensión equilibra, por así decirlo, la del dominio
        de la causalidad: es el mundo del azar1.
        
        Así, por ejemplo el señor Gross (grande)
        padece de megalomanía, el señor Kleiner (pequeño) tiene un complejo
        de inferioridad. Dos hermanas Altmann (hombre viejo) se casan ambas
        con hombres que les llevan veinte años de edad; el señor Feist (obeso)
        es ministro de alimentación; el señor Rosstäuscher (chalán tramposo) es
        abogado; el señor Kalberer (comadrón veterinario) es partero; el señor
        Freud (alegría) sostiene el principio del placer; el señor Adler (águila)
        sostiene la voluntad de poder; el señor Jung (joven) la idea de renacimiento,
        etc. ¿Trátase aquí de absurdos caprichos del azar o de un efecto
        sugestivo del nombre, como parece suponer Stekel, o de "coincidencias
        significativas"?
        
        En esta concepción, "el sujeto del gran sueño de la vida. . .
        es sólo uno", la voluntad trascendental, la prima causa de la
        cual irradian todas las series causales como meridianos desde
        el polo, guardando entre sí una significativa relación de simultaneidad
        en virtud de los círculos paralelos 11. Schopenhauer creía
        en el determinismo absoluto del proceso natural y también en una
        causa primera. Nada hay que confirme ninguno de los dos supuestos.
        La causa primera no es sino un mitologema filosófico que
        sólo merece fe donde aparece en la forma de la antigua paradoja
        (En to\ pa=n, a saber, como unidad y multiplicidad al mismo tiempo.
        
        Los acontecimientos sincronísticos se basan en la simultaneidad
        de dos diferentes estados psíquicos. Uno de ellos es el normal y
        probable (es decir, causalmente explicable); el otro, la vivencia
        crítica, es el estado que no cabe deducir causalmente del primero.
        
        El fenómeno de
        la sincronización consiste, por lo tanto, en dos factores: 1. Una
        imagen inconsciente entra en lo consciente directamente (es decir,
        literalmente) o indirectamente (simbolizada o insinuada) como
        sueño, ocurrencia o premonición. 2. Una situación objetiva coincide
        con ese contenido.
        
        "Encontré una explicación instructiva (de la magia) en el Liber
        sextus naturalium de Avicena, en el que se afirma que en el alma humana
        mora una cierta facultad (virtus) de cambiar las cosas y de subordinar
        a ella las demás cosas, en particular cuando es arrebatada por un gran
        exceso de amor u odio o algo semejante (quando ipsa fertur in magnum
        amoris excessum aut odii aut alicuius talium). Cuando, pues, el alma de
        un hombre es presa de un gran exceso de alguna pasión, puede probarse
        por el experimento que ése [el exceso] liga a las cosas [mágicamente]
        y las modifica en el sentido que desea (fertur in grandem excessum
        alicuius passionis invenitur experimento manifesto quod ipse ligat
        res et alterat ad idem quod desiderat et diu non credidi illud); por
        largo tiempo no lo quise creer, pero después de haber leído libros nigrománticos
        y otros sobre signos mágicos (imaginum) y magia, encontré
        que la emocionalidad (affectio) del alma humana es la raiz principal
        de todas esas cosas, ya sea porque debido a su gran emoción va alterando
        su cuerpo y las cosas a que tiende, ya sea porque a causa de su
        dignidad las otras cosas inferiores le están sujetas, ya sea porque la hora
        sideral apropiada o la situación astrológica o alguna otra fuerza coinciden
        con un tal afecto, que trasciende todos los límites, haciéndonos creer [en
        consecuencia] que todo cuanto haga esa fuerza es hecho por el alma
        (cum tali affectione exterminata concurrat hora conveniens aut ordo coelestis
        aut alia virtus, quae quodvis faciet, illud reputavimus tunc animam
        facere). .. Quien desee conocer el secreto de hacer y deshacer todo eso,
        debe saber que cualquiera puede influir mágicamente en todas las cosas
        si llega a ser presa de un gran exceso, y hacerlo con las cosas que el alma
        le prescriba. Pues el alma hállase entonces tan ansiosa de las cosas
        que quiete realizar, que espontáneamente aprovecha la hora sideral más
        significativa y más favorable, la cual gobierna también las cosas que mejor
        convengan a ello. .. y así es el alma que apetece las cosas con mayor
        intensidad la que las hace más efectivas y más semejantes a lo que luego
        resulta. .. de manera similar se produce todo cuanto el alma apetece con
        deseo intenso. Todo lo que el alma hace con ese fin, posee energía motriz
        y eficiencia para lo que ella anhela"
        
        "Todos
        tenemos ciertos poderes eléctricos y magnéticos dentro de nosotros,
        y ejercemos, como el imán, una fuerza de atracción o de repulsión,
        según que entremos en contacto con algo homogéneo o heterogéneo"
        
        (...) todos los números de 1 a 9 son "sagrados", así como
        el 10, 12, 13, 14, 28, 32 y 40 tienen un significado especial.
        
        Las potencias eficientes
        (numinosas) de lo inconsciente son los arquetipos.
        
        La gran
        mayoría de los fenómenos de sincronicidad espontáneos que tuve
        ocasión de observar y analizar permitieron reconocer sin dificultad
        su relación directa con el arquetipo.
        
        El principio de sincronicidad afirma
        que los miembros de una coincidencia significativa están vinculados
        por la simultaneidad y el significado.
        
        La sede de la sincronicidad no está, afirma, en los planetas,
        sino en la tierra, pero no en la materia, sino precisamente en
        el anima telluris.
        
        "el alma obedece a
        sus propias leyes, lo mismo que el cuerpo a las suyas, pero ambos
        concuerdan en virtud de la armonía preestablecida entre todas las
        substancias, dado que todas ellas son representaciones del mismo
        universo"
        
        Está aquí claramente expresado el pensamiento de
        que el hombre es un microcosmos. Las almas en general, dice Leibniz,
        "son los espejos o imágenes vivientes del universo de las cosas
        creadas". El distingue, por una parte, los espíritus, que son
        "imágenes de la divinidad" y "capaces de comprender el sistema
        del universo y de imitar una parte del mismo con pruebas constructivas,
        puesto que cada espíritu es dentro de su ámbito una
        pequeña divinidad"54; y por la otra los cuerpos, que actúan
        "conforme a las leyes de las causas finales mediante apeticiones,
        fines y medios"
        
        La filosofía china, en cambio, a partir de la connotación de lo
        mágico produjo el "concepto" de Tao y no una ciencia natural
        basada en la causalidad.
        La sincronicidad presupone un significado que es a priori
        con respecto a la conciencia humana, y que parece existir fuera
        del hombre
        
        El "saber absoluto", es decir, el conocimiento que no ha
        sido alcanzado a través de ningún órgano sensorial, que caracteriza
        al fenómeno sincronístico, confirma la hipótesis de un significado
        o sentido existentes de por sí, o incluso expresa su existencia. Una
        forma tal de existencia sólo puede ser trascendental, dado que,
        como lo demuestra el conocimiento de hechos futuros o espacialmente
        lejanos, se encuentra en un espacio y un tiempo psíquicamente
        relativos, es decir, en un continuo espacio-temporal irrepresentable.
        
        La sincronicidad no es más enigmática o misteriosa que los
        discontinuos de la física.
        
        Coincidences are also a kind of message. By paying attention to
        life’s coincidences, you can learn to hear their messages more clearly.
        
        When you live your life with an appreciation of coincidences and their
        meanings, you connect with the underlying field of infinite possibilities. This is
        when the magic begins. This is a state I call synchrodestiny, in which it becomes
        possible to achieve the spontaneous fulfillment of our every desire.
        Synchrodestiny requires gaining access to a place deep within yourself, while at
        the same time awakening to the intricate dance of coincidences out in the
        physical world. It requires understanding the profound nature of things,
        recognizing the wellspring of intelligence that endlessly creates our universe,
        and yet having the intention to pursue specific opportunities for change as they
        appear.
        
        Seeing the web of coincidence in our lives, however, is just the first stage in
        understanding and living synchrodestiny.
        
        The next stage is to develop an
        awareness of coincidences while they are happening. It is easy to see them in
        hindsight, but if you catch coincidences at the moment they occur, you are better
        positioned to take advantage of the opportunities they may be presenting. Also,
        awareness translates into energy. The more attention you give to coincidences,
        the more likely they are to appear, which means you begin to gain greater and
        greater access to the messages being sent to you about the path and direction of
        your life.
        
        We consciously shape our destinies into the limitlessly creative expressions they
        were meant to be, and by doing so we live out our most profound dreams,
        moving closer to enlightenment.
        
   ## Flores de Bach
      * http://www.institutobach.com.ar/cursos/category/las-38-flores/page/3/
      
   ## Specialize
      * https://amaca.substack.com/p/how-i-got-wealthy-without-working
      
   ## Interview
      * https://www.acefrontend.com/
      * PRACTICE PLATFORMS: LeetCode, HackerRank, Pramp, ExpertMitra, interviewing.io, HackerEarth, AlgoExpert
      * INTERVIEW GUIDES: Tech Interview Handbook, Coding Interview University, “How to ace coding interviews”, Interviews.school
      * https://www.educative.io/blog/crack-amazon-coding-interview-questions // Amazon
      * https://lanie.dev/tech/interviewing/
      * https://www.reddit.com/r/berkeley/comments/ly5bce/i_made_a_chrome_extension_that_autofills_job_apps/ // Job filling application
