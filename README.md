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
   
   ## Step 3: Make the move -> Moving your local project to GitHub
   
      Having a project already stored locally enables you to move it to GitHub rather quickly. The following activity provides instructions to move your local project to GitHub using various tools. Select the tool you are most comfortable with and get importing 😄.

   ⌨️ Activity: Moving your local project 
      
      In the Code tab of this repository, copy the URL shown under Quick Setup.
      Follow the instructions below based on what tool you'd like to use locally.
      
         * Using the command line
            
                  In your command line, navigate to your project directory. Type git init to initialize the directory as a Git repository.
                  Type git remote add origin https://github.com/macmullensantiago/github-upload.git
                  Type git add .
                  Type git commit -m "initializing repository"
                  Type git push -u origin main to push the files you have locally to the remote on GitHub. (You may be asked to log in.)
                  Note: You can also use a password protected SSH key to connect to GitHub. See Connecting to GitHub with SSH in our documentation to learn more.

         
         * Using GitHub Desktop
            
                  GitHub Desktop doesn't allow you to add a new remote for an existing directory, so instead we'll copy the contents of your existing folder to our repo. If you'd like to keep your existing folder, you may want to use the command line or one of the other tools.

                  In GitHub Desktop, click on File and Clone a repository.
                  Click on the URL tab.
                  Paste the URL from this repository.
                  Move the contents of your local repository to this directory.
                  Create a commit by entering a commit message and then clicking on Commit to main
                  Click Publish branch in the top right corner to push your repository to GitHub.
                  
         * Using Visual Studio Code
         
                  In Visual Studio Code, open the folder for your project.
                  Click the icon on the left for Source Control.
                  On the top of the Source Control panel, click the Git icon.
                  If the files you see match the repository you want to create, click Initialize Repository.
                  Next to the word CHANGES, click the symbol of the plus sign to stage all of the changes.
                  This is part of the two stage commit. You can use this staging function to create meaningful commits throughout the development process.
                  In the box in the Source Control panel, type a commit message. Something like "initial commit - moving project" could work.
                  Click the checkmark at the top of the Source Control panel.
                  Open the integrated terminal found under View > Integrated Terminal.
                  In your command line, type git remote add origin https://github.com/macmullensantiago/github-upload
                  In the Source Control Panel, click the expandable three dots that open a menu of options.
                  When asked if you'd like to publish the branch, click Okay.

         
         * Using Atom
         
                  In Atom, open the folder for your project
                  At the top of your screen, click Packages. Select GitHub, and then toggle the Git Tab from the drop-down menu.
                  Select Create Repository within the Git tab on the right-hand size of your screen.
                  Select Init to accept the default prompt of the pop up window
                  In the Git tab, you can see that your files are ready for staging. It should be accounted for, but double check to make sure that none of your binaries or files that you listed in the .gitignore are listed in this dialog menu.
                  - If they are, double check your .gitignore file to make sure they're included or remove them from your directory.
                  Select Stage All
                  - This is part of the two stage commit. You can use this staging function to create meaningful commits throughout the development process.
                  In the box at the bottom of the Git panel, type a commit message. Something like "initial commit - moving project" could work.
                  Select Commit
                  Close Atom
                  In your command line, navigate to your project directory.
                  Type git remote add origin https://github.com/macmullensantiago/github-upload
                  Return to Atom, and select the Up/Down arrow icon at the bottom of your Git Tab
                  Click Push, above the noted dialog.
                  Return to your repository, and note a successful push by finding your files on GitHub's code tab.
         
         * Using Eclipse
         
            In Eclipse, from the Eclipse Marketplace, install the eGit GitHub plugin.
            Open your existing project.
            Display the Git Repositories window by selecting Window > Show View > Other > Git > Git Repositories.
            Click the Create a Git Repository button on the Git Repositories pane.
            Make changes to your project and create a commit.
            Push the changes to your default branch.
            When asked for a remote, paste the URL you copied earlier.
            Click next, and enter the branch name.

         

   ## GitHub Learning Resources
      
      * https://guides.github.com/
      * https://www.youtube.com/githubguides
      
   ## Differences between Software Engineer, Web developer and Programmer
   
   * There are a few ways to spot the differences among software engineer, web developer, and programmer roles.
    
       + Web developers are focused on creating browser apps with a combination of client-side and server-side programming languages. Generally speaking, they are involved in            designing interactive websites and building user-facing applications.
    
       + Software engineers are more likely to work on computer systems as a whole. They develop standalone programs and apps to help users perform various activities. For the            most part, they program, document, test, and maintain software by utilizing the best practices in DevOps.
       
   * Front-End & Back-End
   
       + The only real distinction you have to make is the one between front-end and back-end programming — whether you’re designing surface-level UI and user-centric                    applications or running hidden processes inside a database server.
       
   - "At the end of the day, we're all trying to solve business problems with code."
