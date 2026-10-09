# Propuesta de trabajo final — Primer borrador

**Programa:** Maestría en Ingeniería – Analítica, Facultad de Minas, Universidad Nacional de Colombia  
**Título tentativo:** *Mapeo sistemático de la investigación sobre inteligencia artificial generativa y agéntica en Learning Analytics y Teaching Analytics*  
**Versión:** 0.1 — 9 de octubre de 2026.  
**Estado:** Borrador de trabajo. **[PENDIENTE]** identifica definiciones, decisiones o evidencia por completar; **[POR VALIDAR]** señala datos preliminares.

## 1. Problema de negocio (o equivalente)

### 1.1. Contexto y necesidad de decisión

Las instituciones universitarias, investigadores, responsables de programas y equipos de innovación docente necesitan decidir qué aplicaciones de inteligencia artificial priorizar, evaluar y adoptar en procesos de enseñanza y aprendizaje. *Learning Analytics* (LA) busca obtener conocimiento accionable sobre los procesos de aprendizaje; *Teaching Analytics* (TA) estudia, entre otros asuntos, prácticas y decisiones docentes. Sus fronteras pueden solaparse y no deben presuponerse excluyentes.

La inteligencia artificial generativa (GenAI) permite producir, sintetizar e interpretar contenido. La inteligencia artificial agéntica (Agentic AI) incorpora capacidades de planificación, empleo de herramientas y ejecución de acciones con distintos grados de autonomía. **No son tecnologías equivalentes**, aunque un mismo sistema puede combinar ambas.

La producción científica es reciente, creciente y heterogénea. Ante la falta de un mapa verificable de qué se investiga, en qué condiciones se evalúa y qué resultados se han demostrado, los decisores enfrentan incertidumbre sobre la madurez tecnológica, la pertinencia de aplicaciones y los vacíos de evidencia. Ello puede conducir a proyectos redundantes, adopciones prematuras y prioridades poco fundamentadas.

### 1.2. Formulación tipo INFORMS: decisión y valor de información

- **Decisores:** investigadores, líderes académicos, diseñadores de tecnologías educativas y docentes.
- **Decisión:** seleccionar prioridades de investigación, evaluación y eventual adopción de tecnologías en LA/TA.
- **Alternativas:** funciones tecnológicas, contextos de aplicación, enfoques de evaluación y líneas de investigación.
- **Información disponible:** registros bibliográficos, metadatos, resúmenes y textos completos elegibles.
- **Incertidumbres:** madurez de las tecnologías, precisión terminológica, calidad de la validación y transferibilidad de resultados.
- **Producto de apoyo decisional:** mapa sistemático y reproducible de temas, funciones, aplicaciones, evidencia y vacíos.
- **Valor esperado:** reducir incertidumbre y mejorar trazabilidad y fundamentación de prioridades; no se estimará una utilidad monetaria sin datos apropiados.

**Problema organizacional:** ¿cómo ofrecer evidencia estructurada para que los actores de la analítica educativa establezcan prioridades fundamentadas de investigación y aplicación de GenAI y Agentic AI en LA y TA?

**[PENDIENTE]** Definir el actor institucional concreto y demostrar la existencia de decisiones reales con información insuficiente. El estudio puede abordar un problema de decisión científico-organizacional sin fingir un patrocinador empresarial.

## 2. Problema de analítica

La necesidad decisional se traduce en un **problema de analítica descriptiva, exploratoria y de minería de textos** sobre producción científica: recuperar, depurar, clasificar y sintetizar evidencia para caracterizar el universo

```
(GenAI OR Agentic AI) AND (Learning Analytics OR Teaching Analytics)
```

La expresión es una **unión en cada eje**, sin exigir que un paper incluya simultáneamente ambas tecnologías ni LA y TA.

### 2.1. Unidad, fuentes y variables

La **unidad de observación primaria** es el estudio científico elegible. Su codificación puede ser **multietiqueta**. Fuentes: Scopus como base principal propuesta; títulos, resúmenes, palabras clave, metadatos, y textos completos cuando sean indispensables. Variables iniciales: año, fuente, LA/TA, GenAI/Agentic AI/híbrido, tema, tarea analítica, actor, contexto, arquitectura, función, autonomía, tipo de estudio, método de evaluación, hallazgos y limitaciones.

### 2.2. Transformaciones y productos

**Pipeline propuesto:** ecuaciones reproducibles → recuperación → deduplicación → cribado → extracción de evidencia → validación de codificación → matrices cruzadas y mapas → respuestas a RQ.

**Salidas:** corpus elegible trazable; libro de códigos; matriz estudio–categoría; evolución temática; cruces tecnología × función × LA/TA × actor × tipo de evidencia; mapa de vacíos; agenda argumentada.

**Calidad:** cobertura frente a estudios semilla, precisión del cribado, consistencia de codificación, trazabilidad a fragmentos fuente, transparencia y análisis de sensibilidad. **[PENDIENTE]** Establecer umbrales y procedimientos de medición en piloto.

Este trabajo **no** plantea construir un agente educativo, entrenar un LLM ni medir experimentalmente mejoras de aprendizaje. Los modelos de lenguaje pueden asistir en el análisis documental bajo auditoría humana.

## 3. Revisión de literatura y originalidad

### 3.1. Campos y antecedentes

LA se consolidó como ámbito de investigación sobre datos y procesos de aprendizaje (Siemens & Long, 2011; Ferguson, 2012). TA incluye enfoques de visualización, reflexión, analítica multimodal, orquestación y toma de decisiones docentes (Prieto et al., 2018; Wise & Jung, 2019; Ndukwe & Daniel, 2020). El destinatario docente de un dashboard no basta por sí solo para clasificar un estudio como TA: se requiere una definición operacional más precisa.

### 3.2. IA generativa y agéntica

Trabajos recientes relacionan GenAI con codificación de interacciones, retroalimentación, interpretación de analítica y apoyo a decisiones (Khosravi et al., 2023; Yan et al., 2024; Misiejuk et al., 2025). Los agentes inteligentes y sistemas multiagente poseen antecedentes anteriores a los LLM. Por eso **Agentic AI no se reduce a GenAI** y tampoco cualquier mención de *intelligent agent* demuestra las capacidades agénticas contemporáneas.

**[PENDIENTE]** Elaborar revisión de antecedentes y de revisiones con textos originales, taxonomías explícitas, DOI verificados, periodización y tabla de trabajos más próximos.

### 3.3. Evidencia preliminar

Las exportaciones exploratorias recientes de Scopus obtenidas mediante dos cadenas propuestas por agentes incluyeron 733 y 781 registros, con 884 registros únicos en su unión según la comparación inicial. Son **registros candidatos**, no estudios pertinentes confirmados. La menor representación explícita de TA y la presencia incipiente de términos agénticos necesitan una revisión de pertinencia y sensibilidad.

**[PENDIENTE]** Conservar consultas exactas, filtros, fechas de descarga, identificadores y protocolo de unión/deduplicación. Auditar de nuevo los conteos desde los archivos fuente.

### 3.4. Brecha de conocimiento

**Hipótesis de originalidad, no hecho demostrado:** podría faltar un *systematic mapping study* que integre la unión tecnológica GenAI–Agentic AI con el universo LA–TA y codifique temas, funciones, diseños de investigación, nivel de evaluación y vacíos a nivel de cada estudio.

**[PENDIENTE CRÍTICO]** Una *review of reviews* que busque sistemáticamente revisiones, *scoping reviews*, mappings y análisis bibliométricos hasta la fecha de corte; matriz de comparación de preguntas, corpus y contribución. **No puede afirmarse que “un estudio así no existe” sin completar esta comprobación.**

## 4. Discusión y preguntas de investigación

Una revisión narrativa de oportunidades y riesgos podría duplicar síntesis existentes. El enfoque de *systematic mapping* pone en primer plano preguntas auditables: qué se estudia, qué función cumplen las tecnologías, qué se evalúa y dónde falta evidencia. El análisis bibliométrico y el *tech mining* serán **complementarios**, no sustitutos de la extracción de información de los papers.

- **RQ1.** ¿Cuáles son los temas dominantes y emergentes de la investigación sobre GenAI y Agentic AI en LA y TA y cómo evolucionan?
- **RQ2.** ¿Qué funciones tecnológicas se estudian y cómo se diferencian operacionalmente los usos generativos, agénticos e híbridos?
- **RQ3.** ¿Qué procesos, actores, datos, decisiones e intervenciones de LA/TA son objeto de estudio?
- **RQ4.** ¿Qué tipos de investigación, contextos, métricas y formas de validación se reportan, y cuáles son sus limitaciones?
- **RQ5.** ¿Qué vacíos aparecen al cruzar tecnologías, funciones, contextos y niveles de evidencia, y qué agenda de investigación se deriva de ellos?

**[PENDIENTE]** Confirmar que la revisión de originalidad no invalida ni duplica las RQ; calibrar el alcance con una muestra piloto.

## 5. Hipótesis

El SMS tiene naturaleza fundamentalmente descriptiva/exploratoria. Si la estructura institucional exige hipótesis, se proponen **proposiciones contrastables**, sin predecir de antemano el resultado:

- **H1:** GenAI y Agentic AI presentan distribuciones temáticas y funcionales diferentes en la literatura elegible.
- **H2:** Los documentos centrados en LA y TA presentan diferencias en objetos de analítica, actores y aplicaciones.
- **H3:** Los sistemas con capacidades verificables de planificación y actuación disponen de una distribución de evidencias de validación distinta a la de sistemas centrados en generar e interpretar contenido.

**Operacionalización:** tablas de contingencia, proporciones por categoría y nivel de validación, análisis temporal y de sensibilidad. Evitar inferencias causales o pruebas de significación injustificadas.

**[PENDIENTE]** Decidir con la dirección si se conservan como hipótesis o se formulan como expectativas exploratorias; predefinir criterios para evaluarlas.

## 6. Objetivos

### Objetivo general

**Caracterizar sistemáticamente la investigación sobre inteligencia artificial generativa y agéntica aplicada a Learning Analytics y Teaching Analytics, mediante una recuperación, clasificación y síntesis reproducibles de publicaciones científicas, para identificar temas dominantes y emergentes, funciones tecnológicas, características de la evidencia y vacíos de investigación.**

### Objetivos específicos

1. Construir y validar un corpus de estudios pertinentes mediante ecuaciones de búsqueda, criterios de elegibilidad, deduplicación y cribado documentados.
2. Diseñar y validar un esquema de codificación multietiqueta que diferencie tecnologías, campos, temas, funciones, actores, contextos y validación.
3. Determinar temas dominantes y emergentes y analizar sus relaciones temporales y funcionales en los subcampos LA/TA.
4. Caracterizar las estrategias de evaluación, el nivel de evidencia y las limitaciones reportadas.
5. Sintetizar un mapa sistemático y una agenda de investigación fundamentada en vacíos observables.

## 7. Metodología

### 7.1. Diseño

**Systematic Mapping Study** (SMS) con codificación de evidencia a nivel de documento. La guía de Petersen, Vakkalanka y Kuzniarz (2015) orienta el mapping. **PRISMA 2020** orientará el reporte de identificación, cribado e inclusión; **PRISMA-S** el de las ecuaciones y fuentes. El *Cochrane Handbook* es apoyo complementario para prácticas de revisión, **sin considerar este trabajo una revisión Cochrane ni un metaanálisis**.

### 7.2. Recuperación

- **Base primaria propuesta:** Scopus; justificar si se usa una sola fuente y registrar sus límites.
- **Concepto booleano:** `(GenAI OR Agentic AI) AND (LA OR TA)`.
- **Vocabularios:** términos de LLM/GenAI, términos de agencia, términos explícitos y funcionales de LA/TA; probar falsos positivos por términos genéricos (*agent*, *teacher dashboard*, etc.).
- **Periodo principal:** 2022–fecha de corte; recuperar por separado antecedentes históricos necesarios para interpretar agentes y analítica educativa.
- **Filtros por idioma/tipo:** **[PENDIENTE]**; no excluir automáticamente conferencias.
- **Validación de ecuaciones:** recuperación de papers semilla y revisión de muestras de inclusiones/exclusiones.

**[PENDIENTE CRÍTICO]** Escribir y congelar la(s) cadena(s) Scopus definitiva(s), fechas, filtros, y documentar revisiones de la estrategia.

### 7.3. Criterios de elegibilidad

**Incluir:** estudios que traten de manera sustantiva GenAI y/o sistemas agénticos en procesos de LA o TA y aporten evidencia al menos a una RQ.  
**Excluir:** menciones incidentales, aplicaciones educativas genéricas sin conexión demostrable con analítica, documentos duplicados o sin información mínima según protocolo.

**[PENDIENTE]** Tratamiento de revisiones secundarias, artículos conceptuales, preprints, agentes históricos, registros sin resumen y falta de texto completo.

### 7.4. Selección y extracción

1. Conservar exportaciones brutas, estrategia exacta y fecha.
2. Deduplicar por EID y DOI, con reglas auxiliares registradas.
3. Cribar título/resumen con criterios previamente definidos.
4. Consultar textos completos para resolver elegibilidad o extraer capacidades, evaluaciones y hallazgos cuando sea necesario.
5. Registrar razones de exclusión y elaborar flujo PRISMA.
6. Codificar estudios incluidos, cada código con evidencia textual y grado de certeza.

### 7.5. Libro de códigos provisional

| Dimensión | Variables iniciales |
|---|---|
| Identificación | EID, DOI, año, fuente, tipo documental |
| Campo | LA, TA, ambos, no determinable |
| Tecnología | GenAI, Agentic AI, híbrida, precursor histórico |
| Capacidades | generación, resumen, clasificación, interpretación, recomendación, planificación, herramientas, ejecución |
| Objeto y actor | aprendizaje, enseñanza, evaluación, diseño, orquestación; estudiante, docente, institución |
| Diseño | conceptual, prototipo, observacional, experimental, evaluación en campo, revisión |
| Evidencia | validación técnica, validación pedagógica, usuarios, métricas, limitaciones, no reportado |
| Contexto | nivel, disciplina, modalidad, población |
| Sustento | pasaje fuente, página/sección, codificador, incertidumbre |

La clasificación admite múltiples etiquetas. **Un LLM no constituye por sí solo un agente**; tampoco el uso de agentes implica GenAI.

### 7.6. Piloto y control de calidad

Realizar un piloto de 40–60 estudios estratificados por años, tecnologías y vocabulario, ajustable según resultados. Calibrar definiciones y criterios de inclusión. Cuando sea posible, usar dos codificadores independientes y conciliación de desacuerdos; estimar acuerdo con métricas acordes al tipo de código. Si interviene un LLM en cribado/extracción, registrar modelo, instrucciones, muestras auditadas y revisión humana.

**[PENDIENTE]** Definir tamaño definitivo del piloto, número de revisores, indicadores y metas de consistencia.

### 7.7. Análisis y síntesis

- **RQ1:** temas, frecuencias y evolución anual; redes de términos como triangulación.
- **RQ2:** matrices tecnología × función; revisión de casos híbridos y de afirmaciones de autonomía.
- **RQ3:** cruces LA/TA × actor × proceso × intervención.
- **RQ4:** evidencia técnica/pedagógica, métodos, contextos, limitaciones.
- **RQ5:** matrices de vacíos y agenda basada en ausencias y concentraciones documentadas.

La falta de publicaciones recuperadas no es prueba directa de que no exista investigación. Los clusters bibliométricos no se convertirán automáticamente en categorías sustantivas.

### 7.8. Reproducibilidad y riesgos

Versionar protocolo, búsquedas, scripts, reglas de selección, libro de códigos, matrices y salidas agregadas; atender licencias de Scopus y de textos completos. Reconocer sesgos de indexación, cobertura, idioma, periodo, clasificación y disponibilidad de documentos. **[PENDIENTE]** Confirmar requisitos éticos e institucionales.

## 8. Cronograma preliminar

**[PROPUESTA]** Plan relativo de 24 semanas, sujeto al calendario y dirección del trabajo final.

| Semanas | Actividades | Entregable |
|---|---|---|
| 1–3 | Revisión de revisiones, originalidad, RQ y protocolo | Protocolo v1 y matriz de brecha |
| 4–7 | Validar búsqueda, exportar, deduplicar y cribar | Corpus candidato, registro PRISMA |
| 8–10 | Piloto, código, consistencia | Libro de códigos validado |
| 11–15 | Extracción y auditoría de todos los estudios elegibles | Matriz estudio–categoría |
| 16–19 | Análisis, síntesis, sensibilidad, respuestas RQ | Resultados |
| 20–22 | Redacción, discusión y revisión | Manuscrito de trabajo final |
| 23–24 | Correcciones y anexos | Entrega definitiva |

**[PENDIENTE]** Fechas reales, responsables, recursos, hitos institucionales y revisión con director(a).

## 9. Bibliografía preliminar

> Referencias metodológicas y sustantivas para iniciar la propuesta; se debe verificar metadatos y pertinencia en fuentes originales y completar la revisión hasta la fecha de corte.

1. Ferguson, R. (2012). Learning analytics: Drivers, developments and challenges. *International Journal of Technology Enhanced Learning*, 4(5/6), 304–317. https://doi.org/10.1504/IJTEL.2012.051816
2. Khosravi, H., Viberg, O., Kovanović, V., & Ferguson, R. (2023). Artículo sobre GenAI y LA. *Journal of Learning Analytics*. https://doi.org/10.18608/jla.2023.8333 **[POR VALIDAR: título y metadatos completos]**.
3. Misiejuk, K., Kaliisa, R., & Scianna, J. (2025). Revisión de GenAI y LA. **[PENDIENTE: referencia y DOI verificados]**.
4. Ndukwe, I. G., & Daniel, B. K. (2020). Artículo sobre Teaching Analytics. *International Journal of Educational Technology in Higher Education*. https://doi.org/10.1186/s41239-020-00201-6 **[POR VALIDAR: título completo]**.
5. Page, M. J., et al. (2021). The PRISMA 2020 statement: An updated guideline for reporting systematic reviews. *BMJ*, 372, n71. https://doi.org/10.1136/bmj.n71
6. Petersen, K., Vakkalanka, S., & Kuzniarz, L. (2015). Guidelines for conducting systematic mapping studies in software engineering: An update. *Information and Software Technology*, 64, 1–18. https://doi.org/10.1016/j.infsof.2015.03.007
7. Prieto, L. P., et al. (2018). Multimodal teaching analytics: Automated extraction of orchestration graphs from wearable sensor data. *Journal of Computer Assisted Learning*, 34(2), 193–203. https://doi.org/10.1111/jcal.12232
8. Rethlefsen, M. L., et al. (2021). PRISMA-S: An extension to the PRISMA statement for reporting literature searches in systematic reviews. *Systematic Reviews*, 10, 39. https://doi.org/10.1186/s13643-020-01542-z
9. Siemens, G., & Long, P. (2011). Penetrating the fog: Analytics in learning and education. *EDUCAUSE Review*. https://er.educause.edu/articles/2011/9/penetrating-the-fog-analytics-in-learning-and-education
10. Wise, A. F., & Jung, Y. (2019). Teaching with analytics: Towards a situated model of instructional decision-making. *Journal of Learning Analytics*, 6(2), 53–69. https://doi.org/10.18608/jla.2019.62.4
11. Higgins, J. P. T., et al. (eds.). *Cochrane Handbook for Systematic Reviews of Interventions*. https://training.cochrane.org/handbook **[POR VALIDAR: versión vigente]**.
12. **[PENDIENTE]** Revisiones sobre GenAI × LA, Agentic AI × educación, TA y estudios SMS/bibliométricos equivalentes.

## Pendientes críticos para la versión definitiva

1. Revisar literatura secundaria exhaustivamente para probar originalidad, no solamente declararla.
2. Congelar ecuaciones Scopus y justificar cobertura del eje Agentic AI sin confundirlo con sistemas históricos genéricos.
3. Definir LA, TA, GenAI y Agentic AI con criterios observables.
4. Formalizar inclusión, exclusión, tratamiento de reviews y prueba de calidad de codificación.
5. Decidir carácter de hipótesis y su evaluación.
6. Concretar decisor organizacional e implicaciones de analítica para la maestría.
7. Verificar todas las referencias y condiciones institucionales.

**Documentos de trabajo relacionados en este repositorio:** `output/chatgpt.md`, `output/claude.md`.
