<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="Logo UPC">


# Universidad Peruana de Ciencias Aplicadas

Ingeniería de Software

Ciclo 2023-02

<hr>

# <center>Desarrollo de Aplicaciones Open Source</center>

## TP REPORT

**Sección:** SV52

**Profesor**: Hugo Allan Mori Paiva

**StartUp Name**: LogicMinds

**Producto**: Rentstate

### Team Members:

| Member                        |    Code    |
|:------------------------------|:----------:|
| Asillo Mendoza, Julio Ernesto | u20201b482 |
| Mamani Aro, Leydi Yaquelin    | u20201b745 |
| Lopez Huaman, Edwin Abdias    | u20201b051 |
| Ruiz Carhuamanca, Angie       | u20201b293 |
| Antonio Salazar, Jhan Clinton | u20201b312 |

<br>

Agosto del 2023

<br><br>

# Project Report Collaboration Insights

- TP: Para esta entrega, realizamos como equipo las actividades correspondientes a los capítulos asignados en el siguiente repositorio dentro de nuestra organización de grupo:

  Link del repositorio del Informe Final: [Github - Informe Final LogicMinds](https://github.com/LogicMinds-Group)

    <br>

</div>

# CONTENT

[Registro de versiones del informe](#_toc145263583)

[Student Outcomes](#_toc145263584)

### [1	Capítulo I: Introducción](#_toc145263585)

[1.1	Startup Profile	](#_toc145263586)

[1.1.1	Descripción de la Startup](#_toc145263587)

[1.1.2	Perfiles de integrantes del equipo](#_toc145263588)

[1.2	Solution Profile](#_toc145263589)

[1.2.1	Antecedentes y problemática](#_toc145263590)

[1.2.2	Lean UX Process	](#_toc145263591)

[1.3	Segmentos Objetivo	](#_toc145263592)

### [2	Capítulo II: ReQUIREMENTS ELiCITATION & ANALYSIS](#_toc145263593)

[2.1	Competidores	](#_toc145263594)

[2.1.1	Análisis Competitivo	](#_toc145263595)

[2.1.2	Estrategias y tácticas frente a competidores](#_toc145263596)

[2.2	Entrevistas	](#_toc145263597)

[2.2.1	Diseño de entrevistas](#_toc145263598)

[2.2.2	Registro de entrevistas	](#_toc145263599)

[2.2.3	Análisis de entrevistas	](#_toc145263600)

[2.3	Needfinding	](#_toc145263601)

[2.3.1	User Personas	](#_toc145263602)

[2.3.2	User Task Matrix	](#_toc145263603)

[2.3.3	User Journey Mapping](#_toc145263604)

[2.3.4	Empathy Mapping	](#_toc145263605)

[2.3.5	As-Is Scenario Mapping	](#_toc145263606)

### [3	Capítulo III: Requirements Specification](#_toc145263607)

[3.1	To-Be Scenario Mapping	](#_toc145263608)

[3.2	User Stories	](#_toc145263609)

[3.3	Impact Mapping	](#_toc145263610)

[3.4	Product Backlog	](#_toc145263611)

### [4	Capítulo IV: PRODUCT DESIGN	](#_toc145263612)

[4.1	Style Guidelines](#_toc145263613)

[4.1.1	General Style Guidelines	](#_toc145263614)

[4.1.2	General Style Guidelines](#_toc145263615)

[4.2	Information Architecture	](#_toc145263616)

[4.2.1	Organizations Systems	](#_toc145263617)

[4.2.2	Labeling Systems	](#_toc145263618)

[4.2.3	SEO tags and Meta Tags](#_toc145263619)

[4.2.4	Searching Systems	](#_toc145263620)

[4.3	Landing Page UI Design	](#_toc145263621)

[4.3.1	Landing Page Wireframe	](#_toc145263622)

[4.3.2	Landing Page Mock-up](#_toc145263623)

[4.4	Web Applications UX/UI Design](#_toc145263624)

[4.4.1	Web Applications Wireframes	](#_toc145263625)

[4.4.2	Web Applications Wireflow Diagrams](#_toc145263626)

[4.4.3	Web Applications Mock-ups	](#_toc145263627)

[4.5	Web Applications Prototyping](#_toc145263628)

[4.6	Domain-Driven Software Architecture](#_toc145263629)

[4.6.1	Software Architecture Context Diagram	](#_toc145263630)

[4.6.2	Software Architecture Container Diagrams](#_toc145263631)

[4.6.3	Software Architecture Components Diagrams	](#_toc145263632)

[4.7	Software Object-Oriented Design	](#_toc145263633)

[4.7.1	Class Diagrams](#_toc145263634)

[4.7.2	Class Dictionary](#_toc145263635)

[4.8	Database Design	](#_toc145263636)

[4.8.1	Database Diagram	](#_toc145263637)

### [5	Capítulo V: Product Implementation, Validation & Deployment	](#_toc145263638)

[5.1	Software Configuration Management	](#_toc145263639)

[5.1.1	Software Development Environment Configuration	](#_toc145263640)

[5.1.2	Source Code Management	](#_toc145263641)

[5.1.3	Source Code Style Guide & Convention	](#_toc145263642)

[5.1.4	Software Deployment Configuration	](#_toc145263643)

[5.2	Landing Page, Services & Applications Implementation](#_toc145263644)

[5.2.1	Sprint 1	](#_toc145263645)

### [6	Conclusiones](#_toc145263646)

### [7	Anexos	](#_toc145263647)

### [8	Bibliografia	](#_toc145263648)




# <a name="_toc145263583"></a>**REGISTRO DE VERSIONES DEL INFORME** 


| Versión |   Fecha    |     Autor     | Descripción de modificación                                          |
|:-------:|:----------:|:-------------:|:---------------------------------------------------------------------|
|  1.1.1  | 19/08/2023 | Leydi  Mamani | Descripción de la problemática usando 5W y 2H                        |
|  1.1.2  | 19/08/2023 | Leydi  Mamani | Presentación y análisis de competidores                              |
|  1.1.3  | 19/08/2023 | Jhan Antonio  | Desarrollo del Canvas y diseño de entrevistas                        |
|  1.1.4  | 05/09/2023 |  Edwin Lopez  | Desarrollo del empathy mapping, user mapping y user goal mapping.    |
|  1.1.5  | 05/09/2023 |  Angie Ruiz   | Análisis de entrevistas                                              |
|  1.1.6  | 08/09/2023 |  Edwin Lopez  | Diseño de wireframes y mocks-ups                                     |
|  1.1.7  | 08/09/2023 | Julio Asillo  | Diseño completo de landing page                                      |
|  1.1.8  | 09/09/2023 |  Edwin Lopez  | Diseño completo de la base y explicación de las entidades            |
|  1.1.9  | 09/09/2023 | Jhan Antonio  | Diseño completo del diagrama de clase y explicación de sus atributos |
| 1.1.10  | 09/09/2023 |  Angie Ruiz   | Documentación completa del sprint 1                                  |
| 1.1.11  | 09/09/2023 | Julio Asillo  | Documentación del sprint 2                                           |
|  2.1.1  | 20/09/2023 | Leydi Mamani  | Elaboración del sprint planning y spring backlog 2                   |
|  2.1.2  | 20/09/2023 |  Angie Ruiz   | Desarrollo del formulario para publicar y guardar propiedades        |
|  2.1.3  | 21/09/2023 | Jhan Antonio  | Documentación del sprint 2                                           |
|  2.1.4  | 21/09/2023 |  Edwin Lopez  | Documentación del frontend para mensajería                           |
|  2.1.4  | 21/09/2023 | Julio Asillo  | Documentación de todos los logros obtenidos en el sprint 2           |

<br><br>



# <a name="_toc145263584"></a>**STUDENT OUTCOMES**
ABET – EAC - Student Outcome 3 

Criterio: Capacidad de comunicarse efectivamente con un rango de audiencias. En el siguiente cuadro se describen las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.


|Criterio Específico|Acciones Realizadas|Conclusiones|
| :- | :- | :- |
|Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software.|<p>Asillo Mendoza, Julio Ernesto – TB1</p><p>Para esta TB1 participé de manera activa y usé la plataforma de Discord y Github para administrar los avances.</p><p>Mamani Aro, Leydi Yaquelin - TB1</p><p>Como parte del equipo participé en cada una de las reuniones tanto virtuales (discord) y presenciales. Además, colaboré y me comuniqué constantemente con mi equipo para poder realizar la entrega del proyecto.</p><p>López Huaman Edwin Abdías – TB1</p><p>Para esta entrega realice todos los diagramas relacionados con el usuario y análisis de competidores.</p><p>Jhan Clinton – TB1</p><p>Durante el desarrollo de esta entrega realicé Sprint planning & backlog, class Diagram, DDD Software Architecture.</p><p>Ruiz Carhuamaca, Angie – TB1</p><p>En esta primera entrega participé en cada reunión programada y estuve en constante comunicación con mi equipo para el desarrollo de los capítulos.</p>|<p>TB1</p><p>Como equipo hemos trabajado de manera conjunta y colaborativa, realizando entregas en el tiempo estipulado de acuerdo con lo coordinado en cada reunión.</p><p></p><p>Para poder hacer un buen trabajo en equipo es importante tener una buena comunicación ya que así se pueden coordinar como hacer los trabajos de manera conjunta y eficiente</p><p>También es importante la responsabilidad de cada miembro del equipo porque se debe cumplir los trabajos asignados en los plazos acordados</p><p></p>|
|Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software.|<p>Asillo Mendoza, Julio Ernesto – TB1</p><p>Para esta entrega utilicé HTML y CSS para la creación de la landing page, incluyendo sitios web para el diseño de diagramas.</p><p>Mamani Aro, Leydi Yaquelin - TB1</p><p>Para este primer entregable realicé el cuadro de Lean UX Canvas, así como también efectué el registro de una entrevista y aporté en colaboración con mi equipo para realizar el sprint 1.</p><p>López Huaman Edwin Abdías – TB1</p><p>Para el desarrollo de esta entrega participé activamente en las reuniones de trabajo y el desarrollo de cada uno de los wireframes y diseño de landing page.</p><p>Antonio Salazar, Jhan Clinton– TB1</p><p>Realicé las user Stories, As-Is Scenario, Antecedentes, Problemática y Diseño de entrevistas.</p><p>Ruiz Carhuamaca, Angie – TB1</p><p>Para el desarrollo de esta entrega utilicé diferentes sitios web para realizar los wireframes y MockUps de la Landing Page, Web Applications y sus respectivos diagramas, participé en la realización de los Problem Statements y Product Backlog.</p>|Planear y conocer bien la estructura del software a desarrollar hace que su implementación sea más fácil.|



# ![](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.015.png)
**CAPÍTULO I: INTRODUCCIÓN**


## <a name="_toc131683579"></a><a name="_toc145263586"></a>Startup Profile
### 1.1.1. Description de la StartUp

Nos encargamos de servir como nexo entre personas interesadas en rentar inmuebles y los interesados en alquilar dichas propiedades. Nuestros objetivos son facilitar el proceso de búsqueda, sistematizar el registro y seguimiento de las cláusulas del contrato. Además de proporcionar un informe general sobre los registros y comentarios de los usuarios.


<div align=center>
    <img src="https://i.ibb.co/6tsYXtg/My-project-3.png" alt="logo" style="margin-bottom: 5px;" width="500"/>
</div>

- **Nombre:** RentState
- **Rubro:** Desarrollo de software
- **Visión:** Convertirnos en el principal medio de renta de inmuebles a nivel nacional.
- **Misión:** Mejorar el proceso de arrendamiento mediante un sistema completo e intuitivo que ayude tanto a arrendadores como a arrendatarios.


1. ### <a name="_toc131683581"></a><a name="_toc145263588"></a>Perfiles de integrantes del equipo
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tr align="center">
        <td rowspan="3">
            <img src="https://i.ibb.co/Q9HYJT6/angie.png" alt="Angie" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Ruiz Carhuamaca, Angie Nayeli
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy Angie Nayeli Ruiz Carhuamaca y estudio la carrera de Ingeniería de Software en la UPC, que se enfoca en la creación de programas informáticos confiables y de calidad. Me considero una persona creativa, responsable y organizada. Al realizar algún trabajo grupal, me gusta escuchar ideas de mis compañeros y buscar métodos que nos ayuden a realizar correctamente el proyecto.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://i.ibb.co/vqgrN5N/Julio.png" alt="Julio" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Asillo Mendoza, Julio Ernesto
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy Julio Asillo, tengo 19 años y estoy cursando el sexto ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Soy una persona responsable, activa y comprometida. Al pasar los años en la Universidad he tenido la oportunidad de formar parte de varios equipos, entonces tengo experiencia en trabajos grupales. Presentó los conocimientos de programar en C++, HTML, CSS, Python, etc.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://i.ibb.co/bd39JFb/leydi.png" alt="Leydi" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Mamani Aro, Leydi Yaquelin
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
         Soy Leydi Yaquelin Mamani Aro, estudio la carrera de Ingeniería de Software porque tuve la oportunidad de aprender temas sobre computación y sistemas, donde adquirí conocimientos e intereses relacionados con la informática, programación y diseño gráfico. Por otro lado, desde que comencé el primer ciclo en la universidad he tenido que elaborar trabajos grupales, por esa razón he fortalecido mi habilidad para trabajar en equipo y poder resolver problemas asertivamente. Me comprometo a ser responsable con cada entregable del curso, esperando que el startup cumpla con los objetivos propuestos.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://i.ibb.co/Cn1rQNP/edwin.png" alt="Edwin"  style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            LOpez Huaman, Edwin Abdias
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy Edwin Abdias Lopez Huaman. Estudiante de la carrera Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Me gusta programar, practicar deportes como la natación, ciclismo, calistenia y también jugar fútbol con mis amigos. Además, otro de mis pasatiempos es jugar.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://i.ibb.co/Hx4CWMX/jhan.png" alt="Jhan"  style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Antonio Salazar, Jhan Clinton
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
         Actualmente, soy estudiante de ingeniería de software. Me apasiona la tecnología y el desarrollo de soluciones innovadoras para mejorar la vida de las personas. Estoy emocionado de seguir aprendiendo y creciendo en este campo emocionante y en constante evolución.
        </td>
    </tr>
</table>

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

5 ‘W’ s + 2 ‘H’ s

- What? - ¿Qué?

¿Cuál es el problema?

Dificultad para encontrar inmuebles en renta, no ver información verídica y actualizada del espacio en alquiler para su uso y el consumo de tiempo para poder encontrarlo. 

- When? - ¿Cuándo?

¿Cuándo sucede el problema?

Cuando las personas quieren encontrar un inmueble en una zona aledaña a un lugar de trabajo o estudio. Asimismo, cuando los propietarios no cuentan con un sistema que los ayude a administrar y difundir sus inmuebles disponibles. 

- Where? - ¿Dónde?

¿Dónde está la persona cuando sucede el problema?

Si la persona tiene un manejo de las tecnologías se encuentra en la comodidad de su casa buscando inmuebles por redes sociales o internet. Si es una persona que no maneja estos recursos está buscando estos inmuebles de forma presencial.

¿A dónde se dirige?

Se dirige a los lugares que rentan inmuebles para ver si se adaptan a sus necesidades.

¿Dónde surge el problema?

El problema surge al momento de no haber encontrado un espacio para rentar y demandar demasiado tiempo el poder encontrarlo.

- Why? - ¿Por qué?

¿Cuál es la causa del problema?

No contar con una aplicación o portal que ayude a encontrar estos espacios para la renta y que a la vez esté con información actualizada y verificada por otras personas.

- Who? - ¿Quién?

¿Quiénes están involucrados?

Personas entre los 18 y 30 años que buscan alquilar un inmueble y tienen problemas para encontrarlo.

Personas entre los 25 a 65 años que poseen una propiedad inmueble, no consiguen alquilarla con facilidad y tienen problemas para administrar sus rentas.

- How? - ¿Cómo?

¿Cómo se presenta el problema?

Se presenta mediante el tiempo que las personas invierten en la búsqueda de un inmueble para rentar ideal, muchas veces con poco o ningún éxito.

- How much? - ¿Cuánto?

¿Qué tan severo es el problema?

Según el INEI, para el año 2021, el total de hogares que viven en un inmueble alquilado en Perú es 26,7% y para la región Lima, es de 35,8%. Esto significa que más de ¼ de los hogares peruanos tienen que vivir en una búsqueda continua de una vivienda.


1. ### <a name="_toc131683584"></a><a name="_toc145263591"></a>Lean UX Process
#### Lean UX Problem Statements
Hemos notado que las personas entre los 18 a 25 años que deseen arrendar un inmueble buscan medios digitales que los ayuden a encontrar el inmueble adecuado acorde a sus necesidades. Un factor crítico que dificulta este proceso es la información desactualizada y no verificada que se encuentra registrado de estos inmuebles en redes sociales o internet.

¿Cómo otorgar una búsqueda eficiente sobre inmuebles con información verídica para que las personas logren encontrar el inmueble acorde a sus necesidades?

Una gran cantidad de personas consideran el proceso de búsqueda de inmuebles una actividad estresante y hasta cierto punto frustrante. La selección de un inmueble adecuado acorde a las necesidades puede resultar en una mala experiencia al no poder encontrar rápidamente el inmueble. Un factor crítico es la dificultad de conseguir lo que se desea en la primera oportunidad, ya que depende del presupuesto, lugar y cláusulas que se debe de considerar para recién arrendar un inmueble.

¿Cómo automatizar el proceso de búsqueda y elección de inmuebles según las necesidades del usuario?

Hemos notado que las personas de 25 a 65 años que, arriendan inmuebles buscan formas efectivas para difundir y tener una mejor administración de sus propiedades que están siendo arrendadas, para no desperdiciar demasiado tiempo en dichos procesos. Los factores críticos que afectan en la obtención de resultados es la desorganización de contenido, no actualizar constantemente información, correcto registro, interacción con medios digitales y no manejar una plataforma que pueda satisfacer dichas necesidades.

¿Cómo podemos construir una plataforma que permita al usuario ahorrar tiempo en difusión y administración de su negocio de inmueble para poder satisfacer sus necesidades?


1. #### Lean UX Assumptions
Assumptions Worksheet

- ¿Quién es el usuario?

*Tenemos dos tipos de usuario: los arrendatarios y los arrendadores.*

- ¿Dónde encaja nuestro producto en su trabajo o vida?

*Nuestro producto servirá para poder encontrar de manera rápida, confiable y segura un inmueble (habitación, departamento, local comercial)*

- ¿Qué problemas resuelve nuestro producto?

*El producto resuelve el problema de encontrar un inmueble idóneo que cumple con las necesidades de nuestro segmento arrendatario.*

- ¿Cuándo y cómo es usado nuestro producto?

*Cuando deseen alquilar un inmueble de manera online.*

- ¿Qué características son importantes?

*Para el segmento arrendatarios, filtros de búsqueda adecuados como la cercanía a su lugar de trabajo, rango de precios, categoría, etc.*

- *Para el segmento de arrendadores, gestión organizada de los inmuebles, publicación de inmuebles, etc.*
- ¿Cómo debe verse nuestro producto y cómo comportarse?

*Nuestro producto deberá evocar en el cliente emociones como la confianza en que podrá encontrar un inmueble adecuado.*

*Se deberá de ver minimalista y simple de usar.*

Business Assumptions

- Creemos que nuestros clientes necesitan una manera de poder rentar y encontrar un inmueble de manera segura y confiable.
- Estas necesidades se pueden resolver con la creación de un sistema completo y correctamente organizado de alquiler de habitaciones, casas y departamentos.
- Nuestros clientes iniciales serán jóvenes entre los 18 y 30 años que busquen rentar un inmueble y que presenten problemas al hacerlo. Así como también personas entre los 18 y 65 años que sean propietarios de un inmueble y desean alquilarlo.
- El valor #1 que nuestros clientes obtendrán será información correctamente actualizada y verificada por todos nuestros usuarios.
- El cliente también tendrá como beneficios adicionales acceso a un mapa que le indique la correcta ubicación del inmueble, un filtro de búsqueda personalizado a las necesidades del usuario.
- Obtendremos la mayoría de nuestros clientes mediante publicidad por redes sociales.
- Haremos dinero a través de nuestro plan premium para arrendadores y arrendatarios incluirá mejor acceso a las funcionalidades de la aplicación web.
- Nuestra competencia principal en el mercado serán empresas de rubro similar al nuestro como Airbnb, AdondeVivir, Urbania, etc.
- Los venceremos debido a que tendremos mejor organización, filtros de búsqueda y una interfaz más amigable al usuario.
- Nuestro mayor riesgo es no lograr captar el interés de nuestros potenciales clientes.
- Lo resolveremos diferenciándonos de nuestros competidores al añadir funcionalidades como filtro de búsqueda, secciones de búsqueda por categorías. 
- ¿Qué otras suposiciones tenemos? ¿Eso, si se prueba que es falso, causará que nuestro negocio / proyecto no funcione?  Los clientes potenciales se encuentran actualmente insatisfechos con las aplicaciones web de alquiler de inmuebles existentes en el mercado. Las inmobiliarias estarían dispuestas a formar contratos con nuestro startup. Se deberá de ver minimalista y simple de usar.


1. #### Lean UX Hypothesis Statements
- "Creemos que encontrar de manera rápida y fácil un inmueble para arrendar se logrará si nuestros usuarios arrendatarios obtienen un inmueble que se adapte a sus necesidades con una aplicación que pondrá en contacto a personas que buscan un inmueble para alquilar y a propietarios que deseen arrendar."
- "Creemos que ofrecer facilidad de poder acceder a la información, registros y progreso del negocio se lograrán si nuestros usuarios arrendadores obtienen una organización administrativa de los inmuebles arrendados con la funcionalidad de gestión administrativa de la aplicación web"
- ” Creemos que asegurar que la estancia en el inmueble tendrá un buen ambiente que cumpla expectativas se logrará si nuestros usuarios arrendatarios obtienen una buena experiencia del inmueble elegido con la posibilidad de agendar citas para visitar el inmueble. 
- ” Creemos que brindar la posibilidad de recibir pagos en el plazo acordado en el contrato se logrará si nuestros usuarios arrendadores obtienen a tiempo el pago mensual del inmueble con la funcionalidad de la aplicación de poder notificar a los arrendatarios sobre sus pagos mensuales por el inmueble."
- "Creemos que la mayoría de las personas que quieren arrendar un cuarto presentan la dificultad al momento de buscar información en páginas o redes sociales se encuentran con mucha información variada, desactualizada, falsa, no verificada, etc. Sabremos que estamos teniendo éxito cuando la cantidad de usuarios arrendadores y arrendatarios aumente de manera acelerada y rápida."
- "Creemos que los usuarios necesitan una aplicación intuitiva y fácil de usar para la búsqueda de un inmueble. Sabremos que estamos teniendo éxito cuando las reseñas sobre nuestra aplicación sean positivas."


1. #### Lean UX Canvas

<div align=center>
    <img src="https://i.ibb.co/3v8q06n/c01.png" alt="Canvas"/>
</div>
<div align=center>
    <img src="https://i.ibb.co/mChxT4G/c02.png" alt="Canvas"/>
</div>


1. ## <a name="_toc131683585"></a><a name="_toc145263592"></a>Segmentos Objetivo
Nuestra aplicación está dirigida a dos segmentos objetivos los cuales son:

- Arrendatarios: son aquellos usuarios comprendidos entre 18 y 40 años que han rentado un inmueble ya sea para vivir o algún negocio.

- Arrendadores: son aquellas personas comprendidas entre los 18 y 60 años que tienen inmuebles a la renta.




# ![](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.021.png)
**CAPÍTULO II: REQUIREMENTS ELICITATION & ANALYSIS**

1. ## <a name="_toc131679438"></a><a name="_toc131679529"></a><a name="_toc131682225"></a><a name="_toc131683587"></a><a name="_toc131683588"></a><a name="_toc145263594"></a>Competidores
![](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.022.png)

**Airbnb:**
Es una plataforma en línea que conecta a personas que buscan alojamiento con personas que tienen habitaciones, apartamentos, casas u otros tipos de alojamiento disponibles para alquilar. Los usuarios pueden buscar alojamiento en cualquier parte del mundo y reservar directamente a través del sitio web o de la aplicación móvil de Airbnb. Los anfitriones pueden publicar sus alojamientos en la plataforma de Airbnb, establecer un precio por noche y gestionar las reservas y pagos de los huéspedes. Airbnb también ofrece a los anfitriones herramientas para crear anuncios atractivos, establecer reglas de la casa y administrar las comunicaciones con los huéspedes. Además de alojamiento, Airbnb también ofrece experiencias únicas y actividades en los destinos a los que viajan los usuarios. Los usuarios pueden reservar una amplia variedad de experiencias, desde tours culinarios hasta clases de surf y talleres de artesanía.



![Logotipo, nombre de la empresa

Descripción generada automáticamente](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.023.png)**HomeAway:**
Es una plataforma en línea de alojamiento vacacional que conecta a propietarios de viviendas con personas que buscan alquilar una propiedad para vacaciones o estadías a corto plazo. También, ofrece una amplia variedad de opciones de alojamiento en todo el mundo, que incluyen apartamentos, casas, villas, cabañas y más. Los usuarios pueden buscar alojamiento en el sitio web de HomeAway y reservar directamente con los propietarios a través de la plataforma. HomeAway también ofrece a los propietarios herramientas para administrar sus propiedades, incluyendo la posibilidad de crear anuncios detallados con fotos y descripciones, establecer precios y reglas de la casa, y gestionar las reservas y pagos de los huéspedes. Además, HomeAway es propiedad de Expedia Group, lo que significa que los usuarios pueden acceder a ofertas especiales y descuentos en paquetes de vuelos y alojamiento a través de su sitio web.

![](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.024.png)
**GOPLACEIT:**
Es una aplicación inmobiliaria en línea que ayuda a los usuarios a encontrar propiedades en venta o en alquiler en toda América Latina. GoPlaceIt utiliza tecnología avanzada de aprendizaje automático para ofrecer a los usuarios una experiencia personalizada y relevante de búsqueda de propiedades. La plataforma utiliza algoritmos para analizar las preferencias y el comportamiento de búsqueda de los usuarios, lo que permite ofrecer recomendaciones precisas de propiedades que se ajusten a sus necesidades y gustos. Los usuarios pueden buscar propiedades en GoPlaceIt utilizando una variedad de filtros, como ubicación, precio, tamaño, tipo de propiedad y más. También pueden guardar búsquedas y recibir alertas en tiempo real cuando se publiquen nuevas propiedades que se ajusten a sus criterios.
1. ### <a name="_toc131683589"></a><a name="_toc145263595"></a>Análisis Competitivo


<table><tr><th colspan="6" valign="top">Competitive Analysis Landscape</th></tr>
<tr><td colspan="1" rowspan="2" valign="top">¿Por qué llevar a cabo este análisis? </td><td colspan="5" valign="top">¿Cómo identificar a nuestros principales competidores?</td></tr>
<tr><td colspan="5" valign="top">Con este análisis usando el FODA, es decir, las fortalezas, oportunidades, debilidades y amenazas de nuestros competidores. Asimismo, se evalúa su participación en el mercado y qué estrategias se pueden desarrollar para que nuestra aplicación surja en el mercado laboral. Pero ¿Cómo identificamos a nuestros principales competidores?, Debemos estudiar el mercado e identificar las aplicaciones más usadas por los compradores en el extranjero. Así se concluyó que los principales competidores son:</td></tr>
<tr><td colspan="2" valign="top">Nombre y logo</td><td colspan="1" valign="top">RentState</td><td colspan="1" valign="top">Airbnb</td><td colspan="1" valign="top">HomeAway</td><td colspan="1" valign="top">Goplaceit</td></tr>
<tr><td colspan="1" rowspan="2" valign="top">PERFIL</td><td colspan="1" valign="top">Overview</td><td colspan="1" valign="top">Con esta aplicación se puede encontrar inmuebles para alquilar cercanos a una ubicación. Además, los propietarios de inmuebles pueden publicar sus propiedades en renta.</td><td colspan="1" valign="top">Con esta aplicación puedes obtener información sobre cómo encontrar un alojamiento y pagar por una reservación. Cuenta con un equipo de asistencia a su comunidad las 24 horas, los 7 días de la semana en 11 idiomas distintos.</td><td colspan="1" valign="top">Esta aplicación se declara como la "mayor selección de alquileres vacacionales del mundo" ofrece espacios más íntimos que un hotel con un mejor servicio y aún menor precio.</td><td colspan="1" valign="top">Es una aplicación inmobiliaria en línea que utiliza tecnología avanzada de aprendizaje automático para ofrecer a los usuarios una experiencia personalizada y relevante de búsqueda de propiedades en América Latina, herramientas para propietarios y agentes inmobiliarios y filtros precisos de búsqueda para ayudar a los usuarios a encontrar la propiedad perfecta.</td></tr>
<tr><td colspan="1" valign="top"><p>Ventaja competitiva </p><p>¿Qué valor ofrece a los clientes?</p></td><td colspan="1" valign="top">La mayor ventaja competitiva es ofrecer filtros personalizados en la búsqueda de inmuebles. Además, brinda la opción de mensajería entre arrendador y arrendatario. Por otro lado, el propietario de inmuebles puede publicar y personalizar sus posts de alquiler.</td><td colspan="1" valign="top">La mayor ventaja competitiva de Airbnb es su modelo de negocio de compartir alojamiento entre particulares, que ofrece una amplia variedad de opciones de alojamiento en todo el mundo, a menudo a precios más asequibles que los hoteles tradicionales. Los usuarios pueden encontrar alojamiento en lugares donde no hay hoteles disponibles o donde los precios de los hoteles son muy altos.</td><td colspan="1" valign="top"><p>La mayor ventaja competitiva de HomeAway es su enfoque en propiedades de alquiler de vacaciones de larga duración, de alta gama y en zonas rurales o alejadas de las grandes ciudades, lo que lo convierte en una opción atractiva para aquellos que buscan un lugar tranquilo y relajado para vacacionar. </p><p>Su alianza con Expedia Group, lo que significa que los usuarios pueden acceder a ofertas especiales y descuentos en paquetes de vuelos y alojamiento a través de su sitio web.</p></td><td colspan="1" valign="top">La mayor ventaja competitiva de GoPlaceIt es su enfoque en la personalización y la innovación tecnológica. GoPlaceIt utiliza algoritmos de aprendizaje automático para analizar las preferencias de búsqueda de los usuarios y ofrecer recomendaciones precisas de propiedades que se ajusten a sus necesidades y gustos.</td></tr>
<tr><td colspan="1" rowspan="2" valign="top">Perfil de marketing</td><td colspan="1" valign="top">Mercado objetivo</td><td colspan="1" valign="top"><p>Personas entre 18 y 40 años que buscan alquilar inmuebles.</p><p>Personas entre 18 y 60 años propietarios de inmuebles y desean dar en alquiler su propiedad.</p></td><td colspan="1" valign="top">Son los viajeros que buscan opciones de alojamiento únicas y auténticas en todo el mundo, a precios asequibles y con flexibilidad en cuanto a horarios y comodidades.</td><td colspan="1" valign="top">Son los viajeros que buscan opciones de alojamiento vacacional personalizadas en destinos turísticos populares y remotos, así como propietarios de propiedades vacacionales que buscan alquilar y gestionar sus propiedades de manera eficiente. </td><td colspan="1" valign="top">Son los usuarios que buscan propiedades en América Latina ya sea para comprar o alquilar.</td></tr>
<tr><td colspan="1" valign="top"><p>Estrategias de marketing</p><p></p></td><td colspan="1" valign="top">Publicidad en línea y campañas en redes sociales.</td><td colspan="1" valign="top">Airbnb utiliza varias tácticas de marketing, como publicidad en línea, relaciones públicas y marketing de contenidos, y se enfoca en la segmentación y personalización para ofrecer experiencias únicas a sus usuarios. La empresa también invierte en patrocinios y colaboraciones para mejorar la calidad y la variedad de las opciones de alojamiento en su plataforma.</td><td colspan="1" valign="top">Se enfoca en llegar a viajeros y propietarios de propiedades vacacionales a través de campañas publicitarias en línea y fuera de línea, promociones exclusivas y una red de socios de distribución. La plataforma utiliza varias tácticas de marketing digital y también invierte en publicidad fuera de línea para aumentar la conciencia de su marca y atraer a nuevos clientes potenciales. HomeAway también ofrece promociones y descuentos exclusivos para fomentar las reservas y la fidelidad de los clientes.</td><td colspan="1" valign="top">Utiliza una variedad de canales de marketing, como publicidad en línea y redes sociales, para llegar a nuevos usuarios. Además, ofrece contenido educativo y de entretenimiento para fomentar la interacción con la marca.</td></tr>
<tr><td colspan="1" valign="top">Perfil del producto</td><td colspan="1" valign="top">Productos & Servicios</td><td colspan="1" valign="top">Ofrece una búsqueda personalizada y brinda soporte para los usuarios. Para los propietarios, se les brinda las facilidades para ofrecer sus inmuebles.</td><td colspan="1" valign="top">La plataforma se enfoca en la personalización y la segmentación, utilizando datos de sus usuarios para ofrecer experiencias de viaje únicas y adaptadas a sus necesidades y preferencias.</td><td colspan="1" valign="top">Ofrece un programa de afiliados y una red de socios de distribución, como agencias de viajes en línea y compañías aéreas. También, ofrece promociones y descuentos exclusivos para fomentar las reservas y la fidelidad.</td><td colspan="1" valign="top">Ofrece una experiencia personalizada y centrada en el cliente, utilizando datos de usuarios para dar resultados de búsqueda relevantes y recomendaciones personalizadas.</td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Precios y Costos</td><td colspan="1" valign="top"><p>Costos: Inversión en publicidad y guardar los datos en service público.</p><p>Precios: suscripción para los propietarios</p></td><td colspan="1" valign="top"><p>Costos: Inversión en plataformas digitales</p><p>Precios: gratuito</p></td><td colspan="1" valign="top"><p>Costos: Inversión en plataformas digitales</p><p>Precios: gratuito</p></td><td colspan="1" valign="top"><p>Costos: Inversión en plataformas digitales</p><p>Precios: gratuito</p></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top">Canales de distribución (Web y/o Móvil)</td><td colspan="1" valign="top">Móvil</td><td colspan="1" valign="top">` `Web y Móvil</td><td colspan="1" valign="top">Web</td><td colspan="1" valign="top">Web</td></tr>
<tr><td colspan="1" rowspan="4" valign="top">Análisis FODA</td><td colspan="1" valign="top">Fortalezas</td><td colspan="1" valign="top"><p>Aplicación fácil de usar</p><p>Variedad de inmuebles</p><p>Posibilidad de contactar al propietario</p><p></p></td><td colspan="1" valign="top"><p>Gran cantidad de listados de alojamiento en todo el mundo</p><p>Plataforma fácil de usar y disponible en múltiples idiomas</p><p>Amplia variedad de opciones de alojamiento, desde económicas hasta lujosas</p><p>Fuerte presencia de marca y lealtad del cliente</p></td><td colspan="1" valign="top"><p>Gran cantidad de listados de alojamiento en todo el mundo</p><p>Ofrece una amplia variedad de opciones de alojamiento, desde económicas hasta lujosas</p><p>Plataforma fácil de usar y disponible en múltiples idiomas</p></td><td colspan="1" valign="top"><p>Plataforma fácil de usar y disponible en múltiples idiomas</p><p>Ofrece una amplia variedad de opciones de propiedad en venta y alquiler</p><p>Fuerte presencia en línea y reputación positiva</p><p></p></td></tr>
<tr><td colspan="1" valign="top">Oportunidades</td><td colspan="1" valign="top">Posibilidad de dar diferentes servicios a través de la aplicación</td><td colspan="1" valign="top"><p>Posibilidad de expandirse a nuevos segmentos de mercado, como alojamiento de negocios</p><p>Posibilidad de diversificar los servicios ofrecidos para generar ingresos adicionales</p></td><td colspan="1" valign="top"><p>Potencial de crecimiento en nuevos mercados geográficos</p><p>Cambios en el comportamiento del consumidor y la adopción de nuevas tecnologías</p><p>Posibilidad de diversificar los servicios ofrecidos para generar ingresos adicionales</p></td><td colspan="1" valign="top"><p>Potencial de crecimiento en nuevos mercados geográficos.</p><p>Posibilidad de expandirse a nuevos segmentos de mercado, como propiedades comerciales</p><p></p></td></tr>
<tr><td colspan="1" valign="top">Debilidades</td><td colspan="1" valign="top">Dependencia de terceros en el caso de los productos a ofrecer</td><td colspan="1" valign="top"><p>Dependencia de terceros para la calidad y seguridad de los alojamientos</p><p>Riesgo de mala experiencia del cliente con el alojamiento o el anfitrión</p><p></p></td><td colspan="1" valign="top"><p>Regulaciones y restricciones gubernamentales en algunos mercados</p><p>Dependencia de terceros para la calidad y seguridad de los alojamientos</p><p>Competencia cada vez más fuerte de otros servicios de alojamiento en línea</p></td><td colspan="1" valign="top"><p>Dependencia de terceros para la calidad y la exactitud de la información de propiedad.</p><p>Riesgo de mala experiencia del cliente con la propiedad o el agente</p><p>Dificultades para monetizar o generar ingresos</p></td></tr>
<tr><td colspan="1" valign="top">Amenazas</td><td colspan="1" valign="top"><p>Riesgo de ciberataques por no tener un cuidado de los datos personales de los usuarios.</p><p></p></td><td colspan="1" valign="top"><p>Riesgo de eventos globales, como pandemias, que pueden afectar significativamente a la industria de viajes y alojamiento</p><p>Riesgo de ciberataques o violaciones de datos que pueden comprometer la información personal de los usuarios</p></td><td colspan="1" valign="top"><p>Cambios en las preferencias y expectativas del consumidor</p><p>Riesgo de eventos globales, como pandemias, que pueden afectar significativamente a la industria de viajes y alojamiento</p><p>Riesgo de ciberataques o violaciones de datos que pueden comprometer la información personal de los usuarios</p></td><td colspan="1" valign="top"><p>Riesgo de eventos globales, como pandemias, que pueden afectar significativamente a la industria de viajes</p><p></p><p>Posibilidad de que los competidores lancen productos similares o mejores</p><p>Riesgo de ciberataques o violaciones de datos que pueden comprometer la información personal de los usuarios</p></td></tr>
</table>




1. ### <a name="_toc131683590"></a><a name="_toc145263596"></a>Estrategias y tácticas frente a competidores
- Nos enfocaremos en nicho y lugar específico para tratar de dar un excelente servicio y ser la principal aplicación de alojamiento en dicha área específica
- Se introducirán nuevas características que nos distingan de nuestros competidores y atraer nuevos usuarios.
- Brindaremos un excelente servicio al cliente y una experiencia de usuario excepcional, brindando orientación al momento de buscar alojamiento o publicar un aviso.
  1. ## <a name="_toc131683591"></a><a name="_toc145263597"></a>Entrevistas
     1. ### <a name="_toc131683592"></a><a name="_toc145263598"></a>Diseño de entrevistas
Preguntas para arrendatarios

- ¿Cuál es su nombre y edad?
- ¿En qué trabaja?
- ¿Qué monto paga por el alquiler de su inmueble? ¿Fue fácil encontrar un lugar que se ajuste a su presupuesto?
- ¿Considera que es una cantidad justa?
- ¿Qué métodos utiliza para buscar un inmueble?
- ¿Qué dificultades presenta al momento de buscar un inmueble o cuarto?
- ¿Qué factores toma en cuenta en su búsqueda? ¿Encuentra siempre lo que necesita? Ejemplo: cercanía a su lugar de trabajo
- ¿Cómo se asegura de que el lugar cumpla con sus expectativas?
- ¿Cuánto tiempo se demora en encontrar un inmueble?
- ¿Ha realizado alguna visita previa antes de alquilarlo?
- ¿Le habría gustado tener referencias de la zona o del propietario?
- ¿Ha tenido problemas con su contrato de arrendamiento? ¿Cuáles?



Preguntas para arrendadores/propietarios

- ¿Cuál es su nombre y edad?
- ¿En qué trabaja?
- ¿Qué métodos utiliza para registrar la información de sus clientes?
- ¿Cuánto le preocupa la personalidad del arrendador al que alquila?
- ¿Qué método usa para cobrar alquiler?
- ¿Qué medios utiliza para publicar un anuncio de renta?
- ¿Cuánto tiempo se demora en lograr alquilar su inmueble?
- ¿Ha presentado algún problema relacionado con los pagos del alquiler? ¿Cuál?
- ¿Suelen respetar sus inquilinos las cláusulas del contrato de arrendamiento?
- ¿Han sufrido sus propiedades algún tipo de daño durante el periodo en el que estuvieron en alquiler? ¿Qué tipo y qué hizo?
- ¿Ha tenido algún conflicto con un inquilino? Especifiqué.
- ¿Le gustaría encontrar una plataforma que le ayude a difundir y administrar su negocio o le ayude a registrar sus inquilinos?


1. ### <a name="_toc131683593"></a><a name="_toc145263599"></a>Registro de entrevistas
Entrevista N°01:

Segmento: Propietario de inmueble

Entrevistador: Leydi Mamani

Entrevistado: Maribel Chauca

Edad: 36

Timing: La entrevista inicia a los 3:48 segundos del video

Duración de la entrevista: 5:40 minutos aproximadamente

Link de la entrevista: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201b051_upc_edu_pe/EVk7Ef36WiZIrx6zkyhtKQwBlZfdFR9IV0TMJHT2ygbzsA?e=4sghBZ>

Captura:

![Interfaz de usuario gráfica, Aplicación

Descripción generada automáticamente](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.025.png)

Resumen de la entrevista: La señora Maribel (36) nos cuenta que el método que utiliza para registrar información sobre sus clientes es una agenda, además de tener los papeles de cada contrato de donde se guía para poder cobrar los pagos de cada mes. Ella nos comenta que alquila a diferentes tipos de arrendatarios como estudiantes o personas solas. El método que ella utiliza para cobrar los pagos mensuales es acercarse personalmente cada cierto día del mes. Por otro lado, nos explica que ella para poder dar publicidad coloca un anuncio fuera de su inmueble o también las redes sociales, y que normalmente demora en conseguir arrendar el inmueble en un tiempo de semanas o días. Por último, nos comenta que le gustaría poder encontrar una aplicación que le ayude y le facilite administrar su negocio.

Entrevista N°02:

Segmento: Propietario de inmueble

Entrevistador: Flavia Vela

Entrevistado: Patricia Velarde

Edad: 50 años

Timing: La entrevista inicia a los 5 segundos del video

Duración: 9 minutos aproximadamente

Link de la entrevista: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201b051_upc_edu_pe/EVk7Ef36WiZIrx6zkyhtKQwBlZfdFR9IV0TMJHT2ygbzsA?e=4sghBZ>

![Pantalla de celular con imagen de hombre

Descripción generada automáticamente con confianza media](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.026.png)

Resumen de la entrevista: La señora Velarde comenta que su método de registro de información de sus inquilinos es un documento de Excel. Nos menciona que las principales características que busca en sus inquilinos es que no sean conflictivos, estén mentalmente estables, que no tengan antecedentes de violencia familiar y que, sobre todo, no molesten a los demás vecinos del edificio en el que alquila. Además, el método que usa para cobrar su renta es depósito a su cuenta bancaria. Comentó que para alquilar sus inmuebles usó la compañía RE/MAX y se demoró una semana.

Entrevista N°03:

Segmento: Arrendatario

Entrevistador: Angie Ruiz

Entrevistado: Abraham Castillo Vega 

Edad: 20 años

Timing: La entrevista inicia al minuto 14:19

Duración: 9:00 minutos aproximadamente

Link de la entrevista: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201b051_upc_edu_pe/EVk7Ef36WiZIrx6zkyhtKQwBlZfdFR9IV0TMJHT2ygbzsA?e=4sghBZ>

Captura:

![La cara de un hombre con lentes

Descripción generada automáticamente con confianza media](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.027.png)Resumen de la entrevista: El joven Abraham Vega comenta que no es fácil encontrar un inmueble que se adecue a las necesidades y resulta ser más problemático si tiene factores definidos para escoger, como el lugar. Además, considera que buscar por internet resulta ser no tan beneficioso, puesto que, encuentra anuncios publicados con información desactualizada, donde no aparece el tiempo de publicación y si aún sigue disponible. Por otro lado, considera que contar con referencias de la zona y del propietario le ayudaría bastante para encontrar la mejor opción, pues se estaría verificando el tipo de persona que es el propietario y si se respeta las cláusulas del contrato.

Entrevista N°04:

Segmento: Arrendatario

Entrevistador: Julio Ernesto Asillo Mendoza

Entrevistado: Leonardo Eloy Asillo Mendoza

Edad: 23 años

Timing: La entrevista inicia al minuto 23:30

Duración: 3:07 minutos

Link de la entrevista: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201b051_upc_edu_pe/EVk7Ef36WiZIrx6zkyhtKQwBlZfdFR9IV0TMJHT2ygbzsA?e=4sghBZ>

Captura:

![Captura de pantalla de un celular

Descripción generada automáticamente](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.028.png)

Resumen de la entrevista: El joven Leonardo Asillo cuenta que le costó 1 mes en poder encontrar un cuarto con los aspectos que él buscaba (seguridad, cercanía al trabajo, precio de renta accesible, etc). Considera que nuestra aplicación es interesante porque le ahorra muchos procesos de búsqueda y tiempo al momento de poder ver el cuarto.



Entrevista N°05:

Segmento: Arrendatario

Entrevistador: Edwin Lopez Huaman

Entrevistado: Merly Salon Puerta

Edad: 23 años

Timing: La entrevista dura un aproximado de 14:19 minutos

Duración: 4:50 minutos

Link de la entrevista: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201b051_upc_edu_pe/EVk7Ef36WiZIrx6zkyhtKQwBlZfdFR9IV0TMJHT2ygbzsA?e=4sghBZ>

Captura:

![Captura de pantalla de un celular con la foto de una persona en una pantalla

Descripción generada automáticamente](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.029.png)

Resumen de la entrevista: La señora Merly cuenta su experiencia al momento de buscar departamento para vivir, ella nos comenta qué le tomó mucho tiempo encontrar uno con los requisitos qué quería y aun precio accesible. También, comentó al final de la entrevista qué le gustaría tener referencias del arrendador y nos comentó algunos problemas qué tuvo con arrendadores pasados.



Entrevista N°06:

Segmento: Arrendatario

Entrevistador: Jhan Clinton Antonio Salazar

Entrevistado: Ludwin Romero Alba

Edad: 22 años

Timing: La entrevista dura un aproximado de 26:38 minutos

Duración: 4:50 minutos

Link de la entrevista: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201b051_upc_edu_pe/EVk7Ef36WiZIrx6zkyhtKQwBlZfdFR9IV0TMJHT2ygbzsA?e=4sghBZ>

Captura:

![Cara de un hombre en una pantalla

Descripción generada automáticamente con confianza media](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.030.png)

Resumen de la entrevista: El joven Ludwin comparte su experiencia al buscar un departamento para vivir. Nos comenta que le resultó muy complicado encontrar un departamento cerca de su centro de estudios. Además, nos dijo que no tuvo referencias de la zona ni del propietario en ninguna de las plataformas en las que ingresó para buscar el departamento.
1. ### <a name="_toc131683594"></a><a name="_toc145263600"></a>Análisis de entrevistas
- La edad promedio de los arrendadores entrevistados es 36 años mientras que la de los arrendatarios es, 22 años.

![Gráfico, Gráfico de barras

Descripción generada automáticamente](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.031.png)

- Todos los arrendadores usan un medio físico para guardar la información de sus arrendatarios.
- Los métodos de pago son depósito por banco o recibir el monto en persona.
- El tiempo que toma alquilar un inmueble varía entre días o semanas.
- El método de publicidad más usado es la publicación en una plataforma de rentas.
- ![Gráfico, Gráfico circular

Descripción generada automáticamente](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.032.png)Más de la mitad de nuestros usuarios cuentan con un trabajo.
- Más de la mitad de nuestros usuarios son personas extrovertidas.
- Casi todos nuestros usuarios tienen una personalidad muy sociable
- La mayoría de nuestros usuarios son personas racionales
- La mayoría de nuestros usuarios son personas empáticas
- El 100% de nuestros usuarios viven en lima
- ![Gráfico, Gráfico circular, Gráfico de burbujas

Descripción generada automáticamente](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.033.png)![Gráfico, Gráfico de burbujas

Descripción generada automáticamente](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.034.png)El 100% de nuestros usuarios usa un teléfono android
- ![Gráfico, Gráfico de barras

Descripción generada automáticamente](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.035.png)La mayoría de nuestros usuarios usan el navegador de google.



- La mayoría de nuestro usuario cuenta con un celular, laptop y computadora.

![Gráfico, Gráfico de barras

Descripción generada automáticamente](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.036.png)


- Las aplicaciones qué nuestros usuarios usan con mayor frecuencia son whatssap, Facebook y Tik Tok.

![Gráfico, Gráfico de barras

Descripción generada automáticamente](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.037.png)
1. ## <a name="_toc131683595"></a><a name="_toc145263601"></a>Needfinding
   1. ### <a name="_toc131683596"></a><a name="_toc145263602"></a>User Personas
A continuación, se construirán los User Persona de cada segmento objetivo de nuestra plataforma. Para ello, se utilizarán los datos recolectados de las entrevistas realizadas; principalmente, los que muestran los objetivos, motivaciones y frustraciones con las que cuentan cada uno de los sectores que conforman al público al que va dirigida la aplicación. Es decir, se presenta tanto un estereotipo de una persona que desea arrendar un inmueble, como de una persona dueña de un inmueble que sea poner en arriendo.



Segmento 1: Arrendatario

![Interfaz de usuario gráfica, Aplicación

Descripción generada automáticamente](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.038.png)

Segmento 2: Arrendador

![Interfaz de usuario gráfica, Aplicación

Descripción generada automáticamente](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.039.png)


1. ### <a name="_toc131683597"></a><a name="_toc145263603"></a>User Task Matrix
En esta etapa nos enfocaremos en las tareas que los User Personas arrendadores desean encontrar en la aplicación, representados por Jesus Ramírez. Asimismo, el segundo User Persona de los arrendatarios, representados por Jessica Ramos. A continuación, se presentan las tareas que realizan para alcanzar su propósito.

<table><tr><th colspan="1" rowspan="2" valign="top">User Task Matrix.</th><th colspan="2" valign="top">Jesus Ramirez (Arrendador)</th><th colspan="2" valign="top">Jessica Ramos (Arrendatario)</th></tr>
<tr><td colspan="1" valign="top">Frecuencia</td><td colspan="1" valign="top">Importancia</td><td colspan="1" valign="top">Frecuencia</td><td colspan="1" valign="top">Importancia</td></tr>
<tr><td colspan="1" valign="top">Comparar precios y características de los inmuebles.</td><td colspan="1" valign="top">Always</td><td colspan="1" valign="top">High</td><td colspan="1" valign="top">Rarely</td><td colspan="1" valign="top">Low</td></tr>
<tr><td colspan="1" valign="top">Visitar el lugar para asegurarse qué las fotos sean reales y conocer la zona</td><td colspan="1" valign="top">Always</td><td colspan="1" valign="top">High</td><td colspan="1" valign="top">Rarely</td><td colspan="1" valign="top">Low</td></tr>
<tr><td colspan="1" valign="top">Realizar una reserva en línea</td><td colspan="1" valign="top">Often</td><td colspan="1" valign="top">High</td><td colspan="1" valign="top">Often</td><td colspan="1" valign="top">Medium</td></tr>
<tr><td colspan="1" valign="top">Recordarle al usuario las fechas de pago qué tiene que cumplir</td><td colspan="1" valign="top">Always</td><td colspan="1" valign="top">Medium</td><td colspan="1" valign="top">Always</td><td colspan="1" valign="top">Medium</td></tr>
<tr><td colspan="1" valign="top">Mostrarle referencias del arrendador al arrendatario según contratos pasados y viceversa </td><td colspan="1" valign="top">Often</td><td colspan="1" valign="top">Medium</td><td colspan="1" valign="top">Often</td><td colspan="1" valign="top">Medium</td></tr>
<tr><td colspan="1" valign="top">Realizar una queja a través de la app sobre una mala experiencia</td><td colspan="1" valign="top">Often</td><td colspan="1" valign="top">Low</td><td colspan="1" valign="top">Often</td><td colspan="1" valign="top">Medium</td></tr>
<tr><td colspan="1" valign="top">Antes de desocupar el inmueble tanto el arrendador como el arrendatario podrán calificarse mutuamente</td><td colspan="1" valign="top">Often</td><td colspan="1" valign="top">Low</td><td colspan="1" valign="top">Often</td><td colspan="1" valign="top">Low</td></tr>
</table>

1. ### <a name="_toc131683598"></a><a name="_toc145263604"></a>User Journey Mapping
Un User Journey Mapping, o mapeo del recorrido del usuario, es una poderosa herramienta que se emplea para visualizar y comprender en detalle el camino que un usuario sigue desde el primer punto de contacto con un producto o servicio hasta que alcanza su objetivo final. Esta herramienta es fundamental para identificar áreas de mejora en la experiencia del usuario y garantizar que los procesos de la empresa estén alineados de manera efectiva con las necesidades y expectativas del usuario.



Segmento 1: Arrendatario

![Imagen que contiene Diagrama

Descripción generada automáticamente](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.040.png)








![](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.041.png)Segmento 2: Arrendador 


1. ### <a name="_toc131683599"></a><a name="_toc145263605"></a>Empathy Mapping
En esta sección se presenta el Empathy Mapping de nuestros 2 segmentos objetivos. Esta herramienta se utilizó porque permite identificar nuestro público objetivo, conocer su entorno y sus necesidades, lo cual nos permite ver el mundo a través de su perspectiva.

![Texto

Descripción generada automáticamente](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.042.png)Segmento 1: Arrendatario



![Texto

Descripción generada automáticamente](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.043.png)Segmento 2: Arrendador


1. ### <a name="_toc131683600"></a><a name="_toc145263606"></a>As-Is Scenario Mapping
As-is Scenario mapping para Arrendatarios:

|Phases|Búsqueda de inmueble|Contactándose con el propietario|Pago de alquiler|Fin del contrato|
| :- | :- | :- | :- | :- |
|Doing|<p>-Revisa páginas inmobiliarias</p><p>-Pregunta a conocidos</p>|<p>-Escribe al propietario por WhatsApp o email</p><p>-Se reúne con el propietario para realizar una visita al lugar antes de alquilarlo.</p><p>-Habla con el propietario para determinar las cláusulas del contrato: duración del alquiler, precio acordado, etc.</p>|-Deposita a la cuenta de su arrendador.|<p>-Repara o paga un monto por los posibles daños realizados al inmueble durante su instancia, según lo estipulado en el contrato.</p><p>-Busca de un nuevo lugar para alquilar semanas previas al fin del contrato o renovamiento del contrato anterior, dependiendo de ambas partes.</p>|
|Thinking|-” Tengo muchas opciones, pero ninguna cumple con todos mis requisitos”|-” Espero que me guste el inmueble y sus alrededores”|-Si es que pagara a destiempo: “Espero que no se moleste”|- “Espero poder encontrar un nuevo inmueble antes de que termine el contrato”|
|Feeling|<p>-Apurado por encontrar un inmueble</p><p>-Abrumado </p>|<p>-Optimista por conocer su nueva casa.</p><p>-Contento por haber encontrado un inmueble de su gusto</p><p>-Emocionado por mudarse rápidamente.</p>|-Desperado porque nunca logra acordarse del pago del alquiler.|-|

As-is Scenario mapping para Arrendadores:

|Phases|Búsqueda de inquilinos|Realizando el contrato de alquiler|Recibiendo alquiler|Fin de contrato|
| :- | :- | :- | :- | :- |
|Doing|<p>-Publica anuncios de alquiler en diversos websites.</p><p>-Contesta llamadas de posibles inquilinos.</p><p>-Muestra el inmueble a posibles inquilinos</p><p>-Intenta conseguir información sobre sus inquilinos</p>|<p>-Piensa en las condiciones de alquiler correctas</p><p>-Discute todos los términos y condiciones con su inquilino</p><p>-Redacta el contrato de arrendamiento</p><p>-Paga costo notariales</p><p>-Acude a un notario para realizar la firma del contrato.</p>|<p>-De ser necesario: Hace recordar a su inquilino que le toca pagar la renta</p><p>-Recibe el depósito del monto acordado en su cuenta bancaria.</p>|<p>-Verifica el estado de su propiedad y la repara si hubiera sufrido algún daño.</p><p>-Comienza el proceso de una nueva búsqueda de inquilinos</p>|
|Thinking|<p>- ¿Cuánto tiempo me demoraré en alquilar mi propiedad?</p><p>-Espero que sea un buen pagador</p>|-Me pregunto si habré especificado lo suficiente en el contrato.|-Espero me pague a tiempo|-Me pregunto si encontraré un nuevo inquilino pronto|
|Feeling|-Apurado por alquilar su inmueble|-Frustrado por la cantidad de trabajo que tiene que hacer para lograr alquilar el inmueble|-Un poco preocupado esperando que le paguen|-Nervioso por no lograr a volver alquilarlo.|



CHAPTER
# ![](Aspose.Words.1a4f8edb-5488-4d5f-b36e-f9fefe7baecb.044.png)
**CAPÍTULO III: REQUIREMENTS SPECIFICATION** 

## <a name="_toc131679442"></a><a name="_toc131679533"></a><a name="_toc131682240"></a><a name="_toc131683602"></a><a name="_toc131683603"></a><a name="_toc145263608"></a>To-Be Scenario Mapping
Segmento 1: Arrendatarios

|Phases|Búsqueda de inmueble|Contactándose con el propietario|Pago de alquiler|
| :- | :- | :- | :- |
|Doing|- Entra a la aplicación donde ya se ha registrado con éxito para buscar un cuarto o inmueble en alquiler.|- Le voy a enviar un mensaje al arrendador para acordar cuando reunirnos y ver el cuarto en persona.|- Pude realizar el pago del alquiler del cuarto gracias a que Renstate me notifico la fecha de vencimiento de este.|
|Thinking|<p>- Hay demasiadas opciones y datos específicos del cuarto.</p><p>- Miraré las reseñas de los arrendadores para ver como son.</p>|- Espero que el arrendador me acepte como arrendatario, porque tengo buen historial de pagos dentro de la aplicación.|- Si sigo manteniendo mi racha de buen pagador, entonces tendré un buen historial dentro de Renstate.|
|Feeling|- Tranquilo y paciente hasta encontrar un cuarto de mi agrado.|- Alegre y nervioso porque encontré un cuarto de acuerdo con mis exigencias.|- Feliz y puntual, porque tengo buen tiempo en el cuarto y tener mis pagos al día sin falta.|

Segmento 2: Arrendador

|Phases|Búsqueda de inquilinos|Realizando el contrato de alquiler|Recibiendo alquiler|Fin de contrato|
| :- | :- | :- | :- | :- |
|Doing|- Publico fotos del inmueble que quiero alquilar en Renstate y registro datos necesarios o relevantes.|<p>- Todas las condiciones del contrato lo subo en la aplicacion para que los usuarios arrendatarios puedan ver mis condiciones, también publico horarios para agendar una cita con el arrendatario.</p><p>- Me reúno con el arrendatario para hacer un recorrido por el cuarto y resolver dudas de manera clara del contrato publicado.</p><p>- Procedo a la firma del contrato con el arrendatario.</p><p>- Entrego las llaves del cuarto al arrendatario.</p>|<p>- Si es necesario, hago recordar al usuario que tiene que ir pagando el alquiler mediante notificaciones.</p><p>- Verifica que el depósito se ha realizado en su cuenta bancaria.</p><p>- En la aplicación coloca como pago exitoso del mes respectivo.</p>|<p>- Repara o limpia el cuarto que ha sido alquilado.</p><p>- En la aplicación coloca el cuarto como disponible. </p>|
|Thinking|- No creo demorar demasiado en encontrar un inquilino, espero que tenga buena reseña dentro de la aplicacion.|<p>- Espero que el arrendatario sea como describieron en las reseñas.</p><p>- Al fin tengo un ingreso extra más por el cuarto que tengo alquilado.</p>|<p>- Bien, todo está de acuerdo con el contrato.</p><p>- Tengo suerte de tener un inquilino responsable con los pagos.</p>|<p>- Bueno solo queda esperar a que otro arrendatario se interese por el inmueble.</p><p>- No tengo que olvidarme de revisar las reseñas del arrendatario.</p>|
|Feeling|- Tranquilo hasta encontrar un inquilino que tenga buen historial de pagos.|- Alegre porque ya tengo alquilado mi cuarto y empezare a generar ingresos pasivos.|- Alegre porque acepte un inquilino que tenía una buena calificación en la aplicación y cumple con los pagos.|- Tranquilo y alegre porque he generado ingresos pasivos con el alquiler de mi inmueble, ahora solo tengo que esperar otras solicitudes.|


1. ## <a name="_toc131683604"></a><a name="_toc145263609"></a>User Stories
Epics

|Epics ID|Título|Descripción|
| :- | :- | :- |
|EP01|Optimización de la experiencia de usuario|Como visitante quiero visualizar una presentación atractiva, fácil de usar y entender para conocer rápidamente los servicios y características que ofrece.|
|EP02|Gestión de cuenta|Como usuario quiero acceder a mi cuenta para entrar a la plataforma y poder realizar cambios a mi perfil.|
|EP03|Gestión de resultados de búsqueda|Como arrendatario quiero que todas las búsquedas que realice sean eficientes y efectivas para encontrar rápidamente lo que necesito.|
|EP04|Gestión de registros|Como arrendador quiero gestionar y optimizar mis registros de clientes y propiedades en la plataforma para tener un control eficiente sobre ellos.|
|EP05|Gestión de mensajería|Como usuario quiero que la gestión de mensajes sea eficiente y fácil de usar para recibir información relevante y rápido.|
|EP06|Gestión de calificaciones|Como usuario quiero visualizar mi calificación y calificar a mis arrendatarios o arrendadores para que los demás usuarios tengan referencias.|
|EP07|Gestión de publicaciones|Como arrendador quiero crear, editar y publicar anuncios para poder mostrarlos a posibles arrendatarios.|
|EP08|Gestión de suscripción y anuncios|Como arrendador quiero poder tener la opción de promocionar mi inmueble y así llegar a más personas.|



User Stories

|Epic/Story ID|Título|Descripción|Criterios de Aceptación|Relacionada con (Epic ID)|
| :- | :- | :- | :- | :- |
|US-01|Visualizar una landing page clara y atractiva.|Como visitante, quiero ver una landing page clara y atractiva para que pueda entender rápidamente el propósito de la aplicación web.|<p>Escenario 01:</p><p>Visitante visualiza una landing page clara y atractiva</p><p>Dado que el visitante ve la landing page con imágenes, videos e información relevante</p><p>Cuando complete el proceso de registro y login</p><p>Entonces será redirigido a la aplicación web</p><p>Escenario 02:</p><p>Visitante no visualiza una landing page clara y atractiva</p><p>Dado que el visitante visualiza una landing page sin imágenes, videos e información relevante</p><p>Cuando no vea estas características</p><p>Entonces cierra la ventana y sigue navegando en internet.</p>|EP01|
|US-02|Visualizar una sección sobre nosotros en el landing page.|Como visitante, quiero ver una sección en el landing page que me informe sobre el startup para saber el propósito y con quiénes estoy tratando al momento de usar su aplicación web.|<p>Escenario 01:</p><p>El usuario visualiza una sección sobre el startup en el landing page</p><p>Dado que el usuario visualiza una sección que describe el startup</p><p>Cuando lea y revise la sección</p><p>Entonces entiende el propósito de nuestro startup.</p><p>Escenario 02:</p><p>El usuario no visualiza una sección sobre nosotros en la landing page</p><p>Dado que el usuario no visualiza una sección sobre el startup</p><p>Cuando note esta falta de información</p><p>Entonces cierra la ventana del landing page y sigue navegando por internet.</p>|EP01|
|US-03|Visualizar contenido relevante en el landing page.|Como usuario, quiero que la landing page tenga contenido relevante para que pueda tomar una decisión informada.|<p>Escenario 01:</p><p>El usuario visualiza un contenido relevante en el landing page</p><p>Dado que el usuario visualiza contenido relevante en la landing page</p><p>Cuando se registré dentro del landing page</p><p>Entonces será redirigido a la aplicación web, para que pueda registrarse.</p><p>Escenario 02:</p><p>El usuario visualiza información dudosa en el landing page</p><p>Dado que el usuario visualiza información irrelevante</p><p>Cuando termine de revisar el landing page</p><p>Entonces decide cerrar la landing page y sigue navegando en internet.</p>|EP01|
|US-04|Acceder desde cualquier dispositivo a la landing page.|Como usuario, quiero que la landing page sea accesible desde diferentes dispositivos para que pueda acceder al sitio web desde cualquier lugar.|<p>Escenario 01:</p><p>El usuario accede al contenido del landing page desde cualquier dispositivo</p><p>Dado que la landing page es responsive</p><p>Cuando el usuario ingresa a nuestra landing page</p><p>Entonces podrá visualizar la información de manera organizada, adaptada al tamaño de pantalla que esté utilizando.</p><p></p><p>Escenario 02:</p><p>El usuario accede al landing page, pero no es responsive con cualquier dispositivo</p><p>Dado que el usuario está ingresando al landing page desde otro dispositivo</p><p>Cuando revise la información, lo notará desordenado y desagradable para la vista</p><p>Entonces cierra nuestra landing page y se dedica a seguir navegando por internet.</p>|EP01|
|US-05|Desplegar la landing page|Como startup, quiero desplegar una landing page para informar sobre nuestra aplicación.|<p>Escenario 01:</p><p>Éxito en el despliegue de la landing page</p><p>Dado que la landing page está listo</p><p>Cuando se despliegue la landing page en Github Pages</p><p>Entonces cualquier usuario de internet que tenga el URL o decida indagar en la web, podrá visualizar nuestra landing page.</p><p>Escenario 02:</p><p>Landing page no está listo para el despliegue</p><p>Dado que el startup no puede desplegar la landing page</p><p>Cuando esta no cumple con los requisitos del startup </p><p>Entonces nadie podrá visualizar la landing page y será un retraso para poder informar sobre nuestra aplicación.</p>|EP01|
|US-06|Buscar inmuebles|Como arrendatario quiero que la aplicación me ayude a encontrar inmuebles para tener diferentes opciones de acuerdo con mis necesidades.|<p>Escenario 01:</p><p>El arrendatario busca un inmueble y encuentra resultados</p><p>Dado que el arrendatario quiere buscar un inmueble para arrendar</p><p>Cuando termine de ingresar los datos</p><p>y ejecute la búsqueda</p><p>Entonces se ejecuta la búsqueda de un inmueble de acuerdo con sus preferencias </p><p>Y se muestra una lista de resultados de acuerdo con sus preferencias.</p><p>Escenario 02:</p><p>El arrendatario busca un inmueble y no encuentra resultados</p><p>Dado que el arrendatario quiere buscar un inmueble para arrendar</p><p>Cuando ingrese los datos de búsqueda</p><p>Y la aplicación no encuentre resultados que coincidan con la búsqueda</p><p>Entonces no se muestra resultados.</p>|EP03|
|US-07|Rentar inmueble.|Como arrendatario quiero reservar un inmueble para rentar el inmueble.|<p>Escenario 01: Reservar inmueble </p><p>Dado que el arrendatario quiere reservar un inmueble</p><p>Cuando visualiza una publicación que le interesa</p><p>Entonces reserva el inmueble.</p><p></p><p>Escenario 02: Confirmar renta</p><p>Dado que el arrendador visualiza la reserva del arrendatario</p><p>Cuando ambos usuarios estén de acuerdo</p><p><br>Entonces el arrendador confirma la renta.</p>|EP-04|
|US-08|Visualizar arrendatarios. |Como arrendador quiero visualizar a mis clientes en la aplicación para tener la información organizada de cada uno de ellos.|<p>Escenario 01:  Visualizar lista de arrendatarios</p><p>Dado que el arrendador quiere visualizar la lista de arrendatarios</p><p>Cuando el arrendatario renta un inmueble</p><p>Entonces se agrega automáticamente a la lista de clientes del arrendador</p><p>Escenario 02:  Visualizar lista de reservas</p><p>Dado que el arrendador quiere visual la lista de reservas</p><p>Cuando el usuario reserva un inmueble</p><p>Entonces se agrega automáticamente a la lista de reservas del arrendador</p><p></p><p></p>|EP04|
|US-09|Publicar dentro de la aplicación|Como arrendatario quiero que la aplicación me ayude a encontrar inmuebles para tener diferentes opciones de acuerdo con mis|<p>Escenario 01: Publicar un inmueble </p><p>El arrendador ingresa los datos para la publicación de un inmueble</p><p>Dado que el arrendador esta registrado dentro de la aplicación</p><p>Y está buscando personas que arrienden un inmueble</p><p>Cuando ingrese a la sección de publicar</p><p>Entonces es redirigido a una ventana para crear anuncio donde completa el formulario con los datos del inmueble a publicar.</p><p>Escenario 02: Validar publicación</p><p>Dado que el arrendador está registrado dentro de la aplicación</p><p>Y está buscando personas que arrienden un inmueble</p><p>Cuando ingrese a la sección de publicar</p><p>Entonces se le indica que ya existe una publicación similar o igual.</p><p></p>|EP08|
|US-10|Listar publicaciones|Como arrendador quiero administrar mis publicaciones para tener organizado mi lista de publicaciones.|<p>Escenario 01: Eliminar publicación</p><p>Dado que el arrendador ha realizado una publicación</p><p>Cuando no quiera seguir rentando el inmueble</p><p>Entonces elimina la publicación de su perfil de usuario.</p><p>Escenario 02: Editar publicación</p><p>Dado que el arrendador ya realizó su publicación</p><p>Cuando quiera editar o actualizar</p><p>Entonces el arrendador podrá modificar campos de su publicación.</p>||
|US-11|Calificar al arrendador|Como usuario quiero calificar el perfil del arrendador para que sirva de referencia a otros usuarios.|<p>Escenario 01: Calificar</p><p>Dado que el arrendador esta registrado dentro la aplicación</p><p>Cuando el usuario quiera calificar al arrendador</p><p>Entonces la aplicación muestra la media de calificaciones.</p><p>Escenario 02: Editar la calificación</p><p>Dado que el usuario se equivocó al ingresar la calificación del arrendador</p><p>Cuando ingrese nuevamente al perfil del arrendador</p><p>Entonces puede volver a editar la calificación.</p>|EP06|
|US-12|Categorizar inmuebles|Como usuario quiero visualizar los inmuebles por categorías para encontrar con facilidad un inmueble.|<p>Escenario 01: El usuario quiere rentar </p><p>Dado que el usuario necesita rentar un inmueble en específico</p><p>Cuando busque una categoría en específico </p><p>Entonces visualiza los resultados de su búsqueda. </p><p>Escenario 02: El usuario no encuentra resultado</p><p>Dado que el usuario necesita rentar un inmueble en específico</p><p>Cuando busque una categoría en específico y este no se encuentra resultados</p><p>Entonces no visualiza los resultados.</p>|EP03|
|US-13|Crear mi perfil en la aplicación|Como usuario de la aplicación quiero crear mi cuenta para acceder a todos los servicios de la aplicación.|<p>Escenario 01: Crear un perfil exitosamente</p><p>Dado que el usuario está en la página de creación de cuenta o perfil</p><p>Cuando el usuario completa todos los campos requeridos</p><p>Y crea un profile</p><p>Entonces el sistema debe crear el perfil exitosamente y guardarlo en la base de datos</p><p>Y redirigir al usuario a su respectiva página de Inicio.</p><p><br>Escenario 02: Crear perfil sin completar todos los campos requeridos.</p><p>Dado que el usuario está en la página de creación de perfil</p><p>Cuando el usuario no completa todos los campos requeridos</p><p>Entonces el sistema no crea el perfil.</p><p>Escenario 03:</p><p>Visualizar el perfil creado</p><p>Dado que el usuario ha creado un perfil de manera exitosa</p><p>Cuando el usuario accede a la página de perfil</p><p>Entonces el sistema debe mostrar todos los datos del perfil creado.</p><p>Escenario 04:</p><p>Editar el perfil</p><p>Dado que el usuario ha creado un perfil exitosamente</p><p>Cuando el usuario accede a la página de perfil</p><p>Entonces el sistema debe mostrar el perfil creado</p><p>Escenario 05:</p><p>Eliminar perfil</p><p>Dado que el usuario ha creado un perfil exitosamente</p><p>Cuando desee eliminar su cuenta</p><p>Y confirma la eliminación</p><p>Entonces el sistema debe eliminar el perfil de la base de datos</p><p>Y redirigir al usuario a la página de inicio.</p>|EP02|
|US-14|Gestionar el plan de Suscripción|Como startup, quiero que mis usuarios tengan un plan de suscripción para generar ganancias y poder realizar un buen mantenimiento de la aplicación.|<p>Escenario 01:</p><p>Arrendador decide pagar el plan de suscripción</p><p>Dado que el arrendador esta registrado dentro de la aplicación </p><p>Y mira las ventajas que tiene pagar un plan de suscripción</p><p>Cuando decida realizar el pago de la suscripción </p><p>Entonces realiza la transacción.</p><p>Escenario 02:</p><p>Arrendador no quiere pagar el plan de suscripción</p><p>Dado que el arrendador esta registrado dentro de la aplicación</p><p>Y mira las ventajas de tener un plan de suscripción</p><p>Cuando ya no desee continuar con el plan de suscripción</p><p>Entonces se cancela la suscripción.</p>||
|US-15|Promocionar una publicación|Como arrendador quiero promocionar mi publicación y que este se vea al inicio de la lista para que más personas lo vean|<p>Escenario 01:</p><p>Arrendador va a pagar para publicitar su publicación</p><p>Dado que el arrendador quiere que más personas vean su inmueble en renta</p><p>Cuando decida realizar el pago de la promoción</p><p>Entonces su publicación se mostrar al inicio de todas.</p>|EP08|
|US-16|Configurar la Base de Datos|Como desarrollador, quiero configurar una base de datos para almacenar información de usuarios y propiedades.|<p>Escenario 01: La creación de tablas se realizó de manera exitosa.</p><p>Dado que la base de datos está vacía.</p><p>Cuando ejecuto el script de creación de la base de datos.</p><p>Entonces las tablas de usuarios y propiedades se crean sin errores.</p><p></p><p>Escenario 02: Se agregó un nuevo campo a la tabla correctamente.</p><p>Dado que la base de datos ya tiene tablas existentes.</p><p>Cuando se agrega un nuevo campo a una tabla existente.</p><p>Entonces el nuevo campo se agrega correctamente a la estructura de la tabla.</p><p></p><p>Escenario 03: La tabla se eliminó sin problemas.</p><p>Dado que la base de datos tiene tablas creadas.</p><p>Cuando se ejecuta un script para eliminar las tablas.</p><p>Entonces las tablas se eliminan de la base de datos sin problemas.</p>||
|US-17|Sistema de Autenticación y Registro|Como desarrollador quiero implementar un sistema de autenticación y registro.|<p>Escenario 01: El desarrollador implementa la autenticación.</p><p>Dado que quiero garantizar la seguridad de la aplicación</p><p>Cuando implemento el sistema de autenticación</p><p>Entonces debería permitir a los usuarios registrarse e iniciar sesión de manera segura.</p><p></p><p>Escenario 02: El usuario se registra de manera exitosa.</p><p>Dado que el bounded context de seguridad está completo</p><p>Cuando un usuario nuevo completa el proceso de registro en la aplicación</p><p>Entonces los detalles del usuario: nombre y correo electrónico se almacenan en la base de datos.</p><p></p><p>Escenario 03: La aplicación responde al manejo de errores en el registro.</p><p>Dado que un usuario intenta registrarse, pero proporciona datos incorrectos o incompletos</p><p>Cuando el usuario intenta enviar el formulario de registro</p><p>Entonces la aplicación muestra mensajes de error adecuados para guiar al usuario a corregir los campos incorrectos o faltantes.</p><p></p><p></p><p></p>||
|US-18|Funcionalidad de Búsqueda Avanzada|<p>Como desarrollador, quiero desarrollar la funcionalidad de búsqueda avanzada con filtros.</p><p></p>|<p>Escenario 01: Configuración de filtros</p><p>Dado que se tienen diferentes propiedades almacenadas en la base de datos</p><p>Cuando el desarrollador trabaje en la funcionalidad de búsqueda avanzada</p><p>Entonces el desarrollador crea consultas SQL personalizadas para filtrar propiedades según los criterios de búsqueda especificados como ubicación y rango de precios.</p><p></p><p>Escenario 02: Interfaz de filtros</p><p>Dado que los usuarios necesitan una forma intuitiva de establecer los filtros de búsqueda avanzada</p><p>Cuando el desarrollador implemente la interfaz de usuario para la búsqueda avanzada</p><p>Entonces el desarrollador crea componentes de filtro en la interfaz que permiten a los usuarios elegir criterios.</p><p></p><p>Escenario 03: Visualización de resultados</p><p>Dado que se requiere una forma eficiente de presentar los resultados de la búsqueda</p><p>Cuando desarrollador trabaje en la visualización de los resultados</p><p>Entonces el desarrollador diseña una página de resultados que muestra las propiedades de manera ordenada.</p>||
|US-19|Implementar mensajería|Como desarrollador, quiero implementar un sistema de mensajería para que los usuarios puedan comunicarse en la plataforma.|<p>Escenario 01: Tabla de mensajes</p><p>Dado que los usuarios deben poder enviar y recibir mensajes en tiempo real.</p><p>Cuando el desarrollador configure la mensajería.</p><p>Entonces el desarrollador integra en la aplicación la comunicación en tiempo real entre usuarios.</p><p></p><p>Escenario 02: Tabla de mensajes</p><p>Dado que: Los mensajes deben estar asociados correctamente con los usuarios y las conversaciones.</p><p>Cuando: El desarrollador diseñe la estructura de datos para la mensajería.</p><p>Entonces: El desarrollador crea tablas en la base de datos que almacenan información sobre mensajes, conversaciones, remitentes y destinatarios.</p>||
|US-20|Optimizar el rendimiento de la aplicación|Como desarrollador, quiero optimizar el rendimiento de la aplicación para una experiencia rápida y fluida.|<p>Escenario 01: Carga rápida de propiedades</p><p>Dado que un usuario navega por la lista de propiedades</p><p>Cuando desplaza hacia abajo o arriba</p><p>Entonces la carga de propiedades y las imágenes deben ser suaves y sin retrasos visibles.</p><p></p><p>Escenario 02: Carga rápida entre pantallas</p><p>Dado que un usuario cambia entre pantallas de manera rápida </p><p>Cuando navega por la aplicación </p><p>Entonces no debe haber problemas de carga o bloqueo.</p><p></p><p>Escenario 03: Rendimiento óptimo</p><p>Dado que un usuario abre la aplicación después de un período de inactividad </p><p>Cuando la aplicación se reanuda</p><p>Entonces debe cargar rápidamente sin demoras perceptibles.</p>||
|US-21|Diseñar la Interfaz de Usuario|Como desarrollador quiero diseñar una interfaz de usuario atractiva y fácil de usar para una experiencia agradable.|<p>`	`Escenario 01: Experiencia en la aplicación</p><p>Dado que un usuario abre la aplicación por primera vez</p><p>Cuando ve la pantalla de inicio</p><p>Entonces debe ser recibido con una interfaz atractiva.</p><p></p><p>Escenario 02: Exploración de la aplicación</p><p>Dado que un usuario explora propiedades </p><p>Cuando navega por las listas y detalles </p><p>Entonces debe ser fácil de entender y navegar, con botones y elementos intuitivos.</p><p></p><p>Escenario 03: Mensajes de confirmación</p><p>Dado que un usuario completa una acción, como enviar un mensaje</p><p>Cuando realiza la acción </p><p>Entonces debe recibir retroalimentación visual, como un mensaje de confirmación o un cambio de estado en el botón.</p>||
|US-22|Listar propiedades|Como arrendador, quiero poder listar mis propiedades en la plataforma para que los arrendatarios puedan verlas y alquilarlas.|<p>Escenario 1: Agregar una propiedad</p><p>- Dado que soy un arrendador registrado en la plataforma “RentState”.</p><p>- Cuando decido que quiero listar una de mis propiedades para alquilar.</p><p>- Entonces inicio sesión en mi cuenta de “RentState” y voy a la sección “Mis Propiedades”.</p><p>- Luego hago clic en el botón “Agregar Propiedad” y completo el formulario con la información de mi propiedad, incluyendo fotos y una descripción detallada.</p><p>- Finalmente, hago clic en el botón “Guardar” y veo un mensaje que confirma que mi propiedad ha sido agregada a la plataforma con éxito.</p><p>Escenario 2: Ver mis propiedades listadas</p><p>- Dado que soy un arrendador registrado en la plataforma “RentState” y he agregado una o más propiedades a la plataforma.</p><p>- Cuando quiero ver las propiedades que he listado en la plataforma.</p><p>- Entonces inicio sesión en mi cuenta de “RentState” y voy a la sección “Mis Propiedades”.</p><p>- Luego veo una lista de todas las propiedades que he agregado a la plataforma, con información básica como la dirección, el precio y una foto de portada.</p>||
|US-23|Actualizar información de propiedades|Como arrendador, quiero poder actualizar la información de mis propiedades en cualquier momento para mantenerla actualizada y precisa.|<p>Escenario 1: Actualizar información de propiedades</p><p></p><p>- Dado que soy un arrendador que ha listado una propiedad en la plataforma “RentState”.</p><p>- Cuando decido que quiero cambiar el precio de alquiler de mi propiedad.</p><p>- Entonces inicio sesión en mi cuenta de “RentState”, voy a la lista de mis propiedades y selecciono la propiedad que quiero actualizar.</p><p>- Luego cambio el precio en el campo correspondiente y hago clic en el botón “Actualizar”.</p><p>- Finalmente, veo un mensaje que confirma que la información de mi propiedad ha sido actualizada con éxito.</p>||
|US-24|Leer comentarios sobre propiedades|Como arrendatario, quiero poder leer comentarios de otros usuarios sobre las propiedades para tener una idea de las experiencias de otros inquilinos.|<p>Escenario 1: Ver comentarios en una propiedad</p><p>- Dado que soy un arrendatario registrado en la plataforma “RentState”.</p><p>- Cuando estoy buscando una propiedad para alquilar y encuentro una que me interesa.</p><p>- Entonces hago clic en la propiedad para ver más detalles y voy a la sección de comentarios.</p><p>- Luego veo una lista de comentarios dejados por otros usuarios, con información como la fecha, el nombre del usuario y el contenido del comentario.</p><p>Escenario 2: Filtrar comentarios por calificación</p><p>- Dado que soy un arrendatario registrado en la plataforma “RentState” y estoy viendo los comentarios en una propiedad.</p><p>- Cuando quiero ver solo los comentarios con una calificación específica, por ejemplo, solo los comentarios con 4 o 5 estrellas.</p><p>- Entonces selecciono la opción de filtrar por calificación y elijo las calificaciones que quiero ver.</p><p>- Luego veo que la lista de comentarios se actualiza para mostrar solo los comentarios con las calificaciones seleccionadas.</p>||
|US-25|Dejar comentarios sobre propiedades|Como arrendatario, quiero poder dejar comentarios sobre las propiedades que he alquilado para compartir mi experiencia con otros usuarios.|<p>Escenario 1: Dejar un comentario en una propiedad</p><p>- Dado que soy un arrendatario registrado en la plataforma “RentState” y he alquilado una propiedad a través de la plataforma.</p><p>- Cuando decido que quiero dejar un comentario sobre mi experiencia alquilando esa propiedad.</p><p>- Entonces inicio sesión en mi cuenta de “RentState”, voy a la página de la propiedad y hago clic en el botón “Dejar un comentario”.</p><p>- Luego escribo mi comentario en el campo proporcionado, selecciono una calificación y hago clic en el botón “Publicar comentario”.</p><p>- Finalmente, veo mi comentario publicado en la sección de comentarios de la página de la propiedad.</p><p>Escenario 2: Editar o eliminar un comentario</p><p>- Dado que soy un arrendatario registrado en la plataforma “RentState” y he dejado un comentario en una propiedad.</p><p>- Cuando decido que quiero editar o eliminar mi comentario.</p><p>- Entonces inicio sesión en mi cuenta de “RentState”, voy a la página de la propiedad y busco mi comentario en la sección de comentarios.</p><p>- Luego hago clic en el botón “Editar” o “Eliminar” junto a mi comentario y realizo los cambios necesarios o confirmo que quiero eliminarlo.</p><p>- Finalmente, veo que mi comentario ha sido actualizado o eliminado correctamente.</p>||
|US-26|Responder a comentarios sobre propiedades|Como arrendador, quiero poder responder a los comentarios dejados en mis propiedades para aclarar cualquier duda o inquietud que puedan tener los arrendatarios.|<p>Escenario 1: Responder a un comentario en una propiedad</p><p>- Dado que soy un arrendador registrado en la plataforma “RentState” y un arrendatario ha dejado un comentario en una de mis propiedades.</p><p>- Cuando decido que quiero responder al comentario.</p><p>- Entonces inicio sesión en mi cuenta de “RentState”, voy a la página de la propiedad y busco el comentario en la sección de comentarios.</p><p>- Luego hago clic en el botón “Responder” junto al comentario, escribo mi respuesta en el campo proporcionado y hago clic en el botón “Publicar respuesta”.</p><p>- Finalmente, veo mi respuesta publicada debajo del comentario original en la sección de comentarios de la página de la propiedad.</p><p>Escenario 2: Editar o eliminar una respuesta a un comentario</p><p>- Dado que soy un arrendador registrado en la plataforma “RentState” y he respondido a un comentario en una de mis propiedades.</p><p>- Cuando decido que quiero editar o eliminar mi respuesta.</p><p>- Entonces inicio sesión en mi cuenta de “RentState”, voy a la página de la propiedad y busco mi respuesta en la sección de comentarios.</p><p>- Luego hago clic en el botón “Editar” o “Eliminar” junto a mi respuesta y realizo los cambios necesarios o confirmo que quiero eliminarla.</p><p>- Finalmente, veo que mi respuesta ha sido actualizada o eliminada correctamente.</p>||
|US-27|Participar en un foro|Como arrendador o arrendatario, quiero poder participar en un foro para hacer preguntas y compartir información con otros usuarios de la plataforma.|<p>Escenario 1: Publicar un tema en el foro</p><p>- Dado que soy un usuario registrado en la plataforma “RentState”.</p><p>- Cuando tengo una pregunta o información que quiero compartir con otros usuarios en el foro.</p><p>- Entonces inicio sesión en mi cuenta de “RentState” y voy a la sección del foro.</p><p>- Luego hago clic en el botón “Crear un tema” y completo el formulario con el título y contenido de mi tema.</p><p>- Finalmente, hago clic en el botón “Publicar tema” y veo mi tema publicado en el foro.</p><p>Escenario 2: Responder a un tema en el foro</p><p>- Dado que soy un usuario registrado en la plataforma “RentState” y estoy viendo un tema en el foro.</p><p>- Cuando decido que quiero responder al tema.</p><p>- Entonces escribo mi respuesta en el campo proporcionado debajo del tema y hago clic en el botón “Publicar respuesta”.</p><p>- Finalmente, veo mi respuesta publicada debajo del tema original en el foro.</p>||


1. ## <a name="_toc131683605"></a><a name="_toc145263610"></a>Impact Mapping
Impact Mapping es una metodología que ayuda de una forma visual a pensar en las metas que realmente queremos lograr para tener el alcance de nuestros usuarios. Por ello usamos esta herramienta con el fin de establecer enfoque y alcanzar las metas de nuestro objetivo principal. De tal manera, que al final del mapa mental identificamos las acciones y funcionalidades que debemos llevar a cabo para formar el proyecto de manera eficiente.

User: Arrendador

Se presenta la sección del Impact Map en el usuario, arrendador, en la que se basó en las User Stories de nuestro proyecto, dónde se da opciones que dispone el sitio web para solucionar el percance del usuario, así como satisfacer las necesidades que presente cuando necesite buscar y rentar un inmueble.


<img src="https://i.ibb.co/tY1D1d9/ux.png" alt="ux" border="0">
User: Arrendatario:

En esta versión del arrendatario. En la cual, gracias a la herramienta Impact map, diseñamos los impacts y deliverables que nos ayudará a establecer las opciones determinantes que llamen la atención del usuario y acceda a usar nuestra plataforma. Por último, se utilizó las User Stories como base para implementar.

<img src="https://i.ibb.co/nbG65TV/uxarrendatario.png" alt="uxarrendatario" border="0">


1. ## <a name="_toc131683606"></a><a name="_toc145263611"></a>Product Backlog
Una vez ya redactadas todas las User Stories, debemos priorizarlas. El Product Backlog se encarga de generar un orden de importancia entre todas las historias de usuarios, mientras más Story Points contenga, más relevante será para la plataforma. Por esta razón, se antepondrá el desarrollo de las US que tengan más puntos.

|# Orden/ Priority|User Story Id|Título|Descripción|Story Points (1 / 2 / 3 / 5 / 8)|
| :- | :- | :- | :- | :- |
|1|US-06|Buscar inmueble|Como arrendatario quiero que la aplicación me ayude a encontrar inmuebles para tener diferentes opciones de acuerdo con mis necesidades.|8|
|2|US-09|Publicar dentro de la aplicación|Como arrendatario quiero que la aplicación me ayude a encontrar inmuebles para tener diferentes opciones de acuerdo con mis|8|
|3|US-12|Categorizar inmuebles|Como usuario quiero visualizar los inmuebles por categorías para encontrar con facilidad un inmueble.|5|
|4|US-10|Implementar mensajería|Como desarrollador, quiero implementar un sistema de mensajería para que los usuarios puedan comunicarse en la plataforma.|5|
|5|US-07|Rentar inmueble|Como arrendatario quiero reservar un inmueble para rentar el inmueble.|5|
|6|US-10|Listar publicaciones|Como arrendador quiero administrar mis publicaciones para tener organizado mi lista de publicaciones.|5|
|7|US-08|Visualizar arrendatario|Como arrendador quiero visualizar a mis clientes en la aplicación para tener la información organizada de cada uno de ellos.|5|
|8|US-22|Listar propiedades|Como arrendador, quiero poder listar mis propiedades en la plataforma para que los arrendatarios puedan verlas y alquilarlas.|5|
|9|US-11|Calificar al arrendador|Como usuario quiero calificar el perfil del arrendador para que sirva de referencia a otros usuarios.|5|
|10|US-21|Diseñar la interfaz de usuario|Como desarrollador quiero diseñar una interfaz de usuario atractiva y fácil de usar para una experiencia agradable.|5|
|11|US-25|Dejar comentarios sobre propiedades|Como arrendatario, quiero poder dejar comentarios sobre las propiedades que he alquilado para compartir mi experiencia con otros usuarios.|3|
|12|US-24|Leer comentarios sobre propiedades|Como arrendatario, quiero poder leer comentarios de otros usuarios sobre las propiedades para tener una idea de las experiencias de otros inquilinos.|3|
|13|US-26|Responder comentarios sobre propiedades|Como arrendador, quiero poder responder a los comentarios dejados en mis propiedades para aclarar cualquier duda o inquietud que puedan tener los arrendatarios.|3|
|14|US-27|Participar en el foro|Como arrendador o arrendatario, quiero poder participar en un foro para hacer preguntas y compartir información con otros usuarios de la plataforma.|3|
|15|US-23|Actualizar información de las propiedades|Como arrendador, quiero poder actualizar la información de mis propiedades en cualquier momento para mantenerla actualizada y precisa.|3|
|16|US-13|Crear mi perfil en la aplicación|Como usuario de la aplicación quiero crear mi cuenta para acceder a todos los servicios de la aplicación|3|
|17|US-18|Funcionalidad de búsqueda avanzada|Como desarrollador, quiero desarrollar la funcionalidad de búsqueda avanzada con filtros.|3|
|18|US-14|Gestionar plan de suscripción|Como startup, quiero que mis usuarios tengan un plan de suscripción para generar ganancias y poder realizar un buen mantenimiento de la aplicación.|3|
|19|US-17|Sistema de autentificación y registro|Como desarrollador quiero implementar un sistema de autenticación y registro.|3|
|20|US-15|Promocionar una publicación|Como arrendador quiero promocionar mi publicación y que este se vea al inicio de la lista para que más personas lo vean|3|
|21|US-01|Visualizar una landing page clara y atractiva|Como visitante, quiero ver una landing page clara y atractiva para que pueda entender rápidamente el propósito de la aplicación web.|3|
|22|US-02|Visualizar una sección sobre nosotros|Como visitante, quiero ver una sección en el landing page que me informe sobre el startup para saber el propósito y con quiénes estoy tratando al momento de usar su aplicación web.|3|
|23|US-03|Visualizar contenido relevante de la landing page|Como usuario, quiero que la landing page tenga contenido relevante para que pueda tomar una decisión informada.|3|
|24|US-05|Desplegar la landing page |Como startup, quiero desplegar una landing page para informar sobre nuestra aplicación.|3|
|25|US-04|Acceder desde cualquier dispositivo a la landing page|Como usuario, quiero que la landing page sea accesible desde diferentes dispositivos para que pueda acceder al sitio web desde cualquier lugar.|2|
|26|US-16|Configurar la base de datos|Como desarrollador, quiero configurar una base de datos para almacenar información de usuarios y propiedades.|2|
|27|US-20|Optimizar el rendimiento de la aplicación|Como desarrollador, quiero optimizar el rendimiento de la aplicación para una experiencia rápida y fluida.|2|


<a name="_toc131683607"></a><a name="_toc145263612"></a>4
|<p>43</p><p>![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 001](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/590c048b-96d9-4081-bb69-eaaa58767a35)</p>|
| :- |
CHAPTER
1. # ![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 002](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/26246e51-be7d-4214-926f-7565e7204b79)**CAPÍTULO IV: PRODUCT DESIGN** 


1. ## <a name="_toc131679446"></a><a name="_toc131679537"></a><a name="_toc131682246"></a><a name="_toc131683608"></a><a name="_toc131683609"></a><a name="_toc145263613"></a>Style Guidelines
   1. ### <a name="_toc131683610"></a><a name="_toc145263614"></a>General Style Guidelines
Lenguaje:
El lenguaje que usaremos en nuestra aplicación es el lenguaje formal ya que queremos transmitirle al usuario seguridad y confianza en la información y recomendaciones que le brindemos.

Logo:
El logo de Rentstate se ha diseñado con los elementos que forman parte de la esencia de la aplicación. Está conformado por una silueta de una casa en la parte superior y el nombre de la aplicación en la parte inferior. Dado que nuestra Startup tiene el propósito de la renta de inmuebles.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 003](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/0b8ec074-9bf6-42a1-aaea-a9fc6545c23a)

Color:

Esta es la paleta de colores qué se usará en todo el diseño de la aplicación.

|<a name="_toc131683611"></a>064789|427AA1|<p>EBF2FA</p><p> </p>|
| - | - | - |
|002C3E|78BCC4|F7F8F3|

Web Style Guidelines

Typography:
La tipografía qué se usará es “RerossRectagular” la cuál es sencilla y de fácil de reconocer para que las personas puedan sentirse cómodas en la aplicación.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 004](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/b4a07983-d3f9-462d-87b9-ac94e860d96c)

Spacing:

El uso de los espacios es muy importante en la app ya que como utilizaremos letras grandes y entendibles, no trataremos de usar muchas palabras a la hora de utilizar la app.

1. ### <a name="_toc145263615"></a><a name="_toc131683612"></a>General Style Guidelines
Typography:
Para garantizar la comodidad del usuario al momento de navegar por la aplicación se hará un buen contraste del fondo con el tipo de letra que sea agradable a la vista y conoce al usuario y deje de usar la aplicación. También los espacios entre objetos serán amplios para que no se sature de información y solo se mostrará la necesaria. La fuente que usaremos será la de "RerossRectagular" ya que es una fuente que se adapta a cualquier diseño y además su forma geométrica lo hace agradable a la vista.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 005](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/31056b4b-5cf8-4d7a-94f2-283a9a1112ee)

Imágenes:
Pero para un óptimo funcionamiento de nuestra aplicación se decidió usar imágenes con una menor o igual 90 MB. Además, todas las imágenes deben ser de formato JPG debido a que este es el mejor formato para conservar la información y calidad de una imagen.

Patrón de Diseño web:
Para el diseño de la interfaz decidimos usar el patrón de diseño F, porque es un patrón muy conocido y fácil de leer la información ya que el usuario no tendrá nada especial que hacer y todo será natural para él. La forma de presentar la información con este patrón será de arriba hacia abajo y de izquierda a derecha.


1. ## <a name="_toc145263616"></a>Information Architecture
   1. ### <a name="_toc131683613"></a><a name="_toc145263617"></a>Organizations Systems
A continuación, explicaremos en qué grupos de información se aplicaron los distintos tipos de organización visual para ambos segmentos objetivo, así como también en cuales se utiliza algún tipo de categorización.

Jerárquica:

·   	**Lista de inmuebles en renta:** El arrendatario podrá ver una lista de todos los inmuebles en renta, cuando una de las publicaciones le interese este podrá agendar una cita con el dueño para ir a ver el estado del cuarto y si le gusta y está de acuerdo con el precio de renta entonces decidirá si lo alquila o no.

·   	**Resumen del contrato:** Si el arrendatario decide rentar el inmueble entonces el arrendador deberá completar un formulario qué resumirá los puntos más importantes del contrato como pueden ser, fechas de pago, monto a pagar, fecha de vencimiento del contrato, etc.

·   	**Recordar las fechas de pago:** Nuestra aplicación le notificará al arrendatario cuando se acerque la fecha de pago para qué tome precauciones y pueda cumplir con el pago a tiempo.

·   	**Historial de usuarios:** Cada usuario tendrá un historial de todos los lugares en los qué esté hospedado y también sobre cómo se desempeñó como arrendatario, si pago sin retrasos, si es una persona problemática o no, etc.

·   	**Mis Chats:** Los usuarios podrán comunicarse entre sí a través de la aplicación. Esto es necesario y facilitará la comunicación entre el arrendatario y el arrendador. Ya qué, asi podrán coordinar y agendar la cita.


1. ### <a name="_toc131683614"></a><a name="_toc145263618"></a>Labeling Systems
Los sistemas de etiquetado generalmente se refieren a sistemas o procesos utilizados para etiquetar o marcar productos, paquetes o contenedores con información relevante, como ingredientes, instrucciones de procesamiento, advertencias de materiales peligrosos, etc. El propósito de los sistemas de etiquetado es garantizar que los productos se identifiquen y etiqueten con precisión de acuerdo con los estándares legales y de la industria, lo que también puede ayudar en la trazabilidad, el control de inventario y la seguridad del consumidor.

|Ícono|Descripción|
| - | - |
|![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 006](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/7577e23b-dee6-4bba-ac6c-cdef9e54c938)|<p>“Bocina”</p><p>Silenciar aplicación: Al presionar el botón con este ícono permite silenciar la aplicación, por lo que no hará ningún sonido. Para volver a escuchar la aplicación se debe volver a presionar el botón.</p>|
|![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 007](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/e72b6625-e09a-40bd-be77-0339b605ab5c)|<p>“Notificaciones”</p><p>Notificaciones: Icono qué servirá para qué el usuario pueda identificar cuando tiene una nueva notificación</p>|
|![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 008](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/16b71447-23fb-4331-9f1a-3a1e9273fb98)|<p>“Perfil”</p><p>Perfil: Al presionar el botón con este ícono permite ingresar al perfil para poder ver o modificar el nombre, datos, viajes realizados, etc.</p>|
|![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 009](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/40fe55dd-0432-4a4d-844f-d2de9d6fd43b)|<p>“Configuración”</p><p>Configuración: Al presionar el botón con este ícono permite configurar diversos aspectos de la aplicación como tamaño del mapa, tamaño de letra, volumen de sonido, idioma, sugerencias, etc.</p>|


1. ### <a name="_toc131683615"></a><a name="_toc145263619"></a>SEO tags and Meta Tags
A continuación, se mostrarán los Seo Tags y Meta Tags utilizados en el Landing Page y Web Applications con el propósito de aumentar su visibilidad en los diferentes motores de búsqueda.

1. ### <a name="_toc145263620"></a><a name="_toc131683616"></a>Searching Systems 
A continuación, se mostrarán los sistemas de búsqueda implementados para ayudar a nuestros usuarios a encontrar la información que están buscando. Para el Landing Page, los sistemas de búsqueda son estáticos, ya que la barra de navegación llevará a los usuarios a la sección en la que estén interesados. 


1. ## <a name="_toc131683618"></a><a name="_toc145263621"></a>Landing Page UI Design
   1. ### <a name="_toc145263622"></a>Landing Page Wireframe
En esta Sección, se presentará el diseño del sitio web de nuestro desarrollo de software. Para brindar una mejor idea del contenido que se mostrará en la plataforma. El Landing Page es del tamaño adecuado para las pantallas de los ordenadores, así se mostrará la información centrada y será fácilmente visible para los usuarios. Asimismo, se evidencia una barra de navegación estática que facilitará la navegación del usuario, y así brindar la mejor experiencia.   

**Menú principal** de la plataforma: Opciones de navegación

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 010](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/57d567c7-8624-4e68-ae03-16a674ce1652)


**About us:** Es una sección del menú principal

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 011](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/ac69a8ae-daee-485e-a9c9-4c2db621b25a)

**Categorias:** Es una sección del menú principal

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 012](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/d2b0c455-a6a0-404e-980e-638bbd405910)

**Footer:**

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 013](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/669a6775-a59b-4127-a709-7412b94fbadd)

Link:<https://www.figma.com/file/jQIqlL0sXCpWKGhqa9RHw1/OpenSource---Wireframes?node-id=0%3A1&t=PZFjfsIpIwBiQKEP-1>6


1. ### <a name="_toc131683620"></a><a name="_toc145263623"></a>Landing Page Mock-up
Se presentará la vista preliminar del sitio web, se va a detallar el contenido por secciones, los colores, estilos e imágenes que son coherentes con el propósito y así facilitar al usuario una mejor experiencia con el sitio web y que pueda entender fácilmente el objetivo del sitio web.

**Menú de la plataforma:** Se muestran las principales opciones que permitirán al usuario conocer más de los servicios de la plataforma.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 014](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/3c03a5b0-c862-4808-9225-71667150783c)

**About us:** Es una opción de la barra de herramientas del menú principal, donde se da a conocer el propósito de la plataforma.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 015](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/3868d1ec-4d4d-4f68-8b3e-d5508b514ce2)

- **Categorías:** Es una opción de la barra de herramientas del menú principal, donde se especifica las categorías a las que el usuario podrá encontrar en la plataforma. 

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 016](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/ff7425ef-dc91-4759-9bed-f2c86295bd3b)

- **Suscripción:** 

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 017](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/cb48b114-6ece-494f-8799-0c4226c85bba)

- Footer: 

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 018](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/adb15762-088f-4e8d-a2cd-d8c09d6caed1)

<a name="_toc131683621"></a>Página desplegada: <https://tiempoapurado-grupo.github.io/ProyectLandingPage/> 
**

1. ## <a name="_toc145263624"></a>Web Applications UX/UI Design
   1. ### <a name="_toc131683622"></a><a name="_toc145263625"></a>Web Applications Wireframes
Los wireframes son representaciones visuales de baja fidelidad que muestran la estructura y disposición de los elementos en una aplicación web. Se pueden incluir los elementos principales de la aplicación, como la página de inicio, la búsqueda de propiedades, la visualización de detalles de la propiedad, el formulario de reserva, etc. Estos wireframes ayudan a definir la arquitectura de la información y la navegación de la aplicación, así como la ubicación y disposición de los diferentes elementos en cada pantalla.

Link: <https://www.figma.com/file/mpa7yzaz0TfmwIkF3tWUUb/WIREFRAMES-MOCKUPS-RENTSTATE?type=design&node-id=264%3A2&mode=design&t=UbqEmTeOufyTGYof-1> 

**Sección Login:**

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 019](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/7b024a1c-46ab-4d34-ba16-ac965bbda45d)

**Sección bienvenida y perfil:**

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 020](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/3b45d0f9-e64c-4a6d-99a7-d7ae30290434)

**Sección mensajes:**

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 021](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/c506dfd5-ba2c-4c70-b5cc-17d94dd86819)

**Sección publicaciones:**

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 022](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/d021abf1-16cf-40c1-93c5-262c5df3b0cc)

**Sección registro de propiedad y publicación:**

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 023](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/2f84900c-bd9a-485b-ad51-2f496e2edf8e)

**Sección Foro:**

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 024](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/0e1dd2b6-1cbe-40b3-838e-0a51414a50c9)

**Sección tablas de propiedades, clientes y reservas:**

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 025](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/68a5574b-94b7-4311-86c3-9ab68e648c32)


1. ### <a name="_toc131683623"></a><a name="_toc145263626"></a>Web Applications Wireflow Diagrams
***User Goal:*** Como usuario quiero registrarme fácilmente a Renstate 

***Descripción:*** En el siguiente Wireflow, se evidencia el flujo que seguirá el usuario para poder registrarse. Selecciona el únete del menú principal y completa los campos para poder registrarse correctamente.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 026](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/b75c5994-8aae-4630-a77f-e59972ecdfea)

***User Goal:*** Como usuario quiero iniciar sesión rápidamente 

***Descripción:*** En el siguiente Wireflow, se evidencia el flujo que seguirá el usuario para iniciar sesión. Selecciona Login del menú principal, ingresa correo y contraseña para ingresar a Renstate.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 027](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/d16bb82b-c3eb-4c11-99b4-dfbf87a6e04e)

***User Goal:*** Como arrendatario quiero recuperar mi cuenta en caso olvide mi contraseña 


***User Goal:*** Como arrendatario quiero realizar cambios a mi perfil registrado

***Descripción:*** En el siguiente Wireflow, se evidencia el flujo que seguirá el usuario para realizar cambios a su perfil. Selecciona ícono perfil, redireccionará a la pantalla de editar perfil y realizar los cambios que se desee como personal Email o Age, que una vez conforme al seleccionar “Save” se guardaran las modificaciones

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 028](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/077d0f85-45e9-400e-a472-faf17241ce60)

***User Goal:*** Como usuario quiero encontrar un inmueble acorde a mis necesidades

***Descripción:*** En los siguientes Wireflows, se mostrará la forma de realizar una búsqueda de inmueble

Primero, selecciona las categorías del menú principal que redireccionará a la pantalla de publicaciones que sean específicamente de la categoría seleccionada. Finalmente, la publicación seleccionada se despliega y muestra los detalles.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 029](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/cd86140a-4bf2-4f14-a74b-29d94021dbb0)

***User Goal:*** Como usuario quiero reservar el inmueble

***Descripción:*** En el siguiente Wireflow, se evidencia el flujo para reservar una visita al inmueble. Desplegar el anuncio seleccionado, en la sección de Schedule seleccionar el horario de visita y completar los campos de información para enviar la solicitud de visita.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 030](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/c7f5ad30-0447-4c02-8923-c3e26920c344)

***User Goal:*** Como arrendatario quiero reservar un inmueble

***Descripción:*** En el siguiente Wireflow, se evidencia el flujo para calificar a algún usuario que haya realizado una publicación de algún inmueble. Desplegar el anuncio seleccionado, en la sección de Schedule seleccionar el horario de visita y completar los campos de información para enviar la solicitud de visita.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 031](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/eaab9ffc-4e53-4b46-b004-7542ed33b56d)

***User Goal:*** Como usuario quiero registrar, editar y visualizar una tabla de cliente

***Descripción:*** En los siguientes Wireflows, se evidencian los flujos que seguirá el usuario para visualizar a sus clientes.
Al desplegar la opción My tenants del Menú: 
Seleccionar la opción “See your clientes”, se podrá visualizar la tabla con los clientes con los iconos para poder modificar.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 032](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/99aa56f6-b36c-4fb0-8aa4-c8ff9ff4d206)

***User Goal:*** Como usuario quiero registrar, editar y visualizar mis propiedades

***Descripción:*** En los siguientes Wireflows, se evidencian los flujos que seguirá el usuario para visualizar a sus propiedades, registrar y editar información de la propiedad.
Seleccionar la opción de “See your post”, se podrá observar la tabla de publicaciones, donde se podrá agregar la información de un nuevo inmueble completando todos los campos del formulario.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 033](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/f1ad6ce4-3511-4c29-8df1-d6536e853198)

***User Goal:*** Como usuario quiero recibir y enviar mensajes

***Descripción:*** En los siguientes Wireflows, se mostrará los flujos que seguirá el usuario para enviar mensajes cuando selecciones.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 034](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/c32055db-16e4-4631-a128-47e74a16b717)

***User Goal:*** Como usuario quiero poder realizar consultas en el foro

***Descripción:*** En los siguientes Wireflows, se mostrará los flujos que seguirá el usuario para hacer usuario del foro

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 035](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/2bd2c98c-e17c-48ee-a71d-4c88b25e23bc)


Link Antiguo: <https://lucid.app/lucidspark/12be4b14-371a-45b6-be51-62cafeba966e/edit?viewport_loc=-1171%2C-3689%2C1821%2C884%2C0_0&invitationId=inv_0336407e-089f-4e81-971f-c455cce49dec>


1. ### <a name="_toc131683624"></a><a name="_toc145263627"></a>Web Applications Mock-ups
En el proceso de desarrollo de una aplicación web, los mockups son una herramienta fundamental. Estos son diseños estáticos que representan la interfaz de usuario de la aplicación antes de que se implemente completamente. Los mockups permiten visualizar cómo se verá y funcionará la aplicación final, sin necesidad de escribir código.

Link: <https://www.figma.com/file/mpa7yzaz0TfmwIkF3tWUUb/WIREFRAMES-MOCKUPS-RENTSTATE?type=design&node-id=0%3A1&mode=design&t=UbqEmTeOufyTGYof-1>

**Sección Login:**


![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 036](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/b665ef23-c204-43fd-aa2d-c0df3f532ad7)

**Sección Bienvenida y Perfil:**
![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 037](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/afe06f67-af30-468a-bb0f-06aed01c2e85)

**Sección mensajes:**
![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 038](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/fdbb1bc4-f430-4ce7-8473-b7d3f8d38ff4)

**Sección publicaciones:**
![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 039](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/6b71b635-70a1-4737-8862-05028a5f8283)

**Sección registro de propiedad y publicación:**
![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 040](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/437eb0b3-fd8f-433f-b7b1-4bd53c831a19)

**Sección Foro:**
![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 041](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/21bc153c-7d7a-492c-b8e3-b81dc4dadd63)

**Sección tablas de propiedades, clientes y reservaciones:**
![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 042](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/72127e5e-ad2e-4493-bf3a-fe63cf31db0b)

<a name="_toc131683625"></a>Web Applications User Flow Diagrams

Segmento: Arrendatarios

***User Goal:*** Como arrendatario quiero registrarme fácilmente a Renstate 

***Descripción:*** En el siguiente Wireflow, se evidencia el flujo que seguirá el arrendatario para poder registrarse. Selecciona Register del menú principal, completa los campos y especifica el tipo de usuario para poder registrarse correctamente.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 043](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/aa75819d-ce82-4965-a4cd-daafb199f1bb)

***User Goal:*** Como arrendatario quiero iniciar sesión rápidamente 

***Descripción:*** En el siguiente Wireflow, se evidencia el flujo que seguirá el arrendatario para iniciar sesión. Selecciona Login del menú principal, ingresa correo y contraseña para ingresar a Renstate.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 044](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/10d3f405-15ca-4188-8cb4-36bd7323607b)

***User Goal:*** Como arrendatario quiero recuperar mi cuenta en caso olvide mi contraseña 

***Descripción:*** En el siguiente Wireflow, se evidencia el flujo que seguirá el arrendatario para poder recuperar su cuenta. Selecciona la opción de forgot your password, redireccionará a la pantalla de recuperar cuenta donde ingresará email y nueva contraseña. ![Interfaz de usuario gráfica, Sitio web

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 045](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/babcb24c-62b0-43b3-9703-f5c30941bdc8)

***User Goal:*** Como arrendatario quiero realizar cambios a mi perfil registrado

***Descripción:*** En el siguiente Wireflow, se evidencia el flujo que seguirá el arrendatario para realizar cambios a su perfil. Selecciona ícono perfil, redireccionará a la pantalla de editar perfil y realizar los cambios que se desee como personal information o change password, que una vez conforme “save changes” al seleccionar ícono casa podrá regresar a la pantalla principal del segmento en caso de eliminar la cuenta “delete account” regresará a la pantalla principal de la plataforma.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 046](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/c924f965-b7b6-4952-8c4d-ed3ed8b6c004)

***User Goal:*** Como arrendatario quiero encontrar un inmueble acorde a mis necesidades

***Descripción:*** En los siguientes Wireflows, se mostrarán las diferentes formas de realizar búsquedas. 
Selecciona las categorías del menú principal que redireccionará a la pantalla de anuncios que sean específicamente de la categoría seleccionada y luego selecciona el anuncio con el ícono de desplegar. Finalmente, el anuncio seleccionado se despliega y muestra la descripción del anuncio.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 047](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/31bdac9c-852b-4efd-acba-73a1e283d3c4)

***User Goal:*** Como arrendatario quiero recibir y enviar mensajes.

***Descripción:*** En el siguiente Wireflow, se envidencia como el arrendatario va a poder enviar mensaje con el arrendador o con otro arrendatario para que pueda cotizar precios de acuerdo con el lugar, reservas, etc.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 048](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/2645e1eb-4159-467c-87e0-1386477622c6)

***User Goal:*** Como arrendatario quiero reservar una cita al inmueble

***Descripción:*** En el siguiente Wireflow, se evidencia el flujo para reservar una visita al inmueble. Desplegar el anuncio seleccionado, en la sección de Schedule seleccionar el horario de visita y completar los campos de información para enviar la solicitud de visita.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 049](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/82a4ce18-ee7d-4b8c-a05f-d54c48ee88b7)

***User Goal:*** Como arrendatario quiero calificar al arrendador

***Descripción:*** En el siguiente Wireflow, se evidencia el flujo para calificar al arrendador. Selecciona ícono del perfil del arrendador, agrega comentarios, calificación y Save para que se visualice la calificación.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 050](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/585f736f-3343-4a7f-8a26-1352c8678258)

***User Goal:*** Como arrendatario quiero tener acceso a un foro de consultas y/o comentarios

***Descripción:*** En el siguiente Wireflow, se evidencia el flujo para visualizar foro, dónde el arrendatario puede ver los foros de los arrendadores y responder la cadena de foro o realizar una de cadena.  

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 051](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/43bf8e00-a403-467f-892a-95a8346667d8)

Segmento: Arrendador

***User Goal:*** Como arrendador quiero registrarme fácilmente a Renstate 

***Descripción:*** En los siguientes Wireflows, se mostrará las formas de poder registrase
Primero, el flujo que seguirá el arrendador para poder registrarse al seleccionar Register del menú principal, se completa los campos y especifica el tipo de usuario para poder registrarse correctamente.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 052](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/a32165c3-ad10-4366-816a-7288fb00ca1d)

Segundo, el flujo que seguirá el arrendador al seleccionar un plan de suscripción de la pantalla principal de la plataforma se registra al completar todos los campos y especificar el tipo de usuario seleccionar Continue, será redireccionado a la pantalla de información de los bancos autorizados para realizar el pago, al momento de realizar el pago se registrará correctamente.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 053](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/53847c71-7af8-4a6c-964e-54556313fb44)

***User Goal:*** Como arrendador quiero iniciar sesión rápidamente 

***Descripción:*** En el siguiente Wireflow, se evidencia el flujo que seguirá el arrendador para iniciar sesión. Selecciona Login del menú principal de la plataforma, ingresa correo y contraseña para ingresar a Renstate.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 054](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/981fc273-54fa-4b8b-9089-b6e3ab2f6d72)

***User Goal:*** Como arrendador quiero recuperar mi cuenta en caso olvide mi contraseña 

***Descripción:*** En el siguiente Wireflow, se evidencia el flujo que seguirá el arrendador para poder recuperar su cuenta. Selecciona la opción de forgot your password, redireccionará a la pantalla de recuperar cuenta donde ingresará email y nueva contraseña. 

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 055](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/63af707d-61e4-46a1-b271-85edc28eeca6)

***User Goal:*** Como arrendador quiero realizar cambios a mi perfil registrado

***Descripción:*** En el siguiente Wireflow, se evidencia el flujo que seguirá el arrendador para realizar cambios a su perfil. Selecciona ícono perfil, redireccionará a la pantalla de editar perfil y realizar los cambios que se desee como personal information o change password, que una vez conforme “save changes” al seleccionar ícono casa podrá regresar a la pantalla principal del segmento en caso de eliminar la cuenta “delete account” regresará a la pantalla principal de la plataforma.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 056](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/5e8410cf-9bd5-4d82-826b-aa0323231f6d)

***User Goal:*** Como arrendador quiero visualizar mis anuncios según categoría

***Descripción:*** En el siguiente Wireflow, se evidencia el flujo que seguirá el arrendador para visualizar sus anuncios según categoría. Al seleccionar la opción Advertisement del Menú, se desplegará las categorías, al seleccionar una categoría en específico podrá visualizar los anuncios que realizó según donde corresponda dicho anuncio por categoría.  

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 057](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/1646bda3-ac91-4aab-b663-2343da71fc0d)

***User Goal:*** Como arrendador quiero registrar, editar y visualizar mis propiedades

***Descripción:*** En los siguientes Wireflows, se evidencian los flujos que seguirá el arrendador para visualizar a sus propiedades, registrar y editar información de la propiedad.
Al desplegar la opción My properties del Menú: 
Seleccionar la opción add property para registrar propiedad, Completar formulario, luego agregar con ícono más para registrar correctamente la propiedad a la lista de propiedades de la opción My properties del menú de despliegue y acceder a sus herramientas como ícono editar para actualizar información relevante de la propiedad. 

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 058](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/7f6f2fc2-a370-42b5-9854-77f3956c0ea2)

***User Goal:*** Como arrendatario quiero calificar al arrendatario

***Descripción:*** En el siguiente Wireflow, se evidencia el flujo para calificar al arrendatario. Desplegar la opción My tenants del menú de despliegue, seleccionar cliente, agregar calificación y comentarios. Por último, Save para guardar los cambios.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 059](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/50abcb4a-53f6-411f-b2ac-8c5343b754df)

***User Goal:*** Como arrendador quiero recibir y enviar mensajes

***Descripción:*** En los siguientes Wireflows, se mostrará los flujos que seguirá el arrendador para visualizar y enviar mensajes.
Debes seleccionar el icono de mensaje para poder acceder a la mensajería, ya sea para poder revisar tus mensajes o enviar un mensaje a un amigo arrendador o a un arrendatario.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 060](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/fb533f5f-eeff-4216-8843-5816580c3a39)

***User Goal:*** Como arrendador quiero tener acceso al foro de consultas.

***Descripción:*** En el Wireflow presentado, se muestra el proceso para acceder al foro, donde el arrendatario puede ver los foros creados por los arrendadores y responder a una cadena de discusión o iniciar una nueva.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 061](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/f99f77c2-6b1b-4ca5-98e4-10dd53a019c1)

Link:<https://lucid.app/lucidspark/74e64788-64ea-465b-acf8-2c09f5c5f6d7/edit?viewport_loc=-1766%2C3542%2C6503%2C3156%2C0_0&invitationId=inv_b5ed2be4-a127-4797-9196-83cb0bcf7b3c>

1. ## <a name="_toc145263628"></a>Web Applications Prototyping

El diseño de aplicaciones web es un proceso esencial para garantizar una experiencia de usuario fluida y atractiva. Para la aplicación debe ser importante crear una interfaz intuitiva y visualmente atractiva que facilite la búsqueda y reserva de propiedades.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 062](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/17c5fad2-c14e-4306-b84f-299e64872e08)

**Link: <https://www.figma.com/file/mpa7yzaz0TfmwIkF3tWUUb/WIREFRAMES-MOCKUPS-RENTSTATE?type=design&node-id=0%3A1&mode=design&t=bHvnqsSE2LUdVd6I-1>** 


1. ## <a name="_toc131683627"></a><a name="_toc145263629"></a>Domain-Driven Software Architecture
   1. ### <a name="_toc131683628"></a><a name="_toc145263630"></a>Software Architecture Context Diagram
Un diagrama de contexto de arquitectura de software es una representación visual de un sistema de software que muestra su entorno externo y las interacciones del sistema con entidades externas como usuarios, otros sistemas y dispositivos. Proporciona una visión general de todo el sistema centrándose en el contexto del sistema y las partes interesadas.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 063](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/17383256-d449-4b29-bc1b-b94a7b86058e)

1. ### <a name="_toc131683629"></a><a name="_toc145263631"></a>Software Architecture Container Diagrams
Los diagramas de contenedores de arquitectura de software son un tipo de diagrama que se utiliza para representar la arquitectura de alto nivel de un sistema de software al mostrar las relaciones entre los diversos contenedores que componen el sistema. Los contenedores pueden considerarse entornos de tiempo de ejecución que encapsulan y aíslan un conjunto de componentes y dependencias de software, como un servidor web, un servicio de base de datos o un servidor de aplicaciones. 

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 064](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/7361e47e-f8b0-433e-8e09-c06bab12078e)


1. ### <a name="_toc131683630"></a><a name="_toc145263632"></a>Software Architecture Components Diagrams
Un diagrama de componentes de arquitectura de software (SACD) es un tipo de diagrama que proporciona una descripción general de los componentes de un sistema de software y cómo interactúan entre sí para formar el sistema general. El diagrama normalmente incluye componentes como módulos, bibliotecas y servicios, así como las interfaces y dependencias entre estos componentes. Los SACD se utilizan a menudo como una herramienta para el diseño y la documentación de la arquitectura de software.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 065](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/e851739c-643c-43cc-a831-641bf091409f)

1. ## <a name="_toc131683631"></a><a name="_toc145263633"></a>Software Object-Oriented Design
   1. ### <a name="_toc131683632"></a><a name="_toc145263634"></a>Class Diagrams

Para el diagrama de clase se identificó todos los modelos abstractos que se utilizará para el desarrollo de nuestra aplicación, así como también fue necesario identificar bien el tipo de relación que existe entre ellas.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 066](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/45a6e047-42b7-4de3-bf03-380f4471f4d4)

*Diagrama de clase*


1. ### <a name="_toc131683633"></a><a name="_toc145263635"></a>Class Dictionary

<table><tr><th colspan="1">N</th><th colspan="1">Entidad</th><th colspan="1">Nombre de Atributos</th><th colspan="1">Definición</th><th colspan="2">Tipo de Dato</th><th colspan="2">Rango</th><th colspan="2">Unidad de Medida</th><th colspan="2">Valores Restringidos</th></tr>
<tr><td colspan="1" rowspan="8" valign="top">1</td><td colspan="1" rowspan="8" valign="top">User</td><td colspan="1" rowspan="3" valign="top">id</td><td colspan="2" rowspan="3" valign="top">Es un identificador único que nos permitirá obtener toda su información</td><td colspan="2" valign="top">Long</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top">Valores negativos</td></tr>
<tr><td colspan="2" rowspan="2"></td><td colspan="2" rowspan="2"></td><td colspan="2" rowspan="2"></td><td colspan="2" rowspan="2"></td><td colspan="1"></td></tr>
<tr><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">name</td><td colspan="1" valign="top">Aquí se guarda el nombre del usuario</td><td colspan="2" valign="top">String</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top">Caracteres especiales</td><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">age</td><td colspan="1" valign="top">Se guarda la edad del usuario</td><td colspan="2" valign="top">Integer</td><td colspan="2"></td><td colspan="2">Años</td><td colspan="2" valign="top">Valores menores a 18</td><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">gender</td><td colspan="1" valign="top">Se guarda la edad del usuario</td><td colspan="2" valign="top">String</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top">Caracteres especiales</td><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">isPremium</td><td colspan="1" valign="top">Nos permite saber si el usuario cuenta con privilegios.</td><td colspan="2" valign="top">Bool</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top"></td><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">rankPoints</td><td colspan="1" valign="top">Es la calificación promedio que ha recibido el usuario</td><td colspan="2" valign="top">Integer</td><td colspan="2">1 a 5</td><td colspan="2">puntos</td><td colspan="2" valign="top">Valores menores a 1 y mayores a 5</td><td colspan="1"></td></tr>
<tr><td colspan="1" rowspan="7" valign="top">2</td><td colspan="1" rowspan="7" valign="top">Property</td><td colspan="1" valign="top">id</td><td colspan="1" valign="top">Es identificador único que nos permitirá obtener toda su información</td><td colspan="2" valign="top">Long</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top">Valores negativos</td><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">owner_id</td><td colspan="1" valign="top">Es identificador del dueño de dicha publicación</td><td colspan="2" valign="top">Long</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top">Valores negativos</td><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">name</td><td colspan="1" valign="top">Es el nombre de la propiedad para que el dueño la identifique</td><td colspan="2" valign="top">String</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top">Caracteres especiales</td><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">location</td><td colspan="1" valign="top">Lugar donde está ubicado la propiedad</td><td colspan="2" valign="top">String</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top">Caracteres especiales</td><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">category</td><td colspan="1" valign="top">categoría a la que pertenece la propiedad</td><td colspan="2" valign="top">String</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top">Caracteres especiales</td><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">available</td><td colspan="1" valign="top">Muestra si está disponible o alquilada.</td><td colspan="2" valign="top">Bool</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top"></td><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">renter_id</td><td colspan="1" valign="top">Es identificador que nos permite conocer los datos del usuario que rento la propiedad</td><td colspan="2" valign="top">Long</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top">Valores negativos</td><td colspan="1"></td></tr>
<tr><td colspan="1" rowspan="4" valign="top">3</td><td colspan="1" rowspan="4" valign="top">Post</td><td colspan="1" valign="top">` `id</td><td colspan="1" valign="top">Es identificador único que nos permite obtener toda su información</td><td colspan="2" valign="top">Long</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top">Valores negativos</td><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">property_id</td><td colspan="1" valign="top">Identificador que permite obtener los datos de la propiedad</td><td colspan="2" valign="top">Long</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top">Valores negativos</td><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">title</td><td colspan="1" valign="top">Título de la publicación que se mostrara a los usuarios </td><td colspan="2" valign="top">String</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top">Caracteres especiales</td><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">price</td><td colspan="1" valign="top">precio de renta de la habitación</td><td colspan="2" valign="top">Float</td><td colspan="2"></td><td colspan="2">Soles </td><td colspan="2" valign="top">Caracteres especiales</td><td colspan="1"></td></tr>
<tr><td colspan="1" rowspan="5" valign="top">4</td><td colspan="1" rowspan="5" valign="top">Message</td><td colspan="1" valign="top">id</td><td colspan="1" valign="top">Identificador que permite obtener la información de cada mensaje</td><td colspan="2" valign="top">Long</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top">Valores negativos</td><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">author_id</td><td colspan="1" valign="top">Identificador que permite obtener información del autor</td><td colspan="2" valign="top">Long</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top">Valores negativos</td><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">content</td><td colspan="1" valign="top">Contenido de mensaje</td><td colspan="2" valign="top">String</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top">Caracteres especiales</td><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">recipient_id</td><td colspan="1" valign="top">Identificador que permite obtener la informacion del usuario destino</td><td colspan="2" valign="top">Long</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top">Valores negativos</td><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">isOpen</td><td colspan="1" valign="top">Indica si el mensaje ha sido leído o no</td><td colspan="2" valign="top">Bool</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top"> </td><td colspan="1"></td></tr>
<tr><td colspan="1" rowspan="3" valign="top">5</td><td colspan="1" rowspan="3" valign="top">Account</td><td colspan="1" valign="top">user_id</td><td colspan="1" valign="top">Identificador que nos permite saber la cuanta a la que pertenecen estas credenciales</td><td colspan="2" valign="top">Long</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top">Valores negativos</td><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">email</td><td colspan="1" valign="top">Email único de la cuenta</td><td colspan="2" valign="top">String</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top"></td><td colspan="1"></td></tr>
<tr><td colspan="1" valign="top">password</td><td colspan="1" valign="top">Contraseña de la cuenta</td><td colspan="2" valign="top">String</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" valign="top"></td><td colspan="1"></td></tr>
</table>


1. ## <a name="_toc131683634"></a><a name="_toc145263636"></a>Database Design
   1. ### <a name="_toc131683635"></a><a name="_toc145263637"></a>Database Diagram
Para el diseño de la base de datos se ha identificado 9 entidades las cuales se describen de la siguiente manera

- **Users:** Aquí se registran los datos de usuarios como nombre, edad, genero, etc.
- **Accounts:** Aquí se registra información sensible como con el correo y la contraseña.
- Properties: Aquí se guarda toda información básica e importante de un inmueble.
- **Reservations:** Aquí se guarda la información de los usuarios que reservaron una propiedad.
- **Posts:** Aquí se guarda la información de las publicaciones que hacen los arrendadores como precio y detalles a tener en cuenta cuando se reserve la propiedad.
- **Comments:** Aquí se guarda la información de los comentarios que recibe cada publicación y su respectivo autor.
- **Messages:** Aquí se guarda la información de los mensajes, tanto el contenido, autor y usuario al que va dirigido.
- **Forums:** Se guarda las consultas o dudas que los usuarios en general hagan en la aplicación.
- **Answers:** Se guardan todas las respuestas a cada uno de los foros.

![Aspose Words 121be8f5-2512-4026-b394-395baa5280e4 067](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/4545cb46-d41f-42be-8790-c3ca725df6d2)
*Diseño de la base de datos.*



**CAPÍTULO V: PRODUCT** 
# **IMPLEMENTATION, VALIDATION & DEPLOYMENT**

## <a name="_toc131679450"></a><a name="_toc131679541"></a><a name="_toc131682275"></a><a name="_toc131683637"></a><a name="_toc131683638"></a><a name="_toc145263639"></a>Software Configuration Management
5.1.1 ### <a name="_toc131683639"></a><a name="_toc145263640"></a>Software Development Environment Configuration
Project Management

Para gestionar los avances y poder coordinar los trabajos en tiempo real y de manera organizada, utilizamos muchas herramientas como:

- Google Drive:  Es un servicio de alojamiento y sincronización de archivos desarrollado por Google

![Google Drive](https://www.infobae.com/new-resizer/4gb71JcAfkXNjKSpqyjD75Ywc2M=/filters:format(webp):quality(85)/cloudfront-us-east-1.images.arcpublishing.com/infobae/IZ34LU4DDZFHNJEUIY2YZ72VFI.png)

- Documentos de Google: Es un procesador de texto en línea que se incluye como parte de la suite Google Docs Editors basada en la web de Google

  ![Google Docs](https://cloudfront-us-east-1.images.arcpublishing.com/infobae/JWRITYPDSJFGJF2PN47TFK3STI.png)

- Discord: Es un servicio de mensajería instantánea y chat de voz VolP. Funciona a través de servidores y está separado en canales de texto o de voz 

![Discord](https://cdn.sanity.io/images/kts928pd/production/3a8feb0e279d07a02c91451aebf4dba91263075a-1140x620.png)

- Git: Es un software de control de versiones diseñado por Linus Torvalds, pensando en la eficiencia

![Git](https://nodd3r.com/media/blog/Portadas_blog_21.png)

- Trello: Es un software de administración de proyectos con interfaz web y con cliente para iOS y android para organizar proyectos.

![Trello](https://i.pcmag.com/imagery/reviews/04C2m2ye5UfXyb5x5WWIsZ4-19..v1625759628.png)

Product UX/UI Design

Para esta parte utilizamos una herramienta muy conocida que es Uxpressia, para los As-Is y To-Be Scenarios Mapping, utilizamos plantillas detalladas en los enunciados del trabajo, para los diseños de landing page y web application, utilizamos Figma para hacer los Wireframes y Mock-ups.

- Uxpressia: Es una herramienta en línea para el mapeo de la trayectoria del cliente que crea mapas de impacto y personas

![Uxpressia](https://images.g2crowd.com/uploads/product/image/large_detail/large_detail_4d126824c327c773931faea0871f3bca/uxpressia.png)

- Figma: Es un editor de gráficos vectorial y una herramienta de generación de prototipos, principalmente basada en la web, con características off-line adicionales habilitadas por aplicaciones de escritorio en macOS y Windows. 

![Figma](https://www.bynder.com/imager/metaimage/1676016/meta-figma_1d7c0a086ec922a4f11c61b256f9b311.jpg)

Software Development

Para esta primera parte del trabajo, en el tema de desarrollo de software utilizamos las sgtes herramientas y lenguajes para el landing page.

- Webstorm: Proporciona una experiencia de desarrollo más inteligente y eficiente, automatizando el trabajo rutinario y ayudando a manejar tareas complejas con facilidad.

![WebStorm](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c0/WebStorm_Icon.svg/1200px-WebStorm_Icon.svg.png)

- GitHub: Es una plataforma de desarrollo colaborativo que nos permite alojar proyectos utilizando el sistema de control de versiones de git. Es propiedad de Microsoft y ofrece a los desarrolladores la posibilidad de crear repositorios de código y colaborar en proyectos con otros desarrolladores.

![GitHub](https://global-uploads.webflow.com/5f5a53e153805db840dae2db/64e79ca5aff2fb7295bfddf9_github-que-es.jpg)

- HTML: HypexText Markup Language, es un lenguaje de etiquetas para la creación de páginas web.

![HTML](https://cms.rootstack.com/sites/default/files/inline-images/23-237381_java-html-language-logo-png-transparent-png.png)

- CSS: Cascading Style Sheets o en español Hojas de Estilo en Cascada, es un lenguaje diseñado y utilizado para definir y modificar la apariencia de los documentos HTML y XML. Se utiliza mucho para el dar estilos a las páginas web a la mano de HTML.

![CSS](https://1000marcas.net/wp-content/uploads/2021/02/CSS-Logo.png)

5.1.2 ### <a name="_toc131683640"></a><a name="_toc145263641"></a>Source Code Management
Para todo el ciclo de vida de nuestro proyecto, utilizaremos el sistema de control de versiones Git, donde la evidencia será visualizada y registrada en la plataforma de GitHub de nuestra organización. Dentro de nuestra organización podrá visualizar todos los cambios y modificaciones hechos por cada miembro de nuestro equipo.

Github URL: <https://github.com/LogicMinds-Group>

|Alumno|Correo|Usuario de Github|
| :- | :- | :- |
|Edwin López|<U20201b051@upc.edu.pe>|<p>EdwinLopezz17</p><p><https://github.com/EdwinLopezz17> </p>|
|Leydi Mamani|<U20201b745@upc.edu.pe> |<p>Leydi-Aro</p><p><https://github.com/Leydi-Aro></p>|
|Julio Asillo|<U20201b482@upc.edu.pe>|<p>JulioAsillo</p><p><https://github.com/JulioAsillo></p>|
|Angie Ruiz|<U20201b293@upc.edu.pe>|<p>Angie-RC</p><p><https://github.com/Angie-RC> </p>|
|Jhan Antonio|U20201B32@upc.edu.pe |<p>` `Asjhanc </p><p>https://github.com/asjhanc </p>|


5.1.3 ### <a name="_toc131683641"></a><a name="_toc145263642"></a>Source Code Style Guide & Convention
Para esta parte del trabajo y futuros presentables, nos planteamos utilizar las convenciones descritas en la guía “HTML Style Guide and Coding Conventions”. Donde podemos encontrar convenciones como las siguientes:

- Declaración del tipo de documento en HTML.
- Declaraciones de nombres de elementos en minúsculas en HTML.
- Cerrar todos los elementos o secciones en HTML.
- Uso de atributos en minúsculas y valores en HTML.
- Utilizar comillas dobles para los valores de los atributos en HTML.

Estas convenciones nos ayudan a mantener una consistencia, flexibilidad y legibilidad de nuestro código HTML, además nos beneficiará para que otras personas puedan entender el código y poder darle mantenimiento.

5.1.4 ### <a name="_toc131683642"></a><a name="_toc145263643"></a>Software Deployment Configuration
Para desplegar nuestra landing page, utilizamos GitHub, donde se puede observar lo siguiente:

- Images: Se aloja las imágenes utilizadas en el landing page.
- Principal.css: Contiene los estilos que ayudaran a que el landing page se vea ordenado y atractivo.
- principal.html: Contiene la estructura del landing page por secciones.

Link del Repositorio: <https://github.com/LogicMinds-Group>


1. ## <a name="_toc131683643"></a><a name="_toc145263644"></a>Landing Page, Services & Applications Implementation
   1. ### <a name="_toc131683644"></a><a name="_toc145263645"></a>Sprint 1
En el primer sprint se implementó y desplegó la Landing Page.
1. #### Sprint Planning

El Sprint Planning es un evento o reunión que se realiza al inicio de cada Sprint en el marco de la metodología Scrum. Durante esta reunión, el equipo Scrum se reúne para planificar y definir la meta del Sprint, así como para discutir el backlog del producto y seleccionar los elementos de trabajo que se abordarán en el próximo Sprint. El equipo de desarrollo también define los elementos del backlog del sprint y crea un plan detallado para poder completarlos. La reunión suele durar unas pocas horas y participan todos los miembros del equipo Scrum, incluyendo el Scrum Master y el Product Owner. El objetivo principal del Sprint Planning es crear una visión clara y compartida de lo que se va a conseguir durante el Sprint y cómo se va a lograr.

|Sprint #|Sprint 1|
| :- | :- |
|Sprint Planning Background||
|Date|28/08/2023|
|Time|3 horas|
|Location o Platform|Discord|
|Prepared by|Edwin Abdias Lopez Huaman – U20201B051|
|Attendess (to planning meeting)|<p>Julio Ernesto Asillo Mendoza - U20201B482 </p><p>Leydi Yaquelin Mamani Aro - U20201B745</p><p>Angie Ruiz Carhuamaca - U20201B293</p><p>Jhan Clinton Antonio Salazar - U20201B312</p>|
|Sprint 0 Review Summary|- Diseño y desarrollo del landing page|
|Sprint 0 Retrospective Summary|- Completar los diseños y estandarizar el lenguaje usado en el desarrollo y presentación del landing page|
|Sprint Goal & User Stories||
|Sprint 1 Goal|Implementar y desplegar Landing Page|
|Sprint 1 Velocity|15|
|Sum of Story Point|15|


1. #### Sprint Backlog

|Sprint #|Sprint 1|||||||
| :- | :- | :- | :- | :- | :- | :- | :- |
|User Story|Work-Item/Task|||||||
|Id|Title|Id|Title|Description|Estimation (Hours)|Assigned To|Status (To-do / InProcess / ToReview / Done)|
|US-01|Visualizar una landing page clara y atractiva.|W-01|Diseño|Como visitante, quiero ver una landing page clara y atractiva para que pueda entender rápidamente el propósito del sitio web.|3 hours|Leydi|Done|
|US-02|Visualizar una sección sobre nosotros en el landing page.|W-02|Sección nosotros|Como visitante, quiero ver una sección en el landing page que hable sobre el startup para saber el propósito y con quiénes estoy tratando al momento de usar su aplicación web.|3 hours|Edwin|Done|
|US-03|Visualizar contenido relevante en el landing page.|W-03|Contenido|Como usuario, quiero que la landing page tenga contenido relevante para que pueda tomar una decisión informada.|3 hours|Julio|Done|
|US-04|Acceder desde cualquier dispositivo a la landing page.|W-04|Accesibilidad|Como usuario, quiero que la landing page sea accesible desde diferentes dispositivos para que pueda accedes al sitio web desde cualquier lugar.|3 hours|Angie|Done|
|US-05|Desplegar la landing page|W-05|Desplegar|Como startup, quiero desplegar una landing page para informar sobre nuestra aplicación.|1 hours|Jhan|Done|


1. #### Development Evidence for Sprint Review


<table><tr><th colspan="1" valign="top">Repository</th><th colspan="1" valign="top">Branch</th><th colspan="1" valign="top">Commit id</th><th colspan="1" valign="top">Commit Message</th><th colspan="1" valign="top">Committed on(Date)</th></tr>
<tr><td colspan="1" rowspan="5" valign="top"><p></p><p></p><p>landingPage</p></td><td colspan="1" valign="top">Master</td><td colspan="1" valign="top">1e419b089c3ec8364cb488684b74eb8030fef11f</td><td colspan="1" valign="top">Basic structure with html</td><td colspan="1" valign="top">09/09/2023</td></tr>
<tr><td colspan="1" valign="top">Master</td><td colspan="1" valign="top">ac12796589e90f9b868340f611d1f9e75796f4ab </td><td colspan="1" valign="top">Basic styles added</td><td colspan="1" valign="top">09/09/2023</td></tr>
<tr><td colspan="1" valign="top">Master</td><td colspan="1" valign="top">98479592c997a29272872b50606b50c81e2af988</td><td colspan="1" valign="top">Completed styles</td><td colspan="1" valign="top">09/09/2023</td></tr>
<tr><td colspan="1" valign="top">Master</td><td colspan="1" valign="top">ff5ec7148fefe40c5fd627081dece81aa79784c8</td><td colspan="1" valign="top">Responsiveness was completed</td><td colspan="1" valign="top">09/09/2023</td></tr>
<tr><td colspan="1" valign="top">Master</td><td colspan="1" valign="top">08881964a3d8698f05240489009fc2741c906e54</td><td colspan="1" valign="top">Plans with java script added</td><td colspan="1" valign="top">10/09/2023</td></tr>
</table>

### JIRA SOFTWARE:
Utilizamos Jira para el sprint 1 de la siguiente manera:

![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/e5618694-e1de-4ebe-a41f-9b2fc87b111f)


1. #### Testing Suite Evidence for Sprint Review

Para esta entrega no se realizaron pruebas de testeo.
1. #### Execution Evidence for Sprint Review

Durante este sprint, se diseñó y desarrolló la primera iteración del landing page con meticulosa consideración de patrones de diseño, una paleta de colores apropiada, y el objetivo primordial de persuadir al usuario a utilizar nuestra aplicación.

![EXECUTION IMAGE 1](https://github.com/LogicMinds-Group/Informe-Final/assets/89101139/5e7b37c5-ad6e-4ae9-85b8-dcc215889b11)

![EXECUTION IMAGE 2](https://github.com/LogicMinds-Group/Informe-Final/assets/89101139/01bc9039-c48e-4498-ab28-441495a17b82)

![EXECUTION IMAGE 3](https://github.com/LogicMinds-Group/Informe-Final/assets/89101139/f6877953-9ca3-433b-8dfa-d1599cdfc0b2)

1. #### Documentation Evidence for Sprint Review

Para este sprint solo se realizó el diseño e implementación de la landing page. No se realizaron end points.


1. #### Software Deployment Evidence for Sprint Review
En esta sección se presentará capturas del despliegue exitoso del landing page que se realizó en este sprint 1.

![DEPLOYMENT IMAGE 1](https://github.com/LogicMinds-Group/Informe-Final/assets/89101139/b0795102-c2ea-4e22-86b1-44177efd515a)

![DEPLOYMENT IMAGE 2](https://github.com/LogicMinds-Group/Informe-Final/assets/89101139/bb6b437f-9219-4f28-bae7-f57e82645b05)

1. #### Team Collaboration Insights during Sprint
Se evidencia la colaboración de todos los integrantes del equipo para el desarrollo de la landing page.

![INSIGHTS IMAGE 1](https://github.com/LogicMinds-Group/Informe-Final/assets/89101139/4c54c657-a97f-4893-b03c-1ab082246c06)

![INSIGHTS IMAGE 2](https://github.com/LogicMinds-Group/Informe-Final/assets/89101139/54d181a1-2e8c-4192-9f56-b10f5437407a)

![INSIGHTS IMAGE 3](https://github.com/LogicMinds-Group/Informe-Final/assets/89101139/ce642a3f-61ad-466c-9f0f-db4d7e4b2815)

1. ### 5.2.2 Sprint 2
1. #### 5.2.2.1 Sprint Planning 
<table style="">
  <tbody>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;"><strong>Sprint #</strong></td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;"><strong>Sprint 2</strong></td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;" colspan="2"><strong>Sprint Planning Background</strong></td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Date</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">2023-09-29</td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Time</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">9:00 PM</td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Location</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Discord</td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Prepared By</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Edwin Lopez</td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Attendees (to planning meeting)</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;"> Asillo Mendoza, Julio Ernesto, Mamani Aro, Leydi Yaquelin, Ruiz Carhuamanca, Angie y Antonio Salazar, Jhan Clinton</td>
    </tr>
    <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Sprint n – 1 Review
Summary</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;"> - El sprint 1 se centró en poder completar las historias de usuario acordadas por el equipo. Como parte de los resultados se finalizó con los 5 ítems planificados.</td>
    </tr>
     </tr>
    <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Sprint n – 1 Retrospective Summary</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;"> El equipo se reunió al finalizar el primer sprint para realizar una retroalimentación retrospectiva. Durante la reunión, se discutieron los aspectos positivos y negativos del sprint y se identificaron oportunidades de mejora para futuras iteraciones. </td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;" colspan="2"><strong>Sprint Goal & User Stories</strong></td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Sprint 2 Goal</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Diseñar las interfaces de la aplicación, implementando los métodos de POST y GET para las user stories que lo requieran</td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Sprint 2 Velocity</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">        
        - <strong>US09 Publicar dentro de la aplicación (Story Point 8)</strong>   
        - <strong>US10 Implementar mensajería (Story Point 5)</strong> 
        - <strong>US11 Listar publicaciones (Story Point 5)</strong> 
        - <strong>US27 Participar en el foro (Story Point 3)</strong> 
        - <strong>US13 Crear mi perfil en la aplicación (Story Point 3)</strong> 
        - <strong>US08 Visualizar arrendatario (Story Point 5)</strong> 
        - <strong>US22 Listar propiedades (Story Point 5)</strong> 
        - <strong>US21 Diseñar la interfaz de usuario (Story Point 5)</strong>        
      </td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Sum of Story Points</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;"><strong>39</strong></td>
    </tr>
  </tbody>
</table>

1. #### 5.2.2.2 Sprint Backlog 2

|Sprint #|Sprint 2|||||||
| :- | :- | :- | :- | :- | :- | :- | :- |
|User Story|Work-Item/Task|||||||
|Id|Title|Id|Title|Description|Estimation |Assigned To|Status|
|US-09|Publicar dentro de la aplicación|W-01|Implementar la funcionalidad de publicación de propiedades dentro de la aplicación|<p>- Desarrollar una opción de publicación de propiedades que permita a los usuarios compartir información e imágenes dentro de la aplicación.</p><p>- La publicación debe ser fácil de usar, intuitiva y estéticamente agradable para mejorar la experiencia del usuario.</p>|5 hours|Edwin|Done|
|US-10|Implementar mensajería|W-02|Desarrollar sistema de mensajería en la aplicación|<p>- Diseñar una interfaz de usuario intuitiva y atractiva para la función de mensajería.</p><p>- Desarrollar la lógica necesaria para gestionar el envío y recepción de mensajes.</p><p></p><p></p><p></p>|4 hours|Edwin|In process|
|US-11|Listar publicaciones|W-03|Mostrar todas las publicaciones|<p>- Implementar una funcionalidad que permita al usuario ver todas las publicaciones disponibles en la plataforma.</p><p>- incluye la creación de una página o sección dedicada a la lista de publicaciones, donde se mostrará el título, la descripción y otros detalles relevantes de cada publicación.</p>|3 hours|Leydi|In process|
|US-27|Participar en el foro|W-04|Implementar el diseño y funcionalidades del foro|<p>-Desarrollar la interfaz del foro.</p><p>-Desarrollar los métodos del floro.</p>|3 hours|Leydi|In process|
|US-13|Crear mi perfil en la aplicación|W-05|Configuración inicial del perfil de usuario en la aplicación|<p>-Desarrollar la interfaz del foro.</p><p></p>|3 hours|Jhan|Done|
|US-08|Visualizar arrendatario|W-06|Visualización de información del arrendatario|<p>-Crear una interfaz de usuario para mostrar los detalles del arrendatario.</p><p>- Obtener y mostrar el nombre completo del arrendatario.</p>|5 hours|Angie|Done|
|US-22|Listar propiedades|W-07|Mostrar una lista de propiedades|<p>- Crear una interfaz de usuario que muestre una lista de propiedades.</p><p>-Implementar la funcionalidad de ordenar la lista de propiedades según diferentes criterios, como precio, ubicación o tamaño.</p><p>-Agregar la capacidad de ver detalles adicionales de cada propiedad, como imágenes, descripciones y características.</p><p></p>|5 hours|Angie|In process|
|US-21|Diseñar la interfaz de usuario|W-08|Crear una interfaz de usuario intuitiva y atractiva|-Diseñar un esquema de navegación claro y fácil de usar.|6 hours|Julio|Done|

###JIRA SOFTWARE:

Hemos utilizado Jira para el sprint 2:

![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/9a77cb52-7046-4717-96dc-aeff3bd90dd4)


1. #### 5.2.2.3 Development Evidence for Sprint Review
####

<table><tr><th colspan="1" valign="top"><b>Repository</b> </th><th colspan="1" valign="top"><b>Branch</b> </th><th colspan="1" valign="top"><b>Commit id</b> </th><th colspan="1" valign="top"><b>Commit Message</b> </th><th colspan="1" valign="top"><b>Commited on(Date)</b> </th></tr>
<tr><td colspan="1" rowspan="13" valign="top"><p> https://github.com/LogicMinds-Group/frontEnd </p><p> </p><p> </p><p> </p><p> </p><p> </p><p> </p><p> </p><p> </p><p> </p><p> </p><p> </p><p></b> </p></td><td colspan="1" valign="top">(origin/publish-property, publish-property</td><td colspan="1" valign="top">f847f87bd8ee4b8d283b8fb34754a40e263aba54 </td><td colspan="1" valign="top">add publish section </td><td colspan="1" valign="top">Fri Sep 29 17:05:32 2023 </td></tr>
<tr><td colspan="1" valign="top">(origin/feature/register-property) </td><td colspan="1" valign="top">1e5120252a3032d0880a7259b01107fe57e97c8c </td><td colspan="1" valign="top">add property-form v1 </td><td colspan="1" valign="top">Fri Sep 29 00:51:13 2023 </td></tr>
<tr><td colspan="1" valign="top"><p>(origin/feature/register-property) </p><p> </p></td><td colspan="1" valign="top"><p>763cf114f59aeaea407bf730737dbf03bef41f63 </p><p> </p></td><td colspan="1" valign="top">add property-form v1 </td><td colspan="1" valign="top">Fri Sep 29 00:51:13 2023 </td></tr>
<tr><td colspan="1" valign="top">(origin/feature/forum-list) </td><td colspan="1" valign="top">6ec42df72e5915b85bf64abe97b00a0b28ce214e </td><td colspan="1" valign="top">Forum Secction completed </td><td colspan="1" valign="top">Sun Sep 24 04:43:39 2023 </td></tr>
<tr><td colspan="1" valign="top"><p>(origin/feature/forum-list) </p><p> </p></td><td colspan="1" valign="top"><p>0b6e4ce46109b7782e2c8bca87f6015c8edad02d </p><p> </p></td><td colspan="1" valign="top">Forum Secction completed </td><td colspan="1" valign="top"><p>Sun Sep 24 04:43:39 2023 </p><p> </p></td></tr>
<tr><td colspan="1" valign="top"><p>(origin/feature/forum-list) </p><p> </p></td><td colspan="1" valign="top">0b6e4ce46109b7782e2c8bca87f6015c8edad02d </td><td colspan="1" valign="top">forum-list and forum-see </td><td colspan="1" valign="top">Sat Sep 23 18:19:13 2023 </td></tr>
<tr><td colspan="1" valign="top">(origin/feature/edit-profile) </td><td colspan="1" valign="top">388e626cf4227499d635419498efbcb82e904019 </td><td colspan="1" valign="top">section message completed </td><td colspan="1" valign="top">Sat Sep 23 11:01:32 2023 </td></tr>
<tr><td colspan="1" valign="top">(origin/feature/edit-profile) </td><td colspan="1" valign="top">047af980e7dac86742374bc749ad6f67e3e7d020 </td><td colspan="1" valign="top">gender added </td><td colspan="1" valign="top">Fri Sep 22 19:53:25 2023 </td></tr>
<tr><td colspan="1" valign="top">(origin/feature/edit-profile) </td><td colspan="1" valign="top">440e9684fe33d14bbeb8b31ae34651e56d0a4d5e </td><td colspan="1" valign="top">Send message completed </td><td colspan="1" valign="top">Fri Sep 22 19:53:25 2023 </td></tr>
<tr><td colspan="1" valign="top">(origin/feature/edit-profile) </td><td colspan="1" valign="top">e5622fbbfb97e9a8726a551f1381228c443d54d7 </td><td colspan="1" valign="top">see and qualify profile completed </td><td colspan="1" valign="top"><p>Fri Sep 22 19:53:25 2023 </p><p> </p></td></tr>
<tr><td colspan="1" valign="top">(origin/feature/edit-profile) </td><td colspan="1" valign="top">c3dcb0c46abe130af637230f2a5f56fd34668bb2 </td><td colspan="1" valign="top">see post desing completed </td><td colspan="1" valign="top"><p>Fri Sep 22 19:53:25 2023 </p><p> </p></td></tr>
<tr><td colspan="1" valign="top">(origin/feature/edit-profile) </td><td colspan="1" valign="top">dc4daf6754d9002b3a7055e6e03e335259f13a71 </td><td colspan="1" valign="top">list post desing completed </td><td colspan="1" valign="top"><p>Fri Sep 22 19:53:25 2023 </p><p> </p></td></tr>
<tr><td colspan="1" valign="top">(origin/feature/register) </td><td colspan="1" valign="top">61a1b0e6233afe0e988db3a81ee7a79c8ae06af9 </td><td colspan="1" valign="top">Edit profile dising  completed </td><td colspan="1" valign="top">Thu Sep 21 23:55:11 2023</td></tr>
</table>

![Aspose Words 1f3db494-a6ea-46b6-8f1e-e7d54ebe29ff 016](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/661d0245-275a-4958-be9d-3e97240c6b4a)

 #### 5.2.2.4 Testing Suite Evidence for Sprint Review

Para esta entrega no se realizaron pruebas de testeo.

 #### 5.2.2.5 Execution Evidence for Sprint Review

![Imagen de WhatsApp 2023-09-30 a las 01 16 23](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/6a406b43-1cc7-42d1-b0ef-9b15ee2455ff)

![Imagen de WhatsApp 2023-09-30 a las 01 17 32](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/3df83ef8-2f30-49e4-90f8-d068ce0dfc20)

![Imagen de WhatsApp 2023-09-30 a las 01 17 46](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/64281f92-393f-4bca-98e1-d510b69fd15e)

![Imagen de WhatsApp 2023-09-30 a las 01 18 04](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/0b4e0f11-7544-4024-91a8-f950aae65b25)

![Imagen de WhatsApp 2023-09-30 a las 01 18 18](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/7f1894a0-1e62-4cb6-9305-b5a57ab7aa54)

![Imagen de WhatsApp 2023-09-30 a las 01 18 35](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/a9b580e6-175b-496c-acfc-fe44b4dbc8df)

![Imagen de WhatsApp 2023-09-30 a las 01 18 52](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/0d0c10aa-2194-4ab0-b228-c039d384811b)

![Imagen de WhatsApp 2023-09-30 a las 01 16 44](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/edc2c382-1b3a-4839-8091-a7c780b50bd6)

![Imagen de WhatsApp 2023-09-30 a las 01 17 10](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/7c5bcea8-d45f-4baa-9218-eb74925c0bf5)

![Imagen ZZZZ](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/d96b0c65-c9bd-4182-8c39-0b75d032f617)

Link de la App: https://renstate2-0.web.app/home

 #### 5.2.2.6 Documentation Evidence for Sprint Review

Para este sprint se documentará el template o directorio para poder desplegar el db.json.

![fdsfsdf](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/0b003dfc-c820-474d-a8df-f665144bcbee)


 #### 5.2.2.7 Software Deployment Evidence for Sprint Review
Para este sprint se desplegó una Fake Api, para poder desplegar el frontend. Se utilizó la herramienta Render y Github.

![Aspose Words 98ab3de6-4375-4a0d-b77a-63c7c9506ac4 001](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/7580cf97-5c9e-4e2e-a11f-84f7a582f3e8)

Link del Fake Api desplegado: <https://logicminds-server.onrender.com>



 #### 5.2.2.8 Team Collaboration Insights during Sprint
Cada miembro del equipo trabajó en conjunto para la implementación del frontend.

Repositorios de la Organización:

![Aspose Words 1f3db494-a6ea-46b6-8f1e-e7d54ebe29ff 017](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/733bb607-04da-4a39-a69a-b8cceaf401c1)

![Aspose Words 1f3db494-a6ea-46b6-8f1e-e7d54ebe29ff 019](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/aaf4e32b-74ce-44c4-9566-cdda63e3eba2)

![Aspose Words 1f3db494-a6ea-46b6-8f1e-e7d54ebe29ff 020](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/ff526baf-dc35-4f34-a461-a0fbf1498091)


1. ### 5.2.2 Sprint 3
1. #### 5.2.2.1 Sprint Planning
   Para este tercer sprint la planificación se hizo de la siguiente manera:
   
<table style="">
  <tbody>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;"><strong>Sprint #</strong></td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;"><strong>Sprint 3</strong></td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;" colspan="2"><strong>Sprint Planning Background</strong></td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Date</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">2023-10-28</td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Time</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">9:00 PM</td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Location</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Discord</td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Prepared By</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Edwin Abdias Lopez Huaman</td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Attendees (to planning meeting)</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;"> Asillo Mendoza, Julio Ernesto, Mamani Aro, Leydi Yaquelin, Ruiz Carhuamanca, Angie y Antonio Salazar, Jhan Clinton</td>
    </tr>
    <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Sprint n – 2 Review
Summary</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;"> - El sprint 2 se centró en poder completar las historias de usuario acordadas por el equipo. Como parte de los resultados se finalizó con los ítems planificados que corresponde al diseño de las interfaces de la aplicación. </td>
    </tr>
     </tr>
    <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Sprint n – 2 Retrospective Summary</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;"> El equipo se reunió al finalizar el primer sprint para realizar una retroalimentación retrospectiva. Durante la reunión, se discutieron los aspectos positivos y negativos del sprint y se identificaron oportunidades de mejora para futuras iteraciones. </td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;" colspan="2"><strong>Sprint Goal & User Stories</strong></td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Sprint 2 Goal</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;"> -Culminación del FrontEnd y primera implementación del backend.</td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Sprint 3 Velocity</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">        
        - <strong>Implementar la opción premium para usuarios (SP:5)</strong>   
        - <strong>Implementar la sección de los clientes (SP:3)</strong> 
        - <strong>Implementar la sección de propiedades y reservas de propiedades (SP:3)</strong> 
        - <strong>Implementar la sección para las publicaciones (SP:3)</strong> 
        - <strong>Implementar el servicio para los posts (SP:5)</strong>     
      </td>
    </tr>
    <tr>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;">Sum of Story Points</td>
      <td style="border:1pt solid #000000;padding:5pt;vertical-align:top;"><strong>19</strong></td>
    </tr>
  </tbody>
</table>


#### Sprint Backlog 3

<table><tr><th colspan="1" valign="top">Sprint #</th><th colspan="7" valign="top">Sprint 3</th></tr>
<tr><td colspan="2" valign="top">User Story</td><td colspan="6" valign="top">Work-Item/Task</td></tr>
<tr><td colspan="1" valign="top">Id</td><td colspan="1" valign="top">Title</td><td colspan="1" valign="top">Id</td><td colspan="1" valign="top">Title</td><td colspan="1" valign="top">Description</td><td colspan="1" valign="top">Estimation </td><td colspan="1" valign="top">Assigned To</td><td colspan="1" valign="top">Status</td></tr>
<tr><td colspan="1" rowspan="6" valign="top">S3</td><td colspan="1" rowspan="4" valign="top">Finalización del Frontend</td><td colspan="1" valign="top">SP301 </td><td colspan="1" valign="top">Implementar la sección premium para los usuarios</td><td colspan="1" valign="top"><p>Desarrollar la opción de ser usuario premium que permita a los usuarios acceder a más funcionalidades según subscripción</p><p>Desarrollar la opción de cancelar subscripción</p></td><td colspan="1" valign="top">5 horas</td><td colspan="1" valign="top">Edwin</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">SP302</td><td colspan="1" valign="top">Implementar la sección de clientes y publicaciones</td><td colspan="1" valign="top"><p>Diseñar una interfaz de usuario intuitiva para visualizar las tablas de cada sección</p><p>Implementar la opción visualizar las tablas de clientes del arrendador</p><p>Implementar la opción visualizar las tablas de publicaciones del arrendador</p></td><td colspan="1" valign="top">5 horas</td><td colspan="1" valign="top">Angie</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">SP303 </td><td colspan="1" valign="top">Implementar la sección de propiedades</td><td colspan="1" valign="top"><p>Diseñar una interfaz de usuario intuitiva para visualizar las tablas de las propiedades y de reserva de propiedades</p><p>Implementar la opción visualizar las tablas de propiedades y de reserva en el perfil del arrendador que corresponde</p></td><td colspan="1" valign="top">5 horas</td><td colspan="1" valign="top">Leydi</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">SP304 </td><td colspan="1">Desplegar la Web Applications en Firebase </td><td colspan="1">Luego de haber concluido con la implementación de los frames de la aplicación se completó con el despliegue del frontend en Firebase.</td><td colspan="1" valign="top">5 horas</td><td colspan="1" valign="top">Julio</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="2" valign="top">Primera versión del backend</td><td colspan="1" valign="top">SP305</td><td colspan="1" valign="top">Implementacion del servicio Post</td><td colspan="1">Desarrollar el servicio que corresponde a las publicaciones de propiedades para acceder al servicio en el frontend</td><td colspan="1" valign="top">5 horas</td><td colspan="1" valign="top">Edwin</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">SP306 </td><td colspan="1">Primera integración del backend y frontend</td><td colspan="1">Desarrollo de la integración del frontend y el backend para la sección de Post.</td><td colspan="1" valign="top">5 horas</td><td colspan="1" valign="top">Angie</td><td colspan="1" valign="top">Done</td></tr>
</table>

###JIRA SOFTWARE:
Hemos hecho uso de la herramienta Jira para este Sprint colocando las historias o tareas correspondientes:
![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/1eb91b58-8aa7-4d87-96da-0a62b026c46e)

LINK JIRA: https://julioasillo.atlassian.net/jira/software/projects/LOS/boards/6/backlog   

### Development Evidence for Sprint Review

<table><tr><th colspan="1" valign="top"><b>Repository</b> </th><th colspan="1" valign="top"><b>Branch</b> </th><th colspan="1" valign="top"><b>Commit id</b> </th><th colspan="1" valign="top"><b>Commit Message</b> </th><th colspan="1" valign="top"><b>Commited on(Date)</b> </th></tr>
<tr><td colspan="1" rowspan="4" valign="top"><p><https://github.com/LogicMinds-Group/backEnd></p><p> </p><p> </p><p> </p><p> </p><p> </p><p> </p><p> </p><p> </p><p> </p><p></b> </p></td><td colspan="1" valign="top">origin/feature/messages</td><td colspan="1" valign="top">` `a975e5ae77e42d41c93bfea7da551e8301de0304</td><td colspan="1" valign="top">delete other service</td><td colspan="1" valign="top">Fri Nov 3 2023</td></tr>
<tr><td colspan="1" valign="top">origin/feature/post</td><td colspan="1" valign="top">14a5d22cc4adb167532b98235d452cf89f97e5df</td><td colspan="1" valign="top">add implementation postServiceImpl</td><td colspan="1" valign="top">Fri Nov 3 2023</td></tr>
<tr><td colspan="1" valign="top">origin/feature/post</td><td colspan="1" valign="top">1184b40146309df1d789309ca0da1b30e3d84322</td><td colspan="1" valign="top">create postserviceImpl</td><td colspan="1" valign="top">Fri Nov 3 2023</td></tr>
<tr><td colspan="1" valign="top">origin/feature/post</td><td colspan="1" valign="top">bd6c7da4ff9d8d89dab47201bc8f1fdb226e3982</td><td colspan="1" valign="top">add entity, repository and service of Post</td><td colspan="1" valign="top">Fri Nov 3 2023</td></tr>
<tr><td colspan="1" valign="top"><https://github.com/LogicMinds-Group/frontEnd></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
</table>

#### Testing Suite Evidence for Sprint Review
No aplica para esta entrega
#### Execution Evidence for Sprint Review
(capturas de forma local)
#### Documentation Evidence for Sprint Review
No aplica para esta entrega
#### Software Deployment Evidence for Sprint Review
(desplegar frontend)
#### Team Collaboration Insights during Sprint
• Members

![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/eab1ad03-2477-4385-970d-5147ad234777)

• Network Backend

![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/c402f58e-eac0-498e-a1b6-ff74cbd08217)

•	Netword Frontend

![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/ca306114-ecff-4be9-8d30-ae1d504697e4)



5.3.  ## <a name="_toc143240722"></a>Validation Interviews
En esta sección, se detallan y se describen las actividades de las entrevistas de validación llevadas a cabo durante el proyecto.
5.3.1. ### <a name="_toc143240723"></a>Diseño de Entrevistas
Se validarán los siguientes productos: 

Landing Page: https://logicminds-group.github.io/landingPage/  

![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/136520bd-e7f7-44bb-b874-c793e6332fef)

Web Application: https://renstate2-0.web.app/home 

![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/582cd797-1175-4c29-a5df-70d72abfe1bc)


1. ### <a name="_toc143240724"></a>Registro de Entrevistas
Segmento Arrendador:

- Entrevista 1:
- Entrevistador: Leydi Mamani
- Nombres y Apellidos: Maribel Chauca
- Edad: 36
- Distrito: San Juan de Miraflores
- ![Interfaz de usuario gráfica, Sitio web

![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/f28a807b-b231-4b98-a337-91bd94e841da)

Evidencia de la Reunión:
- URL de Stream: 
- Duración de la entrevista: 5 minutos aproximadamente
- Timing de la entrevista:
- Resumen sobre la entrevista:

La señora Maribel nos comenta que la aplicación le parece completa, respecto a las funcionalidades según su opinión cumple con los requisitos y sus necesidades. Por otro lado, sugiere que la lista de publicaciones podrías mostrar más de una imagen.



- Entrevista 2:
- Entrevistador: Edwin Lopez Huaman
- Nombres y Apellidos: Miguel
- Edad: 20 años
- Distrito: Jesus Maria
- Evidencia de la Reunión:

![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/61895e52-201b-4a4d-ad33-fee9136cb5d0)

- URL de Stream: 
- Duración de la entrevista: 7 minutos
- Timing de la entrevista: 11:33
- Resumen sobre la entrevista:

Miguel comenta que le gusta el diseño minimalista que tiene la aplicación que le genera interés seguir navegando.



Segmento Arrendatario:

- Entrevista 1: 
- Entrevistador: Julio Asillo
- Nombres y Apellidos: Sebastián Montes Molina
- Edad: 24 años
- Distrito: Comas
- Evidencia de la Reunión:
![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/90fe1efd-d08e-4187-b649-b09b4950aa51)
  
- URL de Stream: 
- Duración de la entrevista: 04:09 minutos
- Timing de la entrevista: 00:07 – 04:16 minutos
- Resumen sobre la entrevista: En la entrevista el entrevistador Julio Asillo muestra nuestro landing page donde encontrará información sobre nuestra idea de negocio, para luego mostrar la aplicación web con sus rutas de navegación y lo que podrá ver al usar la aplicación web, para concluir le muestro las ventanas del log in y Register. El entrevistado Sebastián Montes aclara que es una buena idea de negocio, porque aplicaciones conocidas solo hay Airbnb y solo eso, entonces el recalca que es una buena idea de negocio ya que mostraremos información verídica de los inmuebles en alquiler. También recalca que debería haber un sistema de mensajería o chat con el arrendador o propietario del inmueble para llegar a un acuerdo, luego el entrevistador Julio Asillo procede a decirle que esa función está en desarrollo porque sí hay un botón que dice “send message”, listo para abarcar el sistema aun no creado de chat o mensajería directa con el arrendador.



- Entrevista 2:
- Entrevistador: Angie Ruiz
- Nombres y Apellidos: Abrahaam Issac Vega Castillo
- Edad: 20 años
- Distrito: Santa Anita
- Evidencia de la Reunión:

![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/da1511f5-effe-41ee-a4c6-8d6db9aaf5a6))

- URL de Stream: 
- Duración de la entrevista: 7 minutos aproximadamente
- Timing de la entrevista: 04:20 – 11:26 minutos
- Resumen sobre la entrevista: 

Abrahaam nos comenta que le parece interesante nuestro desarrollo, es fácil de entender y navegar. Además, considera interesante el enfoque de nuestro proyecto y que esté cumpliendo con las funcionalidades que se le explicó. 


1. ### <a name="_toc143240725"></a>Evaluación según heurísticas
**UX Heuristics & Principles Evaluation**

**Usability – Inclusive Design – Information Architecture**

- CARRERA: Ingeniería de Software 
- CURSO: Desarrollo de Aplicaciones Open Source 
- SECCIÓN: SV52
- PROFESORES: Hugo Allan Mori Paiva
- AUDITOR: LogicMinds
- CLIENTE: Usuarios
- SITE O APP A EVALUAR: Renstate

TAREAS POR EVALUAR

El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas: 

1\. Registro de un usuario nuevo 

2\. Listado de un post 

3\. Búsqueda de posts de alquiler 

4\. Realizar calificación por cantidad de estrellas

6\. Agregar Clientes a un Arrendador 

7\. Acceso a la información



ESCALA DE SEVERIDAD:

Los errores serán puntuados tomando en cuenta la siguiente escala de severidad

|Nivel|Descripción|
| :- | :- |
|1|Problema superficial: puede ser fácilmente superador por el usuario o ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.|
|2|Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente reléase|
|3|Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta.|
|4|Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento.|



TABLA RESUMEN:

|#|Problema|Escala de severidad|Heurística/Principio violada(o)|
| :- | :- | :- | :- |
|1|La sección de registro de usuario de la aplicación no posee una Ventana de confirmación |3|Usabilidad: Libertad y control usuario|
|2|La sección de registro de usuario de la aplicación no posee validación de los datos ingresados   |3|Usabilidad: Prevención de errores|
|3|La sección de propiedades no muestra un sistema de búsqueda funcional |3|Usabilidad: Libertad y control usuario|
|<p>4</p><p></p>|La lista de clientes no cuenta con ningún filtro y sistema de búsqueda funcional |3|Usabilidad: Libertad y control usuario|
|<p>5</p><p></p>|Incluyen los botones de navegación según categoría, pero no existe contenido al que dirigirse |3|Information Architecture: Is it usable?|
|<p>6</p><p></p>|Incluyen botones “Save”, “search”, “cancel” y otros con íconos para realizar acciones|3|Principio de arquitectura de la información: Navegación|



DESCRIPCIÓN DE PROBLEMAS:

**PROBLEMA #1:** La sección de registro de usuario de la aplicación no posee una ventana de confirmación* 

Severidad: 3 

**Heurística violada:** Usabilidad - Libertad y control del usuario 

Problema: 

Al momento de realizar el registro de un nuevo usuario y dar click en el botón para realizar el registro, no aparece ninguna ventana que confirme que sea creado una cuenta satisfactoriamente. 

![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/c21cd27e-d429-41ef-8495-5a21bf7a2403)

Recomendación: 

Agregar una ventana emergente con el mensaje de registro exitoso y con opciones de aceptar o cancelar el registro. 


**PROBLEMA #2:** La sección de registro de usuario de la aplicación no posee una ventana validación de confirmación de los datos ingresados*   

Severidad: 3 

**Heurística violada:** Usabilidad - Libertad y control del usuario: Prevención de errores

Problema: 

Al momento de llenar todos los campos en la sección de registro de un nuevo usuario, la aplicación no valida que los datos ingresados sean coherentes con el campo a completar.  

![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/e83e4e39-3c13-47d5-bae4-ca5d7c93ad3e)

Recomendación: 

Agregar una ventana emergente con el mensaje de registro exitoso y con opciones de aceptar o cancelar el registro. 



**PROBLEMA #3:** La sección de propiedades no muestra un sistema de búsqueda funcional*  

Severidad: 3

**Heurística violada:** Usabilidad: Libertad y control usuario

Problema: 

En la sección de anuncios no existe un filtro o Sistema de búsqueda funcional para buscar anuncios en particular. 

![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/44e94c5f-6a8c-46fe-b8e3-1cd34c2e664d)

Recomendación: 

Agregar un sistema de búsqueda para mejorar la experiencia de usuario y facilitar la búsqueda del anuncio que realiza. 



**PROBLEMA #4:** La lista de clientes no cuenta con ningún filtro y sistema de búsqueda funcional

Severidad: 3

**Heurística violada:** Usabilidad: Libertad y control usuario** 

Problema: 

La lista de anuncios de los inmuebles no presenta un sistema de búsqueda functional para encontrar anuncios específicos. Lo cual, genera en el usuario incomodidad por tener que revistar todos los anuncios para encontrar lo que desea. 

![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/7dab80e7-770f-43fb-8ebf-2b9c27e384be)

Recomendación: 

Implementar un sistema de búsqueda.



**PROBLEMA #5:** Incluyen los botones de navegación según categoría, pero no existe contenido al que dirigirse 

Severidad: 3

**Heurística violada:** Information Architecture: Is it usable?

Problema: 

Al momento de dirigirse a la página principal del segmento arrendatario, se puede visualizar las categorías de la aplicación. Sin embargo, no existe contenido al que dirigirse.

![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/294cd4da-7058-4d5d-819a-d244f9304d3c)

Recomendación: 

Redirigir a una ventana que si tenga la información necesaria que el usuario desea de esa sección y que el contenido sea el que corresponda.

**PROBLEMA #6:** Incluyen botones “Save”, “search”, “cancel” y otros con íconos para realizar acciones en diferentes secciones de la aplicación

Severidad: 3

**Heurística violada:** Principio de arquitectura de la información: Navegación** 

Problema: 

Al momento de dirigirse a las secciones de la aplicación de ambos segmentos, se puede visualizar íconos y botones que facilitan la navegación del usuario, entre ellas está la sección anuncios que el ícono para brindar más detalles te redirige a los detalles del anuncio seleccionado. Sin embargo, contar con etiquetas podría ayudar a entender rápidamente que hace cada botón.

![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/f3788813-081c-4b5f-80d7-718b5ab32cbc)

(Te redirige a los detalles del anuncio)

![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/e7752b01-67e5-49fe-98b6-9cd04c6aa968)

Recomendación: 

Agregar etiquetas que ayuden al usuario saber qué hace cada botón y poder entender la navegación y las opciones que se brinda. 


1. ## Video About the product
El video About The Product es una herramienta audiovisual que se emplea para mostrar y promocionar un producto de una manera atractiva y convincente. A través de imágenes, gráficos, música y narración, este video busca captar la atención del público y transmitir de manera efectiva las características, beneficios y usos del producto en cuestión. El Video sobre el producto puede ser utilizado en diferentes plataformas, como páginas web, redes sociales o presentaciones comerciales, con el objetivo de generar interés en el producto y aumentar las ventas.

![image](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/e9c9af4a-d2af-4436-8a07-2027760b7ae3)

Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201b482_upc_edu_pe/ETtt6dk6e0dEsdy9RRaoGsYBmw1_23yCCJ4u5Gz5emEmvg?e=eYg6Lb     



1. ### 5.2.2 Sprint 4
1. #### 5.2.2.1 Sprint Planning
El Sprint Planning es un evento o reunión que se realiza al inicio de cada Sprint en el marco de la metodología Scrum. Durante esta reunión, el equipo Scrum se reúne para planificar y definir la meta del Sprint, así como para discutir el backlog del producto y seleccionar los elementos de trabajo que se abordarán en el próximo Sprint. 

|Sprint #|Sprint 4|
| :- | :- |
|Sprint Planning Background||
|Date|13/11/2023|
|Time|3 horas|
|Location o Platform|Discord|
|Prepared by|Edwin Abdias Lopez Huaman – U20201B051|
|Attendess (to planning meeting)|<p>Julio Ernesto Asillo Mendoza - U20201B482 </p><p>Leydi Yaquelin Mamani Aro - U20201B745</p><p>Angie Ruiz Carhuamaca - U20201B293</p><p>Jhan Clinton Antonio Salazar - U20201B312</p>|
|Sprint 3 Review Summary|- El sprint 3 se centró en poder completar las historias de usuario acordadas por el equipo. Como parte de los resultados se finalizó con 5 ítems planificados.|
|Sprint 3 Retrospective Summary|- El equipo se reunió al finalizar el sprint para realizar una retroalimentación retrospectiva. Durante la reunión, se discutieron los aspectos positivos y negativos del sprint y se identificaron oportunidades de mejora para futuras iteraciones.|
|Sprint Goal & User Stories||
|Sprint 4 Goal|-El objetivo principal para el presente sprint es poder culminar satisfactoriamente las historias de usuario acordadas por el equipo, completando así el Product Backlog del proyecto.|
|Sprint 4 Velocity|<p>-US-06 Buscar inmuebles (Story Point 8)</p><p>-US-12 Categorizar inmuebles (Story Point 5)</p><p>-US-25 Dejar comentarios sobre propiedades (Story Point 3)</p><p>-US-24 Leer comentarios sobre propiedades (Story Point 3)</p><p>-US-26 Responder comentarios sobre propiedades (Story Point 3)</p><p>-US-20 Optimizar el rendimiento de la aplicación (Story Point 2)</p>|
|Sum of Story Point|24|


#### Sprint Backlog
Se trata de una lista de todas las tareas que el equipo de desarrollo ha acordado completar durante un sprint específico. Esta lista se crea en base del Product Backlog, que contiene todas las funcionalidades y requisitos del producto.

<table><tr><th colspan="1" valign="top">Sprint #</th><th colspan="7" valign="top">Sprint 4</th></tr>
<tr><td colspan="2" valign="top">User Story</td><td colspan="6" valign="top">Work-Item/Task</td></tr>
<tr><td colspan="1" valign="top">Id</td><td colspan="1" valign="top">Title</td><td colspan="1" valign="top">Id</td><td colspan="1" valign="top">Title</td><td colspan="1" valign="top">Description</td><td colspan="1" valign="top">Estimation (Hours)</td><td colspan="1" valign="top">Assigned To</td><td colspan="1" valign="top">Status (To-do / InProcess / ToReview / Done)</td></tr>
<tr><td colspan="1" rowspan="2" valign="top">US-06</td><td colspan="1" rowspan="2" valign="top">Buscar inmuebles</td><td colspan="1" valign="top">T01</td><td colspan="1" valign="top">Implementar sistema de búsqueda</td><td colspan="1" valign="top">Implementar un sistema de búsqueda avanzada que permita a los usuarios filtrar los inmuebles según sus necesidades.</td><td colspan="1" valign="top">3 hours</td><td colspan="1" valign="top">Angie Ruiz</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">T02</td><td colspan="1" valign="top">Implementar el servicio de propiedades</td><td colspan="1" valign="top">Implementar el servicio de propiedades en el backend.</td><td colspan="1" valign="top">4 hours</td><td colspan="1" valign="top">Angie Ruiz</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="2" valign="top">US-12</td><td colspan="1" rowspan="2" valign="top">Categorizar inmuebles</td><td colspan="1" valign="top">T01</td><td colspan="1" valign="top">Implementación del Toolbar con las categorías.</td><td colspan="1" valign="top">Crear una interfaz de administración que permita a los usuarios categorizar los inmuebles en diferentes tipos, como apartamentos, casas y locales comerciales.</td><td colspan="1" valign="top">3 hours</td><td colspan="1" valign="top">Leydi Aro</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">T02</td><td colspan="1" valign="top">Implementar un sistema de vista</td><td colspan="1" valign="top">Implementar un sistema para que los usuarios puedan visualizar solo las publicaciones con cierta categoría seleccionada.</td><td colspan="1" valign="top">2 hours</td><td colspan="1" valign="top">Leydi Aro</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="2" valign="top">US-25</td><td colspan="1" rowspan="2" valign="top">Dejar comentarios sobre propiedades</td><td colspan="1" valign="top">T01</td><td colspan="1" valign="top">Desarrollo del servicio de comentarios</td><td colspan="1" valign="top">Implementación en el backend del bounded context que incluya el sistema de comentarios.</td><td colspan="1" valign="top">5 hours</td><td colspan="1" valign="top">Edwin Lopez</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">T02</td><td colspan="1" valign="top">Diseño de interfaz</td><td colspan="1" valign="top">Diseñar una interfaz de usuario intuitiva que permita a los usuarios dejar comentarios y calificaciones sobre las propiedades.</td><td colspan="1" valign="top">4 hours</td><td colspan="1" valign="top">Edwin Lopez</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">US-24</td><td colspan="1" valign="top">Leer comentarios sobre propiedades</td><td colspan="1" valign="top">T01</td><td colspan="1" valign="top">Implementación de la vista de comentarios</td><td colspan="1" valign="top">Mostrar los comentarios y calificaciones de los usuarios en la página de detalles de cada propiedad.</td><td colspan="1" valign="top">3 hours</td><td colspan="1" valign="top">Jhan Salazar</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">US-26</td><td colspan="1" valign="top">Responder comentarios sobre propiedades</td><td colspan="1" valign="top">T01</td><td colspan="1" valign="top">Desarrollo del servicio de comentarios</td><td colspan="1" valign="top">Implementación del backend para poder responder a comentarios.</td><td colspan="1" valign="top">3 hours</td><td colspan="1" valign="top">Julio Asillo</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="2" valign="top">US-20</td><td colspan="1" rowspan="2" valign="top">Optimizar el rendimiento de la aplicación</td><td colspan="1" valign="top">T01</td><td colspan="1" valign="top">Carga y optimización</td><td colspan="1" valign="top">Realizar pruebas de carga y optimización para mejorar los tiempos de carga de la aplicación y la respuesta del servidor.</td><td colspan="1" valign="top">3 hours</td><td colspan="1" valign="top">Edwin Lopez</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">T02</td><td colspan="1" valign="top">Técnicas de almacenamiento</td><td colspan="1" valign="top">Implementar técnicas de almacenamiento en caché para reducir la carga en el servidor y mejorar la velocidad de la aplicación.</td><td colspan="1" valign="top">3 hours</td><td colspan="1" valign="top">Edwin Lopez</td><td colspan="1" valign="top">Done</td></tr>
</table>


#### ` `Development Evidence for Sprint Review

<table><tr><th colspan="1" valign="top">&emsp;Repository</th><th colspan="1" valign="top">Branch</th><th colspan="1" valign="top">Commit id</th><th colspan="1" valign="top">Commit Message</th><th colspan="1" valign="top">Commited on (Date)</th></tr>
<tr><td colspan="1" rowspan="12" valign="top"><p><https://github.com/LogicMinds-Group/backEnd></p><p></p></td><td colspan="1" valign="top">Origin/ Feature/forums</td><td colspan="1" valign="top">f61bc64ee8a0fcac2bc9ca85106c10487ed6cc24</td><td colspan="1" valign="top">Merge pull request #3</td><td colspan="1" valign="top">Fri Nov 17 2023</td></tr>
<tr><td colspan="1" valign="top">Origin/ Feature/forums</td><td colspan="1" valign="top">437e1b79bb87b7ba81c0407279c735260e06e6eb</td><td colspan="1" valign="top">Controllers forum completed</td><td colspan="1" valign="top">Fri Nov 17 2023</td></tr>
<tr><td colspan="1" valign="top">Origin/ Feature/forums</td><td colspan="1" valign="top">a09f831688e0475c3e73b16e772836ae426a7560</td><td colspan="1" valign="top">Creating packages and classes</td><td colspan="1" valign="top">Fri Nov 17 2023</td></tr>
<tr><td colspan="1" valign="top">Origin/ Feature/ posts-update</td><td colspan="1" valign="top">e044fade21d9b390bd66a1c5212a335859285603</td><td colspan="1" valign="top">Merge pull request #4</td><td colspan="1" valign="top">Fri Nov 18 2023</td></tr>
<tr><td colspan="1" valign="top">Origin/ Feature/ posts-update</td><td colspan="1" valign="top">6defd8c668a2054ac1b8e96af1a5c873afa31f91</td><td colspan="1" valign="top">add property for bounded context Posts</td><td colspan="1" valign="top">Fri Nov 18 2023</td></tr>
<tr><td colspan="1" valign="top">Origin/ Feature/ post-properties</td><td colspan="1" valign="top">ea9510502ccd323057385571030a5bc3a6bc290f</td><td colspan="1" valign="top">Merge pull request #5</td><td colspan="1" valign="top">Fri Nov 18 2023</td></tr>
<tr><td colspan="1" valign="top">Origin/ Feature/ post-properties</td><td colspan="1" valign="top">b66dd6c4c9ea274bc6d8098f809a65b71ab7c95a</td><td colspan="1" valign="top">POST for user completed</td><td colspan="1" valign="top">Fri Nov 17 2023</td></tr>
<tr><td colspan="1" valign="top">Origin/ Feature/ post-properties</td><td colspan="1" valign="top">a4f1e7dcd4028262bc47139bca60e891094c4fb7</td><td colspan="1" valign="top">CRUD user completed</td><td colspan="1" valign="top">Fri Nov 17 2023</td></tr>
<tr><td colspan="1" valign="top">Origin/ Feature/ post-properties</td><td colspan="1" valign="top">6dbaae36c34a970452fd4d70754d6b0e7778f4a7</td><td colspan="1" valign="top">Rated user was completed</td><td colspan="1" valign="top">Fri Nov 17 2023</td></tr>
<tr><td colspan="1" valign="top">Origin/ Feature/ post-properties</td><td colspan="1" valign="top">24c7b961d774c50d0013914c4e61a374296737b5</td><td colspan="1" valign="top">Message apis completed</td><td colspan="1" valign="top">Sa Nov 17 2023</td></tr>
<tr><td colspan="1" valign="top">Origin/ Feature/ post-properties</td><td colspan="1" valign="top">c4d57880f230ae55c304c0e6c0e65b1ca2a74972</td><td colspan="1" valign="top">Emergency login added</td><td colspan="1" valign="top">Sa Nov 17 2023</td></tr>
<tr><td colspan="1" valign="top">revert-5-feature/post-properties</td><td colspan="1" valign="top">4cf36eac2f62804080fd0091f899fe2b61438bba</td><td colspan="1" valign="top">Merge pull request #6</td><td colspan="1" valign="top">Sa Nov 18 2023</td></tr>
<tr><td colspan="1" rowspan="7" valign="top"><https://github.com/LogicMinds-Group/frontEnd></td><td colspan="1" valign="top">Develop</td><td colspan="1" valign="top">4b5eef7fe9621f016459fda66189f01f52a557c1</td><td colspan="1" valign="top">Message completed</td><td colspan="1" valign="top">Fri Nov 17 2023</td></tr>
<tr><td colspan="1" valign="top">Develop</td><td colspan="1" valign="top">3341d401b6642d6af545ba925f0ebb3e459fce84</td><td colspan="1" valign="top">Api conection useers</td><td colspan="1" valign="top">Fri Nov 17 2023</td></tr>
<tr><td colspan="1" valign="top">Develop</td><td colspan="1" valign="top">442d5fbdf6689163acab030dcaf17ad68f2d044a</td><td colspan="1" valign="top">Forum completed</td><td colspan="1" valign="top">Sa Nov 18 2023</td></tr>
<tr><td colspan="1" valign="top">Develop</td><td colspan="1" valign="top">ef5c7fb710c74fed58164522b672e6f94d535051</td><td colspan="1" valign="top">Desing ajusted</td><td colspan="1" valign="top">Sa Nov 18 2023</td></tr>
<tr><td colspan="1" valign="top">Develop</td><td colspan="1" valign="top">056ac0cfbf481ea1925a952f1ffdde0bb796fffd</td><td colspan="1" valign="top">Api properties connected</td><td colspan="1" valign="top">Sa Nov 18 2023</td></tr>
<tr><td colspan="1" valign="top">Develop</td><td colspan="1" valign="top">57dd19241fa7d4556a9862da8bb494ef15ea6e80</td><td colspan="1" valign="top">avanced</td><td colspan="1" valign="top">Th Nov 23 2023</td></tr>
<tr><td colspan="1" valign="top">Develop</td><td colspan="1" valign="top">9d5c7b7c71bea39fa0ff2e46ab88ea64a4c7e6d5</td><td colspan="1" valign="top">Completed</td><td colspan="1" valign="top">Sa Nov 24 2023</td></tr>
</table>




JIRA SOFTWARE:

Para la gestión y vida del proyecto utilizamos Jira Software, donde documentamos los sprint, las historias de usuario, las tareas acordadas por cada historia de usuario y que participante del equipo este asociado con dicha historia.

Sprint N°04

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 002](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/d757bdd0-4512-43ea-9a74-e1792ca1dbca)

-Tareas relacionadas con la US-06 Buscar inmuebles 

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 003](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/7e7222e4-2b21-4cc8-81d3-346e83d424e2)

- Tareas relacionadas con la US-12 Categorizar inmuebles

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 004](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/d620572f-5209-47a2-a260-61422ca413bd)

- Tareas relacionadas con la US-25 Dejar comentarios sobre propiedades 

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 005](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/5a33af6b-5f32-435c-98eb-9c74102f6f07)

- Tareas relacionadas con la US-24 Leer comentarios sobre propiedades 

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 006](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/3482ee31-5ec9-411d-a87a-10a87a487d18)

- Tareas relacionadas con la US-26 Responder comentarios sobre propiedades 

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 008](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/7c2c5529-1854-4e16-a904-705b6b8bf7dc)

- Tareas relacionadas con la US-20 Optimizar el rendimiento de la aplicación 

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 007](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/fb9651f3-0187-43bb-aa5d-c65df2439e41)


#### Testing Suite Evidence for Sprint Review
Se muestra los siguientes Tests de las historias de usuario más relevantes según el equipo.
#####PostService.feature:
![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 009](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/30010d6d-c170-44eb-932f-0ede0d0d0151)

#####PropertyService.feature:
![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 010](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/9f6e17f7-508b-48f3-acb9-c3a20bc06373)



#### Execution Evidence for Sprint Review
Durante este sprint, se diseñó y desarrolló la última iteración con meticulosa consideración de patrones de diseño, una paleta de colores apropiada.

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 011](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/2bbbc5ca-8b89-41b3-9e95-f2a39fb70206)

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 012](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/8a748349-7962-4866-b6fb-e4673ba4bc46)

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 013](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/d7af4eb4-9e66-4767-a962-f6ebd83207f5)

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 014](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/45a4b853-bdf0-4f44-b7da-801009aa7ae6)

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 015](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/4d44049d-8bef-4ff4-a293-f6990d2ae35d)

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 016](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/fc7a0967-c591-40e6-a8fc-0b634694c0a8)


#### Documentation Evidence for Sprint Review
En esta sección se visualizará los endpoints implementados en el Backend. Se utilizó Swagger para la documentación de las API's como se puede ver a continuación:

API de Posts:
![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 017](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/b6d8137c-b08d-4cc8-abef-1748354b708d)

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 018](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/b4ef6013-ae54-4a0f-af91-c070b77747b2)

API de Users:

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 019](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/2499b039-d8be-455a-87d1-f6b05bc986ef)

API de Properties:

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 020](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/bfead3ab-d4eb-40f2-b1be-474d2d22e795)


Otras API's:
![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 021](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/548feb95-8b8d-4fe5-a4b6-baeadfcf4adb)

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 022](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/621001e9-0cae-4e96-8257-579f446c1309)

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 023](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/8494de6c-5690-4846-aa64-222829316528)

MySQL - AWS

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 024](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/8cac9e21-a8f6-415e-905a-252ddd9eac4e)

Link despliegue del Backend:


#### Software Deployment Evidence for Sprint Review
En esta sección se presentará capturas del despliegue exitoso de la aplicación

Link del despliegue: Link: https://renstate2-0.web.app/home 

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 025](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/67e26aa4-a53b-44c1-98d3-3a64d2608773)

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 026](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/eb3f554e-4d2c-48f3-9165-ab300c3154eb)


#### Team Collaboration Insights during Sprints
Se evidencia la colaboración de todos los integrantes del equipo para el desarrollo del Backend y Frontend:

Frontend:

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 027](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/430265fc-2164-4bb1-9209-29fda6be62b6)

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 028](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/a35e9212-3ed5-47ee-8a9a-fdb8d1679124)

Backend:

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 029](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/20240671-5d0d-4314-97d2-3c162f84bbce)

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 030](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/89995f4c-dd91-423c-a346-f35484aaa2bb)


1. # **CONCLUSIONES**
Para esta entrega del trabajo hemos identificado la problemática y a la vez planteamos varias soluciones que tenga aplicaciones de ingeniería de software, entonces podemos concluir que hasta el momento tenemos diseños preparados para poder empezar a programar o desarrollar la aplicación, para posteriormente ver los resultados analizados en esta entrevista.

- **Análisis Competitivo sólido**: El análisis de competidores fue esencial para comprender el mercado y las tendencias actuales en el sector de alquileres de propiedades. Esto nos permitió identificar oportunidades para diferenciarnos y mejorar.

- **Diseño Centrado en el Usuario:** El diseño en Figma se basó en la experiencia del usuario, asegurando que la navegación y la interfaz fueran intuitivas y atractivas para los posibles usuarios.

- **Cumplimiento de las Mejores Prácticas de Diseño**: Se aplicaron principios de diseño web modernos, como la responsividad, la accesibilidad y el uso de imágenes optimizadas para garantizar una experiencia de usuario de alta calidad.
- **Interacción Satisfactoria**: La implementación de JavaScript permitió agregar interacciones dinámicas, como filtros de búsqueda en tiempo real y efectos de desplazamiento suave, lo que mejoró la interacción del usuario en el sitio web.
- **Colaboración Efectiva**: El uso de GitHub para el control de versiones facilitó la colaboración eficiente entre los miembros del equipo, lo que permitió un desarrollo fluido y un seguimiento preciso de los cambios.
- **Optimización de Rendimiento**: Se realizaron esfuerzos para optimizar el rendimiento del sitio web, incluida la compresión de imágenes y la minimización de solicitudes HTTP, lo que resultó en tiempos de carga más rápidos y una experiencia más fluida para los usuarios.
- **Seguridad y Privacidad**: Se implementaron prácticas de seguridad para proteger los datos de los usuarios y garantizar que la información personal estuviera segura.
- **Pruebas Rigurosas**: Se realizaron pruebas exhaustivas en diferentes navegadores y dispositivos para garantizar la compatibilidad cruzada y la funcionalidad sin problemas en una variedad de situaciones.
- **Feedback de Usuarios**: Se recopiló y se tuvo en cuenta el feedback de los usuarios durante el proceso de desarrollo y se realizaron ajustes en el diseño y la funcionalidad según las sugerencias recibidas.

- **Planificación y Gestión de Proyectos**: La planificación adecuada y la gestión de proyectos son fundamentales para evitar retrasos y mantener el proyecto dentro del alcance y el presupuesto establecidos.


1. # **VIDEO ABOUT THE TEAM**

"Video About The Team" es una herramienta audiovisual que permite presentar al equipo de trabajo de una empresa, organización o proyecto. Esta producción audiovisual tiene como objetivo principal dar a conocer a los miembros del equipo, sus roles y responsabilidades, así como mostrar su experiencia, habilidades y logros. A través de este video, se busca crear una conexión entre el equipo y el público objetivo, generando confianza y mostrando la profesionalidad y compromiso del equipo.

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 031](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/e634b108-e75a-499e-910d-9bd983a15cd7)

Link: [Video About-the-Team](https://www.youtube.com/watch?v=_gASB4oFDzk)

1. # **VIDEO ABOUT THE PRODUCT**
El "Video About The Product" es una herramienta publicitaria que nos ayuda a promocionar nuestra aplicación y conseguir usuarios, utilizando frases precisas y contenido audiovisual casual.

![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 032](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/fa125d83-6c41-41c3-b913-be771c04bfb0)


Link: <a name="_hlt151726271"></a>[About-The-Product Open Source](https://youtu.be/kFc2CH9FLnA)


1. ##**ANEXOS**

Link del Repositorio de GitHub: <https://github.com/LogicMinds-Group>

Landing page: <https://logicminds-group.github.io/landingPage/>


|**Sección**|**Características del video**|**Sobre el contenido**|**Integración y entrega**|
| :- | :- | :- | :- |
|Prototypes Navigation / Product Navigation|<p>Cantidad de videos: 1 </p><p>` `Nomenclatura:                             upc-pre-202302-si729-SW51-Renstate-prototype navigation-sprint-1</p><p>Formato: .mp4 </p><p>Duración: 1min 40 seg.</p>|Consolida demostración del flujo de navegación del Landing Page y las aplicaciones, priorizando los user flows relacionados con el core business.|<p>Enlace Landing Page  navigation:[navigation_landing.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201b293_upc_edu_pe/EfRTWqszX75IoCvIH11T2YUBPD8wxaMRyvO6JU3Az3-MBg?e=pgFItI) ![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 033](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/65e6b252-98ae-41de-8ded-a12e7292cb70)</p><p>

Descripción generada automáticamente](Aspose.Words.3c73ee82-cdc5-45de-bf7f-2f2d85520d2c.033.png)   </p>|

Video About the Product: [About-The-Product Open Source](https://youtu.be/kFc2CH9FLnA)

Video About the Team: [Video About-the-Team](https://www.youtube.com/watch?v=_gASB4oFDzk)

Reunión de equipo:
![Aspose Words 3c73ee82-cdc5-45de-bf7f-2f2d85520d2c 034](https://github.com/LogicMinds-Group/Informe-Final/assets/83793319/302f3f04-f007-4a4e-ab0e-43ff4a356285)


1. <a name="_toc131683654"></a><a name="_toc145263648"></a>**BIBLIOGRAFIA**

Lozano, A. (2021, mayo 11). Las 3 mejores apps para tu departamento de inversión en Chile [Entrada de blog]. Inversión Fácil. <https://blog.inversionfacil.com/las-3-mejores-apps-para-tu-departamento-de-inversi%C3%B3n-en-chile> [Fecha de consulta 14/04/2023]

Instituto Nacional de Estadística e Informática. (s. f.). Vivienda y servicios básicos [Página web]. Índice Temático - Housing. <https://m.inei.gob.pe/estadisticas/indice-tematico/housing/> [Fecha de consulta 14/04/2023]

W3Schools. (s. f.). HTML5 Syntax [Página web]. <https://www.w3schools.com/html/html5_syntax.asp>





