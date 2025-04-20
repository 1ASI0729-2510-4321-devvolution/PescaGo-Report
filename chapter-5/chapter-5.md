## Capítulo V: Product Implementation, Validation & Deployment  
### 5.1. Software Configuration Management
En esta sección describimos los productos de software que hemos usado en el proyecto.
  #### 5.1.1. Software Development Environment Configuration
  
  - Project Management
  
    - Github: (https://github.com/)
        
        Es donde organizamos el proyecto. Aquí está la organización, la cual contiene 4 repositorios: Informe, Landing Page, Frontend y Backend
    
  - Requirements Management

    - Pivotal Tracker: (https://www.pivotaltracker.com/)

        Es un software que usamos para gestionar los proyectos y establecer las historias de usuario del proyecto

  - Product UX/UI Design
    
    - UXPressia: (https://uxpressia.com/)

        Acá diseñamos las User Persona, User Journey Mapping y Empathy Mapping
    
    - Figma: (https://www.figma.com/es-es/)

        Acá hicimos los diseños de la landing page y de la aplicación web (wireframes, mockups y prototipos)

  - Software Development
    - Git: Es un software de control de versiones para desarrollar el proyecto
    - Github: Es un sistema de control de versiones de Git
    - HTML5: Es un lenguaje de marcado que sirve para estructurar la página
    - CSS3: Es un lenguaje de hojas de estilo en cascada que le da estilo a la página (hace que una  página sea visualmente más atractiva)
    - JavaScript: Es un lenguje de programación que genera interactividad y dinamismo a una sitio web
    - VSCode: Es el editor de código fuente para el desarrollo de la landing page
    - Angular: Es un framework que usaremos para el desarrollo frontend de la aplicación web

  - Software Deployment
    - Github Pages: Plataforma para desplegar la landing page

  #### 5.1.2. Source Code Management

  Utilizamos Github como plataforma, así como un sistema de control de versiones.
  
  Para ello se creó una organización para el proyecto del equipo. En esta organización, se crearon 4 repositorios, los cuales corresponden al informe del proyecto, la landing page, el frontend y el backend.
  
  - Organización del proyecto: https://github.com/1ASI0729-2510-4321-devvolution
    - Informe: https://github.com/1ASI0729-2510-4321-devvolution/PescaGo-Report
    - Landing page: https://github.com/1ASI0729-2510-4321-devvolution/PescaGo-LandingPage
    - Frontend: https://github.com/1ASI0729-2510-4321-devvolution/PescaGo-Frontend
    - Backend: https://github.com/1ASI0729-2510-4321-devvolution/PescaGo-Backend

  Gitflow Decidimos utilizar este modelo de trabajo ya que permite mantener el codigo ordenado al dividirlo en ramas, de tal forma que nos facilita trabajar colaborativamente. Las ramas que se utilizaron son:

  - Main: En esta rama se encuentra el código que se encuentra en producción.
  - Develop: En esta rama se encuentra el código que se encuentra en desarrollo.
  - Feature: En esta rama se encuentran las nuevas funcionalidades que se están desarrollando.

  Conventional commits Se utilizó el estándar de commits convencionales para mantener un historial de cambios limpio y ordenado. Los commits se dividen en los siguientes tipos:

  - feat: Se utiliza para nuevas funcionalidades.
  - fix: Se utiliza para corrección de errores.
  - chore: Se utiliza para cambios en el código que no afectan la funcionalidad.
  - refactor: Se utiliza para cambios en el código que no afectan la funcionalidad.

  #### 5.1.3. Source Code Style Guide & Conventions

  Para desarrollar nuestro proyecto hemos requerido de algunas nomenclaturas, referencias y lenguajes para la solución.
  
  Tecnologias: Utilizamos HTML5, CSS3 y JavaScript para el desarrollo de la landing page.

  - HTML: Para el lenguaje HTML, nos planteamos utilizar las convenciones descritas en la guía “HTML Style Guide and Coding Conventions”:
  
    - Usar nombres de elementos en minúsculas.
    - Cerrar todos los elementos HTML.
    - Usar nombres de atributos en minúsculas.
    - Usar atributos en imágenes.
    - Evitar líneas de código largas.
    - Usar sintaxis simple para los enlaces para las hojas de estilo y para cargar script externos

  - CSS: Para el lenguaje CSS, utilizaremos las siguientes prácticas para alcanzar un código coherente, sostenible y ordenado:

    - Utilizar minúsculas y guiones para los nombres de propiedades.
    - Utilizar un espacio después de los dos puntos y un punto y coma para separar pares -  propiedad-valor.
    - Agrupar reglas CSS relacionadas y separarlas con una línea en blanco.
    - Utilizar nombres de clases que sean descriptivos y reflejen el propósito del elemento.
    - Separar los nombres de las clases y ID con un guión

  Herramientas: Nos apoyamos de las tecnologías más utilizadas y recomendadeas para el desarrollo web, como los son Webstorm, Git, GitHub, LudcidChart, Figma y Miro.


  #### 5.1.4. Software Deployment Configuration

  Implementaremos la landing page utilizando Github Pages. Esta herramienta nos permite publicarla directamente desde un repositorio de Github. El proceso implica crear el repositorio, configurarlo para la publicación, subir los archivos con un commit y copiar el nombre del repositorio para finalizar la configuración. Con estos pasos, la página estará accesible en la web.

### 5.2. Landing Page, Services & Applications Implementation
  #### 5.2.1. Sprint 1
   #### 5.2.1.1. Sprint Planning 1
  
  <table border="1px" align="center">
      <tr>
          <th>Sprint #</th>
          <th>Sprint 1</th>
      </tr>
      <tr> 
          <td colspan="2" style="text-align: center;">Sprint Planning Background</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Date</td>
          <td>07-04-2025</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Time</td>
          <td>8:00 pm - 10:00 pm</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Location</td>
          <td>Canal de Voz de Discord</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prepared By</td>
          <td>Belleza Tello, Paolo Eduardo</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Attendees (to planning meeting)</td>
          <td>
              Belleza Tello, Paolo Eduardo<br>
              Fernandez Alva, María Fernanda<br>
              Macavilca Quispe, Ian<br>
              Prado Vargas, Mario Benjamín<br>
              Ramos Argüelles, Alexandra Belen<br>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Sprint 1 Review Summary</td>
          <td>Se desarrolló la landing page a partir de los diseños de wireframe, mockup y  prototipo, para luego implementar el código en HTML, CSS y JavaScript.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Sprint 1 Retrospective Summary</td>
          <td>Buscaremos ser más precisos con los plazos de entrega de los avances. La comunicación entre el equipo fue positiva y todos contribuyeron con ideas al proyecto.</td>
      </tr>
      <tr> 
          <td colspan="2" style="text-align: center;">Sprint Goal & User Stories</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Sprint 1 Goal</td>
          <td>
              El objetivo principal de este sprint es la creación de la landing page de nuestro   producto. Esperamos que esta página ofrezca una experiencia visualmente atractiva y   una información concisa, lo cual se validará con la interacción de los usuarios en  cada parte.
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Sprint 1 Velocity</td>
          <td>18</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Sum of Story Points</td>
          <td>18</td>
      </tr>
    </table>


   #### 5.2.1.2. Sprint Backlog 1


| Sprint # | Sprint 1 | | | | | | |
|:-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| User Story | Work-Item / Task | | | | | | |
| Id | Title | Id | Title | Description | Estimation (Hours) | Assigned To | Status (To-Do / In-Process/ To- Review/ Done) |



   #### 5.2.1.3. Development Evidence for Sprint Review

   <table>
    <tr>
     <td><strong>Repository</strong></td>
     <td><strong>Branch</strong></td>
     <td><strong>Commit Id</strong></td>
     <td><strong>Commit Message</strong></td>
     <td><strong>Commit Message Body</strong></td>
     <td><strong>Commited on (Date)</strong></td>
    </tr>
    <tr>
     <td>Landing-Page</td>
     <td>main</td>
     <td>8bda2cc</td>
     <td>feature:</td>
     <td>feat(repo): add README</td>
     <td>0x/0x/2025</td>
    </tr>  
   </table>

   #### 5.2.1.4. Testing Suite Evidence for Sprint Review
   #### 5.2.1.5. Execution Evidence for Sprint Review
   #### 5.2.1.6. Services Documentation Evidence for Sprint Review
   #### 5.2.1.7. Software Deployment Evidence for Sprint Review
   #### 5.2.1.8. Team Collaboration Insights during Sprint
  