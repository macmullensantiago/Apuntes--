# Apuntes--

## What is programming?
     * It's about making software.
      
  # What is software?
     * It's what runs in our hardware, runs in our computer.
     * Software is the files that you can open up in your computer and you can interact with.
     * It's what is written using programming code.
      
  # What is code?
     * Code is just a technical implementation of algorithms, wich are step-by-step instructions for solving problems.
      
 # What share in common computer programs? // Definir
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
      
   Committing to Git
      
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
      
   Opening a file to work on it
      
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
      
   Backing up and sharing
   
      With the changes made in Section 1, we’re now ready to push a copy of our project
      to a remote repository. This will serve as a backup of our project and its history,
      and will also make it easier for collaborators to work with us on our site.
      We’ll start by pushing our project up to GitHub, a site designed to facilitate
      collaboration with Git repositories. For repositories that are publicly available,
      GitHub is free, so we’ll plan to make our website’s repo public to take advantage
      of this.
      
      Over time, releasing projects publicly on GitHub serves to build up
      a portfolio, which is one good reason to make as much work public as possible.
      
   Remote repo
   
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
      
   Adding a README
   
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
      
   Branching and merging
   
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
      
   Recovering from errors
   
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
     
   Collaborating
   
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
      
   ## Specialize
      * https://amaca.substack.com/p/how-i-got-wealthy-without-working
      
   ## Interview
      * https://www.acefrontend.com/
