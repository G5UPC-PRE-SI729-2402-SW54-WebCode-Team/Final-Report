
---

# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration

En este apartado, se mencionarán los distintos productos de software empleados por el equipo de desarrollo, para llevar acabo las actividades relacionadas con la elaboración del proyecto.


<br>

**Project Management** 

Discord (https://discord.com/): Es una plataforma de mensajería y chat de voz, los usuarios pueden comunicarse por llamadas de voz, videollamadas, mensajes de texto o con archivos. Facilitando la comunicación entre los integrantes del proyecto. 

<br>

**Product UX/UI Design** 

UXPressia (https://uxpressia.com/): Es una herramienta en línea que permite a los equipos de trabajo identificar y comprender los problemas, necesidades y comportamiento del usuario en relación a la solución de software que se está desarrollando, con el uso de plantillas. Se utilizó para la elaboración de los User Personas, Empathy Maps, Journey Maps e Impact Maps.

Figma (https://www.figma.com/): Figma es una herramienta de edición gráfica, en donde se puede diseñar y prototipar páginas web y aplicaciones de manera colaborativa en tiempo real. Se usó para realizar los wireframes, mock-ups y los desktop and mobile application prototype del proyecto.

Miro (https://miro.com/): Es una plataforma colaborativa el cual permite crear y usar pizarras digitales personalizadas en tiempo real. Miro cuenta con distintas herramientas y plantillas para la elaboración de mapeos, diagramas, flujos de trabajo, etc. Se utilizó para la realización de los As-Is y Tob-Be Scenario Maps.  
<br>

**Software Development**  

Landing Page: Para la creación de la landing page, se utilizaron las tecnologías base del desarrollo web: HTML5, CSS3 y JavaScript.  

GitHub (https://github.com/): Esta es una plataforma digital donde se pueden alojar proyectos mediante repositorios, los cuales utilizan un sistema de control de versiones llamado Git. GitHub nos permite trabajar colaborativamente y tener un seguimiento detallado de los avances en el proyecto. 

Git (https://git-scm.com/): Este es un software de control de versiones el cual se instala localmente y nos permite tener un historial de cambios que se realizan en el proyecto mediante commits. También se utiliza para trabajar colaborativamente en repositorios que se encuentran subidos en GitHub. 

WebStorm: Este es un entorno de desarrollo, el cual nos permite trabajar con HTML, CSS, Javascript y con frameworks como Vue y Angular.

**Software Documentation**  

LucidChart (https://lucid.app/): LucidChart es una plataforma que cuenta con opciones para la creación de diagramas, mapas mentales, flujos y más, con el uso de plantillas y tableros con edición en tiempo real. Fue utilizado en el desarrollo del diagrama de clases UML, así como los Wireflows y User Flows.

Structurizr (https://www.structurizr.com/): Es una plataforma que permite modelado de diagramas de arquitectura de software por medio de código. Structurizr fue utilizado para crear el modelo C4 de nuestro proyecto.     
<br>

**Software Testing**

Gherkin: Este es un lenguaje DSL (Domain Specific Language), que nos permite abordar problemas específicos. Esto lo utilizamos para los criterios de aceptación de las historias de usuario de nuestro proyecto.

Markdown: Este es un lenguaje de marcado ligero, el cual nos permite documentar proyectos. En cuanto a nosotros, utilizamos este lenguaje para redactar el informe de nuestro proyecto y en los archivos README en el repositorio de la organización. 

### 5.1.2. Source Code Management

En esta seccion se detalla que medios se utilizaron parea el seguimiento de las modificaciones, asi como la semantica y nomenclatura que se usara para los commits y releases. 
Para el sistema de control de versiones del informe, landing page, web service y front-end se utilizó Git, el cual se encuentra alojado en GitHub.
- Url de la organizacion: [github.com/UPC-OpenSource-GreenGo](https://github.com/G5UPC-PRE-SI729-2402-SW54-WebCode-Team/Final-Report)
  

**Gitflow**
Decidimos utilizar este modelo de trabajo ya que permite mantener el codigo ordenado al dividirlo en ramas, de tal forma que nos facilita trabajar colaborativamente. Las ramas que se utilizaron son:
- Main: En esta rama se encuentra el código que se encuentra en producción.
- Develop: En esta rama se encuentra el código que se encuentra en desarrollo.
- Feature: En esta rama se encuentran las nuevas funcionalidades que se están desarrollando. 

**Conventional commits**
Se utilizó el estándar de commits convencionales para mantener un historial de cambios limpio y ordenado. Los commits se dividen en los siguientes tipos:
- **feat**: Se utiliza para nuevas funcionalidades.
- **fix**: Se utiliza para corrección de errores.
- **chore**: Se utiliza para cambios en el código que no afectan la funcionalidad.
- **refactor**: Se utiliza para cambios en el código que no afectan la funcionalidad.

### 5.1.3. Source Code Style Guide & Conventions.

Para desarrollar nuestro proyecto hemos requerido de algunas nomenclaturas, referencias y lenguajes para la solución.

**Tecnologias:** Utilizamos HTML5, CSS3 y JavaScript para el desarrollo de la landing page. 
- **HTML:** Para el lenguaje HTML, nos planteamos utilizar las convenciones descritas en la guía “HTML Style Guide and Coding Conventions”:
  - Usar nombres de elementos en minúsculas.
  - Cerrar todos los elementos HTML.
  - Usar nombres de atributos en minúsculas.
  - Usar atributos en imágenes.
  - Evitar líneas de código largas.
  - Usar sintaxis simple para los enlaces para las hojas de estilo y para cargar script externos

- **CSS:** Para el lenguaje CSS, utilizaremos las siguientes prácticas para alcanzar un código coherente, sostenible y ordenado:
  
  - Utilizar minúsculas y guiones para los nombres de propiedades.
  - Utilizar un espacio después de los dos puntos y un punto y coma para separar pares propiedad-valor.
  - Agrupar reglas CSS relacionadas y separarlas con una línea en blanco.
  - Utilizar nombres de clases que sean descriptivos y reflejen el propósito del elemento.
  - Separar los nombres de las clases y ID con un guión

- **Gherkin:** Es un lenguaje de dominio específico diseñado para escribir especificaciones legibles por humanos que describen el comportamiento del software en un formato estructurado y comprensible. En busca de una buena práctica, se utilizarán saltos de línea para mejorar el orden de los escenarios y poder diferenciarlos de forma más óptima. Además, se escribirán los escenarios bajo el formato “Given”, “When”, “Then”, “And” para definir claramente el contexto, la acción y el resultado esperado.
**Herramientas:** Nos apoyamos de las tecnologías más utilizadas y recomendadeas para el desarrollo web, como los son Webstorm, Git, GitHub, LudcidChart, Figma y Miro.

**Convenciones de idioma:** Uso del idioma inglés para elaborar nuestro código, incluyendo la parte de la landing page.

### 5.1.4. Software Deployment Configuration.

Para desplegar la solución se realizó los siguientes pasos:


- Ingresar a los repositorios de la organizacion de GitHub a través del URL: [github.com/UPC-OpneSource-GreenGo](https://github.com/orgs/G5UPC-PRE-SI729-2402-SW54-WebCode-Team/repositories) 

![Organizacion GreenGo](../assets/chapter-05/Deployment-Config/Paso-N1.png)

- Seleccionar el repositorio de la landing page del proyecto.
  
![Repositorio Landing Page](../assets/chapter-05/Deployment-Config/Paso-N2.png)

- Clonar el repositorio en Webstorm utilizando la URL del repositorio.

![Clonar Repositorio](../assets/chapter-05/Deployment-Config/Paso-N3.png)

![Clonar Repositorio](../assets/chapter-05/Deployment-Config/Paso-N4.png)

- Ejecutar el archivo index.html para visualizar la landing page en el navegador.

![Visualizar Landing Page](../assets/chapter-05/Deployment-Config/Paso-N5.png)
![Visualizar Landing Page](../assets/chapter-05/Deployment-Config/Paso-N6.png)


## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1

### 5.2.1.1. Sprint Planning 1
|**Sprint #**|Sprint 1|
| :- | :- |
|**Sprint Planning Background**||
|**Date**|02-09-2024|
|**Time**|07:00 PM|
|**Location**|Canal de Voz de Discord|
|**Prepared By**|Diestra Zambrano, Adriana María|
|**Attendees (to planning meeting)**|Travezaño Patiño, Eduard Gedeon/ Aru Acevedo, Yair Christofer/ Villon Amez, Enrique Manuel/ Horna Silva, Fabio Ernesto|
|**Sprint 1 Review Summary**|**Equipo de desarrollo:** El equipo realizó las tareas asignadas exitosamente para la realización de una buena captura de los requisitos del producto software y su diseño e implementación.<br>**Landing Page:** Se realizaron los diseños wireframe, mockup y prototype para posterior a ello, establecer el código de la página web estática en HTML, CSS y JavaScript.|
|**Sprint 1 Retrospective Summary**|Oportunidades de mejora: Se vio que hay que mejorar un poco en la gestión de tiempos del equipo en cuanto a completar las tareas asignadas e ir midiendo avances.|
|**Sprint Goal & User Stories**||
|**Sprint 1 Goal**|**Objetivos:**<br>Investigación: Realizar el UX Research<br>**Métrica:** Realización y demostración de los hallazgos.<br><br>Diseño: Realizar diseños wireframe, mockup y prototype de la Landing Page.<br>**Métrica:** Creación exitosa de mockups interactivos para al menos el 80%.<br><br>Programación: Codificar Landing Page en los lenguajes de HTML, CSS y JavaScript.<br>**Métrica:** Corrección exitosa del 100% del código a nivel de legibilidad.<br><br>Despliegue: Desplegar la solución estática<br>**Métrica:** Verificación de que la Landing Page se ha desplegado correctamente en el entorno de producción.|
|**Sprint 1 Velocity**|16|
|**Sum of Story Points**|16|

### 5.2.1.2. Sprint Backlog 1

### 5.2.1.3. Development Evidence for Sprint Review

### 5.2.1.4. Testing Suite Evidence for Sprint Review

### 5.2.1.5. Execution Evidence for Sprint Review

### 5.2.1.6. Services Documentation Evidence for Sprint Review

### 5.2.1.7. Software Deployment Evidence for Sprint Review

### 5.2.1.8. Team Collaboration Insights during Sprint


---
