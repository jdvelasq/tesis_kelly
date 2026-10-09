Universidad Nacional de Colombia · Sede Medellín · Facultad de Minas  
**Maestría en Ingeniería – Analítica**

# Inteligencia artificial generativa y agéntica en Learning Analytics y Teaching Analytics: estudio de mapeo sistemático

**Propuesta de trabajo final — versión consolidada v2**  
**Archivo:** `output/propuesta-v2-chatgpt.md`  
**Fecha:** 9 de octubre de 2026  
**Estudiante:** [PENDIENTE] · **Director(a):** [PENDIENTE] · **Codirector(a):** [PENDIENTE]  
**Título en inglés propuesto:** *Generative and Agentic Artificial Intelligence in Learning and Teaching Analytics: A Systematic Mapping Study of Research Themes, Technological Functions, and Evidence Gaps.*

> **Estatus de la evidencia.** Este es un borrador de formulación, no una revisión sistemática concluida. **[PENDIENTE]** señala decisiones, datos o verificaciones futuras; **[POR VALIDAR]** señala afirmaciones derivadas de informes exploratorios. Se integran las propuestas `output/propuesta-chatgpt.md` y `output/propuesta-claude.md` sin asumir que los conteos, categorías o referencias no verificadas son resultados definitivos. La investigación estudia **(GenAI ∪ Agentic AI) ∩ (LA ∪ TA)**: unión dentro de cada eje, intersección entre tecnología y dominio educativo.

## 1. Problema de negocio (o equivalente)

### 1.1. Contexto organizacional y necesidad de decisión

Las instituciones de educación superior, sus docentes, equipos de innovación educativa, responsables de analítica institucional e investigadores enfrentan decisiones sobre qué tecnologías de IA estudiar, implementar y evaluar en la enseñanza y el aprendizaje. *Learning Analytics* (LA) genera conocimiento para comprender y mejorar procesos de aprendizaje; *Teaching Analytics* (TA) se orienta a la práctica, diseño, actuación y decisión docente, con fronteras parcialmente solapadas.

La IA generativa (GenAI) permite, entre otras funciones, generar, resumir, interpretar y transformar contenido. La IA agéntica (*Agentic AI*) remite a sistemas capaces de planificar, utilizar herramientas y ejecutar acciones orientadas a objetivos con distintos niveles de autonomía y supervisión. Una tecnología puede participar en ambas categorías; **no son sinónimos**. Los agentes educativos históricos y los sistemas multiagente tampoco deben confundirse automáticamente con enfoques agénticos recientes.

La abundancia de estudios publicados, la rapidez de su evolución y la inestabilidad terminológica dificultan distinguir tecnologías maduras de prototipos, aplicaciones con evidencia educativa de demostraciones técnicas y áreas consolidadas de oportunidades insuficientemente exploradas. Sin un mapa sistemático de evidencia, las decisiones pueden apoyarse en expectativas, tendencias o etiquetas comerciales más que en resultados contrastables.

### 1.2. Actores, alternativas y valor de información (enfoque INFORMS)

| Actor decisor potencial | Decisión concreta | Información requerida |
|---|---|---|
| Coordinadores y docentes | Priorizar funciones de analítica educativa asistidas por IA | Aplicaciones, contextos y evaluaciones reportadas |
| Unidades TIC, analítica y transformación educativa | Seleccionar prioridades de capacidades y gobernanza | Madurez, riesgos, integración y evidencia |
| Investigadores y programas de posgrado | Definir preguntas, proyectos y recursos de investigación | Temas dominantes, emergentes, redundancias y vacíos |
| Responsables de política educativa | Establecer orientaciones de adopción responsable | Riesgos y mitigaciones documentados |

**Formulación del problema de decisión:**

- **Decisor principal:** [PENDIENTE: escoger y justificar un actor institucional o académico concreto].
- **Decisión:** priorizar líneas de investigación y/o aplicaciones tecnológicas para LA y TA.
- **Alternativas:** funciones y contextos de GenAI, Agentic AI o soluciones híbridas.
- **Estado de la información:** evidencia bibliográfica dispersa, incompleta y heterogénea.
- **Incertidumbre:** pertinencia, evidencia empírica, transferibilidad, limitaciones y grado de autonomía real.
- **Resultado que agrega valor:** un mapa reproducible y trazable que permita distinguir líneas respaldadas, incipientes y poco estudiadas.
- **Costos de decidir sin evidencia:** duplicación de investigación, adopción prematura, sesgos de selección tecnológica, omisión de riesgos.

**Pregunta organizacional:** ¿cómo apoyar decisiones fundamentadas de investigación y adopción de GenAI y Agentic AI para LA y TA cuando la evidencia está dispersa y sus conceptos, aplicaciones y niveles de validación no se encuentran sistemáticamente integrados?

**[PENDIENTE]** Determinar si el decisor privilegiado será un grupo de investigación de la Facultad de Minas, un programa académico u otra unidad. Validar la necesidad real y el producto esperado sin presumir entrevistas o decisiones institucionales ya realizadas.

### 1.3. Criterios de éxito del trabajo

| Indicador | Definición y método | Meta |
|---|---|---|
| Cobertura de búsqueda | Proporción recuperada de un conjunto independiente de estudios semilla pertinentes | [PENDIENTE: umbral y tamaño] |
| Trazabilidad | Proporción de códigos sustantivos respaldados por fragmento o fuente identificable | Objetivo: totalidad de códigos sustantivos |
| Consistencia | Acuerdo entre codificadores para variables nominales y multietiqueta | [PENDIENTE: métrica y umbral después del piloto] |
| Completitud analítica | Preguntas RQ respondidas con evidencia identificable y límites explícitos | Todas las RQ formuladas |
| Utilidad decisional | Valoración del mapa por usuarios académicos/decisores, si se incorpora esta fase | [PENDIENTE: alcance, método y recursos] |
| Difusión | Documento final y manuscrito potencial para IEEE-RITA | Entregables por acordar |

La validación con usuarios es deseable, pero **no se presentará como ejecutada ni obligatoria** mientras no se confirme el alcance del trabajo final.

## 2. Problema de analítica

### 2.1. Traducción analítica

Se busca transformar un conjunto heterogéneo de publicaciones científicas en información estructurada para describir y analizar la investigación sobre GenAI y Agentic AI en LA y TA.

La unidad primaria es el **estudio elegible**, identificado por EID, DOI y reglas complementarias. Un estudio puede recibir varias etiquetas de tecnología, campo, función, actor o aplicación. La pertenencia a un campo se decidirá por criterios sustantivos, no únicamente por coincidencias de palabras.

**Tipo de analítica:** descriptiva, diagnóstica/exploratoria, minería de textos y análisis de evidencia. No se pretende demostrar efectividad causal sobre estudiantes, estimar beneficios económicos de adopción ni construir un sistema agéntico.

### 2.2. Entradas, funciones y resultados

Sea (D) el conjunto de estudios elegibles y (x_d) la información documental disponible de cada estudio (d). El proceso propone una codificación multietiqueta (f_k(x_d)), con reglas y revisión humana, para obtener una matriz documento–faceta (M) y caracterizar:

1. Distribuciones y cambios temporales de campos, temas, tipos de IA y aplicaciones.
2. Relaciones entre tecnología, función, actor, contexto y tipo de evidencia.
3. Grados de validación reportados y diferencias entre enfoques generativos, agénticos e híbridos.
4. Vacíos de evidencia y preguntas futuras derivadas de celdas poco estudiadas.

**Entradas:** metadatos de Scopus, resúmenes, títulos, palabras clave, textos completos cuando sea necesario, registro de cribado y estudios semilla.

**Operaciones:** normalización, deduplicación, cribado, codificación, verificación, tablas de contingencia, análisis temporal, coocurrencia de términos y comunidades temáticas como triangulación; análisis de sensibilidad.

**Salidas:** corpus trazable, libro de códigos, matriz documento–faceta, mapas de evidencia, resultados por pregunta de investigación, agenda de investigación y, opcionalmente, producto ejecutivo para decisores.

### 2.3. Datos disponibles y límites

Dos nuevas exportaciones exploratorias de Scopus reportaron **733** y **781** registros, con **884 documentos únicos en la unión** según el análisis preliminar. Esos registros **no** representan el corpus definitivo ni una estimación de la cantidad de estudios pertinentes. Los informes de partida presentan además filtros y conteos automatizados intermedios diferentes; no se adoptará ninguna de esas cifras como resultado científico sin una auditoría reproducible.

**[POR VALIDAR]** Disponibilidad efectiva de referencias citadas y afiliaciones en las exportaciones. Si faltan, no podrán analizarse acoplamiento bibliográfico, cocitación ni distribuciones por afiliación sin reexportación.

**[PENDIENTE]** Evaluar si se usará una segunda fuente bibliográfica con propósito explícito (validación de cobertura o complemento) y definir la política de una fuente por estudio para evitar atribuciones bibliométricas ambiguas.

### 2.4. Riesgos analíticos y su control

La presencia de *teacher agency* no demuestra un agente de IA; `agent` puede describir tutores clásicos; un LLM no equivale a un sistema autónomo; un dashboard dirigido al profesor no convierte automáticamente un estudio en TA. Se controlarán estas ambigüedades mediante definiciones operacionales, clasificación supervisada y análisis de falsos positivos/negativos.

La carencia de palabras clave o de texto completo restringe algunos métodos. Las conclusiones sobre funciones, autonomía y eficacia deberán proceder de información sustantiva, no de redes bibliométricas.

## 3. Revisión de literatura

### 3.1. Learning Analytics y Teaching Analytics

LA se ha desarrollado como área de investigación sobre datos, procesos y entornos de aprendizaje, incluyendo el apoyo a decisiones docentes (Siemens & Long, 2011; Ferguson, 2012). TA enfatiza aspectos relacionados con la enseñanza, la reflexión y las decisiones del docente; incluye orquestación y análisis multimodal (Prieto et al., 2018; Wise & Jung, 2019; Ndukwe & Daniel, 2020). Existen cruces conceptuales y terminológicos que exigen criterios explícitos de delimitación.

**[PENDIENTE]** Contrastar definiciones oficiales y revisiones primarias para fijar una taxonomía que no equipare LA con «estudiante» ni TA con «dashboard para docente».

### 3.2. GenAI en LA y TA

Entre los antecedentes señalados por los informes figuran trabajos de Khosravi et al. (2023), Yan et al. (2024) y Misiejuk et al. (2025) sobre GenAI en LA. La literatura incluye usos relacionados con análisis de discurso, explicación, evaluación, retroalimentación y soporte a decisiones. En TA se describen tableros docentes, análisis y apoyo al diseño; se necesita identificar qué estudios utilizan efectivamente GenAI para estudiar o apoyar la práctica docente.

**[POR VALIDAR]** Detalles bibliográficos, corpus, alcance y resultados de revisiones identificadas en `output/claude.md`, entre ellas Bayrak Karsli et al. (2025), Cabral et al. (2025), Rodríguez-Ortiz et al. (2025) y Razami et al. (2026).

### 3.3. IA agéntica y antecedentes de agentes educativos

La literatura sobre agentes inteligentes, sistemas multiagente y tutores inteligentes precede a los modelos generativos contemporáneos. El estudio distinguirá: **(i)** agentes históricos relevantes como antecedentes; **(ii)** sistemas contemporáneos con planificación, herramientas y/o ejecución de acciones; **(iii)** sistemas híbridos GenAI–Agentic AI. La mención de *agentic AI* o *LLM agent* en metadatos será una señal de recuperación, no prueba suficiente de capacidades.

**[PENDIENTE]** Identificar y validar revisiones específicas sobre agentes agénticos en educación y determinar qué subgrupo realmente cumple criterios de LA/TA.

### 3.4. Comparación de estudios próximos y brecha potencial

| Línea de antecedentes | Qué estudia | Diferencia que pretende aportar la propuesta |
|---|---|---|
| Revisiones de LA/TA previas a GenAI | Analítica educativa, actores y aplicaciones | Incorporar la transformación tecnológica posterior |
| Revisiones de GenAI en LA | LLM y funciones en aprendizaje | Incorporar explícitamente TA y agencia como ejes no equivalentes |
| Revisiones de Teaching Analytics | Práctica docente y herramientas | Estudiar funciones GenAI/agénticas y validación |
| Revisiones de IA agéntica en educación | Arquitecturas y aplicaciones educativas | Delimitar aplicaciones realmente analíticas en LA/TA |
| Bibliometría general de IA educativa | Tendencias de publicaciones y términos | Extraer funciones y niveles de evidencia de los papers |

**Brecha propuesta:** falta por comprobar si existe un *systematic mapping study* que integre **GenAI ∪ Agentic AI** dentro de **LA ∪ TA**, utilizando una codificación explícita de temas, funciones, contextos, diseños de estudio, validación y vacíos.

**[PENDIENTE CRÍTICO: prueba de originalidad]** Ejecutar una búsqueda formal de *reviews of reviews*, *scoping reviews*, SMS y estudios bibliométricos; verificar publicaciones cercanas, comparar RQ y periodos y registrar una matriz de originalidad. **No afirmar que «no existe» un estudio equivalente antes de terminarla**.

## 4. Discusión: necesidad del estudio y preguntas de investigación

Se plantea un estudio de mapeo, en lugar de una discusión narrativa de «retos y oportunidades», porque la necesidad central es **responder sistemáticamente preguntas sobre la literatura** y producir evidencia trazable. Se investigará la estructura del campo sin presuponer la existencia de convergencia entre TA y LA ni de una comunidad agéntica consolidada.

### Preguntas de investigación

| RQ | Pregunta | Evidencia y producto |
|---|---|---|
| **RQ1** | ¿Cómo evoluciona la producción científica y cuáles son sus temas dominantes y emergentes sobre GenAI y Agentic AI en LA y TA? | Serie temporal, mapas temáticos, codificación temática |
| **RQ2** | ¿Qué tecnologías y capacidades se reportan y cómo se distinguen GenAI, Agentic AI y enfoques híbridos? | Taxonomía funcional, evidencia de agencia, matriz tecnológica |
| **RQ3** | ¿Qué procesos, tareas, actores y aplicaciones de LA y TA estudia la literatura y en qué contextos? | Matriz campo × función × actor × nivel/disciplina |
| **RQ4** | ¿Qué diseños de investigación, formas de evaluación, niveles de validación y limitaciones se reportan? | Clasificación de contribuciones, evidencias, métricas y riesgos |
| **RQ5** | ¿Qué vacíos de investigación y retos prioritarios se derivan de los cruces anteriores? | Evidence gap map y agenda argumentada |

El lugar de publicación, el país y el año funcionarán como variables descriptivas transversales; no requieren una RQ autónoma a menos que el director lo considere necesario. **[PENDIENTE]** Confirmar que las cinco preguntas son respondibles con los datos y textos accesibles tras el piloto.

## 5. Hipótesis

Dada la naturaleza **descriptiva y exploratoria** de un SMS, las hipótesis no son un requisito metodológico universal. La sección incluye **proposiciones de trabajo contrastables**, susceptibles de reformulación con el director antes del preregistro. Derivan parcialmente de observaciones exploratorias y, por ello, no se presentarán como predicciones independientes confirmatorias.

- **H1 (diferenciación tecnológica):** los estudios identificados como GenAI y Agentic AI presentan perfiles funcionales distintos.
- **H2 (diferenciación por campo):** los estudios clasificados como LA y TA presentan distribuciones distintas de objetos analíticos, actores y aplicaciones.
- **H3 (madurez de evidencia):** la validación reportada para sistemas que planifican y ejecutan acciones difiere de la registrada para sistemas centrados en generación, interpretación y clasificación.

**Operacionalización:** frecuencias, proporciones y cruces entre categorías, con análisis de sensibilidad a definiciones y reglas de codificación. No inferir causalidad ni emplear pruebas inferenciales sin un fundamento estadístico adecuado. Los niveles y umbrales concretos de confirmación permanecen **[PENDIENTES]**.

## 6. Objetivo general y objetivos específicos

### Objetivo general

**Caracterizar sistemáticamente la producción científica sobre inteligencia artificial generativa y agéntica aplicada a Learning Analytics y Teaching Analytics, mediante recuperación, clasificación y síntesis reproducible de estudios, para identificar sus temas dominantes y emergentes, funciones tecnológicas, formas de validación y vacíos de investigación, aportando evidencia para orientar prioridades de investigación y adopción educativa.**

### Objetivos específicos

1. **Diseñar y validar** una estrategia de búsqueda y criterios de elegibilidad que recuperen conjuntamente los dos enfoques de IA y los dos dominios de analítica educativa sin exigir intersección interna entre ellos.
2. **Construir y depurar** un corpus reproducible mediante deduplicación y cribado documentados.
3. **Diseñar y validar** un libro de códigos multietiqueta para tecnología, campo, función, tema, actor, contexto, diseño de estudio y nivel de evidencia.
4. **Analizar** la estructura temática y temporal del campo, los perfiles funcionales y la distribución de aplicaciones y validaciones.
5. **Sintetizar** respuestas fundamentadas a las RQ, un mapa de vacíos y una agenda de investigación con implicaciones para decisiones de analítica educativa.

| Objetivo | RQ principal | Producto comprobable |
|---|---|---|
| OE1 | Todas (condición metodológica) | Ecuaciones, estudios semilla, registro de sensibilidad |
| OE2 | Todas (corpus) | Dataset elegible, registro de cribado y PRISMA |
| OE3 | RQ2–RQ4 | Libro de códigos, piloto y acuerdo |
| OE4 | RQ1–RQ4 | Matrices, tablas y mapas |
| OE5 | RQ5 y síntesis | Agenda y documento final |

## 7. Metodología

### 7.1. Diseño metodológico y guías

Se propone un **Systematic Mapping Study (SMS)**, guiado por Petersen, Vakkalanka y Kuzniarz (2015). **PRISMA 2020** orientará el reporte transparente de registros identificados, excluidos e incluidos; **PRISMA-S** la reproducibilidad de las búsquedas. El *Cochrane Handbook* aportará principios complementarios de búsqueda, selección y valoración crítica cuando sean pertinentes. No se plantea metaanálisis ni revisión Cochrane. Puede consultarse PRISMA-ScR por analogía de reporte, sin presentar SMS y *scoping review* como exactamente equivalentes.

### 7.2. Fases

| Fase | Actividad | Producto |
|---|---|---|
| F0 | Revisión de revisiones, preguntas, criterios, protocolo | Protocolo versionado y matriz de originalidad |
| F1 | Búsqueda, validación de sensibilidad, registro y exportación | Registros brutos y log PRISMA-S |
| F2 | Deduplicación, cribado título/resumen y texto completo cuando corresponda | Corpus elegible y diagrama PRISMA |
| F3 | Piloto, libro de códigos y calibración de codificadores | Esquema validado y actas de discrepancias |
| F4 | Extracción, auditoría, análisis descriptivo y temático | Matriz documento–faceta y mapas |
| F5 | Síntesis por RQ, vacíos, implicaciones y limitaciones | Trabajo final |
| F6 | Revisión con director y posible artículo IEEE-RITA | Manuscrito [PENDIENTE: decisión editorial] |

### 7.3. Estrategia de búsqueda

**Universo conceptual:** `(GenAI OR Agentic AI) AND (LA OR TA)`, implementado con sinónimos en Scopus `TITLE-ABS-KEY`. La recuperación contemporánea propuesta comienza en 2022 y termina en la fecha de corte de 2026; los antecedentes históricos de agentes y LA/TA se documentarán separadamente para no confundir historia del campo con la ventana focal.

**Buenas prácticas:**
- Registrar cadenas completas **realmente ejecutadas**, fechas, versiones, filtros y resultados.
- Mantener la unión de ambas familias tecnológicas y educativas.
- Probar expresiones genéricas con muestras de precisión; evitar `teacher agency` sin acotación tecnológica.
- Usar un conjunto de artículos semilla validados para estimar sensibilidad.
- Decidir inclusión de artículos, ponencias, revisiones, capítulos e idiomas por protocolo; no excluir automáticamente conferencias.
- Considerar una búsqueda complementaria en WoS/OpenAlex/ERIC para evaluar cobertura según recursos, sin mezclar metadatos de fuentes incompatibles sin control.

**[PENDIENTE]** Cadena exacta congelada; las propuestas existentes son exploratorias. El anexo final deberá contener la expresión ejecutable íntegra, no abreviaturas como «etc.».

### 7.4. Criterios de elegibilidad

**Incluir:** publicaciones que estudien sustantivamente métodos, aplicaciones, evaluaciones o marcos de GenAI y/o sistemas agénticos ligados a tareas propias de LA y/o TA. Un paper puede aportar a una o varias RQ.

**Excluir:** menciones incidentales, adopción genérica de ChatGPT sin analítica educativa, *agentic engagement* entendido como agencia humana, simples estudios de agentes sin conexión con LA/TA, duplicados o estudios sin información mínima según reglas del protocolo.

**[PENDIENTE]** Tratamiento explícito de preprints, revisiones secundarias, editoriales, agentes históricos y estudios sin texto completo. Evitar excluir trabajos conceptuales si RQ1/RQ2/RQ4 necesitan caracterizar este tipo de contribución.

### 7.5. Extracción y codificación

| Faceta | Valores iniciales (revisables) |
|---|---|
| Campo | LA, TA, ambos, indeterminado |
| Tecnología | GenAI, Agentic AI, híbrida verificada, precursor histórico |
| Función | generar, resumir, clasificar, explicar, recomendar, planificar, usar herramientas, ejecutar/intervenir |
| Tema | evaluación, feedback, autorregulación, aprendizaje personalizado, práctica docente, diseño, orquestación, otros emergentes |
| Actor | estudiante, docente, diseñador, institución |
| Contexto | nivel, disciplina, modalidad, población |
| Contribución | conceptual, prototipo, empírica, revisión, despliegue |
| Evaluación | ninguna reportada, técnica, con usuarios, educativa, campo; métricas concretas |
| Limitaciones | privacidad, sesgo, fiabilidad, gobernanza, autonomía, escalabilidad, otras |
| Evidencia | cita/pasaje, sección/página, decisión de codificación, incertidumbre |

**Regla central:** ningún agente se codificará como «agéntico» solo porque el texto use *agent*, ni se atribuirá efectividad por la presencia de una demostración técnica. Los códigos serán **multietiqueta** y admitirán «no reportado».

### 7.6. Validación y control de calidad

1. Seleccionar muestra piloto estratificada (orientativamente 40–60 documentos; ajustar al tamaño y heterogeneidad real).
2. Dos codificadores independientes cuando sea factible; discutir definiciones y adjudicar discrepancias.
3. Medir acuerdo para categorías nominales y múltiples etiquetas mediante una métrica adecuada, no asumir que kappa simple sirve para todas.
4. Validar sensibilidad de búsquedas con semillas y evaluar precisión del cribado con auditoría humana.
5. Versionar reglas y codificación, guardar evidencia textual y registrar cualquier asistencia de LLM.
6. Ejecutar análisis de sensibilidad (cadenas alternativas, definiciones de TA/Agentic AI, documentos dudosos, fuente e idioma).

**[PENDIENTE]** Número de revisores, nivel mínimo de acuerdo, tamaño final del piloto, software de cribado, política de datos y disponibilidad de textos completos.

### 7.7. Análisis

- **Descriptivo:** años, fuentes, tipos documentales, proporciones y contextos; considerar 2026 un año incompleto.
- **Temático:** coocurrencias de términos, comunidades y evolución, con validación por lectura y códigos temáticos. Opcionalmente modelado de temas sobre resúmenes como contraste, no como verdad de referencia.
- **Funcional y comparativo:** cruces GenAI/Agentic AI × LA/TA × funciones × actores × tipos de validación; evitar doble conteo ingenuo en categorías multietiqueta.
- **Intelectual:** cocitación o acoplamiento únicamente si se exportan referencias citadas apropiadas y si contribuyen efectivamente a alguna RQ.
- **Mapa de evidencia:** celdas con escasos estudios evaluados, diferenciando ausencia observada del corpus de ausencia absoluta de investigación.
- **Reproducibilidad:** scripts versionados; herramientas candidatas Python y tm2+, con bibliometrix/VOSviewer como verificación opcional.

### 7.8. Validez, ética y límites

Amenazas: cobertura exclusiva de Scopus; sesgo lingüístico; crecimiento/indexación de 2026; polisemia de «agente», «agéntico» y TA; sesgo del cribado y codificación; ausencia de datos en abstracts; acceso a texto completo; confusión de evidencia técnica con impacto educativo.

Mitigaciones: conjunto semilla, pruebas de precisión, segunda base si se justifica, definiciones operacionales, doble codificación, auditoría humana y sensibilidad. Respetar restricciones de redistribución de Scopus y copyright de textos; publicar derivados y materiales reproducibles cuando sea legal.

**[PENDIENTE]** Revisar normativa institucional de ética, tratamiento de fuentes licenciadas y declaración del uso de GenAI en investigación y redacción.

## 8. Cronograma

**Cronograma preliminar de 24 semanas (seis meses relativos)**; sujeto a calendario oficial del trabajo final y disponibilidad de dirección.

| Etapa | Semanas | Actividades | Hito |
|---|---|---|---|
| Diseño | 1–3 | Originalidad, RQ, definiciones, protocolo | Protocolo v1 |
| Recuperación | 4–7 | Cadenas, validación, exportación y cribado | Corpus elegible, PRISMA |
| Calibración | 8–10 | Piloto y libro de códigos | Códigos y acuerdo documentados |
| Extracción | 11–15 | Codificación y auditorías | Matriz documento–faceta |
| Análisis | 16–19 | Temas, cruces, vacíos, sensibilidad | Respuestas RQ preliminares |
| Escritura | 20–22 | Discusión, hipótesis, límites, revisión | Documento completo |
| Cierre | 23–24 | Correcciones, reproducibilidad y entrega | Versión final |

**Puntos de decisión:** fin de semana 3: brecha defendible; fin de semana 7: corpus pertinente; semana 10: códigos confiables; semana 19: preguntas respondidas. **[PENDIENTE]** Fechas concretas, responsables, evaluación oficial, recursos, y alcance de un manuscrito para IEEE-RITA.

## 9. Bibliografía preliminar

> Esta lista orienta la próxima revisión; algunas referencias proceden de los informes de partida. Verificar autores, títulos, DOI, pertinencia y texto original antes de considerarlas bibliografía definitiva. No es prueba suficiente de originalidad.

1. Aria, M., & Cuccurullo, C. (2017). Bibliometrix: An R-tool for comprehensive science mapping analysis. *Journal of Informetrics, 11*(4), 959–975. https://doi.org/10.1016/j.joi.2017.08.007
2. Ferguson, R. (2012). Learning analytics: Drivers, developments and challenges. *International Journal of Technology Enhanced Learning, 4*(5/6), 304–317. https://doi.org/10.1504/IJTEL.2012.051816
3. Khosravi, H., Viberg, O., Kovanović, V., & Ferguson, R. (2023). Trabajo sobre GenAI y Learning Analytics. *Journal of Learning Analytics*. https://doi.org/10.18608/jla.2023.8333 **[POR VALIDAR: título exacto]**.
4. Ndukwe, I. G., & Daniel, B. K. (2020). Estudio de revisión sobre Teaching Analytics. *International Journal of Educational Technology in Higher Education*. https://doi.org/10.1186/s41239-020-00201-6 **[POR VALIDAR: datos completos]**.
5. Page, M. J., et al. (2021). The PRISMA 2020 statement: An updated guideline for reporting systematic reviews. *BMJ, 372*, n71. https://doi.org/10.1136/bmj.n71
6. Petersen, K., Vakkalanka, S., & Kuzniarz, L. (2015). Guidelines for conducting systematic mapping studies in software engineering: An update. *Information and Software Technology, 64*, 1–18. https://doi.org/10.1016/j.infsof.2015.03.007
7. Prieto, L. P., et al. (2018). Multimodal teaching analytics: Automated extraction of orchestration graphs from wearable sensor data. *Journal of Computer Assisted Learning, 34*(2), 193–203. https://doi.org/10.1111/jcal.12232
8. Rethlefsen, M. L., et al. (2021). PRISMA-S: An extension to the PRISMA statement for reporting literature searches in systematic reviews. *Systematic Reviews, 10*, 39. https://doi.org/10.1186/s13643-020-01542-z
9. Siemens, G., & Long, P. (2011). Penetrating the fog: Analytics in learning and education. *EDUCAUSE Review*. https://er.educause.edu/articles/2011/9/penetrating-the-fog-analytics-in-learning-and-education
10. Wise, A. F., & Jung, Y. (2019). Teaching with analytics: Towards a situated model of instructional decision-making. *Journal of Learning Analytics, 6*(2), 53–69. https://doi.org/10.18608/jla.2019.62.4
11. Higgins, J. P. T., et al. (eds.). *Cochrane Handbook for Systematic Reviews of Interventions*. https://training.cochrane.org/handbook **[PENDIENTE: edición específica]**.
12. **[PENDIENTE]** Completar y verificar trabajos próximos: Misiejuk et al. (2025); Yan et al. (2024); Bayrak Karsli et al. (2025); Cabral et al. (2025); Rodríguez-Ortiz et al. (2025); Razami et al. (2026); revisiones sobre agentes educativos y Agentic AI.

## Anexo A. Registro de búsqueda (a completar)

**Concepto:** `(GenAI OR Agentic AI) AND (LA OR TA)`.

**[PENDIENTE]** Insertar la cadena Scopus ejecutable **completa y final**; fecha y hora; cuenta/base; filtros de idioma, año y tipo de documento; conteos; estrategia semilla; precisión; sensibilidad; log de cambios. La unión de 884 candidatos es un antecedente exploratorio, no el número definitivo de incluidos.

## Anexo B. Decisiones pendientes prioritarias

1. Definir decisor principal, problema institucional y producto de uso decisional.
2. Completar la *review of reviews* y demostrar la contribución diferencial.
3. Congelar conceptos y reglas GenAI/Agentic AI/LA/TA.
4. Ejecutar y documentar cadena definitiva y decidir una o más bases de datos.
5. Revisar elegibilidad y acceso a texto completo; decidir si las revisiones secundarias pertenecen al mapa o solo a antecedentes.
6. Obtener codificadores, realizar piloto y establecer indicadores de consistencia.
7. Decidir tratamiento institucional de hipótesis exploratorias y preregistro.
8. Ajustar cronograma, modalidad exacta de trabajo final y requisitos UNAL.
9. Verificar bibliografía y condiciones editoriales de IEEE-RITA si se prepara un artículo.

## Anexo C. Criterios de consolidación de la versión 2

Esta versión integra la estructura decisional, indicadores y operacionalización analítica más detalladas de `propuesta-claude.md` con la prudencia en originalidad, validez y formulación de hipótesis de `propuesta-chatgpt.md`. Se consolidaron cinco RQ para evitar fragmentación, se mantuvo la unión tecnológica y educativa, y se descartó presentar como evidencia validada el filtrado automatizado inicial o umbrales de acuerdo arbitrarios. Ambas propuestas de origen quedan intactas.
