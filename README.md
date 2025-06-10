# CoderIA
Introducción: Nombre del proyecto. Asistente Legal Automatizado con IA para analizar la competencia territorial y en razón de la materia de un reclamo. 

Presentación del problema a abordar: En la administración pública, y particularmente en el ámbito de defensa del consumidor, el análisis preliminar de competencia territorial y en razón de la materia constituye un paso esencial para determinar la viabilidad de los reclamos. Sin embargo, realizar esta tarea por personal no jurídico, puede generar errores o demoras en la admisión de los casos. La complejidad normativa —que incluye normas locales, provinciales, nacionales y criterios interpretativos— exige considerar múltiples factores para definir correctamente si un organismo resulta competente. La revisión de estos parámetros es una tarea recurrente y, aunque importante, implica tiempo que podría optimizarse. Automatizar parcialmente esta etapa mediante el uso de modelos de lenguaje permitiría reducir tiempos de respuesta, evitar rechazos o derivaciones erróneas, y mejorar la atención al ciudadano desde el inicio del procedimiento administrativo. 

Desarrollo de la propuesta de solución: El proyecto propone la creación de un sistema de prompts que colabore en el análisis preliminar de viabilidad de los reclamos presentados en materia de consumo, específicamente respecto de la competencia en razón del territorio y de la materia. 

Modelo texto a texto: Se desarrollarán prompts que permitan al modelo emitir una sugerencia razonada sobre la competencia de un organismo en base a los siguientes elementos: 
*Relato del consumidor o resumen del caso. 
*Lugar de celebración del contrato, prestación de servicio o de cumplimiento. 
*Naturaleza del bien o servicio involucrado. 
*Cuerpo normativo aplicable (opcional). 
*Jurisprudencia o antecedentes administrativos (opcional). 

Modelo texto a imagen: Se propone complementar el análisis con elementos visuales que faciliten la comprensión y estandarización de los criterios aplicables, tales como: 
*Esquemas de decisión (tipo árbol): Visualización de criterios para determinar competencia según lugar de prestación del servicio, sede del proveedor, y tipo de bien o servicio. 
*Infografías: Representación de los principales artículos normativos que regulan la competencia, con ejemplos de aplicación práctica. 
*Diagramas de flujo: Secuencia del proceso desde la recepción del reclamo hasta la decisión sobre la admisibilidad por competencia. 
*Mapas visuales: Ámbitos territoriales de actuación de distintos organismos locales, regionales o nacionales. 

Justificación de la viabilidad del proyecto: La propuesta es viable por las siguientes razones: Las reglas de competencia en materia de consumo pueden sistematizarse en criterios comprensibles por modelos de lenguaje, especialmente si se formulan de manera clara y estructurada. Los organismos de defensa del consumidor reciben una gran cantidad de reclamos similares, donde aplicar la misma matriz de análisis permite estandarizar respuestas y reducir el margen de error. Modelos IA pueden interpretar los elementos de un caso, considerar variables normativas y ofrecer respuestas razonadas que sirvan de guía para quienes evalúan la admisibilidad de los reclamos. La incorporación de imágenes y diagramas generados por IA facilita la capacitación del personal no jurídico, al tiempo que mejora la comunicación interna y la toma de decisiones. 

Es una que promueve la eficiencia, seguridad jurídica, y mejora la gestión administrativa desde el primer contacto con el ciudadano. 

Objetivos: Indica los objetivos del proyecto. 

General: Desarrollar un sistema basado en prompts que asista en la evaluación preliminar de la competencia territorial y en razón de la materia en reclamos de defensa del consumidor, permitiendo orientar de manera más eficiente la admisión de los casos. 

Específicos: 

Crear prompts que permitan al modelo identificar y analizar variables jurídicas clave a partir de relatos de casos. 

Reducir errores administrativos relacionados con la admisión de reclamos. 

Mejorar los tiempos de respuesta y la calidad en la atención ciudadana. 

Capacitar a personal no jurídico mediante herramientas visuales generadas por IA que simplifiquen la comprensión de criterios normativos. 

 

Metodología:  

La ejecución del proyecto se estructura en cuatro etapas: 

Relevamiento normativo y procedimental: 

Sistematización de los criterios de competencia (territorial y material) establecidos en la normativa nacional y local aplicable en materia de defensa del consumidor. 

Identificación de casos frecuentes y variables relevantes (por ejemplo, lugar de cumplimiento, tipo de servicio, sede del proveedor). 

Diseño de prompts: 

Elaboración de prompts guía que simulen cómo un operador jurídico consulta al modelo sobre un caso concreto. 

Enfoque en el formato few-shot prompting, donde se introducen ejemplos representativos para guiar la generación del modelo. 

Iteración y testeo: 

Prueba de los prompts con casos reales anonimizados o ficticios. 

Ajuste de los textos para mejorar la precisión y relevancia de las respuestas. 

Desarrollo visual complementario: 

Generación de imágenes (esquemas, diagramas y mapas) mediante IA para su uso como material de apoyo interno y para capacitaciones. 

Justificación: Esta metodología garantiza que el modelo trabaje con criterios jurídicos claros y contextualizados, promoviendo una automatización útil y responsable dentro del proceso administrativo. 

Herramientas y tecnologías:  

Técnica de prompting: Few-shot prompting 

Se utilizará este enfoque porque permite “enseñar” al modelo a razonar como lo haría un operador jurídico, sin necesidad de entrenamiento adicional. 

La inclusión de ejemplos concretos mejora la calidad y coherencia de las respuestas. 

Es especialmente útil en escenarios con estructuras de decisión complejas y múltiples factores, como el análisis de competencia. 

Modelos utilizados: 

Modelos de lenguaje tipo GPT (texto a texto) para analizar relatos de casos. 

Modelos de generación de imágenes (como DALL·E o similares) para crear recursos visuales explicativos. 
