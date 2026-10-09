# Investigación: IA generativa, Teaching Analytics y Learning Analytics

> **Nombre de archivo sugerido:** `investigacion_ta_la_genai_2026-10-02_0944.md`
> **Fecha de generación:** 2026-10-02, 09:44 (America/Bogota)
> **Advertencia de cobertura:** este informe se elaboró con búsqueda web y verificación puntual de registros bibliográficos (DOI y páginas editoriales). **No** es una exportación reproducible de Scopus, Web of Science, Dimensions ni OpenAlex. El intento de consulta automatizada a la API de OpenAlex falló (error 429 y bloqueo de red), por lo que **ningún conteo bibliométrico de este documento proviene de una consulta propia**. Los únicos números citados proceden de estudios publicados y se atribuyen a ellos.
>
> **Convención de solidez:** **[S]** bien sustentado (fuente verificada); **[I]** inferencia razonada del equipo; **[P]** pendiente de validación con búsqueda bibliográfica formal.
>
> **Actualización 2026 (9 de octubre de 2026):** se incorporó una revisión de la literatura de enero a comienzos de octubre de 2026 y se verificaron los ítems [P] previos (secciones 1, 3.2, 3.4, 4.2, 5, 9, 11, 12 y 13). La cobertura de 2026 es **parcial**: no se enumeraron los artículos de LAK26, L@S 2026 se conoce solo por títulos y autores, y no se buscó en AIED, EDM, BJET ni *Computers & Education*; Crossref y OpenAlex estuvieron bloqueados. Sigue sin haber conteos bibliométricos propios.

---

## 1. Resumen ejecutivo

**Estado del campo.** Learning Analytics (LA) es un campo consolidado desde 2011, con conferencia propia (LAK), revista propia (*Journal of Learning Analytics*, JLA), manuales y una tradición de revisiones sistemáticas (Siemens & Long, 2011; Ferguson, 2012; Viberg et al., 2018) **[S]**. Teaching Analytics (TA) es un subcampo más pequeño y menos estable terminológicamente; nace en torno a LAK 2011 con el trabajo sobre analítica visual para la toma de decisiones docentes (Vatrapu et al., 2011) y se ha desarrollado sobre todo en torno a tableros docentes, indagación docente (*teacher inquiry*), orquestación y analítica multimodal (Sergis & Sampson, 2017; Prieto et al., 2018; Ndukwe & Daniel, 2020) **[S]**. Un mapeo bibliométrico reciente de TA identifica como objetivos dominantes el diseño de tableros/sistemas y la evaluación de actividades docentes, con Estados Unidos y Estonia como países más productivos y EPFL y Tallinn University of Technology como instituciones destacadas (Bayrak Karsli et al., 2025) **[S]**.

**Irrupción de la IA generativa.** La intersección LA–GenAI se institucionaliza rápidamente después de noviembre de 2022: editorial de JLA sobre GenAI y LA (Khosravi et al., 2023), artículo de LAK 2024 que ubica oportunidades y riesgos en el ciclo de LA (Yan, Martinez-Maldonado & Gašević, 2024) y una sección especial de JLA en 2025 con diez artículos (Khosravi et al., 2025) **[S]**. Una revisión sistemática de GenAI en LA identificó **41 estudios empíricos**, con predominio de codificación de discurso, puntuación y clasificación, y advirtió que no siempre se validan las salidas cuando alimentan tableros (Misiejuk et al., 2025) **[S]**. Otra revisión PRISMA (2018–2025, 12 bases) incluyó 101 estudios, de los cuales **26** abordan GenAI en LA de educación superior, y calificó las implementaciones como mayormente experimentales y con escasa participación docente (Rodríguez-Ortiz et al., 2025) **[S para "experimentales"; P para "escasa participación docente", no reverificada en la actualización 2026]**.

**Intersección triple (GenAI + TA + LA).** Existen trabajos puntuales sobre tableros docentes asistidos por LLM y explicaciones generadas para docentes (p. ej., LAK 2025; L@S 2025) **[S, metadatos de autoría pendientes]**, pero el volumen etiquetado explícitamente como "teaching analytics" + GenAI parece **muy escaso** **[I/P]**. La intersección LA + GenAI es **emergente con masa crítica incipiente**; la triple es **emergente-escasa**.

**Recomendación de viabilidad.** Un estudio de *tech mining* es **viable solo con diseño híbrido (Escenario C)**: (i) corpus amplio TA/LA 2010–2026 para el análisis longitudinal (Artículo 1) y (ii) corpus focal GenAI 2022–2026 ampliado con sinónimos y clasificación asistida/manual (Artículo 2), complementado con *scoping review*. Un núcleo estricto (Escenario A) probablemente produciría un corpus insuficiente para co-citación y acoplamiento estables **[I]**. Antes de comprometer el diseño, deben ejecutarse las ecuaciones de la sección 4 en Scopus y WoS y aplicar los umbrales operativos de la sección 5.

**Actualización 2026.** La literatura verificada de enero a octubre de 2026 **confirma y profundiza este diagnóstico sin alterarlo** **[S/I]**. LA + GenAI se institucionaliza más: el *Journal of Learning Analytics* (JLA) 13(1) se organiza en torno a GenAI y competencias del siglo XXI (Barthakur et al., 2026), y LAK26 (Bergen) tuvo como lema "Learning Analytics and AI Synergy", con 372 envíos y 107 aceptados según su portada **[S]**. En los estudios primarios verificados domina el LLM como instrumento de codificación y puntuación (rol a), con validación rutinaria contra juicio humano y resultados mixtos **[S]**. La intersección triple con TA sigue siendo **emergente-escasa**, aunque ya hay un grupo identificable (el número especial de *IJETHE* sobre LA, GenAI y decisión educativa, un artículo de *Scientific Reports* y varios preprints y títulos de L@S 2026) **[I]**. Ningún artículo de 2026 leído usa "teaching analytics" como etiqueta propia, así que TA debe recuperarse por vocabulario (tableros docentes, orquestación, *teacher noticing*), no por su etiqueta **[S para lo leído; I para el campo]**. Las revisiones de 2026 verificadas cuentan decenas de estudios incluidos (31 a 80), lo que respalda la cautela sobre el Escenario A **[S/I]**. Detalle en las secciones 3.4, 4.2 y 5; la cobertura de 2026 es parcial (sección 11).

---

## 2. Mapa conceptual

```
                    ┌─────────────────────────────────────────────┐
                    │  Analítica académica / institucional        │
                    │  (retención, planeación, gestión)           │
                    └───────────────┬─────────────────────────────┘
                                    │
       ┌────────────────────────────┼─────────────────────────────┐
       │                            │                             │
┌──────▼─────────┐         ┌────────▼────────┐          ┌─────────▼────────┐
│ Educational    │◄───────►│ LEARNING        │◄────────►│ TEACHING         │
│ Data Mining    │ métodos │ ANALYTICS (LA)  │ datos de │ ANALYTICS (TA)   │
│ (EDM)          │         │ foco: aprendiz  │ aprendiz │ foco: docente    │
└────────────────┘         └───┬─────────┬───┘ para el  └──┬──────────┬────┘
                               │         │     docente      │          │
                     ┌─────────▼──┐  ┌───▼──────────┐  ┌────▼─────┐ ┌──▼──────────┐
                     │ MMLA       │  │ Learning     │  │ Teacher  │ │ Orquestación│
                     │ multimodal │  │ design       │  │ inquiry  │ │ / tableros  │
                     └────────────┘  └──────────────┘  └──────────┘ └─────────────┘
                               ▲            ▲              ▲              ▲
                               └────────────┴──────┬───────┴──────────────┘
                                                   │
                                     ┌─────────────▼─────────────┐
                                     │ IA GENERATIVA (LLM, chat- │
                                     │ bots, generación de       │
                                     │ texto/código/feedback)    │
                                     │ dentro de AIED            │
                                     └───────────────────────────┘
```

| Concepto | Unidad de interés | Usuario principal | Solapamiento | Diferencia clave | Fuente |
|---|---|---|---|---|---|
| Learning Analytics | Proceso y resultados de aprendizaje | Estudiante, docente, institución | Comparte datos y técnicas con TA y EDM | Orientado a comprender/optimizar el aprendizaje y sus entornos | Siemens & Long (2011); Ferguson (2012) **[S]** |
| Teaching Analytics | Diseño y práctica docente, decisiones pedagógicas | Docente, diseñador instruccional | Usa datos de LA como insumo; *teaching and learning analytics* (TLA) es la etiqueta integradora | Sujeto analítico = práctica docente, no solo el aprendiz | Vatrapu et al. (2011); Sergis & Sampson (2017); Ndukwe & Daniel (2020) **[S]** |
| EDM | Patrones en datos educativos | Investigador | Técnicas compartidas con LA | Énfasis en descubrimiento automatizado vs. juicio humano en LA | Siemens & Baker (2012) **[S]** |
| MMLA | Datos multimodales (sensores, audio, video) | Investigador/docente | Puente LA–TA (p. ej., grafos de orquestación) | Datos más allá de logs | Ochoa & Worsley (2016); Prieto et al. (2018) **[S]** |
| AIED | Sistemas inteligentes para educación | Diseñadores de sistemas | GenAI es hoy un subtema AIED | AIED construye sistemas; LA/TA analizan y apoyan decisiones | Zawacki-Richter et al. (2019); Ouyang & Jiao (2021) **[S]** |
| GenAI en educación | Generación de contenido y retroalimentación | Estudiante/docente | Produce nuevos datos (prompts, diálogos) y nuevas herramientas analíticas | Puede ser **objeto**, **herramienta** o **contexto** de la analítica | Kasneci et al. (2023); Yan et al. (2024b) **[S]** |

**Refinamiento de las definiciones operativas [I]:**
- La literatura confirma la definición de TA propuesta, pero conviene añadir que TA incluye **analítica sobre la práctica docente** (p. ej., orquestación capturada con sensores) y **analítica para el docente** (tableros), dos acepciones que no siempre se distinguen (Sergis & Sampson, 2017; Prieto et al., 2018).
- La definición de LA debe incluir el entorno de aprendizaje (Siemens & Long, 2011), no solo al estudiante; esto genera el solapamiento con TA.
- Tipología GenAI propuesta para la codificación (exigida en el encargo):
  - **(a) GenAI como instrumento analítico** (p. ej., codificar discurso, puntuar respuestas) — categoría dominante según Misiejuk et al. (2025) **[S]**.
  - **(b) GenAI como fuente de datos** (trazas de interacción estudiante–LLM).
  - **(c) Analítica para apoyar enseñanza/aprendizaje mediado por GenAI** (tableros, explicaciones generadas para docentes).
  - **(d) Textos opinativos/normativos** (editoriales, marcos, guías).

---

## 3. Estado de la evidencia

### 3.1 Trabajos seminales y de consolidación (pre-GenAI)

| Referencia | Año | Tipo | Foco | Papel GenAI | Método | Aporte principal | DOI/URL |
|---|---|---|---|---|---|---|---|
| Siemens & Long | 2011 | Ensayo | LA | Ninguno | Conceptual | Definición fundacional de LA | https://er.educause.edu/articles/2011/9/penetrating-the-fog-analytics-in-learning-and-education |
| Vatrapu, Teplovs, Fujita & Bull | 2011 | Actas LAK | TA | Ninguno | Diseño/conceptual | Analítica visual para decisiones pedagógicas docentes; origen del término TA | https://doi.org/10.1145/2090116.2090129 |
| Ferguson | 2012 | Artículo | LA | Ninguno | Revisión | Impulsores, desarrollo y retos de LA | https://doi.org/10.1504/IJTEL.2012.051816 |
| Siemens & Baker | 2012 | Actas LAK | LA/EDM | Ninguno | Conceptual | Delimitación LA vs. EDM | https://doi.org/10.1145/2330601.2330661 |
| Slade & Prinsloo | 2013 | Artículo | LA | Ninguno | Conceptual-ético | Marco ético de LA | https://doi.org/10.1177/0002764213479366 |
| Gašević, Dawson & Siemens | 2015 | Artículo | LA | Ninguno | Conceptual | LA debe anclarse en teoría del aprendizaje | https://doi.org/10.1007/s11528-014-0822-x |
| Ochoa & Worsley | 2016 | Editorial | MMLA | Ninguno | Conceptual | Agenda de analítica multimodal | https://doi.org/10.18608/jla.2016.32.10 |
| Schwendimann et al. | 2017 | Revisión | LA (tableros) | Ninguno | Revisión sistemática | Estado de tableros de aprendizaje | https://doi.org/10.1109/TLT.2016.2599522 |
| Sergis & Sampson | 2017 | Capítulo | Ambos (TLA) | Ninguno | Revisión sistemática | TLA para indagación docente | https://doi.org/10.1007/978-3-319-52977-6_2 |
| Prieto et al. | 2018 | Artículo | TA (multimodal) | Ninguno | Empírico (sensores) | Grafos de orquestación automáticos | https://doi.org/10.1111/jcal.12232 |
| Viberg et al. | 2018 | Revisión | LA | Ninguno | Revisión sistemática | Evidencia limitada de mejora del aprendizaje | https://doi.org/10.1016/j.chb.2018.07.027 |
| Mangaroska & Giannakos | 2019 | Revisión | LA + diseño | Ninguno | Revisión sistemática | LA para diseño de aprendizaje | https://doi.org/10.1109/TLT.2018.2868673 |
| Holstein, McLaren & Aleven | 2019 | Artículo | TA | IA no generativa | Co-diseño | Complementariedad docente–IA en aula | https://doi.org/10.18608/jla.2019.62.3 |
| Wise & Jung | 2019 | Artículo | TA | Ninguno | Cualitativo | Modelo situado de decisión docente con analítica | https://doi.org/10.18608/jla.2019.62.4 |
| Zawacki-Richter et al. | 2019 | Revisión | AIED | Pre-GenAI | Revisión sistemática | Escasa reflexión pedagógica en AIED | https://doi.org/10.1186/s41239-019-0171-0 |
| Ndukwe & Daniel | 2020 | Revisión | TA | Ninguno | Revisión sistemática tripartita | Valor y herramientas de TA; alfabetización docente en datos | https://doi.org/10.1186/s41239-020-00201-6 |

### 3.2 Era GenAI (2022–2026)

| Referencia | Año | Tipo | Foco | Papel GenAI (a–d) | Método | Aporte principal | DOI/URL |
|---|---|---|---|---|---|---|---|
| Kasneci et al. | 2023 | Comentario | Educación general | (d) | Conceptual | Oportunidades/retos de LLM en educación | https://doi.org/10.1016/j.lindif.2023.102274 |
| Gašević, Siemens & Sadiq | 2023 | Editorial | LA/AIED | (d) | Conceptual | Empoderar al aprendiz en la era de la IA | https://doi.org/10.1016/j.caeai.2023.100130 |
| Khosravi, Viberg, Kovanovic & Ferguson | 2023 | Editorial JLA | LA | (d) | Conceptual | Implicaciones de los LLM para la investigación en LA | https://doi.org/10.18608/jla.2023.8333 |
| Yan, Sha, et al. | 2024a | Revisión de alcance | Educación (LLM) | (a)(d) | Scoping review | Retos prácticos y éticos de LLM en educación | https://doi.org/10.1111/bjet.13370 |
| Yan, Martinez-Maldonado & Gašević | 2024b | Actas LAK | LA | (a)(b)(c)(d) | Conceptual | Oportunidades y riesgos de GenAI a lo largo del ciclo de LA (pp. 101–111) | https://doi.org/10.1145/3636555.3636856 |
| Misiejuk, Kaliisa & Scianna | 2024 | Artículo | LA (evaluación) | (a) | Empírico | Fiabilidad de la codificación con IA del discurso estudiantil (vol. 6, art. 100216, verificado) | https://doi.org/10.1016/j.caeai.2024.100216 |
| Khosravi, Shibani, Jovanovic, Pardos & Yan | 2025 | Editorial sección especial JLA | LA | (d) + síntesis | Síntesis de 10 artículos | Organiza la sección especial según el ciclo de Clow; tensión entre potencial de GenAI y principios centrados en lo humano | https://doi.org/10.18608/jla.2025.8961 |
| Misiejuk, López-Pernas, Kaliisa & Saqr | 2025 | Revisión sistemática | LA | (a)(b)(c) | RSL, 41 estudios empíricos | Predominio de codificación/puntuación/clasificación; validación incompleta en pipelines | https://doi.org/10.18608/jla.2025.8591 |
| Rodríguez-Ortiz, Santana-Mancilla & Anido-Rifón | 2025 | Revisión sistemática | LA (ES) | (a)(c) | PRISMA 2020, 12 bases, 101 estudios (26 GenAI) | GenAI experimental (verificado); poca participación docente **[P]**; subrepresentación de América Latina **[P]** (no reverificadas en la actualización 2026) | https://doi.org/10.3390/app15158679 |
| Bayrak Karsli et al. | 2025 | Revisión sistemática de métodos mixtos (mapeo bibliométrico + análisis de contenido) | TA | Ninguno/indirecto | Herramientas, bases y n de documentos **[P]** (no figuran en el resumen; texto completo de pago) | Tendencias de TA: tableros y evaluación de la enseñanza | https://doi.org/10.1007/s10758-024-09773-y |
| Wang, Lin & Hu, *Self-service teacher-facing LA dashboard with LLMs* | 2025 | Actas LAK (pp. 824–830) | **TA + LA** | (c) | Diseño/evaluación; pruebas de usabilidad con 15 docentes (según el resumen en OpenAlex) | Tablero docente autoservicio con LLM: consultas y visualizaciones en lenguaje natural; ejemplo de intersección triple | https://doi.org/10.1145/3706468.3706491 |
| Yang, Wang & Chen, *Chat-LAD* | 2025 | Actas (L@S, pp. 197–201) | **TA + LA** | (c) | Método **[P]** (el registro no tiene resumen) | Explicaciones generadas por IA para que docentes interpreten tableros | https://doi.org/10.1145/3698205.3733922 |

**Nota:** autoría, título, páginas y fecha de las dos últimas filas se verificaron en OpenAlex (Crossref y la ACM DL no se abrieron). El método de *Chat-LAD* sigue **[P]**. Los trabajos de 2026 están en la sección 3.4.

### 3.3 Respuestas a las preguntas de investigación

**P1. Definición y relación TA–LA [S/I].** LA se define desde 2011 como medición, recolección, análisis y reporte de datos sobre aprendices y contextos (Siemens & Long, 2011). TA surge en paralelo como analítica visual para la decisión docente (Vatrapu et al., 2011) y converge hacia *teaching and learning analytics* (Sergis & Sampson, 2017). La relación es **asimétrica**: TA usa datos de LA como insumo, pero LA rara vez se ocupa de datos de la práctica docente. La frontera es difusa en la literatura, pues muchos artículos de tableros docentes se etiquetan solo como LA **[I]**. Esto implica que TA **no puede recuperarse solo por su etiqueta**.

**P2. Emergencia de GenAI [S/I].** En la era pre-ChatGPT, las técnicas cercanas eran PLN, generación automática de retroalimentación, agentes conversacionales y GAN para datos sintéticos. Misiejuk et al. (2025) incluyen GAN y BERT junto a GPT, lo que confirma una **capa histórica** pre-2022 **[S]**. La aceleración posterior a noviembre de 2022 se observa en la secuencia institucional editorial JLA 2023 → LAK 2024 → sección especial JLA 2025 **[S]**. La forma de la curva anual está **[P]**.

**P3. Subtemas y métodos predominantes [S].** Con GenAI predominan codificación de discurso, puntuación automática y clasificación; con menor frecuencia aparecen resumen y datos sintéticos (Misiejuk et al., 2025). También destacan retroalimentación personalizada y aprendizaje adaptativo con GPT-4/BERT, con datos estructurados de LMS para la parte de ML y fuerte concentración en educación superior y países de altos ingresos (Rodríguez-Ortiz et al., 2025) **[S para retroalimentación y aprendizaje adaptativo con GPT-4/BERT; P para los datos de LMS y la concentración geográfica, no reverificados en la actualización 2026]**. En TA predominan tableros/sistemas y evaluación de la enseñanza (Bayrak Karsli et al., 2025).

**P4. Intersección triple [I/P].** Existe evidencia aislada (tableros docentes con LLM, explicaciones generadas para docentes), pero la etiqueta "teaching analytics" casi no aparece junto a GenAI. Clasificación: **emergente-escasa**. LA+GenAI se clasifica como **emergente con masa crítica incipiente** (dos revisiones sistemáticas en 2025 con 41 y 26 estudios empíricos, respectivamente).

**P5. Vacíos [S/I]:**
- **Conceptuales:** no existe un marco que distinga GenAI como herramienta, dato y contexto en TA.
- **Metodológicos:** validación de salidas de LLM en pipelines analíticos (Misiejuk et al., 2025) y reproducibilidad ante modelos cambiantes.
- **Empíricos:** pocos estudios longitudinales o con resultados de aprendizaje sostenidos (Khosravi et al., 2025; Rodríguez-Ortiz et al., 2025).
- **Docentes:** baja participación en el co-diseño.
- **Éticos:** privacidad de diálogos, sesgo y dependencia cognitiva.
- **Geográficos:** América Latina subrepresentada; esta es una **oportunidad explícita** para un equipo colombiano.

**P6 y P7.** Se responden en las secciones 4, 5 y 8.

### 3.4 Actualización 2026 (enero a comienzos de octubre de 2026)

**Alcance y límites.** "Verificado" significa que autoría y DOI (o identificador arXiv/Anthology) se leyeron en la página del editor, del registro o del preprint. Los roles de GenAI siguen la tipología (a)–(d) de la sección 2; los marcados con * los asigna esta actualización **[I]**. La cobertura es **parcial**: no se enumeraron los artículos de LAK26, L@S 2026 se conoce solo por su programa, y no se buscó en AIED, EDM, BJET ni *Computers & Education*. Todas las cifras se atribuyen a su fuente; no hay conteos bibliométricos propios.

**Tabla 3.4a. Estudios primarios y editoriales verificados (2026)**

| Referencia | Tipo | Foco | Rol | Método / muestra (según la fuente) | DOI |
|---|---|---|---|---|---|
| Barthakur, Viberg, Kizilcec, Baker & Dawson, JLA 13(1), 1–6 | Editorial | LA, competencias del siglo XXI | (d) | Introduce cinco estudios en cuatro temas; pide evaluación basada en procesos y gobernanza | 10.18608/jla.2026.9743 |
| Xu, Guan, Shi, Chen & Yu, JLA 13(1), 7–30 | Empírico | Currículos de posgrado | (a) | LLM mapean 200 cursos a 38 competencias (7.600 puntuaciones anotadas a mano); ningún modelo alcanzó precisión humana fina | 10.18608/jla.2026.9127 |
| Hilliger et al., JLA 13(1), 74–88 | Empírico (DBR) | Autorregulación con chatbot GAI | (c) | Tres ciclos de diseño; 276 estudiantes, 10 cursos | 10.18608/jla.2026.9143 |
| Ren et al., JLA 13(2), 1–24 | Empírico | Codificación de protocolos de pensamiento en voz alta | (a) | GPT-4o, Claude 3.5 Sonnet y Gemini 1.5 Pro; 600 verbalizaciones; exactitud mayor en matemáticas que en biología | 10.18608/jla.2026.9025 |
| Claassen et al., *IJETHE* 23, art. 43 | Empírico | Docentes: LA y GenAI en decisiones de diseño | (c)* | 11 grupos focales (21 participantes en LA, 18 en GenAI) en una universidad australiana; análisis temático + ENA | 10.1186/s41239-026-00619-4 |
| Rienties, Divjak & Law, *IJETHE* 23, art. 48 | Editorial | LA + GenAI, diseño y decisión | (d) | Presenta cuatro estudios; pide estudios de intervención | 10.1186/s41239-026-00622-9 |
| Svetec, Divjak & Kadoić, *IJETHE* 23, art. 45 | Empírico | Habilitadores de intervenciones basadas en LA | (d)* | Encuesta (n = 34), dos rondas Delphi, priorización SNAP; siete habilitadores; GenAI es marco, no foco | 10.1186/s41239-026-00620-x |
| Chen, Han, Niu & He, *Scientific Reports* 16, art. 7602 | Empírico | Interacción docente–estudiante en video | (a)* | VisualGLM-6B ajustado; 2.380 imágenes anotadas; exactitud 82 % en 100 imágenes | 10.1038/s41598-026-38626-0 |

Preprints verificados en arXiv (no arbitrados): Borchers et al. (arXiv:2603.27806; 117 docentes aceptaron ≈ 80 % de 1.349 retroalimentaciones de LLM sin cambios); Chen et al. (arXiv:2603.27440; kappa 0,78 en conjunto reservado frente a 0,91–0,93 en desarrollo); Liu et al. (arXiv:2607.28890; Jaccard humano–LLM 0,30 frente a 0,52 humano–humano); Ma et al. (arXiv:2603.22674; tablero docente con resúmenes de chats estudiante–GenAI; muestra no leída); Lu & Hsu (arXiv:2603.03307; TopicENA). Ítems adyacentes o no verificados, con sus DOI, en las secciones 12.3 y 12.4.

**Tabla 3.4b. Revisiones de 2026 y corpus reportado (según cada fuente)**

| Referencia | Alcance | Bases | Tamaño reportado |
|---|---|---|---|
| Razami et al. | GenAI en LA y apoyo a decisiones | Scopus, WoS, IEEE | 38 incluidos; cadena y ventana no declaradas |
| Ivanova & Terzieva | LLM en sistemas educativos inteligentes | Google Scholar, ACM, IEEE, Scopus, WoS | 8.200 → 5.436 → 724 → 80 |
| Zhang, Deng & Shadiev | Metarrevisión de GenAI en educación | No declaradas | 35 revisiones |
| Ikram et al. | IA y aprendizaje personalizado | Solo Scopus, solo títulos | 219 → 31 |
| Keržič et al. | Bibliometría de LA en educación superior | Scopus | 8.979 documentos, hasta diciembre de 2024 |

**Respuestas actualizadas a las preguntas de investigación**

- **P2 (emergencia) [S/I].** La secuencia institucional (editorial JLA 2023 → LAK 2024 → sección especial JLA 2025) suma un cuarto eslabón en 2026: JLA 13(1) y LAK26, con 372 envíos de 46 países, 107 aceptados (67 completos, 40 cortos) según su portada. JLA 13(2) (31 de agosto de 2026) no tiene editorial ni sección especial. El mapeo de Švábenský et al. (936 artículos de LAK 2011–2025) registra el crecimiento del clúster "Automated Feedback" entre 2021 y 2025, indicio de continuidad pre-GenAI **[I]**. La forma de la curva anual de producción sigue **[P]**.
- **P3 (temas y métodos) [S para los ítems verificados; I para el campo].** Domina el LLM como codificador o puntuador con comparación contra juicio humano, coherente con Misiejuk et al. (2025). La muestra verificada no es representativa, y no existe una distribución temática cuantitativa publicada para 2026 **[P]**. La validación da resultados mixtos: sobreajuste de prompts (Chen et al.) y desacuerdo sobre el criterio de verdad (Liu et al.: un verificador ciego no distinguió entre codificación humana y de LLM, 51,5 % frente a 48,5 %, con la salvedad de un solo verificador y un solo codebook). Ren et al. usan versiones de modelo antiguas; la dependencia de la versión es una preocupación de reproducibilidad **[I]**.
- **P4 (intersección triple) [S/I].** Sigue **emergente-escasa**, pero con un grupo verificable (tres textos de *IJETHE*, *Scientific Reports*, preprints) y un frente de conferencia no enumerado (L@S 2026, LAK26). La precisión de los modelos multimodales sobre la práctica docente es modesta (82 % en Chen et al.). Borchers et al. observan aceptación de ≈ 80 % de la retroalimentación del LLM sin cambios, mientras Rienties et al. sostienen que "human-in-the-loop" es insuficiente si el humano solo aprueba decisiones tomadas en otra parte; la comparación es indicativa, porque los contextos difieren **[I]**.
- **P5 (vacíos) [S/I/P].** *Conceptual:* sigue sin haber un marco que distinga GenAI como herramienta, dato y contexto en TA. *Empírico:* el editorial de Rienties et al. afirma que la mayor parte de la evidencia es correlacional o autorreportada y pide estudios de intervención **[S]**. *Docente:* ningún estudio de 2026 leído mide la alfabetización de datos del docente con un tablero GenAI **[P]**. *Ético:* las revisiones señalan brechas de gobernanza, privacidad, sesgo y dependencia, pero no se halló un estudio sobre privacidad de diálogos estudiante–LLM **[P]**. *Geográfico:* Bacalso et al. reconocen sesgo hacia Norteamérica, Europa y Australia; Hilliger et al. es trabajo latinoamericano pero en inglés; no se verificó ningún artículo de 2026 en español o portugués, y su ausencia no está probada **[P]**. *Nuevo:* no se encontró una revisión sistemática de TA con lente GenAI, ni una actualización posterior a 2024 de Bayrak Karsli et al.; Cabral et al. (2025, 21 estudios de tableros con IA) ubican GenAI solo como dirección futura **[S para lo leído; I para la ausencia]**.

---

## 4. Estrategia de búsqueda reproducible

### 4.1 Bases y roles

| Base | Rol | Motivo |
|---|---|---|
| Scopus | Principal | Cobertura de actas (LAK vía ACM, LNCS de AIED/EC-TEL) y exportación con referencias citadas |
| Web of Science Core Collection | Principal/contraste | Referencias citadas limpias para co-citación |
| OpenAlex | Contraste abierto y reproducible | Mayor cobertura de actas y acceso abierto; API reproducible |
| Dimensions / Lens | Sensibilidad | Validar cobertura de preprints y actas |
| ERIC, ACM DL, IEEE Xplore | Verificación manual | Actas LAK, L@S, ICALT, EDM |
| arXiv | Capa separada | Preprints, que **no** entran al corpus principal |

### 4.2 Bloques conceptuales

**Bloque LA**
`"learning analytic*" OR "learning data analytic*" OR "multimodal learning analytic*" OR "learning dashboard*" OR "educational data mining"`
→ Captura el núcleo LA. *EDM* amplía hacia métodos; se recomienda usarlo solo en el Escenario B o como variable de sensibilidad.

**Bloque TA**
`"teaching analytic*" OR "teacher analytic*" OR "teacher-facing analytic*" OR "teacher-facing dashboard*" OR "instructor analytic*" OR "instructor dashboard*" OR "educator analytic*" OR "pedagogical analytic*" OR "teaching and learning analytic*" OR "classroom orchestration"`

Advertencias de ambigüedad:
- *"teacher analytics"* puede referirse a analítica **sobre** desempeño docente de recursos humanos.
- *"pedagogical analytics"* tiene uso escaso y heterogéneo.
- *"classroom orchestration"* captura TA implícita, pero también literatura CSCL sin analítica.
- Todo registro recuperado solo por estos términos requiere cribado manual.

**Ampliación sugerida por la evidencia de 2026 [I].** En los artículos de 2026 efectivamente leídos, ninguno usa "teaching analytics" como etiqueta propia: emplean *teaching dashboards*, *instructor insight*, *class-level analytics*, *teacher noticing*, *multimodal learning analytics*, *human-in-the-loop*, *learning design* y *educational decision-making* (Claassen et al., 2026; Chan, 2026; Ma et al., 2026). No se ejecutó una búsqueda sistemática de la frase exacta y ninguna fuente cuantifica su uso, de modo que es inferencia a partir de una muestra pequeña. Se recomienda una ecuación de **sensibilidad** que añada a S2: `"teacher dashboard*" OR "teaching dashboard*" OR "instructor-facing" OR "teacher noticing" OR "classroom orchestration" OR "learning design analytic*" OR "decision-making"` (este último solo combinado con LA o dashboard, por su ruido), y comparar el tamaño y el solapamiento con la versión estricta.

**Bloque GenAI**
`"generative AI" OR "generative artificial intelligence" OR GenAI OR ChatGPT OR "GPT-3*" OR "GPT-4*" OR "large language model*" OR LLM OR LLMs OR "foundation model*" OR "generative language model*" OR "AI chatbot*" OR "conversational agent*" OR "generative pre-trained transformer*"`

Advertencias:
- `GPT` aislado genera ruido (otros acrónimos); usar variantes con número.
- `LLM` coincide con "Master of Laws"; filtrar por área temática.
- *"conversational agent*"* recupera la capa pre-2022; etiquetarla por separado.
- Las revisiones de 2026 usan además `RAG`, `GAN`, `AIGC` y "multimodal large language model*" (Razami et al., 2026; Rienties et al., 2026). Ninguna fuente de 2026 analiza cuantitativamente la deriva terminológica GenAI/LLM/BERT/GAN **[P]**; incluir `AIGC` y "multimodal large language model*" como variantes de sensibilidad es una decisión de diseño **[I]**.

**Capa histórica (pre-2022, separada)**
`"natural language generation" OR "automated feedback generation" OR "pedagogical agent*" OR chatbot*` (2010–2022), combinada con LA/TA.

### 4.3 Ecuaciones por base

**Scopus**
```
S1 (LA):       TITLE-ABS-KEY("learning analytic*" OR "multimodal learning analytic*" OR "learning dashboard*")
S2 (TA):       TITLE-ABS-KEY("teaching analytic*" OR "teacher analytic*" OR "teacher-facing analytic*"
               OR "teacher-facing dashboard*" OR "instructor analytic*" OR "instructor dashboard*"
               OR "educator analytic*" OR "pedagogical analytic*" OR "teaching and learning analytic*")
S3 (GenAI):    TITLE-ABS-KEY("generative AI" OR "generative artificial intelligence" OR genai OR chatgpt
               OR "GPT-3*" OR "GPT-4*" OR "large language model*" OR llm OR llms OR "foundation model*"
               OR "generative language model*" OR "AI chatbot*" OR "generative pre-trained transformer*")
S4a: S1 AND S3
S4b: S2 AND S3
S4c: (S1 OR S2) AND S3
S4d: S1 AND S2 AND S3
Filtros: PUBYEAR > 2009 AND PUBYEAR < 2027; DOCTYPE(ar OR cp OR re OR ch); LANGUAGE(english OR spanish OR portuguese)
```

**Web of Science (Core Collection)**
```
TS=("learning analytic*" OR "multimodal learning analytic*" OR "learning dashboard*")      #1
TS=("teaching analytic*" OR "teacher-facing analytic*" OR "teacher-facing dashboard*"
    OR "instructor analytic*" OR "instructor dashboard*" OR "educator analytic*"
    OR "pedagogical analytic*" OR "teaching and learning analytic*")                       #2
TS=("generative AI" OR "generative artificial intelligence" OR GenAI OR ChatGPT OR "GPT-4*"
    OR "large language model*" OR LLM* OR "foundation model*" OR "AI chatbot*")             #3
(#1 OR #2) AND #3     — Años: 2010–2026; tipos: Article, Proceedings Paper, Review
```
Nota: `LLM*` en WoS es ruidoso; revisar el área "Law".

**OpenAlex (API; reproducible con fecha de consulta)**
```
https://api.openalex.org/works?filter=title_and_abstract.search:("learning analytics" OR "teaching analytics"),
  title_and_abstract.search:("generative AI" OR "large language model" OR ChatGPT OR LLM),
  from_publication_date:2010-01-01&group_by=publication_year
```
Guardar el JSON crudo, la URL exacta y la fecha. OpenAlex no admite truncamiento con `*`, por lo que deben listarse variantes singulares y plurales.

**Dimensions**: búsqueda en "Title and abstract" con las mismas frases exactas; exportar a CSV para bibliometrix.

### 4.4 Criterios de inclusión y exclusión

| Inclusión | Exclusión |
|---|---|
| Educación formal o no formal; LA o TA como objeto, método o contexto | Uso de "analytics" ajeno a educación (negocios, salud) |
| GenAI en cualquiera de los roles (a)–(c); (d) solo se codifica | Menciones de GenAI solo en trabajo futuro |
| Artículos, actas completas, revisiones (2010–2026) | Resúmenes de póster < 4 págs., editoriales en el análisis de redes (se conservan para el análisis cualitativo) |
| Inglés, español, portugués | Duplicados, retractaciones |

### 4.5 Cribado y normalización

1. **Deduplicación:** DOI → título normalizado (minúsculas, sin puntuación) + año ± 1 → revisión manual de casos dudosos.
2. **Cribado en dos etapas:** (i) título y resumen, con dos revisores sobre una muestra del 20 % para calcular κ de Cohen (meta ≥ 0,70) antes de continuar con un solo revisor; (ii) texto completo para el corpus focal GenAI. Opcionalmente, un LLM como tercer clasificador, **nunca como único**, con tasa de acuerdo reportada.
3. **Codificación:** foco (TA / LA / ambos), rol GenAI (a–d), nivel educativo, tipo de dato, método y tipo de evidencia (empírica / conceptual).
4. **Normalización:**
   - Tesauro de palabras clave con término preferido único por concepto (p. ej., `large language models` ← `llm`, `llms`, `large language model`), con versionado.
   - Autores por ORCID/ID de Scopus.
   - Afiliaciones por ROR.
5. **Registro:** diagrama PRISMA 2020 (Page et al., 2021), o PRISMA-ScR (Tricco et al., 2018) para la parte de alcance.
6. **Campos a exportar:** título, resumen, palabras clave de autor e índice, autores, ID de autores, afiliaciones, año, fuente, referencias citadas, DOI, tipo documental, citas, áreas temáticas y financiación.

---

## 5. Matriz de viabilidad de tech mining

| Criterio | Valoración | Evidencia | Riesgo | Mitigación |
|---|---|---|---|---|
| Volumen documental | **Alta** (LA), **Media-baja** (LA+GenAI), **Baja** (TA+GenAI) | LA es un campo con conferencia y revista desde 2011–2014 [S]; las revisiones de GenAI-LA hallan 41 y 26 estudios empíricos [S]; los conteos propios están [P] | Redes inestables en el subcorpus focal | Escenario C; umbrales operativos (abajo) |
| Calidad/disponibilidad de metadatos | **Media-alta** | Scopus/WoS exportan referencias; las actas LAK (ACM) están indexadas [I] | Actas de 2025–2026 con indexación tardía; resúmenes incompletos | Complementar con OpenAlex; fecha de corte explícita |
| Consistencia terminológica | **Baja** (TA), **Media** (GenAI) | TA es difusa y suele etiquetarse como LA [I]; los términos GenAI cambian rápido (GPT-3 → GPT-4 → "LLM") | Infra-recuperación de TA; deriva léxica | Tesauro y codificación manual del foco TA |
| Recuperación de referencias citadas | **Media** | Disponible en Scopus/WoS; parcial en OpenAlex [I] | Literatura reciente con pocas citas acumuladas | Usar **acoplamiento** (no co-citación) en 2022–2026 |
| Sensibilidad al año 2022 | **Alta** | Secuencia editorial 2023–2025 [S] | Confundir volumen con madurez; efecto ChatGPT en las palabras clave | Periodización probada con datos; citas normalizadas |
| Sesgo por indexación | **Media** | Rodríguez-Ortiz et al. (2025) muestran sesgo geográfico [S] | Subrepresentación de América Latina y de actas | Multibase; reportar cobertura por base |
| Separar TA de LA | **Baja-media** | Bayrak Karsli et al. (2025) lo lograron para TA sin GenAI [S] | Clasificación subjetiva | Codificación doble con κ; categoría "ambos" |
| Contribución original | **Alta** | No se halló mapeo bibliométrico de TA+LA+GenAI con evolución temporal [I/P] | Publicaciones concurrentes (campo volátil) | Búsqueda de vigilancia mensual; preregistro OSF |

**Umbrales operativos sugeridos [I]** (reglas prácticas de la comunidad bibliométrica, no estándares formales):
- **≥ 200 documentos** para co-ocurrencia de palabras clave con *clusters* estables.
- **≥ 300–500 documentos** con referencias para acoplamiento bibliográfico fiable.
- **Co-citación:** solo si ≥ 50 referencias citadas con frecuencia ≥ 5; poco probable en 2022–2026.
- **Coautoría:** ≥ 150 documentos y ≥ 100 autores con ≥ 2 trabajos.
- **Modelado temático (LDA/BERTopic):** ≥ 300 resúmenes; si hay menos, solo de forma exploratoria.
- Si el corpus focal es **< 100**, pasar a *scoping review* con mapa descriptivo y abandonar redes inferenciales.

### Escenarios

| Escenario | Ventajas | Amenazas a la validez | Corpus aconsejable |
|---|---|---|---|
| **A. Núcleo estricto** (TA/LA explícitos + GenAI) | Alta precisión; fácil de reproducir | Baja exhaustividad; TA casi ausente; redes inestables | Útil solo si ≥ 200 tras cribado [P]; probablemente insuficiente [I] |
| **B. Corpus ampliado** (+sinónimos, EDM, AIED con analítica) | Mayor volumen; captura TA implícita | Ruido; frontera difusa con AIED; mucha carga de cribado | 300–800 tras cribado |
| **C. Híbrido** (TA/LA 2010–2026 amplio + focal GenAI 2022–2026 + *scoping review*) | Sirve a ambos artículos; la serie larga contextualiza el quiebre | Dos corpus por documentar; riesgo de solapamiento entre artículos | Amplio: miles (LA) [P]; focal: 200–800 |

**Recomendación: Escenario C**, con el corpus focal construido según las reglas de B y un subconjunto "núcleo A" reportado como análisis de sensibilidad.

**Efecto de la evidencia de 2026 sobre la matriz [S/I].**
- **Volumen:** las revisiones de 2026 verificadas incluyen entre 31 y 80 estudios (38 en la de GenAI en LA, Razami et al.); el hallazgo es que el número de estudios incluidos en revisiones de GenAI + LA ronda **decenas, no cientos**, lo que respalda la cautela sobre el Escenario A (umbral ≥ 200 tras cribado). Esas cifras son estudios incluidos tras criterios de calidad, no el corpus recuperado por una ecuación, por lo que **no deben usarse para fijar los umbrales**; las ecuaciones propias siguen **[P]**.
- **Cobertura de bases:** de las cinco fuentes de 2026 que declaran bases, Scopus aparece en todas y WoS en tres; ninguna usa OpenAlex ni Dimensions. Como buena parte de la evidencia docente de 2026 está en actas (LAK, L@S, WACV, AIME-Con), preprints y revistas de acceso abierto, depender de una sola base comercial es un riesgo; conviene sumar ACM DL, OpenAlex y arXiv. La proporción indexada en Scopus o WoS no se verificó **[P]**.
- **Consistencia terminológica de TA:** la valoración "Baja" se refuerza (sección 4.2).
- **Reportabilidad:** Razami et al. no declaran la cadena de búsqueda ni la ventana temporal, y Bacalso et al. presentan inconsistencias internas de conteo; esto refuerza la exigencia de registrar la cadena exacta y la fecha de cada exportación.

---

## 6. Diseño propuesto para el Artículo 1

**Título tentativo**
- ES: *De los tableros a los modelos de lenguaje: evolución de Learning Analytics y Teaching Analytics ante la IA generativa (2010–2026)*
- EN: *From Dashboards to Language Models: The Evolution of Learning and Teaching Analytics in the Age of Generative AI (2010–2026)*

**Objetivo.** Caracterizar la evolución conceptual, temática y estructural de LA y TA entre 2010 y 2026, y evaluar si la expansión de GenAI constituye una discontinuidad o una aceleración de agendas preexistentes.

**Preguntas de investigación**
1. ¿Cómo evolucionaron la producción, las fuentes, los países y las comunidades de LA y TA?
2. ¿Qué temas emergen, se consolidan, se fusionan o declinan entre periodos?
3. ¿Hay evidencia de quiebre estructural en 2022–2023 en la producción y en la composición temática?
4. ¿Cómo cambia la proporción y la posición de TA dentro de LA?

**Corpus.** Corpus amplio S1 ∪ S2 (Scopus + WoS, 2010–2026), deduplicado, con la variable de codificación GenAI (S3) como marcador.

**Periodización (por probar, no presupuesta)**
- P1, 2011–2015: fundación (LAK, JLA en 2014).
- P2, 2016–2019: institucionalización y tableros.
- P3, 2020–2022: pandemia, analítica remota y ML.
- P4, 2023–2026: GenAI.

Validación:
- Contrastar con la detección de puntos de cambio sobre la serie anual (p. ej., regresión segmentada).
- Comparar con cortes alternativos (2022 vs. 2023) y reportar la sensibilidad de los *clusters* a la elección del corte.

**Indicadores.** Producción anual y tasa de crecimiento (CAGR por periodo); fuentes (Bradford); países y colaboración internacional; autores (Lotka, índice h local); citas normalizadas por año y campo; frecuencia y novedad de palabras clave; evolución temática (Cobo et al., 2011); acoplamiento por periodo.

**Visualizaciones**
- Tendencia anual con puntos de cambio.
- *Thematic evolution* (Sankey entre periodos).
- *Strategic diagram* (centralidad × densidad) por periodo.
- *Three-fields plot* (países–palabras clave–fuentes).
- Red temporal de palabras clave (superposición por año medio en VOSviewer).
- Mapa de acoplamiento por periodo, más co-citación solo para P1–P3.

**Interpretación prudente**
- Normalizar por el crecimiento general de la producción en educación e IA; un aumento de documentos **no** equivale a madurez.
- Usar indicadores de madurez: proporción de estudios empíricos, revisiones sistemáticas, estabilidad de *clusters* y diversidad de fuentes.

**Amenazas y mitigación**
- Deriva terminológica → tesauro por periodo.
- Indexación tardía de 2026 → corte explícito y nota de incompletitud.
- Sesgo de base → comparación Scopus vs. WoS vs. OpenAlex.
- Confusión TA/LA → codificación manual de una muestra estratificada.

**Contribución**
- **Teórica:** primera periodización empírica conjunta LA–TA que prueba la hipótesis de discontinuidad GenAI.
- **Práctica:** guía para comités de programa e investigadores sobre qué agendas se desplazan y cuáles persisten.

---

## 7. Diseño propuesto para el Artículo 2

**Título tentativo**
- ES: *Frentes emergentes en la intersección de IA generativa, Learning Analytics y Teaching Analytics: una cartografía temática validada*
- EN: *Emerging Research Fronts at the Intersection of Generative AI, Learning Analytics and Teaching Analytics: A Validated Thematic Mapping*

**Objetivo.** Identificar, nombrar y validar los *clusters* y frentes emergentes en la literatura GenAI + LA/TA (2022–2026), distinguiendo roles de GenAI (a–d) y foco (TA/LA).

**Preguntas de investigación**
1. ¿Qué *clusters* temáticos estructuran el campo?
2. ¿Cuáles cumplen criterios de emergencia?
3. ¿Cómo se distribuyen por rol GenAI y por foco TA/LA?
4. ¿Qué frentes carecen de evidencia empírica?

**Definición operacional de "emergente."** Un *cluster* se considera emergente si cumple ≥ 3 de 5 criterios:
1. **Crecimiento:** su participación en el último año es mayor que su participación media.
2. **Novedad:** año medio de sus términos ≥ percentil 75 del corpus.
3. **Centralidad creciente** entre ventanas anuales.
4. **Explosión:** *burst* de términos o citas (Kleinberg, 2003) cuando sea viable.
5. **Coherencia y persistencia:** presente en ≥ 2 ventanas y validado cualitativamente.

Referencia conceptual: Rotolo et al. (2015).

**Corpus y unidad.** Corpus focal (S4c, construido según reglas del Escenario B, 2022–2026), cribado a texto completo. Unidades:
- Palabras clave normalizadas.
- Términos de resumen (n-gramas / extracción de frases).
- Referencias citadas, para acoplamiento.

**Codificación y validación humana**
- Dos codificadores sobre el 100 % del corpus focal si es < 400 registros, o sobre una muestra estratificada si es mayor.
- Libro de códigos (foco, rol a–d, nivel, dato, método, evidencia).
- Acuerdo κ ≥ 0,70 y resolución por consenso.

**Técnicas**
- Co-ocurrencia de palabras clave y términos con detección de comunidades (Leiden/Louvain; normalización por fuerza de asociación).
- Acoplamiento bibliográfico, técnica principal dada la juventud del corpus.
- Co-citación, solo para identificar la base intelectual.
- BERTopic o LDA como contraste, nunca como evidencia única.
- *Bursts* en CiteSpace.

**Clusters hipotéticos (por confirmar o refutar; NO son hallazgos)**
1. Retroalimentación generativa.
2. Analítica conversacional (trazas de diálogo con LLM).
3. Evaluación e integridad académica (incluye puntuación automática).
4. Orquestación y apoyo a la decisión docente (núcleo TA).
5. Personalización y autorregulación.
6. Diseño instruccional asistido.
7. Analítica multimodal.
8. Explicabilidad y tableros explicados por LLM.
9. Privacidad, equidad y gobernanza.
10. Competencia/alfabetización en IA.

Hipótesis adicional derivada de Misiejuk et al. (2025): un *cluster* metodológico de **"LLM como codificador"** (rol a), posiblemente el más denso **[I]**.

**Visualizaciones**
- Mapa de red con superposición temporal.
- Diagrama estratégico.
- Mapa temático longitudinal por año.
- Sankey de *clusters* entre 2023, 2024, 2025 y 2026.
- **Tabla de evidencias por *cluster***: documentos representativos, rol GenAI, proporción empírica y foco TA/LA.

**Protocolo de nombrado y validación**
1. Extraer los 10 términos más centrales y los 5 documentos más representativos por *cluster* (mayor fuerza de enlace o mayor probabilidad temática).
2. Lectura completa de los representativos por dos investigadores.
3. Nombrado independiente y conciliación.
4. Prueba de intrusión (¿un documento aleatorio de otro *cluster* es detectable?).
5. *Member check* con 2–3 expertos externos de LA/TA.

**Contribución frente al Artículo 1.** El Artículo 1 explica la **trayectoria** del campo (diacrónico, corpus amplio). El Artículo 2 explica la **estructura del frente actual** (sincrónico-reciente, corpus focal y validación cualitativa), con aporte conceptual en la tipología de roles de GenAI.

**Amenazas a la validez**
- Corpus pequeño: inestabilidad → *bootstrap* de *clusters* y reporte de estabilidad.
- Volatilidad: corte temporal estricto y fecha de consulta registrada.
- Sesgo del investigador al nombrar → protocolo ciego.
- Uso de LLM en la clasificación → reportar modelo, versión, prompt y acuerdo.

---

## 8. Tabla de delimitación entre artículos

| Dimensión | Artículo 1 | Artículo 2 | Riesgo de solapamiento |
|---|---|---|---|
| Pregunta | ¿Cómo evolucionaron LA y TA y hubo quiebre GenAI? | ¿Qué frentes estructuran hoy GenAI + LA/TA? | Medio: ambos tratan 2023–2026 |
| Corpus | Amplio LA ∪ TA, 2010–2026 | Focal GenAI ∩ (LA ∪ TA), 2022–2026, cribado a texto completo | Bajo si el periodo P4 del Art. 1 se presenta agregado |
| Métodos | Indicadores de desempeño, evolución temática, puntos de cambio, co-citación histórica | Acoplamiento, comunidades, *bursts*, topic modeling, validación cualitativa | Bajo |
| Resultados esperados | Periodización, trayectoria de TA dentro de LA, indicadores de madurez | Mapa de *clusters*, tipología de roles GenAI, frentes sin evidencia | Bajo |
| Contribución | Histórica-estructural | Conceptual-prospectiva | Bajo |
| Regla anti-redundancia | El Art. 1 **no** nombra *clusters* finos de GenAI; los remite al Art. 2 | El Art. 2 **no** reporta series 2010–2022; cita al Art. 1 | — |

---

## 9. Agenda de investigación

Prioridad: N = novedad, F = factibilidad, I = impacto (1–3).

| # | Pregunta o hipótesis | N | F | I | Prioridad |
|---|---|---|---|---|---|
| 1 | H: Después de 2022, la proporción de trabajos LA con contenido TA aumenta, porque GenAI abarata herramientas para docentes | 3 | 3 | 3 | Alta |
| 2 | H: El rol (a) "GenAI como instrumento analítico" domina el frente, por encima de (b) y (c) | 2 | 3 | 3 | Alta |
| 3 | ¿Qué proporción de estudios GenAI-LA valida las salidas del LLM contra codificación humana, y con qué métricas? | 3 | 3 | 3 | Alta |
| 4 | H: Los *clusters* GenAI-LA tienen menor densidad interna que los *clusters* LA clásicos (campo fragmentado) | 3 | 2 | 2 | Alta |
| 5 | ¿Existe un quiebre estructural en 2023 en la red de palabras clave de LA, o solo un efecto de volumen? | 2 | 3 | 3 | Alta |
| 6 | ¿Cómo se representan América Latina y el español/portugués en GenAI-LA/TA? | 2 | 3 | 2 | Media |
| 7 | ¿Qué tipos de datos docentes (planeación, retroalimentación, discurso en aula) se analizan con LLM? | 3 | 2 | 3 | Media |
| 8 | H: Los trabajos de explicabilidad de tableros mediante LLM forman un frente emergente de TA | 3 | 2 | 2 | Media |
| 9 | ¿Cómo cambian las referencias teóricas (aprendizaje autorregulado, ciclo de Clow) en la literatura GenAI-LA frente a la LA clásica? | 2 | 2 | 2 | Media |
| 10 | ¿Qué proporción del frente GenAI-LA/TA es opinativo (rol d) frente a empírico, y cómo evoluciona? | 2 | 3 | 2 | Media |
| 11 | ¿Qué brechas éticas (privacidad de diálogos, consentimiento) se discuten y cuáles se operacionalizan? | 2 | 2 | 3 | Media |
| 12 | ¿Son estables los *clusters* obtenidos entre Scopus, WoS y OpenAlex? (aporte metodológico) | 3 | 2 | 2 | Media (vía *Scientometrics*) |
| 13 | H (2026): la agenda normativa pide agencia docente contestable, pero la evidencia observacional muestra alta aceptación de la salida del LLM sin cambios (≈ 80 % en Borchers et al., preprint); ¿cómo se distribuye esa tensión en el frente GenAI–TA? | 3 | 2 | 3 | Media (requiere leer L@S 2026 y LAK26) |
| 14 | ¿Cuánto del corpus TA se pierde si se exige la etiqueta "teaching analytics" frente a la ecuación de sensibilidad (tableros docentes, *teacher noticing*, orquestación)? | 3 | 3 | 3 | Alta |
| 15 | ¿Existe una revisión sistemática o un mapeo de TA con lente GenAI posterior a 2024? (nicho abierto si el recuento propio lo confirma) | 3 | 3 | 2 | Media |

---

## 10. Plan de ejecución (10 semanas)

| Semana | Actividad | Decisión de calidad | Producto verificable |
|---|---|---|---|
| 1 | Prueba de ecuaciones S1–S4d en Scopus, WoS y OpenAlex; conteos | ¿El corpus focal alcanza los umbrales? Elegir el escenario final | Hoja de conteos con fecha y consulta exacta |
| 2 | Preregistro (OSF): protocolo, criterios y libro de códigos | Aprobación del protocolo por el equipo | DOI de OSF |
| 3 | Exportación, deduplicación y PRISMA de identificación | Regla de deduplicación documentada | Exportaciones crudas + script |
| 4 | Cribado de título/resumen; piloto κ | κ ≥ 0,70 o reentrenamiento | Registro de cribado |
| 5 | Texto completo del corpus focal; codificación (a–d, TA/LA) | Resolución de desacuerdos | Base codificada v1 |
| 6 | Tesauro y normalización de palabras clave, autores y afiliaciones | Revisión doble del tesauro | Tesauro versionado |
| 7 | Art. 1: indicadores, puntos de cambio, evolución temática | Prueba de sensibilidad del corte 2022/2023 | Figuras y tablas del Art. 1 |
| 8 | Art. 2: redes, comunidades, *bursts*, BERTopic de contraste | Estabilidad por *bootstrap* | Mapas y matrices |
| 9 | Validación cualitativa de *clusters*; *member check* | Nombres consensuados | Tabla de evidencias por *cluster* |
| 10 | Redacción, control de coherencia afirmaciones–citas–ecuaciones, paquete de reproducibilidad | Lista de verificación final | Dos manuscritos + repositorio |

**Archivos a conservar:** consultas exactas y fechas; exportaciones originales sin modificar; reglas y scripts de deduplicación; tesauro; decisiones de cribado con motivo; libro de códigos y codificaciones; matrices y redes (`.net`, `.gml`); tablas de datos; versiones de software (R/bibliometrix, VOSviewer, CiteSpace, Python) y, si se usan LLM, el modelo, la versión, los prompts y la fecha.

### Flujo de herramientas

| Pregunta | Técnica | Herramienta |
|---|---|---|
| P1, P2 (evolución) | Desempeño, evolución temática, puntos de cambio | bibliometrix/biblioshiny; R (`strucchange`) |
| P3 (subtemas) | Co-ocurrencia + codificación | VOSviewer; Python/R; tesauro propio (p. ej., tm2+) |
| P4 (intersección) | Conteos por conjunto + lectura completa | Scopus/WoS/OpenAlex + hoja de codificación |
| Art. 2 (emergencia) | Acoplamiento, *bursts*, comunidades | VOSviewer, CiteSpace, `igraph`/`networkx` |
| Contraste temático | BERTopic/LDA | Python |

---

## 11. Limitaciones y riesgos

- **Disponibilidad de datos:** este informe no contiene conteos propios; todos los volúmenes están **[P]** hasta ejecutar la semana 1. El acceso a Scopus/WoS depende de la suscripción institucional.
- **Sesgos:** sesgo de indexación (inglés, Norte Global, revistas frente a actas); sesgo de etiqueta (TA invisible bajo LA); sesgo de publicación (resultados positivos de GenAI).
- **Volatilidad:** el campo cambia mensualmente; los resultados de 2026 estarán incompletos. Se recomienda corte fijo y actualización documentada.
- **Confusión terminológica:** ambigüedad de LLM (Derecho), GPT y "teacher analytics" (RR. HH.); mitigación con filtros de área y cribado.
- **Ética:** si se usan LLM para clasificar, existe riesgo de sesgo y falta de reproducibilidad; reportar todo y nunca delegar decisiones finales. Revisar las políticas de uso de GenAI de cada revista destino.
- **Reproducibilidad:** las bases propietarias cambian retroactivamente; deben conservarse las exportaciones crudas, y OpenAlex sirve como capa abierta.
- **Ítems [P] resueltos en la actualización 2026:** autoría, título, páginas y fecha de LAK 2025 y L@S 2025 (verificados en OpenAlex; Crossref y la ACM DL no se abrieron) y el volumen de Misiejuk, Kaliisa & Scianna (2024). **Siguen [P]:** el método de *Chat-LAD*, la carga del URL de UNESCO (2023), y las herramientas, bases y tamaño de corpus de Bayrak Karsli et al. (2025).
- **Limitaciones de la actualización 2026:**
  - **Bloqueos de acceso:** la API de Crossref estuvo bloqueada desde la terminal y devolvió HTTP 429 por WebFetch; OpenAlex falló como búsqueda; ScienceDirect, UNESDOC y varias páginas de la ACM DL no cargaron (robots.txt o errores).
  - **Alcance no cubierto:** no se enumeraron los artículos de LAK26 (solo su portada: 372 envíos, 107 aceptados); L@S 2026 se conoce solo por títulos y autores; no se buscó en AIED, EDM, BJET, *Computers & Education*, CAEAI, *Smart Learning Environments* ni *Teaching and Teacher Education* para estudios primarios. De JLA solo se verificaron cuatro artículos en profundidad. No se buscó en Scopus, WoS, OpenAlex, Dimensions, SciELO ni Redalyc. Por eso la ausencia de trabajos en español o portugués, de revisiones de TA con GenAI y de estudios bibliométricos de la intersección triple **no está probada**.
  - **Fechas:** hay discrepancias sin resolver en Ren et al., Claassen et al., Lu & Hsu y Lekshmi Narayanan et al. **[P]**.
  - **Muestra:** la muestra verificada es parcial y no representativa; las conclusiones sobre distribución de temas y métodos son lecturas de esa muestra **[I]**.

**Control de calidad realizado:**
- Las afirmaciones **[S]** del resumen se corresponden con fuentes verificadas en sus páginas editoriales o repositorios (JLA, ORO-Open University, MDPI, Springer, ACM, arXiv).
- Las ecuaciones de la sección 4 cubren todos los términos de los bloques solicitados.
- Las definiciones (sección 2) son coherentes con las referencias citadas.
- No se introdujeron conteos propios.
- Actualización 2026: cada DOI o identificador de las secciones 3.4 y 12.3 se leyó en la página del editor, del registro o del preprint; lo que no se pudo verificar está separado en 12.4.

---

## 12. Bibliografía verificable (APA 7)

### 12.1 Fuentes académicas revisadas por pares

- Aria, M., & Cuccurullo, C. (2017). bibliometrix: An R-tool for comprehensive science mapping analysis. *Journal of Informetrics, 11*(4), 959–975. https://doi.org/10.1016/j.joi.2017.08.007
- Bayrak Karsli, M., Cilligol Karabey, S., Kaba, E., Guler, M., Aydemir Arslan, M., & Kursun, E. (2025). Research trends in teaching analytics: Bibliometric mapping and content analysis. *Technology, Knowledge and Learning, 30*(3), 1345–1369. https://doi.org/10.1007/s10758-024-09773-y
- Chen, C. (2006). CiteSpace II: Detecting and visualizing emerging trends and transient patterns in scientific literature. *Journal of the American Society for Information Science and Technology, 57*(3), 359–377. https://doi.org/10.1002/asi.20317
- Cobo, M. J., López-Herrera, A. G., Herrera-Viedma, E., & Herrera, F. (2011). An approach for detecting, quantifying, and visualizing the evolution of a research field: A practical application to the Fuzzy Sets Theory field. *Journal of Informetrics, 5*(1), 146–166. https://doi.org/10.1016/j.joi.2010.10.002
- Ferguson, R. (2012). Learning analytics: Drivers, developments and challenges. *International Journal of Technology Enhanced Learning, 4*(5/6), 304–317. https://doi.org/10.1504/IJTEL.2012.051816
- Gašević, D., Dawson, S., & Siemens, G. (2015). Let's not forget: Learning analytics are about learning. *TechTrends, 59*(1), 64–71. https://doi.org/10.1007/s11528-014-0822-x
- Gašević, D., Siemens, G., & Sadiq, S. (2023). Empowering learners for the age of artificial intelligence. *Computers and Education: Artificial Intelligence, 4*, 100130. https://doi.org/10.1016/j.caeai.2023.100130
- Holstein, K., McLaren, B. M., & Aleven, V. (2019). Co-designing a real-time classroom orchestration tool to support teacher–AI complementarity. *Journal of Learning Analytics, 6*(2), 27–52. https://doi.org/10.18608/jla.2019.62.3
- Kasneci, E., Seßler, K., Küchemann, S., et al. (2023). ChatGPT for good? On opportunities and challenges of large language models for education. *Learning and Individual Differences, 103*, 102274. https://doi.org/10.1016/j.lindif.2023.102274
- Khosravi, H., Shibani, A., Jovanovic, J., Pardos, Z. A., & Yan, L. (2025). Generative AI and learning analytics: Pushing boundaries, preserving principles. *Journal of Learning Analytics, 12*(1), 1–11. https://doi.org/10.18608/jla.2025.8961
- Khosravi, H., Viberg, O., Kovanovic, V., & Ferguson, R. (2023). Generative AI and learning analytics. *Journal of Learning Analytics, 10*(3), 1–6. https://doi.org/10.18608/jla.2023.8333
- Kleinberg, J. (2003). Bursty and hierarchical structure in streams. *Data Mining and Knowledge Discovery, 7*(4), 373–397. https://doi.org/10.1023/A:1024940629314
- Mangaroska, K., & Giannakos, M. (2019). Learning analytics for learning design: A systematic literature review of analytics-driven design to enhance learning. *IEEE Transactions on Learning Technologies, 12*(4), 516–534. https://doi.org/10.1109/TLT.2018.2868673
- Misiejuk, K., Kaliisa, R., & Scianna, J. (2024). Augmenting assessment with AI coding of online student discourse: A question of reliability. *Computers and Education: Artificial Intelligence, 6*, Article 100216. https://doi.org/10.1016/j.caeai.2024.100216
- Misiejuk, K., López-Pernas, S., Kaliisa, R., & Saqr, M. (2025). Mapping the landscape of generative artificial intelligence in learning analytics: A systematic literature review. *Journal of Learning Analytics, 12*(1), 12–31. https://doi.org/10.18608/jla.2025.8591
- Ndukwe, I. G., & Daniel, B. K. (2020). Teaching analytics, value and tools for teacher data literacy: A systematic and tripartite approach. *International Journal of Educational Technology in Higher Education, 17*, 22. https://doi.org/10.1186/s41239-020-00201-6
- Ochoa, X., & Worsley, M. (2016). Augmenting learning analytics with multimodal sensory data. *Journal of Learning Analytics, 3*(2), 213–219. https://doi.org/10.18608/jla.2016.32.10
- Ouyang, F., & Jiao, P. (2021). Artificial intelligence in education: The three paradigms. *Computers and Education: Artificial Intelligence, 2*, 100020. https://doi.org/10.1016/j.caeai.2021.100020
- Page, M. J., McKenzie, J. E., Bossuyt, P. M., et al. (2021). The PRISMA 2020 statement: An updated guideline for reporting systematic reviews. *BMJ, 372*, n71. https://doi.org/10.1136/bmj.n71
- Prieto, L. P., Sharma, K., Kidzinski, Ł., Rodríguez-Triana, M. J., & Dillenbourg, P. (2018). Multimodal teaching analytics: Automated extraction of orchestration graphs from wearable sensor data. *Journal of Computer Assisted Learning, 34*(2), 193–203. https://doi.org/10.1111/jcal.12232
- Rodríguez-Ortiz, M. Á., Santana-Mancilla, P. C., & Anido-Rifón, L. E. (2025). Machine learning and generative AI in learning analytics for higher education: A systematic review of models, trends, and challenges. *Applied Sciences, 15*(15), 8679. https://doi.org/10.3390/app15158679
- Rotolo, D., Hicks, D., & Martin, B. R. (2015). What is an emerging technology? *Research Policy, 44*(10), 1827–1843. https://doi.org/10.1016/j.respol.2015.06.006
- Schwendimann, B. A., Rodríguez-Triana, M. J., Vozniuk, A., et al. (2017). Perceiving learning at a glance: A systematic literature review of learning dashboard research. *IEEE Transactions on Learning Technologies, 10*(1), 30–41. https://doi.org/10.1109/TLT.2016.2599522
- Sergis, S., & Sampson, D. G. (2017). Teaching and learning analytics to support teacher inquiry: A systematic literature review. En A. Peña-Ayala (Ed.), *Learning analytics: Fundaments, applications, and trends* (pp. 25–63). Springer. https://doi.org/10.1007/978-3-319-52977-6_2
- Siemens, G., & Baker, R. S. J. d. (2012). Learning analytics and educational data mining: Towards communication and collaboration. En *Proceedings of LAK '12* (pp. 252–254). ACM. https://doi.org/10.1145/2330601.2330661
- Slade, S., & Prinsloo, P. (2013). Learning analytics: Ethical issues and dilemmas. *American Behavioral Scientist, 57*(10), 1510–1529. https://doi.org/10.1177/0002764213479366
- Tricco, A. C., Lillie, E., Zarin, W., et al. (2018). PRISMA extension for scoping reviews (PRISMA-ScR). *Annals of Internal Medicine, 169*(7), 467–473. https://doi.org/10.7326/M18-0850
- van Eck, N. J., & Waltman, L. (2010). Software survey: VOSviewer, a computer program for bibliometric mapping. *Scientometrics, 84*(2), 523–538. https://doi.org/10.1007/s11192-009-0146-3
- Vatrapu, R., Teplovs, C., Fujita, N., & Bull, S. (2011). Towards visual analytics for teachers' dynamic diagnostic pedagogical decision-making. En *Proceedings of LAK '11* (pp. 93–98). ACM. https://doi.org/10.1145/2090116.2090129
- Viberg, O., Hatakka, M., Bälter, O., & Mavroudi, A. (2018). The current landscape of learning analytics in higher education. *Computers in Human Behavior, 89*, 98–110. https://doi.org/10.1016/j.chb.2018.07.027
- Wise, A. F., & Jung, Y. (2019). Teaching with analytics: Towards a situated model of instructional decision-making. *Journal of Learning Analytics, 6*(2), 53–69. https://doi.org/10.18608/jla.2019.62.4
- Yan, L., Martinez-Maldonado, R., & Gašević, D. (2024b). Generative artificial intelligence in learning analytics: Contextualising opportunities and challenges through the learning analytics cycle. En *Proceedings of the 14th Learning Analytics and Knowledge Conference (LAK '24)* (pp. 101–111). ACM. https://doi.org/10.1145/3636555.3636856
- Yan, L., Sha, L., Zhao, L., Li, Y., Martinez-Maldonado, R., Chen, G., Li, X., Jin, Y., & Gašević, D. (2024a). Practical and ethical challenges of large language models in education: A systematic scoping review. *British Journal of Educational Technology, 55*(1), 90–112. https://doi.org/10.1111/bjet.13370
- Zawacki-Richter, O., Marín, V. I., Bond, M., & Gouverneur, F. (2019). Systematic review of research on applications of artificial intelligence in higher education. *International Journal of Educational Technology in Higher Education, 16*, 39. https://doi.org/10.1186/s41239-019-0171-0

**Actas con autoría verificada en OpenAlex (Crossref y ACM DL no se abrieron)**
- Wang, Z., Lin, W., & Hu, X. (2025). Self-service teacher-facing learning analytics dashboard with large language models. En *Proceedings of the 15th International Learning Analytics and Knowledge Conference (LAK 2025)* (pp. 824–830). ACM. https://doi.org/10.1145/3706468.3706491
- Yang, C., Wang, D., & Chen, G. (2025). Chat-LAD: Enhancing teacher understanding of learning analytics dashboard with AI-empowered explanations. En *Proceedings of the Twelfth ACM Conference on Learning @ Scale (L@S 2025)* (pp. 197–201). ACM. https://doi.org/10.1145/3698205.3733922 (método y resultados **[P]**)

### 12.2 Informes, ensayos no arbitrados y preprints (sección separada)

- Siemens, G., & Long, P. (2011). Penetrating the fog: Analytics in learning and education. *EDUCAUSE Review, 46*(5), 30–40. https://er.educause.edu/articles/2011/9/penetrating-the-fog-analytics-in-learning-and-education
- Yan, L., Martinez-Maldonado, R., & Gašević, D. (2023). *Generative artificial intelligence in learning analytics* [Preprint]. arXiv. https://arxiv.org/abs/2312.00087
- Journal of Learning Analytics. (s. f.). *Special section on generative AI and learning analytics* [Convocatoria]. https://learning-analytics.info/index.php/JLA/announcement/view/191
- Miao, F., & Holmes, W. (2023). *Guidance for generative AI in education and research*. UNESCO. https://unesdoc.unesco.org/ark:/48223/pf0000386693 (ISBN 9789231006128; metadatos según VOCEDplus; la carga del URL sigue **[P]** porque UNESDOC bloquea la lectura automatizada)

### 12.3 Referencias de 2026 y adyacentes verificadas (actualización)

*Nota:* en varias entradas las fuentes solo traían apellidos; se dejan como aparecen y las iniciales deben completarse. En los capítulos de libro no se capturaron los editores.

- Barthakur, A., Viberg, O., Kizilcec, R. F., Baker, R. S., & Dawson, S. (2026). Advancing 21st-century professional competencies with learning analytics in the age of generative AI [Editorial]. *Journal of Learning Analytics, 13*(1), 1–6. https://doi.org/10.18608/jla.2026.9743
- Bacalso, Villamor, Paclipan, Orquia, Rendon, Albiso, & Himang. (2026). Institutional approaches to generative AI management in higher education: A systematic review. *Frontiers in Education, 11*, Article 1814426. https://doi.org/10.3389/feduc.2026.1814426
- Cabral, L., Pinto, R., & Gonçalves, G. (2025). AI-powered learning analytics dashboards: A systematic review of applications, techniques, and research gaps. *Discover Education, 4*, Article 525. https://doi.org/10.1007/s44217-025-00964-y
- Caspari-Sadeghi, S. (2026). AI literacy for teacher educators: A holistic curriculum for capacity-building in higher education. *Frontiers in Education, 11*, Article 1745768. https://doi.org/10.3389/feduc.2026.1745768
- Chan, M. C. E. (2026). Using multimodal learning analytics to study student engagement and teacher noticing in mathematics classroom: Two different human-in-the-loop workflows. *ZDM Mathematics Education, 58*(5), 899–909. https://doi.org/10.1007/s11858-026-01809-0 (adyacente: no usa GenAI)
- Chen, G., Han, G., Niu, J., & He, J. (2026). Exploring teacher-student interaction through multimodal large language models: An empirical investigation. *Scientific Reports, 16*(1), Article 7602. https://doi.org/10.1038/s41598-026-38626-0
- Claassen, A., Ebbert, D., Kovanović, V., Mirriahi, N., & Dawson, S. (2026). Understanding the role of learning analytics and generative artificial intelligence in decision-making and learning design practice in higher education. *International Journal of Educational Technology in Higher Education, 23*(1), Article 43. https://doi.org/10.1186/s41239-026-00619-4
- Hilliger, I., Pérez-Sanagustín, M., González, C., Villalobos, E., & Celis, S. (2026). A GAI-based chatbot for scaffolding self-regulated learning: Insights from a design-based research approach. *Journal of Learning Analytics, 13*(1), 74–88. https://doi.org/10.18608/jla.2026.9143
- Ikram, Hanefar, Saleem, & Zulfiqar. (2026). Artificial intelligence in education: A systematic review of personalized learning trends and future directions. *Frontiers in Education, 11*, Article 1782626. https://doi.org/10.3389/feduc.2026.1782626
- Ivanova, & Terzieva. (2026). Large language models in intelligent education systems: New educational perspectives—A systematic review. *Information, 17*(5), Article 433. https://doi.org/10.3390/info17050433
- Keržič, Aristovnik, & Ravšelj. (2026). A bibliometric analysis of learning analytics evolution in higher education: From traditional to artificial intelligence-based approaches. En *Artificial intelligence in education technologies: New development and innovative practices* (AIET 2025; Vol. 279, pp. 559–575). Springer. https://doi.org/10.1007/978-981-95-4423-3_35
- Lekshmi Narayanan, A. B., Hassany, M., & Brusilovsky, P. (2026). Can LLMs replace semantic similarity for scoring student code explanations? En *Proceedings of AIME-Con 2026: Full papers* (pp. 92–99). ACL Anthology. https://aclanthology.org/2026.aimecon-main.10/ (sin DOI; fecha "October 2026", por confirmar)
- Razami, Singh, Sampedro, Kovilpillai, Raza, Anwar, Hamdan, & Konno. (2026). A systematic review of generative AI in higher education learning analytics and decision support. *Discover Artificial Intelligence*. https://doi.org/10.1007/s44163-026-01888-8 (adelanto en línea; volumen y artículo no declarados)
- Ren, S., Nguyen, H., Bernacki, M. L., Yu, L., & Greene, J. A. (2026). Using large language models for automated coding of self-regulated learning think-aloud protocol data. *Journal of Learning Analytics, 13*(2), 1–24. https://doi.org/10.18608/jla.2026.9025
- Rienties, B., Divjak, B., & Law, N. (2026). From insight to intervention: Learning analytics and generative AI support for learning design and educational decision-making [Editorial]. *International Journal of Educational Technology in Higher Education, 23*(1), Article 48. https://doi.org/10.1186/s41239-026-00622-9
- Svetec, B., Divjak, B., & Kadoić, N. (2026). From learning analytics to educational interventions: Enhancing decision-making and learning design. *International Journal of Educational Technology in Higher Education, 23*, Article 45. https://doi.org/10.1186/s41239-026-00620-x
- Xu, Z., Guan, X., Shi, C., Chen, Q., & Yu, R. (2026). Evaluating 21st-century competencies in postsecondary curricula with large language models: Performance benchmarking and reasoning-based prompting strategies. *Journal of Learning Analytics, 13*(1), 7–30. https://doi.org/10.18608/jla.2026.9127
- Zhang, Deng, & Shadiev. (2026). A meta-review of generative AI in education: Synthesizing findings from systematic reviews. *Journal of Educational Computing Research, 64*(4), 1068–1092. https://doi.org/10.1177/07356331261419689

**Preprints verificados en arXiv (no arbitrados)**
- Borchers, C., Rodrigues, L., Torrezão da Costa, N., Xavier, C., & Ferreira Mello, R. (2026). *Understanding teacher revisions of large language model-generated feedback* [Preprint]. arXiv:2603.27806. https://arxiv.org/abs/2603.27806
- Chen, E., Wang, I., Yuan, N., Judicke, S., Beigh, K., & Tang, X. (2026). *From tool to teammate: LLM coding agents as collaborative partners for behavioral labeling in educational dialogue analysis* [Preprint]. arXiv:2603.27440. https://arxiv.org/abs/2603.27440
- Kim, M., Kim, S., Lee, S., Yoon, Y., Myung, J., Yoo, H., Lim, H., Han, J., Kim, Y., Ahn, S.-Y., Kim, J., Oh, A., Hong, H., & Lee, T. Y. (2024). *LLM-driven learning analytics dashboard for teachers in EFL writing education* [Preprint]. arXiv:2410.15025. https://arxiv.org/abs/2410.15025
- Liu, A., Esbenshade, L., Xiao, M., Tian, V., Sun, M., Zhang, Z., & He, K. (2026). *Agreement is not quality: Blind expert verification of human and LLM qualitative coding when human consensus is not ground truth* [Preprint]. arXiv:2607.28890. https://arxiv.org/abs/2607.28890 (año según el identificador; fecha no declarada en la página)
- Lu, O. H. T., & Hsu, T. T. Y. (2026). *TopicENA: Enabling epistemic network analysis at scale through automated topic-based coding* [Preprint]. arXiv:2603.03307. https://arxiv.org/abs/2603.03307
- Ma, B., Ren, B., Li, H., Li, G., Chen, L., Shimada, A., & Konomi, S. (2026). *Designing a meta-reflective dashboard for instructor insight into student-AI interactions* [Preprint]. arXiv:2603.22674. https://arxiv.org/abs/2603.22674
- Švábenský, V., Borchers, C., Fortuna, E., Cloude, E. B., & Gašević, D. (2026). *Fifteen years of learning analytics research: Topics, trends, and challenges* [Preprint]. arXiv:2601.07629. https://arxiv.org/abs/2601.07629

### 12.4 Ítems de 2026 NO verificados (no usar como evidencia hasta validar)

- **JLA 13(2), autoría y páginas leídas en la página del número, DOI no verificado:** Borchers, C., Thomas, D. R., Lin, J., & Koedinger, K. R. (2026), estimación de fiabilidad para evaluar habilidad tutorial con LLM, 43–62; Bucalon, B., Yan, L., Shaw, T., Gasevic, D., Kay, J., & Janssen, A. (2026), GenAI en el ciclo de LA para educación en profesiones de la salud, 63–86; Nadine, Junus, Santoso, Michael, & Mannix (2026), revisión sistemática de tableros adaptativos de LA para autorregulación, 105–124; Choi, Karumbaiah, & Matayoshi (2026), estimación de sesgo algorítmico, 147–165 (GenAI no demostrado). Método y muestra no leídos. https://learning-analytics.info/index.php/JLA/issue/view/518
- **JLA 13(1):** Hernández-Campos, Hilliger, & García-Peñalvo (2026), analítica curricular; título, DOI, afiliaciones y rol de GenAI no verificados. https://learning-analytics.info/index.php/JLA/issue/view/517
- **L@S 2026 (solo título y autores en el programa):** Lim, Worden, Sales, & Heffernan, "LLM-generated summaries for teachers: A randomized field experiment in a digital learning platform" (el DOI 10.1145/3774398.3811606 apareció solo en la URL de un resultado de búsqueda); más seis títulos docente-céntricos (TEACHMate; Tao et al.; Li, Wang, & Wang; Albaladejo-González et al.; ScreenLive; Hossain et al.). https://learningatscale.hosting.acm.org/las2026/?p=119
- **Parciales:** Bueno, Hou, et al. (2026), WACV 2026, pp. 6806–6817, DOI 10.1109/WACV61042.2026.00658 (tomado de la página de TUM; lista de autores incompleta); Graf et al. (2026), *Education and Information Technologies, 31*(15), DOI 10.1007/s10639-026-14082-1 (tablero para estudiantes, fuera del alcance docente); Dong, Chen, & Shen y Tang & Wang (2026), artículos del número especial de *IJETHE* citados solo en el editorial de Rienties et al., sin DOI.
- **Solo existencia (vistos en resultados de búsqueda, no abiertos):** varios artículos de LAK26 y de Springer/ScienceDirect sobre análisis multimodal en aulas; Hon (SAGE, DOI 10.1177/00472395251400089, fecha dudosa); el *OECD Digital Education Outlook 2026*; el taller GenAILA y la convocatoria LA4GenAISLE 2026.

---

## 13. Estrategia de publicación

**No se afirman indexación, cuartil, APC, tasas de aceptación ni tiempos editoriales**; deben verificarse en el sitio oficial y en Scopus/JCR. Los enlaces apuntan a la página oficial de cada revista, donde se encuentran las instrucciones para autores; confirmar la URL específica de *Guide for Authors* en cada caso.

| Revista | Art. | Alcance temático | Ajuste metodológico | Contribución esperada | Riesgo de encaje | Página oficial |
|---|---|---|---|---|---|---|
| *Journal of Learning Analytics* | 1 (prioritaria) / 2 | LA, incluida la sección especial sobre GenAI | Alto para revisiones y metodología | Periodización LA–TA y quiebre GenAI | Exige aporte conceptual a LA, no solo un mapa | https://learning-analytics.info/index.php/JLA |
| *Educational Technology Research and Development* | 1 | Teoría y diseño en tecnología educativa | Medio | Marco conceptual de TA/LA en la era GenAI | Bibliometría pura puede considerarse fuera de alcance | https://link.springer.com/journal/11423 |
| *British Journal of Educational Technology* | 1 / 2 | Tecnología educativa, analítica e IA | Medio | Discusión internacional de la trayectoria | Requiere discusión sustantiva más allá del mapa | https://bera-journals.onlinelibrary.wiley.com/journal/14678535 |
| *Computers & Education: Artificial Intelligence* | 2 (prioritaria) | IA en educación, LLM | Alto | Tipología de roles GenAI y frentes emergentes | Competencia alta en revisiones de GenAI | https://www.sciencedirect.com/journal/computers-and-education-artificial-intelligence |
| *Smart Learning Environments* | 2 | Entornos inteligentes y analítica | Alto | *Clusters* de personalización y trazas | Menor visibilidad en LA nuclear [I] | https://slejournal.springeropen.com/ |
| *International Journal of Artificial Intelligence in Education* | 2 | AIED | Medio | Implicaciones metodológicas para AIED | Debe profundizar en AIED, no solo en LA | https://link.springer.com/journal/40593 |
| *Int. J. of Educational Technology in Higher Education* | 1 / 2 | Tecnología e IA en educación superior | Alto para revisiones | Cartografía con implicaciones para educación superior | El corpus debe acotarse a educación superior o justificarlo | https://educationaltechnologyjournal.springeropen.com/ |
| *Computers & Education* | 1 / 2 | Tecnología educativa | Medio-bajo para bibliometría | Solo con aporte teórico fuerte | Alta exigencia; mapas descriptivos son poco probables | https://www.sciencedirect.com/journal/computers-and-education |
| *Educational Technology & Society* | 1 / 2 | Innovación educativa | Medio | Implicaciones para docentes e instituciones | Verificar política vigente sobre revisiones | https://www.j-ets.net/ |
| *Education and Information Technologies* | 1 / 2 | Tecnología, IA y educación | Medio-alto | Alternativa amplia | Menor especificidad en LA | https://link.springer.com/journal/10639 |
| *Scientometrics* | 1 / 2 (versión metodológica) | Cienciometría | Alto solo si el método es el aporte | Estabilidad multibase y emergencia validada (agenda #12) | Rechazo si el aporte es solo temático | https://link.springer.com/journal/11192 |
| *Research Evaluation* | Variante metodológica | Evaluación de la investigación | Bajo-medio | Validez del mapeo de campos volátiles | Encaje temático débil con educación | https://academic.oup.com/rev |

**Ruta recomendada [I]:**
- **Artículo 1** → JLA; alternativas: BJET, ETR&D.
- **Artículo 2** → Computers & Education: AI; alternativas: Smart Learning Environments, IJAIED.
- Un tercer producto metodológico (agenda #12) → *Scientometrics*.
- Antes de enviar, revisar la política de cada revista sobre el uso de GenAI en la investigación y la redacción.

**Verificaciones de políticas en la actualización 2026.**
- **JLA:** las páginas de envíos, directrices y políticas no contienen declaración sobre uso de GenAI **[S, solo para esas páginas]**.
- **Elsevier:** su política corporativa (actualizada en julio de 2026) exige una declaración de uso de IA antes de las referencias y prohíbe listar la IA como autora **[S]**. Su aplicación a *Computers & Education: Artificial Intelligence* es **[P]**, porque la guía de autores de la revista no se pudo leer.
- ***Smart Learning Environments* e *IJETHE*:** las páginas abiertas no declaran regla de IA, pero pueden tener una página aparte de políticas editoriales **[P]**.
- **BJET, *Scientometrics*, IJAIED y ETR&D:** no se leyeron **[P]**.
- **Encaje temático:** el número especial de *IJETHE* sobre LA, GenAI y decisión educativa (editorial de Rienties et al., 2026) muestra interés reciente de esa revista en el puente conceptual de este proyecto; su colección no lista artículos ni fecha de lanzamiento, de modo que no se confirma que sea una convocatoria de 2026 **[P]**.