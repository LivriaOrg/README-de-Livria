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
