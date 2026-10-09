Universidad Nacional de Colombia · Sede Medellín · Facultad de Minas  
**Maestría en Ingeniería – Analítica**

# Inteligencia artificial generativa y agéntica en Learning Analytics y Teaching Analytics: un estudio de mapeo sistemático (2022–2026)

**Propuesta de trabajo final — versión consolidada**  
**Archivo:** `output/propuesta-consolidada.md`  
**Fecha:** 9 de octubre de 2026 · **Estado:** borrador 0.3 (consolida `propuesta-v2-claude.md` y `propuesta-v2-chatgpt.md`)  
**Estudiante:** [PENDIENTE] · **Director(a):** [PENDIENTE] · **Codirector(a):** [PENDIENTE]  
**Título en inglés propuesto:** *Generative and Agentic Artificial Intelligence in Learning and Teaching Analytics: A Systematic Mapping Study of Research Themes, Technological Functions, and Evidence Gaps.*  
*Título por definir con la dirección.*

> **Convenciones y estatus de la evidencia.** Borrador de formulación, no una revisión concluida. **[PENDIENTE]** = decisión, dato o verificación por completar. **[S]** = verificado en la fuente. **[I]** = inferencia propia por contrastar. **[POR VALIDAR]** = cifra o afirmación de una pasada exploratoria **automatizada** (reglas léxicas sobre título, resumen y palabras clave de exportaciones de Scopus), no de codificación manual; léase como aproximación o cota superior. La investigación estudia **(GenAI ∪ Agentic AI) ∩ (LA ∪ TA)**: unión dentro de cada eje, intersección entre tecnología y dominio educativo; no se exige que un documento trate ambas tecnologías ni ambos campos.

## Contenido

1. Problema de negocio (o equivalente)
2. Problema de analítica
3. Revisión de literatura
4. Discusión: necesidad del estudio y preguntas de investigación
5. Hipótesis
6. Objetivo general y objetivos específicos
7. Metodología
8. Cronograma
9. Bibliografía
- Anexo A. Registro de búsqueda (cadena Scopus propuesta)
- Anexo B. Decisiones y pendientes prioritarios
- Anexo C. Criterios de consolidación

## 1. Problema de negocio (o equivalente)

Como la tesis es de analítica, la sección se formula al estilo INFORMS: contexto de decisión, decisor, alternativas, incertidumbre, valor de la información, costo de decidir sin evidencia y medidas de éxito. El «negocio» es la toma de decisiones sobre qué IA estudiar, adoptar y evaluar en la analítica de la enseñanza y del aprendizaje; no se simula un patrocinador empresarial.

### 1.1 Contexto y necesidad de decisión

Entre 2022 y 2026 la IA generativa (GenAI; modelos de lenguaje grandes, LLM) entró en la analítica del aprendizaje (*Learning Analytics*, LA) y, más recientemente, apareció el discurso de la IA agéntica (*Agentic AI*): sistemas capaces de planificar, usar herramientas y ejecutar acciones orientadas a objetivos con distintos niveles de autonomía y supervisión. **No son sinónimos**, aunque un mismo sistema puede combinar ambas; y los agentes educativos históricos y sistemas multiagente tampoco deben confundirse con enfoques agénticos recientes. La analítica de la enseñanza (*Teaching Analytics*, TA), orientada a la práctica, el diseño y las decisiones del docente, es una subárea más pequeña y de fronteras solapadas con LA [S: Ndukwe & Daniel, 2020; Bayrak Karsli et al., 2025].

La producción es abundante, veloz y terminológicamente inestable. Esto dificulta distinguir tecnologías maduras de prototipos, aplicaciones con evidencia educativa de demostraciones técnicas, y áreas consolidadas de áreas poco exploradas. Sin un mapa sistemático, las decisiones se apoyan en expectativas, tendencias o etiquetas comerciales.

### 1.2 Actores, decisiones e información requerida

| Actor decisor potencial | Decisión concreta | Información requerida |
|---|---|---|
| Coordinadores y docentes (educación superior, énfasis iberoamericano) | Priorizar funciones de analítica educativa asistidas por IA para su enseñanza (TA) y el seguimiento estudiantil (LA) | Aplicaciones, contextos y evaluaciones reportadas; riesgos documentados |
| Unidades TIC, analítica institucional y transformación educativa | Seleccionar capacidades y gobernanza ante GenAI frente a agentes | Madurez real de lo «agéntico» (¿pilotos o conceptos?), tipos de contribución, integración |
| Investigadores y programas de posgrado (incluida esta línea en la UNAL) | Definir preguntas, proyectos, recursos y foros (p. ej., IEEE RITA) | Temas dominantes y emergentes, redundancias, vacíos, producción iberoamericana |
| Responsables de política educativa | Orientaciones de adopción responsable | Riesgos y mitigaciones documentados |

> **PENDIENTE.** Escoger y justificar un decisor principal concreto (grupo de investigación o programa de la Facultad de Minas u otra unidad), y validar la existencia de decisiones reales con información insuficiente. La tabla es una hipótesis de trabajo [I]; no se presume que haya habido entrevistas ni decisiones institucionales previas.

### 1.3 Formulación del problema de decisión

- **Decisor principal:** [PENDIENTE: ver 1.2].
- **Decisión:** priorizar líneas de investigación y/o aplicaciones tecnológicas para LA y TA.
- **Alternativas:** funciones y contextos de GenAI, Agentic AI o soluciones híbridas.
- **Estado de la información:** evidencia bibliográfica dispersa, incompleta y heterogénea.
- **Incertidumbres:** madurez tecnológica, precisión terminológica, calidad de la validación, transferibilidad y grado real de autonomía.
- **Valor de la información:** un mapa reproducible y trazable que distinga líneas respaldadas, incipientes y poco estudiadas. No se estimará una utilidad monetaria sin datos apropiados.
- **Costo de decidir sin evidencia:** (i) invertir en capacidades sin respaldo empírico, (ii) ignorar riesgos documentados, (iii) duplicar investigación en temas saturados dejando otros sin explorar.

**Declaración del problema.** Los decisores de educación superior deben elegir cómo y dónde incorporar IA generativa y agéntica en LA y TA, pero carecen de una síntesis estructurada y actualizada (2022–2026) que distinga entre IA generativa y agéntica, entre analítica centrada en el docente (TA) y en el estudiante (LA), y entre estudios empíricos, marcos conceptuales y opiniones.

**Pregunta organizacional.** ¿Cómo apoyar decisiones fundamentadas de investigación y adopción de GenAI y Agentic AI para LA y TA cuando la evidencia está dispersa y sus conceptos, aplicaciones y niveles de validación no están sistemáticamente integrados?

### 1.4 Medidas de éxito del trabajo

| Indicador | Definición y método | Meta (tentativa, a ratificar) |
|---|---|---|
| Cobertura de búsqueda | Proporción recuperada de un conjunto independiente de estudios semilla pertinentes (benchmark de ≥ 20 estudios verificados [I]) | Umbral y tamaño [PENDIENTE]; referencia ≥ 90 % |
| Trazabilidad | Proporción de códigos sustantivos respaldados por pasaje o fuente identificable | 100 % de los códigos sustantivos |
| Consistencia | Acuerdo entre codificadores por faceta (κ de Cohen por etiqueta o α de Krippendorff; ver 7.7) | Métrica y umbral tras el piloto; referencia κ ≥ 0,70 |
| Completitud analítica | RQ respondidas con evidencia identificable y límites explícitos | 5 de 5 |
| Utilidad decisional | Valoración del mapa por decisores académicos, **si** se incorpora esta fase | [PENDIENTE: alcance, método, recursos] |
| Difusión | Documento final y manuscrito potencial para IEEE RITA | Entregables por acordar |

La validación con usuarios es deseable pero **no se presenta como ejecutada ni obligatoria** mientras no se confirme el alcance del trabajo final.

### 1.5 Restricciones y supuestos

- **Datos:** solo literatura indexada en Scopus en la fase actual; las exportaciones disponibles **no incluyen referencias ni afiliaciones** [S], lo que bloquea acoplamiento bibliográfico, cocitación y análisis por país hasta reexportar.
- **Recursos:** trabajo final de maestría; un investigador principal; herramientas propias (tm2+) y software abierto.
- **Dinamismo:** 2026 está incompleto y el corpus es un objeto en movimiento.
- **Ética:** se trabaja con metadatos bibliográficos, sin datos personales; el uso de IA generativa como apoyo se declara conforme a la política del programa y de la revista [PENDIENTE].

## 2. Problema de analítica

### 2.1 Traducción analítica

Se transforma un conjunto heterogéneo de publicaciones en información estructurada para describir y analizar la investigación sobre GenAI y Agentic AI en LA y TA. **Tipo de analítica:** descriptiva y diagnóstica/exploratoria, con minería de textos y análisis de evidencia; las conclusiones son sobre la **literatura**, no sobre efectos educativos.

**Alcance negativo.** El trabajo **no** construye un agente educativo, no entrena ni ajusta un LLM, no mide experimentalmente mejoras de aprendizaje ni estima beneficios económicos de adopción. Los LLM solo podrán asistir el análisis documental (cribado/extracción) bajo auditoría humana, con registro de modelo, instrucciones y muestras auditadas.

**Unidad de observación.** El **estudio elegible**, identificado por EID, DOI y reglas complementarias, con codificación **multietiqueta** (tecnología, campo, función, actor, aplicación). La pertenencia a un campo se decide por criterios sustantivos, no solo por coincidencia de palabras.

### 2.2 Formulación

Sea *D* el conjunto de estudios elegibles y *x_d* la información documental de cada estudio *d*. Una codificación multietiqueta *f_k(x_d)*, con reglas y revisión humana, produce una matriz documento–faceta *M* con la que se caracterizan:

1. distribuciones y cambios temporales de campos, temas, tipos de IA y aplicaciones;
2. relaciones entre tecnología, función, actor, contexto y tipo de evidencia;
3. grados de validación reportados y diferencias entre enfoques generativos, agénticos e híbridos;
4. vacíos de evidencia y preguntas futuras derivadas de celdas poco estudiadas.

**Entradas:** metadatos de Scopus, títulos, resúmenes, palabras clave, textos completos cuando sea necesario, registro de cribado y estudios semilla. **Operaciones:** normalización, deduplicación, cribado, codificación, verificación, tablas de contingencia, análisis temporal, coocurrencia de términos y comunidades como triangulación, sensibilidad. **Salidas:** corpus trazable, libro de códigos, matriz documento–faceta, mapas de evidencia, resultados por RQ, agenda de investigación y, opcionalmente, producto ejecutivo para decisores (p. ej., tablero en tm2+ [PENDIENTE]).

### 2.3 Datos disponibles y límites

Dos rondas de exportaciones de Scopus, producidas por cadenas sugeridas por dos agentes distintos, constituyen el insumo exploratorio. Las cifras siguientes son **[POR VALIDAR]**: provienen de un script propio (no versionado aún en el repositorio) y de reglas léxicas, y no se adoptan como resultado científico sin una auditoría reproducible.

| Elemento | Resultado exploratorio | Nota |
|---|---|---|
| Exportaciones de la segunda ronda | 733 y 781 registros; **884 únicos** en la unión (por EID) | Registros candidatos, no estudios pertinentes |
| Depuración | 884 → 801 (limpio) → 713 (sin ruido «teacher agency») → 662 (corpus de la primera pasada de mapeo) | Los filtros intermedios difieren entre informes de partida |
| Núcleo LA × GenAI (título o palabras clave del autor) | 323 | Idéntico entre exportaciones |
| TA con frases explícitas | 46 (24 en título/palabras clave); TA ≈ 7 % del corpus | Lente, no red propia |
| IA agéntica propiamente dicha | 19–25 (≈ 3–4 en 2025; 16–21 en 2026) | Mayormente marcos, sistemas y textos conceptuales; ≈ 10 de 25 no mencionan GenAI/LLM |
| «AI agent» / «LLM agent» a secas | ≈ 20 (5 en 2022–2024) | Mezcla con agentes pre-LLM; depurar |
| Composición | ≈ 94 % generativa; ≈ 57 % ponencias; 2026 parcial | |
| Campos | 22 columnas; **sin Referencias ni Afiliaciones** [S] | Reexportar |
| Cobertura de palabras clave | ≈ 34 % de documentos (223) sin palabras clave útiles | Requiere modelado de tópicos sobre resúmenes |

> **PENDIENTE.** Versionar el script y los CSV de cada exportación con fecha, filtros e identificadores; auditar los conteos desde los archivos fuente; decidir si se usa una segunda base (WoS/OpenAlex/ERIC) con propósito explícito (validación de cobertura o complemento) y una política de «una fuente por estudio» para evitar atribuciones bibliométricas ambiguas.

### 2.4 Métodos analíticos

- **Descriptivo:** producción anual, fuentes, tipos documentales; *burst* y puntos de cambio (Kleinberg, 2003); 2026 como año incompleto.
- **Temático:** coocurrencia de palabras con comunidades (Louvain) y evolución por ventanas (Cobo et al., 2011); modelado de tópicos sobre resúmenes (BERTopic/LDA) como contraste, no como verdad de referencia.
- **Funcional y comparativo:** cruces tecnología × campo × función × actor × validación, sin doble conteo ingenuo en categorías multietiqueta; tablas de contingencia con intervalos de confianza.
- **Intelectual:** acoplamiento bibliográfico y cocitación **solo** si se reexporta con referencias y contribuyen a alguna RQ.
- **Mapa de evidencia:** celdas con pocos estudios, distinguiendo ausencia observada en el corpus de ausencia de investigación.
- **Implementación:** Python (pandas, networkx/igraph, scikit-learn, BERTopic) y tm2+, con bibliometrix/VOSviewer como verificación (Aria & Cuccurullo, 2017; van Eck & Waltman, 2010).

### 2.5 Riesgos analíticos y control

*Teacher agency* no demuestra un agente de IA; *agent* puede describir tutores clásicos; un LLM no equivale a un sistema autónomo; un tablero dirigido al docente no convierte automáticamente un estudio en TA; *agentic engagement* suele ser agencia humana. Se controla con definiciones operacionales, clasificación con revisión humana y análisis de falsos positivos/negativos. Las conclusiones sobre funciones, autonomía y eficacia deben proceder de información sustantiva y no de redes bibliométricas. **Calidad:** cobertura frente a semillas, precisión del cribado, consistencia de codificación, trazabilidad a pasajes, transparencia y sensibilidad.

> **PENDIENTE.** Umbrales y procedimientos de medición tras el piloto; formato exacto del producto de decisión y su público.

## 3. Revisión de literatura

Objetivo: mostrar el estado del arte y **argumentar** que, hasta donde se ha verificado, no se identifica un estudio que mapee conjuntamente LA y TA bajo IA generativa *y* agéntica distinguiéndolas. Es una **hipótesis de originalidad**, no un hecho demostrado.

### 3.1 Fundamentos: LA y TA

La LA nace como campo orientado a medir y analizar datos de aprendices para comprender y optimizar el aprendizaje (Siemens & Long, 2011; Ferguson, 2012), con críticas que piden anclarla en el aprendizaje y en la ética (Gašević et al., 2015; Slade & Prinsloo, 2013). La TA desplaza el foco a las decisiones del docente: tableros, *noticing*, orquestación y diseño (Vatrapu et al., 2011; Prieto et al., 2018; Holstein et al., 2019; Wise & Jung, 2019; Mangaroska & Giannakos, 2019). Ndukwe & Daniel (2020) son la revisión de referencia sobre valor y herramientas de TA, y Bayrak Karsli et al. (2025) mapean bibliométricamente la TA sin analizar GenAI. Que el destinatario de un tablero sea el docente **no basta** para clasificar un estudio como TA, ni LA debe equipararse a «estudiante».

> **PENDIENTE.** Contrastar definiciones oficiales y revisiones primarias para fijar una taxonomía operacional de LA y TA (criterios observables).

### 3.2 IA generativa en LA

Los editoriales de *Journal of Learning Analytics* fijaron la agenda (Khosravi et al., 2023; Khosravi et al., 2025) y Yan et al. (2024b) contextualizan oportunidades y desafíos en el ciclo de LA. Misiejuk et al. (2025) es la revisión sistemática de referencia (GenAI en LA; 41 estudios). Rodríguez-Ortiz et al. (2025) revisan ML y GenAI en LA en educación superior (101 identificados; 26 incluidos). Adyacentes: Yan et al. (2024a) sobre desafíos prácticos y éticos de los LLM en educación; Cabral et al. (2025) sobre tableros de LA con IA; Razami et al. (2026) sobre GenAI en LA y apoyo a la decisión (38 estudios); Ivanova & Terzieva (2026) sobre LLM en sistemas educativos inteligentes (80 estudios); Keržič et al. (2026) sobre la evolución bibliométrica de LA hacia enfoques basados en IA; y Rienties et al. (2026) y Claassen et al. (2026) sobre LA, GenAI y decisión/diseño del aprendizaje.

### 3.3 IA generativa en TA

Hay estudios puntuales de tableros docentes con LLM: Wang, Lin y Hu (2025), Yang, Wang y Chen (2025; Chat-LAD), y los preprints de Kim et al. (2024) y Ma et al. (2026). Son estudios de herramienta, no mapas del campo; falta identificar qué estudios usan efectivamente GenAI para estudiar o apoyar la práctica docente.

### 3.4 IA agéntica y antecedentes de agentes educativos

La literatura sobre agentes inteligentes, sistemas multiagente y tutores inteligentes precede a los modelos generativos: **la IA agéntica no se reduce a la generativa**, un LLM no es por sí solo un agente y el uso de agentes no implica GenAI. El estudio distinguirá **(i)** agentes históricos como antecedente, **(ii)** sistemas contemporáneos con planificación, herramientas y/o ejecución de acciones, y **(iii)** sistemas híbridos GenAI–Agentic AI. La mención de *agentic AI* o *LLM agent* en los metadatos es una señal de recuperación, no prueba de capacidades. En la pasada exploratoria los documentos agénticos propios son pocos y mayormente conceptuales [POR VALIDAR]; existen agentes de codificación como apoyo analítico en preprints (Chen et al., 2026). No se identificó revisión sistemática o mapeo de lo agéntico en LA/TA [I].

> **PENDIENTE.** Identificar y validar revisiones sobre agentes/Agentic AI en educación y qué subgrupo cumple criterios de LA/TA.

### 3.5 Comparación de estudios próximos y brecha

| Estudio / línea | LA | TA | GenAI | Agéntica | Tipo / n | Diferencia que aporta esta propuesta |
|---|---|---|---|---|---|---|
| Ndukwe & Daniel, 2020 | sí | sí | no | no | Revisión | Incorpora la transformación tecnológica posterior |
| Bayrak Karsli et al., 2025 | parcial | sí | no | no | Bibliométrico | Incorpora GenAI y agéntica |
| Misiejuk et al., 2025 | sí | no central | sí | no | RSL, 41 | Incorpora TA y distingue agéntica |
| Rodríguez-Ortiz et al., 2025 | sí | no | sí (con ML) | no | RSL, 26 incl. | Amplía más allá de ML en superior |
| Razami et al., 2026 | sí | no | sí | no | RSL, 38 | Estudia funciones, TA y validación |
| Cabral et al., 2025 | tableros | parcial | IA general | no | RSL | Más allá de tableros |
| Ivanova & Terzieva, 2026 | no | no | sí (LLM) | no | RSL, 80 | Delimita lo realmente analítico (LA/TA) |
| Keržič et al., 2026 | sí | no | parcial | no | Bibliométrico | Extrae funciones y niveles de evidencia |
| Revisiones de IA agéntica en educación | — | — | — | sí | por identificar | Delimita aplicaciones analíticas |
| **Esta propuesta** | sí | sí (lente) | sí | sí (distinguida) | Mapeo 2022–2026 | — |

*Las columnas se basan en resúmenes y fichas del informe de investigación; la verificación en texto completo está pendiente [I].*

**Brecha propuesta.** Falta por comprobar si existe un *systematic mapping study* que integre **GenAI ∪ Agentic AI** dentro de **LA ∪ TA**, con codificación explícita de temas, funciones, contextos, diseños, validación y vacíos. Las revisiones identificadas cubren GenAI en LA o TA sin GenAI, pero ninguna de las verificadas distingue lo generativo de lo agéntico ni trata LA y TA en un mismo marco con GenAI. **No puede afirmarse que «un estudio así no existe» antes de completar la prueba de originalidad.**

> **PENDIENTE CRÍTICO (prueba de originalidad).** (a) Búsqueda formal de *reviews of reviews*, *scoping reviews*, SMS y estudios bibliométricos (Scopus, WoS, OpenAlex, ERIC, arXiv) con registro PRISMA-S y matriz de originalidad (RQ, periodo, corpus, contribución); (b) verificar en texto completo Keržič et al. (2026) y Razami et al. (2026); (c) completar LAK 2026 y L@S 2026 (no enumerados); (d) ampliar con literatura iberoamericana (SciELO, Redalyc, LASI/LALA, RITA).

## 4. Discusión: necesidad del estudio y preguntas de investigación

Se justifica un mapeo, y no una discusión narrativa de «retos y oportunidades», porque la necesidad central es **responder sistemáticamente preguntas sobre la literatura** y producir evidencia trazable; un texto de opinión duplicaría editoriales ya existentes (JLA, IJETHE). Cuatro razones sostienen que se requiere el estudio:

- **Magnitud y dinamismo:** cientos de documentos candidatos, con 2026 concentrando una parte importante; ninguna revisión de 2025 puede reflejarlo.
- **Confusión conceptual:** «agente» y «agéntico» se usan con laxitud; hace falta una operacionalización que separe lo generativo de lo agéntico.
- **Desbalance de lentes:** LA domina; TA (≈ 7 %) es periférica justo donde más afectaría la decisión del profesorado [POR VALIDAR].
- **Decisión sin mapa:** los decisores no saben qué es evidencia empírica, qué es marco conceptual y qué es opinión (§1).

La bibliometría y el *tech mining* son **complementarios**, no sustitutos de la extracción de información de los documentos; los clústeres no se convertirán automáticamente en categorías sustantivas. Se investiga la estructura del campo sin presuponer convergencia entre TA y LA ni una comunidad agéntica consolidada.

### 4.1 Preguntas de investigación

| RQ | Pregunta | Evidencia y producto |
|---|---|---|
| **RQ1** | ¿Cómo evoluciona la producción científica (años, fuentes, tipos) y cuáles son sus temas dominantes y emergentes sobre GenAI y Agentic AI en LA y TA? | Serie temporal, co-palabras/tópicos, codificación temática |
| **RQ2** | ¿Qué tecnologías y capacidades se reportan y cómo se distinguen GenAI, Agentic AI y enfoques híbridos? | Taxonomía funcional, evidencia de agencia, matriz tecnológica |
| **RQ3** | ¿Qué procesos, tareas, actores y aplicaciones de LA y TA se estudian, y en qué contextos (nivel, dominio, modalidad)? | Matriz campo × función × actor × nivel/disciplina |
| **RQ4** | ¿Qué tipos de contribución, diseños, formas de evaluación y niveles de validación se reportan, y qué limitaciones y desafíos (fiabilidad, sesgo, privacidad/ética, gobernanza) declaran? | Clasificación de contribuciones, evidencia, métricas y riesgos |
| **RQ5** | ¿Qué vacíos de investigación y retos prioritarios se derivan de los cruces anteriores? | Mapa de vacíos y agenda argumentada |

Lugar de publicación, país y año son variables descriptivas transversales (el país depende de reexportar con afiliaciones), sin RQ autónoma salvo decisión de la dirección. *Equivalencia con la primera versión (7 RQ):* RQ1↔RQ1; RQ2↔RQ2; RQ3 y RQ4 antiguas (foco y funciones)↔RQ1 y RQ3; RQ5 antigua (nivel/dominio)↔RQ3; RQ6 y RQ7 antiguas (contribución y desafíos)↔RQ4.

### 4.2 Por qué las RQ no se responden con la literatura existente

Cada RQ exige una combinación (LA/TA × generativa/agéntica × 2022–2026 × facetas) que no aparece en las revisiones de §3.5. Un mapeo (Petersen et al., 2015) es proporcionado: se describe y localizan vacíos, no se estiman efectos; una revisión de efectividad o un metaanálisis no corresponden.

> **PENDIENTE.** Confirmar con la prueba de originalidad que las RQ no duplican síntesis existentes, y con el piloto (§7.7) que las cinco son respondibles con los datos y textos accesibles. Decidir con el director si el alcance es (i) solo mapeo, o (ii) mapeo más estudio empírico posterior (p. ej., entrevistas a docentes): es la decisión de alcance más importante. Definir si el producto para RITA coincide con un capítulo de la tesis.

## 5. Hipótesis

Un mapeo es esencialmente descriptivo/exploratorio, así que las hipótesis no son un requisito metodológico universal. Se proponen dos niveles, para separar lo que se contrastará de lo que ya sugiere la pasada exploratoria, y se reformularán con la dirección antes del preregistro.

### 5.1 Proposiciones contrastables (sin dirección predicha)

| Id | Proposición | Operacionalización |
|---|---|---|
| H1 (diferenciación tecnológica) | Los estudios GenAI y Agentic AI presentan perfiles temáticos y funcionales distintos. | Tablas de contingencia tecnología × tema/función |
| H2 (diferenciación por campo) | Los estudios LA y TA presentan distribuciones distintas de objetos analíticos, actores y aplicaciones. | Cruces campo × objeto × actor |
| H3 (madurez de evidencia) | La validación reportada para sistemas que planifican y ejecutan acciones difiere de la de sistemas centrados en generar, interpretar o clasificar. | Tecnología × nivel de evidencia/validación |

Operacionalización común: frecuencias, proporciones con intervalos de confianza, análisis temporal y de sensibilidad a definiciones y reglas de codificación. No se infiere causalidad ni se emplean pruebas inferenciales sin fundamento estadístico. Los umbrales concretos de confirmación quedan **[PENDIENTES]**.

### 5.2 Expectativas exploratorias (derivadas de la pasada exploratoria; no confirmatorias)

Formuladas tras ver datos automatizados, se tratan como **expectativas a refutar**, con evaluación definitiva sobre el corpus final codificado manualmente, para limitar el sesgo de formular después de ver los resultados (HARKing).

| Id | Expectativa | Estado preliminar |
|---|---|---|
| E1 | La producción crece de forma sostenida en 2022–2026, con cambio de nivel después de 2023. | Soportada preliminarmente [POR VALIDAR] |
| E2 | La IA agéntica es pequeña (< 10 % del corpus) y se concentra en marcos, sistemas y textos conceptuales con poca evidencia empírica. | 19–25 de ≈ 660 [POR VALIDAR]; contribución sin validar |
| E3 | TA está subrepresentada frente a LA. | ≈ 7 % (46 estrictos) [POR VALIDAR] |
| E4 | Las funciones dominantes son evaluación/retroalimentación, personalización y codificación automática de datos; los tableros docentes con LLM son minoritarios. | Pendiente |
| E5 | Los desafíos más reportados son fiabilidad/alucinación, ética/privacidad y sesgo, con pocos estudios que evalúen mitigaciones. | Pendiente |
| E6 | La producción iberoamericana está subrepresentada. | **Bloqueada** (sin afiliaciones) |
| E7 | Predominan educación superior y dominios STEM/lenguas. | Pendiente |

> **PENDIENTE.** Decidir con la dirección si H1–H3 se conservan como hipótesis o pasan a expectativas; fijar criterios de evaluación **antes** de codificar; preregistrar (OSF); decidir si E6 se mantiene (requiere reexportar con afiliaciones).

## 6. Objetivo general y objetivos específicos

### 6.1 Objetivo general

**Caracterizar sistemáticamente la producción científica 2022–2026 sobre inteligencia artificial generativa y agéntica aplicada a Learning Analytics y Teaching Analytics, mediante recuperación, clasificación y síntesis reproducibles de estudios, para identificar sus temas dominantes y emergentes, funciones tecnológicas, formas de validación y vacíos de investigación, aportando evidencia para orientar prioridades de investigación y adopción educativa.**

### 6.2 Objetivos específicos

1. **Diseñar y validar** una estrategia de búsqueda y criterios de elegibilidad que recuperen conjuntamente los dos enfoques de IA y los dos dominios de analítica sin exigir intersección interna entre ellos, y que distingan GenAI de Agentic AI y TA de LA.
2. **Construir y depurar** un corpus reproducible mediante deduplicación y cribado documentados (PRISMA).
3. **Diseñar y validar** un libro de códigos multietiqueta (tecnología, campo, función, tema, actor, contexto, diseño y nivel de evidencia, desafíos).
4. **Analizar** la estructura temática y temporal del campo, los perfiles funcionales y la distribución de aplicaciones, validaciones y desafíos.
5. **Sintetizar** respuestas fundamentadas a las RQ, un mapa de vacíos y una agenda de investigación con implicaciones para decisiones de analítica educativa, y contrastar H/E.

| Objetivo | RQ principal | Producto comprobable |
|---|---|---|
| OE1 | Todas (condición metodológica) | Ecuaciones, estudios semilla, registro de sensibilidad, recall |
| OE2 | Todas (corpus) | Dataset elegible, registro de cribado, diagrama PRISMA |
| OE3 | RQ2–RQ4 | Libro de códigos, piloto y acuerdo (κ/α) |
| OE4 | RQ1–RQ4 | Matrices, tablas y mapas |
| OE5 | RQ5 y síntesis | Agenda, informe final y, si se decide, manuscrito RITA |

> **PENDIENTE.** Revisar verbos y nivel de taxonomía con la guía de la Maestría, y que OE5 no exceda el alcance de un trabajo final.

## 7. Metodología

### 7.1 Diseño y guías

**Systematic Mapping Study (SMS)** guiado por Petersen et al. (2015), con codificación de evidencia a nivel de documento. **PRISMA 2020** (Page et al., 2021) orienta el reporte de identificación, cribado e inclusión, y **PRISMA-S** (Rethlefsen et al., 2021) el de ecuaciones y fuentes. La extensión **PRISMA-ScR** (Tricco et al., 2018) puede consultarse por analogía de reporte, sin equiparar SMS y *scoping review*. El *Cochrane Handbook* (Higgins et al.) aporta principios complementarios de búsqueda, selección y valoración; **no se plantea revisión Cochrane ni metaanálisis**. La búsqueda es iterativa al estilo Cochrane: cadena sensible, medición de recall frente a semillas, refinamiento documentado. Concepto de tecnología emergente: Rotolo et al. (2015).

### 7.2 Fases

| Fase | Actividad | Producto |
|---|---|---|
| F0. Protocolo | Revisión de revisiones, RQ, criterios, definiciones operacionales; preregistro (OSF) y congelación de hipótesis | Protocolo versionado y matriz de originalidad |
| F1. Búsqueda | Cadena(s) con sensibilidad; reexportación con Referencias y Afiliaciones; segunda base si se justifica; literatura gris/preprints solo como contraste | Registros brutos y log PRISMA-S |
| F2. Cribado | Deduplicación (EID/DOI/título); cribado título-resumen y texto completo cuando corresponda; razones de exclusión | Corpus elegible y diagrama PRISMA |
| F3. Calibración | Piloto, libro de códigos y calibración de codificadores | Esquema validado y actas de discrepancias |
| F4. Extracción y análisis | Codificación multietiqueta con pasaje fuente y certeza; auditoría; análisis descriptivo, temático y funcional | Matriz documento–faceta y mapas |
| F5. Síntesis | Respuestas por RQ, contraste de H/E, vacíos, implicaciones y limitaciones | Informe de trabajo final |
| F6. Difusión | Revisión con el director; posible artículo IEEE RITA | Manuscrito [PENDIENTE: decisión editorial] |

### 7.3 Estrategia de búsqueda

**Universo conceptual:** `(GenAI OR Agentic AI) AND (LA OR TA)` en Scopus `TITLE-ABS-KEY`. Ventana focal: 2022–fecha de corte de 2026; los antecedentes históricos de agentes y de LA/TA se recuperan por separado para no confundir historia del campo con la ventana focal. La cadena propuesta está en el Anexo A.

- Registrar cadenas **realmente ejecutadas**, fechas, versiones, filtros y resultados.
- Mantener la unión de ambas familias tecnológicas y educativas.
- Probar términos genéricos con muestras de precisión. Lecciones documentadas: no usar *agentic** sin acotar (ruido de *agentic engagement*), y **no** añadir *teacher agency* ni *teacher-in-the-loop* a la cadena principal: *teacher agency* introdujo 88 de 801 registros solo recuperables por ese término, en su mayoría estudios de percepción de docentes de inglés sin analítica. Esto corrige una recomendación mía anterior.
- Validar con semillas (sensibilidad) y con revisión de muestras de inclusiones/exclusiones.
- No excluir automáticamente ponencias (≈ 57 % del corpus).
- Considerar WoS/OpenAlex/ERIC para evaluar cobertura, sin mezclar metadatos incompatibles sin control.

### 7.4 Criterios de elegibilidad

| | Inclusión | Exclusión |
|---|---|---|
| Fenómeno | Estudios que traten **sustantivamente** métodos, aplicaciones, evaluaciones o marcos de GenAI y/o sistemas agénticos ligados a tareas de LA y/o TA y aporten evidencia a ≥ 1 RQ | Menciones incidentales; adopción genérica de ChatGPT sin analítica educativa; *agentic engagement* como agencia humana; estudios de agentes sin conexión con LA/TA |
| Contexto | Educación (superior prioritariamente; otros niveles se codifican) | Educación no formal y corporativa, salvo decisión contraria |
| Tipo de documento | Artículo, ponencia, revisión, capítulo | Duplicados o registros sin información mínima según el protocolo |
| Periodo e idioma | 2022–corte; inglés, español, portugués | Otros idiomas (limitación declarada) |

> **PENDIENTE.** Tratamiento de preprints, revisiones secundarias, editoriales (se codifican aparte como «opinión/normativo»), agentes históricos y estudios sin texto completo. No excluir trabajos conceptuales si RQ1, RQ2 o RQ4 necesitan caracterizar ese tipo de contribución.

### 7.5 Libro de códigos provisional

| Faceta | Valores iniciales (revisables) |
|---|---|
| Identificación | EID, DOI, año, fuente, tipo documental |
| Campo | LA, TA, ambos, indeterminado |
| Tecnología | GenAI, Agentic AI, híbrida verificada, precursor histórico |
| Función | generar, resumir, clasificar, explicar, recomendar, planificar, usar herramientas, ejecutar/intervenir |
| Tema | evaluación, retroalimentación, autorregulación, aprendizaje personalizado, práctica docente, diseño, orquestación, codificación de datos, otros emergentes |
| Actor | estudiante, docente, diseñador, institución |
| Contexto | nivel, disciplina, modalidad, población |
| Contribución | conceptual, prototipo/sistema, empírica, revisión, despliegue |
| Evaluación / evidencia | ninguna reportada, técnica, con usuarios, educativa, en campo; métricas concretas |
| Limitaciones y desafíos | fiabilidad/alucinación, sesgo, privacidad/ética, gobernanza, autonomía, escalabilidad/costo, otras |
| Sustento | pasaje, sección/página, decisión de codificación, codificador, certeza |

**Regla central:** ningún sistema se codifica «agéntico» solo porque el texto use *agent*; no se atribuye efectividad por una demostración técnica; los códigos son multietiqueta y admiten «no reportado».

### 7.6 Gestión de datos y análisis

Flujo programado en Python y tm2+, con scripts versionados en el repositorio y semillas fijadas. La pasada exploratoria usó reglas por expresiones regulares y una red de co-palabras con comunidades Louvain; esas reglas pueden servir de clasificador auxiliar, pero la verdad de referencia será la codificación manual. Se respetan las restricciones de redistribución de Scopus y el copyright de los textos; se publican derivados y materiales reproducibles cuando sea legal. Análisis según §2.4.

### 7.7 Piloto y control de calidad

1. Muestra piloto estratificada por año, tecnología y vocabulario (orientativamente 40–60 documentos; ajustable).
2. Dos codificadores independientes cuando sea factible; discusión de definiciones y adjudicación de discrepancias.
3. Acuerdo por faceta con métrica acorde al tipo de código: κ de Cohen (o α de Krippendorff) para nominales y, en multietiqueta, por etiqueta; no asumir que un kappa simple sirve para todo. Referencia tentativa κ ≥ 0,70 por confirmar tras el piloto.
4. Muestra de validación de al menos 20 % doblemente codificada, completando los grupos pequeños (TA estricto y agénticos, ≈ 90 documentos) [I].
5. Validar sensibilidad de la búsqueda con semillas y evaluar la precisión del cribado con auditoría humana.
6. Versionar reglas y codificación, guardar evidencia textual y registrar cualquier asistencia de LLM (modelo, instrucciones, muestras auditadas, revisión humana).
7. Análisis de sensibilidad: cadenas alternativas (escenarios A estricto, B ampliado, C híbrido), definiciones de TA y Agentic AI, documentos dudosos, fuente e idioma.

> **PENDIENTE.** Número de revisores, nivel mínimo de acuerdo, tamaño final del piloto, software de cribado (Rayyan/ASReview), política de datos, disponibilidad de textos completos.

### 7.8 Validez, ética y amenazas

| Amenaza | Mitigación |
|---|---|
| Cobertura exclusiva de Scopus; sesgo de idioma | Segunda base si se justifica; análisis de solapamiento; limitación declarada |
| Ruido léxico («agent», «agentic», TA) | Bloques acotados, definiciones operacionales, revisión manual, reporte de precisión |
| Subjetividad de codificación | Libro de códigos, doble codificación, acuerdo, auditoría |
| Corpus 2026 incompleto / retraso de indexación | Fecha de corte explícita; actualización antes de la sustentación |
| Hipótesis formuladas post hoc | Preregistro y contraste en el corpus final |
| Falta de resumen/texto completo | Registro de incertidumbre y códigos «no reportado» |
| Confundir evidencia técnica con impacto educativo | Faceta de evaluación separada |
| Uso de IA generativa en el propio estudio | Declaración y verificación humana de toda salida |

> **PENDIENTE.** Normativa institucional de ética, tratamiento de fuentes licenciadas y declaración del uso de GenAI en investigación y redacción; si se preregistrará (OSF; PROSPERO suele no aceptar mapeos); fecha de corte final.

## 8. Cronograma

Plan relativo de 24 semanas (seis meses), sujeto al calendario oficial del trabajo final y a la disponibilidad de la dirección.

| Etapa | Semanas | Actividades | Hito |
|---|---|---|---|
| Diseño | 1–3 | Prueba de originalidad, RQ, definiciones, protocolo y preregistro | Protocolo v1, matriz de brecha |
| Recuperación | 4–7 | Validar y congelar búsqueda; exportar con Referencias y Afiliaciones; segunda base; deduplicar y cribar | Corpus elegible, registro PRISMA |
| Calibración | 8–10 | Piloto (40–60), libro de códigos, acuerdo | Códigos y acuerdo documentados |
| Extracción | 11–15 | Codificación y auditoría de todos los estudios elegibles | Matriz documento–faceta |
| Análisis | 16–19 | Análisis bibliométrico y temático, cruces, vacíos, sensibilidad, contraste de H/E | Respuestas preliminares a las RQ |
| Escritura | 20–22 | Discusión, límites y revisión; manuscrito RITA en paralelo | Documento completo |
| Cierre | 23–24 | Correcciones, reproducibilidad, anexos y sustentación | Versión final |

**Puntos de decisión:** fin de la semana 3, brecha defendible; fin de la semana 7, corpus pertinente; semana 10, códigos confiables; semana 19, preguntas respondidas.

**Restricciones de IEEE RITA** [S]: manuscrito original en inglés; 10–16 páginas (costo adicional por página sobre 10); similitud ≥ 25 % implica rechazo; la traducción a español/portugués se hace tras la aceptación. Indexación/cuartil y política de IA generativa: [PENDIENTE].

> **PENDIENTE.** Fechas reales, responsables, recursos, hitos institucionales, evaluación oficial, ciclos de convocatoria de RITA, disponibilidad de codificadores, riesgos y plan de contingencia.

## 9. Bibliografía

> Referencias verificadas en el informe de investigación del repositorio (`output/claude.md`, §12), más tres referencias metodológicas (Petersen, PRISMA-S, Cochrane Handbook) aportadas por ambas versiones y **aún por confirmar** contra la fuente original. Las entradas con datos incompletos se señalan. Esta lista **no es prueba de originalidad**.

- Aria, M., & Cuccurullo, C. (2017). bibliometrix: An R-tool for comprehensive science mapping analysis. *Journal of Informetrics, 11*(4), 959–975. https://doi.org/10.1016/j.joi.2017.08.007
- Bayrak Karsli, M., Cilligol Karabey, S., Kaba, E., Guler, M., Aydemir Arslan, M., & Kursun, E. (2025). Research trends in teaching analytics: Bibliometric mapping and content analysis. *Technology, Knowledge and Learning, 30*(3), 1345–1369. https://doi.org/10.1007/s10758-024-09773-y
- Cabral, L., Pinto, R., & Gonçalves, G. (2025). AI-powered learning analytics dashboards: A systematic review of applications, techniques, and research gaps. *Discover Education, 4*, Article 525. https://doi.org/10.1007/s44217-025-00964-y
- Chen, E., Wang, I., Yuan, N., Judicke, S., Beigh, K., & Tang, X. (2026). *From tool to teammate: LLM coding agents as collaborative partners for behavioral labeling in educational dialogue analysis* [Preprint]. arXiv:2603.27440. https://arxiv.org/abs/2603.27440
- Claassen, A., Ebbert, D., Kovanović, V., Mirriahi, N., & Dawson, S. (2026). Understanding the role of learning analytics and generative artificial intelligence in decision-making and learning design practice in higher education. *International Journal of Educational Technology in Higher Education, 23*(1), Article 43. https://doi.org/10.1186/s41239-026-00619-4
- Cobo, M. J., López-Herrera, A. G., Herrera-Viedma, E., & Herrera, F. (2011). An approach for detecting, quantifying, and visualizing the evolution of a research field. *Journal of Informetrics, 5*(1), 146–166. https://doi.org/10.1016/j.joi.2010.10.002
- Ferguson, R. (2012). Learning analytics: Drivers, developments and challenges. *International Journal of Technology Enhanced Learning, 4*(5/6), 304–317. https://doi.org/10.1504/IJTEL.2012.051816
- Gašević, D., Dawson, S., & Siemens, G. (2015). Let's not forget: Learning analytics are about learning. *TechTrends, 59*(1), 64–71. https://doi.org/10.1007/s11528-014-0822-x
- Higgins, J. P. T., et al. (Eds.). *Cochrane handbook for systematic reviews of interventions*. Cochrane. https://training.cochrane.org/handbook [versión vigente y edición por verificar]
- Holstein, K., McLaren, B. M., & Aleven, V. (2019). Co-designing a real-time classroom orchestration tool to support teacher–AI complementarity. *Journal of Learning Analytics, 6*(2), 27–52. https://doi.org/10.18608/jla.2019.62.3
- Ivanova, & Terzieva. (2026). Large language models in intelligent education systems: New educational perspectives—A systematic review. *Information, 17*(5), Article 433. https://doi.org/10.3390/info17050433 [iniciales por completar]
- Keržič, Aristovnik, & Ravšelj. (2026). A bibliometric analysis of learning analytics evolution in higher education: From traditional to artificial intelligence-based approaches. En *Artificial intelligence in education technologies: New development and innovative practices* (AIET 2025; Vol. 279, pp. 559–575). Springer. https://doi.org/10.1007/978-981-95-4423-3_35 [iniciales por completar]
- Khosravi, H., Shibani, A., Jovanovic, J., Pardos, Z. A., & Yan, L. (2025). Generative AI and learning analytics: Pushing boundaries, preserving principles. *Journal of Learning Analytics, 12*(1), 1–11. https://doi.org/10.18608/jla.2025.8961
- Khosravi, H., Viberg, O., Kovanovic, V., & Ferguson, R. (2023). Generative AI and learning analytics. *Journal of Learning Analytics, 10*(3), 1–6. https://doi.org/10.18608/jla.2023.8333
- Kim, M., Kim, S., Lee, S., et al. (2024). *LLM-driven learning analytics dashboard for teachers in EFL writing education* [Preprint]. arXiv:2410.15025. https://arxiv.org/abs/2410.15025
- Kleinberg, J. (2003). Bursty and hierarchical structure in streams. *Data Mining and Knowledge Discovery, 7*(4), 373–397. https://doi.org/10.1023/A:1024940629314
- Ma, B., Ren, B., Li, H., Li, G., Chen, L., Shimada, A., & Konomi, S. (2026). *Designing a meta-reflective dashboard for instructor insight into student-AI interactions* [Preprint]. arXiv:2603.22674. https://arxiv.org/abs/2603.22674
- Mangaroska, K., & Giannakos, M. (2019). Learning analytics for learning design: A systematic literature review of analytics-driven design to enhance learning. *IEEE Transactions on Learning Technologies, 12*(4), 516–534. https://doi.org/10.1109/TLT.2018.2868673
- Misiejuk, K., López-Pernas, S., Kaliisa, R., & Saqr, M. (2025). Mapping the landscape of generative artificial intelligence in learning analytics: A systematic literature review. *Journal of Learning Analytics, 12*(1), 12–31. https://doi.org/10.18608/jla.2025.8591
- Ndukwe, I. G., & Daniel, B. K. (2020). Teaching analytics, value and tools for teacher data literacy: A systematic and tripartite approach. *International Journal of Educational Technology in Higher Education, 17*, 22. https://doi.org/10.1186/s41239-020-00201-6
- Page, M. J., McKenzie, J. E., Bossuyt, P. M., et al. (2021). The PRISMA 2020 statement: An updated guideline for reporting systematic reviews. *BMJ, 372*, n71. https://doi.org/10.1136/bmj.n71
- Petersen, K., Vakkalanka, S., & Kuzniarz, L. (2015). Guidelines for conducting systematic mapping studies in software engineering: An update. *Information and Software Technology, 64*, 1–18. https://doi.org/10.1016/j.infsof.2015.03.007 [tomada de `propuesta-chatgpt.md`; DOI por confirmar en la fuente]
- Prieto, L. P., Sharma, K., Kidzinski, Ł., Rodríguez-Triana, M. J., & Dillenbourg, P. (2018). Multimodal teaching analytics: Automated extraction of orchestration graphs from wearable sensor data. *Journal of Computer Assisted Learning, 34*(2), 193–203. https://doi.org/10.1111/jcal.12232
- Razami, Singh, Sampedro, Kovilpillai, Raza, Anwar, Hamdan, & Konno. (2026). A systematic review of generative AI in higher education learning analytics and decision support. *Discover Artificial Intelligence*. https://doi.org/10.1007/s44163-026-01888-8 [adelanto en línea; iniciales por completar]
- Rethlefsen, M. L., Kirtley, S., Waffenschmidt, S., et al. (2021). PRISMA-S: An extension to the PRISMA statement for reporting literature searches in systematic reviews. *Systematic Reviews, 10*, 39. https://doi.org/10.1186/s13643-020-01542-z [tomada de `propuesta-chatgpt.md`; autores completos y DOI por confirmar]
- Rienties, B., Divjak, B., & Law, N. (2026). From insight to intervention: Learning analytics and generative AI support for learning design and educational decision-making [Editorial]. *International Journal of Educational Technology in Higher Education, 23*(1), Article 48. https://doi.org/10.1186/s41239-026-00622-9
- Rodríguez-Ortiz, M. Á., Santana-Mancilla, P. C., & Anido-Rifón, L. E. (2025). Machine learning and generative AI in learning analytics for higher education: A systematic review of models, trends, and challenges. *Applied Sciences, 15*(15), 8679. https://doi.org/10.3390/app15158679
- Rotolo, D., Hicks, D., & Martin, B. R. (2015). What is an emerging technology? *Research Policy, 44*(10), 1827–1843. https://doi.org/10.1016/j.respol.2015.06.006
- Siemens, G., & Long, P. (2011). Penetrating the fog: Analytics in learning and education. *EDUCAUSE Review, 46*(5), 30–40. https://er.educause.edu/articles/2011/9/penetrating-the-fog-analytics-in-learning-and-education
- Slade, S., & Prinsloo, P. (2013). Learning analytics: Ethical issues and dilemmas. *American Behavioral Scientist, 57*(10), 1510–1529. https://doi.org/10.1177/0002764213479366
- Tricco, A. C., Lillie, E., Zarin, W., et al. (2018). PRISMA extension for scoping reviews (PRISMA-ScR). *Annals of Internal Medicine, 169*(7), 467–473. https://doi.org/10.7326/M18-0850
- van Eck, N. J., & Waltman, L. (2010). Software survey: VOSviewer, a computer program for bibliometric mapping. *Scientometrics, 84*(2), 523–538. https://doi.org/10.1007/s11192-009-0146-3
- Vatrapu, R., Teplovs, C., Fujita, N., & Bull, S. (2011). Towards visual analytics for teachers' dynamic diagnostic pedagogical decision-making. En *Proceedings of LAK '11* (pp. 93–98). ACM. https://doi.org/10.1145/2090116.2090129
- Wang, Z., Lin, W., & Hu, X. (2025). Self-service teacher-facing learning analytics dashboard with large language models. En *Proceedings of LAK 2025* (pp. 824–830). ACM. https://doi.org/10.1145/3706468.3706491
- Wise, A. F., & Jung, Y. (2019). Teaching with analytics: Towards a situated model of instructional decision-making. *Journal of Learning Analytics, 6*(2), 53–69. https://doi.org/10.18608/jla.2019.62.4
- Yan, L., Martinez-Maldonado, R., & Gašević, D. (2024b). Generative artificial intelligence in learning analytics: Contextualising opportunities and challenges through the learning analytics cycle. En *Proceedings of LAK '24* (pp. 101–111). ACM. https://doi.org/10.1145/3636555.3636856
- Yan, L., Sha, L., Zhao, L., et al. (2024a). Practical and ethical challenges of large language models in education: A systematic scoping review. *British Journal of Educational Technology, 55*(1), 90–112. https://doi.org/10.1111/bjet.13370
- Yang, C., Wang, D., & Chen, G. (2025). Chat-LAD: Enhancing teacher understanding of learning analytics dashboard with AI-empowered explanations. En *Proceedings of L@S 2025* (pp. 197–201). ACM. https://doi.org/10.1145/3698205.3733922 [método y resultados por verificar]

> **PENDIENTE.** Verificar Petersen (2015), PRISMA-S y Cochrane Handbook contra las fuentes originales; incorporar la guía de IEEE RITA y, opcionalmente, Kitchenham. Bibliografía iberoamericana (LASI, LALA, RITA, Scielo/Redalyc) por construir. Completar iniciales de autores donde falten.

## Anexo A. Registro de búsqueda (cadena Scopus propuesta)

**Concepto:** `(GenAI OR Agentic AI) AND (LA OR TA)`.

Cadena **propuesta** (diseño final tras la segunda ronda). Las exportaciones exploratorias se obtuvieron con las cadenas de los dos agentes; esta versión única **no ha sido ejecutada** en esta forma, por lo que no hay conteo asociado.

```
TITLE-ABS-KEY(
  ("learning analytic*" OR "multimodal learning analytic*" OR "learning dashboard*"
   OR "teaching analytic*" OR "teacher analytic*" OR "teacher-facing analytic*"
   OR "teacher-facing dashboard*" OR "instructor analytic*" OR "instructor dashboard*"
   OR "educator analytic*" OR "pedagogical analytic*" OR "teaching and learning analytic*"
   OR "teacher dashboard*" OR "teaching dashboard*" OR "instructor-facing"
   OR "teacher noticing" OR "classroom orchestration" OR "learning design analytic*"
   OR "analítica del aprendizaje" OR "analítica de la enseñanza" OR "analítica docente")
  AND
  (
   ("generative AI" OR "generative artificial intelligence" OR genai OR chatgpt
    OR "GPT-3*" OR "GPT-4*" OR "large language model*" OR llm OR llms OR "foundation model*"
    OR "generative language model*" OR "AI chatbot*" OR "generative pre-trained transformer*"
    OR "multimodal large language model*" OR aigc
    OR "IA generativa" OR "inteligencia artificial generativa" OR "inteligência artificial generativa")
   OR
   ("agentic AI" OR "agentic artificial intelligence" OR "agentic system*" OR "agentic workflow*"
    OR "agentic framework*" OR "agentic architecture*" OR "agentic RAG" OR "agentic LLM*"
    OR "AI agent*" OR "LLM agent*" OR "LLM-based agent*"
    OR "IA agéntica" OR "inteligencia artificial agéntica" OR "agentes de IA")
  )
)
AND PUBYEAR > 2021 AND PUBYEAR < 2027
AND DOCTYPE(ar OR cp OR re OR ch)
AND LANGUAGE(english OR spanish OR portuguese)
```

Notas: se retiraron *teacher agency* y *teacher-in-the-loop* (ruido). Los términos de TA en español devolvieron 0 registros. El bloque agéntico debe guardarse como conjunto aparte para separar grupos. **[PENDIENTE]** Ejecutar y registrar fecha y hora, base y cuenta, conteos, estrategia semilla, precisión, sensibilidad y registro de cambios; la unión de 884 candidatos es un antecedente exploratorio, no el número de incluidos.

## Anexo B. Decisiones y pendientes prioritarios

1. **Alcance:** solo mapeo vs mapeo + estudio empírico; título definitivo; si el manuscrito RITA es un capítulo de la tesis.
2. **Decisor y producto:** definir decisor principal, problema institucional y producto de uso decisional (tablero en tm2+, informe).
3. **Originalidad:** completar la *review of reviews* y demostrar la contribución diferencial; verificar en texto completo Keržič et al. (2026) y Razami et al. (2026).
4. **Definiciones:** congelar conceptos y reglas de GenAI, Agentic AI, LA y TA con criterios observables.
5. **Búsqueda:** ejecutar y documentar la cadena definitiva; segunda base; reexportar con Referencias y Afiliaciones (desbloquea acoplamiento, cocitación y país/E6).
6. **Elegibilidad:** revisiones secundarias, preprints, agentes históricos, acceso a texto completo.
7. **Codificación:** codificadores, piloto, métricas y umbral de acuerdo; muestra ≥ 20 % doblemente codificada; TA estricto (46) y agénticos (≈ 45) completos; tópicos sobre resúmenes (≈ 34 % sin palabras clave).
8. **Reproducibilidad:** versionar script y exportaciones del corpus exploratorio; auditar los conteos.
9. **Hipótesis:** estatus de H1–H3 y E1–E7; criterios antes de codificar; preregistro.
10. **Institucional:** cronograma oficial, sustentación, evaluadores, reglamento de la Maestría, ética y política de uso de GenAI de la UNAL.
11. **RITA:** indexación/cuartil y política de IA generativa; completar LAK 2026 y L@S 2026; literatura iberoamericana.
12. **Bibliografía:** confirmar Petersen (2015), PRISMA-S y Cochrane Handbook; completar iniciales de autores.

## Anexo C. Criterios de consolidación

Esta versión unifica `propuesta-v2-claude.md` y `propuesta-v2-chatgpt.md`; las dos quedan intactas. Decisiones principales:

- **Base:** la estructura común de ambas (9 secciones). En la sección 1 se unen la tabla de actores y los costos de decidir sin evidencia, con los indicadores de éxito de ambas (trazabilidad, completitud, cobertura).
- **Datos:** se conservan los conteos del corpus (v2-claude), pero etiquetados **[POR VALIDAR]** y con la advertencia de que los filtros intermedios difieren entre informes y de que el script aún no está versionado (cautela de v2-chatgpt).
- **RQ:** se adoptan **cinco** (v2-chatgpt) para evitar fragmentación; las siete originales se reasignan (§4.1) y desafíos, nivel/dominio y país se absorben como facetas y variables transversales.
- **Hipótesis:** H1–H3 sin dirección (ambas) más expectativas exploratorias E1–E7 (v2-claude) separadas y declaradas como no confirmatorias.
- **Originalidad:** se mantiene como hipótesis con prueba pendiente crítica; se corrige el encabezado de §3 de v2-claude, que afirmaba «no existe».
- **Metodología:** libro de códigos fusionado, piloto de 40–60, métricas de acuerdo por faceta (κ o α), análisis de sensibilidad A/B/C y lección sobre *teacher agency*.
- **Anexo A:** cadena Scopus completa y ejecutable (la de v2-claude estaba abreviada), declarada como propuesta no ejecutada.
- **Bibliografía:** la verificada de v2-claude; se descartan las entradas con metadatos incompletos o atribuidos incorrectamente de las versiones de ChatGPT (p. ej., Khosravi 2023 y Ndukwe 2020 sin título; Misiejuk 2025 con autoría errónea).
