# :wave: GitHub: introducción

## 🤓 Idea general de este curso y aprendizaje que se obtendrá

 🚀
El objetivo de este curso es darte una introducción sencilla a GitHub. También se te proporcionan recursos para continuar elmaprendizaje y unas pocas ideas para empezar a manejar esta plataforma.

## :octocat: Git y GitHub

Git es un **Sistema distribuido de Control de Versiones**, en inglés **distributed Version Control System (VCS)**, lo que significa que se usa para llevar control de los cambios que se van haciendo en tus programas, para hacerlo colaborativamente, y para compartir el código. Con Git puedes hacer seguimiento de los cambios que se hacen en un proyecto, de manera que siempre tenemos registrode en qué hemos trabajado, y se pueden deshacer estos cambios fácilmente, volviendo a una versión anterior si es necesario. También facilita trabajar con los demás. Grupos de colaboradores pueden trabajar juntos en el mismo proyecto y unir sus cambios en la versión final.

GitHub es una herramienta que proporciona la misma capacidad de Git, pero desde una web online, para que sea más fácil de usar. Se usa extensamente en todo el mundo, entre desarrolladores de software, para participar en proyectos y para conservar una copia "historica" de los mismos.

GitHub es el lugar donde se alojan algunas de las tecnologías más avanzadas del mundo. Ya sea que estés visualizando datos o creando un nuevo juego, habrá una comunidad y un conjunto de herramientas en GitHub que te pueden ayudar a avanzar en tu tarea. Este curso comienza con los aspectos básicos de GitHub, pero se profundizará más tarde en lo demás.

## :octocat: El flujo de trabajo de GitHub

El flujo de trabajo de GitHub es sencillo, y permite experimentar con los cambios y realizar colaboraciones con facilidad, sin riesgo de perder el trabajo previo.

### Repositorios

Un repositorio es el sitio que almacena un proyecto. Se puede pensar en él como si fuera el armario o el archivador de ese proyecto, la carpeta de ese proyecto. Contiene totos los archivos del proyecto y el historial de cambios. Se puede trabajar en un repositorio siendo una sola persona, o invitar a otros a colaborar para que modifiquen esos archivos.

### Clonar

Cuando se crea un repositorio con GitHub, el almacenamiento está en la nube ☁️. Puedes clonar ese repositorio para crear una copia local en tu ordenador, y después usar **git** para sincronizarlos. Así es más fácil reparar los errores, y añadir o borrar archivos, o hacer cambios múltiples de golpe. Además, también se puede usar la herramienta de edición que prefieras, al contrario que si editas desde la web de GitHub. Al clonar un repositorio, se obtienen todos los datos de control que hay en GitHub acerca de ese proyecto en ese momento, incluyendo todas las versiones de cada archivo y carpeta. Esto sirve de gran ayuda, ya que si experimentamos con el funcionamiento de una modificación podemos darnos cuenta de que alguna versión anterior era mejor que la actual.
Para aprender más sobre el clonado, leer ["Cloning a Repository"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

### Commit y push
**Commit** y **push** son las instrucciones con las que se hacen efectivos los cambios de tus archivos y se suben desde tu máquina hacia el repositorio online "remoto" en GitHub. De esta manera, los compañeros de equipo y el dueño del repositorio pueden ver tus últimas modificaciones. Se hace un "commit" cuando has hecho una serie de modificaciones que quieres someter a la comprobación por parte de tus compañeros. En esta instrucción se agrega normalmente un mensaje, **commit message** para que sirva de recordatorio del trabajo que se ha modificado (Por ejemplo, "he añadido un archivo README con información de los objetivos de nuestro programa para los lectores externos").

Cuando ya hemos acumulado varios commit (o solo uno si no hacen falta más), se debe usar la instrucción **push** para guardar esos cambios en el repositorio de GitHub. Estas dos instrucciones pueden parecer raros al principio, pero os vais a acostumbrar muy pronto. 🙂

## 💻 vocabulario GitHub imprescindible

### Repositorio
Como se ha dicho antes, es donde se almacena el proyecto -archivos y carpetas, y también llevala cuenta de los cambios hechos-. Veámoslo en más detalle. Conforme vamos trabajando en GitHub cada vez tendremos más repositorios, y eso es confuso al principio. Afortunadamente, tu ["Escritorio GitHub"](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard) permite navegar fácilmente por tus repositorios y ver la información necesaria sobre cada uno. ¡Asegúrate de estar identificado para poder verlo!

Los repositorios suelen contener archivos **README**. Sirven para dejar escrita la explicación básica del proyecto, para que la gente que entra sepa para qué sirve este proyecto, qué pueden hacer con él, y cómo se manejan sus archivos. Esto que estás leyendo ahora es un archivo README. 😄 
Para aprender más acerca de los repositorios, leed ["Creating, Cloning, and Archiving Repositories](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) y ["About README's"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes). 

### Ramas ("Branches")
Las ramas guardan de manera separada los cambios que no queremos mezclar todavía en el proyecto final. cada "branch" te permite probar características nuevas en las que todavía no hemos combrobado el funcionamiento, corregir errores anteriores, o experimentar de manera segura con nuevas ideas en un área separada que no afecte a lo que ya funciona. De manera normal, uno debe crear una rama nueva desde la rama principal del repositorio para empezar a trabajar con cualquier retoque. En esa rama creamos los cambios.A continuación hacemos un "commit" y "push", para compartir esa nueva rama con un compañero para que la compruebe si funciona, nos dé sugerencias, y después, si se considera adecuado, mezclarla con la rama principal y borrar (o no) la que habíamos creado.
Para aprender más sobre ramas, leed ["About Branches"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).

### Forks
A fork is another way to copy a repository, but is usually used when you want to contribute to someone else’s project. Forking a repository allows you to freely experiment with changes without affecting the original project and is very popular when contributing to open source software projects!
To learn more about forking, read ["Fork a repo"](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo)

### Pull requests
When working with branches, you can use a pull request to tell others about the changes you want to make and ask for their feedback. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add more changes if need be. You can add specific people as reviewers of your pull request which shows you want their feedback on your changes! Once a pull request is ready-to-go, it can be merged into your main branch.
To learn more about pull requests, read ["About Pull Requests"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests). 


### Issues
Issues are a way to track enhancements, tasks, or bugs for your work on GitHub. Issues are a great way to keep track of all the tasks you want to work on for your project and let others know what you plan to work on. You can also use issues to tell a favorite open source project about a bug you found or a feature you think would be great to add!

For larger projects, you can keep track of many issues on a project board. GitHub Projects help you organize and prioritize your work and you can read more about them [in this "About Project boards document](https://docs.github.com/en/github/managing-your-work-on-github/about-project-boards). You likely won’t need a project board for your assignments, but once you move on to even bigger projects, they’re a great way to organize your team’s work!
You can also link together pull requests and issues to show that a fix is in progress and to automatically close the issue when someone merges the pull request.
To learn more about issues and linking them to your pull requests, read ["About Issues"](https://docs.github.com/en/github/managing-your-work-on-github/about-issues). 

### Your user profile

Your profile page tells people the story of your work through the repositories you're interested in, the contributions you've made, and the conversations you've had. You can also give the world a unique view into who you are with your profile README. You can use your profile to let future employers know all about you! 
To learn more about your user profile and adding and updating your profile README, read ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme). 

### Using markdown on GitHub 

You might have noticed already, but you can add some fun styling to your issues, pull requests, and files. ["Markdown"](https://guides.github.com/features/mastering-markdown/) is an easy way to style your issues, pull requests, and files with some simple syntax. This can be helpful to organize your information and make it easier for others to read. You can also drop in gifs and images to help convey your point!
To learn more about using GitHub’s flavor of markdown, read ["Basic Writing and Formatting Syntax"](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax). 

### Engaging with the GitHub community

The GitHub community is vast. There are many types of people who use GitHub in their day to day—students like you, professional developers, hobbyists working on open source projects, and explorers who are just jumping into the world of software development on their own. There are many ways you can interact with the larger GitHub community, but here are three places where you can start. 

#### Starring repositories 

If you find a repository interesting or you want to keep track of it, star it! When you star a repository it’s also used as a signal to surface better recommendations on github.com/explore. If you’d like to get back to your starred repositories you can do so via your user profile. 
To learn  more about starring repositories, read ["Saving Repositories with Stars"](https://docs.github.com/en/github/getting-started-with-github/saving-repositories-with-stars). 

#### Following users 

You can follow people on GitHub to receive notifications about their activity and discover projects in their communities. When you follow a user, their public GitHub activity will show up on your dashboard so you can see all the cool things they are working on. 
To learn more about following users, read ["Following People"](https://docs.github.com/en/github/getting-started-with-github/following-people).

#### Browsing GitHub Explore 

GitHub Explore is a great place to do just that … explore :smile: You can find new projects, events, and developers to interact with.

You can check out the GitHub Explore website [at github.com/explore](https://github.com/explore). The more you intereact with GitHub the more tailored your Explore view will be. 

## 📝 Optional next steps 

* Open a pull request and let your teacher know that you’ve finished this course.  
* Create a new markdown file in this repository. Let them know what you learned and what you are still confused about! Experiment with different styles!
* Create your profile README. Let the world know a little bit more about you! What are you interested in learning? What are you working on? What's your favorite hobby? Learn more about creating your profile README in the document, ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).
* Go to your user dashboard and create a new repository. Experiment with the features within that repository to familiarize yourself with them. 
* [Let us know what you liked or didn’t like about the content of this course](https://support.github.com/contact/education). What would you like to see more of? What would be interesting or helpful to your learning journey? 

## 📚  Resources 
* [A short video explaining what GitHub is](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be) 
* [Git and GitHub learning resources](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources) 
* [Understanding the GitHub flow](https://guides.github.com/introduction/flow/)
* [How to use GitHub branches](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Interactive Git training materials](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub's Learning Lab](https://lab.github.com/)
* [Education community forum](https://education.github.community/)
* [GitHub community forum](https://github.community/)
