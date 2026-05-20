# Matemática III (05-N0051) — Referencia del curso

**Institución:** PUCE — Facultad de Ciencias Exactas, Naturales y Ambientales  
**Programa:** Catálogo STEM  
**Periodo:** 2026-1  
**Docente:** Andrés Merino (aemerinot@gmail.com)  
**Clases totales:** 25 (+ 1 retroalimentación)

---

## Temas del curso

| # | Clases | Nombre |
|---|--------|--------|
| 1  | 1–2   | Funciones vectoriales y curvas paramétricas |
| 2  | 3–4   | Geometría diferencial de curvas |
| 3  | 5     | Topología de ℝⁿ |
| 4  | 6–7   | Límites y diferenciabilidad |
| 5  | 8–9   | Derivadas parciales y gradiente |
| 6  | 10    | Función implícita y Hessiana |
| 7  | 11–12 | Campos vectoriales |
| 8  | 13    | Campos conservativos |
| 9  | 14–15 | Optimización |
| 10 | 16–17 | Integrales dobles |
| 11 | 18    | Cambio de variable |
| 12 | 19–20 | Integrales triples |
| 13 | 21    | Cambio de variable en integrales triples |
| 14 | 22–23 | Integrales de línea |
| 15 | 24    | Integrales de superficie |
| 16 | 25    | Teoremas integrales |

---

## Resultados de Aprendizaje y Criterios de Evaluación

Nunca cambies los Resultados de Aprendizaje (RdA) ni los Criterios de Evaluación, siempre colocalos de manera literal.

- **RdA 1:** Identificar conceptos, teoremas y propiedades de funciones vectoriales, derivadas parciales e integral vectorial.
  - 1.1: Representación gráfica y ley de asignación de funciones de varias variables.
  - 1.2: Concepto de derivada en varias variables.
  - 1.3: Concepto de integrales en varias variables.
- **RdA 2:** Calcular derivadas parciales e integrales con asistentes computacionales.
  - 2.1: Dominios de funciones de varias variables.
  - 2.2: Cálculo de derivadas de funciones de varias variables.
  - 2.3: Cálculo de integrales de funciones de varias variables.
- **RdA 3:** Aplicar Cálculo Vectorial para resolver problemas reales.
  - 3.1: Modelado con funciones de varias variables.
  - 3.2: Optimización con derivadas.
  - 3.3: Áreas, superficies y volúmenes con integrales múltiples.

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
├── 04Ejercicios/
│   ├── EjerciciosCompilado.tex # Todos los ejercicios juntos
│   └── Ejercicios0m.tex        # Ejercicios del tema m
├── 03Extra/                    # Material adicional
├── 05Proyectos-Retos/          # Retos aplicados
├── 06Examenes/                 # Exámenes escritos
├── 07Exposiciones/             # Video-exposiciones
└── 08Cuestionarios/            # Cuestionarios en línea
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
