# Graph Report - .  (2026-05-31)

## Corpus Check
- Corpus is ~3,383 words - fits in a single context window. You may not need a graph.

## Summary
- 10 nodes · 15 edges · 3 communities (2 shown, 1 thin omitted)
- Extraction: 53% EXTRACTED · 47% INFERRED · 0% AMBIGUOUS · INFERRED: 7 edges (avg confidence: 0.82)
- Token cost: 1,800 input · 950 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Learning Outcomes|Learning Outcomes]]
- [[_COMMUNITY_Course Identity|Course Identity]]
- [[_COMMUNITY_CICD Pipeline|CI/CD Pipeline]]

## God Nodes (most connected - your core abstractions)
1. `Matemática III (05-N0051) README` - 8 edges
2. `Cálculo Vectorial` - 4 edges
3. `RdA 2: Calcular derivadas e integrales con asistentes computacionales` - 4 edges
4. `RdA 1: Identificar conceptos de funciones vectoriales y derivadas parciales` - 3 edges
5. `RdA 3: Aplicar Cálculo Vectorial para problemas reales` - 3 edges
6. `GitHub Actions: Compile LaTeX Documents` - 2 edges
7. `PUCE Logo — Pontificia Universidad Católica del Ecuador` - 2 edges
8. `PUCE — Facultad de Ciencias Exactas, Naturales y Ambientales` - 2 edges
9. `MIT License` - 1 edges
10. `LaTeX Document Compilation Workflow` - 1 edges

## Surprising Connections (you probably didn't know these)
- `PUCE Logo — Pontificia Universidad Católica del Ecuador` --conceptually_related_to--> `Matemática III (05-N0051) README`  [INFERRED]
  Logos/logoPUCE_04_ac.png → README.md
- `GitHub Actions: Compile LaTeX Documents` --conceptually_related_to--> `Matemática III (05-N0051) README`  [INFERRED]
  .github/workflows/latex_build.yml → README.md
- `PUCE Logo — Pontificia Universidad Católica del Ecuador` --references--> `PUCE — Facultad de Ciencias Exactas, Naturales y Ambientales`  [EXTRACTED]
  Logos/logoPUCE_04_ac.png → README.md
- `Matemática III (05-N0051) README` --references--> `MIT License`  [EXTRACTED]
  README.md → LICENSE.md

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Matemática III Course Learning Outcomes and Cálculo Vectorial** — concept_rda1, concept_rda2, concept_rda3, concept_calculo_vectorial [EXTRACTED 0.95]
- **Project Identity: Institution, Course, and Branding** — readme_matematicaiii, logo_puce, concept_puce_institution [INFERRED 0.85]

## Communities (3 total, 1 thin omitted)

### Community 0 - "Learning Outcomes"
Cohesion: 0.83
Nodes (4): Cálculo Vectorial, RdA 1: Identificar conceptos de funciones vectoriales y derivadas parciales, RdA 2: Calcular derivadas e integrales con asistentes computacionales, RdA 3: Aplicar Cálculo Vectorial para problemas reales

### Community 1 - "Course Identity"
Cohesion: 0.67
Nodes (4): PUCE — Facultad de Ciencias Exactas, Naturales y Ambientales, MIT License, PUCE Logo — Pontificia Universidad Católica del Ecuador, Matemática III (05-N0051) README

## Knowledge Gaps
- **1 isolated node(s):** `MIT License`
  These have ≤1 connection - possible missing edges or undocumented components.
- **1 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Matemática III (05-N0051) README` connect `Course Identity` to `Learning Outcomes`, `CI/CD Pipeline`?**
  _High betweenness centrality (0.787) - this node is a cross-community bridge._
- **Why does `GitHub Actions: Compile LaTeX Documents` connect `CI/CD Pipeline` to `Course Identity`?**
  _High betweenness centrality (0.222) - this node is a cross-community bridge._
- **Why does `Cálculo Vectorial` connect `Learning Outcomes` to `Course Identity`?**
  _High betweenness centrality (0.009) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `Matemática III (05-N0051) README` (e.g. with `PUCE Logo — Pontificia Universidad Católica del Ecuador` and `GitHub Actions: Compile LaTeX Documents`) actually correct?**
  _`Matemática III (05-N0051) README` has 2 INFERRED edges - model-reasoned connections that need verification._
- **Are the 3 inferred relationships involving `Cálculo Vectorial` (e.g. with `RdA 1: Identificar conceptos de funciones vectoriales y derivadas parciales` and `RdA 2: Calcular derivadas e integrales con asistentes computacionales`) actually correct?**
  _`Cálculo Vectorial` has 3 INFERRED edges - model-reasoned connections that need verification._
- **Are the 3 inferred relationships involving `RdA 2: Calcular derivadas e integrales con asistentes computacionales` (e.g. with `RdA 1: Identificar conceptos de funciones vectoriales y derivadas parciales` and `Cálculo Vectorial`) actually correct?**
  _`RdA 2: Calcular derivadas e integrales con asistentes computacionales` has 3 INFERRED edges - model-reasoned connections that need verification._
- **Are the 2 inferred relationships involving `RdA 1: Identificar conceptos de funciones vectoriales y derivadas parciales` (e.g. with `Cálculo Vectorial` and `RdA 2: Calcular derivadas e integrales con asistentes computacionales`) actually correct?**
  _`RdA 1: Identificar conceptos de funciones vectoriales y derivadas parciales` has 2 INFERRED edges - model-reasoned connections that need verification._