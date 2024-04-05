

# Universidad Peruana de Ciencias Aplicadas  
### INFORME DEL TRABAJO 1 (TB1)
![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/c8a24a74-515a-436b-b7b9-ea1b2e418e60)

**Curso:** Desarrollo de Aplicaciones Open Source

**Sección:** SW54

**Profesor:** Elio Jefferrson Navarrete Vilca

**Carrera:** Ingeniería de Software

**Ciclo:** 2024-01

**Startup:** TripTeam

**Producto:** TripMate

### Integrantes:

| Nombre                            | Código       |
|-----------------------------------|--------------|
| Adrián Enrique Jesús Palma Obispo| u202210066   |
| Paolo Del Carmen Martinez Villanueva | 202010039 |
| Bárbara Antonella Espinoza Delgado| u201911727 |
| Jeremy Joel Quispe Andia         | u202216279   |
| Leonel Alfaro Cumba         | u20201A930   |

### Marzo del 2024

### Registro de Informes

| Versión   | Fecha       | Autor      | Descripción                                                                                      | Estado    |
|-----------|-------------|------------|--------------------------------------------------------------------------------------------------|-----------|
| 1.0       |  2024/03/22| Quispe Andia, Jeremy Joel | Creación del documento de trabajo en formato markdown. | Completo  |
| 1.1       |  2024/03/22    | |ante la fase de diseño, arquitectura propuesta y diseños de interfaz.               | Completo  |
| 1.2       |  2024/03/22    | Adrián Palma |implementación de funcionalidades, obstáculos encontrados y decisiones tomadas.     | En Proceso|
| 1.3       |  2024/03/22    | |de la entrega final del proyecto, implementación completa y pruebas realizadas.    | Pendiente |


### Project Report Collaboration Insights




### Tabla de contenidos
- [Capítulo I: Introducción](#cap%C3%ADtulo-i-introducci%C3%B3n)
- [Capítulo II: Requirements Elicitation & Analysis](#cap%C3%ADtulo-ii-requirements-elicitation--analysis)
- [Capítulo III: Requirements Specification](#cap%C3%ADtulo-iii-requirements-specification)
- [Capítulo IV: Product Design](#cap%C3%ADtulo-iv-product-design)
- [Capítulo V: Product Implementation, Validation & Deployment](#cap%C3%ADtulo-v-product-implementation-validation--deployment)

### Studen Outcome


| Criterio específico | Acciones Realizadas | Conclusiones |
|---------------------|----------------------|--------------|
| Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software. | 2024/03/22 | |
| Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software. | 2024/03/22 | |

### Capítulo I: Introducción
- 1.1. Startup Profile
  - 1.1.1. Descripción de la Startup  
  TripTeam es una startup conformada por 5 integrantes de la carrera de Ingenieria de Software de 5to y 6to ciclo de la Universidad Peruana de Ciencias Aplicadas.
Nuesta misión es crear plataformas web con el proposito de facilitar y organizar las actividades de las personas y ayudar a nuestros usuarios a optimizar su tiempo, mientras que nuesta visión es ser la primera opción de ayuda web de los usuarios.  
Como startup hemos notado que aun con todos los avances tecnologicos existentes y la variedad de plataformas dirigidas a viajeros, aun existen problemas de optimización de tiempo al planear un viaje y de insatisfaccion posterior al viaje realizado, por lo que en esta oportunidad hemos realizado una plataforma web que busca ayudar a las personas viajeras con
  los problemas de la desorganización, gastos innecesarios, pérdida de tiempo y no optar por las mejores opciones. Por ese motivo, nuestro objetivo como startup
  se enfoca en ayudar a los viajeros a tener un viaje organizado y satisfactorio.
  Para lograrlo, contamos con una plataforma que, mediante filtros, mostrará a los usuarios las aerolíneas, hoteles, restaurantes y actividades de
  entretenimiento que más se adecuen a sus preferencias y presupuestos, se mostrará más de una opción con imágenes, una descripción y los precios, los cuales
  serán igual o menores al que se indique para que la persona y así pueda elegir el que más le guste sin necesidad de entrar a varias páginas, investigar por
  horas y tantear, optimizando el tiempo del usuario. También se le hará un itinerario ordenado según las horas de vuelo y horarios de los restaurantes o
  lugares de interés los cuales estarán sujetos a cambios repentinos por motivos externos y serán notificados por nosotros a los usuarios en el menor tiempo
  posible. que el usuario puede tomar como recomendación para cada día de estancia. Además, se mostrarán las promociones que ofrecen las empresas desde sus
  páginas o descuentos exclusivos los cuales serán proporcionados por las empresas y cadenas con las que formaremos convenios o acuerdos para mostrar a los usuarios sus servicios a cambio de comisiones.
Creemos que con esta plataforma la expreriencia previa y posterior a un viaje sera mas facil y placentera, animando a mas personas a viajar sin el temor de pasar malos ratos durante su experiencia.

  - 1.1.2. Perfiles de integrantes del equipo

| Integrante                           | Foto | Descripción del Perfil                                                                                          |
|-------------------------------------|-------|-----------------------------------------------------------------------------------------------------------|
| Adrián Enrique Jesús Palma Obispo|![image](https://github.com/TripTeamOrganization/Informes/assets/98995070/79dbf73c-6e06-47fe-a345-531161e88620)|Curso la carrera de Ingeniería de Software de 5to Ciclo. Experiencia trabajando en equipo, aportando en diversas áreas y ayudando en tecnologías. Capacidad para aprender rápido. Curioso y puntual. |
| Bárbara Antonella Espinoza Delgado  |![image](https://github.com/TripTeamOrganization/Informes/assets/98995070/712a15a3-030d-4570-ba72-724b1268f23a)|Estudiante de Ingeniería de Software de 6to ciclo. Experiencia en dirección de grupos, SQL, redacción, búsqueda de información, exposiciones y cumplimiento de tareas. Estricta y puntual. |
| Jeremy Quispe                        |![image](https://github.com/TripTeamOrganization/Informes/assets/98995070/a1230b61-493e-4634-9eeb-fe7993998983)| Cursando el 5to ciclo de Ingeniería de Software en la UPC. Interés en crear soluciones tecnológicas con impacto positivo en la sociedad. Agradece a la universidad por brindar recursos para su desarrollo. |
| Leonel Alfaro Cumba                 |![image](https://github.com/TripTeamOrganization/Informes/assets/98995070/018abefb-69f2-4693-b384-faa43ccc95c0)|Estudiante de Ingeniería de Software con gran interés en la tecnología y la innovación. Motivado por ampliar conocimientos y desarrollarse constantemente. |
| Paolo Del Carmen Martinez Villanueva |![image](https://github.com/TripTeamOrganization/Informes/assets/98995070/1ffcc794-1c38-4461-9844-372f11b56a28)|Estudiante del 6to ciclo de Ingeniería de Software. Conocimientos intermedios en programación. Responsable, ordenado y trabajador. Comprometido a apoyar al equipo y adquirir nuevos conocimientos. |
- 1.2. Solution Profile
  - 1.2.1. Antecedentes y problemática  
    **¿Cuál es el problema?**
    El problema a resolver es la mala elección de servicios, gastos innecesarios, cambios imprevistos de horarios y desorganización cuando se va a hacer un viaje
    a un nuevo destino.

    **¿Cuándo sucede el problema?**
    El problema sucede cuando las personas quieren o tienen que viajar a un lugar en el que no conocen las mejores opciones que estén dentro de su presupuesto,
    preferencias y horarios.

    **¿Dónde sucede el problema?**
    El problema sucede en el lugar donde se esté buscando información sobre las aerolíneas, hoteles, restaurantes y actividades de entretenimiento del lugar al
    que se planea viajar.

    **¿A quién se le presenta el problema? ¿Cuál es tu público objetivo?**
    El problema se le presenta a las personas que quieren o necesitan viajar y desconocen de las mejores opciones para tener un viaje organizado y satisfactorio.
    Nuestro público objetivo son las familias que quieran pasar sus vacaciones viajando pero sin gastar dinero de más y los viajeros de clase alta que buscan las
    opciones de más alto lujo y calidad.

    **¿Por qué sucede el problema? ¿Qué situación ocasiona el problema?**  
    El problema sucede porque las personas muchas veces no tienen el tiempo para ver una por una a cada empresa y comparar todas las opciones manualmente, esto
    puede ocasionar que las personas se guíen por la popularidad o publicidad de las empresas y terminen optando por una mala opción, y revisar uno por uno llega
    a ser tedioso y muchas veces las personas terminan optando por una opción que no les terminó de satisfacer o que terminan siendo cambiadas a último momento
    debido a desconocimiento de sus cambios de hora. La situación que ocasiona este problema es que existen miles de empresas que están relacionadas con el
    turismo, como las aerolíneas, hoteles y restaurantes, todos con diversos precios, horarios y calidades que resulta muy difícil poder comparar todas esas
    opciones manualmente y elegir la mejor de todas.

    **¿Cómo sucede el problema? ¿Cuáles son las precondiciones para que se presente el problema?**
    El problema ocurre en situaciones en las que las personas deben organizar un viaje pero al desconocer de todas las opciones que hay para los vuelos,
    hospedajes y restaurantes, intentan comparar solo unas cuantas opciones y eligen la que creen que es más conveniente por el reconocimiento de la empresa pero
    en ocasiones el servicio no termina siendo del agrado de la persona o dejaron pasar una mejor opción en cuanto a precios y/o calidad. Las precondiciones para
    que el problema se presente es ser una persona que está por realizar un viaje, que desconoce las opciones y condiciones de las aerolíneas, hoteles y
    restaurantes, que busca optimizar su tiempo y busca las mejores opciones para su viaje.

    **¿Cuánto impacto económico genera este problema? Representar datos estadísticos del segmento que tiene el problema.**
    La falta de conocimiento de los precios de cada servicio que se necesita al hacer un viaje puede ocasionar que las personas tengan que extender sus
    presupuestos y hacer gastos de más y muchas veces en un servicio que no termina por satisfacer al cliente. Según Von Berg, en la web de GoBankingRates, el
    gasto diario en un viaje es de 150 dólares por día para destinos europeos, sin embargo, muchas veces este costo puede llegar a ser menor si se tiene
    organización y conocimiento. Según Salomon Asmar (2023), Alrededor de 36% de las personas se endeudan para ir de viaje pero cerca de 82% no logra pagar las
    deudas a fin de mes. Además, según una encuesta de lastminute.com, indica que sólo el 1% de los consultados logra cumplir al 100%. Esto indica que las
    personas usualmente cometen gastos muy elevados por desinformación y falta de cultura de ahorro, lo que puede llegar a costar varios sueldos mensuales e
    inclusive ocasionar deudas y aun así no asegurar un viaje totalmente gratificante.

  - 1.2.2. Lean UX Process
    - 1.2.2.1. Lean UX Problem Statements  
      Hacer un viaje es un gusto costoso y muchas veces se debe ampliar el presupuesto inicial para mejorar la experiencia. ¿Cómo podemos ayudar a que las
      personas economicen sus viajes y aún así tener los mejores servicios posibles?

      A pesar que existen grandes cadenas de hoteles, aerolíneas famosas y restaurantes mundialmente reconocidos, muchas veces no terminan de satisfacer a los
      viajeros más exigentes. ¿Cómo se podría ayudar a las personas que buscan lujos a tener un viaje perfecto y a su gusto?

      Notamos que la información en internet es abundante al igual que las opciones, las personas deben invertir grandes cantidades de tiempo en investigar qué
      aerolíneas, hoteles y restaurantes escoger para su viaje y comparar sus precios, horarios y reseñas puede ser enredado y causar malas decisiones. ¿Existe
      alguna forma de proporcionar toda la información y opciones que los viajeros necesitan en una sola plataforma donde las opciones se muestran según los
      filtros ingresados?
      
      En ocaciones, cuando se tienen todas las opciones seleccionadas, ocurren cambios de hora, cancelaciones de vuelos o suspensión de atención y esta información
      tarda en llegar al usuario. ¿Cómo podríamos evitar que los viajeros se vean obligados a cambiar sus planes a última hora?

    - 1.2.2.2. Lean UX Assumptions  
      **Business Outcomes**  
      Asumimos que nuestros clientes y usuarios necesitan tener las mejores opciones para todo lo que requiera un viaje según sus preferencias y presupuesto.

      Esta necesidad se puede resolver por medio del filtrado, el cual mostrará solamente las opciones que se adecuen a las preferencias del usuario y no tenga
      que perder tiempo investigando empresa por empresa manualmente.

      Mis clientes principales son aquellos usuarios que quieran hacer un viaje y busquen la mayor satisfacción posible.

      El valor #1 qué quiere un cliente de este servicio es poder planificar un viaje satisfactorio y lo más perfecto posible en el menor tiempo posible y de la
      manera más sencilla.

      El cliente puede obtener beneficios adicionales como poder ver descuentos que ofrecen las empresas.

      Obtendré a mis clientes mediante la promoción del producto en grupos de viajeros y publicidad en internet.

      Las ganancias se obtendrán mediante la versión premium que le otorgara a los usuarios opciones mucho más ajustadas a sus preferencias, además de comisiones
      que se recibirán por parte de hoteles y restaurantes por cada usuario que opte por adquirir su servicio.

      Mi competencia principal serán apps como TripIt, AirBnB y Expedia, las cuales son plataformas que se encargan de recomendar opciones para viajes a las
      personas.

      Tomaremos ventaja sobre ellos incluyendo filtros precisos, ingreso de presupuestos y mostrando las promociones vigentes.

      A diferencia de estas app mencionadas anteriormente, TripMate muestra recomendaciones que cumplan estrictamente con los filtros, presupuestos y preferencias
      del usuario.

      El riesgo con la app es que puede que la información que se proporciona no sea suficiente o difícil de entender debido a que muchas empresas recortan o no
      proporcionan al 100% sus especificaciones.

      Se resolverá mediante la adición de reviews de viajeros reales que puedan proporcionar información adicional según su experiencia.
      
      **User Outcomes**  
      ¿Quién es el usuario?  
      Personas viajeras que busquen la mayor satisfacción posible durante todo su viaje.

      ¿Dónde encaja el producto?  
      En el tiempo previo a la realización del viaje.

      ¿Qué problemas tiene el producto y cómo se pueden resolver?  
      Es posible que por los filtros proporcionados y la poca variedad que se encuentra en el país de destino, solo se muestre unas cuantas opciones o ninguna,
      esto se puede resolver mostrando una opción que pase un mínimo de costo del presupuesto especificado.

      ¿Cuándo y cómo es usado el producto?  
      Cuando el usuario quiera realizar un viaje y debe planificarlo en un tiempo menor al promedio y quiera las mejores opciones en el destino al que irá. Una
      vez se esté en la plataforma ingresará sus filtros y presupuesto para el vuelo, hospedaje, restaurantes y actividades de entretenimiento para que la
      plataforma proceda a mostrar todas las opciones y adquirir, reservar o tener en cuenta las opciones escogidas.

      ¿Qué características son importantes?  
      Interfaz amigable, sencillez de uso y apta para todo tipo de necesidad de los usuarios, filtros fáciles de encontrar e ingresar, e información precisa de
      cada opción mostrada.

      ¿Cómo debe verse nuestro producto y cómo debe comportarse?  
      La aplicación debe tener una paleta de colores agradable a la vista, con imágenes que muestran la satisfacción de los viajeros y con una fuente de letra
      legible y lo suficientemente grande para que todas las personas que quieran usar la plataforma puedan leer fácilmente. Cuando un usuario selecciona una
      opción se la añadirá a un carrito de compras y en caso la compra no pueda ser realizada desde la plataforma se redirigirá al usuario a la página principal
      de la empresa y le mostrará al usuario la opción que eligió.

    - 1.2.2.3. Lean UX Hypothesis Statements  
      **Creemos** que mostrar las opciones de aerolíneas, hoteles y restaurantes en una sola plataforma optimizará el tiempo de los viajeros al planificar sus viajes.  
      **Sabremos que** estamos bien.  
      **Cuando** la cantidad de tiempo promedio que se invierte en investigar opciones para un viaje se ha reducido.  

      **Creemos** que el uso de filtros e ingreso de presupuesto para cada gasto del viaje hará que las personas eviten gastar de más en sus viajes.  
      **Sabremos que** estamos bien.  
      **Cuando** veamos que los usuarios viajan más a menudo y la cifra de endeudamientos por viaje se reduce.  

      **Creemos** que mostrar opciones de aerolíneas, hoteles y restaurantes de calidad y mundialmente reconocidas hará que los viajeros sin límite de presupuesto
      tengan viajes de lujo satisfactorios.  
      **Sabremos que** estamos bien.  
      **Cuando** veamos que estas personas dejan opiniones muy positivas de su experiencia de viaje.
      
      **Creemos** que informar de la manera más rápida posible a nuestros usuarios sobre cambios de hora de vuelo, suspensión de atención o cambios de horario en los
      servicios elegidos hará que los viajeros eviten pasar un mal rato durante su viaje.  
      **Sabremos que** estamos bien.  
      **Cuando** veamos que las personas cambian de servicios previamente al viaje y no mientras ya están en su destino.  

      **Creemos** que generar un itinerario de viaje a nuestros usuarios hará que los usuarios tengan un viaje más ordenado.  
      **Sabremos que** ha resultado.  
      **Cuando** los usuarios hagan un mayor uso de la opción de generar itinerario al usar por segunda vez la plataforma.  


    - 1.2.2.4. Lean UX Canvas
      <table>
            <tr>
              <td valign="top"><p><b>Problema de negocio</b></p><br>
                <p>Hacer un viaje es un gusto costoso y muchas veces se debe ampliar el presupuesto inicial para mejorar la experiencia. ¿Cómo podemos ayudar a que las personas economicen sus viajes y aún así tener los mejores servicios posibles?</p><br>
                <p>A pesar que existen grandes cadenas de hoteles, aerolíneas famosas y restaurantes mundialmente reconocidos, muchas veces no terminan de satisfacer a los viajeros más exigentes. ¿Cómo se podría ayudar a las personas que buscan lujos a tener un viaje perfecto y a su gusto?</p><br>
                <p>Notamos que la información en internet es abundante al igual que las opciones, las personas deben invertir grandes cantidades de tiempo en investigar qué aerolíneas, hoteles y restaurantes escoger para su viaje y comparar sus precios, horarios y reseñas puede causar malas decisiones. ¿Existe alguna forma de proporcionar toda la información y opciones que los viajeros necesitan en una sola plataforma donde las opciones se muestran según los filtros ingresados?</p><br></td>
              <td rowspan="2" valign="top"><p><b>Ideas de solución</b></p><br>
                <p>Una plataforma que muestre a las personas las mejores opciones de aerolíneas, hoteles, restaurantes y actividades de entretenimiento según sus presupuestos y le brindará descuentos que les permitirá ahorrar más dinero.</p><br>
                <p>Mostrarles a los usuarios con membresía opciones altamente calificadas por otros usuarios para que ellos puedan asegurarse de tener una buena experiencia.</p><br>
                <p>El usuario podrá tener acceso a toda la información sobre lo que se necesita para viajar en una misma plataforma que además le seleccionará las opciones que vayan acorde a sus preferencias, se le ayudará a planificar itinerarios por cada día de pase de viaje y se le informará sobre cambios en sus opciones elegidas.</p><br>
                <p>Se notificará sobre cualquier cambio de hora o suspensión del servicio elegido anticipadamente al usuario para que pueda hacer cambios previos al viaje.</p></td>
              <td valign="top"><p><b>Resultados comerciales esperados</b></p><br>
              <p>Mejor experiencia y tranquilidad al viajar con poca o nula deuda y ahorrar más dinero.</p><br>
              <p>La confianza por invertir en un viaje de lujo será mayor y la satisfacción de la experiencia será mucho más alta.</p><br>
              <p>El tiempo de planificación previa al viaje será menor para toda persona que esté pensando en viajar.</p><br>
              <p>La insatisfacción, decepción y cambios de planes repentinos de los usuarios por los servicios escogidos se verán reducidos.</p><br></td>
            </tr>
            <tr>
              <td valign="top"><p><b>Usuarios y clientes</b></p><br>
                <p>Familias viajeras que buscan economizar sus viajes y personas viajeras de clase alta que buscan opciones de lujo y calidad en sus viajes.</p>
                </td>
              <td valign="top"><p><b>Beneficios de usuarios</b></p><br>
                <p>Tener acceso a las opciones que van acorde con sus presupuestos y se les mostrará descuentos vigentes en la plataforma.</p><br>
                <p>Brindar al usuario una manera más sencilla de tener una lista con las mejores opciones del destino al que se dirige.</p><br>
                <p>Mostrar al usuario todo lo necesario para un viaje en la misma plataforma y mantenerlo informado sobre sus elecciones.</p><br>
                </td>
            </tr>
            <tr><td valign="top"><p><b>Hipótesis</b></p><br>
                <p><b>Creemos</b> que mostrar las opciones de aerolíneas, hoteles y restaurantes en una sola plataforma optimizará el tiempo de los viajeros al planificar sus viajes</p>
                <p><b>Sabremos que</b> estamos bien.</p>
                <p><b>Cuando</b> la cantidad de tiempo promedio que se invierte en investigar opciones para un viaje se ha reducido.</p><br>
              <p><b>Creemos</b> que el uso de filtros e ingreso de presupuesto para cada gasto del viaje hará que las personas eviten gastar de más en sus viajes.</p>
                <p><b>Sabremos que</b> estamos bien.</p>
                <p><b>Cuando</b> veamos que los usuarios viajan más a menudo y la cifra de endeudamientos por viaje se reduce.</p><br>
              <p><b>Creemos</b> que mostrar las opciones de aerolíneas, hoteles y restaurantes en una sola plataforma optimizará el tiempo de los viajeros al planificar sus viajes</p>
                <p><b>Sabremos que</b> estamos bien.</p>
                <p><b>Cuando</b> veamos que estas personas dejen opiniones muy positivas de su experiencia de viaje.</p><br>
              <p><b>Creemos</b> que informar de la manera más rápida posible a nuestros usuarios sobre cambios de hora de vuelo, suspensión de atención o cambios de horario en los servicios elegidos hará que los viajeros eviten pasar un mal rato durante su viaje.</p>
                <p><b>Sabremos que</b> estamos bien.</p>
                <p><b>Cuando</b> veamos que las personas cambian de servicios previamente al viaje y no mientras ya están en su destino.</p><br>
              <p><b>Creemos</b> que generar un itinerario de viaje a nuestros usuarios hará que los usuarios tengan un viaje más ordenado.</p>
                <p><b>Sabremos que</b> ha resultado</p>
                <p><b>Cuando</b> los usuarios hagan un mayor uso de la opción de generar itinerario al usar por segunda vez la plataforma.</p>
            </td>
              <td valign="top"><p><b>¿Qué es lo más importante que necesitamos aprender primero?</b></p><br>
                <p>Conocer el nivel de manejo de tecnología de nuestro público objetivo.</p><br> 
                <p>Conocer las principales inquietudes o preocupaciones de nuestro público objetivo.</p><br>
                <p>Conocer el nivel socioeconómico de nuestro público objetivo.</p><br>
                <p>Conocer las diversas empresas con las que tendremos convenios para ofrecer sus servicios a los viajeros y saber cómo conseguir y  mantener el convenio.</p><br></td>
              <td valign="top"><p><b>¿Cual es la menor cantidad de trabajo que necesitamos hacer para aprender lo siguiente más importante?</b></p><br>
              <p>Entrevistas a familias viajeras y viajeros de clase alta.<br>
                <p>Testing del prototipo de la plataforma a posibles usuarios que se encuentren dentro de uno de nuestros segmentos objetivo.</p><br>       
                <p>Investigación de los servicios que ofrecen las aerolíneas, hoteles, restaurantes, etc. que planeamos mostrar  a nuestros usuarios.</p><br>
                <p>Investigar cuales son las opiniones de los usuarios sobre el servicio que ofrecen las empresas.</p><br>
                <p>Identificar e investigar a las empresas que estén interesadas en ofrecer descuentos a cambio de poder vender sus servicios en nuestra plataforma.</p></td></tr>
          </table>
- 1.3. Segmentos objetivo
    
**Segmento objetivo 1: Familias Viajeras y Aventureras**

**Aspectos demográficos:**
- **Sexo:** Ambos sexos.
- **Edades:** Padres de familia de entre **30 y 50 años**, niños de **0 a 18 años**.
- **Nivel socioeconómico:** Diverso, desde clases media hasta alta.

**Aspectos geográficos:**
- **Nacionalidad:** Internacional, con un enfoque inicial en países con una cultura de viaje arraigada.
- **Zona geográfica en la que viven:** Principalmente urbanos, pero con un interés en destinos turísticos naturales y culturales.

**Aspectos psicográficos:**
- Buscan experiencias de viaje que sean **divertidas y educativas** para todas las edades.
- Interesados en actividades y atracciones que sean adecuadas para niños y adultos por igual.
- Valoración de la **seguridad y comodidad** durante el viaje, así como opciones de alojamiento que se adapten a las necesidades de una familia.
- Presupuesto **flexible**, pero consciente, buscando maximizar el valor de cada sol gastado en sus viajes.

**Segmento objetivo 2: Viajeros de Lujo**

**Aspectos demográficos:**
- **Sexo:** Ambos sexos.
- **Edades:** Adultos de mediana edad y mayores, entre **30 y 55 años**.
- **Nivel socioeconómico:** Clases alta y ultra-alta.

**Aspectos geográficos:**
- **Nacionalidad:** Internacional, con una concentración en países desarrollados y emergentes con alta riqueza.
- **Zona geográfica en la que viven:** Principalmente urbana, con acceso a servicios de lujo y de alto nivel.

**Aspectos psicográficos:**
- Buscan experiencias **exclusivas y de alta gama** durante sus viajes.
- Dispuestos a pagar más por servicios **premium** y comodidades de lujo.
- Interesados en alojamientos de lujo, gastronomía gourmet, transporte de primera clase y actividades VIP.
- Valoración de la **privacidad, la exclusividad** y el trato personalizado en sus experiencias de viaje.

### Capítulo II: Requirements Elicitation & Analysis
- 2.1. Competidores
    
En el mercado de aplicaciones todo en uno para planificar y gestionar viajes, existen varios productos que compiten ofreciendo soluciones similares para los viajeros. A continuación, se mencionan algunos de los competidores clave identificados:

**TripIt:** TripIt es una aplicación popular que permite a los usuarios organizar sus viajes de manera eficiente al consolidar todos los detalles del viaje, como vuelos, alojamiento, alquiler de coches y actividades, en un solo lugar. La aplicación crea automáticamente itinerarios detallados a partir de los correos electrónicos de confirmación de reserva que los usuarios le envían, lo que facilita la organización y planificación del viaje. Además, TripIt ofrece funciones de seguimiento de vuelos, recordatorios de reservas y acceso offline a la información del viaje.

**Expedia:** Expedia es una plataforma líder en reservas de viajes que permite a los usuarios buscar y reservar vuelos, alojamiento, alquiler de coches y actividades en todo el mundo. La aplicación ofrece una amplia gama de opciones y precios competitivos, así como ofertas exclusivas para usuarios registrados. Expedia también cuenta con una función de itinerario de viaje, que permite a los usuarios organizar y gestionar todos los aspectos de su viaje desde una sola plataforma.

**Airbnb:** Airbnb es una plataforma de alojamiento que ofrece una amplia variedad de opciones de hospedaje, desde apartamentos y casas privadas hasta habitaciones compartidas y experiencias únicas. Los usuarios pueden buscar y reservar alojamiento en destinos de todo el mundo, y también pueden acceder a experiencias locales organizadas por anfitriones de la comunidad. Airbnb se destaca por su enfoque en la autenticidad y la conexión con la cultura local, ofreciendo a los viajeros la oportunidad de experimentar destinos de una manera única y personalizada.

Estos competidores, al igual que TripMate, están enfocados en proporcionar soluciones integrales para la planificación y gestión de viajes, ofreciendo una variedad de herramientas y recursos para ayudar a los viajeros a organizar sus itinerarios, encontrar alojamiento, reservar actividades y disfrutar de experiencias locales auténticas. Cada plataforma tiene sus propias características y ventajas competitivas, por lo que es importante que los usuarios evalúen sus necesidades y preferencias individuales al elegir la aplicación de viajes que mejor se adapte a ellos.

  - 2.1.1. Análisis competitivo
        
<table><tr><th colspan="2" valign="top">Nombre</th><th valign="top"><b>TripMate</b></th><th valign="top">TripIt</th><th valign="top">Expedia</th><th valign="top">Airbnb</th></tr>
<tr><td rowspan="2" valign="top">Perfil</td><td valign="top">Overview</td><td valign="top"><p>TripMate es una aplicación móvil innovadora que simplifica la planificación y gestión de viajes. Permite crear itinerarios personalizados con recomendaciones locales, reservar alojamiento y actividades fácilmente, y acceder a descuentos exclusivos. </p><p></p></td><td valign="top">TripIt es una aplicación que simplifica la organización de viajes al consolidar todos los detalles del mismo, como vuelos, alojamiento y actividades, en un solo lugar. Automáticamente crea itinerarios detallados a partir de los correos electrónicos de confirmación de reserva que los usuarios envían, facilitando la planificación del viaje. </td><td valign="top">Expedia es una plataforma líder para reservar vuelos, alojamiento, alquiler de coches y actividades en todo el mundo. Ofrece una amplia gama de opciones y precios competitivos, junto con ofertas exclusivas para usuarios registrados. </td><td valign="top">Airbnb es una plataforma de alojamiento que brinda una diversa selección de hospedaje, desde apartamentos y casas privadas hasta habitaciones compartidas y experiencias únicas. Los usuarios pueden buscar y reservar alojamiento en todo el mundo, y también participar en experiencias locales organizadas por anfitriones.</td></tr>
<tr><td valign="top">Ventaja competitiva ¿Que valor ofrecemos a los clientes?</td><td valign="top">La ventaja competitiva de TripMate se basa en su enfoque integral y eficiente para la planificación de viajes, que ofrece itinerarios personalizados con recomendaciones locales, reserva fácil de alojamiento y actividades, descuentos exclusivos, notificaciones en tiempo real y una función de compartir experiencias.</td><td valign="top">La ventaja competitiva de TripIt es su capacidad para simplificar la organización de viajes al consolidar todos los detalles en un solo lugar. Su característica distintiva de crear itinerarios automáticos a partir de correos electrónicos de confirmación de reserva ahorra tiempo y esfuerzo al usuario. </td><td valign="top">Expedia ofrece a los clientes la conveniencia de buscar y reservar vuelos, alojamiento, alquiler de coches y actividades en un solo lugar, con una amplia gama de opciones y precios competitivos. Además, proporciona ofertas exclusivas para usuarios registrados y una función de itinerario de viaje para organizar y gestionar todos los aspectos del viaje desde una sola plataforma.</td><td valign="top">La ventaja competitiva de Airbnb radica en ofrecer a los clientes una amplia gama de opciones de alojamiento únicas y auténticas, desde apartamentos y casas privadas hasta habitaciones compartidas y experiencias locales.</td></tr>
<tr><td valign="top">Plan de marketing</td><td valign="top">Mercado objetivo</td><td valign="top"><p>` `Familias Viajeras y Aventureras y viajeros de lujo</p><p></p><p></p></td><td valign="top">Viajeros frecuentes, tanto de negocios como de placer.</td><td valign="top">Turistas que buscan vacaciones como a viajeros de negocios que necesitan organizar sus desplazamientos.</td><td valign="top">El mercado objetivo de Airbnb son viajeros que buscan experiencias de alojamiento únicas y auténticas en destinos de todo el mundo.</td></tr>
<tr><td valign="top"> </td><td valign="top">Estrategias de Marketing</td><td valign="top">Las estrategias de marketing de TripMate son a través de campañas digitales, redes sociales y asociaciones con empresas relacionadas con los viajes.</td><td valign="top">El plan de marketing de TripIt se centra en colaboraciones con influencers y socios estratégicos en la industria de los viajes.</td><td valign="top">Las estrategias de marketing de Expedia se basan en publicidad en línea, redes sociales y asociaciones con empresas relacionadas con los viajes. </td><td valign="top">Las estrategias de marketing de Airbnb utilizan una combinación de marketing digital, incluyendo publicidad en línea, redes sociales y marketing de contenido</td></tr>
<tr><td rowspan="3" valign="top">Perfil del producto</td><td valign="top">Productos y Servicios</td><td valign="top"><p>Los productos y servicios de TripMate incluyen una aplicación móvil innovadora diseñada para facilitar la planificación y gestión de viajes.</p><p></p></td><td valign="top">TripIt ofrece una aplicación móvil que simplifica la organización de viajes al crear automáticamente itinerarios detallados a partir de correos electrónicos de confirmación de reserva. Además, proporciona funciones de seguimiento de vuelos, recordatorios de reservas y acceso offline.</td><td valign="top">Proporciona una función de itinerario de viaje que permite a los usuarios organizar y gestionar todos los aspectos de su viaje desde una sola plataforma, brindando comodidad y opciones a los clientes durante la planificación y reserva de sus viajes.</td><td valign="top">Airbnb ofrece una variedad de productos y servicios que revolucionan la forma en que las personas viajan y experimentan el mundo.</td></tr>
<tr><td valign="top">Precios y Costos</td><td valign="top"><p>Ofrece una versión gratuita y una versión premium la cual cuesta 1.99 dólares para obtener asistencia por cada viaje que realices.</p><p>.</p></td><td valign="top">Ofrece una versión gratuita con funcionalidades básicas, mientras que su versión premium tiene un costo anual de 49 dólares.</td><td valign="top">Los precios de los servicios de Expedia varían según el tipo de reserva y el proveedor. Expedia usualmente no cobra una tarifa adicional por sus servicios, sino que obtiene sus ingresos a través de comisiones.</td><td valign="top">La plataforma generalmente cobra una tarifa de servicio a los huéspedes y una comisión a los anfitriones por cada reserva realizada a través de su plataforma.</td></tr>
<tr><td valign="top">Canales de distribución</td><td valign="top"><p>Web site & aplicativo disponible en IOS y android.</p><p> </p></td><td valign="top">TripIt distribuye su aplicación principalmente a través de tiendas de aplicaciones como App Store y Google Play Store </td><td valign="top">Los canales de distribución de Expedia incluyen principalmente su plataforma en línea, que está disponible a través de su sitio web y su aplicación móvil. </td><td valign="top"><p>Los canales de distribución de Airbnb se centran principalmente en su plataforma en línea, accesible a través de su sitio web y aplicación móvil.</p><p> </p></td></tr>
<tr><td rowspan="4" valign="top">Análisis SWOT</td><td valign="top">Fortalezas</td><td valign="top">TripMate ofrece una solución completa y eficiente para la planificación y gestión de viajes, con características clave como itinerarios personalizados, reservas fáciles, descuentos exclusivos y notificaciones en tiempo real, así como la función de compartir experiencias para una colaboración más fluida.</td><td valign="top">TripIt es una aplicación líder en la organización de viajes con una función de creación automática de itinerarios, seguimiento de vuelos y recordatorios de reservas, ofreciendo una experiencia conveniente y eficiente para los usuarios.</td><td valign="top">Expedia se destaca por ser una plataforma líder en reservas de viajes que ofrece una amplia gama de opciones y precios competitivos para vuelos, alojamiento, alquiler de coches y actividades en todo el mundo, proporcionando una experiencia integral y conveniente para los usuarios.</td><td valign="top">Airbnb destaca por ofrecer una amplia variedad de alojamientos únicos, desde apartamentos y casas privadas hasta experiencias auténticas, proporcionando a los usuarios una alternativa personalizada y diversa a los alojamientos tradicionales.</td></tr>
<tr><td valign="top">Oportunidades</td><td valign="top">La aplicación tiene potencial para expandir su base de usuarios a través de estrategias de marketing digital y asociaciones con empresas de viajes, aprovechando la creciente demanda de herramientas de planificación de viajes eficientes y personalizadas.</td><td valign="top">Existe la posibilidad de expandir su base de usuarios a través de asociaciones estratégicas y el desarrollo de nuevas características para satisfacer las necesidades cambiantes de los viajeros, así como la adopción de tecnologías emergentes para mejorar la funcionalidad de la aplicación.</td><td valign="top">La plataforma tiene oportunidades para expandir su alcance a nuevos mercados y aumentar su base de usuarios mediante asociaciones estratégicas y el desarrollo de nuevas características para mejorar la experiencia del usuario, así como la adopción de tecnologías emergentes para mantenerse competitivo en el mercado.</td><td valign="top">La plataforma tiene oportunidades para expandir su alcance a nuevos mercados y aumentar su base de usuarios mediante asociaciones estratégicas y el desarrollo de nuevas características para mejorar la experiencia del usuario, así como la adopción de tecnologías emergentes para mantenerse competitivo.</td></tr>
<tr><td valign="top">Debilidades</td><td valign="top"><p>TripMate podría enfrentar desafíos relacionados con la competencia en el mercado de aplicaciones de viajes y preocupaciones sobre seguridad y privacidad de datos, además de la dependencia de la conectividad a internet para algunas funciones.</p><p> </p></td><td valign="top">La dependencia de la conectividad a internet y la competencia en el mercado de aplicaciones de viaje son desafíos importantes, además de que no cuenta con un plan mensual y condiciona al cliente a adquirir un plan anual a un precio bastante elevado y poco atractivo.</td><td valign="top">Expedia puede enfrentar desafíos relacionados con la dependencia de la conectividad a internet y la competencia agresiva en el mercado de reservas de viajes, así como posibles preocupaciones sobre la satisfacción del cliente y la calidad del servicio en algunos casos.</td><td valign="top">Airbnb puede enfrentar desafíos relacionados con la regulación gubernamental y posibles preocupaciones sobre la seguridad y la calidad del alojamiento en algunos casos, lo que puede afectar su reputación y su posición en el mercado.</td></tr>
<tr><td valign="top">Amenazas</td><td valign="top">Las amenazas potenciales incluyen la competencia de nuevas aplicaciones de viajes, riesgos de seguridad cibernética y regulaciones gubernamentales que podrían afectar su operación y reputación.</td><td valign="top">TripIt enfrenta riesgos potenciales como cambios en las preferencias de los usuarios, riesgos de seguridad cibernética y la competencia agresiva de otras aplicaciones similares en el mercado.</td><td valign="top">Las amenazas potenciales incluyen cambios en las preferencias de los usuarios, riesgos de seguridad cibernética y la competencia de otras plataformas de reservas de viajes que podrían impactar su participación en el mercado y su reputación en la industria.</td><td valign="top">Las amenazas potenciales incluyen cambios en las políticas gubernamentales y la regulación, así como riesgos de seguridad cibernética y la competencia de otras plataformas de alojamiento que podrían impactar su participación en el mercado y su imagen de marca.</td></tr>
</table>

  - 2.1.2. Estrategias y tácticas frente a competidores
    
**Diferenciación de producto:** TripMate se diferenciará de sus competidores destacando características únicas como itinerarios personalizados, descuentos exclusivos y notificaciones en tiempo real sobre cambios en vuelos y reservas. Se enfocará en proporcionar una experiencia de usuario excepcional y conveniente, lo que lo distinguirá en el mercado.

**Marketing y promoción agresivos:** Se llevarán a cabo campañas de marketing digital dirigidas y estrategias de promoción agresivas para aumentar la visibilidad de TripMate. Esto incluirá publicidad en línea, colaboraciones con influencers y socios en la industria de los viajes, así como la participación en eventos y ferias relacionadas con el turismo.

**Colaboraciones estratégicas:** TripMate establecerá asociaciones estratégicas con empresas de viajes, aerolíneas, hoteles y otras organizaciones relacionadas para ampliar su alcance y ofrecer beneficios adicionales a los usuarios. Esto puede incluir descuentos exclusivos en alojamiento, actividades y servicios relacionados con los viajes.

**Mejora continua:** La aplicación TripMate se mantendrá actualizada con nuevas características y mejoras basadas en la retroalimentación de los usuarios y el análisis del mercado. Se priorizará la innovación para garantizar que TripMate siga siendo relevante y competitivo en el mercado de aplicaciones de viajes en constante evolución. Además, se implementarán programas de fidelización para retener a los usuarios existentes y atraer a nuevos clientes.

- 2.2. Entrevistas
  - 2.2.1. Diseño de entrevistas
    
Segmento objetivo 1: Familias Viajeras y Aventureras

Para el segmento de familias viajeras y aventureras, las preguntas se centran en la evaluación de la receptividad y necesidades de las familias viajeras y aventureras frente a la potencial aplicación TripMate. Exploran la utilidad percibida de la aplicación para mejorar la organización y disfrute de los viajes en familia, así como las características deseadas, preocupaciones de seguridad, preferencias de personalización, y cómo la aplicación podría abordar los desafíos comunes que enfrentan estas familias en la planificación y realización de sus viajes.

- ¿Qué piensas sobre la idea de una aplicación diseñada específicamente para ayudar a familias a planificar y gestionar sus viajes de manera integral?
- ¿Crees que una aplicación como esta sería útil para hacer que los viajes en familia sean más organizados y placenteros?
- ¿Qué características específicas esperarías encontrar en una aplicación diseñada para ayudar a las familias a planificar sus aventuras de viaje?
- ¿Qué aspectos de seguridad y privacidad consideras importantes al utilizar una aplicación para planificar los viajes de tu familia?
- ¿Te gustaría poder recibir recomendaciones personalizadas sobre destinos, actividades y alojamientos adecuados para familias y niños?
- ¿Qué desafíos crees que enfrentan las familias al planificar y organizar sus viajes, y cómo crees que una aplicación como TripMate podría ayudar a superar estos desafíos?
- ¿Cómo te gustaría compartir tus experiencias de viaje con otros miembros de la familia a través de la aplicación?
- ¿Qué tipo de actividades o experiencias te gustaría poder reservar fácilmente a través de la aplicación para enriquecer los viajes de tu familia?
- ¿Prefieres una aplicación que se adapte a las preferencias individuales de cada miembro de la familia, o una con características más generales pero ampliamente útiles para todos?
- ¿Cómo crees que una aplicación como esta podría mejorar la experiencia general de viaje de tu familia y hacerla más emocionante y satisfactoria?

Segmento objetivo 2: Viajeros de lujo
Para el segmento objetivo de viajeros de lujo, nuestras preguntas exploran las preferencias y necesidades de los viajeros de lujo en relación con TripMate, abordando temas como las experiencias buscadas, la complementación de la aplicación a dichas experiencias, las expectativas de personalización, seguridad y privacidad, así como la percepción sobre la tecnología en la mejora de la experiencia de viaje de lujo. También se indaga sobre experiencias previas con aplicaciones móviles para la planificación de viajes de lujo.

- ¿Qué tipo de experiencias de lujo buscas cuando planificas tus viajes?
- ¿Cómo crees que una aplicación como TripMate podría complementar tus experiencias de viaje de lujo?
- ¿Qué características específicas esperarías encontrar en una aplicación diseñada para viajeros de lujo como tú?
- ¿Consideras que la capacidad de personalización es importante cuando utilizas aplicaciones para planificar tus viajesde lujo?
- ¿Qué tipo de recomendaciones o sugerencias valorarías más al utilizar una aplicación como TripMate durante tus viajesde lujo?
- ¿Cómo valoras la seguridad y la protección de tus datos personales al utilizar aplicaciones móviles durante tusviajes de lujo?
- ¿Qué aspectos de la aplicación TripMate crees que podrían mejorar aún más la experiencia de viaje de lujo para sususuarios?
- ¿Prefieres la exclusividad y la privacidad al utilizar servicios de reserva a través de aplicaciones móviles para tusviajes de lujo?
- ¿Cómo crees que la tecnología puede mejorar la experiencia de viaje de lujo en general?
- ¿Has tenido alguna experiencia positiva o negativa al utilizar aplicaciones móviles para planificar tus viajes delujo en el pasado?

- 2.2.2. Registro de entrevistas

Segmento objetivo 1: Familias Viajeras y Aventureras

| Entrevistado N°1: Sandro Quispesivana |<img src="https://github.com/TripTeamOrganization/Informes/assets/134337719/36f9bff8-5412-4069-a221-182eef515dbb" alt="Andrés Valle" style="width: 185px;">|
|--------------------------------|------------------------------------------------------------|
| **Nombre:**                    | Sandro Quispesivana                                               |
| **Edad:**                      | 30                                                         |
| **Sexo:**                      | Masculino                                                  |
| **Ocupación:**                 | Docente                                     |
| **Entrevista:**                | [Link](https://youtu.be/DzOgJiNWUvI)       |
| **Momento de inicio:**         | 0:03                                                       |
| **Duración:**                  | 3:59                                                       |



| Entrevistado N°2: Isabel Martinez |<img src="https://github.com/TripTeamOrganization/Informes/assets/134337719/12f8c567-9528-4494-86cb-3fb749280fc4" alt="Andrés Valle" style="width: 220px;">|
|--------------------------------|------------------------------------------------------------|
| **Nombre:**                    | Isabel Martinez Quispe                                               |
| **Edad:**                      | 35                                                         |
| **Sexo:**                      | Femenino                                                  |
| **Ocupación:**                 | Cosmetóloga                                      |
| **Entrevista:**                | [Link](https://www.youtube.com/watch?v=pdUGOwDCa0Y)       |
| **Momento de inicio:**         | 0:02                                                       |
| **Duración:**                  | 7:14                                                       |



| Entrevistado N°3: Isaak Sánches | <img src="https://github.com/TripTeamOrganization/Informes/assets/134337719/d5c28126-a804-4c18-833c-a98db0a4f349" alt="Andrés Valle" style="width: 230px;"> |
|--------------------------------|------------------------------------------------------------|
| **Nombre:**                    | Isaak Sánches                                              |
| **Edad:**                      | 31                                                        |
| **Sexo:**                      | Masculino                                                  |
| **Ocupación:**                 | Electrónico                                      |
| **Entrevista:**                | [Link](https://www.youtube.com/watch?v=JSYodc8w27U)        |
| **Momento de inicio:**         | 0:02                                                       |
| **Duración:**                  | 8:21                                                       |



Segmento objetivo 2: Viajeros de lujo

| Entrevistado N°4: Andrés Valle |<img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/8f336f70-40b0-4477-94eb-6e92b7917524" alt="Andrés Valle" style="width: 240px;">|
|--------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **Nombre:**                   | Andrés Valle                                                                                                          |
| **Edad:**                     | 32                                                                                                                    |
| **Sexo:**                    | Masculino                                                                                                             |
|**Ocupación:**                | Ingeniero Aeronáutico                                                                                                 |
| **Entrevista:**             | [Link](https://www.youtube.com/watch?v=DpATSL0ElpE)                                                                    |
| **Momento de inicio:**         | 0:04                                                                                                                  |
| **Duración:**               | 3:50                                                                                                                  |


| Entrevistado N°5: Gustavo Chinchay | <img src=https://github.com/TripTeamOrganization/Informes/assets/89095594/bdda83a4-be1a-4c7e-a8a2-fa329cf779c9 alt="Andrés Valle" style="width: 200px;"> |
|--------------------------------|------------------------------------------------------------|
| **Nombre:**                    | Gustavo Chinchay                                              |
| **Edad:**                      | 30                                                         |
| **Sexo:**                      | Masculino                                                  |
| **Ocupación:**                 | Ingeniero de sonido                                      |
| **Entrevista:**                | [Link](https://www.youtube.com/watch?v=ggIC9Cf1or4)       |
| **Momento de inicio:**         | 0:01                                                       |
| **Duración:**                  | 5:25                                                       |


| Entrevistado N°6: Jhan Caseres | <img src=https://github.com/TripTeamOrganization/Informes/assets/134337719/9da98916-6e6e-4b85-9d32-c8f2fd49c87a alt="Andrés Valle" style="width: 240px;"> |
|--------------------------------|------------------------------------------------------------|
| **Nombre:**                    | Jhan Caseres                                              |
| **Edad:**                      | 30                                                         |
| **Sexo:**                      | Masculino                                                  |
| **Ocupación:**                 | Ingeniero Mecánico                                        |
| **Entrevista:**                | [Link](https://www.youtube.com/watch?v=eeLvMoP6shI)       |
| **Momento de inicio:**         | 0:01                                                       |
| **Duración:**                  | 4:21                                                       |


- 2.2.3. Análisis de entrevistas
  

Análisis de Entrevistas sobre Aplicación de Viajes Familiares:

| **Entrevistado**                    | **Análisis**                                                                 |
|------------------------------------|-----------------------------------------------------------------------------------------|
| Sandro Quispesivana               | Apoya la idea de una aplicación para planificar viajes familiares. <br>Destaca la utilidad de características como la planificación de itinerarios personalizados y la seguridad. <br>Aboga por una combinación de características generales y opciones de personalización para mejorar la experiencia de viaje familiar. |
|  Isabel Martinez                  | Considera que una aplicación para organizar viajes familiares es una excelente idea.<br>Destaca su utilidad, practicidad y capacidad para hacer los viajes más ordenados y agradables.<br>Menciona la importancia de la seguridad, la privacidad y la recepción de sugerencias para facilitar la planificación del itinerario. |
| Isaak Sánches          | Expresa su respaldo a una aplicación para la planificación de viajes familiares.<br>Destaca la conveniencia y utilidad de la aplicación para hacer los viajes más organizados y placenteros.<br>Enfatiza la importancia de la veracidad de la información, la seguridad de los datos y la capacidad de recibir recomendaciones adaptadas. |


Análisis de Entrevistas sobre Experiencias de Viaje de Lujo:

| **Entrevistado**                    | **Análisis**                                                                 |
|------------------------------------|-----------------------------------------------------------------------------------------|
| Andrés Valle        | Busca experiencias lujosas que ofrezcan sofisticación y comodidad. Valora la capacidad de personalización, la seguridad de sus datos y la exclusividad en sus reservas.<br>Ha tenido experiencias tanto positivas como negativas al utilizar aplicaciones móviles para planificar sus viajes de lujo. |
| Gustavo Chinchay                      | Reconoce en TripMate la posibilidad de enriquecer sus viajes de lujo por el Perú.<br>Valora la personalización, la seguridad de sus datos y la exclusividad en sus reservas.<br>Considera que la tecnología puede mejorar significativamente la experiencia de viaje de lujo. |
| Jhan Caseres        | Reconoce en TripMate la oportunidad de elevar la calidad de sus travesías por el territorio peruano.<br>Aprecia la personalización, la seguridad de sus datos y la exclusividad en sus reservas.<br>Considera que la tecnología puede contribuir significativamente a mejorar la experiencia de viaje de lujo. |


- 2.3. Needfinding
- 2.3.1. User Personas

Ahora procederemos a crear los perfiles de User Persona para cada uno de nuestros segmentos objetivo. Utilizaremos la información recopilada de las entrevistas realizadas, centrándonos especialmente en los objetivos, motivaciones y desafíos específicos de los diferentes grupos que componen nuestra audiencia objetivo. Esto implica la creación de perfiles representativos tanto de las familias viajeras y aventureras como de los viajeros de lujo. Estos perfiles se basarán en datos demográficos, geográficos y psicográficos detallados, que incluyen aspectos como edad, nivel socioeconómico, intereses de viaje y preferencias de alojamiento, entre otros.

Segmento objetivo 1: Julia Nuñez

![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/f6280515-826e-4297-96d2-b1b1af2e796b)

Segmento objetivo 2: Martin Casanova

![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/74c24f2b-8e87-495d-a29d-05210456d6cf)


- 2.3.2. User Task Matrix

En esta fase, nos centraremos en las actividades que los User Persona del segmento objetivo de Familias Viajeras desean llevar a cabo en la aplicación, personificados por Julia Nuñez. Del mismo modo, consideraremos las necesidades del segundo User Persona del segmento de Viajeros de Lujo, personificado por Martin Casanova. A continuación, detallamos las actividades que ambos realizan para lograr sus objetivos.

Segmento objetivo 1: Julia Nuñez

|       Actividades                                                                                    | Frecuencia |Importancia|
|----------------------------------------------------------------------------------------------|-----------------------|-----------------------------|
| Almacenar itinerarios y detalles de viaje en la aplicación TripMate:                        | Con Frecuencia | Alta |
| Reservar alojamiento y actividades a través de TripMate:                                    | Con Frecuencia|  Alta |
| Organizar junto a su familia los viajes para lograr una gestión más efectiva:                | A veces | Media       |
| Acceder a descuentos exclusivos proporcionados por TripMate:                                 |  A veces|   Media       |
| Recibir notificaciones en tiempo real sobre cambios en vuelos y reservas a través de TripMate:|  Con Frecuencia |  Alta |
| Compartir experiencias de viaje con amigos y familiares a través de TripMate:                | Con Frecuencia|   Baja |


Segmento objetivo 2: Martin Casanova

| Actividades                                                                                                      | Frecuencia      | Importancia |
|------------------------------------------------------------------------------------------------------------------|-----------------|-------------|
| Almacenar detalles de viaje y preferencias en la aplicación TripMate:                                          | Diariamente     | Alta        |
| Reservar alojamiento exclusivo y actividades de lujo a través de TripMate:                                      | Con Frecuencia | Alta        |
| Acceder a descuentos exclusivos proporcionados por TripMate para experiencias de lujo:                          | A veces         | Alta        |
| Recibir notificaciones en tiempo real sobre cambios en vuelos, reservas y actualizaciones de lujo a través de TripMate:| A veces     | Media       |
| Compartir experiencias de viaje exclusivas con amigos y colegas a través de TripMate:                            | Con Frecuencia | Alta        |


- 2.3.3. User Journey Mapping

Un mapa de viaje del usuario, también conocido como mapeo del recorrido del usuario, es una herramienta valiosa utilizada para visualizar y comprender en profundidad la trayectoria que un usuario sigue desde su primer encuentro con un producto o servicio hasta que logra su objetivo deseado. Este recurso es esencial para detectar áreas de mejora en la experiencia del usuario y asegurar que los procesos de la empresa estén perfectamente alineados con las necesidades y expectativas del usuario.

Segmento objetivo 1: Julia Nuñez

![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/a2d90813-164b-4598-90a0-9bdecbb4c395)

Segmento objetivo 2: Martin Casanova

![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/7baacfc6-3819-4067-ae7d-e808e68230fd)

- 2.3.4. Empathy Mapping
En esta sección se expone el Mapeo de Empatía de nuestros dos segmentos objetivos. Esta técnica se empleó para identificar a nuestra audiencia objetivo, comprender su contexto y sus necesidades, lo que nos permite entender su perspectiva y visión del mundo.

Segmento objetivo 1: Julia Nuñez
![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/96253bbc-28eb-46b1-badc-9b08939d9da4)

Segmento objetivo 2: Martin Casanova
![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/0b9d748d-d567-4210-a2fe-86e4f829b8db)


- 2.3.5. As-is Scenario Mapping


Segmento objetivo 1: Julia Nuñez

![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/3f05f9e5-65fc-422b-86ff-3673418777d0)

Segmento objetivo 2: Martin Casanova

![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/cc2ea0c9-1098-4e83-924d-1b0d08008ce4)

- 2.4. Ubiquitous Language

1. **Technical Interview** (Entrevista Técnica)  
   A structured assessment process conducted by employers in the technology industry to evaluate a candidate's technical skills, problem-solving abilities, and suitability for a specific role or position within the organization. Technical interviews often involve a series of questions, coding exercises, and problem-solving scenarios.

2. **Coding Exercise** (Ejercicio de Codificación)  
   A practical task assigned to candidates during a technical interview to evaluate their programming proficiency, algorithmic thinking, and coding abilities. Coding exercises typically require candidates to write code to solve a specific problem or implement a given algorithm within a specified timeframe.

3. **Mock Interview** (Simulacro de Entrevista)  
   A simulated interview session designed to replicate the format and experience of a real technical interview. Mock interviews provide candidates with an opportunity to practice answering technical questions, solving coding challenges, and receiving feedback from experienced interviewers to improve their performance.

4. **Frequently Asked Questions (FAQs)** (Preguntas Frecuentes)  
   A compilation of common queries, topics, and concerns frequently encountered by candidates during technical interviews. FAQs provide candidates with valuable insights, tips, and strategies for navigating the interview process effectively and increasing their chances of success.

5. **Tutorials** (Tutoriales)  
   Comprehensive guides, tutorials, and instructional materials aimed at helping candidates improve their technical skills, enhance their understanding of core concepts, and prepare for technical interviews. Tutorials cover a wide range of topics, including data structures, algorithms, programming languages, and problem-solving techniques.

6. **Exclusive Content** (Contenido Exclusivo)  
   Specialized resources, content, or insights available only to members or subscribers of a particular platform or service. Exclusive content may include advanced tutorials, in-depth articles, insider tips from industry experts, and access to exclusive webinars or events.

7. **Recruitment Opportunities** (Oportunidades de Reclutamiento)  
   Job openings, internship positions, or networking opportunities provided by technology companies seeking to recruit talent from within the platform's user community. Recruitment opportunities enable candidates to explore career options, connect with potential employers, and pursue professional growth opportunities.

8. **Premium Memberships** (Membresías Premium)  
   Subscription-based access levels offering users enhanced features, benefits, and privileges beyond those available in the standard free version. Premium memberships may include access to exclusive content, personalized coaching sessions, priority support, and ad-free browsing.

9. **Personalized Tutoring Sessions** (Sesiones de Tutoría Personalizada)  
   Individualized coaching sessions tailored to meet the unique learning needs and goals of candidates preparing for technical interviews. Personalized tutoring sessions provide candidates with targeted guidance, feedback, and support to help them improve their skills, build confidence, and perform their best during interviews.

10. **Money-Back Guarantee** (Garantía de Devolución de Dinero)  
    A commitment or assurance provided to users that they will receive a full refund of their subscription fee or payment if they are not satisfied with the services or outcomes delivered by the platform. The money-back guarantee reflects the platform's confidence in its offerings and its commitment to customer satisfaction.


### Capítulo III: Requirements Specification
- 3.1. To-Be Scenario Mapping

Segmento Objetivo #1: Familias Viajeras y Aventureras

**Juliana Nuñez**

![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/4b4c6df1-8bda-411d-b9c1-907338e3bb49)

Segmento Objetivo #2: Viajeros de lujo

**Martin Casanova**

![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/679a00be-c59e-4110-8267-1ced4b2d2114)

- 3.2. User Stories

|**Epic / Story ID**|**Título**|**Descripción**|**Criterios de aceptación**|**Relacionado con (Epic ID)**|
| :- | :- | :- | :- | :- |
|EP01|Autenticación de usuario|<p>**Como** usuario</p><p>**Quiero** poder registrarme e iniciar sesión</p><p>**Para** acceder a la aplicación de TripMate</p>|Epic|EP01|
|EP02|Gestión de cuentas|<p>**Como** usuario</p><p>**Quiero** poder administrar y personalizar mi cuenta</p><p>**Para** poder realizar** cambios en mi cuenta</p>|Epic|EP02|
|EP03|Búsqueda y exploración de destinos|<p>**Como** usuario</p><p>**Quiero** poder buscar y explorar destinos</p><p>**Para** planificar mi viaje</p>|Epic|EP03|
|EP04|Reservas y planificación de itinerarios|<p>**Como** usuario</p><p>**Quiero** poder realizar reservas y planificar itinerarios</p><p>**Para** preparar mi viaje</p>|Epic|EP04|
|EP05|Gestión de presupuestos|<p>**Como** usuario</p><p>**Quiero** tener herramientas de gestión de presupuestos</p><p>**Para re**alizar un seguimiento de mis gastos</p>|Epic|EP05|
|EP06|Ver y publicar reseñas|<p>**Como** usuario</p><p>**Quiero** poder compartir y ver reseñas de viajes** </p><p>**Para** descubrir destinos de viaje recomendados por otros usuarios</p>|Epic|EP06|
|EP07|Contacto|<p>**Como** visitante del landing page</p><p>**Quiero** contar con una sección que me permita contactar con los desarrolladores de la aplicación</p><p>**Para** resolver algún problema o dar mi opinión sobre la aplicación </p>|Epic|EP07|
|EP08|Optimización de la experiencia del usuario|<p>**Como** visitante del landing page</p><p>**Quiero** visualizar una presentación atractiva</p><p>**Para** conocer los servicios y características que ofrece TripMate</p>|Epic|EP08|
|EP9|Descuentos|<p>**Como** usuario</p><p>**Quiero** poder acceder a descuentos en la aplicación</p><p>**Para** ahorrar dinero en mis viajes</p>|Epic|EP09|
|US01|Registro de usuario|<p>**Como** usuario nuevo</p><p>**Quiero** poder registrarme en TripMate** </p><p>**Para** poder acceder a todas las funcionalidades de la aplicación</p>|<p>**Escenario 1: Registro exitoso**</p><p>**Dado que** el usuario es nuevo</p><p>**Cuando** acceda a la página de registro</p><p>**Y** complete todos los campos requeridos</p><p>**Entonces** debería recibir una confirmación de registro</p><p></p><p>**Escenario 2: Registro fallido**</p><p>**Dado que** el usuario completó el formulario de registro</p><p>**Cuando** ingrese información inválida o incompleta</p><p>**Entonces** debería recibir un mensaje de error que indiquen los campos a corregir</p>|EP01|
|US02|Inicio de sesión|<p>**Como** usuario registrado</p><p>**Quiero** poder iniciar sesión en la aplicación</p><p>**Para** acceder a mi cuenta</p>|<p>**Escenario 1:** Inicio de sesión exitoso</p><p>**Dado que** el usuario se ha registrado</p><p>**Cuando** ingrese su correo electrónico y contraseña</p><p>**Entonces** debería poder acceder a mi cuenta</p><p></p><p>**Escenario 2:** Inicio de sesión fallido</p><p></p><p>**Dado que** el usuario se ha registrado</p><p>**Cuando** ingrese una credencial incorrecta</p><p>**Entonces** debería recibir un mensaje de error</p>|EP01|
|US03|Recuperación de contraseña|<p>**Como** usuario registrado</p><p>**Quiero** tener la opción de recuperación de contraseña</p><p>**Para** poder acceder a mi cuenta sin problemas</p>|<p>**Escenario 1:** Solicitud de recuperación de contraseña exitosa</p><p></p><p>**Dado que** el usuario ha olvidado su contraseña</p><p>**Cuando** acceda a la opción de recuperar contraseña</p><p>**Y** coloca el correo asociado a su cuenta</p><p>**Entonces** recibirá un correo electrónico con instrucciones para recuperar su contraseña</p><p></p><p>**Escenario 2:** Solicitud de recuperación de contraseña fallida</p><p></p><p>**Dado que** el usuario ha olvidado su contraseña</p><p>**Cuando** accede a la opción de recuperar contraseña</p><p>**Y** coloca un correo no asociado a su cuenta</p><p>**Entonces** mostrará un mensaje de error</p><p>**Y** deberá ingresar su correo nuevamente</p><p></p>|EP01|
|US04|Cambiar dirección de correo electrónico|<p>**Como** usuario</p><p>**Quiero** poder cambiar la dirección de correo electrónico asociada a mi cuenta</p><p>**Para** mantener mi información de contacto actualizada</p>|<p>**Escenario 1:** Acceder a la configuración de la cuenta</p><p></p><p>Dado que el usuario está registrado y ha iniciado sesión en la aplicación</p><p>Cuando acceda a la configuración de su cuenta desde el menú de perfil</p><p>Entonces podrá encontrar una opción para cambiar su dirección de correo electrónico</p><p></p><p>**Escenario 2:** Verificación de la nueva dirección de correo electrónico</p><p></p><p>**Dado que** el usuario ha ingresado una nueva dirección de correo electrónico en la configuración de su cuenta</p><p>**Cuando** guarde los cambios y la aplicación solicite verificar la nueva dirección</p><p>**Entonces** recibirá un correo electrónico de verificación en la nueva dirección y seguirá un proceso para confirmar el cambio</p><p></p>|EP01|
|US05|Buscar destinos por filtros|<p>**Como** usuario</p><p>**Quiero** poder buscar destinos por categorías</p><p>**Para** explorar opciones según mis intereses y preferencias</p>|<p>**Escenario 1:** Filtración de destinos</p><p></p><p>**Dado que** el usuario quiere planificar un viaje personalizado</p><p>**Cuando** utilice los filtros en la sección de búsqueda</p><p>**Entonces** debería ver una variedad de destinos según los filtros aplicados</p><p></p><p>**Escenario 2:** Selección de destino</p><p></p><p>**Dado que** el usuario quiere seleccionar un destino</p><p>**Cuando** encuentre su destino ideal</p><p>**Entonces** podrá seleccionarlo como destino del viaje</p>|EP03|
|US06|Información sobre destinos|<p>**Como** usuario</p><p>**Quiero** poder acceder a información sobre destino de mi viaje</p><p>**Para pod**er conocer el lugar y planificar un itinerario</p>|<p>**Escenario 1:** Información sobre destino</p><p></p><p>**Dado que** el usuario seleccionó el destino de su viaje</p><p>**Cuando** ingrese al apartado de información</p><p>**Entonces** podrá leer acerca de mi destino turístico</p><p></p><p>**Escenario 2:** Observar fotos y videos</p><p></p><p>**Dado que** el usuario quiere conocer el destino de su viaje</p><p>**Cuando** ingrese al apartado de videos y fotografías</p><p>**Entonces** podrá ver una variedad de fotos y videos acerca de su destino</p>|EP03|
|US07|Explorar destinos populares|<p>**Como** usuario</p><p>**Quiero** poder explorar destinos populares en la aplicación</p><p>**Para** descubrir lugares recomendados por otros viajeros</p>|<p>**Escenario 1:** Destino más visitado</p><p></p><p>**Dado que** el usuario quiere explorar destinos populares</p><p>**Cuando** acceda a la sección de destinos destacados</p><p>**Entonces** debería ver una lista de los destinos más visitados</p><p></p><p>**Escenario 2:** Recomendaciones de destinos</p><p></p><p>**Dado que** el usuario está interesado en recibir recomendaciones</p><p>**Cuando** complete su perfil con sus preferencias de viaje</p><p>**Entonces** debería ver sugerencias basadas en sus intereses</p>|EP03|
|US08|Reservar alojamiento|<p>**Como** usuario </p><p>**Quiero** poder reservar alojamiento en la aplicación</p><p>**Para** asegurar mi hospedaje durante el viaje</p>|<p>**Escenario 1:** Selección de fecha y tipo de alojamiento</p><p></p><p>**Dado que** el usuario quiere reservar alojamiento para su viaje</p><p>**Cuando** seleccione las fechas de estadía y el tipo de alojamiento deseado</p><p>**Entonces** se mostrará una lista de opciones de alojamiento disponibles</p>|EP04|
|US09|Planificar itinerario|<p>**Como** usuario</p><p>**Quiero** poder planificar mi itinerario en la aplicación</p><p>**Para** organizar mis actividades durante el viaje</p>|<p>**Escenario 1:** Agregar actividades</p><p></p><p>**Dado que** el usuario está planificando su viaje</p><p>**Cuando** explore las opciones de actividades </p><p>**Y** seleccione las que desea realizar</p><p>**Entonces** debería poder agregarlas a su itinerario con fecha y horario</p><p></p><p>**Escenario 2:** Visualizar itinerario</p><p></p><p>**Dado que** el usuario ha agregado actividades a su itinerario</p><p>**Cuando** acceda a la planificación de su viaje</p><p>**Entonces** podrá ver todas sus actividades organizadas por día y hora</p>|EP04|
|US10|Compartir itinerario|<p>**Como** usuario</p><p>**Quiero** poder compartir mi itinerario de viaje** con otras personas</p><p>**Para** coordinar actividades y compartir planes</p>|<p>**Escenario 1:** Compartir itinerario</p><p></p><p>**Dado que** el usuario ha creado un itinerario en la aplicación</p><p>Cuando seleccione la opción de compartir itinerario</p><p>**Entonces** podrá enviar una invitación a otros usuarios para que vean su itinerario</p><p></p><p>**Escenario 2:** Aceptar invitación</p><p></p><p>**Dado que** el usuario ha recibido una invitación para un itinerario</p><p>**Cuando** acepte la invitación</p><p>**Entonces** podrá ver y colaborar en el itinerario compartido</p><p></p>|EP04|
|US11|Explorar actividades cercanas|<p>**Como** usuario</p><p>**Quiero** poder explorar actividades y lugares de interés cercanos a mi ubicación actual</p><p>**Para** descubrir opciones adicionales durante mi viaje</p>|<p>**Escenario 1:** Búsqueda de actividades</p><p></p><p>**Dado que** el usuario se encuentra en una nueva ubicación durante su viaje</p><p>**Cuando** acceda a la función de explorar actividades cercanas</p><p>**Entonces** podrá ver una lista de actividades, restaurantes o lugares de interés recomendados en las cercanías</p><p></p><p>**Escenario 2:** Búsqueda por filtro</p><p></p><p>**Dado que** el usuario está buscando actividades personalizadas</p><p>**Cuando** explore las actividades cercanas por filtro</p><p>**Entonces** podrá encontrar fácilmente actividades adecuadas a sus preferencias</p>|EP04|
|US12|Reservar transporte local|<p>**Como** usuario</p><p>**Quiero** poder reservar transporte local</p><p>**Para** facilitar mis desplazamientos durante el viaje</p>|<p>**Escenario 1:** Búsqueda de transporte</p><p></p><p>Dado que el usuario necesita un transporte desde su ubicación hasta un lugar específico</p><p>Cuando acceda a la sección de transporte en la aplicación</p><p>Entonces podrá ver opciones de transporte disponibles</p><p></p><p>**Escenario 2:** Reserva de transporte</p><p></p><p>**Dado que** el usuario desea alquilar un transporte</p><p>**Cuando** encuentre el transporte adecuado y seleccione la hora, fecha y punto de inicio y fin del viaje</p><p>**Entonces** podrá reservar un transporte según sus necesidades</p>|EP04|
|US13|Descubrir eventos locales|<p>**Como** usuario</p><p>**Quiero** poder descubrir eventos locales</p><p>**Para** mejorar mi experiencia cultural durante mi viaje</p>|<p>**Escenario 1:** Búsqueda de eventos</p><p></p><p>**Dado que** el usuario está buscando eventos en su destino</p><p>**Cuando** use la función de buscar eventos locales</p><p>**Entonces** podrá visualizar todos los eventos locales que hay en su destino</p><p></p><p>**Escenario 2:** Selección de evento</p><p></p><p>**Dado que** el usuario está buscando eventos en su destino</p><p>**Cuando** use la función de buscar eventos locales</p><p>Y encuentre un evento que le llame la atención</p><p>**Entonces** podrá registrar ese evento como una actividad en su itinerario</p>|EP04|
|US14|Realizar pago|<p>**Como** usuario</p><p>**Quiero** poder realizar los pagos dentro de la aplicación</p><p>**Para** poder terminar de planificar el viaje</p>|<p>**Escenario 1:** Pago exitoso</p><p>**Dado que** el usuario ha organizado su viaje</p><p>**Cuando** quiera realizar el pago</p><p>**Entonces** la aplicación lo redireccionará a la sección de pago</p><p>**Y** podrá pagar el total de su viaje</p><p></p><p>**Escenario 2:** Pago fallido</p><p></p><p>**Dado que** el usuario ha organizado su viaje</p><p>**Y** desea realizar el pago</p><p>**Cuando** ingrese credenciales incorrectas en la sección de pago</p><p>**Entonces** la aplicación mostrará un mensaje de error</p><p>**Y** le permitirá volver a ingresar sus datos</p>|EP04|
|US15|Seguimiento de gastos|<p>**Como** usuario</p><p>**Quiero** poder realizar un seguimiento de mis gastos en la aplicación</p><p>**Para** mantenerme dentro de mi presupuesto</p>|<p>**Escenario 1:** Registro de gastos</p><p></p><p>**Dado que** el usuario está viajando</p><p>**Cuando** realice algún gasto relacionado con su viaje</p><p>**Entonces** podra registrar el monto en la aplicación</p><p></p><p>**Escenario 2:** Visualización de gastos</p><p></p><p>**Dado que** el usuario ha registrado varios gastos durante su viaje</p><p>**Cuando** acceda a la sección de seguimiento de gastos</p><p>**Entonces** podrá ver un resumen de sus gastos y un total acumulado</p>|EP05|
|US16|Establecer presupuesto|<p>**Como** usuario</p><p>**Quiero** poder establecer un presupuesto para mi viaje en la aplicación</p><p>**Para** poder controlar mis gastos</p>|<p>**Escenario 1:** Configuración de presupuesto</p><p></p><p>**Dado que** el usuario está planeando su viaje</p><p>**Cuando** ingrese el presupuesto total que tiene disponible</p><p>**Entonces** podrá establecer un límite de gastos para su viaje</p><p></p><p>**Escenario 2:** Alertas de presupuesto</p><p></p><p>**Dado que** el usuario está gastando durante su viaje</p><p>**Cuando** se acerque al límite de su presupuesto o lo exceda</p><p>**Entonces** debería recibir una alerta para ayudarle a controlar sus gastos</p>|EP05|
|US17|Ver reseñas|<p>**Como** usuario</p><p>**Quiero** poder ver reseñas de otros viajeros sobre destinos o actividades en la aplicación</p><p>**Para** poder tomar decisiones e informarme sobre mis viajes</p>|<p>**Escenario 1:** Explorar reseñas de destinos</p><p></p><p>**Dado que** el usuario está buscando reseñas sobre su destino</p><p>**Cuando** acceda a la página del destino</p><p>**Entonces** podrá ver las reseñas de otros usuarios junto con comentarios y calificaciones</p><p><br>**Escenario 2:** Explorar reseñas de actividades</p><p></p><p>**Dado que** el usuario está buscando reseñas sobre una actividad en particular</p><p>**Cuando** explore las opciones de actividades</p><p>**Entonces** podrá ver las reseñas de otros usuarios para esa actividad</p>|EP06|
|US18|Publicar reseñas|<p>**Como** usuario</p><p>**Quiero** poder publicar mis propias reseñas de destinos y servicios en la aplicación</p><p>**Para** compartir mi experiencia a los demás usuarios</p>|<p>**Escenario 1:** Escribir reseña</p><p></p><p>**Dado que** el usuario ha tenido una experiencia positiva en su viaje incluyendo destino, hotel o actividades</p><p>**Cuando** visite la página de los servicios</p><p>**Entonces** podrá escribir una reseña detallada y calificar su experiencia</p>|EP06|
|US19|Explorar ofertas y descuentos|<p>**Como** usuario</p><p>**Quiero** poder explorar ofertas y descuentos en la aplicación</p><p>**Para** encontrar oportunidades de ahorro durante la planificación del viaje</p>|<p>**Escenario 1:** Búsqueda de ofertas</p><p></p><p>**Dado que** el usuario está buscando descuentos</p><p>**Cuando** acceda a la sección de ofertas y descuentos</p><p>**Entonces** podrá ver descuentos especiales que brinda la aplicación</p><p></p><p>**Escenario 2:** Búsqueda de ofertas por filtros</p><p></p><p>**Dado que** el usuario está buscando descuentos para viajes, actividades o alojamientos específicos</p><p>**Cuando** acceda a la sección de ofertas y descuentos</p><p>Y aplique los filtros deseados</p><p>**Entonces** podrá encontrar descuentos especiales según los filtros ingresados</p>|EP09|
|US20|Aplicación de códigos promocionales|<p>**Como** usuario</p><p>**Quiero** tener la opción de ingresar códigos promocionales durante el proceso de pago</p><p>**Para** obtener descuentos adicionales en los servicios ofrecidos</p><p></p>|<p>**Escenario 1:** Ingresar código promocional</p><p></p><p>**Dado que** el usuario tiene un código promocional válido</p><p>**Cuando** esté en la página de pago durante el proceso de reserva</p><p>**Entonces** debería poder ingresar el código promocional en un campo designado y ver el descuento reflejado en el precio total antes de confirmar la reserva.</p><p></p>|EP09|
|US21|Compartir experiencia en redes sociales|<p>**Como** usuario</p><p>**Quiero** poder compartir mi experiencia de viaje en mis redes sociales</p><p>**Para** compartir momentos memorables de mi viaje</p>|<p>**Escenario 1:** Selección de red social</p><p></p><p>**Dado que** el usuario desea compartir la experiencia de su viaje en sus redes sociales</p><p>**Cuando** seleccione la opción de compartir</p><p>**Entonces** podrá ver todas las redes sociales disponibles que podrá vincular</p><p></p><p>**Escenario 2:** Compartir en red social</p><p></p><p>**Dado que** el usuario desea compartir la experiencia de su viaje en su red social preferida</p><p>**Cuando** seleccione la opción de compartir</p><p>Y elija su red social preferida</p><p>**Entonces** podrá compartir a su red social su experiencia de viaje</p>|EP06|
|US22|Contactar al soporte|<p>**Como** usuario</p><p>**Quiero** poder contactar al equipo de soporte de la aplicación</p><p>**Para** obtener ayuda con problemas técnicos</p>|<p>**Escenario 1:** Envío de consulta</p><p></p><p>**Dado que** el usuario tiene una pregunta sobre el funcionamiento de la aplicación o desea realizar un reclamo</p><p>**Cuando** acceda a la sección de soporte</p><p>**Y** complete el formulario de contacto</p><p>**Entonces** podrá enviar su consulta al soporte</p><p></p><p>**Escenario 2:** Respuesta del soporte</p><p></p><p>**Dado que** el usuario ha enviado una consulta al soporte</p><p>**Cuando** reciba una respuesta</p><p>**Entonces** podrá recibir asistencia a su problema</p>|EP07|
|US23|Dar feedback|<p>**Como** usuario</p><p>**Quiero** poder proporcionar feedback sobre la aplicación</p><p>**Para** compartir sugerencias o comentarios que ayuden a mejorar la experiencia del usuario</p>|<p>**Escenario 1:** Compartir sugerencias</p><p></p><p>**Dado que** el usuario tiene una idea para mejorar la aplicación</p><p>**Cuando** acceda a la sección de contacto</p><p>**Entonces** podrá enviar un correo al equipo de desarrollo para poder mejorar la aplicación</p>|EP07|
|US24|Visualizar una landing page atractiva|<p>**Como** visitante del landing page</p><p>**Quiero** visualizar una landing page clara y atractiva</p><p>**Para** entender el propósito de la aplicación</p>|<p>**Escenario 01:** Landing page clara y atractiva</p><p></p><p>**Dado que** el visitante ve la landing page con imágenes, videos e información relevante</p><p>**Cuando** complete el proceso de registro y login</p><p>**Entonces** será redirigido a la aplicación web</p>|EP08|
|US25|Visualizar features de la aplicación|<p>**Como** visitante del landing page</p><p>**Quiero** visualizar todos las funcionalidades y servicios que brinda TripMate</p><p>**Para** entender el uso de la aplicación</p>|<p>**Escenario 1:** Visualizar features</p><p></p><p>**Dado que** el usuario se encuentra en el landing page</p><p>**Cuando** visualice los features de la aplicación</p><p>**Entonces** entenderá el uso de la aplicación</p>|EP08|
|US26|Sección “Acerca de nosotros”|<p>**Como** visitante del landing page</p><p>**Quiero** visualizar una sección que me informe sobre el startup</p><p>**Para** conocer al equipo de TripMate y su propósito</p>|<p>**Escenario 1:** Visualiza sección sobre nosotros</p><p></p><p>**Dado que** el usuario se encuentra en el landing page</p><p>**Cuando** se dirija a la sección “Acerca de nosotros”</p><p>**Entonces** podrá visualizar a los miembros del startup y su propósito al crear TripMate</p>|EP08|
|US27|Sección “Convenios”|<p>**Como** visitante del landing page</p><p>**Quiero** visualizar los convenios que tiene TripMate</p><p>**Para** conocer las distintas empresas asociadas</p>|<p>**Escenario 1:** Acceso a la sección convenios</p><p></p><p>**Dado que** el usuario se encuentra en la landing page</p><p>**Cuando** acceda a la sección “Convenios”</p><p>**Entonces** visualizará las distintas empresas con las que trabaja TripMate</p>|EP08|
|US28|Sección “Testimonios”|<p>**Como** visitante del landing page</p><p>**Quiero** poder ver testimonios y experiencias de otros usuarios</p><p>**Para** conocer la opinión del público sobre TripMate</p>|<p>**Escenario 1:** Acceso a la sección de testimonios</p><p></p><p>**Dado que** el usuario está explorando el landing page</p><p>**Cuando** acceda a la sección de testimonios</p><p>**Entonces** podrá leer experiencias de otras personas usando la aplicación</p>|<p>EP08</p><p></p>|
|US29|Acceder desde cualquier dispositivo a la landing page|<p>**Como** visitante del landing page</p><p>**Quiero** que sea accesible desde diferentes dispositivos </p><p>**Para** poder ingresar al sitio web desde cualquier dispositivo</p>|<p>**Escenario 1:** Acceso al contenido del landing page desde cualquier dispositivo</p><p></p><p>**Dado que** la landing page es responsive</p><p>**Cuando** el usuario ingresa a nuestra landing page</p><p>**Entonces** podrá visualizar la información de manera organizada, adaptada al tamaño de pantalla que esté utilizando.</p><p></p><p>**Escenario 2:** Acceso al landing page, pero no es responsive con cualquier dispositivo</p><p></p><p>**Dado que** el usuario está ingresando al landing page desde otro dispositivo</p><p>**Cuando** revise la información y lo note desordenado y desagradable para la vista</p><p>**Entonces** cierra nuestra landing page y se dedica a seguir navegando por internet</p><p></p>|EP08|
|US30|Suscripción a membresía premium|<p>**Como** usuario</p><p>**Quiero** poder suscribirme a una membresía en la aplicación</p><p>**Para** poder adquirir beneficios adicionales</p>|<p>**Escenario 1:** Suscripción exitosa</p><p></p><p>**Dado** que el usuario está interesado en obtener beneficios adicionales en la aplicación</p><p>**Cuando** acceda a la sección de membresía premium</p><p>**Y** seleccione el plan premium</p><p>**Entonces** podrá completar el proceso de suscripción</p><p></p><p>**Escenario 2:** Error durante la suscripción</p><p></p><p>**Dado que** el usuario está interesado en obtener beneficios adicionales en la aplicación</p><p>**Cuando** intente suscribirse a la membresía premium</p><p>**Y** durante el proceso ingrese un método de pago incorrecto o haya un problema con el servicio de pago</p><p>**Entonces** recibirá un mensaje de error indicando la naturaleza del problema</p>|EP02|
|US31|Eliminar cuenta|<p>**Como** usuario</p><p>**Quiero** tener la opción de eliminar permanentemente mi cuenta y todos los datos asociados</p><p>**Para** borrar la información de mi cuenta de la aplicación</p><p></p>|<p>**Escenario 1:** Eliminar cuenta</p><p></p><p>**Dado que** el usuario ha decidido eliminar su cuenta de TripMate</p><p>**Cuando** acceda a la configuración de su cuenta y seleccione la opción para eliminarla</p><p>**Entonces** recibirá una confirmación </p><p>**Y**, después de confirmar, su cuenta y todos los datos asociados serán eliminados permanentemente</p><p></p>|EP02|


**Technical User Stories**

|**Technical story ID**|**Título**|**Descripción**|
| :- | :- | :- |
|TS01|Post User|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** registrar a un nuevo usuario mediante una API</p><p>**Para** visualizar los usuarios afiliados a nuestra aplicación</p>|
|TS02|Get User|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener la información de un usuario mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|
|TS03|Get User by Membership|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener la información de los usuarios por sus membresías</p><p>**Para** brindar la diferencia en las funcionalidades según su membresía</p>|
|TS04|Post Reservation|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** registrar una nueva reserva asociada a un usuario mediante una API</p><p>**Para** mantener el registro de reservas por usuario</p>|
|TS05|Get Reservation|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener la información de las reservas por usuario mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|
|<p>TS06</p><p></p>|Post Itinerary|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** registrar un nuevo itinerario asociado a un usuario mediante una API</p><p>**Para** mantener un registro de itinerarios por usuario</p>|
|TS07|Get Itinerary|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener la información sobre itinerarios de viaje por usuario **mediante una API**</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|
|TS08|Post Payment** Method|<p>**Como** desarrollador que trabaja en la aplicación de Tripmate</p><p>**Quiero** registrar un método de pago asociado a un usuario mediante una API</p><p>**Para** contar con la información para pagos futuros</p>|
|TS09|Get Payment Method|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener información sobre métodos de pago por usuario mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|
|TS10|Get Information by Places|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener información de los destinos de viaje mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|
|TS11|Get Budget|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener información sobre el presupuesto de los usuarios mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|
|TS12|Post Expenses|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** registrar pagos** realizados por los usuarios en sus viajes mediante una API</p><p>**Para** mantener un registro de los pagos por usuario</p>|
|TS13|Get Expenses|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener información sobre los gastos por usuario mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|
|TS14|Post Review|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** registrar reseñas de los usuarios mediante una API</p><p>**Para** mantener un registro de reseñas por usuario</p>|
|TS15|Get Review|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener información sobre las reseñas de distintos lugares, alojamientos o actividades</p><p>**Para** mostrarlas en la aplicación cuando se solicite</p>|

- 3.3. Impact Mapping

El Impact Mapping es una metodología de planificación estratégica que se centra en identificar y alinear los objetivos comerciales y las necesidades del usuario con las acciones concretas a realizar en el desarrollo de software. Se utiliza para visualizar y comunicar cómo las características y funcionalidades de un producto pueden contribuir al logro de objetivos empresariales más amplios.

Segmento Objetivo #1: Familias Viajeras y Aventureras

![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/8f05b34f-95bd-4ada-98ec-20085f71c1c5)

Segmento Objetivo #2: Viajeros lujosos

![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/e13c7cb7-f68a-4c98-a3b8-c74260b2ea98)

- 3.4. Product Backlog

|**# Orden**|**User Story ID**|**Título**|**Descripción**|**Story Points (1 / 2 / 3 / 5 / 8)**|
| :- | :- | :- | :- | :- |
|1|US05|Buscar destinos por filtros|<p>**Como** usuario</p><p>**Quiero** poder buscar destinos por categorías</p><p>**Para** explorar opciones según mis intereses y preferencias</p>|<p></p><p>5</p>|
|2|US06|Información sobre destinos|<p>**Como** usuario</p><p>**Quiero** poder acceder a información sobre destino de mi viaje</p><p>**Para pod**er conocer el lugar y planificar un itinerario</p>|<p></p><p>3</p>|
|3|US07|Explorar destinos populares|<p>**Como** usuario</p><p>**Quiero** poder explorar destinos populares en la aplicación</p><p>**Para** descubrir lugares recomendados por otros viajeros</p>|<p></p><p>3</p>|
|4|US08|Reservar alojamiento|<p>**Como** usuario </p><p>**Quiero** poder reservar alojamiento en la aplicación</p><p>**Para** asegurar mi hospedaje durante el viaje</p>|<p></p><p>8</p>|
|5|US09|Planificar itinerario|<p>**Como** usuario</p><p>**Quiero** poder planificar mi itinerario en la aplicación</p><p>**Para** organizar mis actividades durante el viaje</p>|<p></p><p>8</p>|
|6|US10|Compartir itinerario|<p>**Como** usuario</p><p>**Quiero** poder compartir mi itinerario de viaje** con otras personas</p><p>**Para** coordinar actividades y compartir planes</p>|<p></p><p>3</p>|
|7|US11|Explorar actividades cercanas|<p>**Como** usuario</p><p>**Quiero** poder explorar actividades y lugares de interés cercanos a mi ubicación actual</p><p>**Para** descubrir opciones adicionales durante mi viaje</p>|<p></p><p>3</p>|
|8|US12|Reservar transporte local|<p>**Como** usuario</p><p>**Quiero** poder reservar transporte local</p><p>**Para** facilitar mis desplazamientos durante el viaje</p>|<p></p><p>5</p>|
|9|US13|Descubrir eventos locales|<p>**Como** usuario</p><p>**Quiero** poder descubrir eventos locales</p><p>**Para** mejorar mi experiencia cultural durante mi viaje</p>|<p></p><p>3</p>|
|10|US15|Seguimiento de gastos|<p>**Como** usuario</p><p>**Quiero** poder realizar un seguimiento de mis gastos en la aplicación</p><p>**Para** mantenerme dentro de mi presupuesto</p>|<p></p><p>3</p>|
|11|US16|Establecer presupuesto|<p>**Como** usuario</p><p>**Quiero** poder establecer un presupuesto para mi viaje en la aplicación</p><p>**Para** poder controlar mis gastos</p>|<p></p><p>5</p>|
|12|US19|Explorar ofertas y descuentos|<p>**Como** usuario</p><p>**Quiero** poder explorar ofertas y descuentos en la aplicación</p><p>**Para** encontrar oportunidades de ahorro durante la planificación del viaje</p>|<p></p><p>3</p>|
|13|US20|Aplicación de códigos promocionales|<p>**Como** usuario</p><p>**Quiero** tener la opción de ingresar códigos promocionales durante el proceso de pago</p><p>**Para** obtener descuentos adicionales en los servicios ofrecidos</p><p></p>|<p></p><p>3</p>|
|14|US17|Ver reseñas|<p>**Como** usuario</p><p>**Quiero** poder ver reseñas de otros viajeros sobre destinos o actividades en la aplicación</p><p>**Para** poder tomar decisiones e informarme sobre mis viajes</p>|<p></p><p>3</p>|
|15|US18|Publicar reseñas|<p>**Como** usuario</p><p>**Quiero** poder publicar mis propias reseñas de destinos y servicios en la aplicación</p><p>**Para** compartir mi experiencia a los demás usuarios</p>|<p></p><p>3</p>|
|16|US21|Compartir experiencia en redes sociales|<p>**Como** usuario</p><p>**Quiero** poder compartir mi experiencia de viaje en mis redes sociales</p><p>**Para** compartir momentos memorables de mi viaje</p>|<p></p><p>3</p>|
|17|US14|Realizar pago|<p>**Como** usuario</p><p>**Quiero** poder realizar los pagos dentro de la aplicación</p><p>**Para** poder terminar de planificar el viaje</p>|<p></p><p>5</p>|
|18|US30|Suscripción a membresía premium|<p>**Como** usuario</p><p>**Quiero** poder suscribirme a una membresía en la aplicación</p><p>**Para** poder adquirir beneficios adicionales</p>|<p></p><p>3</p>|
|19|US24|Visualizar una landing page atractiva|<p>**Como** visitante del landing page</p><p>**Quiero** visualizar una landing page clara y atractiva</p><p>**Para** entender el propósito de la aplicación</p>|<p></p><p>3</p>|
|20|US25|Visualizar features de la aplicación|<p>**Como** visitante del landing page</p><p>**Quiero** visualizar todos las funcionalidades y servicios que brinda TripMate</p><p>**Para** entender el uso de la aplicación</p>|<p></p><p>3</p>|
|21|US26|Sección “Acerca de nosotros”|<p>**Como** visitante del landing page</p><p>**Quiero** visualizar una sección que me informe sobre el startup</p><p>**Para** conocer al equipo de TripMate y su propósito</p>|<p></p><p>3</p>|
|22|US27|Sección “Convenios”|<p>**Como** visitante del landing page</p><p>**Quiero** visualizar los convenios que tiene TripMate</p><p>**Para** conocer las distintas empresas asociadas</p>|<p></p><p>3</p>|
|23|US28|Sección “Testimonios”|<p>**Como** visitante del landing page</p><p>**Quiero** poder ver testimonios y experiencias de otros usuarios</p><p>**Para** conocer la opinión del público sobre TripMate</p>|<p></p><p>3</p>|
|24|US29|Acceder desde cualquier dispositivo a la landing page|<p>**Como** visitante del landing page</p><p>**Quiero** que sea accesible desde diferentes dispositivos </p><p>**Para** poder ingresar al sitio web desde cualquier dispositivo</p>|<p></p><p>3</p>|
|25|US23|Dar feedback|<p>**Como** usuario</p><p>**Quiero** poder proporcionar feedback sobre la aplicación</p><p>**Para** compartir sugerencias o comentarios que ayuden a mejorar la experiencia del usuario</p>|<p></p><p>3</p>|
|26|US22|Contactar al soporte|<p>**Como** usuario</p><p>**Quiero** poder contactar al equipo de soporte de la aplicación</p><p>**Para** obtener ayuda con problemas técnicos</p>|<p></p><p>2</p>|
|27|US01|Registro de usuario|<p>**Como** usuario nuevo</p><p>**Quiero** poder registrarme en TripMate** </p><p>**Para** poder acceder a todas las funcionalidades de la aplicación</p>|<p></p><p>1</p>|
|28|US02|Inicio de sesión|<p>**Como** usuario registrado</p><p>**Quiero** poder iniciar sesión en la aplicación</p><p>**Para** acceder a mi cuenta</p>|<p></p><p>1</p>|
|29|US03|Recuperación de contraseña|<p>**Como** usuario registrado</p><p>**Quiero** tener la opción de recuperación de contraseña</p><p>**Para** poder acceder a mi cuenta sin problemas</p>|<p></p><p>1</p>|
|30|US04|Cambiar dirección de correo electrónico|<p>**Como** usuario</p><p>**Quiero** poder cambiar la dirección de correo electrónico asociada a mi cuenta</p><p>**Para** mantener mi información de contacto actualizada</p>|<p></p><p>1</p>|
|31|US31|Eliminar cuenta|<p>**Como** usuario</p><p>**Quiero** tener la opción de eliminar permanentemente mi cuenta y todos los datos asociados</p><p>**Para** borrar la información de mi cuenta de la aplicación</p><p></p>|<p></p><p>1</p>|
|32|TS01|Post User|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** registrar a un nuevo usuario mediante una API</p><p>**Para** visualizar los usuarios afiliados a nuestra aplicación</p>|<p></p><p>3</p>|
|33|TS02|Get User|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener la información de un usuario mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|<p></p><p>3</p>|
|34|TS03|Get User by Membership|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener la información de los usuarios por sus membresías</p><p>**Para** brindar la diferencia en las funcionalidades según su membresía</p>|<p></p><p>3</p>|
|35|TS04|Post Reservation|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** registrar una nueva reserva asociada a un usuario mediante una API</p><p>**Para** mantener el registro de reservas por usuario</p>|<p></p><p>5</p>|
|36|TS05|Get Reservation|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener la información de las reservas por usuario mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|<p></p><p>3</p>|
|37|<p>TS06</p><p></p>|Post Itinerary|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** registrar un nuevo itinerario asociado a un usuario mediante una API</p><p>**Para** mantener un registro de itinerarios por usuario</p>|<p></p><p>5</p>|
|38|TS07|Get Itinerary|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener la información sobre itinerarios de viaje por usuario **mediante una API**</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|<p></p><p>3</p>|
|39|TS08|Post Payment** Method|<p>**Como** desarrollador que trabaja en la aplicación de Tripmate</p><p>**Quiero** registrar un método de pago asociado a un usuario mediante una API</p><p>**Para** contar con la información para pagos futuros</p>|<p></p><p>3</p>|
|40|TS09|Get Payment Method|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener información sobre métodos de pago por usuario mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|<p></p><p>3</p>|
|41|TS10|Get Information by Places|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener información de los destinos de viaje mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|<p></p><p>3</p>|
|42|TS11|Get Budget|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener información sobre el presupuesto de los usuarios mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|<p></p><p>3</p>|
|43|TS12|Post Expenses|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** registrar pagos** realizados por los usuarios en sus viajes mediante una API</p><p>**Para** mantener un registro de los pagos por usuario</p>|<p></p><p>5</p>|
|44|TS13|Get Expenses|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener información sobre los gastos por usuario mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|<p></p><p>3</p>|
|45|TS14|Post Review|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** registrar reseñas de los usuarios mediante una API</p><p>**Para** mantener un registro de reseñas por usuario</p>|<p></p><p>5</p>|
|46|TS15|Get Review|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener información sobre las reseñas de distintos lugares, alojamientos o actividades</p><p>**Para** mostrarlas en la aplicación cuando se solicite</p>|<p></p><p>3</p>|


### Capítulo IV: Product Design
- 4.1. Style Guidelines
  - 4.1.1. General Style Guidelines
    Se prioriza, legibilidad, espaciado, consistencia visual y simplicidad
- **Gráficos cohesivos:** Los íconos, botones, cajas de texto y otros agregados tendrán una estética similar para formar una identidad propia.
-**Main Font**: https://fonts.google.com/specimen/Roboto
<p align="center">
<img src="https://github.com/Jemisas/TripMate-Proyecto-Desarollo-de-Aplicaciones-Open-Source/assets/48342953/493ba2d5-e977-4495-965c-8aaab86e1ecc" width="350" height="250"></p>   
  - 4.1.2. Web Style Guidelines

- **Diseño Responsivo:** La aplicación debe ser compatible con diferentes dispositivos y tamaños de pantalla para una experiencia de usuario consistente en todos los dispositivos.
-**Navegación Intuitiva:** Estructura de navegación clara y fácil de usar que permita a los usuarios encontrar rápidamente la información que están buscando, se prioriza la simplicidad.
- **Carga Rápida:** Optimización del rendimiento de la aplicación para tiempos de carga rápidos, lo que incluye la optimización de imágenes y el uso de técnicas de almacenamiento en caché así como los scripts cargados al inicio de la página.
- **Diseño de Tarjetas:** Diseños de tarjetas para mostrar la información de manera visualmente atractiva y organizada, especialmente para la presentación de destinos y detalles de viajes.
- 4.2. Information Architecture
- 4.2.1. Organization Systems
- **Organización Secuencial (Step-by-Step to Accomplish):** Se usa en el proceso de reserva de alojamiento y actividades, guiando a los usuarios paso a paso para completar la reserva de manera eficiente, de forma que se complete mediante una serie de pasos consecuentes y ordenados.
- 4.2.2. Labeling Systems
    Se procura evitar confusiones y que las etiquetas utilizadas sean descriptivas y simples:
    - **Itinerarios:** "Aventura", "Cultura", "Relax", etc.
    - **Actividades:** "Excursión en la naturaleza", "Visita cultural", "Cena gourmet", etc.
    - **Alojamiento:** "Hotel", "Hostal", "Apartamento", etc.
- 4.2.3. SEO Tags and Meta Tags
- 4.2.4. Searching Systems

    Se expondrán los sistemas de búsqueda implementados para ayudar a nuestros usuarios a encontrar la información que están buscando.
        - En el Landing Page, los sistemas de búsqueda son estáticos, ya que la barra de navegación guiará a los usuarios hacia la sección de su interés. Estos sistemas están diseñados para optimizar la experiencia del usuario, proporcionando acceso rápido y directo a la información relevante que están buscando. 
- 4.2.5. Navigation Systems
  
     En cuanto a los sistemas de navegación, TripTeam ha implementado un enfoque intuitivo y fácil de usar para guiar a los usuarios a través de nuestra plataforma. Nuestra barra de navegación está diseñada para dirigir de manera eficiente a los usuarios hacia las secciones de su interés, facilitando la exploración y la búsqueda de información relevante.
- 4.3. Landing Page UI Design
- 4.3.1. Landing Page Wireframe
    
  En este apartado, se describe la estructura del sitio de nuestro proyecto. Con el fin de proporcionar una visión más clara del contenido que estará disponible en la plataforma. Esta es una representación en forma de bosquejo para Tripmate. 

  ![Imagen1](https://github.com/TripTeamOrganization/Informes/assets/89095594/c07127af-579d-4eb6-a24b-0c540b2abe0d)
  ![Imagen2](https://github.com/TripTeamOrganization/Informes/assets/89095594/b696399b-4eec-45c6-85e2-c282b092591d)
  ![Imagen3](https://github.com/TripTeamOrganization/Informes/assets/89095594/b4fe9e16-b1bc-4913-be0f-e02589544def)
  ![Imagen4](https://github.com/TripTeamOrganization/Informes/assets/89095594/1cd39301-5502-4ad6-9c05-1ea10574c83c)
  ![Imagen5](https://github.com/TripTeamOrganization/Informes/assets/89095594/ac7a845e-1da5-4557-a76d-b1c7ea0d0df1)
 
- 4.3.2. Landing Page Mock-up
    
  El Landing Page se desarrolló utilizando un prototipo en forma de Mock Up. A continuación, te presentamos una vista previa de nuestra propuesta:
    
   ![image](https://github.com/TripTeamOrganization/Informes/assets/89095594/60580ef7-89e3-40f9-a786-cd8282cf606d)
   ![image](https://github.com/TripTeamOrganization/Informes/assets/89095594/c37dbae6-8b3b-4cf5-9883-3b6d473f8ff7)
  ![image](https://github.com/TripTeamOrganization/Informes/assets/89095594/d41d33eb-53b0-47df-b550-db3325648568)
![image](https://github.com/TripTeamOrganization/Informes/assets/89095594/eac83dbe-e95d-4649-8e37-33b5a61f8cc1)
![image](https://github.com/TripTeamOrganization/Informes/assets/89095594/0b5bba97-43d8-4ffd-858c-ea6783db8b0a)
![image](https://github.com/TripTeamOrganization/Informes/assets/89095594/4ba87251-818b-4f59-ab35-8b0c898363a5)
![image](https://github.com/TripTeamOrganization/Informes/assets/89095594/164978aa-0523-4ae7-a749-0852cb16f329)
![image](https://github.com/TripTeamOrganization/Informes/assets/89095594/31ae7127-5de0-48e9-aa24-9ff566bc6ef0)
Desplazamiento de la barra hacia testimonios

  ![image](https://github.com/TripTeamOrganization/Informes/assets/89095594/743cca82-5667-480b-9c85-d86e96eca1f3)

  Desplazamiento de la barra hacia Acerca


   ![image](https://github.com/TripTeamOrganization/Informes/assets/89095594/295137c9-99e4-482c-87f7-0b2b6a6fac3d)

   Versiones

   ![image](https://github.com/TripTeamOrganization/Informes/assets/89095594/f8dfaf94-98d4-4603-8a10-6107a982204e)

  
  https://www.figma.com/file/2eL1Zj6N0ULup3L12N3imY/Leo%27s-team-library?type%3Ddesign%26node-id%3D0-1%26mode%3Ddesign%26t%3DCXLIiwbDD1OiPXhC-0
 

- 4.4. Web Applications UX/UI Design
  - 4.4.1. Web Applications Wireframes
  - 4.4.2. Web Applications Wireflow Diagrams
  - 4.4.3. Web Applications Mock-ups


  ![image](https://github.com/TripTeamOrganization/Informes/assets/89095594/cc0f33ed-24b5-46bc-9428-60ab2d6dac1f)
  
  - 4.4.4. Web Applications User Flow Diagrams


- 4.5. Web Applications Prototyping
- 4.6. Domain-Driven Software Architecture
  - 4.6.1. Software Architecture Context Diagram
  
   ![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/249ba48d-ab33-4e72-b479-43b4c6910565)

  - 4.6.2. Software Architecture Container Diagrams
  
   **Container Diagram elaborado para los usuarios:**
  ![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/e4781115-cfae-4325-820f-dd383101304d)
  
   **Container Diagram elaborado para los administradores:**
  ![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/29eb4b8d-08b2-4c6a-bdee-2baa9b084e3f)

  - 4.6.3. Software Architecture Components Diagrams

![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/f2877233-5baf-4816-a7c6-57337817b2dc)

- 4.7. Software Object-Oriented Design
  - 4.7.1. Class Diagrams
  
![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/36c60b42-bf36-4d13-babb-ca160ca4da46)

  - 4.7.2. Class Dictionary

**Class Usuario**

| Atributo             | Variable            | Descripción                                          |
|----------------------|---------------------|------------------------------------------------------|
| idUsuario (PK)         | int                 | Identificador único del usuario                      |
| nombreCompleto               | str                 | Nombre del usuario                                   |
| correo  | str                 | Correo electrónico del usuario                       |
| contrasenia           | str                 | Contraseña del usuario                               |
| fechaRegistro       | datetime            | Fecha de registro del usuario                        |

**Class Alojamiento**

| Atributo             | Variable            | Descripción                                          |
|----------------------|---------------------|------------------------------------------------------|
| idAlojamiento (PK)  | int                 | Identificador único del alojamiento                  |
| nombre               | str                 | Nombre del alojamiento                               |
| ubicacion            | str                 | Ubicación del alojamiento                            |
| tipo                 | str                 | Tipo de alojamiento                                  |
| comodidades          | str                 | Comodidades ofrecidas por el alojamiento             |
| precio               | money             | Precio del alojamiento por noche                     |

**Class Actividad**

| Atributo             | Variable            | Descripción                                          |
|----------------------|---------------------|------------------------------------------------------|
| idActividad (PK)    | int                 | Identificador único de la actividad                 |
| nombre               | str                 | Nombre de la actividad                               |
| descripcion          | str                 | Descripción de la actividad                          |
| ubicacion            | str                 | Ubicación de la actividad                            |
| duracion             | time             | Duración de la actividad en horas                    |
| precio               | money             | Precio de la actividad por persona                   |

**Class Reserva**

| Atributo             | Variable            | Descripción                                          |
|----------------------|---------------------|------------------------------------------------------|
| idReserva (PK)      | int                 | Identificador único de la reserva                    |
| idUsuario (FK)         | int                 | Identificador del usuario que realizó la reserva     |
| idAlojamiento (FK)  | int                 | Identificador del alojamiento reservado              |
| idActividad (FK)    | int                 | Identificador de la actividad reservada              |
| fechaReserva        | datetime            | Fecha y hora de la reserva                           |
| precioTotal     | money           | Precio total de la reserva                           |
| estado               | char                 | Estado de la reserva                                 |

**Class Valoracion**

| Atributo             | Variable            | Descripción                                          |
|----------------------|---------------------|------------------------------------------------------|
| idValoracion (PK)   | int                 | Identificador único de la valoración                 |
| idUsuario (FK)         | int                 | Identificador del usuario que realizó la valoración  |
| idAlojamiento (FK)  | int                 | Identificador del alojamiento valorado               |
| idActividad (FK)    | int                 | Identificador de la actividad valorada               |
| calificacion         | int                 | Calificación otorgada por el usuario                 |
| comentario           | str                 | Comentario del usuario sobre la valoración           |
| fechaValoracion     | datetime            | Fecha y hora de la valoración                        |

**Class Promocion**

| Atributo             | Variable            | Descripción                                          |
|----------------------|---------------------|------------------------------------------------------|
| idPromocion (PK)    | int                 | Identificador único del descuento                    |
| codigoPromocional   | str                 | Código promocional del descuento                     |
| tipoDescuento       | char                 | Tipo de descuento                                    |
| fechaInicio         | date                | Fecha de inicio del descuento                        |
| fechaFin            | date                | Fecha de fin del descuento                           |
| condicionesUso      | str                 | Condiciones de uso del descuento                     |

**Class Pago**

| Atributo             | Variable            | Descripción                                          |
|----------------------|---------------------|------------------------------------------------------|
| idPago (PK)    | int                 | Identificador único del descuento                    |
| descripcion       | str                 | Descripción del pago                                    |
| metodoPago         | str               | Metodo usado para el pago                       |
| fechaHoraPago            | datetime                | Fecha y hora del pago                          |
| condicionesUso      | str                 | Condiciones de uso del descuento                     |

- 4.8. Database Design
  
Para el proyecto TripMate, se ha optado por utilizar MySQL como motor de base de datos. Se ha tomado esta decisión debido a que MySQL es una plataforma escalable y cuenta con una interfaz intuitiva y fácil de usar. Además, el equipo tiene experiencia previa con el motor de Microsoft SQL Server, lo que facilita la transición. MySQL permite expandir los recursos utilizados en la base de datos según las necesidades y requisitos del negocio, lo que lo hace una elección adecuada para nuestro proyecto.

  - 4.8.1. Database Diagram
![image](https://github.com/TripTeamOrganization/Informes/assets/98995070/2c030260-e3db-485d-9a74-43e819a180e8)


### Capítulo V: Product Implementation, Validation & Deployment
- 5.1. Software Configuration Management
  - 5.1.1. Software Development Environment Configuration

    **Requirements Management**

      1. **Miro:** Plataforma en línea que permite la colaboración en tiempo real a través de pizarras digitales. Ofrece herramientas para la creación de diagramas, mapas mentales, diagramas de flujo, y más. En este caso, utilizamos Miro para la elaboración de As-Is y To-Be Scenarios Mapping.

      ![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/c6a157d4-5891-4df6-9a52-4155c04d3c37)

      2. **UXPressia:** Herramienta especializada en la creación de mapas de impacto de experiencia de usuario (UX). En este caso, utilizamos UXPressia para la elaboración del Impact Mapping para cada segmento objetivo.

      ![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/8337a3ad-5689-4f7c-9a67-1b7f6df8d95b)

      3. **Figma:** Herramienta de diseño de interfaces de usuario (UI) y prototipado colaborativo basada en la nube. En este caso, utilizamos Figma para la elaboración del prototipo de la aplicación.

      ![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/c4a55064-caee-464b-bdd8-908578c23e5f)

      4. **Trello**: Herramienta de gestión de proyectos basada en tableros. En este caso, utilizamos Trello para visualizar y actualizar el estado de las tareas e historias de usuario pertenecientes al sprint a desarrollar.

      ![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/6710a4bb-bc36-4e42-8417-57057bed3146)

      **Software Development**

      1. **Visual Studio Code:** Editor de código fuente desarrollado por Microsoft que ofrece una amplia gama de funcionalidades para programadores. En este caso, utilizamos Visual Studio Code como nuestro entorno de desarrollo integrado principal para escribir, editar y depurar el código HTML y CSS de nuestro proyecto.

      ![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/4e2f9613-5067-4294-89e2-e3426ca7605a)

      2. **HTML:** HTML (Hypertext Markup Language) es el lenguaje estándar utilizado para crear y diseñar páginas web. En este caso, utilizamos el lenguaje HTML para la creación y presentación de nuestra página web.

      ![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/d4a632ca-5dc9-4c77-b51a-3d1839e5476b)

      3. **CSS:** CSS (Cascading Style Sheets) es un lenguaje de diseño utilizado para estilizar la presentación de documentos HTML.

      ![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/2ff3321a-5c8f-4dc9-804e-cd6fa4027417)

      4. **GitHub:** Plataforma de desarrollo colaborativo basada en la nube que utiliza el sistema de control de versiones Git. Permite a los desarrolladores alojar, revisar y colaborar en proyectos de software. En este caso, utilizamos GitHub como un repositorio remoto para almacenar y gestionar el código fuente de nuestro proyecto.

      ![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/80bc9459-2cdd-40de-851b-d23d9eb62d4b)


  - 5.1.2. Source Code Management

    Para todo el ciclo de vida de nuestro proyecto, utilizaremos el sistema de control de versiones Git donde la evidencia será visualizada y registrada en la plataforma de GitHub de nuestra organización. Se podrá visualizar todos los cambios y modificaciones hechos por cada uno de los miembros del grupo. 

    GitHub URL: https://github.com/TripTeamOrganization 

  - 5.1.3. Source Code Style Guide & Conventions
  
    **HTML:** Para el lenguaje HTML, nos planteamos utilizar las convenciones descritas en la guía “HTML Style Guide and Coding Conventions”:

      1. Usar nombres de elementos en minúsculas
      2. Cerrar todos los elementos HTML
      3. Usar nombres de atributos en minúsculas 
      4. Usar atributos en imágenes
      5. Evitar líneas de código largas 
      6. Usar sintaxis simple para los enlaces para las hojas de estilo y para cargar script externos

    **CSS:** Para el lenguaje CSS, utilizaremos las siguientes prácticas para alcanzar un código coherente, sostenible y ordenado:

      1. Utilizar minúsculas y guiones para los nombres de propiedades
      2. Utilizar un espacio después de los dos puntos y un punto y coma para separar pares propiedad-valor.
      3. Agrupar reglas CSS relacionadas y separarlas con una línea en blanco.
      4. Utilizar nombres de clases que sean descriptivos y reflejen el propósito del elemento.
      5. Separar los nombres de las clases y ID con un guión

    **Gherkin:** Es un lenguaje de dominio específico diseñado para escribir especificaciones legibles por humanos que describen el comportamiento del software en un formato estructurado y comprensible. En busca de una buena práctica, se utilizarán saltos de línea para mejorar el orden de los escenarios y poder diferenciarlos de forma más óptima. Además, se escribirán los escenarios bajo el formato “Given”, “When”, “Then”, “And” para definir claramente el contexto, la acción y el resultado esperado.


  - 5.1.4. Software Deployment Configuration

    **Landing Page Deployment**

      Para desplegar nuestro landing page, utilizamos GitHub. Para esto es necesario contar con una cuenta personal, una organización y un repositorio al cual cargar los documentos. En este repositorio, se puede observar lo siguiente:
        - Una carpeta “html” con el archivo “index.html” el cual contiene nuestra landing page.
        - Una carpeta “css” la cual contiene nuestra hoja de estilos “style.css”
        - Una carpeta “images” la cual contiene las imágenes utilizadas en el landing page 
        - Una carpeta “js” la cual contiene nuestros scripts en un archivo “index.js” 


- 5.2. Landing Page, Services & Applications Implementation
  - 5.2.1. Sprint 1
    - 5.2.1.1. Sprint Planning 1
    Un sprint representa un periodo corto y fijo de tiempo durante el cual se desarrolla un conjunto de tareas o actividades específicas en un proyecto, asociado con metodologías ágiles como Scrum. El Sprint #1 tiene como fecha de inicio el 25/03/2024 y plantea elaborar una landing page atractiva para TripMate que capte la atención de los usuarios visitantes y comunique los principales beneficios de nuestro producto.


    |**Sprint #**|**Sprint 1**|
    | :- | :- |
    |Sprint Planning Background||
    |Date|25/03/2024|
    |Time|8:00 PM - 11:00 PM|
    |Location|Discord|
    |Prepared By||
    |Attendees|<p>Adrián Enrique Jesús Palma Obispo - u202210066</p><p>Paolo Del Carmen Martinez Villanueva - u202010039</p><p>Bárbara Antonella Espinoza Delgado - u201911727</p><p>Jeremy Joel Quispe Andia - u202216279</p><p>Leonel Alfaro Cumba -u20201a930</p>|
    |Sprint 0 Review Summary|Diseño y desarrollo del Landing Page|
    |Sprint 0 Retrospective Summary|Completar los diseños y estandarizar el lenguaje usado en el desarrollo y presentación del landing page|
    |Sprint Goal & User Stories||
    |Sprint 1 Goal|Elaborar, diseñar y desplegar una Landing Page atractiva e informativa para la aplicación TripMate|
    |Sprint 1 Velocity|15|
    |Sum of Story Points|15|

    - 5.2.1.2. Sprint Backlog 1

### Sprint 1

| User Story | Work-Item / Task              | Description                                                                                                                                                           | Estimation (Hours) | Assigned To                               | Status      |
|------------|-------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|-------------------------------------------|-------------|
| US24       | Sección de Galería            | Como usuario quiero poder ver una sección de galería que muestre imágenes relacionadas con los destinos y servicios ofrecidos, cambiando cada cierto tiempo.          | 5                  | Jeremy Joel Quispe Andia - u202216279   | ToReview    |
| US25       | Barra de Navegación          | Como usuario quiero tener una barra de navegación para poder moverme fácilmente entre las diferentes secciones de la página.                                        | 3                  | Bárbara Antonella Espinoza Delgado - u201911727 | Todo        |
| US23       | Fondo Animado                | Como usuario quiero experimentar un fondo animado utilizando un video de fondo para mejorar la estética y la experiencia visual de la página.                        | 2                  | Adrián Enrique Jesús Palma Obispo - u202210066 | InProcess   |
| US26       | Sección del Héroe            | Como usuario quiero ver una sección del héroe con un mensaje atractivo y convincente para tener una experiencia agradable en la página.                              | 3                  | Paolo Del Carmen Martinez Villanueva - u202010039 | Done        |
| US27       | Botón de Empezar Ahora       | Como usuario quiero tener un botón "Empezar Ahora" que me dirija hacia la siguiente acción deseada en la página.                                                      | 2                  | Leonel Alfaro Cumba                      | Todo        |

### Sprint 2

| Id | Title                              | Id | Title                              | Description                                                    | Estimation(Hours) | Assigned To                               | Status   |
|----|------------------------------------|----|------------------------------------|----------------------------------------------------------------|-------------------|-------------------------------------------|----------|
| 6  | US05 - Buscar destinos por filtros |    |                                     | Como usuario Quiero poder buscar destinos por categorías Para explorar opciones según mis intereses y preferencias | 8                 | Jeremy Joel Quispe Andia - u202216279   | Todo     |
| 7  | US06 - Información sobre destinos  |    |                                     | Como usuario Quiero poder acceder a información sobre destino de mi viaje Para poder conocer el lugar y planificar un itinerario | 5                 | Bárbara Antonella Espinoza Delgado - u201911727 | InProcess|
| 8  | US07 - Explorar destinos populares |    |                                     | Como usuario Quiero poder explorar destinos populares en la aplicación Para descubrir lugares recomendados por otros viajeros | 5                 | Paolo Del Carmen Martinez Villanueva - u202010039 | Todo     |
| 9  | US08 - Reservar alojamiento        |    |                                     | Como usuario Quiero poder reservar alojamiento en la aplicación Para asegurar mi hospedaje durante el viaje | 13                | Adrián Enrique Jesús Palma Obispo - u202210066 | Done     |
| 10 | US09 - Planificar itinerario       |    |                                     | Como usuario Quiero poder planificar mi itinerario en la aplicación Para organizar mis actividades durante el viaje | 13                | Leonel Alfaro Cumba                      | Todo     |

### Sprint 3

| Id | Title                             | Id | Title                             | Description                                                    | Estimation(Hours) | Assigned To                               | Status   |
|----|-----------------------------------|----|-----------------------------------|----------------------------------------------------------------|-------------------|-------------------------------------------|----------|
| 11 | US10 - Compartir itinerario       |    |                                     | Como usuario Quiero poder compartir mi itinerario de viaje con otras personas Para coordinar actividades y compartir planes | 5                 | Jeremy Joel Quispe Andia - u202216279   | Todo     |
| 12 | US11 - Explorar actividades cercanas |    |                                     | Como usuario Quiero poder explorar actividades y lugares de interés cercanos a mi ubicación actual Para descubrir opciones adicionales durante mi viaje | 5                 | Bárbara Antonella Espinoza Delgado - u201911727 | InProcess|
| 13 | US12 - Reservar transporte local  |    |                                     | Como usuario Quiero poder reservar transporte local Para facilitar mis desplazamientos durante el viaje | 8                 | Paolo Del Carmen Martinez Villanueva - u202010039 | Todo     |
| 14 | US13 - Descubrir eventos locales  |    |                                     | Como usuario Quiero poder descubrir eventos locales Para mejorar mi experiencia cultural durante mi viaje | 5                 | Adrián Enrique Jesús Palma Obispo - u202210066 | Done     |
| 15 | US15 - Seguimiento de gastos      |    |                                     | Como usuario Quiero poder realizar un seguimiento de mis gastos en la aplicación Para mantenerme dentro de mi presupuesto | 5                 | Leonel Alfaro Cumba                      | Todo     |
    
  - 5.2.1.3. Development Evidence for Sprint Review
    
|Repository|Branch|Commit ID|Commit Message|Commit Message Body|Commited On (Date)|  
|----------|------|---------|--------------|-------------------|------------------|
|TripTeamOrganization/FrontEnd|Main|f2dd6d87319d340e8b03afc44f7c9e50d8b7f2e0|Initial Commit|-|23/03/2024| 
|TripTeamOrganization/FrontEnd|Main|674d37b56cda9ce92f21c58d15c551d434b4bf8c|Images|-|23/03/2024| 
|TripTeamOrganization/FrontEnd|Main|47bef222912cdf116e49ae5a921929839d57804f|Button|-|23/03/2024| 
|TripTeamOrganization/FrontEnd|Main|234f27e728f50dd38feabf348e8b815c01749286|Update index.html|-|24/03/2024| 
|TripTeamOrganization/FrontEnd|Main|2a836c499e33e210cd4d489c65024bd79bd56a07|Navbar|-|25/03/2024| 
|TripTeamOrganization/FrontEnd|Main|d867e4d88ff0d400251e7229a427c7734d738577|Login y Register|-|28/03/2024| 
|TripTeamOrganization/FrontEnd|Main|6b4ccba822cabaffc7288ce022b3eed91e4aa15f|Navbar Estatica|-|29/03/2024| 
|TripTeamOrganization/FrontEnd|Main|b052271b0096a1149a3864ba181954029a4cdb96|More Cards and Better Button|-|29/03/2024| 
|TripTeamOrganization/FrontEnd|Main|eba687cddf7d0b6dd8433e3e49276455c43286e9|Mejora del Footer|Mejorar el footer|29/03/2024| 
|TripTeamOrganization/FrontEnd|Main|4d3d002997acb28a1ca0fed00b6f96db8197dd54|Prueba|-|29/03/2024| 
|TripTeamOrganization/FrontEnd|Main|b283a9c34d352016200864fef0865c182fc4c755|Update index.html|-|29/03/2024| 
|TripTeamOrganization/FrontEnd|Responsive|b30b72bb20a12c5afa243e91d11f1e78d33ba3b4|Responsive NavBar|-|30/03/2024| 
|TripTeamOrganization/FrontEnd|Responsive|08008d5496aa8899b1e0b6e4dd0678b0a964ddbe|Update index.css|-|30/03/2024| 
|TripTeamOrganization/FrontEnd|Responsive|5427a2b1714cac4c763eaf57e2e26fee8502842a|ResponsiveFooter|-|30/03/2024| 
|TripTeamOrganization/FrontEnd|Responsive|163aee97b6fa7a5698f67d74325ccb723e3193e8|Cambio de Fuente|-|31/03/2024| 
|TripTeamOrganization/FrontEnd|Responsive|8cfe8d8f2181f4906a7d2ecc0267ac97daa3f087|Responsive Cards|-|31/03/2024| 
|TripTeamOrganization/FrontEnd|Responsive|0e02db775d3c46bac114e2cf69db1211a65c78b3|Implementación Botón|-|31/03/2024|
|TripTeamOrganization/FrontEnd|Testimonios|15640e5a70139e4bf67aaa7077e2bc772f8f7026|Update index.css|-|29/03/2024| 
|TripTeamOrganization/FrontEnd|Testimonios|4524d2e6bdce66e14ca25c037b8c7ec113c5d8cf|Add Buttons|-|31/03/2024| 
|TripTeamOrganization/FrontEnd|Testimonios|df60b4b190f5ad459e66d243e49d60eb05040842|Add Buttons Styles|-|31/03/2024| 
|TripTeamOrganization/FrontEnd|Testimonios|6948049460628bcafd5257997a5c084cc41873d1|add js|-|31/03/2024| 
|TripTeamOrganization/FrontEnd|Testimonios|cffd774c830fa29804391aac5350d7c64044a76d|Remove Buttons css|-|31/03/2024|
|TripTeamOrganization/FrontEnd|Convenios|012de9ab0aadc3973bc2c8750ca2daed5f5fb728|Add Images|-|29/03/2024| 
|TripTeamOrganization/FrontEnd|Convenios|9e94cdadca756eea85b088f43f7957a31f876152|Update Section Convenios|-|29/03/2024|
|TripTeamOrganization/FrontEnd|Acerca de Nosotros|560ef7a4a955b748e2f28626668f54fa19a817e5|About|-|29/03/2024|
|TripTeamOrganization/FrontEnd|Acerca de Nosotros|37c73d7bc7dc4259fd831926e9906b9eab6c846e|Update index.css|-|31/03/2024|
|TripTeamOrganization/FrontEnd|Acerca de Nosotros|c5fd37d7d3f3b8ff52eb8b4e48241011dd8376f7|Update index.css|-|31/03/2024|

  - 5.2.X.4. Testing Suite Evidence for Sprint Review
    
En el proceso de desarrollo de la landing page, se aplicaron diversas estrategias de prueba para garantizar su correcto funcionamiento y adaptabilidad en diferentes entornos. A continuación se detallan las herramientas utilizadas y los enfoques adoptados:



## **1. Utilización de Live Server de Microsoft Visual Studio Code** 🖥

### Propósito:
Live Server se implementó para facilitar el desarrollo y la prueba de la landing page de manera local.

### Descripción:
Esta herramienta permitió la visualización dinámica de la landing page en el navegador web, lo que agilizó el proceso de desarrollo al mostrar los cambios en tiempo real sin necesidad de recargar manualmente la página.



## **2. Firefox Developer para Pruebas de Dimensiones Móviles** 

### Propósito:
Firefox Developer fue empleado para verificar la compatibilidad y el aspecto visual de la landing page en dispositivos móviles.

### Descripción:
Esta herramienta proporcionó un entorno de desarrollo amigable para simular diferentes dimensiones de pantalla y validar el diseño responsivo de la landing page en dispositivos móviles.



## **3. Aprovechamiento de las Propiedades del Navegador para Mejorar el Responsive** 

### Propósito:
Se aprovecharon las características específicas del navegador para mejorar la compatibilidad con CSS Grid y el diseño responsivo.

### Descripción:
Se exploraron las capacidades de inspección de elementos del navegador para ajustar y optimizar el diseño de la landing page, especialmente en lo que respecta al uso de CSS Grid. Además, se utilizaron las herramientas de depuración del navegador para identificar y corregir cualquier problema de diseño responsivo.



Estas estrategias de prueba garantizaron la funcionalidad, la estética y la adaptabilidad de la landing page en diversos dispositivos y navegadores, contribuyendo así a una experiencia de usuario excepcional. 

  - 5.2.X.5. Execution Evidence for Sprint Review
    
# Sprint 1

### Progreso en el Desarrollo
Durante el Sprint 1, se realizaron las siguientes implementaciones en la página de inicio:

1. **Sección de Galería:**
   - Se diseñó e implementó una sección de galería para mostrar imágenes relacionadas con los destinos y servicios ofrecidos cambiando cada cierto tiempo.
     
     ![image](https://github.com/TripTeamOrganization/Informes/assets/48342953/4885c9b1-affd-4881-a972-317e93ab264c)
     ![image](https://github.com/TripTeamOrganization/Informes/assets/48342953/33b25947-0ec1-4252-8e93-2f0e9ba8f972)

2. **Barra de Navegación (Navbar):**
   - Se creó y configuró una barra de navegación para permitir la navegación fácil entre las diferentes secciones de la página
     
     ![image](https://github.com/TripTeamOrganization/Informes/assets/48342953/3d31bf76-1433-44ff-b2ab-e5405a8df0e5)

3. **Fondo Animado:**
   - Se agregó un fondo animado utilizando un video de fondo para mejorar la estética y la experiencia visual de la página.
     
     ![image](https://github.com/TripTeamOrganization/Informes/assets/48342953/ab20dc42-f01b-4552-83fb-23f77e06b03f)

4. **Sección del Héroe:**
   - Se diseñó y desarrolló la sección del héroe con un mensaje atractivo y convincente para los usuarios.
     
     ![image](https://github.com/TripTeamOrganization/Informes/assets/48342953/e299d034-7a5f-4699-bac5-429aea84bee8)    

5. **Botón de Empezar Ahora:**
   - Se implementó el botón "Empezar Ahora" para dirigir a los usuarios hacia la siguiente acción deseada.
     
     ![image](https://github.com/TripTeamOrganization/Informes/assets/48342953/2ceca461-280f-4b96-af93-96eb6f1c1740)

6. **Características Principales:**
   - Se agregaron seis características principales con iconos representativos y descripciones concisas.
     
     ![image](https://github.com/TripTeamOrganization/Informes/assets/48342953/c0f3d4cb-d4e4-4476-8123-9b4e6d18053d)

7. **Sección "Acerca de Nosotros":**
   - Se completó la sección "Acerca de Nosotros" con información sobre la empresa y su misión.
     
     ![Imagen de WhatsApp 2024-04-01 a las 00 44 14_7411e807](https://github.com/TripTeamOrganization/Informes/assets/48342953/80816fce-d84b-4faf-a454-4cfcb7a9dee1)
     
8. **Sección de Convenios:**
   - Se agregaron detalles sobre los convenios establecidos con aerolíneas, hoteles y restaurantes.
          
     ![image](https://github.com/TripTeamOrganization/Informes/assets/48342953/f5177359-cb89-4a3e-a236-71d4b161f8c3)

9. **Sección de Testimonios:**
   - Se implementó la sección de testimonios con comentarios positivos de usuarios.
     ![Imagen de WhatsApp 2024-04-02 a las 22 19 20_f75d955c](https://github.com/TripTeamOrganization/Informes/assets/48342953/60a57cf9-9db6-47b1-86d3-06c2045c6cf5)

### Trabajo Restante
Aunque se logró mucho en el Sprint 1, aún quedan algunas tareas pendientes para completar:

- Integrar una galería de imágenes en la sección correspondiente.
- Realizar pruebas de rendimiento y corrección de errores menores antes del lanzamiento final.

### Conclusiones
El Sprint 1 fue crucial para añadir elementos clave a la página de inicio, como la sección del héroe y el botón "Empezar Ahora". Estas adiciones fortalecieron la llamada a la acción y la identidad de la marca. Sin embargo, aún hay aspectos adicionales por completar en los próximos sprints para mejorar aún más la experiencia del usuario.

# Conclusiones 

El proyecto de la *web app* **Tripmate** busca abordar de manera **efectiva** el problema de la mala elección de servicios, gastos innecesarios y desorganización al planificar un viaje a un nuevo destino. Al proporcionar una plataforma centralizada que ofrece opciones personalizadas y filtradas según las preferencias y presupuestos del usuario, se simplifica y optimiza significativamente el proceso de planificación de viajes. Esto se traduce en un **ahorro de tiempo y dinero** para los viajeros, así como en una mayor satisfacción al encontrar las opciones más adecuadas para sus necesidades.

La aplicación se centra en ofrecer una experiencia de usuario intuitiva y amigable, con características como:
- Filtros precisos
- Ingreso de presupuestos
- Notificaciones anticipadas sobre cambios en los servicios seleccionados

Estas funcionalidades están diseñadas para facilitar la búsqueda y selección de opciones de viaje, así como para evitar inconvenientes de última hora que puedan afectar negativamente la experiencia del usuario. Al priorizar la comodidad y la eficiencia, la *landing page* busca garantizar que los viajeros tengan una experiencia agradable desde el momento en que visitan nuestro sitio web hasta que deciden explorar más a fondo nuestras ofertas.

A través de un enfoque centrado en las necesidades del usuario y la diferenciación de la competencia, la *landing page* busca destacarse en el mercado de viajes en línea. La inclusión de características únicas, como la sección de galería para inspirar a los viajeros, la barra de navegación intuitiva y el fondo animado para captar la atención del usuario, se suma a su propuesta de valor. Además, la colaboración con empresas asociadas y la promoción de descuentos exclusivos pueden atraer a una base de usuarios más amplia y consolidar la posición de la página de inicio en el mercado. En resumen, la *landing page* se presenta como una solución atractiva y funcional para los viajeros, ofreciendo una experiencia de usuario fluida y diferenciada para planificar sus próximas aventuras.

## Bibliografía 

- Leiva, I. (2022). Esta es la cantidad de dinero que necesitas para viajar un año por el mundo. Recuperado de: [Yahoo Finanzas](https://es-us.finanzas.yahoo.com/noticias/esta-es-la-cantidad-de-dinero-que-necesitas-para-viajar-un-ano-por-el-mundo-161251049.html)
- Asmar, S. (2023). Consejos para no endeudarse en sus próximos viajes y pagar la deuda en pocos meses. Recuperado de: [La República](https://www.larepublica.co/finanzas-personales/consejos-para-no-endeudarse-en-sus-proximos-viajes-y-pagar-la-deuda-en-pocos-meses-3598007) 

## Anexos 📎

- Repositorio GitHub Frontend: [TripTeamOrganization/FrontEnd](https://github.com/TripTeamOrganization/FrontEnd)
- Repositorio GitHub Informe: [TripTeamOrganization/Informes](https://github.com/TripTeamOrganization/Informes)
- Figma: [Diseño en Figma](https://www.figma.com/file/9P8ofdPg7ra5Q4hRaNfbiy/Untitled?type=design&node-id=0-1&mode=design&t=X9NqDuXiAid9yx61-0)



