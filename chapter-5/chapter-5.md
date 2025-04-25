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
| Epic/ Story | | Work-Item | | | | | |
| Id | Title | Id | Title | Description | Estimation (Hours) | Assigned To | Status (To-Do / In-Process/ To- Review/ Done) |
| E1-US01 | Barra de Navegación en la Landing Page | W01 | Barra de Navegación | Facilitar el acceso a las secciones más relevantes del servicio |  4 | Prado Vargas, Mario Benjamín | Done  |
| E1-US02 | Información sobre el servicio brindado | W02 | Info Trasfondo del Servicio | La página web debe mostrar la información de los servicios que me van a brindar |  4 | Prado Vargas, Mario Benjamín | Done  |
| E1-US03 | Información sobre el procedimiento de uso de la aplicación web | W03 | Info Uso del Servicio | Mostrar el procedimiento que tendría que hacer un usuario para usar este servicio | 4  | Prado Vargas, Mario Benjamín |  Done |
| E1-US04 | Conocer los testimonios de clientes pasados | W04 | Sección Testimonios | Mostrar algunos testimonios de "clientes anteriores" |4   | Prado Vargas, Mario Benjamín | Done  |
| E1-US05 | Conocer las ventajas de la aplicación web | W05 | Sección Beneficios | Mostrar las ventajas que tiene la aplicación frente a otras aplicaciones similares |  4 | Prado Vargas, Mario Benjamín | Done  |
| E1-US06 | Contacto | W06 | Sección Contactos | Sección con información de contacto | 4  | Prado Vargas, Mario Benjamín | Done  |
| E1-US07 | Cambiar idiomas | W07 | Botón Idiomas | Cambiar el idioma de la página web de Inglés al Español  y viceversa| 4  | Prado Vargas, Mario Benjamín |  To-Do |


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
     <td>PescaGo-LandingPage</td>
     <td>main</td>
     <td>81b0748</td>
     <td>Create index.html</td>
     <td>Add base code to the index.html doc</td>
     <td>24/04/2025</td>
    </tr>
    <tr>
     <td>PescaGo-LandingPage</td>
     <td>main</td>
     <td>09032da</td>
     <td>feat: add navbar</td>
     <td></td>
     <td>24/04/2025</td>
    </tr>
    <tr>
     <td>PescaGo-LandingPage</td>
     <td>main</td>
     <td>dc8a856</td>
     <td>feat: add hero section</td>
     <td></td>
     <td>24/04/2025</td>
    </tr>
    <tr>
     <td>PescaGo-LandingPage</td>
     <td>main</td>
     <td>59a0490</td>
     <td>feat: Adding the Features Section</td>
     <td></td>
     <td>24/04/2025</td>
    </tr>
    <tr>
     <td>PescaGo-LandingPage</td>
     <td>main</td>
     <td>9671f7d</td>
     <td>feat: Adding the Works Section</td>
     <td></td>
     <td>24/04/2025</td>
    </tr> 
    <tr>
     <td>PescaGo-LandingPage</td>
     <td>main</td>
     <td>99cff96</td>
     <td>feat: add testimonials section</td>
     <td></td>
     <td>24/04/2025</td>
    </tr> 
    <tr>
     <td>PescaGo-LandingPage</td>
     <td>main</td>
     <td>2ca13af</td>
     <td>feat: add Why Choose Us Section</td>
     <td></td>
     <td>24/04/2025</td>
    </tr> 
    <tr>
     <td>PescaGo-LandingPage</td>
     <td>main</td>
     <td> 249afd7</td>
     <td>Create script.js</td>
     <td></td>
     <td>24/04/2025</td>
    </tr> 
    <tr>
     <td>PescaGo-LandingPage</td>
     <td>main</td>
     <td>0a3ab9e</td>
     <td>feat: add footer and bootstrap</td>
     <td></td>
     <td>24/04/2025</td>
    </tr> 
    <tr>
     <td>PescaGo-LandingPage</td>
     <td>main</td>
     <td>23fb61f</td>
     <td>Create style.css</td>
     <td></td>
     <td>24/04/2025</td>
    </tr> 
    <tr>
     <td>PescaGo-LandingPage</td>
     <td>main</td>
     <td>aff84c2</td>
     <td>feat: Animation added</td>
     <td></td>
     <td>24/04/2025</td>
    </tr>
    <tr>
     <td>PescaGo-LandingPage</td>
     <td>main</td>
     <td>13c3ffb</td>
     <td>feat: Add base styles and hero section to style.css</td>
     <td></td>
     <td>24/04/2025</td>
    </tr>
    <tr>
     <td>PescaGo-LandingPage</td>
     <td>main</td>
     <td>4b09311</td>
     <td>feat: add styles for primary buttons and section layout with transitions</td>
     <td></td>
     <td>24/04/2025</td>
    </tr>
    <tr>
     <td>PescaGo-LandingPage</td>
     <td>main</td>
     <td>3d77f25</td>
     <td>docs: add styles</td>
     <td></td>
     <td>24/04/2025</td>
    </tr>
    <tr>
     <td>PescaGo-LandingPage</td>
     <td>main</td>
     <td>3ee40be</td>
     <td>Create logo.svg</td>
     <td></td>
     <td>24/04/2025</td>
    </tr>
    <tr>
     <td>PescaGo-LandingPage</td>
     <td>main</td>
     <td>ba13e90</td>
     <td>feat: add footer and bootstrap</td>
     <td></td>
     <td>24/04/2025</td>
    </tr>
    <tr>
     <td>PescaGo-LandingPage</td>
     <td>main</td>
     <td>c17b832</td>
     <td>docs: add image and assets folder</td>
     <td>Created the `assets` folder and uploaded an image for use as the logo.</td>
     <td>24/04/2025</td>
    </tr>
   </table>

   #### 5.2.1.4. Testing Suite Evidence for Sprint Review

   
Para la entrega del Sprint 1, nos enfocamos en lograr el desarrollo completo y el despliegue del Landing Page.

| Repository   | Branch | Commit Id | Commit Message                      | Commit Message Body | Commited On |
| ------------ | ------ | --------- | ----------------------------------- | ------------------- | ----------- |
| PescaGo-LandingPage | main   | 81b0748   | Create index.html | - | 24/04/2025  |

   #### 5.2.1.5. Execution Evidence for Sprint Review
   
   En este sprint, el equipo logro desplegar la primera versión de la landing page satisfactoriamente, en este punto se mostrara la evidencia de ello.   
   
   #### Inicio
   <img src="./assets/landing_d1_01.png"/>

   #### Caracteristicas
   <img src="./assets/landing_d1_02.png"/>

   #### Cómo Funciona
   <img src="./assets/landing_d1_03.png"/>

   #### Testimonios
   <img src="./assets/landing_d1_04.png"/>

   #### Beneficios
   <img src="./assets/landing_d1_05.png"/>

   #### Contacto
   <img src="./assets/landing_d1_06.png"/>   

   #### 5.2.1.6. Services Documentation Evidence for Sprint Review
   
   Link de la landing page desployada: https://pescago.netlify.app/

   #### 5.2.1.7. Software Deployment Evidence for Sprint Review

   Para el desarrollo de la landing page, se usó lo siguiente:
   
   - HTML: Para la estructura de la landing page
   - CSS: Para darle estilos a la landing page
   - JS: Para darle dinamismo a la landing page
   - Git: Es el sistema de control de versiones
   - Github: Software online para almacenar repositorios Git


   #### 5.2.1.8. Team Collaboration Insights during Sprint

   
A continuación, se compartirá la tabla de colaboradores del repositorio de Github para identificar a cada miembro del equipo:

| Username (GitHub) | Nombre                          |
| ----------------- | ------------------------------- |
| AleRamosA                     | Ramos Argüelles, Alexandra Belen |
| PaoloBellezaTelloo            | Belleza Tello, Paolo Eduardo |
| MariaFernandaFernandezAlva    | Fernandez Alva, María Fernanda    |
| IanMQ                         | Macavilca Quispe, Ian      |
| mariopvdev                    | Prado Vargas, Mario Benjamín     |
  

<img src="./assets/commits_sprint1.PNG" alt="imagen de commits"/>
  
    
              
              
              