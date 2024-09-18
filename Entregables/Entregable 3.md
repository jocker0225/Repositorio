> # ENTREGABLE 3
> ### *PROBLEMATICA*
> 
> Contexto

De acuerdo con la Organización Mundial de la Salud (OMS), las lesiones de la médula espinal (LME) tienen una incidencia aproximada de 40 casos por cada 1 millón de habitantes, con una estimación anual de 250,000 a 500,000 personas que sufren este tipo de lesiones en todo el mundo. De estos casos, 1 de cada 20 ocurre por zambullidas mal ejecutadas, como es el caso de nuestro paciente. [1] En Perú, el Instituto Nacional de Rehabilitación (INR) es el único centro a nivel nacional que cuenta con tratamientos especializados para pacientes con LME en hospitalización.[2]
En pacientes con una lesión medular a nivel C6-C7, como el de nuestro caso, la parálisis afecta tanto a las piernas como al tronco, junto con una movilidad limitada en muñecas y manos, pero con movimiento normal en los codos y hombros. [3] Este tipo de lesiones presenta importantes desafíos en la recuperación de la funcionalidad de los miembros superiores, crucial para la independencia en actividades de la vida diaria.


> Definición del problema

El problema específico que buscamos resolver es la recuperación de la funcionalidad de las manos y los dedos en un paciente con lesión medular C6-C7. Aunque el paciente conserva cierta movilidad en las muñecas, carece de la fuerza y el control necesarios para realizar movimientos esenciales como la pinza, la separación de los dedos o el cierre completo de la mano. Estas funciones son fundamentales para que el paciente pueda realizar actividades cotidianas y mejorar su calidad de vida.

> Impacto

 La pérdida de funcionalidad en las extremidades superiores tiene un impacto directo en la vida diaria de las personas con lesión medular, dificultando tareas tan simples como alimentarse, vestirse o escribir. A nivel psicológico, entre el 20% y el 30% de las personas con LME presentan síntomas clínicamente significativos de depresión, y un porcentaje considerable sufre aislamiento social. [4] En términos de salud, las personas con LME están en mayor riesgo de complicaciones prevenibles como infecciones o úlceras de decúbito. Además, el estrés y la carga emocional afectan tanto a los pacientes como a sus cuidadores.
En este contexto, nuestra propuesta es desarrollar un dispositivo de rehabilitación que fortalezca la función de las manos y los dedos, permitiendo al paciente realizar movimientos esenciales como la pinza, separar los dedos y cerrar la mano. La restauración de estas funciones mejoraría significativamente su capacidad de realizar tareas cotidianas, facilitando una mayor independencia y reduciendo el impacto emocional y social asociado a su condición.

Relevancia en Ingeniería Biomédica:

El campo de la ingeniería biomédica tiene un papel clave en el desarrollo de tecnologías que mejoren la rehabilitación y calidad de vida de personas con lesiones medulares. La creación de dispositivos de asistencia o rehabilitación personalizados, como el que se propone aquí, no solo mejora la funcionalidad física del paciente, sino que también impacta en su bienestar psicológico, emocional y social. Al integrar principios de biomecánica, robótica suave y rehabilitación, la ingeniería biomédica tiene el potencial de crear soluciones que ayuden a las personas a recuperar funciones perdidas y a reintegrarse en la vida cotidiana de manera más efectiva.


> ### *PROPUESTA DE SOLUCIÓN*

> 1. Características del prototipo y descripción de la solución:
El guante robótico se diseñó con un enfoque en satisfacer las necesidades específicas de pacientes con movilidad reducida en la mano, especialmente aquellos con lesiones medulares o pérdida de función motora.
#### a. Estimulación Sensorial:
El guante incluye sensores de presión distribuidos en las yemas de los dedos y la palma. Los sensores permiten al paciente sentir la cantidad de fuerza aplicada durante el agarre y soltar objetos, mejorando la conciencia de su propio movimiento y brindando una experiencia más natural durante la rehabilitación. Mejora la percepción táctil y la conciencia de la fuerza, lo que es crucial para el paciente.
#### b. Estabilización dinámica de la muñeca:
El guante está diseñado con una férula integrada que estabiliza la muñeca en una posición ergonómica mientras permite el movimiento de los dedos.
La férula impide que la muñeca se desvíe de su posición óptima, reduciendo la posibilidad de lesiones adicionales o malformaciones durante el uso. Al ser dinámica, permite cierto grado de movilidad sin sacrificar el soporte.
#### c. Ligereza y comodidad:
El diseño liviano asegura que el paciente use el dispositivo durante varias horas, tanto para rehabilitación como para actividades cotidianas, sin generar fatiga muscular o incomodidad. Esenciales para promover el uso constante del guante, lo que es clave para un proceso de rehabilitación rapida.

> 2. Beneficios:
Uno de los principales beneficios del guante robótico es que permite a los usuarios realizar movimientos precisos de agarre y manipulación de objetos.
El guante robótico facilita la autonomía en las actividades diarias. Al mejorar la funcionalidad de la mano, los pacientes pueden realizar tareas que antes eran inalcanzables o que requerían la asistencia de otra persona.
A comparación de otras alternativas como son:
Las férulas solo proporcionan estabilización pasiva y no permiten movimientos de agarre. En cambio, el guante robótico ofrece movilidad activa en los dedos, lo que facilita la ejecución de tareas diarias de manera independiente.
Muchos exoesqueletos de mano son voluminosos y costosos, lo que dificulta su uso cotidiano. El guante robótico propuesto es ligero, portátil y de bajo costo en comparación, lo que lo hace más accesible para una mayor cantidad de usuarios.
En los métodos tradicionales de rehabilitación, los pacientes requieren de terapia física constante, lo que implica un alto costo y tiempo. El guante robótico permite que los usuarios realicen ejercicios de rehabilitación por su cuenta, disminuyendo la necesidad de asistencia constante.
> 3. Viabilidad Técnica:
Para los actuadores en los dedos, se pueden emplear motores eléctricos de bajo peso, como los utilizados en prótesis robóticas. Con la estructura del guante, se utilizará un polímero como es la silicona , que por sus características  son suaves, flexibles y duraderos. Estos materiales dan comodidad al usuario y permiten el uso prolongado sin causar lesiones o incomodidades.
El guante incorpora microcontroladores como el Arduino, que han sido ampliamente utilizados en dispositivos robóticos y son capaces de procesar señales de los sensores de presión y controlar los actuadores. Estos controladores son accesibles, asequibles y programables .
Conocimientos necesarios:
- Control robótico: El desarrollo del software que controle los actuadores y sensores.
- Anatomía básica de la mano y la muñeca, para garantizar que el dispositivo respete la fisiología del paciente.
- Programación básica de microcontroladores para integrar los componentes electrónicos y sensores del dispositivo.

Un ejemplo claro es el guante robótico SoftHand Pro, que ha sido desarrollado para pacientes con discapacidad motora severa. Este guante utiliza actuadores suaves (soft actuators) que permiten movimientos precisos y naturales, combinados con sensores que proporcionan retroalimentación sensorial, lo que mejora la autonomía de los usuarios en actividades diarias .

> ### *COHERENCIA*

> Contexto del proyecto:
> 
La propuesta del exoesqueleto blando es esencial para la rehabilitación de pacientes con lesión medular en C6 y C7, ya que ofrece una solución adaptativa y cómoda para mejorar la movilidad de la mano y facilitar la recuperación funcional. Su diseño permite un ajuste personalizado y la integración de sensores de fuerza, lo que permite un monitoreo preciso del progreso del paciente. Esta solución se alinea con el enfoque de la ingeniería biomédica en el desarrollo de dispositivos médicos innovadores que combinan tecnología avanzada con comodidad, mejorando la rehabilitación y la calidad de vida de los pacientes.

> Objetivos del proyecto:

General : Recrear un guante electronico con fin de rehabilitación física para paciente con movilidad restrigida de manos por lesiones medulares de tipo C6/C7 o pérdida de función motora posibilitando la reinserción al campo laboral.

Especifico: Recuperar la funcionalidad de las manos y los dedos a un plazo no mayor de 1 año.

> Justificación del prototipo:
>
Nuestra propuesta ofrece varias ventajas en comparación con las soluciones revisadas en el estado del arte. En lugar de utilizar un guante, proponemos un exoesqueleto blando que se adapta mejor a la mano del paciente. Esta adaptación permite una mayor precisión durante la rehabilitación, ya que el exoesqueleto blando proporciona una mejor fijación del sensor de fuerza integrado. Este sensor es crucial para monitorear el progreso del paciente y obtener un diagnóstico más preciso sobre la mejora en su agarre. Además, nos centraremos en la rehabilitación de los tres dedos más importantes: el pulgar, el índice y el del medio. Estos dedos son fundamentales para realizar actividades básicas, como agarrar un lápiz o un objeto.
Otra ventaja significativa de nuestra propuesta es el control del exoesqueleto mediante el movimiento de la muñeca. Dado que el paciente no presenta problemas en esta área, podemos evitar el uso del antebrazo, que es común en otros productos para proporcionar estabilidad. Esta decisión no solo simplifica el diseño y reduce los costos, sino que también se alinea mejor con las capacidades funcionales actuales del paciente.


> Alineación con el problema:

El prototipo está diseñado para personas con lesión medular en las vértebras C6 y C7, con el objetivo de rehabilitar la mano y mejorar su movilidad, específicamente en la flexión y extensión. Este exoesqueleto blando permitirá al paciente realizar actividades básicas de manera más independiente, facilitando tareas como agarrar un lápiz o cualquier objeto necesario para su vida diaria y profesional, como en el caso de un abogado. Además, el sensor de fuerza integrado proporcionará información continua sobre el progreso del paciente, ayudando a monitorear y ajustar el proceso de rehabilitación a lo largo del tiempo.

> ### *RESUMEN*

> Recapitulación del problema y solución planteada:

Lesión medular, especialmente del tipo C7, resultado de un zambullido. Resalta en la pérdida parcialmente y temporalmente de la movilidad en las extremidades superiores e inferiores, afectando la capacidad del paciente a realizar actividades diarias o laborales en su caso de Abogado.
Para abordar estos desafios, se propone un guante electrónico que imite los movimientos de los dedos y la mano y facilite en su rehabilitación física de estos. Ofreciendo características de movimiento asistido, sensor de presión y estimulación háptica, estabilizador dinámico de muñeca con características de ser ligero y comodo usando materiales como polimeros y/o textiles tecnicos.

> Resultados deseados:

Se espera que el proyecto obtenga los siguientes resultados:
Mejora en recuperacion de movimientos de la mano y los dedos en mayor relevancia en el agarre.
Rehabilitación funcional ayudando a la reintegracion de actividad diarias.
Monitoreo de progreso por la proporcion de datos a través de sensores que registren la fuerza de flexión de los dedos.
Comodidad y usabilidad por el uso de un diseño ergonomico.
Estimulación neuromuscular en músculos y nervios de la mano, promoviendo la plasticidad neuronal.
Eficiencia del prototipado electronico (Circuito electrónico y componentes electróonicos)

> Siguientes pasos:

Se considera a realizar una metodología de diseño considerando las entradas y salidas de energía, señales y materia de una caja negra. De esta manera se busca hacer un esquema de funciones que realizaría el proyecto como flexión, procesar datos de variables, reguladores de fuerza, ligereza y comodidad, no invasivo y portatil capaz de usarse por largo periodos de tiempo. Luego hacer una matrix morfologica que incluya dispositivos electronicos que vamos a implementar evaluando los conceptos de solución. De la misma manera se seguiría con el modelado 3D, es decir con la estructura optima que agrupe todas las características de solución, es concierne al uso de programas como Autodesk Inventor y para la parte del modelado electronico Proteus y/o ArduinoIDE. Por consiguiente se busca una inmejorable impresion 3D haciendo uso de programas como Cura Multimaker. Finalmente se estarian realizando calculos finales de las variables, revisar el historial de propuestas de soluciones y validando las funciones finales obtenidas para hacer pruebas en un simulacro del paciente para evaluar su eficacia del producto.

> ### *REFERENCIAS BIBLIOGRAFICAS (IEEE)*
> [1] UPCH. “Lesiones de la médula espinal por enfermedades y de causa traumática.” 2024, https://upch.blackboard.com/ultra/courses/_12309_1/outline/file/_670764_1.

> [2] “Instituto Nacional de Rehabilitación brindó cerca de 16 mil 500 atenciones atenciones de enero a mayo 2024.” Instituto Nacional de Rehabilitación brindó cerca
> de 16 mil 500 atenciones atenciones de enero a > mayo 2024, 14 July 2024, https://www.gob.pe/institucion/inr/noticias/988814-instituto-nacional-de-rehabilitacion-
> brindo-cerca-de-16-mil-500-atenciones-atenciones-de-enero-a-mayo-2024. Accessed 16 September 2024.

> [3] Corral López, Irene, et al. “Traumatismo medular.” Manuales Clínicos, https://manualclinico.hospitaluvrocio.es/urgencias-de-traumatologia/patologia-de-cabeza-
> y-tronco/traumatismo-medular/. Accessed 16 September 2024.

> [4] OMS, et al. “Lesiones de la Mèdula Espinal Perspectivas Internacionales.” Untitled, https://iris.who.int/bitstream/handle/10665/131504/WHO_NMH_VIP_13.03_spa.pdf?sequence=1&isAllowed=y.
> Accessed 16 September 2024.

