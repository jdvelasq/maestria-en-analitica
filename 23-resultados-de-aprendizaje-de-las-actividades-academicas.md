# **Resultados de Aprendizaje de las Actividades Académicas**

Cada asignatura del núcleo disciplinar concreta uno o varios resultados de aprendizaje comunes del programa (sección 14) en un producto evaluable propio. A continuación se describe el propósito de cada asignatura y los resultados que el estudiante debe demostrar al finalizarla.

## **Analítica descriptiva y visualización de datos**

Esta asignatura convierte datos observados en descripciones, diagnósticos e interpretaciones útiles para una decisión de negocio: qué está ocurriendo, para quién, dónde, cuándo y con qué evidencia. Su producto terminal es una descripción o un diagnóstico interpretado para una decisión, con sus métricas, sus visualizaciones, su incertidumbre y sus límites comunicados de forma responsable.

Al finalizar, el estudiante demuestra que puede:

* Formular la pregunta descriptiva de un caso de negocio y las medidas de éxito que orientarán la exploración de los datos, antes de explorarlos.
* Evaluar la calidad de los datos del caso —valores faltantes, atípicos e inconsistencias— y determinar cómo esos problemas limitan lo que la descripción puede afirmar.
* Construir un reporte o tablero que responda la pregunta del caso con métricas y visualizaciones pertinentes para la audiencia, refinando la pregunta inicial con lo observado.
* Estimar, mediante un experimento o un estudio observacional, el efecto de un factor o una intervención sobre un resultado del caso, discutiendo explícitamente los límites de causalidad del diseño elegido.

## **Analítica predictiva**

Esta asignatura construye y valida modelos que anticipan un resultado futuro o no observado de una organización, con su desempeño medido fuera de la muestra de entrenamiento y sus consecuencias de uso documentadas. Su producto terminal es una estimación validada e interpretable, útil para una decisión de negocio, nunca un modelo con buen desempeño técnico sin línea base ni consecuencias de uso evaluadas.

Al finalizar, el estudiante demuestra que puede:

* Formular un problema predictivo con su horizonte, su línea base y el costo de sus errores, y sustentarlo frente al profesor sobre un caso preparado.
* Preparar los datos de un caso predictivo sin fuga de información, con la representación de las variables justificada y sus sesgos y límites documentados.
* Construir y validar un modelo que estime el resultado del caso, con su desempeño medido sobre un conjunto de prueba independiente.
* Seleccionar, entre varias familias de modelo construidas para el caso, la más adecuada, y justificar esa elección frente a su exactitud y su interpretabilidad.
* Interpretar el desempeño, la incertidumbre y las consecuencias de uso de una predicción, y especificar los indicadores con los que se monitorearía en producción para decidir cuándo revisarla.

## **Analítica prescriptiva**

Esta asignatura diseña, valida y gobierna políticas de decisión para decisiones de negocio operativas y recurrentes de una organización: qué acción debe tomarse, bajo qué objetivos y restricciones, con qué salvaguardas, autoridad humana y mecanismo de revisión. Su producto terminal es una política computable y gobernada; un modelo, una frontera de Pareto o una simulación aislados no bastan como entrega final.

Al finalizar, el estudiante demuestra que puede:

* Formular una decisión operativa recurrente de una organización como el contrato completo de una política —su contexto observable, su responsable, su cadencia, sus acciones posibles, sus objetivos y sus restricciones— y sustentarlo ante un panel de interesados hasta obtener su acuerdo.
* Diseñar una política que lleve el contexto observado a una acción factible, y validarla frente a la práctica actual de la organización, a escenarios históricos o simulados y a un análisis de sensibilidad, antes de operarla.
* Establecer la autoridad humana, las salvaguardas, las excepciones y los indicadores de seguimiento de una política, con los umbrales que obligan a revisarla o suspenderla.

## **Analítica de grandes datos**

Esta asignatura lleva la preparación de datos, el modelado y la evaluación a volúmenes, velocidades o variedades de información que exigen cómputo distribuido. Su producto terminal es un análisis ejecutado a escala al servicio de una pregunta analítica explícita, con sus decisiones de partición, costo y tiempo de respuesta justificadas; procesar grandes volúmenes de datos sin una pregunta de negocio que los oriente no constituye, por sí solo, un producto válido.

Al finalizar, el estudiante demuestra que puede:

* Construir un conjunto de datos analítico documentado a partir de fuentes cuyo volumen o variedad superan lo que un solo equipo puede procesar, adaptando sus decisiones de limpieza e integración a esa escala.
* Diseñar un flujo de procesamiento distribuido que prepare los datos de un caso a un volumen que un solo equipo no puede procesar, documentando sus decisiones de partición y paralelización.
* Justificar, para un análisis ejecutado a escala, el costo y el tiempo de respuesta frente a al menos dos alternativas de particionamiento y de recursos de cómputo.

## **Productos de datos**

Esta asignatura convierte una capacidad descriptiva, predictiva o prescriptiva ya validada en un producto reproducible, desplegado, observable, seguro y gobernable para los usuarios de una organización. Su producto terminal es una capacidad analítica versionada, con su contrato operativo —usuarios, decisión de negocio que apoya, entradas, salidas, límites, nivel de servicio y criterios de éxito—, desplegada y monitoreada en producción.

Al finalizar, el estudiante demuestra que puede:

* Llevar una política de decisión ya diseñada a un producto que la ejecute en un proceso de la organización y registre sus resultados para que pueda revisarse.
* Desplegar una capacidad analítica validada como un producto versionado, con su contrato operativo, en un proceso de la organización, y verificar su funcionamiento en producción.
* Validar los datos que alimentan un producto analítico en operación, mediante contratos de datos y pruebas de calidad automatizadas frente al uso operativo previsto.
* Monitorear el desempeño, la calidad de los datos y el uso de un producto analítico en producción, y decidir, con indicadores propios, cuándo recalibrarlo o renovarlo.

## **IA generativa e IA agéntica para analítica**

Esta asignatura especifica, verifica y gobierna el trabajo que asistentes y agentes de inteligencia artificial realizan dentro de un flujo analítico de negocio, siempre al servicio de una pregunta o de un producto analítico ya definido, nunca como fin en sí misma. Su producto terminal es un flujo analítico apoyado por inteligencia artificial, con la tarea delegada especificada y sus resultados verificados y auditados frente a los datos originales; una respuesta de un asistente o un agente sin verificar no constituye, por sí sola, un producto válido.

Al finalizar, el estudiante demuestra que puede:

* Usar un asistente de inteligencia artificial generativa para explorar más a fondo una descripción analítica ya construida y explicar sus hallazgos, verificándolos frente a los datos originales.
* Integrar un agente de inteligencia artificial en la preparación de datos y en la ejecución o la extensión de un modelo predictivo ya construido, documentando qué pasos ejecutó el agente y qué decidió el estudiante.
* Verificar y auditar el código, los datos o los resultados que un agente produce al preparar datos o ejecutar un modelo, corrigiendo los errores y las limitaciones que encuentre antes de aceptarlos.

## **Programas de asignatura**

Los programas de asignatura de cada curso detallarán los contenidos, la dedicación, los instrumentos de evaluación y los criterios de aceptación correspondientes a cada resultado descrito en este capítulo.
