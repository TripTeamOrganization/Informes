

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
  Nuestra startup TripTeam es una plataforma que busca ayudar a las personas viajeras con
  los problemas de la desorganización, gastos innecesarios, pérdida de tiempo y no optar por las mejores opciones. Por ese motivo, nuestro objetivo como startup
  se enfoca en ayudar a los viajeros a tener un viaje organizado y satisfactorio.
  Para lograrlo, contamos con una plataforma que, mediante filtros, mostrará a los usuarios las aerolíneas, hoteles, restaurantes y actividades de
  entretenimiento que más se adecuen a sus preferencias y presupuestos, se mostrará más de una opción con imágenes, una descripción y los precios, los cuales
  serán igual o menores al que se indique para que la persona y así pueda elegir el que más le guste sin necesidad de entrar a varias páginas, investigar por
  horas y tantear, optimizando el tiempo del usuario. También se le hará un itinerario ordenado según las horas de vuelo y horarios de los restaurantes o
  lugares de interés los cuales estarán sujetos a cambios repentinos por motivos externos y serán notificados por nosotros a los usuarios en el menor tiempo
  posible. que el usuario puede tomar como recomendación para cada día de estancia. Además, se mostrarán las promociones que ofrecen las empresas desde sus
  páginas o descuentos exclusivos los cuales serán proporcionados por las empresas y cadenas con las que formaremos convenios.

  - 1.1.2. Perfiles de integrantes del equipo

| Integrante                           | Descripción del Perfil                                                                                          |
|-------------------------------------|------------------------------------------------------------------------------------------------------------------|
| Adrián Enrique Jesús Palma Obispo   | Curso la carrera de Ingeniería de Software de 5to Ciclo. Experiencia trabajando en equipo, aportando en diversas áreas y ayudando en tecnologías. Capacidad para aprender rápido. Curioso y puntual. |
| Bárbara Antonella Espinoza Delgado  | Estudiante de Ingeniería de Software de 6to ciclo. Experiencia en dirección de grupos, SQL, redacción, búsqueda de información, exposiciones y cumplimiento de tareas. Estricta y puntual. |
| Jeremy Quispe                        | Cursando el 3er ciclo de Ingeniería de Software en la UPC. Interés en crear soluciones tecnológicas con impacto positivo en la sociedad. Agradece a la universidad por brindar recursos para su desarrollo. |
| Leonel Alfaro Cumba                 | Estudiante de Ingeniería de Software con gran interés en la tecnología y la innovación. Motivado por ampliar conocimientos y desarrollarse constantemente. |
| Paolo Del Carmen Martinez Villanueva | Estudiante del 6to ciclo de Ingeniería de Software. Conocimientos intermedios en programación. Responsable, ordenado y trabajador. Comprometido a apoyar al equipo y adquirir nuevos conocimientos. |
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

| Entrevistado N°1: Sandro Quispesivana |<img src="https://github.com/TripTeamOrganization/Informes/assets/134337719/36f9bff8-5412-4069-a221-182eef515dbb" alt="Andrés Valle" style="width: 200px;">|
|--------------------------------|------------------------------------------------------------|
| **Nombre:**                    | Sandro Quispesivana                                               |
| **Edad:**                      | 30                                                         |
| **Sexo:**                      | Masculino                                                  |
| **Ocupación:**                 | Docente                                     |
| **Entrevista:**                | [Link](https://youtu.be/DzOgJiNWUvI)       |
| **Momento de inicio:**         | 0:03                                                       |
| **Duración:**                  | 3:59                                                       |

| Entrevistado N°2: Andrés Valle | <img src="URL_DE_LA_IMAGEN" alt="image" width="40" height="40"> |
|--------------------------------|------------------------------------------------------------|
| **Nombre:**                    | Andrés Valle                                               |
| **Edad:**                      | 32                                                         |
| **Sexo:**                      | Masculino                                                  |
| **Ocupación:**                 | Ingeniero Aeronáutico                                      |
| **Entrevista:**                | [Link](https://www.youtube.com/watch?v=DpATSL0ElpE)       |
| **Momento de inicio:**         | 0:04                                                       |
| **Duración:**                  | 3:50                                                       |


| Entrevistado N°3: Andrés Valle | <img src="URL_DE_LA_IMAGEN" alt="image" width="40" height="40"> |
|--------------------------------|------------------------------------------------------------|
| **Nombre:**                    | Andrés Valle                                               |
| **Edad:**                      | 32                                                         |
| **Sexo:**                      | Masculino                                                  |
| **Ocupación:**                 | Ingeniero Aeronáutico                                      |
| **Entrevista:**                | [Link](https://www.youtube.com/watch?v=DpATSL0ElpE)       |
| **Momento de inicio:**         | 0:04                                                       |
| **Duración:**                  | 3:50                                                       |

Segmento objetivo 2: Viajeros de lujo

| Entrevistado N°1: Andrés Valle |<img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/8f336f70-40b0-4477-94eb-6e92b7917524" alt="Andrés Valle" style="width: 200px;">|
|--------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| Nombre:                    | Andrés Valle                                                                                                          |
| Edad:                      | 32                                                                                                                    |
| Sexo:                      | Masculino                                                                                                             |
| Ocupación:                 | Ingeniero Aeronáutico                                                                                                 |
| Entrevista:                | Link                                                                    |
| Momento de inicio:         | 0:04                                                                                                                  |
| Duración:                  | 3:50                                                                                                                  |


| Entrevistado N°5: Andrés Valle | <img src="URL_DE_LA_IMAGEN" alt="image" width="40" height="40"> |
|--------------------------------|------------------------------------------------------------|
| **Nombre:**                    | Andrés Valle                                               |
| **Edad:**                      | 32                                                         |
| **Sexo:**                      | Masculino                                                  |
| **Ocupación:**                 | Ingeniero Aeronáutico                                      |
| **Entrevista:**                | [Link](https://www.youtube.com/watch?v=DpATSL0ElpE)       |
| **Momento de inicio:**         | 0:04                                                       |
| **Duración:**                  | 3:50                                                       |


| Entrevistado N°6: Andrés Valle | <img src="URL_DE_LA_IMAGEN" alt="image" width="40" height="40"> |
|--------------------------------|------------------------------------------------------------|
| **Nombre:**                    | Andrés Valle                                               |
| **Edad:**                      | 32                                                         |
| **Sexo:**                      | Masculino                                                  |
| **Ocupación:**                 | Ingeniero Aeronáutico                                      |
| **Entrevista:**                | [Link](https://www.youtube.com/watch?v=DpATSL0ElpE)       |
| **Momento de inicio:**         | 0:04                                                       |
| **Duración:**                  | 3:50                                                       |


- 2.2.3. Análisis de entrevistas
- 2.3. Needfinding
- 2.3.1. User Personas

Ahora procederemos a crear los perfiles de User Persona para cada uno de nuestros segmentos objetivo. Utilizaremos la información recopilada de las entrevistas realizadas, centrándonos especialmente en los objetivos, motivaciones y desafíos específicos de los diferentes grupos que componen nuestra audiencia objetivo. Esto implica la creación de perfiles representativos tanto de las familias viajeras y aventureras como de los viajeros de lujo. Estos perfiles se basarán en datos demográficos, geográficos y psicográficos detallados, que incluyen aspectos como edad, nivel socioeconómico, intereses de viaje y preferencias de alojamiento, entre otros.

Segmento objetivo 1: Julia Nuñez

![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/7cbfe038-1f9a-4cc3-815e-7950e9bee350)

Segmento objetivo 2: Martin Casanova

![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/1eb63308-e526-426f-a0e2-f8b5a16352b6)


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

![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/48fae10f-cc5a-4b1c-aff8-4de90cf00f5d)

Segmento objetivo 2: Martin Casanova

![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/4277733a-f9d9-467e-b4c9-bf3e9be88a4a)

- 2.3.4. Empathy Mapping
En esta sección se expone el Mapeo de Empatía de nuestros dos segmentos objetivos. Esta técnica se empleó para identificar a nuestra audiencia objetivo, comprender su contexto y sus necesidades, lo que nos permite entender su perspectiva y visión del mundo.

Segmento objetivo 1: Julia Nuñez
![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/a6ec1f85-77ca-4d58-8edb-2b961aa5c3da)

Segmento objetivo 2: Martin Casanova
![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/0d7adb09-340b-4109-aaea-3e018ba98e3f)


- 2.3.5. As-is Scenario Mapping



Segmento objetivo 1: Julia Nuñez

![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/8a3acc6a-d95c-469d-87dc-4a00a060b8e6)


Segmento objetivo 2: Martin Casanova

![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/32f038b7-9009-427b-a86c-0575b177d809)


- 2.4. Ubiquitous Language

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
|EP03|Búsqueda y exploración de destinos|<p>**Como** usuario</p><p>**Quiero** poder buscar y explorar destinos</p><p>**Para** planificar mi viaje</p>|Epic|EP02|
|EP04|Reservas y planificación de itinerarios|<p>**Como** usuario</p><p>**Quiero** poder realizar reservas y planificar itinerarios</p><p>**Para** preparar mi viaje</p>|Epic|EP03|
|EP05|Gestión de presupuestos|<p>**Como** usuario</p><p>**Quiero** tener herramientas de gestión de presupuestos</p><p>**Para re**alizar un seguimiento de mis gastos</p>|Epic|EP04|
|EP06|Ver y publicar reseñas|<p>**Como** usuario</p><p>**Quiero** poder compartir y ver reseñas de viajes** </p><p>**Para** descubrir destinos de viaje recomendados por otros usuarios</p>|Epic|EP05|
|EP07|Contacto|<p>**Como** visitante del landing page</p><p>**Quiero** contar con una sección que me permita contactar con los desarrolladores de la aplicación</p><p>**Para** resolver algún problema o dar mi opinión sobre la aplicación </p>|Epic|EP06|
|EP08|Información acerca de la aplicación|<p>**Como** visitante del landing page</p><p>**Quiero** contar con secciones que detallan los beneficios de la aplicación</p><p>**Para** tener información sobre el propósito del producto</p>|Epic|EP07|
|EP09|Vínculo entre la landing page y la aplicación|<p>**Como** visitante del landing page</p><p>**Quiero** contar con componentes que me dirijan a la aplicación** </p><p>**Para** poder acceder de una forma sencilla</p>|Epic|EP08|
|EP10|Descuentos|<p>**Como** usuario</p><p>**Quiero** poder acceder a descuentos en la aplicación</p><p>**Para** ahorrar dinero en mis viajes</p>|Epic|EP09|
|US01|Registro de usuario|<p>**Como** usuario nuevo</p><p>**Quiero** poder registrarme en TripMate** </p><p>**Para** poder acceder a todas las funcionalidades de la aplicación</p>|<p>**Escenario 1: Registro exitoso**</p><p>**Dado que** el usuario es nuevo</p><p>**Cuando** acceda a la página de registro</p><p>**Y** complete todos los campos requeridos</p><p>**Entonces** debería recibir una confirmación de registro</p><p></p><p>**Escenario 2: Registro fallido**</p><p>**Dado que** el usuario completó el formulario de registro</p><p>**Cuando** ingrese información inválida o incompleta</p><p>**Entonces** debería recibir un mensaje de error que indiquen los campos a corregir</p>|EP01|
|US02|Inicio de sesión|<p>**Como** usuario registrado</p><p>**Quiero** poder iniciar sesión en la aplicación</p><p>**Para** acceder a mi cuenta</p>|<p>Escenario 1: Inicio de sesión exitoso</p><p>**Dado que** el usuario se ha registrado</p><p>**Cuando** ingrese su correo electrónico y contraseña</p><p>**Entonces** debería poder acceder a mi cuenta</p><p></p><p>Escenario 2: Inicio de sesión fallido</p><p></p><p>**Dado que** el usuario se ha registrado</p><p>**Cuando** ingrese una credencial incorrecta</p><p>**Entonces** debería recibir un mensaje de error</p>|EP01|
|US03|Recuperación de contraseña|<p>**Como** usuario registrado</p><p>**Quiero** tener la opción de recuperación de contraseña</p><p>**Para** poder acceder a mi cuenta sin problemas</p>|<p>Escenario 1: Solicitud de recuperación de contraseña exitosa</p><p></p><p>**Dado que** el usuario ha olvidado su contraseña</p><p>**Cuando** acceda a la opción de recuperar contraseña</p><p>**Y** coloca el correo asociado a su cuenta</p><p>**Entonces** recibirá un correo electrónico con instrucciones para recuperar su contraseña</p><p></p><p>Escenario 2: Solicitud de recuperación de contraseña fallida</p><p></p><p>**Dado que** el usuario ha olvidado su contraseña</p><p>**Cuando** accede a la opción de recuperar contraseña</p><p>**Y** coloca un correo no asociado a su cuenta</p><p>**Entonces** mostrará un mensaje de error</p><p>**Y** deberá ingresar su correo nuevamente</p><p></p>|EP01|
|US04|Cambiar dirección de correo electrónico|<p>**Como** usuario</p><p>**Quiero** poder cambiar la dirección de correo electrónico asociada a mi cuenta</p><p>**Para** mantener mi información de contacto actualizada</p>|<p>Escenario 1: Acceder a la configuración de la cuenta</p><p></p><p>Dado que el usuario está registrado y ha iniciado sesión en la aplicación</p><p>Cuando acceda a la configuración de su cuenta desde el menú de perfil</p><p>Entonces podrá encontrar una opción para cambiar su dirección de correo electrónico</p><p></p><p>Escenario 2: Verificación de la nueva dirección de correo electrónico</p><p></p><p>**Dado que** el usuario ha ingresado una nueva dirección de correo electrónico en la configuración de su cuenta</p><p>**Cuando** guarde los cambios y la aplicación solicite verificar la nueva dirección</p><p>**Entonces** recibirá un correo electrónico de verificación en la nueva dirección y seguirá un proceso para confirmar el cambio</p><p></p>|EP01|
|US05|Buscar destinos por filtros|<p>**Como** usuario</p><p>**Quiero** poder buscar destinos por categorías</p><p>**Para** explorar opciones según mis intereses y preferencias</p>|<p>Escenario 1: Filtración de destinos</p><p></p><p>**Dado que** el usuario quiere planificar un viaje personalizado</p><p>**Cuando** utilice los filtros en la sección de búsqueda</p><p>**Entonces** debería ver una variedad de destinos según los filtros aplicados</p><p></p><p>Escenario 2: Selección de destino</p><p></p><p>**Dado que** el usuario quiere seleccionar un destino</p><p>**Cuando** encuentre su destino ideal</p><p>**Entonces** podrá seleccionarlo como destino del viaje</p>|EP03|
|US06|Información sobre destinos|<p>**Como** usuario</p><p>**Quiero** poder acceder a información sobre destino de mi viaje</p><p>**Para pod**er conocer el lugar y planificar un itinerario</p>|<p>Escenario 1: Información sobre destino</p><p></p><p>**Dado que** el usuario seleccionó el destino de su viaje</p><p>**Cuando** ingrese al apartado de información</p><p>**Entonces** podrá leer acerca de mi destino turístico</p><p></p><p>Escenario 2: Observar fotos y videos</p><p></p><p>**Dado que** el usuario quiere conocer el destino de su viaje</p><p>**Cuando** ingrese al apartado de videos y fotografías</p><p>**Entonces** podrá ver una variedad de fotos y videos acerca de su destino</p>|EP03|
|US07|Explorar destinos populares|<p>**Como** usuario</p><p>**Quiero** poder explorar destinos populares en la aplicación</p><p>**Para** descubrir lugares recomendados por otros viajeros</p>|<p>Escenario 1: Destino más visitado</p><p></p><p>**Dado que** el usuario quiere explorar destinos populares</p><p>**Cuando** acceda a la sección de destinos destacados</p><p>**Entonces** debería ver una lista de los destinos más visitados</p><p></p><p>Escenario 2: Recomendaciones de destinos</p><p></p><p>**Dado que** el usuario está interesado en recibir recomendaciones</p><p>**Cuando** complete su perfil con sus preferencias de viaje</p><p>**Entonces** debería ver sugerencias basadas en sus intereses</p>|EP03|
|US08|Reservar alojamiento|<p>**Como** usuario </p><p>**Quiero** poder reservar alojamiento en la aplicación</p><p>**Para** asegurar mi hospedaje durante el viaje</p>|<p>Escenario 1: Selección de fecha y tipo de alojamiento</p><p></p><p>**Dado que** el usuario quiere reservar alojamiento para su viaje</p><p>**Cuando** seleccione las fechas de estadía y el tipo de alojamiento deseado</p><p>**Entonces** se mostrará una lista de opciones de alojamiento disponibles</p>|EP04|
|US09|Planificar itinerario|<p>**Como** usuario</p><p>**Quiero** poder planificar mi itinerario en la aplicación</p><p>**Para** organizar mis actividades durante el viaje</p>|<p>Escenario 1: Agregar actividades</p><p></p><p>**Dado que** el usuario está planificando su viaje</p><p>**Cuando** explore las opciones de actividades </p><p>**Y** seleccione las que desea realizar</p><p>**Entonces** debería poder agregarlas a su itinerario con fecha y horario</p><p></p><p>Escenario 2: Visualizar itinerario</p><p></p><p>**Dado que** el usuario ha agregado actividades a su itinerario</p><p>**Cuando** acceda a la planificación de su viaje</p><p>**Entonces** podrá ver todas sus actividades organizadas por día y hora</p>|EP04|
|US10|Compartir itinerario|<p>**Como** usuario</p><p>**Quiero** poder compartir mi itinerario de viaje** con otras personas</p><p>**Para** coordinar actividades y compartir planes</p>|<p>Escenario 1: Compartir itinerario</p><p></p><p>**Dado que** el usuario ha creado un itinerario en la aplicación</p><p>Cuando seleccione la opción de compartir itinerario</p><p>**Entonces** podrá enviar una invitación a otros usuarios para que vean su itinerario</p><p></p><p>Escenario 2: Aceptar invitación</p><p></p><p>**Dado que** el usuario ha recibido una invitación para un itinerario</p><p>**Cuando** acepte la invitación</p><p>**Entonces** podrá ver y colaborar en el itinerario compartido</p><p></p>|EP04|
|US11|Explorar actividades cercanas|<p>**Como** usuario</p><p>**Quiero** poder explorar actividades y lugares de interés cercanos a mi ubicación actual</p><p>**Para** descubrir opciones adicionales durante mi viaje</p>|<p>Escenario 1: Búsqueda de actividades</p><p></p><p>**Dado que** el usuario se encuentra en una nueva ubicación durante su viaje</p><p>**Cuando** acceda a la función de explorar actividades cercanas</p><p>**Entonces** podrá ver una lista de actividades, restaurantes o lugares de interés recomendados en las cercanías</p><p></p><p>Escenario 2: Búsqueda por filtro</p><p></p><p>**Dado que** el usuario está buscando actividades personalizadas</p><p>**Cuando** explore las actividades cercanas por filtro</p><p>**Entonces** podrá encontrar fácilmente actividades adecuadas a sus preferencias</p>|EP04|
|US12|Reservar transporte local|<p>**Como** usuario</p><p>**Quiero** poder reservar transporte local</p><p>**Para** facilitar mis desplazamientos durante el viaje</p>|<p>Escenario 1: Búsqueda de transporte</p><p></p><p>Dado que el usuario necesita un transporte desde su ubicación hasta un lugar específico</p><p>Cuando acceda a la sección de transporte en la aplicación</p><p>Entonces podrá ver opciones de transporte disponibles</p><p></p><p>Escenario 2: Reserva de transporte</p><p></p><p>**Dado que** el usuario desea alquilar un transporte</p><p>**Cuando** encuentre el transporte adecuado y seleccione la hora, fecha y punto de inicio y fin del viaje</p><p>**Entonces** podrá reservar un transporte según sus necesidades</p>|EP04|
|US13|Descubrir eventos locales|<p>**Como** usuario</p><p>**Quiero** poder descubrir eventos locales</p><p>**Para** mejorar mi experiencia cultural durante mi viaje</p>|<p>Escenario 1: Búsqueda de eventos</p><p></p><p>**Dado que** el usuario está buscando eventos en su destino</p><p>**Cuando** use la función de buscar eventos locales</p><p>**Entonces** podrá visualizar todos los eventos locales que hay en su destino</p><p></p><p>Escenario 2: Selección de evento</p><p></p><p>**Dado que** el usuario está buscando eventos en su destino</p><p>**Cuando** use la función de buscar eventos locales</p><p>Y encuentre un evento que le llame la atención</p><p>**Entonces** podrá registrar ese evento como una actividad en su itinerario</p>|EP04|
|US14|Realizar pago|<p>**Como** usuario</p><p>**Quiero** poder realizar los pagos dentro de la aplicación</p><p>**Para** poder terminar de planificar el viaje</p>|<p>Escenario 1: Pago exitoso</p><p>**Dado que** el usuario ha organizado su viaje</p><p>**Cuando** quiera realizar el pago</p><p>**Entonces** la aplicación lo redireccionará a la sección de pago</p><p>**Y** podrá pagar el total de su viaje</p><p></p><p>Escenario 2: Pago fallido</p><p></p><p>**Dado que** el usuario ha organizado su viaje</p><p>**Y** desea realizar el pago</p><p>**Cuando** ingrese credenciales incorrectas en la sección de pago</p><p>**Entonces** la aplicación mostrará un mensaje de error</p><p>**Y** le permitirá volver a ingresar sus datos</p>|EP04|
|US15|Seguimiento de gastos|<p>**Como** usuario</p><p>**Quiero** poder realizar un seguimiento de mis gastos en la aplicación</p><p>**Para** mantenerme dentro de mi presupuesto</p>|<p>Escenario 1: Registro de gastos</p><p></p><p>**Dado que** el usuario está viajando</p><p>**Cuando** realice algún gasto relacionado con su viaje</p><p>**Entonces** podra registrar el monto en la aplicación</p><p></p><p>Escenario 2: Visualización de gastos</p><p></p><p>**Dado que** el usuario ha registrado varios gastos durante su viaje</p><p>**Cuando** acceda a la sección de seguimiento de gastos</p><p>**Entonces** podrá ver un resumen de sus gastos y un total acumulado</p>|EP05|
|US16|Establecer presupuesto|<p>**Como** usuario</p><p>**Quiero** poder establecer un presupuesto para mi viaje en la aplicación</p><p>**Para** poder controlar mis gastos</p>|<p>Escenario 1: Configuración de presupuesto</p><p></p><p>**Dado que** el usuario está planeando su viaje</p><p>**Cuando** ingrese el presupuesto total que tiene disponible</p><p>**Entonces** podrá establecer un límite de gastos para su viaje</p><p></p><p>Escenario 2: Alertas de presupuesto</p><p></p><p>**Dado que** el usuario está gastando durante su viaje</p><p>**Cuando** se acerque al límite de su presupuesto o lo exceda</p><p>**Entonces** debería recibir una alerta para ayudarle a controlar sus gastos</p>|EP05|
|US17|Ver reseñas|<p>**Como** usuario</p><p>**Quiero** poder ver reseñas de otros viajeros sobre destinos o actividades en la aplicación</p><p>**Para** poder tomar decisiones e informarme sobre mis viajes</p>|<p>Escenario 1: Explorar reseñas de destinos</p><p></p><p>**Dado que** el usuario está buscando reseñas sobre su destino</p><p>**Cuando** acceda a la página del destino</p><p>**Entonces** podrá ver las reseñas de otros usuarios junto con comentarios y calificaciones</p><p><br>Escenario 2: Explorar reseñas de actividades</p><p></p><p>**Dado que** el usuario está buscando reseñas sobre una actividad en particular</p><p>**Cuando** explore las opciones de actividades</p><p>**Entonces** podrá ver las reseñas de otros usuarios para esa actividad</p>|EP06|
|US18|Publicar reseñas|<p>**Como** usuario</p><p>**Quiero** poder publicar mis propias reseñas de destinos y servicios en la aplicación</p><p>**Para** compartir mi experiencia a los demás usuarios</p>|<p>Escenario 1: Escribir reseña</p><p></p><p>**Dado que** el usuario ha tenido una experiencia positiva en su viaje incluyendo destino, hotel o actividades</p><p>**Cuando** visite la página de los servicios</p><p>**Entonces** podrá escribir una reseña detallada y calificar su experiencia</p>|EP06|
|US19|Explorar ofertas y descuentos|<p>**Como** usuario</p><p>**Quiero** poder explorar ofertas y descuentos en la aplicación</p><p>**Para** encontrar oportunidades de ahorro durante la planificación del viaje</p>|<p>Escenario 1: Búsqueda de ofertas</p><p></p><p>**Dado que** el usuario está buscando descuentos</p><p>**Cuando** acceda a la sección de ofertas y descuentos</p><p>**Entonces** podrá ver descuentos especiales que brinda la aplicación</p><p></p><p>Escenario 2: Búsqueda de ofertas por filtros</p><p></p><p>**Dado que** el usuario está buscando descuentos para viajes, actividades o alojamientos específicos</p><p>**Cuando** acceda a la sección de ofertas y descuentos</p><p>Y aplique los filtros deseados</p><p>**Entonces** podrá encontrar descuentos especiales según los filtros ingresados</p>|EP010|
|US20|Aplicación de códigos promocionales|<p>**Como** usuario</p><p>**Quiero** tener la opción de ingresar códigos promocionales durante el proceso de pago</p><p>**Para** obtener descuentos adicionales en los servicios ofrecidos</p><p></p>|<p>Escenario 1: Ingresar código promocional</p><p></p><p>**Dado que** el usuario tiene un código promocional válido</p><p>**Cuando** esté en la página de pago durante el proceso de reserva</p><p>**Entonces** debería poder ingresar el código promocional en un campo designado y ver el descuento reflejado en el precio total antes de confirmar la reserva.</p><p></p>|EP10|
|US21|Compartir experiencia en redes sociales|<p>**Como** usuario</p><p>**Quiero** poder compartir mi experiencia de viaje en mis redes sociales</p><p>**Para** compartir momentos memorables de mi viaje</p>|<p>Escenario 1: Selección de red social</p><p></p><p>**Dado que** el usuario desea compartir la experiencia de su viaje en sus redes sociales</p><p>**Cuando** seleccione la opción de compartir</p><p>**Entonces** podrá ver todas las redes sociales disponibles que podrá vincular</p><p></p><p>Escenario 2: Compartir en red social</p><p></p><p>**Dado que** el usuario desea compartir la experiencia de su viaje en su red social preferida</p><p>**Cuando** seleccione la opción de compartir</p><p>Y elija su red social preferida</p><p>**Entonces** podrá compartir a su red social su experiencia de viaje</p>|EP06|
|US22|Contactar al soporte|<p>**Como** usuario</p><p>**Quiero** poder contactar al equipo de soporte de la aplicación</p><p>**Para** obtener ayuda con problemas técnicos</p>|<p>Escenario 1: Envío de consulta</p><p></p><p>**Dado que** el usuario tiene una pregunta sobre el funcionamiento de la aplicación o desea realizar un reclamo</p><p>**Cuando** acceda a la sección de soporte</p><p>**Y** complete el formulario de contacto</p><p>**Entonces** podrá enviar su consulta al soporte</p><p></p><p>Escenario 2: Respuesta del soporte</p><p></p><p>**Dado que** el usuario ha enviado una consulta al soporte</p><p>**Cuando** reciba una respuesta</p><p>**Entonces** podrá recibir asistencia a su problema</p>|EP07|
|US23|Dar feedback|<p>**Como** usuario</p><p>**Quiero** poder proporcionar feedback sobre la aplicación</p><p>**Para** compartir sugerencias o comentarios que ayuden a mejorar la experiencia del usuario</p>|<p>Escenario 1: Compartir sugerencias</p><p></p><p>**Dado que** el usuario tiene una idea para mejorar la aplicación</p><p>**Cuando** acceda a la sección de contacto</p><p>**Entonces** podrá enviar un correo al equipo de desarrollo para poder mejorar la aplicación</p>|EP07|
|US24|Visualizar features de la aplicación|<p>**Como** visitante del landing page</p><p>**Quiero** conocer sobre las funcionalidades de la **aplicación**</p><p>**Para** informarme sobre su uso</p>|<p>Escenario 1: Visualización de los features</p><p></p><p>**Dado que** el usuario se encuentra en el landing page </p><p>**Cuando** visualice la sección de features</p><p>**Entonces** podrá visualizar las funcionalidades de la aplicación</p>|EP08|
|US25|Acceso a descarga de la aplicación|<p>**Como** visitante del landing page</p><p>**Quiero** poder acceder al enlace de descarga de la aplicación</p><p>**Para** poder descargar la aplicación de forma rápida y sencilla</p>|<p>Escenario 1: Enlace directo</p><p></p><p>**Dado que** el usuario está interesado en usar la aplicación</p><p>**Cuando** haga clic en el enlace de descarga desde la landing page</p><p>**Entonces** la página redirigirá al usuario a la tienda o al sitio web para comenzar la descarga</p>|EP09|
|US26|Visualización de testimonios|<p>**Como** visitante del landing page</p><p>**Quiero** poder ver testimonios y experiencias de otros usuarios</p><p>**Para** conocer la opinión del público sobre TripMate</p>|<p>Escenario 1: Acceso a la sección de testimonios</p><p></p><p>**Dado que** el usuario está explorando el landing page</p><p>**Cuando** acceda a la sección de testimonios</p><p>**Entonces** podrá leer experiencias de otras personas usando la aplicación</p>|<p>EP08</p><p></p>|
|US27|Acceso a información legal|<p>**Como** visitante del landing page</p><p>**Quiero** poder acceder a la información legal de TripMate</p><p>**Para** conocer mis derechos y responsabilidades al utilizar la aplicación</p>|<p>Escenario 1: Visualizar información legal</p><p></p><p>**Dado que** el usuario está en el landing page</p><p>**Cuando** busque secciones que proporcionen información legal</p><p>**Entonces** podrá acceder a los términos de servicio y política de privacidad de TripMate</p>|EP09|
|US28|Suscripción a membresía premium|<p>**Como** usuario</p><p>**Quiero** poder suscribirme a una membresía en la aplicación</p><p>**Para** poder adquirir beneficios adicionales</p>|<p>Escenario 1: Suscripción exitosa</p><p></p><p>**Dado** que el usuario está interesado en obtener beneficios adicionales en la aplicación</p><p>**Cuando** acceda a la sección de membresía premium</p><p>**Y** seleccione el plan premium</p><p>**Entonces** podrá completar el proceso de suscripción</p><p></p><p>Escenario 2: Error durante la suscripción</p><p></p><p>**Dado que** el usuario está interesado en obtener beneficios adicionales en la aplicación</p><p>**Cuando** intente suscribirse a la membresía premium</p><p>**Y** durante el proceso ingrese un método de pago incorrecto o haya un problema con el servicio de pago</p><p>**Entonces** recibirá un mensaje de error indicando la naturaleza del problema</p>|EP02|
|US29|Eliminar cuenta|<p>**Como** usuario</p><p>**Quiero** tener la opción de eliminar permanentemente mi cuenta y todos los datos asociados</p><p>**Para** borrar la información de mi cuenta de la aplicación</p><p></p>|<p>Escenario 1: Eliminar cuenta</p><p></p><p>**Dado que** el usuario ha decidido eliminar su cuenta de TripMate</p><p>**Cuando** acceda a la configuración de su cuenta y seleccione la opción para eliminarla</p><p>**Entonces** recibirá una confirmación </p><p>**Y**, después de confirmar, su cuenta y todos los datos asociados serán eliminados permanentemente</p><p></p>|EP02|

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

Segmento Objetivo #1: Familias Viajeras y Aventureras

![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/8f05b34f-95bd-4ada-98ec-20085f71c1c5)

Segmento Objetivo #2: Viajeros lujosos

![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/e13c7cb7-f68a-4c98-a3b8-c74260b2ea98)

- 3.4. Product Backlog

|**# Orden**|**User Story ID**|**Título**|**Descripción**|**Story Points (1 / 2 / 3 / 5 / 8)**|
| :- | :- | :- | :- | :- |
|1|US24|Visualizar features de la aplicación|<p>**Como** visitante del landing page</p><p>**Quiero** conocer sobre las funcionalidades de la **aplicación**</p><p>**Para** informarme sobre su uso</p>|<p></p><p>1</p>|
|2|US25|Acceso a descarga de la aplicación|<p>**Como** visitante del landing page</p><p>**Quiero** poder acceder al enlace de descarga de la aplicación</p><p>**Para** poder descargar la aplicación de forma rápida y sencilla</p>|<p></p><p>1</p>|
|3|US23|Dar feedback|<p>**Como** usuario</p><p>**Quiero** poder proporcionar feedback sobre la aplicación</p><p>**Para** compartir sugerencias o comentarios que ayuden a mejorar la experiencia del usuario</p>|<p></p><p>1</p>|
|4|US26|Visualización de testimonios|<p>**Como** visitante del landing page</p><p>**Quiero** poder ver testimonios y experiencias de otros usuarios</p><p>**Para** conocer la opinión del público sobre TripMate</p>|<p></p><p>1</p>|
|5|US27|Acceso a información legal|<p>**Como** visitante del landing page</p><p>**Quiero** poder acceder a la información legal de TripMate</p><p>**Para** conocer mis derechos y responsabilidades al utilizar la aplicación</p>|<p></p><p>1</p>|
|6|US05|Buscar destinos por filtros|<p>**Como** usuario</p><p>**Quiero** poder buscar destinos por categorías</p><p>**Para** explorar opciones según mis intereses y preferencias</p>|<p></p><p>5</p>|
|7|US06|Información sobre destinos|<p>**Como** usuario</p><p>**Quiero** poder acceder a información sobre destino de mi viaje</p><p>**Para pod**er conocer el lugar y planificar un itinerario</p>|<p></p><p>3</p>|
|8|US07|Explorar destinos populares|<p>**Como** usuario</p><p>**Quiero** poder explorar destinos populares en la aplicación</p><p>**Para** descubrir lugares recomendados por otros viajeros</p>|<p></p><p>3</p>|
|9|US08|Reservar alojamiento|<p>**Como** usuario </p><p>**Quiero** poder reservar alojamiento en la aplicación</p><p>**Para** asegurar mi hospedaje durante el viaje</p>|<p></p><p>8</p>|
|10|US09|Planificar itinerario|<p>**Como** usuario</p><p>**Quiero** poder planificar mi itinerario en la aplicación</p><p>**Para** organizar mis actividades durante el viaje</p>|<p></p><p>8</p>|
|11|US10|Compartir itinerario|<p>**Como** usuario</p><p>**Quiero** poder compartir mi itinerario de viaje** con otras personas</p><p>**Para** coordinar actividades y compartir planes</p>|<p></p><p>3</p>|
|12|US11|Explorar actividades cercanas|<p>**Como** usuario</p><p>**Quiero** poder explorar actividades y lugares de interés cercanos a mi ubicación actual</p><p>**Para** descubrir opciones adicionales durante mi viaje</p>|<p></p><p>3</p>|
|13|US12|Reservar transporte local|<p>**Como** usuario</p><p>**Quiero** poder reservar transporte local</p><p>**Para** facilitar mis desplazamientos durante el viaje</p>|<p></p><p>5</p>|
|14|US13|Descubrir eventos locales|<p>**Como** usuario</p><p>**Quiero** poder descubrir eventos locales</p><p>**Para** mejorar mi experiencia cultural durante mi viaje</p>|<p></p><p>3</p>|
|15|US15|Seguimiento de gastos|<p>**Como** usuario</p><p>**Quiero** poder realizar un seguimiento de mis gastos en la aplicación</p><p>**Para** mantenerme dentro de mi presupuesto</p>|<p></p><p>3</p>|
|16|US16|Establecer presupuesto|<p>**Como** usuario</p><p>**Quiero** poder establecer un presupuesto para mi viaje en la aplicación</p><p>**Para** poder controlar mis gastos</p>|<p></p><p>5</p>|
|17|US19|Explorar ofertas y descuentos|<p>**Como** usuario</p><p>**Quiero** poder explorar ofertas y descuentos en la aplicación</p><p>**Para** encontrar oportunidades de ahorro durante la planificación del viaje</p>|<p></p><p>3</p>|
|18|US20|Aplicación de códigos promocionales|<p>**Como** usuario</p><p>**Quiero** tener la opción de ingresar códigos promocionales durante el proceso de pago</p><p>**Para** obtener descuentos adicionales en los servicios ofrecidos</p><p></p>|<p></p><p>3</p>|
|19|US17|Ver reseñas|<p>**Como** usuario</p><p>**Quiero** poder ver reseñas de otros viajeros sobre destinos o actividades en la aplicación</p><p>**Para** poder tomar decisiones e informarme sobre mis viajes</p>|<p></p><p>3</p>|
|20|US18|Publicar reseñas|<p>**Como** usuario</p><p>**Quiero** poder publicar mis propias reseñas de destinos y servicios en la aplicación</p><p>**Para** compartir mi experiencia a los demás usuarios</p>|<p></p><p>3</p>|
|21|US21|Compartir experiencia en redes sociales|<p>**Como** usuario</p><p>**Quiero** poder compartir mi experiencia de viaje en mis redes sociales</p><p>**Para** compartir momentos memorables de mi viaje</p>|<p></p><p>3</p>|
|22|US14|Realizar pago|<p>**Como** usuario</p><p>**Quiero** poder realizar los pagos dentro de la aplicación</p><p>**Para** poder terminar de planificar el viaje</p>|<p></p><p>5</p>|
|23|US28|Suscripción a membresía premium|<p>**Como** usuario</p><p>**Quiero** poder suscribirme a una membresía en la aplicación</p><p>**Para** poder adquirir beneficios adicionales</p>|<p></p><p>3</p>|
|24|US22|Contactar al soporte|<p>**Como** usuario</p><p>**Quiero** poder contactar al equipo de soporte de la aplicación</p><p>**Para** obtener ayuda con problemas técnicos</p>|<p></p><p>2</p>|
|25|US01|Registro de usuario|<p>**Como** usuario nuevo</p><p>**Quiero** poder registrarme en TripMate** </p><p>**Para** poder acceder a todas las funcionalidades de la aplicación</p>|<p></p><p>1</p>|
|26|US02|Inicio de sesión|<p>**Como** usuario registrado</p><p>**Quiero** poder iniciar sesión en la aplicación</p><p>**Para** acceder a mi cuenta</p>|<p></p><p>1</p>|
|27|US03|Recuperación de contraseña|<p>**Como** usuario registrado</p><p>**Quiero** tener la opción de recuperación de contraseña</p><p>**Para** poder acceder a mi cuenta sin problemas</p>|<p></p><p>1</p>|
|28|US04|Cambiar dirección de correo electrónico|<p>**Como** usuario</p><p>**Quiero** poder cambiar la dirección de correo electrónico asociada a mi cuenta</p><p>**Para** mantener mi información de contacto actualizada</p>|<p></p><p>1</p>|
|29|US29|Eliminar cuenta|<p>**Como** usuario</p><p>**Quiero** tener la opción de eliminar permanentemente mi cuenta y todos los datos asociados</p><p>**Para** borrar la información de mi cuenta de la aplicación</p><p></p>|<p></p><p>1</p>|
|27|TS01|Post User|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** registrar a un nuevo usuario mediante una API</p><p>**Para** visualizar los usuarios afiliados a nuestra aplicación</p>|<p></p><p>3</p>|
|28|TS02|Get User|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener la información de un usuario mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|<p></p><p>3</p>|
|29|TS03|Get User by Membership|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener la información de los usuarios por sus membresías</p><p>**Para** brindar la diferencia en las funcionalidades según su membresía</p>|<p></p><p>3</p>|
|30|TS04|Post Reservation|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** registrar una nueva reserva asociada a un usuario mediante una API</p><p>**Para** mantener el registro de reservas por usuario</p>|<p></p><p>5</p>|
|31|TS05|Get Reservation|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener la información de las reservas por usuario mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|<p></p><p>3</p>|
|32|<p>TS06</p><p></p>|Post Itinerary|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** registrar un nuevo itinerario asociado a un usuario mediante una API</p><p>**Para** mantener un registro de itinerarios por usuario</p>|<p></p><p>5</p>|
|33|TS07|Get Itinerary|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener la información sobre itinerarios de viaje por usuario **mediante una API**</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|<p></p><p>3</p>|
|34|TS08|Post Payment** Method|<p>**Como** desarrollador que trabaja en la aplicación de Tripmate</p><p>**Quiero** registrar un método de pago asociado a un usuario mediante una API</p><p>**Para** contar con la información para pagos futuros</p>|<p></p><p>3</p>|
|35|TS09|Get Payment Method|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener información sobre métodos de pago por usuario mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|<p></p><p>3</p>|
|36|TS10|Get Information by Places|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener información de los destinos de viaje mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|<p></p><p>3</p>|
|37|TS11|Get Budget|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener información sobre el presupuesto de los usuarios mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|<p></p><p>3</p>|
|38|TS12|Post Expenses|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** registrar pagos** realizados por los usuarios en sus viajes mediante una API</p><p>**Para** mantener un registro de los pagos por usuario</p>|<p></p><p>5</p>|
|39|TS13|Get Expenses|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener información sobre los gastos por usuario mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|<p></p><p>3</p>|
|40|TS14|Post Review|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** registrar reseñas de los usuarios mediante una API</p><p>**Para** mantener un registro de reseñas por usuario</p>|<p></p><p>5</p>|
|41|TS15|Get Review|<p>**Como** desarrollador que trabaja en la aplicación de TripMate</p><p>**Quiero** obtener información sobre las reseñas de distintos lugares, alojamientos o actividades</p><p>**Para** mostrarlas en la aplicación cuando se solicite</p>|<p></p><p>3</p>|

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
- 4.3. Landing Page UI Design
  - 4.3.1. Landing Page Wireframe
  - 4.3.2. Landing Page Mock-up
- 4.4. Web Applications UX/UI Design
  - 4.4.1. Web Applications Wireframes
  - 4.4.2. Web Applications Wireflow Diagrams
  - 4.4.3. Web Applications Mock-ups
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
![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/d04f07c2-3999-4c01-9b7c-36b612563ab0)


### Capítulo V: Product Implementation, Validation & Deployment
- 5.1. Software Configuration Management
  - 5.1.1. Software Development Environment Configuration
  - 5.1.2. Source Code Management
  - 5.1.3. Source Code Style Guide & Conventions
  - 5.1.4. Software Deployment Configuration
- 5.2. Landing Page, Services & Applications Implementation
  - 5.2.X. Sprint 1
    - 5.2.X.1. Sprint Planning 1
    - 5.2.X.2. Sprint Backlog 1
    - 5.2.X.3. Development Evidence for Sprint Review
    - 5.2.X.4. Testing Suite Evidence for Sprint Review
    - 5.2.X.5. Execution Evidence for Sprint Review
    - 5.2.X.6. Services Documentation Evidence for Sprint Review
    - 5.2.X.7. Software Deployment Evidence for Sprint Review
    - 5.2.X.8. Team Collaboration Insights during Sprint

**Conclusiones**

**Bibliografía**

**Anexos**


