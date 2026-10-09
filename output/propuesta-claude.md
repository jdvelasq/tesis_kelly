Universidad Nacional de Colombia · Sede Medellín · Facultad de Minas  
Maestría en Ingeniería – Analítica  

# IA generativa y agéntica en la analítica de la enseñanza y del aprendizaje: un estudio de mapeo sistemático (2022–2026)

*Título tentativo; por definir con el director.*  

PRIMER BORRADOR DE TRABAJO – no es la propuesta definitiva

Estudiante: **pendiente**  |  Director: **pendiente**  |  Codirector(a): **pendiente**  
Versión: borrador 0.1 · 9 de octubre de 2026  

> **Convenciones de este documento.** Los recuadros `> **PENDIENTE.**` marcan contenido **PENDIENTE** (no se puede llenar todavía o requiere una decisión/validación). Etiquetas de evidencia: **[S]** verificada en la fuente; **[I]** inferencia propia, por contrastar; **[P]** pendiente de verificar. Las cifras del corpus provienen de una **primera pasada exploratoria automatizada** sobre exportaciones de Scopus (regex sobre título, resumen y palabras clave), no de codificación manual validada; deben leerse como cotas superiores o aproximaciones.

## Contenido

1. Problema de negocio (o equivalente)

2. Problema de analítica

3. Revisión de literatura

4. Discusión: justificación de un estudio que responda las preguntas de investigación

5. Hipótesis

6. Objetivo general y objetivos específicos

7. Metodología

8. Cronograma

9. Bibliografía

Anexo A. Cadena de búsqueda Scopus vigente

Anexo B. Lista de pendientes consolidada

## 1. Problema de negocio (o equivalente)

Como la tesis es de analítica, esta sección se formula al estilo INFORMS: se describe primero el contexto de decisión, quién decide, qué decisión está en juego, cuál es el costo de decidir sin evidencia y cómo se mediría el éxito. El «negocio» aquí es la toma de decisiones sobre adopción de IA en la analítica educativa.

### 1.1 Contexto y organización

Entre 2022 y 2026 la IA generativa (modelos de lenguaje grandes, LLM) entró en la analítica del aprendizaje (*Learning Analytics*, LA) y, más recientemente, emergió el discurso de la IA agéntica (sistemas con planificación, uso de herramientas y ciclos autónomos). La analítica de la enseñanza (*Teaching Analytics*, TA), es decir, la analítica orientada a las decisiones del docente y al diseño de la enseñanza, es una subárea más pequeña y menos consolidada [S: Ndukwe & Daniel, 2020; Bayrak Karsli et al., 2025]. La producción científica crece rápido y se dispersa en revistas, actas y editoriales; no hay un mapa consolidado que permita saber qué se sabe, qué falta y dónde está el riesgo.

### 1.2 Actores y decisiones

| Actor | Decisión que enfrenta | Evidencia que necesita |
|---|---|---|
| Docentes y coordinadores de programa (educación superior, énfasis iberoamericano) | Si incorporar asistentes/tableros con LLM o agentes para apoyar su propia enseñanza (TA) y el seguimiento estudiantil (LA). | Qué usos tienen respaldo, en qué niveles/dominios, con qué riesgos documentados. |
| Unidades de analítica institucional y dirección TIC | Qué capacidades priorizar (infraestructura, gobernanza, formación) ante GenAI frente a agentes. | Madurez real de lo «agéntico» (¿pilotos o conceptos?), tipos de contribución dominantes. |
| Investigadores y programas de posgrado (incluida esta línea en la UNAL) | Dónde invertir esfuerzo de investigación y en qué foros publicar (p. ej., IEEE RITA). | Temas dominantes, vacíos, evolución temporal, producción iberoamericana. |
| Entes de política educativa | Qué lineamientos éticos y de gobernanza exigir. | Desafíos reportados con frecuencia (sesgo, privacidad, fiabilidad). |

> **PENDIENTE.** Validar con el director y, si es posible, con 3–5 actores reales (p. ej., coordinadores de la Facultad de Minas) cuál es el decisor principal, su decisión concreta y su horizonte. Hasta entonces, la tabla anterior es una hipótesis de trabajo [I].

### 1.3 Problema de negocio (formulación)

**Declaración.** Los decisores de educación superior deben elegir cómo y dónde incorporar IA generativa y agéntica en la analítica de la enseñanza y del aprendizaje, pero carecen de una síntesis estructurada y actualizada de la evidencia (2022–2026) que distinga entre IA generativa y agéntica, entre analítica centrada en el docente (TA) y en el estudiante (LA), y entre estudios empíricos, marcos conceptuales y opiniones. Decidir sin ese mapa implica (i) invertir en capacidades sin respaldo empírico, (ii) ignorar riesgos documentados y (iii) duplicar esfuerzos de investigación en temas saturados mientras otros permanecen sin explorar.

### 1.4 Medidas de éxito (KPI del proyecto)

| Indicador | Definición operativa | Meta tentativa |
|---|---|---|
| Cobertura del corpus | Recall frente a un conjunto de referencia de artículos clave conocidos (benchmark de ≥20 estudios verificados) | ≥ 90 % [I] |
| Fiabilidad de codificación | Kappa de Cohen entre dos codificadores en muestra ≥ 20 % | κ ≥ 0,70 |
| Respuesta a las RQ | Número de RQ con respuesta soportada por datos validados | 7 de 7 |
| Utilidad para decisión | Valoración de utilidad por expertos/decisores (escala Likert, n por definir) | pendiente |
| Difusión | Manuscrito sometido a IEEE RITA o equivalente | 1 manuscrito |

> **PENDIENTE.** Metas de utilidad para decisión y cuántos expertos consultar; criterios de aceptación de la tesis según el reglamento del programa.

### 1.5 Restricciones y supuestos

- Datos: solo literatura indexada en Scopus en la fase actual; las exportaciones disponibles **no incluyen referencias ni afiliaciones** (límite para acoplamiento bibliográfico y análisis por país).
- Tiempo y recursos: tesis de maestría; un solo investigador principal; herramientas propias (tm2+) y software abierto.
- Dinamismo: 2026 está parcialmente cubierto (la primera pasada incluye registros hasta la fecha de exportación); el corpus es un objeto en movimiento.
- Ética: se trabaja con metadatos bibliográficos; no hay datos personales. Uso de IA generativa como apoyo debe declararse conforme a la política del programa y de la revista [P].

## 2. Problema de analítica

Se traduce el problema de negocio a una pregunta analítica precisa: qué tipo de analítica se requiere, con qué datos, qué técnicas, cómo se evalúa y qué decisión alimenta.

### 2.1 Tipo de problema y nivel de analítica

Descriptivo-diagnóstico, con un componente exploratorio de minería de texto. Se busca *describir* la estructura temática y su evolución, y *diagnosticar* vacíos y asociaciones (p. ej., qué funciones se asocian con IA agéntica frente a generativa). No se pretende predicción causal; las conclusiones son sobre la **literatura**, no sobre efectos educativos.

### 2.2 Formulación analítica

Sea *D* el conjunto de documentos recuperados de Scopus para 2022–2026 y *x_d* los metadatos y texto (título, resumen, palabras clave) del documento *d*. Se define un conjunto de facetas categóricas *f_k(x_d)* (tipo de IA, foco TA/LA, función, nivel/dominio, tipo de contribución, desafío reportado) con codificación manual validada y un clasificador/regla auxiliar. El problema es estimar, con incertidumbre, (a) las distribuciones y asociaciones entre facetas por periodo, (b) las comunidades temáticas en la red de co-ocurrencia de palabras clave y su evolución, y (c) los vacíos (celdas de baja densidad) en el espacio facetado.

### 2.3 Datos

| Elemento | Descripción | Estado |
|---|---|---|
| Fuente primaria | Scopus (tipos: artículo, ponencia, revisión, capítulo; idiomas: inglés, español, portugués; 2022–2026) | Exportaciones de 2 rondas disponibles |
| Campos disponibles | 22 columnas (título, autores, año, fuente, resumen, palabras clave, EID, DOI, tipo, etc.) | **Sin Referencias ni Afiliaciones** |
| Corpus exploratorio | 884 registros unión → 801 limpios → 713 sin ruido «teacher agency» → 662 en la mapeo de primera pasada | [S] conteos propios |
| Núcleo LA×GenAI | 323 registros con términos de LA e IA generativa en título/palabras clave del autor (estable entre exportaciones) | [S] |
| TA estricto | 46 registros (24 en título/palabras clave); TA como «lente» ≈ 7 % del corpus | [S] |
| IA agéntica propiamente dicha | 19–25 registros (≈3–4 en 2025; 16–21 en 2026); 94 % del corpus es generativa | [S] aproximado |
| Fuentes complementarias | Web of Science, OpenAlex, ERIC, Scielo/Redalyc, LAK/L@S 2026 | pendiente |

### 2.4 Métodos analíticos

- Bibliometría descriptiva: producción anual, fuentes, tipos de documento; *burst* y puntos de cambio (Kleinberg, 2003).
- Co-palabras con detección de comunidades (Louvain) y evolución temática por ventanas (Cobo et al., 2011).
- Acoplamiento bibliográfico y co-citación: **bloqueados** hasta reexportar con Referencias.
- Análisis facetado y tablas de contingencia para vacíos; prueba exacta de Fisher/χ² con corrección por comparaciones múltiples para asociaciones.
- Modelado de tópicos sobre resúmenes (BERTopic o LDA) como contraste del co-word, dado que ≈34 % de los documentos carece de palabras clave útiles.
- Implementación con herramientas propias (tm2+) y bibliometrix/VOSviewer como referencia de validación (Aria & Cuccurullo, 2017; van Eck & Waltman, 2010).

### 2.5 Evaluación y validez

Validez de construcción: definición operativa de «agéntico» y de «TA» frente a «generativo» y «LA» (el uso de la palabra *agentic* sin más genera ruido, p. ej. «agentic engagement»). Validez interna: doble codificación (κ ≥ 0,70) y reconciliación. Validez externa: sensibilidad de los resultados a variantes de la cadena (escenarios A, B, C) y a otras bases de datos. Sesgos: dominio de Scopus, sesgo de lengua, 57 % de ponencias, retraso de indexación de 2026.

### 2.6 Entregables analíticos y decisión que alimentan

(i) Mapa temático 2022–2026 de TA/LA con IA generativa y agéntica; (ii) matriz de vacíos; (iii) lista priorizada de desafíos reportados; (iv) conjunto de datos y código reproducibles; (v) guía de decisión para adopción (qué usos tienen respaldo, cuáles son conceptuales).

> **PENDIENTE.** Definir el formato exacto del producto de decisión (p. ej., tablero interactivo en tm2+, informe ejecutivo) y su público; precisar el conjunto benchmark para medir recall.

## 3. Revisión de literatura

Objetivo de la sección: mostrar el estado del arte y justificar, con evidencia, que **no existe** (hasta donde se ha verificado) un estudio que mapee conjuntamente TA y LA bajo IA generativa *y* agéntica, distinguiéndolas. La ausencia se sostiene con una tabla de comparación; la prueba de ausencia formal (búsqueda estructurada de revisiones) queda pendiente.

### 3.1 Fundamentos: LA y TA

La LA nace como campo orientado a medir, recopilar y analizar datos de aprendices para comprender y optimizar el aprendizaje (Siemens & Long, 2011; Ferguson, 2012). Críticas tempranas insisten en que la LA debe estar anclada en el aprendizaje y en consideraciones éticas (Gašević et al., 2015; Slade & Prinsloo, 2013). La TA desplaza el foco hacia las decisiones del docente: tableros, *noticing*, orquestación y diseño de aprendizaje (Vatrapu et al., 2011; Prieto et al., 2018; Holstein et al., 2019; Wise & Jung, 2019; Mangaroska & Giannakos, 2019). Ndukwe & Daniel (2020) ofrecen la revisión de referencia sobre valor y herramientas de TA, y Bayrak Karsli et al. (2025) mapean bibliométricamente la TA, sin analizar IA generativa.

### 3.2 IA generativa en LA

Los editoriales de *Journal of Learning Analytics* establecieron la agenda (Khosravi et al., 2023; Khosravi et al., 2025) y Yan et al. (2024b) contextualizan oportunidades y desafíos en el ciclo de LA. Misiejuk et al. (2025) realizan la revisión sistemática de referencia: mapean la GenAI en LA sobre 41 estudios. Rodríguez-Ortiz et al. (2025) revisan ML y GenAI en LA en educación superior (101 estudios identificados; 26 incluidos). Revisiones adyacentes: Yan et al. (2024a) sobre desafíos prácticos y éticos de los LLM en educación; Cabral et al. (2025) sobre tableros de LA con IA; Razami et al. (2026) sobre GenAI en LA y apoyo a la decisión en educación superior (38 estudios); Ivanova & Terzieva (2026) sobre LLM en sistemas educativos inteligentes (80 estudios); Keržič et al. (2026) bibliometría de LA hacia enfoques basados en IA. Rienties et al. (2026) y Claassen et al. (2026) abordan el papel conjunto de LA y GenAI en la toma de decisiones y el diseño del aprendizaje.

### 3.3 IA generativa en TA (herramientas de apoyo docente)

Existen estudios puntuales de tableros docentes con LLM: Wang, Lin y Hu (2025) proponen un tablero autoservicio; Yang, Wang y Chen (2025) presentan Chat-LAD para explicar tableros; Kim et al. (2024, preprint) un tablero con LLM para escritura en inglés como lengua extranjera; Ma et al. (2026, preprint) un tablero meta-reflexivo para ver interacciones estudiante–IA. Son estudios de herramienta, no mapas del campo.

### 3.4 IA agéntica

En la primera pasada, los documentos con IA agéntica propiamente dicha son pocos (19–25) y mayormente marcos, sistemas o contribuciones conceptuales, concentrados en 2026. Existen agentes de codificación como apoyo analítico en preprints (Chen et al., 2026) [preprint]. No se identificó revisión sistemática o mapeo que trate lo agéntico en TA/LA. [I]

### 3.5 Síntesis comparativa y vacío

| Estudio | LA | TA | GenAI | Agéntica | Tipo / n | Limitación frente a esta propuesta |
|---|---|---|---|---|---|---|
| Ndukwe & Daniel, 2020 | sí | sí | no | no | Revisión | Anterior a GenAI |
| Bayrak Karsli et al., 2025 | parcial | sí | no | no | Bibliométrico | No considera GenAI |
| Misiejuk et al., 2025 | sí | no (lente docente no central) | sí | no | RSL, 41 | No distingue agéntica; TA no es eje |
| Rodríguez-Ortiz et al., 2025 | sí | no | sí (con ML) | no | RSL, 26 incl. | Foco en modelos/ML en superior |
| Razami et al., 2026 | sí | no | sí | no | RSL, 38 | Foco en decisión; superior |
| Cabral et al., 2025 | tableros | parcial | IA general | no | RSL | Solo tableros |
| Ivanova & Terzieva, 2026 | no | no | sí (LLM) | no | RSL, 80 | Sistemas inteligentes, no LA/TA |
| Keržič et al., 2026 | sí | no | parcial | no | Bibliométrico | Cobertura TA/agéntica no verificada |
| **Esta propuesta** | sí | sí (lente) | sí | sí (distinguida) | Mapeo 2022–2026 | — |

**Lectura.** Las revisiones identificadas cubren GenAI en LA o TA sin GenAI, pero ninguna de las verificadas distingue IA generativa de agéntica ni trata TA y LA en un mismo marco con GenAI. La afirmación es de «no se encontró», no de «no existe»: depende de la sensibilidad de la búsqueda de revisiones y de la ventana temporal (2026 se mueve rápido). [I]

> **PENDIENTE.** (a) Búsqueda formal de revisiones previas (Scopus, WoS, OpenAlex, ERIC, arXiv; cadena de revisiones: «systematic review\|scoping review\|mapping\|bibliometric» × bloque LA/TA × bloque GenAI/agéntico) con registro PRISMA-S; (b) verificar texto completo de Keržič et al. (2026) y Razami et al. (2026) para confirmar que no distinguen agéntica; (c) registrar la ecuación de búsqueda y fecha; (d) completar LAK 2026 y L@S 2026 (no enumerados); (e) ampliar con literatura iberoamericana (Scielo, Redalyc, actas LASI/LALA, RITA).

## 4. Discusión: se requiere un estudio que responda las RQ definidas

Esta sección formaliza el paso de la revisión a la pregunta. Argumento en cuatro pasos.

- **Magnitud y dinamismo.** El corpus exploratorio (≈660–710 documentos) crece de forma acelerada y 2026 concentra buena parte de los registros: ninguna revisión puntual de 2025 puede reflejarlo.
- **Confusión conceptual.** La literatura usa «agente» y «agéntico» de manera laxa; se necesita una operacionalización explícita que separe sistemas generativos (respuesta a un prompt) de sistemas agénticos (planificación, herramientas, bucle de acción).
- **Desbalance de lentes.** LA domina; la TA (≈7 % del corpus) es periférica; la perspectiva docente puede quedar subrepresentada justamente donde más afectaría la decisión de los profesores.
- **Decisión sin mapa.** Los decisores necesitan saber qué es evidencia empírica, qué es marco conceptual y qué es opinión, y cuáles son los riesgos reportados (problema de negocio, §1).

### 4.1 Preguntas de investigación

| RQ | Pregunta | Facetas / método |
|---|---|---|
| RQ1 | ¿Cómo ha evolucionado la producción sobre IA generativa/agéntica en TA y LA (2022–2026) y en qué foros se publica? | Conteos, fuentes, burst, puntos de cambio |
| RQ2 | ¿En qué medida la literatura distingue y aborda la IA generativa frente a la agéntica? | Faceta tipo de IA; análisis conceptual |
| RQ3 | ¿Cuál es el foco (TA vs LA) y cuáles son los temas dominantes? | Co-palabras, comunidades, modelado de tópicos |
| RQ4 | ¿Qué funciones o usos se reportan (evaluación/retroalimentación, tableros, tutoría, codificación de datos, personalización, etc.)? | Faceta función |
| RQ5 | ¿En qué nivel educativo y dominio se aplican? | Faceta nivel/dominio; geografía [bloqueada sin afiliaciones] |
| RQ6 | ¿Qué tipo de contribución predomina (empírica, sistema, marco/conceptual, revisión, opinión)? | Faceta diseño/contribución |
| RQ7 | ¿Qué desafíos y riesgos se reportan y con qué frecuencia? | Faceta desafíos (sesgo, privacidad, fiabilidad, alucinación, ética) |

Resultados preliminares (primera pasada automatizada, a validar): la producción es predominantemente generativa (≈94 %), la IA agéntica es incipiente y conceptual (19–25 documentos, con aceleración en 2026), la TA es una fracción pequeña (46 estrictos), el 57 % son ponencias y se identifican cinco comunidades temáticas que cubren ≈66 % de los documentos.

### 4.2 Por qué las RQ no se responden con la literatura existente

Cada RQ exige una combinación (TA/LA × generativa/agéntica × 2022–2026 × facetas) que no aparece en las revisiones de §3.5. Responderlas con un mapeo sistemático es proporcionado: el objetivo es describir y localizar vacíos, no estimar efectos, por lo que un mapeo (Petersen) es más adecuado que una revisión sistemática de efectividad o un metaanálisis.

> **PENDIENTE.** Decidir con el director si la tesis será (i) solo mapeo, o (ii) mapeo más estudio empírico posterior (p. ej., entrevistas a docentes) — esta es la decisión de alcance más importante. Además, definir si el producto en RITA coincide con un capítulo de la tesis.

## 5. Hipótesis

En un mapeo descriptivo las hipótesis son conjeturas contrastables sobre la distribución de la literatura. Se formulan a partir de la primera pasada exploratoria; por ello **no son confirmatorias** y su contraste definitivo debe hacerse sobre el corpus final con codificación manual validada, con riesgo explícito de sesgo de selección post hoc (HARKing) en caso contrario.

| Id | Hipótesis (tentativa) | Operacionalización | Estado |
|---|---|---|---|
| H1 | La producción sobre GenAI en LA/TA crece sostenidamente en 2022–2026 con un cambio de nivel después de 2023. | Serie anual; punto de cambio | Soportada preliminarmente [S] |
| H2 | La IA agéntica representa menos del 10 % del corpus y se concentra en contribuciones de marco/sistema/conceptuales con baja evidencia empírica. | Proporción por tipo de IA × tipo de contribución | Preliminar: 19–25 de ≈660 [S]; falta contribución validada |
| H3 | La TA (perspectiva del docente) está subrepresentada frente a la LA (perspectiva del estudiante). | Proporción TA estricto / LA | Preliminar: ≈7 % [S] |
| H4 | Las funciones dominantes son evaluación/retroalimentación, personalización y codificación automática de datos; los tableros docentes con LLM son minoritarios. | Distribución de la faceta función | Pendiente de validación |
| H5 | Los desafíos más reportados son fiabilidad/alucinación, ética/privacidad y sesgo, con pocos estudios que evalúen mitigaciones. | Frecuencia de desafíos; presencia de mitigación | Pendiente |
| H6 | La producción iberoamericana está subrepresentada respecto de su peso en la matrícula regional. | Afiliaciones por país | **Bloqueada** (sin afiliaciones) |
| H7 | La mayoría de los estudios se concentran en educación superior y en dominios STEM/lenguas. | Faceta nivel/dominio | Pendiente |

> **PENDIENTE.** Definir el umbral de contraste (p. ej., IC de proporciones al 95 %); decidir si H6 se mantiene (requiere reexportar con afiliaciones); registrar las hipótesis antes de la codificación manual (preregistro en OSF) para limitar HARKing.

## 6. Objetivo general y objetivos específicos

### 6.1 Objetivo general

Caracterizar, mediante un estudio de mapeo sistemático con analítica bibliométrica y de texto, la producción científica 2022–2026 sobre IA generativa y agéntica en analítica de la enseñanza y del aprendizaje, con el fin de identificar temas dominantes, usos, desafíos y vacíos que orienten decisiones de adopción e investigación.

### 6.2 Objetivos específicos

| Id | Objetivo específico | RQ | Producto verificable |
|---|---|---|---|
| OE1 | Diseñar y validar una estrategia de búsqueda reproducible (PRISMA-S) que distinga IA generativa de agéntica y TA de LA. | — | Cadena final + registro de sensibilidad + recall frente a benchmark |
| OE2 | Construir y depurar el corpus (deduplicación, cribado, codificación manual con κ ≥ 0,70). | RQ2, 4–7 | Corpus codificado + diagrama PRISMA |
| OE3 | Describir la evolución, fuentes y distribución geográfica de la producción. | RQ1, RQ5 | Tablas/figuras bibliométricas |
| OE4 | Identificar la estructura temática y su evolución mediante co-palabras, modelado de tópicos y (si hay datos) acoplamiento bibliográfico. | RQ3 | Mapa temático + evolución |
| OE5 | Analizar funciones, contribuciones y desafíos, y detectar vacíos de investigación. | RQ4, 6, 7 | Matriz de vacíos |
| OE6 | Contrastar las hipótesis y formular una agenda y recomendaciones de decisión; preparar un manuscrito para IEEE RITA. | Todas | Informe final + manuscrito |

> **PENDIENTE.** Revisar redacción y verbos con la guía de la Maestría (nivel de taxonomía), y verificar que OE6 no exceda el alcance de un trabajo final de maestría.

## 7. Metodología

### 7.1 Diseño y marcos de referencia

Mapeo sistemático (Petersen et al., 2008/2015 [P: referencia por completar]) reportado conforme a PRISMA 2020 (Page et al., 2021), PRISMA-S para la búsqueda y la extensión PRISMA-ScR de la revisión de alcance (Tricco et al., 2018) en los elementos aplicables. La búsqueda es iterativa al estilo Cochrane: se parte de una cadena sensible, se mide su recall frente a un conjunto de referencia y se refina, documentando cada versión. Como complemento, un análisis bibliométrico/minería tecnológica (Rotolo et al., 2015, para el concepto de tecnología emergente).

### 7.2 Fases

| Fase | Actividad | Salida |
|---|---|---|
| F0. Protocolo | Fijar RQ, criterios y plan de análisis; preregistrar (OSF) y congelar hipótesis | Protocolo v1.0 |
| F1. Búsqueda | Cadena Scopus (Anexo A) + sensibilidad A/B/C; segunda y tercera base de datos; reexportar con Referencias y Afiliaciones; búsqueda de literatura gris y de preprints solo como contraste | Registros crudos + log PRISMA-S |
| F2. Cribado | Deduplicación por EID/DOI/título; cribado título-resumen y texto completo por dos revisores con κ | Corpus final + diagrama PRISMA |
| F3. Codificación | Extracción de facetas (tipo de IA, foco, función, nivel/dominio, contribución, desafíos); muestra ≥ 20 % doble codificada | Libro de códigos + κ |
| F4. Análisis | Bibliometría descriptiva; co-palabras y Louvain; acoplamiento; tópicos; evolución; vacíos | Figuras y tablas |
| F5. Síntesis | Contraste de hipótesis; discusión; agenda; guía de decisión | Informe |
| F6. Difusión | Manuscrito para RITA; sustentación | Manuscrito + tesis |

### 7.3 Criterios de elegibilidad

|  | Inclusión | Exclusión |
|---|---|---|
| Población/contexto | Educación (superior prioritariamente; otros niveles se codifican) | Educación no formal y corporativa, salvo que se declare lo contrario |
| Fenómeno | Uso de IA generativa y/o agéntica en contextos de LA o TA (instrumento, fuente de datos, soporte de enseñanza/aprendizaje mediada por GenAI) | Uso de LLM sin vínculo con analítica (p. ej., redacción docente); «agentic» como sinónimo de agencia humana |
| Tipo de documento | Artículo, ponencia, revisión, capítulo | Editoriales sin datos y resúmenes de taller se codifican aparte como «opinión/normativo» |
| Periodo e idioma | 2022 – 2026 (corte por fecha); inglés, español, portugués | Otros idiomas (limitación declarada) |

### 7.4 Estrategia de búsqueda

Cadena única vigente en el Anexo A: bloque LA/TA AND (bloque GenAI OR bloque agéntico), con PUBYEAR > 2021 y < 2027. Lecciones documentadas: no usar *agentic** sin acotar, y no añadir *teacher agency* ni *teacher-in-the-loop* porque introdujeron ≈88 de 801 registros ruidosos (estudios de percepción de docentes de inglés); esta decisión corrige una recomendación previa.

### 7.5 Gestión de datos y análisis

Todo el flujo se programará en Python (pandas, networkx/igraph, scikit-learn, BERTopic) y tm2+, con scripts versionados en el repositorio de la tesis y semillas fijadas. La primera pasada usó reglas por expresiones regulares y una red de co-palabras con comunidades Louvain; esas reglas serán la base de un clasificador auxiliar, pero la verdad de referencia será la codificación manual (κ ≥ 0,70).

### 7.6 Amenazas a la validez y mitigación

| Amenaza | Mitigación |
|---|---|
| Sesgo de base de datos (solo Scopus) | Segunda base (WoS/OpenAlex) y análisis de solapamiento |
| Ruido léxico («agentic», «agent») | Bloques acotados + revisión manual + reporte de precisión |
| Subjetividad de codificación | Libro de códigos, doble codificación, κ |
| Corpus 2026 incompleto | Fecha de corte explícita; actualización antes de la sustentación |
| Hipótesis post hoc | Preregistro y contraste en corpus final |
| Uso de IA generativa en el propio estudio | Declaración y verificación humana de toda salida |

> **PENDIENTE.** Definir segunda base de datos (WoS vs OpenAlex), número de revisores humanos disponibles, software de cribado (Rayyan/ASReview), y si se preregistrará (OSF vs PROSPERO no aplica a mapeos); precisar la fecha de corte final.

## 8. Cronograma

Plan tentativo en meses, sobre una duración supuesta de un semestre académico ampliado (≈6 meses). Debe ajustarse a la duración reglamentaria del trabajo final y a la fecha de sustentación, aún no definidas.

| Actividad | M1 | M2 | M3 | M4 | M5 | M6 |
|---|---|---|---|---|---|---|
| F0 Protocolo y preregistro | ■ | ■ |  |  |  |  |
| F1 Búsqueda multi-base y reexportación | ■ | ■ |  |  |  |  |
| F2 Deduplicación y cribado |  | ■ | ■ |  |  |  |
| F3 Codificación y κ |  |  | ■ | ■ |  |  |
| F4 Análisis bibliométrico y temático |  |  |  | ■ | ■ |  |
| F5 Síntesis, hipótesis, guía de decisión |  |  |  |  | ■ | ■ |
| F6 Manuscrito RITA y sustentación |  |  |  |  | ■ | ■ |

**Hitos.** M1: protocolo congelado y benchmark de recall. M3: corpus final y diagrama PRISMA. M4: κ ≥ 0,70 alcanzado. M5: resultados completos. M6: manuscrito sometido y documento de tesis.

**Restricciones de calendario de RITA** [S]: manuscrito original en inglés; 10–16 páginas (costo adicional por página sobre 10); similitud ≥ 25 % implica rechazo; la traducción a español/portugués se hace tras la aceptación. Indexación/cuartil y política de IA generativa: [P].

> **PENDIENTE.** Calendario oficial del programa, fecha de sustentación, ciclos de la convocatoria RITA, disponibilidad de codificadores; riesgos de cronograma y plan de contingencia.

## 9. Bibliografía

Se incluyen solo referencias verificadas (etiqueta [S]) en el informe de investigación del repositorio (*output/claude.md*, §12). Las entradas con datos incompletos se señalan.

- Aria, M., & Cuccurullo, C. (2017). bibliometrix: An R-tool for comprehensive science mapping analysis. *Journal of Informetrics, 11*(4), 959–975. https://doi.org/10.1016/j.joi.2017.08.007
- Bayrak Karsli, M., Cilligol Karabey, S., Kaba, E., Guler, M., Aydemir Arslan, M., & Kursun, E. (2025). Research trends in teaching analytics: Bibliometric mapping and content analysis. *Technology, Knowledge and Learning, 30*(3), 1345–1369. https://doi.org/10.1007/s10758-024-09773-y
- Cabral, L., Pinto, R., & Gonçalves, G. (2025). AI-powered learning analytics dashboards: A systematic review of applications, techniques, and research gaps. *Discover Education, 4*, Article 525. https://doi.org/10.1007/s44217-025-00964-y
- Chen, E., Wang, I., Yuan, N., Judicke, S., Beigh, K., & Tang, X. (2026). *From tool to teammate: LLM coding agents as collaborative partners for behavioral labeling in educational dialogue analysis* [Preprint]. arXiv:2603.27440. https://arxiv.org/abs/2603.27440
- Claassen, A., Ebbert, D., Kovanović, V., Mirriahi, N., & Dawson, S. (2026). Understanding the role of learning analytics and generative artificial intelligence in decision-making and learning design practice in higher education. *International Journal of Educational Technology in Higher Education, 23*(1), Article 43. https://doi.org/10.1186/s41239-026-00619-4
- Cobo, M. J., López-Herrera, A. G., Herrera-Viedma, E., & Herrera, F. (2011). An approach for detecting, quantifying, and visualizing the evolution of a research field. *Journal of Informetrics, 5*(1), 146–166. https://doi.org/10.1016/j.joi.2010.10.002
- Ferguson, R. (2012). Learning analytics: Drivers, developments and challenges. *International Journal of Technology Enhanced Learning, 4*(5/6), 304–317. https://doi.org/10.1504/IJTEL.2012.051816
- Gašević, D., Dawson, S., & Siemens, G. (2015). Let's not forget: Learning analytics are about learning. *TechTrends, 59*(1), 64–71. https://doi.org/10.1007/s11528-014-0822-x
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
- Prieto, L. P., Sharma, K., Kidzinski, Ł., Rodríguez-Triana, M. J., & Dillenbourg, P. (2018). Multimodal teaching analytics: Automated extraction of orchestration graphs from wearable sensor data. *Journal of Computer Assisted Learning, 34*(2), 193–203. https://doi.org/10.1111/jcal.12232
- Razami, Singh, Sampedro, Kovilpillai, Raza, Anwar, Hamdan, & Konno. (2026). A systematic review of generative AI in higher education learning analytics and decision support. *Discover Artificial Intelligence*. https://doi.org/10.1007/s44163-026-01888-8 [adelanto en línea; iniciales por completar]
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

> **PENDIENTE.** Petersen et al. (mapeos sistemáticos en ingeniería de software), Kitchenham/Cochrane Handbook y la guía de IEEE RITA: referencias por incorporar y verificar. Bibliografía iberoamericana (LASI, LALA, RITA, Scielo/Redalyc) por construir. Completar iniciales de autores donde falten.

## Anexo A. Cadena de búsqueda Scopus vigente

Estructura (resumida; la versión ejecutable se mantiene en el repositorio):

`TITLE-ABS-KEY( ("learning analytic*" OR "multimodal learning analytic*" OR "learning dashboard*" OR "teaching analytic*" OR "teacher analytic*" OR "teacher-facing analytic*" OR "teacher-facing dashboard*" OR "instructor analytic*" OR "instructor dashboard*" OR "educator analytic*" OR "pedagogical analytic*" OR "teaching and learning analytic*" OR "teacher dashboard*" OR "teaching dashboard*" OR "instructor-facing" OR "teacher noticing" OR "classroom orchestration" OR "learning design analytic*" OR "analítica del aprendizaje" OR "analítica de la enseñanza" OR "analítica docente") AND ( [BLOQUE GenAI: generative AI / LLM / ChatGPT / GPT / foundation model, etc.] OR [BLOQUE AGÉNTICO: "agentic AI" / "agentic system" / "agentic workflow" / "agentic framework" / "agentic architecture" / "AI agent*" / "LLM agent*" / "LLM-based agent*" / RAG, y variantes en español y portugués] ) ) AND PUBYEAR > 2021 AND PUBYEAR < 2027 AND DOCTYPE(ar OR cp OR re OR ch) AND LANGUAGE(english OR spanish OR portuguese)`

> **PENDIENTE.** Registrar la cadena textual completa, fecha de ejecución y número de resultados en el log PRISMA-S; los bloques GenAI y agéntico se copian literalmente del archivo de búsqueda del repositorio.

## Anexo B. Lista de pendientes consolidada

- Alcance: solo mapeo vs mapeo + estudio empírico (decisión con director). Título definitivo.
- Validar actores/decisor y KPI con personas reales; definir producto de decisión (tablero tm2+, informe).
- Búsqueda formal de revisiones previas (prueba de «no existe») y registro PRISMA-S.
- Segunda base de datos; reexportación con Referencias y Afiliaciones (desbloquea acoplamiento y RQ5 geográfica/H6).
- Completar LAK 2026 y L@S 2026; literatura iberoamericana.
- Codificación manual (≈20 %: ~130 documentos del corpus; TA 46 y agénticos ≈45 completos) y κ.
- Modelado de tópicos sobre resúmenes (≈34 % sin palabras clave).
- Preregistro (OSF) de hipótesis y protocolo.
- Cronograma oficial, sustentación, evaluadores, reglamento de la Maestría.
- Política de RITA (indexación/cuartil, uso de IA generativa); política de la UNAL sobre uso de IA.
- Referencias metodológicas faltantes (Petersen; Cochrane Handbook; Kitchenham) e iniciales de autores.
