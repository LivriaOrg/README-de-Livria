# Livria

<p align="center">Universidad Peruana de Ciencias Aplicadas (UPC)</p>
<p align="center">Carrera: Ingeniería de Software</p>
<p align="center">Ciclo: 06</p>
<p align="center">Aplicaciones Móviles 1ACC0238</p>
<p align="center">Sección 12614</p>
<p align="center">Profesor: David Gerardo Quevedo Velasco</p>

<p align="center"><strong>Informe del TB1</strong></p>

<p align="center">Defontes</p>
<p align="center">Binda Arbañil, Marcelo Alejandro U202311157</p>
<p align="center">Borja Molina, Gabriel Sebastián U202310308</p>
<p align="center">Castillo Garay, Ainhoa Lucía U202311701</p>
<p align="center">Martel Andrade, Cassius Estefano U202312287</p>
<p align="center">Nakamurake Teruya, Alex Tomio U20201f855</p>

<p align="center">Septiembre 2025</p>

# Registro de versiones del informe

## Versiones del Documento

| Versión   | Fecha     | Autor(es)                                                                                 | Descripción                                                                                   |
|-----------|-----------|--------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| 1.0 (TB1) | 25/04/25  | - Binda Arbañil, Marcelo Alejandro<br>- Borja Molina, Gabriel Sebastián<br>- Castillo Garay, Ainhoa Lucía<br>- Martel Andrade, Cassius Estefano<br>- Nakamurakare Teruya, Alex Tomio<br> | Capítulo I: Presentación
<br>Capítulo II: Requirements Development and Software Solution Design |

# Project Report Collaboration Insights

Repositorio donde está el project report: 




# Contenido

- [Livria](#livria)

- [Registro de versiones del informe](#registro-de-versiones-del-informe)
 
- [Project Report Collaboration Insights](#project-report-collaboration-insights)

- [Contenido](#contenido)

- [Student Outcome](#student-outcome)


# CAPÍTULO I: PRESENTACIÓN

## 1.1. Startup Profile

### 1.1.1. Descripción del Startup

Defontes es una startup liderada por estudiantes de la Universidad Peruana de Ciencias Aplicadas (UPC) dedicada a impulsar la lectura y facilitar su acceso en entornos digitales. Con el objetivo de acercar la literatura a más personas, se ha desarrollado el proyecto Livria, una aplicación web innovadora que permite a los usuarios descubrir, adquirir y disfrutar de libros en diversos formatos: físicos, electrónicos y audiolibros. 
En Defontes, creemos que la lectura es fundamental para el aprendizaje, la cultura y el desarrollo del pensamiento crítico. No solo se trata de un hábito, sino de una elección. Por ello, a través de una experiencia intuitiva y personalizada, Livria busca convertirse en el punto de encuentro ideal entre lectores y su próxima gran historia.
Misión: Promover el hábito de la lectura y facilitar el acceso a la literatura mediante una plataforma digital intuitiva y accesible. Livria busca conectar a los lectores con una amplia selección de libros en diferentes formatos, brindando una experiencia personalizada que fomente el amor por la lectura y el conocimiento.
Visión: Convertirse en la plataforma líder en América Latina para la compra y disfrute de libros en formatos físico, digital y audiolibro. Aspiramos a revolucionar la forma en que las personas acceden a la literatura, creando una comunidad de lectores apasionados y fortaleciendo la cultura literaria en el mundo digital.

### 1.1.2. Perfiles de los integrantes del equipo

| Nombre | Código | Carrera | Descripción |
|---|---|---|---|
| Binda Arbañil, Marcelo Alejandro | U202311157 | Ingeniería de Software | Soy Marcelo Binda y actualmente me encuentro cursando el sexto ciclo de la carrera de Ingeniería de Software, cuento con conocimientos técnicos en C++. Tengo una gran habilidad para organizar y realizar trabajos con la mayor eficiencia posible. |
| Borja Molina, Gabriel Sebastián | U202310308 | Ingeniería de Software | Soy Gabriel Borja y estudio la carrera de Ingeniería de Software de la UPC. Tengo conocimiento en el lenguaje de programación C++ y facilidad para aprender sobre temas nuevos. Me comprometo a brindar mi apoyo y responsabilidad para ayudar al equipo para culminar exitosamente el curso. |
| Castillo Garay, Ainhoa Lucía | U202311701 | Ingeniería de Software | Mi nombre es Ainhoa Castillo y estoy cursando mi sexto ciclo en la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Me considero una persona activa y responsable. Me gusta trabajar en un ambiente tranquilo y divertido, pero siempre eficaz. Me gusta programar y resolver problemas mediante soluciones creativas. |
| Martel Andrade, Cassius Estefano | U202312287 | Ingeniería de Software | Me llamo Cassius Martel y soy estudiante de Ingeniería de Software, y tengo cierta experiencia usando C++, C#, Java, etc. Me caracterizó por ser una persona con iniciativa y liderazgo, que siempre procura la efectividad de cada integrante del equipo y la realización de un buen trabajo. |
| Nakamurakare Teruya, Alex Tomio | U20201f855 | Ingeniería de Software | Mi nombre es Alex Tomio Nakamurakare y soy estudiante de la carrera de Ingeniería de Software de la UPC. El motivo por el cual estoy en esta carrera es debido a que me gusta mucho analizar problemas y crear soluciones mediante el uso de la programación. |

## 1.2. Solution Profile

Livria es una aplicación web diseñada para revolucionar la manera en que las personas adquieren y disfrutan de los libros. A través de una plataforma intuitiva y accesible, ofrece una amplia selección de títulos, permitiendo a los usuarios explorar y comprar sus lecturas favoritas de forma fácil y rápida. Con el objetivo de fomentar el hábito de la lectura y crear una comunidad de amantes de los libros, Livria facilita la conexión entre los lectores y el mundo literario en un entorno digital moderno.
 
### 1.2.1. Antecedentes y Problemática

De acuerdo con Lean Construction México, la metodología de las 5W’s y 2H’s permite estructurar y desarrollar un plan de acción o una estrategia detallada (Alvarez, 2020). En este contexto, esta herramienta resulta clave para comprender a fondo las necesidades de los usuarios. Por esta razón, se utilizó para recopilar información, la cual se presentará a continuación.

#### 1.2.1.1. What

##### ¿Cuál es el problema?

Livria nace como respuesta a una problemática alarmante: la falta de hábito de lectura y los bajos niveles de comprensión lectora, especialmente en adolescentes y jóvenes. Según la Encuesta Nacional de Lectura de 2022 (Ministerio de Cultura), solo el 15.3 % de menores de 0 a 17 años lee con regularidad diaria y, peor aún, el 21.2 % no lee en absoluto. En adultos alfabetos de 18 a 64 años, a nivel nacional, existe un porcentaje mayor de no lectores, que asciende al 52.7% (Ministerio de Cultura, 2022), lo que evidencia un hábito lector frágil y poco sostenido.

A esto se suma la influencia de las redes sociales y el consumo de contenido breve e inmediato, que ha desplazado el interés por la lectura profunda y reflexiva. Un estudio realizado en una institución educativa pública del distrito de El Agustino en 2022 reveló que el 72.2 % de los estudiantes de secundaria se encuentran en un nivel bajo de comprensión lectora, y solo un 1.9 % alcanzó un nivel alto (Torres-Vega, 2025). Esta situación refleja una crisis silenciosa en el desarrollo educativo y cognitivo de las nuevas generaciones.

En este contexto, Livria se presenta como una solución innovadora que busca revertir esta tendencia preocupante. A través de una plataforma web moderna, accesible y atractiva, busca acercar los libros a los usuarios, fomentar el gusto por la lectura y construir una comunidad de lectores comprometidos, adaptada a los hábitos digitales de hoy.

##### ¿Cuál es la relación con la persona en cuestión?

Para todo aquel que esté interesado en la lectura, Livria se presenta como una plataforma atractiva que elimina las barreras en el acceso a materiales adecuados, fomenta el hábito de la lectura y conecta a los jóvenes con libros en distintos formatos, adaptándose a sus costumbres digitales y promoviendo el interés por la lectura de manera dinámica y envolvente.

#### 1.2.1.2. When

##### ¿Cuándo sucede el problema?

El problema de la baja tasa de lectura y comprensión lectora se agrava cuando los potenciales lectores enfrentan barreras de acceso a los materiales de lectura. 

Específicamente, esto ocurre cuando:

* Una persona intenta acceder a material de estudio o contenido literario que no está disponible en las principales plataformas
* Enfrenta dificultades con los procesos de compra o alquiler debido a largos tiempos de entrega
* Encuentra inconvenientes con los métodos de pago ofrecidos
* Necesita acceso inmediato a contenido pero debe esperar por cuestiones logísticas
* No encuentra un entorno motivador o una red de apoyo que lo incentive a continuar leyendo, lo que impide que la lectura se transforme en un hábito.

Estas barreras desincentivan el hábito lector y contribuyen directamente a las bajas estadísticas citadas en la Encuesta Nacional de Lectura, especialmente en un contexto donde lo digital e inmediato predomina.

##### ¿Cuándo utiliza el cliente el servicio?

El cliente usará Livria precisamente cuando quiera o necesite acceder a material de lectura sin enfrentar estas barreras, permitiéndole desarrollar y mantener un hábito lector regular gracias a su sistema de entrega rápida para libros físicos y acceso instantáneo a materiales digitales.
Además, cuando el cliente desea compartir sus opiniones, descubrir nuevas lecturas recomendadas por personas con intereses similares o interactuar con otros lectores apasionados, utilizará la sección de comunidad. Este espacio impulsa la conexión social en torno a la lectura, creando un entorno motivador y enriquecedor para los usuarios.

#### 1.2.1.3. Where

##### ¿Dónde está el cliente cuando usa el producto?

Livria está diseñada como una aplicación accesible tanto en versión web como móvil, lo que permite a los usuarios disfrutar de sus funcionalidades desde cualquier lugar con conexión a internet. De este modo, pueden acceder a la plataforma ya sea desde sus computadoras o dispositivos móviles, facilitando la lectura y el acceso a libros en cualquier momento y contexto.

##### ¿Dónde surge el problema?

La problemática surge en los hogares y escuelas del Perú. Estos espacios son fundamentales para la formación de hábitos y habilidades lectoras, pero, en la actualidad, no se promueve activamente la lectura como una práctica cotidiana. La escasa presencia de libros, la ausencia de rutinas de lectura y el poco estímulo hacia el interés por los textos en estos espacios limitan el desarrollo del hábito lector.

#### 1.2.1.4. Who

##### ¿Quiénes están involucrados?

Los principales involucrados en Livria son, en primer lugar, los amantes de la lectura, quienes buscan un espacio dinámico y accesible para descubrir, compartir y disfrutar de nuevos libros. Además, un grupo clave son aquellas personas, especialmente adolescentes y jóvenes, que desean mejorar su hábito lector o incluso dar sus primeros pasos en el mundo de la lectura.

##### ¿A quiénes les sucede el problema?

El problema afecta principalmente a adolescentes y jóvenes, quienes enfrentan dificultades en la comprensión lectora y han perdido el interés por la lectura debido a la influencia de las redes sociales y el consumo de contenido breve e inmediato. Asimismo, afecta a adultos de diferente rango de edad, quienes muchas veces no cuentan con el tiempo, el hábito o el acceso a libros adecuados. En un sentido más amplio, el problema repercute en la sociedad en general, ya que la falta de lectura impide el desarrollo del pensamiento crítico, la educación y el acceso a la información, reduciendo las oportunidades de crecimiento personal y profesional.

##### ¿Quién lo utilizará?

Livria será utilizada por una variedad de usuarios con necesidades y características específicas. En primer lugar, por adolescentes y jóvenes en busca de entretenimiento educativo, que desean una plataforma que haga la lectura más atractiva y relevante, con géneros y libros populares y recomendaciones personalizadas; así como aquellos con dificultades en comprensión lectora que buscan mejorar sus habilidades de lectura de manera accesible y adaptada a su ritmo. Por otro lado, adultos de diferentes edades que han dejado de leer por falta de tiempo o motivación, pero ahora desean retomar el hábito de la lectura con libros que se ajusten a sus intereses y disponibilidad de tiempo.

#### 1.2.1.5. Why

##### ¿Cuál es la causa del problema?

Puesto que la problemática es la falta de hábito de lectura y los bajos niveles de comprensión lectora, se pueden identificar diversas causas que contribuyen a esta situación.

Una de las principales es la influencia de las redes sociales y el consumo de contenido digital breve. La exposición constante a videos cortos, memes y publicaciones rápidas ha modificado los hábitos de consumo de información, reduciendo la capacidad de concentración y la disposición a leer textos extensos. Esto ha generado que, especialmente entre adolescentes y jóvenes, la lectura se perciba como una actividad poco atractiva o demasiado exigente en comparación con el entretenimiento inmediato que ofrece el entorno digital. A medida que los jóvenes dedican mayor tiempo a las redes sociales, se incrementa el impacto negativo en su rendimiento académico (Mamami et al.,2024) y, por ende, se compromete su nivel de comprensión lectora. 

Otra causa significativa es la falta de estímulo lector en el hogar. Muchos niños y jóvenes crecen en contextos donde la lectura no forma parte de la rutina diaria, ya sea por la ausencia de libros en casa, el poco interés de los adultos responsables o la falta de tiempo para compartir momentos de lectura en familia. Esta falta de acompañamiento desde edades tempranas limita el desarrollo de un vínculo positivo con la lectura. Además, se suma el escaso acceso a libros atractivos y adecuados. La adquisición de ellos es, muchas veces, dificultosa por cuestiones económicas; el acceso a nuevas ediciones se convierte en un lujo (D’Adderio, 2020). La limitada oferta de títulos que conecten con los gustos, intereses y realidades de los jóvenes, junto con el elevado costo de muchos libros o su baja disponibilidad en espacios públicos como bibliotecas, hace que el hábito lector sea difícil de desarrollar y sostener en el tiempo.

#### 1.2.1.6. How

##### ¿En qué condiciones los clientes utilizan nuestro producto?

Los clientes utilizan Livria en diversas condiciones, principalmente desde su entorno cotidiano, como el hogar, el centro de estudios o el lugar de trabajo, a través de dispositivos como celulares, tablets o computadoras. Gracias a su disponibilidad tanto en versión web como en aplicación móvil, los usuarios pueden explorar o adquirir libros en sus momentos libres, durante viajes o en tiempos de ocio.

Además, muchos acceden a Livria cuando desean descubrir nuevas lecturas, mejorar su comprensión lectora o simplemente reconectar con el hábito de leer. Estas condiciones responden a intereses personales, necesidades académicas o al deseo de aprovechar mejor el tiempo libre. En general, la plataforma se adapta al usuario, priorizando la comodidad, la accesibilidad y la personalización de la experiencia lectora.

##### ¿Cómo nos conocieron los compradores?

Los compradores conocen Livria mediante diversas vías de marketing, tales como la promoción en redes sociales (TikTok, Instagram, etc.), donde se comparte contenido relevante sobre el producto y se realizan campañas publicitarias para atraer a posibles clientes interesados en la lectura. Asimismo, los compradores pueden descubrir la plataforma a través de cartelería publicitaria en locales relacionados con el mundo de la lectura, como las bibliotecas públicas o la tienda física de Livria.

##### ¿Cómo prefieren los lectores acceder a nuestro contenido?

Los lectores prefieren acceder al contenido de Livria de manera rápida, sencilla y personalizada, ya sea desde la aplicación móvil o la versión web disponible en sus computadoras. Esta flexibilidad les permite realizar búsquedas y compras de libros desde cualquier lugar en el que se encuentren. Asimismo, valoran la propuesta de Livria por ofrecer un acceso dinámico y adaptado a sus hábitos digitales, donde la lectura se vive como una experiencia placentera y motivadora, más que como una obligación.

##### ¿Qué llevó a la persona a llegar a esta situación?

Lo que llevó a la persona a llegar a esta situación —es decir, a perder el hábito de lectura o a tener poca comprensión de textos— es una combinación de factores personales y sociales que se han acumulado a lo largo del tiempo.

En muchos casos, la falta de estímulos adecuados desde la infancia, tanto en el hogar como en la escuela, impidió que la lectura se convirtiera en una actividad cotidiana o placentera. Muchos educadores afirman que los recursos que poseen son poco suficientes para desarrollar la motivación de lectura en sus estudiantes (Fabiana & Vega, 2022). Además, la poca disponibilidad de libros atractivos o económicamente accesibles han contribuido al alejamiento del mundo literario.

A esto se suma la influencia creciente del entorno digital, donde predominan contenidos breves, visuales y de consumo rápido, que reducen la capacidad de concentración y hacen que leer un libro parezca una tarea demandante o incluso aburrida. En algunos casos, también influyen falta de tiempo, desmotivación o desconocimiento sobre qué leer o cómo empezar.

Todo esto ha llevado a que muchas personas lleguen a la actualidad sin una conexión real con los libros, con niveles bajos de comprensión lectora y con la sensación de que leer es algo ajeno a sus intereses o estilo de vida.

#### 1.2.1.7. How much

##### 1.2.1.7.1 Estadísticas que sustentan la problemática

Según los resultados de la Encuesta Nacional de Lectura de 2022 (Ministerio de Cultura), aunque el 78,8 % de niños y adolescentes de 0 a 17 años leyeron o fueron expuestos a la lectura de libros impresos o digitales, solo un 15,3 % lo hizo con frecuencia diaria, mientras que la mayoría (63,5 %) leyó con menor regularidad. Además, un 21,2 % no tuvo contacto con la lectura en absoluto, lo que evidencia una baja intensidad en las prácticas lectoras dentro de este grupo etario.

<p align="center">
  <img src="https://imgur.com/667JbQo.jpg" alt="12171">
</p>
Nota. Adaptado de Encuesta Nacional de Lectura 2022. Informe de lectores y no lectores, por Ministerio de Cultura, 2022 (https://perulee.pe/sites/default/files/ENL%202022%20-%20Informe%20de%20lectores%20y%20no%20lectores.pdf)

Un estudio realizado en una institución educativa pública del distrito de El Agustino en 2022 reveló que el 72,2 % presenta un nivel bajo de comprensión lectora, el 25,9 % se encuentra en un nivel regular y solo el 1,9 % alcanza un nivel alto, lo que evidencia una preocupante deficiencia en esta habilidad (Torres–Vega, 2025).

<p align="center">
  <img src="https://imgur.com/R74IWKZ.jpg" alt="121712">
</p>
Nota. Adaptado de Comprensión lectora en estudiantes de secundaria en Perú, por Torres-Vega, 2025 (https://doi.org/10.33996/revistahorizontes.v9i36.909)

Una investigación realizada en la Institución Educativa San Jerónimo-Asillo, en Perú, analizó la relación entre el uso de TikTok y el rendimiento académico de estudiantes de quinto grado. Los resultados muestran que el 74.8 % de los alumnos se encuentra en un nivel de rendimiento regular y el 25.2 % en un nivel alto (Mamani et al., 2024). La mayoría de quienes usan TikTok con frecuencia tienden a ubicarse en el grupo de rendimiento regular, lo que sugiere una posible relación entre el uso de esta red social y un menor desempeño académico.

<p align="center">
  <img src="https://imgur.com/DY6cqya.jpg" alt="121713">
</p>
Nota. Adaptado de Efecto del uso de Tik Tok en el rendimiento académico de estudiantes de 5to grado, por Mamani et al, 2024 (https://doi.org/10.59659/revistatribunal.v4i9.71)

### 1.2.2. Lean UX Process

#### 1.2.2.2. Lean UX Assumptions

##### Features
* Algoritmos de recomendación de libros y autores.
* Comunidades de usuarios con inclinaciones literarias similares.
* Búsqueda avanzada
* Compra y venta de libros digitales y físicos
* Opciones de entrega flexibles según las necesidades del cliente
* Amplio catálogo de obras literarias

##### Business Outcomes
Incentivar la lectura: El principal objetivo de Livria es promover el hábito de la lectura en las personas, ya sea con fines educativos, de entretenimiento o como una alternativa de pasatiempo saludable. Nuestra startup promueve el acceso a material de lectura de todo tipo de manera rápida y sencilla, ofreciendo al lector diferentes opciones, filtros de búsqueda y recomendaciones personalizadas, facilitando el proceso de encontrar un libro que se ajuste a sus intereses. Además, Livria incorpora una sección de comunidad, donde los usuarios pueden interactuar con otros lectores, compartir reseñas, participar en foros temáticos y descubrir lecturas recomendadas por personas con gustos similares.

Generación de ingresos: Al habilitar la monetización a través del uso de la aplicación web y el modelo de negocio por suscripciones, nuestra startup podrá generar ganancias que pueden ser utilizadas para mejorar la calidad de nuestro servicio, expandir nuestra marca y ofrecer un catálogo más amplio de productos para nuestros usuarios. Estas mejoras garantizarán una mejor experiencia para los usuarios previos y captar nuevo público.

Livria generará ingresos principalmente mediante la venta de libros físicos y digitales a través de la aplicación web y móvil. Adicionalmente, se ofrece un plan de suscripción mensual para la comunidad. Esta combinación permite garantizar la sostenibilidad del negocio, mejorar continuamente la plataforma y ampliar el catálogo de productos y servicios para los usuarios.

Diferenciación en el mercado: La aplicación web y móvil de Livria permitirá que nuestra startup se destaque en el mercado gracias a funcionalidades únicas, como algoritmos de recomendación de libros y la sección de comunidad. Estas características crean una experiencia de lectura digital diferenciada que atrae a lectores interesados en descubrir, compartir y conectar con otros usuarios.

Formación de asociaciones comerciales: Las características únicas del servicio de Livria permitirán el establecimiento de alianzas estratégicas con negocios de rubros similares o relacionados al nuestro, tales como imprentas, distribuidoras y editoriales.

##### User Benefits
* Acceso a una amplia variedad de libros impresos y digitales desde una sola plataforma, permitiendo explorar y adquirir lecturas de forma rápida y sencilla.
* Recomendaciones personalizadas según intereses, facilitando la conexión con libros significativos y motivadores.
* Espacios de interacción y comunidad donde los usuarios pueden compartir opiniones, participar en clubes de lectura y descubrir nuevas obras a través de otros lectores.
* Experiencia accesible desde cualquier dispositivo, pensada para adolescentes, jóvenes y adultos que buscan flexibilidad y comodidad al leer.
* Fomento del hábito lector mediante notificaciones personalizadas.
* Ahorro de tiempo y esfuerzo en la búsqueda de libros adecuados, al centralizar en una sola plataforma la selección, compra y gestión de lecturas.

1. Creo que mis usuarios, dueños, administradores y entrenadores de gimnasios o centros de entrenamiento, desean una solución integral que les permita gestionar su operación de forma más organizada, eficiente y profesional, sin depender de hojas de cálculo, registros manuales o múltiples plataformas dispersas. Al mismo tiempo, sus clientes también buscan una experiencia más clara y accesible, donde puedan consultar horarios, reservar clases y dar seguimiento a sus entrenamientos desde un solo lugar.
2. Esto se puede resolver mediante FitManager, ya que centraliza todas las operaciones administrativas del gimnasio en una sola plataforma: control de pagos, programación de clases, gestión de membresías, historial de asistencia, métricas de rendimiento y más, todo desde un panel web accesible y fácil de usar.
3. Mis usuarios iniciales son dueños de gimnasios pequeños y medianos, estudios de entrenamiento personalizado y entrenadores independientes que gestionan su propio espacio y enfrentan desafíos en la administración diaria de sus negocios. Estos usuarios buscan una solución integral que les permita organizar mejor su operación, optimizar recursos y profesionalizar la experiencia de sus servicios, sin depender de hojas de cálculo, registros manuales o plataformas dispersas. A su vez, los usuarios finales de estos gimnasios, sus clientes, también son usuarios de FitManager, ya que acceden a la plataforma para consultar horarios, reservar clases y gestionar su experiencia de entrenamiento.
4. El valor #1 que un usuario quiere de FitManager es el control centralizado de sus operaciones, lo cual les permite ahorrar tiempo, reducir errores administrativos y enfocarse más en mejorar su servicio al cliente.
5. El usuario también puede obtener el beneficio adicional de escalar su negocio con mayor facilidad, gracias a funciones como el acceso multiusuario, la personalización de planes y el monitoreo de métricas clave para la toma de decisiones.
6. Voy a adquirir la mayoría de mis usuarios mediante estrategias de marketing digital dirigidas en redes sociales y contenido educativo en YouTube sobre gestión de gimnasios, además de posibles alianzas con distribuidores de equipos de entrenamiento y asociaciones deportivas locales.
7. Haré dinero a través de planes de suscripción mensual o anual para los gimnasios, segmentados por funcionalidades o cantidad de usuarios permitidos.
8. Mi competencia principal son otras plataformas de gestión que ofrecen soluciones de administración para centros fitness, pero a menudo están pensadas para mercados más grandes o tienen costos elevados.
9. Los venceremos al enfocarnos en gimnasios independientes y estudios más pequeños, ofreciendo un producto localmente adaptado, más accesible en precio, fácil de implementar y con una curva de aprendizaje mínima para el usuario.
10. Mi mayor riesgo de producto es que los usuarios perciban la plataforma como innecesaria o complicada, prefiriendo seguir usando métodos tradicionales como Excel, agendas físicas o WhatsApp para su gestión diaria.
11. Resolveremos esto mediante una experiencia de usuario simple e intuitiva, acompañada de un onboarding guiado, tutoriales claros, soporte técnico constante y una propuesta de valor que enfatiza el ahorro de tiempo y la profesionalización del negocio.
    
**¿Quién es el usuario?**  
El usuario principal de FitManager son los dueños y administradores de gimnasios independientes, estudios de entrenamiento personalizado y entrenadores que gestionan su propio espacio. También lo utilizan los entrenadores y el personal administrativo que participa en la operación diaria del gimnasio. Los clientes de los gimnasios también se benefician de la plataforma, ya que pueden consultar horarios, realizar reservas y gestionar sus entrenimientos.

**¿Dónde encaja nuestro producto, en su trabajo o en su vida?**  
FitManager se integra directamente en las labores diarias de gestión del gimnasio, permitiendo a los usuarios (dueños, administradores, entrenadores y personal administrativo) organizar clases, manejar pagos, controlar asistencia, segmentar entrenamientos y supervisar el rendimiento del negocio desde un solo lugar. Los clientes de los gimnasios lo utilizan para consultar horarios, hacer reservas y gestionar su experiencia de entrenamiento.

**¿Qué problemas tiene nuestro producto y cómo se puede resolver?**  
Los problemas potenciales del producto pueden incluir una curva de aprendizaje inicial, resistencia al cambio por parte del personal o falta de integración con ciertos sistemas de pago. Estos pueden resolverse mediante una interfaz intuitiva, tutoriales interactivos, soporte técnico constante y compatibilidad con múltiples métodos de pago y plataformas, asegurando también que los clientes de los gimnasios puedan navegar de manera fácil y rápida.

**¿Cuándo y cómo es usado nuestro producto?**  
FitManager se utiliza de forma diaria, tanto desde computadoras como desde dispositivos móviles, para gestionar la operación completa del gimnasio. Los dueños y administradores acceden al panel para revisar métricas y finanzas, mientras que entrenadores y personal administrativo lo usan para programar clases, controlar asistencias y organizar a los clientes.

**¿Qué características son importantes?**  
Las funciones más importantes incluyen: gestión centralizada de clientes y membresías, calendario dinámico con reservas, control automatizado de pagos y vencimientos, panel de métricas operativas, personalización de planes, y acceso multiusuario para distintos roles dentro del gimnasio. Los clientes del gimnasio también se beneficiarán de una visualización clara de horarios, opciones de reservas y su propio historial de entrenamientos.

**¿Cómo debe verse nuestro producto y cómo comportarse?**  
FitManager debe tener un diseño moderno, claro y profesional, con una interfaz amigable, adaptable a cualquier dispositivo y de navegación sencilla. Debe comportarse de forma fluida, sin tiempos de carga largos, con respuestas rápidas a las acciones del usuario y funcionalidades que simplifiquen, no compliquen, la gestión diaria del gimnasio, beneficiando tanto a los administradores como a los clientes del gimnasio.


#### 1.2.2.3. Lean UX Hypothesis Statements

Creemos que, al facilitar el acceso a libros en formato físico, digital (ebooks) y audiolibro en la aplicación de Livria, aumentaremos la constancia lectora de nuestros usuarios y mejoraremos el hábito de lectura en comunidades con baja frecuencia de lectura. Sabremos que hemos tenido éxito, cuando veamos un aumento del 60% en el número de usuarios que terminan de completar al menos un libro por mes en cualquier tipo de formato utilizado.

Creemos que, al ofrecer recomendaciones personalizadas basados en los gustos, hábitos de lectura e intereses de nuestros clientes, mejoraremos la experiencia del usuario y fomentaremos que descubran diversos libros nuevos con la finalidad de aumentar la retención y participación en la aplicación. Sabremos que hemos tenido éxito, cuando veamos que al menos un 80% de los usuarios interactúa con la sección de recomendaciones y registra libros sugeridos por la aplicación.

Creemos que, al diseñar una aplicación accesible y funcional en múltiples dispositivos para nuestros clientes, permitirá una adopción más inclusiva en el hábito de la lectura. Sabremos que hemos tenido éxito, cuando veamos que un 70% de los usuarios activos, que acceden a la aplicación desde diferentes plataformas, provienen de distintos contextos sociales y niveles educativos.

Creemos que, al integrar una sección de comunidad en Livria, donde los usuarios puedan interactuar, compartir recomendaciones, participar en foros literarios y formar redes con otros lectores, incrementaremos la motivación y el compromiso con la lectura, especialmente en personas que actualmente no leen con frecuencia o abandonan libros antes de terminarlos. Sabremos que hemos tenido éxito cuando observemos que al menos el 65% de los usuarios activos participan en alguna actividad de la comunidad (comentarios, reseñas, debates, grupos de lectura, etc.) y que el 50% de ellos reporta haber terminado más libros gracias al incentivo de estas interacciones sociales.

#### 1.2.2.3. Lean UX Canvas
<p align="center">
  <img src="https://imgur.com/e7jJez9.jpg" alt="12231">
</p>

<p align="center">
  <img src="https://imgur.com/u8fO3mz.jpg" alt="122312">
</p>

Link del Lean UX Canvas: https://docs.google.com/document/d/1J1PJ1gn62fnoB0Saa-rrgXwppnVQFzs8/edit?usp=sharing&ouid=112054289490328588638&rtpof=true&sd=true

## 1.3. Segmentos Objetivo
Con el objetivo de atraer eficazmente a futuros usuarios y brindar un producto que responda de manera precisa a sus necesidades, se han identificado los siguientes dos segmentos objetivo.

**Segmento objetivo #1: Personas que desean desarrollar y expandir el hábito de la lectura**  
Este segmento incluye tanto a personas que ya tienen afinidad por la lectura, como a aquellas que buscan incorporar este hábito en su vida diaria, con fines recreativos y educativos. Son individuos que desean encontrar plataformas digitales que faciliten el acceso a material variado, atractivo y adaptado a sus intereses. Este grupo busca principalmente plataformas de compra de libros que sean cómodas, intuitivas y que los ayuden a encontrar títulos en base a sus preferencias y objetivos de lectura.

**Aspectos demográficos:**
* Sexo: Masculino y femenino  
* Rango de edad: 16 a 64 años  
* Nivel socioeconómico: clases A, B y C (alta, media-alta y media), con acceso frecuente a dispositivos móviles e internet  

**Aspectos geográficos:**
* Nacionalidad: Global, no limitado a un país específico  
* Zona geográfica: Urbana  

**Aspectos psicográficos:**
* Intereses: Lectura contemporánea y clásica, exploración cultural, apreciación artística, entretenimiento y desarrollo personal a través de la lectura  
* Estilo de vida: Personas independientes o profesionales que valoran el crecimiento personal y buscan enriquecer su tiempo libre con actividades intelectuales y culturales. Utilizan servicios digitales para entretenimiento y consumo literario  
* Actitudes: Valoran la comodidad, la personalización y el acceso inmediato a contenido de calidad. Son curiosos, abiertos a nuevas experiencias literarias y disfrutan descubrir autores y tendencias  

Las estadísticas respaldan que este segmento constituye un público relevante: según la Encuesta Nacional de Lectura 2022, el 47,3 % de la población alfabeta de 18 a 64 años leyó libros en el último año, siendo la lectura más frecuente en mujeres (51,5 %) que en hombres (43,2 %) y concentrándose principalmente en áreas urbanas (50,3 % frente al 29,8 % en zonas rurales) (Ministerio de Cultura del Perú & Instituto Nacional de Estadística e Informática, 2023). Además, el 36,3 % de estos lectores prefirió libros de literatura, mientras que un 68,5 % eligió sus lecturas por el tema y un 23,3 % por recomendación de amigos o familiares, lo que muestra el interés en explorar nuevas obras y recibir orientación en sus elecciones de lectura. Estos datos evidencian que este grupo tiene motivación e interés en acceder a contenido literario, lo que lo convierte en un segmento estratégico para Livria.

**Segmento objetivo #2: Personas interesadas en compartir intereses literarios e interactuar con otros lectores**  
Este segmento incluye a jóvenes y adultos que buscan no solo leer, sino también intercambiar opiniones, descubrir nuevos títulos y conectarse con otros lectores mediante comunidades literarias, ya sean en línea o presenciales. Son personas motivadas por la socialización, el desarrollo personal y el aprendizaje continuo, que valoran espacios donde puedan discutir libros, recibir recomendaciones y participar en actividades grupales relacionadas con la lectura. Este grupo aprovecha plataformas digitales para conectar con otros lectores y formar parte de comunidades activas, fomentando así la constancia lectora y la interacción social en torno a la lectura.

**Aspectos demográficos:**
* Sexo: Masculino y femenino  
* Rango de edad: 16-40 años  
* Nivel socioeconómico: Clases A, B y C (alta, media-alta y media), con acceso a dispositivos móviles e internet.  

**Aspectos geográficos:**
* Nacionalidad: Global, no específico  
* Zona geográfica: Urbana  

**Aspectos psicográficos:**
* Intereses: Desarrollo personal, lectura digital, entretenimiento, educación y productividad  
* Estilo de vida: Jóvenes y adultos que utilizan plataformas digitales para informarse, aprender y entretenerse. Buscan mejorar sus hábitos, ampliar sus conocimientos y disfrutar de la lectura en entornos digitales  
* Actitudes: Motivados por el crecimiento personal, valoran la comodidad de acceder a información y contenido desde cualquier lugar, y están abiertos a probar nuevas herramientas digitales que faciliten su aprendizaje y fomenten su hábito lector  

Los Millennials y la Generación Z muestran un creciente interés en comunidades lectoras, participando en clubes de lectura presenciales y virtuales que fomentan la interacción social y el hábito lector (Allen, 2024). Plataformas como TikTok (#BookTok), Instagram y Facebook permiten a los jóvenes compartir reseñas y recomendaciones, creando redes que incentivan la lectura. Según Statista (2024), alrededor del 30 % de los jóvenes lectores descubren su club de lectura a través de redes sociales, evidenciando que la conexión digital es clave para este segmento, lo que lo convierte en un público estratégico para Livria.

# Capítulo II: Requirements Development and Software Solution Design

## 2.1. Competidores
En el sector de la venta y distribución de libros a través de dispositivos móviles, existen varias empresas que ofrecen aplicaciones móviles o versiones optimizadas para smartphones. Los principales competidores directos son:

* Crisol: Crisol cuenta con una aplicación móvil que complementa su red de librerías físicas y su portal web. A través de la app, los usuarios pueden explorar su variado catálogo de libros académicos, de ficción, infantiles y más. Su fortaleza principal radica en la accesibilidad al combinar experiencia digital y física, respaldada por grandes editoriales. No obstante, su aplicación móvil se percibe como una extensión de su web, con oportunidades de mejora en personalización, usabilidad y comunidad lectora.
* Ibero Librerías: Ibero ofrece su catálogo a través de su plataforma digital, principalmente orientada a estudiantes, docentes y profesionales. Aunque dispone de un sistema de compra en línea, su presencia en aplicaciones móviles es limitada, lo que restringe la experiencia de los usuarios que buscan inmediatez en dispositivos móviles. Su fortaleza está en los títulos especializados, pero carece de funcionalidades móviles como recomendaciones personalizadas, interacción social o accesibilidad mejorada.
* Communitas: Communitas es una librería independiente que apuesta por una experiencia cercana y personalizada con la comunidad lectora. Su enfoque principal está en la curaduría de títulos y la promoción cultural. Si bien dispone de venta en línea, su presencia en aplicaciones móviles es reducida, lo que limita la experiencia de interacción digital desde un smartphone. Esto abre un espacio para apps que combinen curaduría, personalización y comunidad lectora en un formato más interactivo y móvil-friendly.

## 2.1.1. Análisis Competitivo

¿Por qué realizar este análisis?  
Este análisis es clave porque nos brinda una visión clara del panorama competitivo en el ecosistema móvil. Permite detectar oportunidades de diferenciación a partir de la experiencia en aplicaciones móviles, así como identificar fortalezas y debilidades en cuanto a usabilidad, accesibilidad y valor agregado en dispositivos móviles. Nos ayuda a reconocer en qué aspectos podemos superar a la competencia y ofrecer una experiencia única, fluida y adaptada al usuario móvil.

| Aspecto | **Livria** | **Crisol** | **Ibero Librerías** | **Communitas** |
|---------|------------|------------|----------------------|----------------|
| **Logo** | <div align="center"><img src="https://imgur.com/8Y0vIkI.jpg" height="100"/></div> | <div align="center"><img src="https://imgur.com/cp7XfPx.jpg" height="100"/></div> | <div align="center"><img src="https://imgur.com/U7qSPil.jpg" height="100"/></div> | <div align="center"><img src="https://imgur.com/zAP7Dvf.jpg" height="100"/></div> |
| **Overview** | Livria es una librería especializada emergente cuyo enfoque principal es brindar accesibilidad a diversos materiales de lectura para sus clientes, facilitando la búsqueda de obras de entretenimiento o educativas que se ajusten a los gustos e intereses del cliente. | Crisol es una de las cadenas de librerías más grandes y conocidas de Perú, se destaca por su amplia oferta de obras artísticas y educativas, además de su compromiso con la cultura y calidad. Cuenta con locales en puntos estratégicos del país. | Ibero Librerías es una cadena de librerías muy popularizada en Perú, resalta por su especialización en ejemplares educativos, culturales y de ciencias sociales, con una selección variada de editoriales y autores emergentes. | Communitas es una librería cuyo enfoque se centra en libros que tratan temas complejos, filosóficos y modernos. Se destaca por ofrecer a sus clientes una experiencia más profunda y centrada en el pensamiento crítico, mediante un repertorio que invita al lector a reflexionar. |
| **Ventaja competitiva** | Combina un enfoque centrado en el cliente con herramientas de búsqueda rápidas y personalizadas, además de espacios de interacción que permiten a los usuarios compartir intereses y conectar con otros lectores. | Posee un amplio inventario de obras de todos los géneros y cuenta con locales ubicados en puntos estratégicos del Perú, lo que amplía tanto el catálogo de productos a ofrecer como su accesibilidad. | Ofrece un amplio repertorio de obras educativas y culturales menos comerciales y más exigentes, proyectando una imagen de marca más especializada en comparación con otras cadenas. | Presenta una curaduría enfocada en títulos que invitan al lector a la reflexión y el aprendizaje, apostando por una selección cuidadosa de títulos, priorizando la calidad sobre la rotación comercial. |
| **Mercado objetivo** | Jóvenes y adultos jóvenes que busquen empezar el hábito de la lectura y buscan comodidad, personalización y conexión social. | Personas de todas las edades interesadas en novelas y obras educativas o de entretenimiento. Lectores casuales y escolares. | Jóvenes y adultos de todas las edades interesados en obras educativas o culturales, lectores frecuentes y profesionales. | Jóvenes y adultos jóvenes interesados en obras ideológicas y literatura alternativa, lectores críticos. |
| **Estrategias de marketing** | Descuentos semanales, publicidad digital, marketing de temporada. | Descuentos frecuentes, marketing de temporada, publicidad digital, fuerte presencia en tiendas físicas. | Publicidad digital, presencia cuidada y refinada, eventos y presentaciones. | Eventos culturales, fuerte presencia en la comunidad lectora, colaboraciones con artistas y autores. |
| **Productos y servicios** | Libros físicos y digitales, suscripción (Community Plan), comunidades, publicaciones y reseñas. | Libros digitales y físicos, merchandising. | Libros físicos. | Libros físicos. |
| **Precios y costos** | Descuentos semanales y de temporada. <br> Promedio: S/. 30 – 90 <br> Suscripción: S/. 39.90 | Descuentos frecuentes y de temporada. <br> Promedio: S/. 40 – 200 <br> No cuenta con servicio de suscripción | Descuentos regulares y de temporada. <br> Promedio: S/. 40 – 130 <br> No cuenta con servicio de suscripción | Descuentos regulares. <br> Promedio: S/. 50 – 140 <br> No cuenta con servicio de suscripción |
| **Canales de distribución** | Entrega a domicilio, compra en local, venta digital (app web y móvil). | Entrega a domicilio, compra en local (app web y móvil). | Entrega a domicilio, compra en local (web responsive). | Entrega a domicilio, compra en local (web básica). |
| **Fortalezas** | - Amplia cobertura a través de envíos a domicilio.<br>- Gran variedad de obras, tanto literarias como educativas.<br>- Imagen moderna y amigable.<br>- Orientación centrada en el cliente. | - Amplia cobertura local (tiendas físicas y envíos).<br>- Gran variedad de obras.<br>- Popularidad y marca establecida.<br>- Veinte años de experiencia en el mercado. | - Curaduría especializada en títulos educativos y culturales.<br>- Imagen profesional y cercana.<br>- Fidelización del público objetivo.<br>- Treinta años de experiencia en el mercado. | - Curaduría selectiva y refinada.<br>- Imagen de marca fuerte.<br>- Comunidad establecida.<br>- Diez años de experiencia. |
| **Oportunidades** | - Captar lectores iniciantes con diseño orientado al usuario.<br>- Fidelizar con funciones únicas y exclusivas de la app. | - Posibilidad de expansión internacional.<br>- Convenios estratégicos con editoriales emergentes. | - Alianzas con centros educativos.<br>- Expansión al entorno digital con libros electrónicos. | - Expansión de marca en eventos o como agencia artística.<br>- Expansión al entorno digital con libros electrónicos. |
| **Debilidades** | - Escala pequeña para incursión en el mercado.<br>- Imagen de marca aún no establecida.<br>- Dificultad para competir frente a cadenas consolidadas. | - Enfoque demasiado amplio en catálogo (riesgo de falta de títulos específicos). | - Falta de venta de libros digitales (dependencia de lo físico). | - Nicho pequeño y especializado, poco escalable comercialmente. |
| **Amenazas** | - Competencia de grandes cadenas con más capital.<br>- Riesgo de acaparamiento del mercado. | - Aparición de un competidor con mayor alcance y precios más accesibles. | - Competidores similares con más locales o venta digital. | - Acaparamiento de su nicho por marcas grandes con más presupuesto. |

### 2.1.2. Estrategias y tácticas frente a competidores

***Estrategias de diferenciación de producto***

**#1 Implementación de funcionalidad de comunidad:**
* Fortaleza utilizada: Orientación en torno al cliente
* Oportunidad aprovechada: Posibilidad de fidelizar lectores
* Descripción: El apartado de comunidad nos permitirá captar y mantener la atención de grupos de lectores con intereses en común, ya que les ofrecerá un espacio en el que puedan compartir sus opiniones y gustos de una manera amigable. Esta funcionalidad también aportará más valor a la suscripción de cada usuario, ofreciendo acceso a aspectos exclusivos que pueden llamar la atención del cliente.

**#2 Implementación de funcionalidad de recomendaciones:**
* Fortaleza utilizada: Orientación en torno al cliente
* Oportunidad aprovechada: Posibilidad de captar al segmento de lectores iniciantes.
* Descripción: La innovadora función de recomendaciones personalizadas nos permitirá acatar las necesidades de este tipo de clientes de una manera más efectiva, ya que toda persona que quiera empezar a formar el hábito de la lectura podrá utilizar este apartado de nuestro servicio para encontrar obras que estén alineadas con sus intereses y necesidades de una manera mucho más rápida, permitiéndoles adquirir un título de su interés dentro de nuestra misma aplicación.

***Estrategias de expansión de mercado***

**#1 Implementación de productos digitales**
* Debilidad/amenaza aprovechada: Falta de venta de productos digitales en otras librerías y el riesgo de que competidores con mayor oferta tecnológica atraigan a su público.
* Fortaleza utilizada: Imagen moderna y amigable.
* Oportunidad aprovechada: Posibilidad de captar al segmento de lectores iniciantes.
Descripción: Incorporar en Livria un catálogo de e-books y audiolibros permitirá atender a los lectores que buscan comodidad y formatos digitales, segmento actualmente desatendido por competidores tradicionales. Esto no solo diferencia nuestra oferta, sino que también posiciona a Livria como una plataforma innovadora que se adapta a las tendencias de consumo literario en un mercado cada vez más digitalizado.

**#2 Alianzas con editoriales nacionales:**
* Fortaleza utilizada: Gran variedad de obras
* Oportunidad aprovechada: Posibilidad de fidelizar lectores
* Descripción: Establecer alianzas estratégicas con editoriales emergentes resultaría en una gran expansión al catálogo de obras que ofrecemos y la posibilidad de comercializar obras a precios mucho más competitivos, aumentando los beneficios de nuestros clientes y suscriptores.

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas

Las entrevistas se adaptan a cada segmento con el fin de obtener información relevante para comprender sus necesidades y expectativas. Para iniciar, se plantean preguntas generales que permiten recoger datos demográficos básicos y sentar las bases para la construcción de arquetipos.

**Preguntas generales:**

* ¿Cuál es tu nombre?
* ¿Cuántos años tienes?
* ¿Cuál es tu distrito de residencia?
* ¿Cuál es tu estado civil?
* ¿A qué te dedicas?

***Segmento Objetivo #1: Personas que desean desarrollar y expandir el hábito de la lectura***

**Preguntas principales**

* ¿Con qué frecuencia lees actualmente y qué tipo de libros sueles preferir?
* ¿Qué factores influyen más en tu elección de libros (tema, autor, recomendaciones, reseñas, precio)?
* ¿Qué tan cómodo/a te resulta acceder a libros en formato físico versus digital?
* ¿Qué obstáculos encuentras actualmente para mantener o ampliar tu hábito de lectura?
* ¿Qué características valoras más en una plataforma digital de compra o lectura de libros?

**Preguntas complementarias**

* ¿Qué dispositivos usas más frecuentemente para leer (celular, tablet, laptop, lector digital)?
* ¿Cuánto influyen tus amigos, familiares o redes sociales en tu elección de lecturas?
* ¿Qué esperas de una experiencia digital de lectura (comodidad, personalización, rapidez, variedad)?
* ¿Has usado antes plataformas digitales de lectura? Si es así, ¿qué te gustó y qué no?

***Segmento objetivo #2: Personas interesadas en compartir intereses literarios e interactuar con otros lectores***

**Preguntas principales**

* ¿Qué tan importante es para ti compartir tus lecturas u opiniones con otros?
* ¿Participas en comunidades o clubes de lectura, ya sean físicos o virtuales? Si es así, ¿cómo es tu experiencia?
* ¿Qué plataformas digitales utilizas para descubrir libros o compartir reseñas (ej. TikTok, Instagram, Goodreads)?
* ¿Qué valor agregado te motiva a unirte a una comunidad lectora (descubrir títulos, interacción social, aprendizaje)?
* ¿Qué características debería tener una aplicación o plataforma para motivarte a interactuar con otros lectores?

**Preguntas complementarias**

* ¿Prefieres las recomendaciones de personas cercanas, de comunidades online o de algoritmos automatizados?
* ¿Qué te desmotiva o frustra en las comunidades literarias en las que has participado?
* ¿Qué tan importante es para ti que una plataforma combine lectura con interacción social?
* ¿Has comprado libros o decidido lecturas por sugerencia de un club o comunidad online?

### 2.2.2. Registro de entrevistas

***Segmento #1: Personas que desean desarrollar y expandir el hábito de la lectura***

**Entrevistado N.º 1: Valentina Binda**

* Edad: 18
* Distrito: Surquillo
* Estado civil: Soltero
* Ocupación: Estudiante

Acerca de la entrevista:

<p align="center">
  <img src="https://imgur.com/QN0La0c.jpg" alt="12231">
</p>

* Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/EWZiS1n_89FKgISqOVCjVmUB9Kn699X3OkaJF1K_yNxkpQ?e=6ctcJp
* Instante en el que inicia: 0:01
* Duración: 3:09

Valentina, una estudiante de 18 años, soltera y residente en el distrito de Surquillo, se identifica como una lectora motivada por la conexión emocional. Actualmente, lee con poca frecuencia, principalmente por falta de tiempo.

Su género favorito es el terror, ya que le gustan los libros que la mantienen "enganchada", con una trama que la sumerge por completo. A la hora de elegir sus lecturas, se deja influir por las reseñas y el autor, lo que demuestra que valora las opiniones de otros lectores y la trayectoria del escritor.

Valentina se siente más cómoda con los libros físicos, pues considera que los formatos digitales son difíciles de conseguir. A pesar de esto, si tuviera que leer en un dispositivo, usaría su tablet o su computadora.

El principal obstáculo que encuentra es la falta de tiempo, ya que sus responsabilidades académicas y personales le restan horas de lectura. Su experiencia con plataformas de lectura es limitada, habiendo utilizado solo una en el pasado, pero valora que estas ofrezcan una amplia variedad de títulos y una experiencia de lectura fluida.

***Segmento #1: Personas que desean desarrollar y expandir el hábito de la lectura***

**Entrevistado N.º 2: Emmanuel Andrades**

* Edad: 16
* Distrito: Miraflores
* Estado civil: Soltero
* Ocupación: Estudiante

Acerca de la entrevista:

<p align="center">
  <img src="https://imgur.com/ow2WB78.jpg" alt="12231">
</p>

* Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/EWZiS1n_89FKgISqOVCjVmUB9Kn699X3OkaJF1K_yNxkpQ?e=6ctcJp
* Instante en el que inicia: 3:09
* Duración: 3:01

Emmanuel, un estudiante de 20 años que reside en el distrito de Miraflores, se define como soltero y con un perfil de lector selectivo y enfocado en el entretenimiento. Su hábito de lectura es esporádico, impulsado principalmente por recomendaciones directas de su círculo de amigos, quienes son lectores ávidos.  

El género que más le atrae es el de terror, buscando una conexión con la trama y la intriga que lo mantenga enganchado. Para él, el factor más influyente en la elección de un libro no es el autor ni las reseñas, sino el tema en sí y las recomendaciones de sus allegados.  

En cuanto a formatos y tecnología, Emmanuel prefiere la lectura digital porque le resulta más cómoda y accesible. Considera que las plataformas digitales agilizan la búsqueda y el proceso de compra, en contraste con la experiencia de buscar un libro físico. Su principal dispositivo de lectura es una tablet, ya que la considera más cómoda que un celular o una laptop.  

A pesar de su preferencia por lo digital, su experiencia con plataformas de lectura es limitada, habiendo usado solo una cuando era niño. Valora en una plataforma la rapidez y la amplia variedad de títulos disponibles. A diferencia de otros lectores, Emmanuel no encuentra grandes obstáculos para mantener su hábito de lectura, más allá de la falta de tiempo. La mayor parte de su tiempo libre está dedicado a sus estudios, lo cual deja menos espacio para la lectura.

**Entrevistado N.º 3: Jorge Binda**

* Edad: 49
* Distrito: Surquillo
* Estado civil: Divorciado
* Ocupación: Ingeniero de sistemas

Acerca de la entrevista:

<p align="center">
  <img src="https://imgur.com/pFD4v3B.jpg" alt="12231">
</p>

* Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/EWZiS1n_89FKgISqOVCjVmUB9Kn699X3OkaJF1K_yNxkpQ?e=6ctcJp
* Instante en el que inicia: 6:11
* Duración: 3:48

Jorge, un trabajador de 49 años, divorciado y residente en el distrito de Surquillo, es un lector con perfil dual. Por un lado, tiene un interés práctico por el aprendizaje y el desarrollo personal. Por otro lado, disfruta del entretenimiento, especialmente con libros de terror, ya que le permiten desconectarse y sumergirse en una historia.  

Su hábito de lectura es actualmente esporádico, leyendo un libro cada dos meses, a diferencia de su juventud, cuando lo hacía con mayor frecuencia. A la hora de elegir sus lecturas, se deja influir por dos factores principales: el autor y las reseñas de otros lectores, lo que sugiere que valora tanto la reputación del escritor como la validación social de la obra.  

Respecto a los formatos, Jorge se siente cómodo con los libros físicos y los digitales, pero tiene una clara preferencia por los físicos, ya que le permiten una lectura más enfocada y libre de distracciones. Considera que al leer en su celular, su dispositivo habitual, las notificaciones y el acceso a otras aplicaciones lo convierten en una actividad más superficial.  

El principal obstáculo que encuentra es la falta de tiempo, ya que sus responsabilidades laborales y personales reducen su disponibilidad para leer. Su única experiencia con plataformas digitales es a través de Spotify, donde escucha audiolibros. Le ha gustado esta experiencia porque le permite realizar otras actividades, como sus quehaceres o sus trayectos, mientras se concentra en el contenido del libro.

**Entrevistado N.º 4: Juan Fukusaki**

* Edad: 21 años
* Distrito de residencia: Pueblo Libre
* Estado civil: Soltero
* Ocupación: Cocinero

Acerca de la entrevista:

<p align="center">
  <img src="https://imgur.com/tz9ujx5.jpg" alt="12231">
</p>


* Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/EWZiS1n_89FKgISqOVCjVmUB9Kn699X3OkaJF1K_yNxkpQ?e=6ctcJp
* Instante en el que inicia: 10:00
* Duración: 4:55

Juan Fukusaki, un joven cocinero de 21 años, presenta un perfil de lector con motivaciones duales. Por un lado, su interés es pragmático y profesional, evidente en su preferencia por libros de cocina que le ayudan a perfeccionar su oficio. Por otro, mantiene un interés por el entretenimiento y la evasión, disfrutando de la fantasía y la aventura medieval en su tiempo libre.  
Su hábito de lectura es actualmente esporádico, un cambio drástico en comparación con su etapa escolar y el inicio de la pandemia. El principal obstáculo que enfrenta es la falta de tiempo, ya que su trabajo le exige mucho y el cansancio lo lleva a preferir ver series de televisión, una actividad que ha reemplazado la lectura nocturna.  

En cuanto a la elección de sus lecturas, Juan no se deja llevar por el autor ni por las reseñas en línea. Su decisión se basa principalmente en el tema del libro y, de manera crucial, en las recomendaciones personales de su círculo de amigos. Esto sugiere que confía más en la validación social directa que en la opinión de extraños.  

Respecto a la tecnología y los formatos, Juan se siente cómodo con los libros físicos, ya que vive cerca de librerías. Su experiencia con plataformas digitales es limitada, habiendo utilizado una sola vez una aplicación de lectura. A pesar de su inexperiencia, tiene expectativas claras: valora que una plataforma sea fácil de usar y que cuente con una gran variedad de títulos, incluyendo temas específicos como la gastronomía. La principal frustración que encontró en su única experiencia digital fue, precisamente, la falta de oferta en el nicho que le interesaba en ese momento. Los dispositivos que utiliza para consumir contenido son su celular cuando está fuera de casa y su laptop en un entorno más relajado.


***Segmento objetivo #2: Lectores casuales y aficionados a la lectura***


**Entrevistado N.º 1: Roxana Arbañil**

* Edad: 50
* Distrito: Surquillo
* Estado civil: Divorciada
* Ocupación: Asistente de desarrollo organizacional en la subgerencia de gestión humana del Perú

Acerca de la entrevista:

<p align="center">
  <img src="https://imgur.com/gCau8K5.jpg" alt="12231">
</p>

* Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/EWZiS1n_89FKgISqOVCjVmUB9Kn699X3OkaJF1K_yNxkpQ?e=6ctcJp
* Instante en el que inicia: 14:55
* Duración: 4:23

Roxana Katty Arbañil, de 50 años, divorciada y residente en el distrito de Surquillo, es una lectora que valora profundamente la interacción social en torno a la lectura. Para ella, compartir opiniones y recomendaciones con otros lectores es fundamental, ya que enriquece su experiencia y le permite descubrir nuevas historias y perspectivas.  

Ella es una participante activa en comunidades virtuales con un grupo de amigos, donde intercambian ideas y se pasan libros. También utiliza Instagram para seguir comunidades literarias y booktubers que le ayudan a descubrir nuevos títulos y a mantenerse al tanto de las tendencias literarias. Las recomendaciones de personas cercanas y de las comunidades online son sus principales fuentes de inspiración.  
Roxana valora que una comunidad lectora le permita aprender y la mantenga motivada. El simple hecho de tener un grupo con el cual comentar lo que lee la impulsa a leer más. Para ella, una plataforma ideal debe ser amigable, práctica y fácil de usar, con funciones que le permitan compartir sus opiniones y recibir recomendaciones de manera sencilla.  

Aunque se siente cómoda con las herramientas digitales, ha experimentado frustración en algunas comunidades online donde se comparten opiniones de manera superficial o sin profundizar en el contenido. Considera que la calidad de la conversación es crucial. La posibilidad de comprar libros o decidir sus próximas lecturas por sugerencia de una comunidad es un valor agregado importante para ella, ya que le ahorra tiempo y le asegura que la recomendación proviene de un grupo con intereses similares.

**Entrevistado N.º 2: Sofia Pimentel**

* Edad: 16
* Distrito: Magdalena del Mar
* Estado civil: Soltera
* Ocupación: Estudiante

Acerca de la entrevista:

<p align="center">
  <img src="https://imgur.com/drReFnp.jpg" alt="12231">
</p>

* Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/EWZiS1n_89FKgISqOVCjVmUB9Kn699X3OkaJF1K_yNxkpQ?e=6ctcJp
* Instante en el que inicia: 19:18
* Duración: 3:08

Sofía Pimentel, una estudiante de 16 años, soltera y residente en el distrito de Magdalena del Mar, es una lectora social para quien el acto de leer no es una actividad solitaria. Para ella, es muy importante compartir sus lecturas y opiniones con otros, ya que esto le permite conectarse con personas que tienen intereses similares.  
Sofía participa en comunidades de lectura, lo que la motiva a leer más y a conocer personas con gustos parecidos a los suyos. Para ella, es fundamental poder escuchar diferentes puntos de vista para entender en profundidad lo que lee.  

La principal motivación de Sofía para unirse a una comunidad de lectura es la interacción social. En su experiencia, valora que estas comunidades sean abiertas y le permitan expresarse libremente. Por otro lado, le desmotiva cuando las comunidades se vuelven cerradas y no permiten que los miembros compartan sus opiniones.  

Para Sofía, la plataforma ideal debe ser fácil de usar, rápida y, sobre todo, debe tener un espacio dedicado para recomendar libros y permitir la interacción entre lectores. Ella prefiere las recomendaciones de personas cercanas o de comunidades online con las que se identifica, ya que le generan mayor confianza.

**Entrevistado N.º 3: Nicole Azaña**

* Edad: 24
* Distrito: Ate
* Estado civil: Soltera
* Ocupación: Estudiante

Acerca de la entrevista:

<p align="center">
  <img src="https://imgur.com/Vfa4w8u.jpg" alt="12231">
</p>

* Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/EWZiS1n_89FKgISqOVCjVmUB9Kn699X3OkaJF1K_yNxkpQ?e=6ctcJp
* Instante en el que inicia: 22:27
* Duración: 4:58

Nicole Azaña, de 24 años, soltera y residente en el distrito de Ate, es una lectora que valora el intercambio de opiniones. Para ella, compartir sus lecturas y reseñas con otros es muy importante, ya que le permite conocer diferentes puntos de vista.  

Nicole participa en comunidades virtuales, específicamente en grupos de Facebook, donde ha descubierto libros interesantes y se guía por las reseñas que otros usuarios le dan. También utiliza Wattpad y la aplicación de libros de Apple para leer, además de la plataforma digital de su universidad, que le otorga acceso a una gran variedad de títulos.  

Su motivación principal para unirse a estas comunidades es la interacción social y el aprendizaje. Para ella es fundamental la conectividad y la calidad de los comentarios en una plataforma ideal de una librería con comunidades. 
Prefiere las recomendaciones de personas cercanas ya que tiene confianza en sus opiniones. Le gusta saber las opiniones de todos para entender mejor lo que lee.  

Su principal frustración con las comunidades online es cuando la conversación es superficial y no profundiza en la discusión del libro. Para ella, una plataforma ideal debería ser amigable, práctica y fácil de usar, combinando lectura con interacción social de forma fluida.

**Entrevistado N.º 4: Fabrizzio Gionti**

* Edad: 21 años
* Distrito de residencia: Callao
* Estado civil: Soltero
* Ocupación: Estudiante

Acerca de la entrevista:

<p align="center">
  <img src="https://imgur.com/RSSwukT.jpg" alt="12231">
</p>

* Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/EWZiS1n_89FKgISqOVCjVmUB9Kn699X3OkaJF1K_yNxkpQ?e=6ctcJp
* Instante en el que inicia: 27:26
* Duración: 5:06

Fabricio Yonti, un estudiante de 21 años del Callao, se presenta como un lector para quien compartir es un pilar fundamental de su experiencia. Para él, compartir sus lecturas no solo es un gusto personal, sino también una forma de motivar a otros a leer y de crear un espacio para conversar sobre intereses comunes.  

A pesar de no haber participado en comunidades formales de lectura, su experiencia en el colegio con un club de lectores, donde se intercambiaban libros y se discutían las lecturas del año, le dejó una impresión muy positiva. Su principal motivación para unirse a una comunidad es la interacción social y el valor de compartir conocimientos.  

Respecto a la tecnología, Fabricio no utiliza plataformas específicas para reseñas o comunidades literarias. En cambio, su proceso de descubrimiento de libros se inicia en Google, donde busca títulos de su interés y explora diversos enlaces para obtener información. Aunque no usa estas plataformas, su preferencia para obtener recomendaciones es clara: prefiere la opinión de comunidades online antes que las de personas cercanas o algoritmos automatizados, lo que demuestra su apertura a interactuar con desconocidos con intereses similares.  

Una plataforma ideal para Fabricio debería tener un buscador inteligente capaz de recomendarle libros basados en sus intereses, evitando el spam o la publicidad excesiva de títulos que no le interesan, un aspecto que le resulta frustrante. Valora que una plataforma combine la lectura con la interacción social, ya que considera que esta combinación amplía su conocimiento de forma significativa. Finalmente, revela que sí ha comprado libros basándose en las sugerencias de una comunidad en línea, específicamente un grupo en Discord, lo que refuerza su confianza en las recomendaciones de este tipo de espacios virtuales.

## 2.2.3. Análisis de entrevistas

En base en las entrevistas recopiladas para cada segmento, se llevó a cabo un análisis, el cual destaca los principales hallazgos y las conclusiones derivadas.

***Segmento objetivo #1: Personas que desean desarrollar y expandir el hábito de la lectura***

**Hallazgos:**

| Característica           | Hallazgos                                                                      | Porcentaje |
|--------------------------|---------------------------------------------------------------------------------|------------|
| Hábito de Lectura        | Es esporádico o poco frecuente, a diferencia de su etapa escolar o juventud.   | 100%       |
| Obstáculo Principal      | La falta de tiempo debido a responsabilidades académicas y laborales.           | 100%       |
| Motivación               | La búsqueda de entretenimiento, para "engancharse" en una historia.            | 100%       |
| Género Preferido         | El terror es el género más popular.                                            | 75%        |
| Intereses Adicionales    | Lectura con fines profesionales o de desarrollo personal                        | 50%        |
| Factores de Elección     | Basan su decisión en recomendaciones o reseñas.                                 | 100%       |
| Influencia de Amigos     | Confían en las recomendaciones de su círculo cercano.                           | 50%        |
| Influencia de Reseñas    | Se guían por la reputación del autor y las reseñas en línea.                    | 50%        |
| Preferencia de Formato   | Prefieren los libros físicos por la experiencia táctil y la ausencia de distracciones. | 75%        |
| Experiencia Digital      | Tienen una experiencia limitada o nula con plataformas digitales.               | 100%       |
| Expectativas Digitales   | Valoran que las plataformas ofrezcan una amplia variedad de títulos.            | 100%       |

**Conclusiones:**

Los lectores de este segmento integran la lectura en su vida de forma esporádica para satisfacer una necesidad específica, ya sea de entretenimiento o de aprendizaje. El obstáculo principal para ellos es la falta de tiempo, lo que los lleva a buscar soluciones convenientes y eficientes. Aunque algunos prefieren los libros físicos, no se oponen a lo digital, valorando la practicidad de los audiolibros o la accesibilidad que ofrecen las plataformas digitales cuando la experiencia es cómoda.

Para que una aplicación como Livria sea atractiva para este segmento, debe enfocarse en ofrecer una experiencia sin fricciones. Es crucial que la plataforma facilite la búsqueda y el descubrimiento de libros con un sistema de recomendaciones robusto, que no solo sugiera títulos populares, sino que también tenga una gran variedad en nichos específicos, como la gastronomía o el marketing. Además, es fundamental que la interfaz sea intuitiva y fácil de usar, ya que muchos tienen una experiencia limitada o nula con plataformas digitales.

***Segmento objetivo #2: Personas interesadas en compartir intereses literarios e interactuar con otros lectores***

**Hallazgos:**

| Característica               | Hallazgos                                                                                                                                                                                                                                    | Porcentaje   |
|-----------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| Importancia de Compartir    | Compartir opiniones y lecturas es fundamental. Lo ven como una forma de enriquecer su experiencia y conocer nuevos puntos de vista.                                                                                                           | 100%         |
| Participación en Comunidades| Participan activamente en comunidades de lectura, ya sea en grupos de amigos, Facebook, Instagram o Discord.                                                                                                                                  | 100%         |
| Uso de Plataformas Digitales| El 75% (Roxana, Sofía y Nicole) utiliza plataformas como Instagram, TikTok y Facebook para descubrir libros y conectar. El otro 25% utiliza Google y Discord (Fabricio).                                                                     | 75% - 25%    |
| Valor Agregado              | La principal motivación para unirse a una comunidad es la interacción social.                                                                                                                                                                 | 100%         |
| Punto de Dolor              | La principal frustración es la falta de calidad en la conversación o cuando las comunidades son cerradas y no permiten la libre expresión de ideas.                                                                                           | 100%         |
| Preferencia de Recomendaciones | Todos prefieren las recomendaciones de personas cercanas o de comunidades online con las que se sienten identificados, ya que les genera confianza.                                                                                       | 100%         |
| Plataforma Ideal            | Una plataforma ideal debe ser amigable, práctica, fácil de usar y rápida. Roxana, Sofía y Nicole también destacan la importancia de un espacio para recomendar libros y una interacción de calidad.                                           | 100%         |
| Obstáculo Principal         | La falta de tiempo debido a responsabilidades, mencionada por el 50% de los entrevistados (Roxana y Sofía), limita su frecuencia de lectura.                                                                                                  | 50%          |

**Conclusiones:**

Los entrevistados de este segmento se definen como "Lectores Sociales", que ven la lectura como una actividad compartida. Su principal motor no es simplemente la lectura, sino la experiencia de compartir y conectar que esta genera. Para ellos, el acto de leer no es una actividad solitaria, sino una oportunidad para debatir, aprender y conocer a personas con intereses similares.

Las plataformas digitales tienen un gran potencial para este segmento si logran crear un ecosistema social robusto y de calidad. Los hallazgos muestran que una solución exitosa debe priorizar la interacción genuina y profunda, ofreciendo un diseño que facilite la conversación y la conexión entre usuarios. El éxito no se medirá solo por el catálogo de libros, sino por la calidad de la comunidad y la fluidez de la experiencia social que ofrezca.

## 2.3. Needfinding

### 2.3.1. User Personas

En esta sección, se presentan las fichas de User Persona, un artefacto clave para visualizar y comprender a nuestros usuarios a un nivel más profundo. Su elaboración se basa en el análisis de las entrevistas realizadas a los dos segmentos de lectores identificados. Se han tomado en cuenta características esenciales como la falta de tiempo para leer, la importancia de las recomendaciones de personas cercanas, la preferencia por formatos digitales o audiolibros que ofrecen conveniencia, y la búsqueda de una experiencia fluida y sin distracciones. Estos perfiles nos permiten humanizar los datos recolectados y guiarán el diseño de Livria para asegurar que sus funcionalidades resuelvan las necesidades y puntos de dolor de sus futuros usuarios de manera efectiva.

***Segmento objetivo #1: Personas que desean desarrollar y expandir el hábito de la lectura***

<p align="center">
  <img src="https://imgur.com/OiQmVr3.jpg" alt="12231">
</p>

***Segmento objetivo #2: Personas interesadas en compartir intereses literarios e interactuar con otros lectores***

<p align="center">
  <img src="https://imgur.com/4fsp9KP.jpg" alt="12231">
</p>

### 2.3.2. User Task Matrix

| Tarea                                                     | Yoel Ramírez |              | Lucia Carnero |              |
|-----------------------------------------------------------|--------------|--------------|---------------|--------------|
|                                                           | Frecuencia   | Importancia  | Frecuencia    | Importancia  |
| Buscar libros para estudio o interés personal             | Con frecuencia | Alta        | Con frecuencia | Alta         |
| Usar el algoritmo de recomendación                        | Con frecuencia | Alta        | A veces        | Media        |
| Unirse a comunidades con intereses similares              | A veces        | Media       | Con frecuencia | Alta         |
| Leer libros en formato digital                            | Con frecuencia | Alta        | Con frecuencia | Alta         |
| Guardar libros o marcar como “pendientes”                 | A veces        | Media       | Con frecuencia | Media        |
| Buscar comunidades                                        | A veces        | Baja        | Con frecuencia | Alta         |
| Compartir publicaciones en las comunidades                | Rara vez       | Baja        | Con frecuencia | Alta         |
| Comentar las publicaciones                                | Rara vez       | Baja        | Con frecuencia | Alta         |
| Pedir libros con envío rápido                             | A veces        | Media       | A veces        | Alta         |
| Publicar y consultar reseñas de libros                    | Con frecuencia | Media       | Con frecuencia | Alta         |
| Realizar búsquedas de libros con filtros                  | Con frecuencia | Alta        | Con frecuencia | Media        |
| Asignar libros como favoritos                              | Con frecuencia | Media       | Con frecuencia | Alta         |

### 2.3.3. User Journey Mapping

En esta sección se presentan los User Journey Maps, diseñados para visualizar y comprender el recorrido de nuestros usuarios en su estado actual, sin la existencia de Livria. Estos diagramas ilustran el "end-to-end journey" de cada uno de los arquetipos de User Persona elaborados, abarcando desde el momento en que un usuario siente la necesidad de leer, hasta el cierre de su experiencia.

A través de estos mapas, se identifican las etapas cruciales del proceso, las acciones que realizan los usuarios, sus pensamientos, emociones y, lo más importante, los puntos de dolor y las oportunidades que la situación actual presenta. Al vincular cada mapa con su User Persona correspondiente, se busca evidenciar de manera clara cómo las frustraciones de cada arquetipo, como la dificultad para encontrar libros relevantes, la falta de tiempo o la desconexión social, son el motor para la creación de Livria. Estos recorridos As-Is nos servirán de base para diseñar una experiencia futura (To-Be) que sea fluida, atractiva y que resuelva de manera efectiva las necesidades de nuestros usuarios.

***Segmento #1: Estudiantes y jóvenes universitarios***
*User Journey Map del Segmento 1*

<p align="center">
  <img src="https://imgur.com/RZ4Ylha.jpg" alt="12231">
</p>

***Segmento #2: Lectores casuales y aficionados a la lectura***
*User Journey Map del Segmento 2*

<p align="center">
  <img src="https://imgur.com/Fue9yto.jpg" alt="12231">
</p>

Para mejor visualización de los User Journey Maps de Livria, acceder al siguiente link:
https://drive.google.com/drive/folders/14E_HWaeTiKD7pzQmV_kdxLkU8VU8cxag?usp=sharing

### 2.3.4. Empathy Mapping

Para la elaboración de los Empathy Maps, el equipo siguió una metodología centrada en el usuario, basada en la recopilación de datos cualitativos obtenidos a través de entrevistas, encuestas, observación directa y análisis de comportamiento digital. Cada mapa fue diseñado teniendo en cuenta un User Persona específico, con el objetivo de capturar lo que el usuario piensa, siente, dice y hace en relación con la plataforma. Posteriormente, se identificaron los principales miedos, frustraciones, necesidades y motivaciones que influyen en su experiencia. Esta herramienta permitió generar una visión empática que guía la toma de decisiones de diseño y desarrollo, asegurando que cada funcionalidad responda realmente a las expectativas y preocupaciones del usuario.

***Segmento #1: Personas que desean desarrollar y expandir el hábito de la lectura***

*Empathy Map del Segmento 1*

<p align="center">
  <img src="https://imgur.com/KEwYBZO.jpg" alt="12231">
</p>

***Segmento #2: Personas interesadas en compartir intereses literarios e interactuar con otros lectores***

*Empathy Map del Segmento 2*

<p align="center">
  <img src="https://imgur.com/LhuwaSw.jpg" alt="12231">
</p>

### 2.3.5. Ubiquitous Language

| Término (Inglés)           | Definición                                                                                                                                                    |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Casual reader              | Persona que lee ocasionalmente por interés o  entretenimiento, sin una hábito fijo de lectura.                                                               |
| Amateur reader             | Persona con un hábito de lectura más constante, que busca libros según sus intereses y disfruta compartir su experiencia lectora.                            |
| Young university student   | Usuario que cursa estudios superiores y busca libros relacionados con sus trabajos o proyectos académicos o materias específicas.                             |
| Recommendations            | Sugerencias personalizadas de libros según el perfil, intereses, historial de lectura o área académica que busca el usuario.                                 |
| Reader community           | Sección donde los usuarios interactúan, comparten opiniones, participan en retos y descubren libros en común.                                                |
| Search for books           | Herramienta que permite encontrar libros mediante filtros avanzados como autor, editorial, género, formato y disponibilidad.                                  |
| Book formats               | Tipos de presentación de un libro:  digital(eBook), audiolibro o físico.                                                                                     |
| Save books                 | Función que permite marcar libros para revisarlos después o recibir notificaciones sobre su disponibilidad.                                                  |
| Reviews                    | Comentarios, calificaciones y valoraciones que los usuarios de la comunidad dejan sobre libros que han leído, para guiar o recomendar a otros lectores.      |
| Audiobook                  | Un libro narrado en formato de audio, que permite a los usuarios escuchar el contenido en vez de leerlo.                                                     |
| Digital books              | Versión electrónica o digital de un libro que puede leerse desde múltiples dispositivos.                                                                     |
| Physical books             | Libro impreso en papel, disponible para compra en formato tradicional.                                                                                       |


## 2.4. Requirements Specification

En esta sección se consolidan los requisitos del producto digital a partir del análisis detallado de la información obtenida durante las fases de investigación y mapeo de experiencia del usuario. El objetivo es traducir los hallazgos en especificaciones claras, priorizadas y alineadas con las necesidades reales de los usuarios y los objetivos del negocio. Mediante el uso de User Stories, el Impact Map y el Product Backlog, se organiza una visión completa del producto que orienta al equipo de desarrollo en la construcción de soluciones útiles, centradas en el usuario y técnicamente factibles. Esta especificación constituye el punto de partida para la planificación, el diseño y la implementación del producto.

### 2.4.1. User Stories

Las User Stories permiten traducir la visión del producto en necesidades concretas de los lectores y de la comunidad que se busca construir. Cada historia refleja, desde la perspectiva del usuario, las funcionalidades que harán posible explorar, adquirir y disfrutar libros dentro de la plataforma. De esta manera, se transforman los objetivos de Livria en requisitos claros y accionables para el equipo de desarrollo. Estas historias no solo sirven como una guía práctica para priorizar y organizar el trabajo en el Product Backlog, sino que también garantizan que cada funcionalidad esté alineada con la propuesta de valor de Livria.

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US01 |
| **User**                                       | Visitante de Landing Page |
| **Priority**                                   | 1 – Must Have |
| **Epic**                                       | EP01: Landing Page |
| **Title**                                      | Presentación de servicios de Livria |
| **Description**                                | Como visitante, quiero ver información relevante sobre las funcionalidades principales que ofrece Livria, para conocer las característica únicas de la aplicación. |
| **Acceptance Criteria – Escenario 1: Acceso a “Servicios” desde el inicio** | Dado que el visitante se encuentra en el inicio de la landing page. Y el visitante quiere ver las funcionalidad de Livria, Cuando el visitante hace clic en “Ver Más +”, Entonces la página se desplaza hasta la sección “Servicios”. |
| **Acceptance Criteria – Escenario 2: Acceso a “Servicios” desde el encabezado** | Dado que el visitante se encuentra en cualquier otra sección de la landing page. Y el visitante quiere ir a la sección “Servicios”, Cuando el visitante hace clic en el link “Servicios” del encabezado, Entonces la página se desplaza hacia dicha sección de forma fluida. |
| **Acceptance Criteria – Escenario 3: Acceso a “Servicios” mediante scroll** | Dado que el visitante se encuentra en la landing page, Cuando el visitante empieza a hacer scroll desde el inicio, Entonces la página le muestra la siguiente sección, es decir, la de “Servicios”. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US02 |
| **User**                                       | Visitante de Landing Page |
| **Priority**                                   | 2 – Should Have |
| **Epic**                                       | EP01: Landing Page  |
| **Title**                                      | Acceso a la sección “Sobre Nosotros” desde la landing page |
| **Description**                                | Como visitante, quiero acceder fácilmente a la sección “Sobre Nosotros”, para conocer la trayectoria de los creadores de Livria, comprender en qué consiste la plataforma y descubrir las funcionalidades que ofrece. |
| **Acceptance Criteria – Escenario 1: Acceso a “Sobre Nosotros” desde el encabezado** | Dado que el visitante se encuentra en cualquier sección de la landing page Y el visitante quiere ver información sobre los creadores de Livria, Cuando el visitante hace clic en el link “Sobre Nosotros” del encabezado Entonces la página se desplaza hacia dicha sección de forma fluida. |
| **Acceptance Criteria – Escenario 2: Acceso a “Sobre Nosotros” mediante scroll** | Dado que el visitante se encuentra en la landing page, Cuando el visitante empieza a hacer scroll desde el inicio Entonces la página le muestra las siguientes secciones hasta llegar a la de “Sobre Nosotros”. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US03 |
| **User**                                       | Visitante de Landing Page |
| **Priority**                                   | 2 – Should Have |
| **Epic**                                       | EP01: Landing Page |
| **Title**                                      | Cambio de idioma en la Landing Page |
| **Description**                                | Como visitante, quiero navegar por la plataforma en mi idioma preferido, para comprender fácilmente el contenido de presentación de Livria. |
| **Acceptance Criteria – Escenario 1: Cambio de inglés a español** | Dado que el visitante quiere cambiar el idioma de la landing page Y la página se encuentra en inglés, Cuando el visitante hace clic en “ES” del encabezado o en el link igual del pie de página Entonces la página cambia de idioma al español. |
| **Acceptance Criteria – Escenario 2: Cambio de español a inglés** | Dado que el visitante quiere cambiar el idioma de la landing page Y la página se encuentra en español, Cuando el visitante hace clic en “EN” del encabezado o en el link igual del pie de página Entonces la página cambia de idioma al inglés. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US04 |
| **User**                                       | Visitante de Landing Page |
| **Priority**                                   | 2 – Should Have |
| **Epic**                                       | EP01: Landing Page |
| **Title**                                      | Visualización de la sección “Home” en la landing page |
| **Description**                                | Como visitante, quiero leer un resumen sobre qué es Livria en el inicio de la página, para entender rápidamente qué producto me ofrece |
| **Acceptance Criteria – Escenario 1: Acceso a “Home”** | Dado que el visitante quiere conocer más sobre Livria Cuando el visitante entre a la landing page Entonces la página muestra el inicio, es decir, “Home” Y esta sección muestra un resumen de Livria y un carrusel de imágenes. |
| **Acceptance Criteria – Escenario 2: Acceso a “Home” desde el encabezado** | Dado que el visitante se encuentra en cualquier otra sección de la landing page Y el visitante quiere ir a la sección de inicio, Cuando el visitante hace clic en el link “Home” del encabezado Entonces la página se desplaza hacia dicha sección de forma fluida. |
| **Acceptance Criteria – Escenario 3: Acceso a “Home” mediante el logo** | Dado que el visitante se encuentra en cualquier otra sección de la landing page, Cuando el visitante hace clic en el logo de Livria, Entonces la página le muestra el inicio, es decir, “Home”. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US05 |
| **User**                                       | Visitante de Landing Page |
| **Priority**                                   | 2 – Should Have |
| **Epic**                                       | EP01: Landing Page |
| **Title**                                      | Acceso a la sección “Contáctanos” desde la landing page |
| **Description**                                | Como visitante, quiero identificar fácilmente la sección “Contáctanos”, para poder establecer comunicación en caso de necesitar información adicional sobre la plataforma o tener interés en colaborar con el equipo de Livria. |
| **Acceptance Criteria – Escenario 1: Acceso a “Contáctanos” desde el encabezado** | Dado que el visitante se encuentra en cualquier sección de la landing page Y el visitante quiere contactarse con el equipo de Bookify - Livria, Cuando el visitante hace clic en el link “Contáctanos” del encabezado Entonces la página se desplaza hacia dicha sección de forma fluida. |
| **Acceptance Criteria – Escenario 2: Acceso a “Contáctanos” mediante scroll** | Dado que el visitante se encuentra en la landing page, Cuando el visitante empieza a hacer scroll desde el inicio Entonces la página le muestra las siguientes secciones hasta llegar a la de “Contáctanos”. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US06 |
| **User**                                       | Visitante de Landing Page |
| **Priority**                                   | 1 – Must Have |
| **Epic**                                       | EP01: Landing Page |
| **Title**                                      | Navegación simple entre secciones en la Landing Page |
| **Description**                                | Como visitante, quiero visualizar un encabezado con las secciones de la landing page, para navegar fácil y rápidamente entre ellas. |
| **Acceptance Criteria – Escenario 1: Acceso inmediato al llegar** | Dado que el visitante acaba de ingresar a la landing page, Cuando la página cargue la pantalla inicial y el encabezado Entonces el visitante puede identificar rápidamente cómo navegar por la página y cómo acceder a las secciones que le interesen. |
| **Acceptance Criteria – Escenario 2: Navegación desde el encabezado** | Dado que el visitante se encuentra en la landing page de Livria, Cuando el visitante hace clic en cualquiera de las opciones del encabezado Entonces la página muestra dicha sección de manera fluida y sin contratiempos. |
| **Acceptance Criteria – Escenario 3: Encabezado visible durante el scroll** | Dado que el visitante se desplaza en la página mediante el scroll, Cuando el visitante navegue las distintas secciones Entonces el encabezado permanece fijo y visible en la parte superior de la página Y el encabezado permite cambiar de sección en cualquier momento sin necesidad de volver al inicio. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US07 |
| **User**                                       | Visitante de Landing Page |
| **Priority**                                   | 1 – Must Have |
| **Epic**                                       | EP01: Landing Page |
| **Title**                                      | Diseño atractivo de la landing page |
| **Description**                                | Como visitante, quiero que la landing page sea visualmente atractiva, para sentirme interesado por Livria y motivado a usar la aplicación que ofrecen. |
| **Acceptance Criteria – Escenario 1: Presentación visualmente atractiva** | Dado que el visitante accede a la landing page de Livria, Cuando la página cargue todos sus elementos Entonces la página mostrará un diseño visual armonioso, imágenes llamativas, una paleta de colores atractiva y una tipografía clara. |
| **Acceptance Criteria – Escenario 2: Elementos visuales concordantes** | Dado que el visitante se encuentra en la landing page de Livria Cuando el visitante navegue a través de las secciones de la página Entonces los elementos visuales seguirán la tipografía y la paleta de colores establecida, de modo que sea agradable a la vista. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US08 |
| **User**                                       | Visitante de Landing Page |
| **Priority**                                   | 2 – Should Have |
| **Epic**                                       | EP01: Landing Page |
| **Title**                                      | Botón de redirección de descarga de la aplicación móvil |
| **Description**                                | Como visitante, quiero tener un acceso directo a la tienda para descargar Livria, para empezar a utilizar la aplicación. |
| **Acceptance Criteria – Escenario 1: Redirección a descarga de aplicación móvil** | Dado que el visitante se encuentra en el inicio de la landing page Cuando el visitante hace clic en el botón “Descargar” Entonces la página lo redirecciona a su tienda de aplicaciones local para que descargue la aplicación. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US09 |
| **User**                                       | Visitante de Landing Page |
| **Priority**                                   | 3 – Could Have |
| **Epic**                                       | EP01: Landing Page |
| **Title**                                      | Acceder a las redes sociales de Livria |
| **Description**                                | Como visitante, quiero poder navegar a las redes sociales oficiales de Livria, para mantenerme informado sobre sus novedades y explorar contenido adicional. |
| **Acceptance Criteria – Escenario 1: Ir a las cuentas oficiales de Livria** | Dado que el visitante se encuentra en el pie de página, Cuando el usuario hace clic en uno de los íconos de redes sociales Entonces se abre en una nueva pestaña la cuenta oficial de Livria en la red social seleccionada. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US10 |
| **User**                                       | Visitante de Landing Page |
| **Priority**                                   | 3 – Could Have |
| **Epic**                                       | EP01: Landing Page |
| **Title**                                      | Footer de la Landing Page |
| **Description**                                | Como visitante, quiero visualizar un apartado en el pie de página con las secciones de la landing page, para retornar a cualquiera de ellas. |
| **Acceptance Criteria – Escenario 1: Navegación desde el pie de página** | Dado que el visitante está en la parte inferior de la landing page Cuando el visitante hace clic en las opciones del apartado de “Navegación” del pie de página Entonces la página se desliza automáticamente hacia la sección correspondiente. |
| **Acceptance Criteria – Escenario 2: Navegación rápida tras desplazamiento largo** | Dado que el visitante ha hecho scroll por toda la página y deseo volver al inicio, Cuando el visitante hace clic en el enlace “Home” dentro del pie de página, Entonces la página se desplaza automáticamente hacia la parte superior mostrando la sección de inicio. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US11 |
| **User**                                       | Visitante de Landing Page |
| **Priority**                                   | 3 – Could Have |
| **Epic**                                       | EP01: Landing Page |
| **Title**                                      | Formulario de contacto |
| **Description**                                | Como visitante, quiero dejar mi información para que el equipo de Bookify - Livria me contacte para resolver una duda o trabajar con ellos. |
| **Acceptance Criteria – Escenario 1: Consulta general con el equipo de Livria** | Dado que el visitante desea realizar alguna consulta al equipo de Livria Cuando el visitante rellene los campos “Nombres y Apellidos”, “Correo electrónico”, “Número celular” y “Motivo de contacto” Y el visitante acceda a compartir su información personal Entonces el formulario enviará esta consulta al equipo de Livria. |
| **Acceptance Criteria – Escenario 2: Oportunidad Laboral en el equipo de Livria** | Dado que el visitante desea trabajar con el equipo de Livria Cuando el visitante rellene todos los campos de información de contacto Y el visitante adjunte el archivo de su CV Y el visitante acceda a compartir su información personal Entonces el formulario enviará la postulación al equipo de Livria. |
| **Acceptance Criteria – Escenario 3: Falta de consentimiento** | Dado que el visitante desea realizar una consulta o postular para trabajo en Livria Cuando rellene los campos pero no seleccione la casilla de consentimiento del envío de información personal Entonces el formulario no enviará la consulta o postulación al equipo de Livria Y la página mostrará un popup señalando que marque la casilla. |
| **Acceptance Criteria – Escenario 4: Información incompleta** | Dado que el visitante desea realizar una consulta o postular para trabajo en Livria Cuando rellene solo algunos campos de información de contacto Entonces el formulario no enviará la consulta o postulación al equipo de Livria Y la página mostrará un popup señalando que rellene todos los campos. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US12 |
| **User**                                       | Usuario de Livria |
| **Priority**                                   | 1 – Must Have |
| **Epic**                                       | EP02: Personalización de la experiencia lectora |
| **Title**                                      | Interacción con recomendaciones según preferencias literarias |
| **Description**                                | Como usuario, quiero recibir recomendaciones personalizadas basadas en mis preferencias literarias para poder descubrir nuevos libros y autores. |
| **Acceptance Criteria – Escenario 1: Recomendaciones iniciales aleatorias** | Dado que el usuario acaba de crear una cuenta en Livria Cuando el usuario ingrese a la sección de “Recomendaciones” Entonces la plataforma mostrará las primeras recomendaciones aleatorias para el nuevo usuario. |
| **Acceptance Criteria – Escenario 2: Marcar un libro como interesante** | Dado que el usuario está explorando los libros Cuando el usuario hace clic en el ícono del bookmark Entonces el sistema registra el libro como preferencia positiva, Y la plataforma muestra una confirmación visual Y el algoritmo de recomendaciones se adapta a la selección. |
| **Acceptance Criteria – Escenario 3: Marcar un libro como no interesante** | Dado que el usuario está explorando los libros Cuando el usuario hace clic en el ícono del negativo Entonces el sistema registra el libro como preferencia negativa, Y la plataforma muestra una confirmación visual Y el algoritmo de recomendaciones se adapta a la selección. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US13 |
| **User**                                       | Usuario de Livria |
| **Priority**                                   | 2 – Should have |
| **Epic**                                       | EP03: Notificaciones de usuario |
| **Title**                                      | Configuración de notificaciones |
| **Description**                                | Como usuario, quiero tener la posibilidad de personalizar mis preferencias de notificación, para recibir únicamente la información que realmente me interesa y así mejorar mi experiencia dentro de la plataforma. |
| **Acceptance Criteria – Escenario 1: Acceso a la sección de configuración de notificaciones** | Dado que el usuario accede al menú de ajustes de su cuenta Cuando selecciona la opción de configuración de notificaciones Entonces podrá visualizar todas las categorías disponibles de notificaciones de la aplicación. |
| **Acceptance Criteria – Escenario 2: Personalización de preferencias de notificación** | Dado que el usuario está dentro de la sección de configuración de notificaciones Cuando decide activar o desactivar alguna categoría específica Entonces la plataforma actualizará inmediatamente las preferencias según su elección, manteniéndolas activas hasta que el usuario decida modificarlas nuevamente o restablecer los valores predeterminados. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US14 |
| **User**                                       | Usuario de Livria |
| **Priority**                                   | 1 – Must Have |
| **Epic**                                       | EP03: Notificaciones de usuario |
| **Title**                                      | Notificaciones instantáneas |
| **Description**                                | Como usuario, quiero recibir notificaciones instantáneas en la aplicación, para mantenerme al tanto sobre nuevas publicaciones en la comunidad y libros disponibles. |
| **Acceptance Criteria – Escenario 1: Notificación de incremento de stock** | Dado que el usuario ha marcado previamente un libro como favorito Cuando el sistema dispone de nuevo stock a un libro agotado Y el usuario ha marcado ese libro como preferido Entonces el usuario recibe una notificación sobre la actualización de stock. |
| **Acceptance Criteria – Escenario 2: Notificación de nuevas publicaciones** | Dado que el usuario pertenece a una comunidad existente Cuando otros usuarios realicen publicaciones en esa comunidad Entonces el usuario recibe una notificación sobre las nuevas publicaciones. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US15 |
| **User**                                       | Usuario de Livria |
| **Priority**                                   | 1 – Must Have |
| **Epic**                                       | EP04: Gestión de cuenta y seguridad de usuario |
| **Title**                                      | Registro e inicio de sesión |
| **Description**                                | Como usuario, quiero poder registrarme e iniciar sesión con mis credenciales, para acceder a la plataforma y descubrir nuevos títulos de mi agrado. |
| **Acceptance Criteria – Escenario 1: Registro de nuevo usuario** | Dado que el usuario abre la aplicación Y el usuario selecciona la opción “Registrarse” Cuando el usuario completa correctamente los campos requeridos Y el usuario confirma el registro Entonces el sistema debe crear una cuenta nueva, iniciar sesión automáticamente y mostrar un mensaje de registro exitoso. |
| **Acceptance Criteria – Escenario 2: Inicio de sesión de usuario registrado** | Dado que el usuario ya tiene una cuenta creada en Livria Cuando el usuario introduce su username y contraseña en el formulario de inicio de sesión Entonces el sistema debe autenticar sus credenciales y redirigirlo a su panel principal, donde podrá continuar con su experiencia de lectura. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US16 |
| **User**                                       | Usuario de Livria |
| **Priority**                                   | 1 – Must Have |
| **Epic**                                       | EP02: Personalización de la experiencia lectora |
| **Title**                                      | Visualización de recomendaciones en la plataforma |
| **Description**                                | Como usuario, quiero observar mis recomendaciones de manera ordenada y atractiva para poder elegir mi siguiente lectura. |
| **Acceptance Criteria – Escenario 1: Visualización clara de recomendaciones** | Dado que el usuario está en la aplicación web de Livria, Cuando el usuario quiere ver sus recomendaciones Y el usuario accede a la sección de “Recomendaciones” Entonces la plataforma muestra seis recomendaciones con una miniatura del libro y su título. |
| **Acceptance Criteria – Escenario 2: Visualización clara de recomendaciones** | Dado que el usuario se encuentra en la sección de “Recomendaciones” Cuando el usuario hace clic en el botón de “Refrescar” Entonces la plataforma muestra nuevas seis recomendaciones con una miniatura del libro y su título. |
| **Acceptance Criteria – Escenario 3: Acceso directo al libro recomendado** | Dado que el usuario se encuentra en la sección de “Recomendaciones” Cuando el usuario hace clic en una de las recomendaciones Entonces la plataforma lo dirige a la visualización completa del libro con más detalles y opciones. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US17 |
| **User**                                       | Usuario de Livria |
| **Priority**                                   | 1 – Must Have |
| **Epic**                                       | EP04: Gestión de cuenta y seguridad de usuario |
| **Title**                                      | Cierre de sesión |
| **Description**                                | Como usuario, quiero poder cerrar sesión de mi cuenta cuando lo desee, para proteger mi información personal y asegurar la privacidad de mis datos al finalizar el uso de la plataforma. |
| **Acceptance Criteria – Escenario 1: Registro de nuevo usuario** | Dado que el usuario ha iniciado sesión Y el usuario se encuentra en la sección de configuración de su cuenta Cuando el usuario selecciona la opción "Cerrar sesión" Entonces el sistema debe cerrar su sesión activa de forma segura Y redirigirlo automáticamente a la pantalla de login de Livria. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US18 |
| **User**                                       | Usuario de Livria |
| **Priority**                                   | 1 – Must Have |
| **Epic**                                       | EP05: Comunidades |
| **Title**                                      | Creación de publicaciones en comunidades |
| **Description**                                | Como usuario, quiero poder crear y compartir publicaciones dentro de las comunidades temáticas de la plataforma, para interactuar con otros lectores a través de imágenes. |
| **Acceptance Criteria – Escenario 1: Publicación de imágenes o contenido gráfico** | Dado que el usuario decide crear una nueva publicación dentro de una comunidad Y el usuario opta por subir una imagen o ilustración Cuando el usuario selecciona y carga el archivo desde su dispositivo Entonces el sistema debe mostrar correctamente la imagen en la publicación, habilitando los comentarios por parte de otros usuarios. |
| **Acceptance Criteria – Escenario 2: Publicación textual sin contenido gráfico** | Dado que el usuario desea compartir una publicación sin usar imágenes Cuando el usuario ingresa un texto en el campo de publicación Y el usuario lo envía Entonces el sistema debe guardar y mostrar la publicación correspondiente |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US19 |
| **User**                                       | Usuario de Livria |
| **Priority**                                   | 1 – Must Have |
| **Epic**                                       | EP05: Comunidades |
| **Title**                                      | Gestión de comunidades |
| **Description**                                | Como usuario, quiero poder crear y unirme a comunidades relacionadas con mis intereses literarios con el fin de conectar con distintos lectores o autores de títulos reconocidos.  |
| **Acceptance Criteria – Escenario 1: Crear una comunidad literaria** | Dado que el usuario se encuentra en la sección "Comunidades" Cuando el usuario selecciona la opción "Crear comunidad" Y el usuario completa el formulario con un nombre, descripción y categoría de la comunidad Entonces el sistema debe registrar la nueva comunidad Y el sistema debe mostrarla dentro del listado general de comunidades disponibles en Livria. |
| **Acceptance Criteria – Escenario 2: Unirse a una comunidad existente** | Dado que el usuario está explorando la lista de comunidades disponibles Cuando el usuario ingresa al perfil de una comunidad de su interés Y el usuario selecciona la opción "Unirse" Entonces el sistema debe agregarlo como miembro de dicha comunidad Y el sistema debe mostrar una confirmación visual de su ingreso exitoso. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US20 |
| **User**                                       | Usuario de Livria |
| **Priority**                                   | 2 – Should Have |
| **Epic**                                       | EP05: Comunidades |
| **Title**                                      | Comentarios en publicaciones |
| **Description**                                | Como usuario, quiero poder comentar en las publicaciones dentro de las comunidades literarias, para compartir opiniones, intercambiar ideas sobre libros y conectar con otros lectores. |
| **Acceptance Criteria – Escenario 1: Agregar un comentario** | Dado que el usuario se encuentra explorando una comunidad Y el usuario visualiza una publicación donde desea comentar Cuando el usuario selecciona la opción comentar Entonces el sistema despliega un cuadro de texto Y el sistema debe publicar su comentario al enviarlo correctamente. |
| **Acceptance Criteria – Escenario 2: Visualización de comentarios** | Dado que el usuario está visualizando una publicación dentro de una comunidad Y el usuario accede a la sección de comentarios Cuando el usuario hace scroll en esa sección Entonces el usuario visualiza los comentarios realizados por otros usuarios |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US21 |
| **User**                                       | Usuario de Livria |
| **Priority**                                   | 1 – Must Have |
| **Epic**                                       | EP06: Compra de libros |
| **Title**                                      | Compra de libros digitales y físicos |
| **Description**                                | Como usuario, quiero poder comprar libros digitales y físicos desde la plataforma para acceder a lecturas nuevas de manera inmediata o recibir ediciones impresas en mi domicilio. |
| **Acceptance Criteria – Escenario 1: Compra de libro digital** | Dado que el usuario está navegando por el catálogo de Livria Cuando el usuario selecciona un libro digital y presiona “Comprar” Y el usuario completa el proceso de pago Entonces el sistema debe confirmar la compra Y el sistema permite la descarga inmediata del libro en su biblioteca digital. |
| **Acceptance Criteria – Escenario 2: Compra de libro físico** | Dado que el usuario está navegando por el catálogo Cuando el usuario selecciona un libro físico y presiona “Comprar” Y el usuario completa el proceso de pago y envío Entonces el sistema debe confirmar la compra Y el sistema genera el pedido con estado “En proceso”. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US22 |
| **User**                                       | Usuario de Livria |
| **Priority**                                   | 1 – Must Have |
| **Epic**                                       | EP06: Compra de libros |
| **Title**                                      | Barra de búsqueda |
| **Description**                                | Como usuario, quiero utilizar una barra de búsqueda para encontrar libros, autores y comunidades literarias de forma rápida y precisa, con el fin de acceder fácilmente a contenido de interés sin tener que navegar por toda la plataforma. |
| **Acceptance Criteria – Escenario 1: Búsqueda de libros específicos** | Dado que el usuario interactúa con la barra de búsqueda Cuando el usuario escribe el nombre de un libro Entonces el sistema debe mostrar una lista de resultados relacionados con el título ingresado, incluyendo portadas y autor. |
| **Acceptance Criteria – Escenario 2: Búsqueda de autores** | Dado que el usuario desea encontrar obras de un autor en particular Cuando ingresa el nombre del autor en la barra de búsqueda Entonces el sistema debe mostrar todos los libros de catálogo pertenecientes a dicho autor. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US23 |
| **User**                                       | Usuario de Livria |
| **Priority**                                   | 2 – Should Have |
| **Epic**                                       | EP06: Compra de libros |
| **Title**                                      | Proceso de pago |
| **Description**                                | Como usuario, quiero poder pagar mis libros mediante distintos métodos de pago, para asegurarme de que mi compra sea rápida y confiable mediante una única plataforma de pago. |
| **Acceptance Criteria – Escenario 1: Pago exitoso** | Dado que el usuario ha añadido uno o más libros a su carrito de compras Cuando el usuario selecciona una opción de pago y completa los datos solicitados Entonces el sistema procesa el pago correctamente Y el sistema muestra un mensaje de confirmación con el comprobante de la transacción. |
| **Acceptance Criteria – Escenario 2: Error en el proceso de pago** | Dado que el usuario intenta completar el pago mediante la opción seleccionada Cuando ocurre un error Entonces el sistema muestra un mensaje explicando el error Y el sistema permite reintentar la operación. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US24 |
| **User**                                       | Usuario de Livria |
| **Priority**                                   | 3 – Could Have |
| **Epic**                                       | EP02: Personalización de la experiencia lectora |
| **Title**                                      | Valoración y reseña de libros |
| **Description**                                | Como usuario, quiero poder valorar y dejar reseñas en los libros que he leído, para compartir mi opinión y ayudar a otros lectores en su elección. |
| **Acceptance Criteria – Escenario 1: Valoración con estrellas** | Dado que el usuario ha finalizado la lectura de un libro Cuando accede a la sección de valoraciones  Entonces puede calificar el libro con una puntuación de 1 a 5 estrellas Y la valoración se actualiza en la ficha del libro |
| **Acceptance Criteria – Escenario 2: Escribir una reseña** | Dado que el usuario desea dejar un comentario detallado Cuando accede a la opción “Escribir reseña” Entonces puede redactar y publicar su opinión sobre el contenido, estilo o experiencia de lectura. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US25 |
| **User**                                       | Usuario de Livria |
| **Priority**                                   | 1 – Must Have |
| **Epic**                                       | EP04: Gestión de cuenta y seguridad de usuario |
| **Title**                                      | Actualización y gestión de suscripción |
| **Description**                                | Como usuario, quiero poder actualizar mi plan de suscripción, recibir notificaciones sobre pagos y revertir cambios si me arrepiento, para tener un mayor control sobre mi experiencia en la plataforma. |
| **Acceptance Criteria – Escenario 1: Cambio de plan (actualización)** | Dado que el usuario tiene un plan gratuito Cuando el usuario selecciona el plan “Community” Y el usuario realiza el pago, completando los datos requeridos Entonces el sistema habilita el acceso a la vista e interacción de comunidades Y el usuario recibe una notificación confirmando la transacción exitosa |
| **Acceptance Criteria – Escenario 2: Reversión al plan gratuito** | Dado que el usuario se encuentra suscrito a un plan de pago activo Cuando el usuario decide cambiar al plan gratuito desde la sección de configuración de suscripción Entonces el sistema revierte su suscripción al plan gratuito inmediatamente. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US26 |
| **User**                                       | Usuario de Livria |
| **Priority**                                   | 1 – Must Have |
| **Epic**                                       | EP07: Accesibilidad y experiencia de uso multiplataforma |
| **Title**                                      | Disponibilidad 24/7 |
| **Description**                                | Como usuario, quiero que la plataforma esté disponible en cualquier momento del día, para acceder a mis libros, comunidades y funcionalidades sin importar el lugar o la hora. |
| **Acceptance Criteria – Escenario 1: Acceso ininterrumpido** | Dado que el usuario desea acceder a la plataforma en cualquier momento Cuando el usuario inicia sesión en Livria en cualquier horario Entonces el sistema debe estar disponible Y el sistema debe permitir el acceso sin restricciones. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US27 |
| **User**                                       | Usuario de Livria |
| **Priority**                                   | 1 – Must Have |
| **Epic**                                       | EP07: Accesibilidad y experiencia de uso multiplataforma |
| **Title**                                      | Interfaz amigable y navegación sencilla de la aplicación móvil |
| **Description**                                | Como usuario, quiero una interfaz intuitiva y fácil de usar, para navegar entre libros, comunidades y configuraciones sin complicaciones ni curvas de aprendizaje. |
| **Acceptance Criteria – Escenario 1: Navegación clara y sencilla** | Dado que el usuario inicia sesión en la plataforma Cuando desea acceder a las secciones principales como la pantalla de inicio o “Recomendaciones” Entonces podrá hacerlo con pocos clics y sin confusión, gracias a una estructura organizada y un diseño intuitivo. |
| **Acceptance Criteria – Escenario 2: Navegación entre categorías** | Dado que el usuario se encuentra en la barra superior de navegación Cuando el usuario hace clic en una categoría Entonces el sistema le redirige a una página que muestra únicamente libros correspondientes a esa categoría. |
| **Acceptance Criteria – Escenario 3: Accesibilidad visual** | Dado que el usuario interactúa con la aplicación Cuando el usuario visualiza la interfaz Entonces los botones, textos e íconos deben tener buen contraste, tamaño adecuado y estar correctamente etiquetados para garantizar la accesibilidad. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US28 |
| **User**                                       | Usuario de Livria |
| **Priority**                                   | 2 – Should Have |
| **Epic**                                       | EP07: Accesibilidad y experiencia de uso multiplataforma |
| **Title**                                      | Soporte multiplataforma |
| **Description**                                | Como usuario, quiero ingresar a Livria desde distintos dispositivos, para acceder a mis libros y comunidades desde cualquier lugar y sin perder mi progreso. |
| **Acceptance Criteria – Escenario 1: Compatibilidad con diferentes sistemas operativos** | Dado que el usuario utiliza distintos dispositivos  Cuando el usuario accede a Livria desde cualquiera de ellos Entonces la experiencia debe mantenerse fluida y funcional, sin errores de formato o limitaciones de funciones. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | US29 |
| **User**                                       | Usuario de Livria |
| **Priority**                                   | 3 – Could Have |
| **Epic**                                       | EP06: Compra de libros |
| **Title**                                      | Filtro lateral por atributos del libro |
| **Description**                                | Como usuario, quiero filtrar los libros según subcategorías, orden de precio o título, formato e idioma para encontrar más fácilmente el contenido que me interesa. |
| **Acceptance Criteria – Escenario 1: Ordenamiento por criterios** | Dado que el usuario se encuentra en una pestaña de un género específico Y el usuario quiere ordenar los resultados Cuando el usuario elige una opción como “Menor a mayor precio” Entonces la lista se reordena automáticamente según esos criterios. |
| **Acceptance Criteria – Escenario 2: Filtrado por idioma** | Dado que el usuario se encuentra en una pestaña de un género específico Y el usuario quiere ordenar los resultados Cuando el usuario selecciona el idioma de su preferencia Entonces se muestran los libros que coincidan con el idioma elegido. |
| **Acceptance Criteria – Escenario 3: Borrado de filtros aplicados** | Dado que el usuario se encuentra en una pestaña de un género específico Y el usuario ha aplicado filtros Cuando el usuario presiona el botón “Borrar selección” Entonces se eliminan todos los filtros activos Y la lista vuelve a su estado inicial. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | TS01 |
| **User**                                       | Developer |
| **Priority**                                   | 1 – Must Have |
| **Epic**                                       | EP08: Vista de administrador |
| **Title**                                      | Acceso rápido a las secciones del sistema desde el Dashboard |
| **Description**                                | Como developer, quiero tener acceso rápido a las principales secciones del sistema, para poder acceder a la gestión libros, pedidos, inventarios, estadísticas y configuraciones de manera rápida. |
| **Acceptance Criteria – Escenario 1: Acceso a “Books” desde el Dashboard** | Dado que el developer se encuentra en el dashboard de la vista de administrador, Cuando el developer hace clic en el botón de "Books" en la sección de “Quick Actions”, Entonces el sistema redirige al developer a la sección de libros. |
| **Acceptance Criteria – Escenario 2: Acceso a “Orders” desde el Dashboard** | Dado que el developer se encuentra en el dashboard de la vista de administrador, Cuando el developer hace clic en el botón de "Orders" en la sección de “Quick Actions”, Entonces el sistema redirige al administrador a la sección de pedidos. |
| **Acceptance Criteria – Escenario 3: Acceso a “Inventory” desde el Dashboard** | Dado que el developer se encuentra en el dashboard de la vista de administrador, Cuando el developer hace clic en el botón de "Inventory" en la sección de “Quick Actions”, Entonces el sistema redirige al administrador a la sección de inventarios. |
| **Acceptance Criteria – Escenario 4: Acceso a “Stadistics” desde el Dashboard** | Dado que el developer se encuentra en el dashboard de la vista de administrador, Cuando el developer hace clic en el botón de "Statistics" en la sección de “Quick Actions”, Entonces el sistema redirige al administrador a la sección de estadísticas. |
| **Acceptance Criteria – Escenario 5: Acceso a “Settings” desde el Dashboard** | Dado que el developer se encuentra en el dashboard de la vista de administrador, Cuando el developer hace clic en el botón de "Settings" en la sección de “Quick Actions”, Entonces el sistema redirige al administrador a la sección de configuraciones. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | TS02 |
| **User**                                       | Developer |
| **Priority**                                   | 2 – Should Have |
| **Epic**                                       | EP08: Vista de administrador |
| **Title**                                      | Visualización de estadísticas de libros |
| **Description**                                | Como developer, quiero ver estadísticas relevantes sobre los libros, para poder tomar decisiones informadas sobre los libros más populares, más vendidos y otros datos clave del inventario. |
| **Acceptance Criteria – Escenario 1: Ver el total de libros y el total de géneros** | Dado que el developer se encuentra en la sección de Books, Cuando el developer visualiza el apartado de estadísticas, Entonces el sistema muestra el total de libros disponibles en el sistema y el total de géneros de libros registrados. |
| **Acceptance Criteria – Escenario 2: Ver el precio promedio de los libros** | Dado que el developer se encuentra en la sección de Books, Cuando el developer visualiza el apartado de estadísticas, Entonces el sistema muestra el precio promedio de todos los libros en el sistema. |
| **Acceptance Criteria – Escenario 3: Ver la cantidad de libros en stock** | Dado que el developer se encuentra en la sección de Books, Cuando el developer visualiza el apartado de estadísticas, Entonces el sistema muestra el número total de libros en stock, es decir, aquellos disponibles para la venta. |
| **Acceptance Criteria – Escenario 4: Ver el libro con más reseñas** | Dado que el developer se encuentra en la sección de Books, Cuando el developer visualiza el apartado de estadísticas, Entonces el sistema muestra el libro más visto en la plataforma y el libro más vendido de la plataforma. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | TS03 |
| **User**                                       | Developer |
| **Priority**                                   | 2 – Should Have |
| **Epic**                                       | EP08: Vista de administrador |
| **Title**                                      | Búsqueda de libros como administrador |
| **Description**                                | Como developer, quiero poder buscar libros de la colección utilizando diversos filtros, para encontrar fácilmente uno o más libros en específico. |
| **Acceptance Criteria – Escenario 1: Búsqueda por título o autor** | Dado que el developer se encuentra en el apartado de "Book Collection" en Books, Cuando el developer ingresa un título o autor en el campo de búsqueda, Entonces el sistema muestra los libros que coinciden con el título o autor ingresado. |
| **Acceptance Criteria – Escenario 2: Filtro por género e idioma** | Dado que el developer se encuentra en el apartado de "Book Collection" en Books, Cuando el developer selecciona un género en el filtro o un idioma en el  filtro, Entonces el sistema muestra los libros que pertenecen a ese género específico o a ese idioma en específico. |
| **Acceptance Criteria – Escenario 3: Ordenamiento de libros** | Dado que el developer se encuentra en el apartado de "Book Collection" en Books, Cuando el developer selecciona un criterio de ordenamiento (por ejemplo, precio, popularidad, fecha de publicación), Entonces el sistema ordena los libros según el criterio seleccionado. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | TS04 |
| **User**                                       | Developer |
| **Priority**                                   | 2 – Should Have |
| **Epic**                                       | EP08: Vista de administrador |
| **Title**                                      | Visualización de detalles completos de un libro |
| **Description**                                | Como developer, quiero ver la información completa de un libro, para poder tomar decisiones informadas sobre la gestión de mis productos. |
| **Acceptance Criteria – Escenario 1: Ver la información básica del libro** | Dado que el developer se encuentra en el apartado de "Book Collection" en Books, Cuando el developer observa un libro en específico, Entonces el sistema muestra una miniatura con la portada del libro, su título, autor, género, idioma, stock y cantidad de reviews. |
| **Acceptance Criteria – Escenario 2: Botón "View" para acceder a más detalles del libro** | Dado que el developer está visualizando un libro en el apartado de "Book Collection" en Books, Cuando el developer hace clic en el botón de "View", Entonces el sistema muestra una ventana con información detallada y completa sobre el libro, incluyendo la sinopsis y datos relacionados con su precio de compra, de venta y de stock. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | TS05 |
| **User**                                       | Developer |
| **Priority**                                   | 3 – Could Have |
| **Epic**                                       | EP08: Vista de administrador |
| **Title**                                      | Visualización de estadísticas y análisis de órdenes |
| **Description**                                | Como developer, quiero ver estadísticas clave sobre todas las órdenes, para poder realizar un análisis completo y tomar decisiones informadas sobre las ventas. |
| **Acceptance Criteria – Escenario 1: Ver el total de órdenes y de ganancias** | Dado que el developer se encuentra en la sección de Orders,  Cuando el developer visualiza el apartado de "Manage and Analyze All Livria Orders", Entonces el sistema muestra el total de órdenes realizadas en la plataforma y el total de ganancias generadas por todas las órdenes. |
| **Acceptance Criteria – Escenario 2: Ver órdenes pendientes y completas** | Dado que el developer se encuentra en la sección de Orders,  Cuando el developer visualiza el apartado de "Manage and Analyze All Livria Orders", Entonces el sistema muestra el número total de órdenes pendientes de procesamiento o envío y el número total de órdenes completas que han sido procesadas y entregadas. |
| **Acceptance Criteria – Escenario 3: Ver el promedio del valor de las órdenes** | Dado que el developer se encuentra en la sección de Orders,  Cuando el developer visualiza el apartado de "Manage and Analyze All Livria Orders", Entonces el sistema muestra el valor promedio de las órdenes realizadas en la plataforma. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | TS06 |
| **User**                                       | Developer |
| **Priority**                                   | 2 – Should Have |
| **Epic**                                       | EP08: Vista de administrador |
| **Title**                                      | Búsqueda y filtrado de órdenes |
| **Description**                                | Como developer, quiero poder buscar órdenes por ID de pedido o por el nombre del cliente, y poder filtrar de distintas formas, para encontrar fácilmente las órdenes que me interesan. |
| **Acceptance Criteria – Escenario 1: Buscar por ID de orden o por nombre del cliente** | Dado que el developer se encuentra en el apartado de "Manage and Analyze All Livria Orders" de Orders, Cuando el developer ingresa un ID de orden o el nombre del cliente en el campo de búsqueda, Entonces el sistema muestra las órdenes que coinciden con ese ID o asociadas a ese cliente. |
| **Acceptance Criteria – Escenario 2: Filtrar por estado del pedido** | Dado que el developer se encuentra en el apartado de "Manage and Analyze All Livria Orders" de Orders, Cuando el developer selecciona un estado de pedido (pendiente, en proceso, completado), Entonces el sistema muestra sólo las órdenes con el estado seleccionado. |
| **Acceptance Criteria – Escenario 3: Filtrar por fecha** | Dado que el developer se encuentra en el apartado de "Manage and Analyze All Livria Orders" de Orders, Cuando el developer selecciona un rango de fechas, Entonces el sistema muestra sólo las órdenes que corresponden a ese rango de fechas. |
| **Acceptance Criteria – Escenario 4: Filtrar por ordenamiento** | Dado que el developer se encuentra en el apartado de "Manage and Analyze All Livria Orders" de Orders, Cuando el developer selecciona un criterio de ordenamiento (por ejemplo, por fecha, por total, por estado), Entonces el sistema ordena las órdenes según el criterio seleccionado. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | TS07 |
| **User**                                       | Developer |
| **Priority**                                   | 2 – Should Have |
| **Epic**                                       | EP08: Vista de administrador |
| **Title**                                      | Visualización de la tabla con detalles de las órdenes |
| **Description**                                | Como developer, quiero que el sistema me muestre una tabla con detalles generales de las órdenes, para gestionar las órdenes de manera eficiente. |
| **Acceptance Criteria – Escenario 1: Ver la tabla con detalles de las órdenes** | Dado que el developer se encuentra en la sección Orders, Cuando el developer visualiza el apartado de "Order List", Entonces el sistema muestra una tabla con diversos atributos relacionados a cada orden.  |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | TS08 |
| **User**                                       | Developer |
| **Priority**                                   | 2 – Should Have |
| **Epic**                                       | EP08: Vista de administrador |
| **Title**                                      | Búsqueda y filtrado de libros en el Inventario |
| **Description**                                | Como developer, quiero tener una barra de búsqueda y filtros en la sección "Book Collection" del inventario, para poder buscar fácilmente un libro específico dentro del inventario. |
| **Acceptance Criteria – Escenario 1: Barra de búsqueda** | Dado que el developer está en el apartado de "Book Collection" de la sección Inventory, Cuando el developer ingresa un término en la barra de búsqueda, Entonces el sistema muestra los libros que coinciden con el término de búsqueda. |
| **Acceptance Criteria – Escenario 2: Filtro por género o por lenguaje** | Dado que el developer está en el apartado de "Book Collection" de la sección Inventory, Cuando el developer selecciona un género en el filtro o un lenguaje en el filtro, Entonces el sistema muestra los libros que pertenecen a ese género específico o los libros disponibles en ese lenguaje. |
| **Acceptance Criteria – Escenario 3: Ordenamiento de libros** | Dado que el developer está en el apartado de "Book Collection" de la sección Inventory, Cuando el developer selecciona un criterio de ordenamiento (por ejemplo, por precio, por stock, por fecha de publicación), Entonces el sistema ordena los libros según el criterio seleccionado. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | TS09 |
| **User**                                       | Developer |
| **Priority**                                   | 2 – Should Have |
| **Epic**                                       | EP08: Vista de administrador |
| **Title**                                      | Visualización de los libros en el inventario |
| **Description**                                | Como developer, quiero ver una tabla que contenga los detalles de cada libro, como su portada, título, autor, etc., para gestionar fácilmente el inventario de libros. |
| **Acceptance Criteria – Escenario 1: Ver la tabla con detalles del libro** | Dado que el developer está en la sección Inventory, Cuando el developer visualiza el apartado de "Book Collection", Entonces el sistema presenta una tabla con los campos de portada, título, autor, género, lenguaje, stock, precio de compra, cantidad y acción. |
| **Acceptance Criteria – Escenario 2: Aumentar stock de un libro de la colección** | Dado que el administrador está visualizando la tabla de "Book Collection" la sección Inventory Y el developer desea aumentar el stock de un libro Cuando el developer completa el campo de Quantity con un número entero Y el developer hace clic en el botón "+" para ese libro, Entonces el sistema cobra el precio de compra multiplicado por la cantidad ingresada, la cual es aumentada al stock del libro seleccionado. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | TS10 |
| **User**                                       | Developer |
| **Priority**                                   | 2 – Should Have |
| **Epic**                                       | EP08: Vista de administrador |
| **Title**                                      | Añadir un libro al inventario |
| **Description**                                | Como developer, quiero agregar un libro nuevo al inventario de Livria, para ampliar el catálogo y aumentar las ventas. |
| **Acceptance Criteria – Escenario 1: Visualizar opción de añadir libro** | Dado que el developer está en la sección Inventory, Cuando el developer visualiza el apartado de "Add a new book to the inventory", Entonces el sistema presenta un formulario con campos a rellenar relacionados con la información del libro. |
| **Acceptance Criteria – Escenario 2: Agregar el nuevo libro al inventario** | Dado que el developer se encuentra en el formulario del apartado de "Add a new book to the inventory", Cuando el developer completa los campos de información del libro como título, género, stock, etc. Y el developer hace clic en el botón "Add new book", Entonces el sistema aumenta ese libro con la información proporcionada al inventario Y el sistema permite visualizarlo en el apartado de "Book Collection". |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | TS11 |
| **User**                                       | Developer |
| **Priority**                                   | 2 – Should Have |
| **Epic**                                       | EP08: Vista de administrador |
| **Title**                                      | Visualización de estadísticas de negocio |
| **Description**                                | Como developer, quiero ver gráficos sobre la gestión del capital y de las ventas para poder manejar mejor las compras de nuevos libros y supervisar las ventas. |
| **Acceptance Criteria – Escenario 1: Visualizar libros más vendidos** | Dado que el developer está en la sección Stadistics, Cuando el developer visualiza el apartado de "Top Three Best Selling Books", Entonces el sistema presenta los 3 libros más vendidos entre todas las compras realizadas por los usuarios. |
| **Acceptance Criteria – Escenario 2: Visualizar ganancias según géneros** | Dado que el developer está en la sección Stadistics, Cuando el developer visualiza el apartado de "Revenue according the genres", Entonces el sistema muestra un gráfico de torta que contiene información sobre las ganancias generadas de acuerdo con cada género literario. |
| **Acceptance Criteria – Escenario 3: Visualizar el flujo de capital** | Dado que el developer está en la sección Stadistics, Cuando el developer visualiza el apartado de "Capital Flow and Operations", Entonces el sistema muestra un gráfico lineal sobre el flujo del capital comparado con las ventas de Livria. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | TS12 |
| **User**                                       | Developer |
| **Priority**                                   | 1 – Must Have |
| **Epic**                                       | EP08: Vista de administrador |
| **Title**                                      | Gestión de la configuración del perfil |
| **Description**                                | Como developer, quiero poder gestionar mi perfil desde una sección de configuración, para poder ver, actualizar mi información personal o cambiar mi contraseña si es necesario. |
| **Acceptance Criteria – Escenario 1: Ver información del perfil** | Dado que el developer se encuentra en la sección Settings, Cuando el developer accede a la pestaña "Profile", Entonces se muestra la información del perfil actual del administrador, incluyendo su nombre, nombre de usuario, correo electrónico y un campo de contraseña. |
| **Acceptance Criteria – Escenario 2: Actualizar la información del perfil** | Dado que el developer está en la sección Settings, Cuando el developer realiza cambios en su nombre, nombre de usuario o correo electrónico, Entonces el sistema permite al administrador guardar los cambios al hacer clic en "Save Changes". |
| **Acceptance Criteria – Escenario 3: Cambiar la contraseña** | Dado que el developer está en la sección Settings, Cuando el developer hace clic en "Change Password", Entonces el sistema permite al developer ingresar y actualizar su contraseña. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | TS13 |
| **User**                                       | Developer |
| **Priority**                                   | 1 – Must Have |
| **Epic**                                       | EP08: Vista de administrador |
| **Title**                                      | Gestión de la configuración de la aplicación |
| **Description**                                | Como developer, quiero gestionar la configuración de la aplicación desde una sección de configuración, para poder activar o desactivar notificaciones, alertas por correo electrónico, autoguardado de cambios y cambiar la configuración de la cantidad de elementos por página. |
| **Acceptance Criteria – Escenario 1: Activar/desactivar notificaciones en la aplicación** | Dado que el developer está en la sección Settings, Y el developer se encuentra en la pestaña "Application", Cuando el administrador marca o desmarca la opción "Receive notifications in the app", Entonces el sistema habilita o deshabilita las notificaciones dentro de la aplicación según la elección del administrador. |
| **Acceptance Criteria – Escenario 2: Activar/desactivar alertas por correo electrónico** | Dado que el developer está en la sección Settings, Y el developer se encuentra en la pestaña "Application", Cuando el developer marca o desmarca la opción "Receive email alerts", Entonces el sistema habilita o deshabilita las alertas por correo electrónico según la elección del administrador. |
| **Acceptance Criteria – Escenario 3: Activar/desactivar auto guardado de cambios** | Dado que el developer está en la sección Settings, Y el developer se encuentra en la pestaña "Application", Cuando el developer marca o desmarca la opción "Automatically save changes", Entonces el sistema habilita o deshabilita el guardado automático de los cambios en la configuración de la aplicación. |
| **Acceptance Criteria – Escenario 4: Configurar el tamaño de página** | Dado que el developer está en la sección Settings, Y el developer se encuentra en la pestaña "Application", Cuando el developer ajusta el número de "Items per page" (por ejemplo, a 5, 10, 20, 50), Entonces el sistema ajusta la cantidad de elementos que se muestran por página según la configuración seleccionada. |
| **Acceptance Criteria – Escenario 5: Guardar los cambios realizados en la configuración** | Dado que el developer ha realizado cambios en las opciones de "Application", Cuando el developer hace clic en "Save Changes", Entonces el sistema guarda los cambios y los aplica inmediatamente a la configuración de la aplicación. |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | TS14 |
| **User**                                       | Developer |
| **Priority**                                   | 2 – Should Have |
| **Epic**                                       | EP08: Vista de administrador |
| **Title**                                      | Barra lateral de navegación en el dashboard del administrador |
| **Description**                                | Como developer, quiero tener una barra lateral en el dashboard que contenga la información fundamental, para poder navegar de forma rápida y eficiente a las diferentes áreas del sistema. |
| **Acceptance Criteria – Escenario 1: Ver secciones principales de navegación** | Dado que el developer se encuentra en el dashboard de la vista de administrador, Cuando el developer dirige su atención la barra lateral, Entonces el sistema muestra accesos directos a las secciones de Home, Books, Orders, Inventory y Stadistics. |
| **Acceptance Criteria – Escenario 2: Ver botón para cambiar el idioma** | Dado que el developer se encuentra en el dashboard de la vista de administrador, Cuando el developer dirige su atención la barra lateral, Entonces el sistema muestra un botón para cambiar el idioma entre "EN" (inglés) y "ES" (español). |
| **Acceptance Criteria – Escenario 3: Ver configuraciones y cerrar sesión** | Dado que el developer se encuentra en el dashboard de la vista de administrador, Cuando el developer dirige su atención la barra lateral, Entonces el sistema muestra un enlace a la sección "Settings" (configuraciones) y un botón para "Log out" (cerrar sesión). |

| Campo                                          | Valor |
|-----------------------------------------------|-------|
| **Story ID**                                   | TS15 |
| **User**                                       | Developer |
| **Priority**                                   | 1 – Must Have |
| **Epic**                                       | EP08: Vista de administrador |
| **Title**                                      | Registro de cuenta con control y seguridad. |
| **Description**                                | Como developer, quiero ingresar a la vista de administrador para poder gestionar operaciones de Livria como el inventario y las ventas. |
| **Acceptance Criteria – Escenario 1: Inicio de sesión exitoso de administrador** | Dado que el developer intenta iniciar sesión en el login de Admin, Cuando el developer rellena los campos del formulario con las credenciales default asignadas, Entonces el sistema valida los datos proporcionados y confirma el inicio de sesión como exitoso. |
| **Acceptance Criteria – Escenario 2: Inicio de sesión inválido** | Dado que el developer intenta iniciar sesión en el login de Admin, Cuando el developer rellena los campos del formulario con credenciales incorrectas o anteriores, Entonces el sistema rechaza el registro y retorna un mensaje de error. |

| Campo | Valor |
|---|---|
| **Story ID** | SS01 |
| **User** | Equipo de desarrollo |
| **Priority** | 2 – Should Have |
| **Epic** | E09: Investigación y Prototipado |
| **Title** | Prototipado de Algoritmo de Recomendación |
| **Description** | Como equipo de desarrollo, quiero investigar y prototipar un algoritmo de recomendación de libros, para que podamos validar la viabilidad técnica y determinar el mejor enfoque para ofrecer sugerencias personalizadas a los usuarios. |
| **Acceptance Criteria – Escenario 1: Investigación de tipos de algoritmos** | Dado que el equipo de desarrollo necesita entender los diferentes tipos de algoritmos de recomendación, Cuando el desarrollador investiga sobre el filtrado colaborativo, basado en contenido y los enfoques híbridos, Entonces el desarrollador documenta en un informe compartido los pros y contras de cada modelo para el contexto de Livria. |
| **Acceptance Criteria – Escenario 2: Investigación de tipos de algoritmos** | Dado que el equipo de desarrollo debe seleccionar la mejor herramienta para el desarrollo, Cuando el desarrollador compara bibliotecas de código abierto (como Apache Mahout) con servicios de IA de terceros (como Google Cloud AI Platform), Entonces el desarrollador propone una solución recomendada basada en costos, escalabilidad y curva de aprendizaje. |
| **Acceptance Criteria – Escenario 3: Investigación de tipos de algoritmos** | Dado que el equipo de desarrollo necesita validar el concepto, Cuando el desarrollador construye un prototipo simple que toma datos de prueba (ej. calificaciones de usuarios) y genera recomendaciones, Entonces el prototipo es funcional y se añade el código de demostración al informe final. |
| **Acceptance Criteria – Escenario 4: Investigación de tipos de algoritmos** | Dado que el algoritmo requiere datos para funcionar, Cuando el desarrollador  identifica qué datos de usuario son esenciales para el sistema, Entonces el desarrollador lista estos campos para su inclusión en la base de datos del proyecto. |

| Campo | Valor |
|---|---|
| **Story ID** | SS02 |
| **User** | Equipo de desarrollo |
| **Priority** | 2 – Should Have |
| **Epic** | E09: Investigación y Prototipado |
| **Title** |  Investigación de Estructura de Comunidades |
| **Description** | Como equipo de desarrollo, quiero investigar las tecnologías y la arquitectura para la sección de comunidad de Livria, para que podamos asegurar un sistema escalable y seguro que gestione las publicaciones y comentarios. |
| **Acceptance Criteria – Escenario 1: Evaluación de arquitecturas de comunidad** | Dado que la comunidad es una funcionalidad central de Livria, Cuando el desarrollador investiga y evalúa diferentes soluciones (ej. APIs REST propias, Firebase Firestore o plataformas de terceros), Entonces el desarrollador propone una arquitectura clara que detalle cómo se manejará el contenido generado por los usuarios. |
| **Acceptance Criteria – Escenario 2: Moderación del contenido de la comunidad** | Dado que el contenido de la comunidad debe ser moderado, Cuando el desarrollador analiza los requisitos para la moderación y las herramientas disponibles (ej. detección de lenguaje ofensivo), Entonces el desarrollador documenta en el informe una estrategia inicial para asegurar un entorno seguro para los usuarios. |
| **Acceptance Criteria – Escenario 3: Identificación de cuellos de botella** | Dado que el sistema debe manejar un alto volumen de interacciones, Cuando el desarrollador identifica los posibles cuellos de botella de rendimiento y escalabilidad (ej. carga de múltiples reseñas en una página), Entonces el desarrollador propone posibles soluciones de optimización, como la paginación o el almacenamiento en caché. |

| Campo | Valor |
|---|---|
| **Story ID** | SS03 |
| **User** | Equipo de desarrollo |
| **Priority** | 2 – Should Have |
| **Epic** | E09: Investigación y Prototipado |
| **Title** | Investigación y Integración de Métodos de Pago |
| **Description** | Como equipo de desarrollo, quiero investigar la integración de una pasarela de pago para la venta de libros y suscripciones, para que podamos entender las implicaciones técnicas, los requisitos de seguridad y el esfuerzo necesario para una implementación completa. |
| **Acceptance Criteria – Escenario 1: Evaluación de plataformas de pago** | Dado que Livria necesita una solución de pagos confiable, Cuando el desarrollador investiga plataformas como Stripe o PayPal, evaluando sus APIs, SDKs y compatibilidad con nuestro stack, Entonces el desarrollador documenta las funcionalidades clave, las tarifas y los requisitos de configuración en un informe. |
| **Acceptance Criteria – Escenario 2: Seguridad de las transacciones** | Dado que se debe garantizar la seguridad de las transacciones, Cuando el desarrollador analiza los requisitos de cumplimiento, la tokenización de datos y el manejo de información sensible en el backend, Entonces el desarrollador incluye en el informe un resumen de los riesgos de seguridad y las estrategias de mitigación. |
| **Acceptance Criteria – Escenario 3: Diagrama del flujo de pagos** | Dado que el equipo necesita entender el flujo de datos, Cuando el desarrollador crea un diagrama que ilustra el proceso de una compra o una suscripción, desde la interfaz de usuario hasta el backend y la pasarela de pago, Entonces el desarrollador incluye este diagrama en el informe para una mejor comprensión. |

| Campo | Valor |
|---|---|
| **Story ID** | SS04 |
| **User** | Equipo de desarrollo |
| **Priority** | 2 – Should Have |
| **Epic** | E09: Investigación y Prototipado |
| **Title** | Prototipado de Gestor de Notificaciones Personalizadas |
| **Description** | Como equipo de desarrollo, quiero investigar y prototipar un gestor de notificaciones que envíe alertas personalizadas a los usuarios, para que podamos validar la infraestructura necesaria para fomentar el hábito de la lectura y la participación en la comunidad. |
| **Acceptance Criteria – Escenario 1: Evaluación de servicios de notificación** | Dado que se deben enviar diferentes tipos de notificaciones, Cuando el desarrollador investiga las APIs y los servicios de mensajería para notificaciones push, correo electrónico y alertas dentro de la aplicación, Entonces el desarrollador propone la mejor plataforma para cada tipo de notificación en el informe. |
| **Acceptance Criteria – Escenario 2: Definición de reglas de personalización** | Dado que las notificaciones deben ser personalizadas, Cuando el desarrollador define las reglas para la activación de las notificaciones (ej. "el usuario no ha leído en 3 días" o "un amigo ha comentado en tu reseña"), Entonces el desarrollador detalla la lógica necesaria en el backend para generar y enviar estas alertas. |
| **Acceptance Criteria – Escenario 3: Validación del flujo de notificaciones** | Dado que el equipo necesita validar el flujo, Cuando el desarrollador crea un prototipo simple que envía una notificación de prueba basada en un evento simulado, Entonces la notificación es recibida correctamente en un dispositivo de prueba y el código se documenta para futuras implementaciones. |

| Campo | Valor |
|---|---|
| **Story ID** | SS05 |
| **User** | Equipo de desarrollo |
| **Priority** | 2 – Should Have |
| **Epic** | E09: Investigación y Prototipado |
| **Title** |  Investigación de Gestión de Libros Físicos y Digitales |
| **Description** | Como equipo de desarrollo, quiero investigar la estructura de datos y el almacenamiento para manejar un catálogo de libros físicos y digitales, para que podamos crear un sistema flexible y escalable que soporte ambos formatos y sus metadatos asociados. |
| **Acceptance Criteria – Escenario 1: Diseño del modelo de datos de libros** | Dado que la plataforma necesita un catálogo unificado, Cuando el desarrollador diseña el esquema de la base de datos para almacenar la información de los libros (ej. autor, género, sinopsis, ISBN, precio, etc.) de forma que sea compatible con ambos formatos, Entonces el desarrollador presenta el modelo de datos en el informe. |
| **Acceptance Criteria – Escenario 2: Almacenamiento de archivos digitales** | Dado que los libros digitales y audiolibros son archivos que deben ser gestionados, Cuando el desarrollador investiga y prototipa el almacenamiento de archivos en la nube para manejar estos activos digitales, Entonces el desarrollador documenta el flujo de carga y acceso a los archivos de forma segura. |
| **Acceptance Criteria – Escenario 3: Poblamiento del catálogo con APIs públicas** | Dado que se necesita poblar el catálogo, Cuando el desarrollador investiga la viabilidad de utilizar APIs de catálogos públicos para enriquecer la información de los libros, Entonces el desarrollador incluye en el informe un plan para la ingestión inicial de datos y la actualización del catálogo. |

