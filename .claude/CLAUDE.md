# Matemática III (05-N0051) — Referencia del curso

**Institución:** PUCE — Facultad de Ciencias Exactas, Naturales y Ambientales  
**Programa:** Catálogo STEM  
**Periodo:** 2026-1  
**Docente:** Andrés Merino (aemerinot@gmail.com)  
**Clases totales:** 26

---

## Temas del curso

| # | Clases | Nombre |
|---|--------|--------|
| 1  | 1–2   | Funciones vectoriales y curvas |
| 2  | 3     | Movimiento en el espacio |
| 3  | 4–5   | Geometría de curvas |
| 4  | 6     | Topología de ℝⁿ |
| 5  | 7–8   | Límites y diferenciabilidad |
| 6  | 9–10  | Derivadas parciales y gradiente |
| 7  | 11    | Función implícita y Hessiana |
| 8  | 12–13 | Campos vectoriales |
| 9  | 14    | Campos conservativos |
| 10 | 15–16 | Optimización |
| 11 | 17–18 | Integrales dobles |
| 12 | 19    | Cambio de variable |
| 13 | 20–21 | Integrales triples |
| 14 | 22    | Cambio de variable en integrales triples |
| 15 | 23–24 | Integrales de línea |
| 16 | 25    | Integrales de superficie |
| 17 | 26    | Teoremas integrales |

---

## Resultados de Aprendizaje y Criterios de Evaluación

Nunca cambies los Resultados de Aprendizaje (RdA) ni los Criterios de Evaluación, siempre colocalos de manera literal.

- **RdA 1:** Identificar los conceptos, teoremas y propiedades de funciones vectoriales, derivadas parciales e integral vectorial.
  - 1.1: Asocia las funciones de varias variables con su ley de asignación y su representación gráfica.
  - 1.2: Interpreta el concepto de derivada en varias variables y reconocer sus elementos y propiedades.
  - 1.3: Interpreta el concepto de integrales en varias variables y reconocer sus elementos y propiedades.
- **RdA 2:** Calcular derivadas parciales, integrales de funciones vectoriales con el apoyo de asistentes computacionales.
  - 2.1: Determina dominios de funciones de varias variables a través de su representación gráfica o su ley de asignación.
  - 2.2: Calcula derivadas de funciones de varias variables.
  - 2.3: Calcula integrales de funciones de varias variables.
- **RdA 3:** Aplicar distintos tópicos del Cálculo Vectorial para la solución de problemas reales en diferentes contextos.
  - 3.1: Utiliza funciones de varias variables para modelar problemas.
  - 3.2: Emplea la derivada para resolver problemas de optimización.
  - 3.3: Emplea integrales múltiples para determinar áreas, superficies y volúmenes.

---

## Estructura de archivos

```
MatematicaIII-05-N0051/
├── 00Cronograma/
│   └── Cronograma.tex          # Cronograma y actividades de evaluación
├── 00PlanTemas/
│   ├── PlanTema00.tex          # Plantilla de plan de clase
│   └── PlanTema0m.tex          # Plan de clase del tema m
├── 01Resumen/
│   ├── ResumenCompilado.tex    # Todos los resúmenes juntos
│   └── Resumen0m.tex           # Resumen del tema m
├── 02ResumenPython/            # Resúmenes con implementación en Python
├── 03Extra/                    # Material adicional
├── 04Ejercicios/
│   ├── EjerciciosCompilado.tex # Todos los ejercicios juntos
│   └── Ejercicios0m.tex        # Ejercicios del tema m
├── 05Proyectos-Retos/          # Retos aplicados
├── 06Examenes/                 # Exámenes escritos
├── 07Exposiciones/             # Video-exposiciones
├── 08Cuestionarios/            # Cuestionarios en línea
├── 09Talleres/
│   └── Taller0m.tex            # Talleres evaluados
└── 10Laboratorios/
    └── Lab0m.ipynb             # Laboratorios computacionales (Jupyter Notebook)
```

---

## Flujo de trabajo por tema

Para cada tema `m`, crear en orden:

1. **`01Resumen/Resumen0m.tex`** — Resumen teórico  
   - Clase: `aleph-notas`  
   - Definiciones, teoremas, propiedades del tema
   - Tomar contenido de `01Resumen/ResumenCompilado.tex`.

2. **`04Ejercicios/Ejercicios0m.tex`** — Ejercicios con respuestas  
   - Clase: `aleph-examen`  
   - Dejar solo el foramato sin contenido.

3. **`00PlanTemas/PlanTema0m.tex`** — Plan de clase  
   - Clase: `aleph-notas`  
   - Secciones: RdA asignatura + RdA del tema, Pregunta inicial (enmarcada en situaciones cotidianas sin usar términos técnicos nuevos), Actividades de desarrollo (motivación, clase magistral, ejercicios guiados, videos, implementación computacional), Verificación de aprendizaje, Cierre (tarea, pregunta de investigación, para el próximo tema)

---

## Configuración LaTeX común

```latex
\institucion{Facultad de Ciencias Exactas, Naturales y Ambientales}
\carrera{Catálogo STEM}
\asignatura{Matemática III}
\autor{Andrés Merino}
\fecha{Periodo 2026-1}
\logouno[0.16\textwidth]{Logos/logoPUCE_04_ac}
\definecolor{colortext}{HTML}{1957d1}
\definecolor{colordef}{HTML}{1957d1}
\fuente{montserrat}
```

Paquete de comandos matemáticos: `aleph-comandos` (define `\func`, `\funcion`, `\R`, normas, etc.)

---

## Actividades de evaluación

| Criterio | Actividad |
|----------|-----------|
| 1.1 | Cuestionario en línea 1 (100%) |
| 1.2 | Cuestionario en línea 2 (100%) |
| 1.3 | Cuestionario en línea 3 (100%) |
| 2.1 | Taller 1 (100%) |
| 2.2 | Examen escrito 1 (100%) |
| 2.3 | Examen escrito 2 (100%) |
| 3.1 | Reto 1 (100%) |
| 3.2 | Examen escrito 3 (100%) |
| 3.3 | Reto 2 (100%) |

## graphify

This project has a knowledge graph at graphify-out/ with god nodes, community structure, and cross-file relationships.

Rules:
- For codebase questions, first run `graphify query "<question>"` when graphify-out/graph.json exists. Use `graphify path "<A>" "<B>"` for relationships and `graphify explain "<concept>"` for focused concepts. These return a scoped subgraph, usually much smaller than GRAPH_REPORT.md or raw grep output.
- If graphify-out/wiki/index.md exists, use it for broad navigation instead of raw source browsing.
- Read graphify-out/GRAPH_REPORT.md only for broad architecture review or when query/path/explain do not surface enough context.
- After modifying code, run `graphify update .` to keep the graph current (AST-only, no API cost).