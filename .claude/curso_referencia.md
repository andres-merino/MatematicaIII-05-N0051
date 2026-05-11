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

## Resultados de Aprendizaje

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

2. **`04Ejercicios/Ejercicios0m.tex`** — Ejercicios con respuestas  
   - Clase: `aleph-examen`  
   - Ambiente `preguntas` / `respuesta`

3. **`00PlanTemas/PlanTema0m.tex`** — Plan de clase  
   - Clase: `aleph-notas`  
   - Secciones: RdA asignatura + RdA del tema, Pregunta inicial, Actividades de desarrollo (motivación, clase magistral, ejercicios guiados, videos, implementación computacional), Verificación de aprendizaje, Cierre (tarea, pregunta de investigación, para el próximo tema)

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
| 1.1 | Cuestionario en línea 1 |
| 1.2 | Cuestionario en línea 2 (60%) + Video-exposición 1 (40%) |
| 1.3 | Cuestionario en línea 3 (60%) + Video-exposición 2 (40%) |
| 2.1 | Examen 1 - parte 1 |
| 2.2 | Examen 1 - parte 2 |
| 2.3 | Examen 2 |
| 3.1 | Reto 1 |
| 3.2 | Reto 2 |
