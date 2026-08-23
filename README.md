# Lumen — Whitepapers

Dos versiones. **v1 está congelada**; **v2 está en curso** y es donde se trabaja.

```
whitepaper/
├── v1/   Enero 2026 — congelada, no se edita
└── v2/   Agosto 2026 — activa
```

---

## v2 — activa

**Tesis**: antes de aprender a elegir la topología de un agente, hay tres cosas que van
adelante del problema de aprendizaje. La factibilidad es aritmética y poda gratis; la
selección sólo paga bajo una condición que se puede enunciar y verificar; y la varianza
que se le atribuye a la topología la gobierna en realidad la superficie de herramientas.

| archivo | qué es | estado |
|---|---|---|
| [`v2/paper-en.md`](v2/paper-en.md) | **el paper** (inglés, canónico → arXiv) | borrador 0.1 |
| [`v2/paper-es.md`](v2/paper-es.md) | el paper en castellano, para leerlo | borrador 0.1 |
| [`v2/PATTERNS.md`](v2/PATTERNS.md) | catálogo de patrones: 10 estructurales, 4 de control, 15 anti-patrones | en curso |
| [`v2/ANALYSIS.md`](v2/ANALYSIS.md) | análisis de fallos por paradigma y por celda | medido |
| [`v2/GATE.md`](v2/GATE.md) | 8 criterios binarios de publicación + veredicto | **sin bloqueantes, 2 condicionales** |
| [`v2/PLAN.md`](v2/PLAN.md) | historia de revisiones de la tesis, incluidos dos marcos superados | referencia |
| [`v2/diagrams/`](v2/diagrams/) | 6 figuras SVG del v2 | falta versión `_es` |

**Orden de lectura**: `GATE.md` primero — dice qué falta y qué no se puede afirmar
todavía. Después el paper. `PLAN.md` sólo si interesa por qué la tesis cambió dos veces.

**El código está afuera**: `D:\Apps\paperlab` — 7 paradigmas, 5 brazos de retrieval,
3 superficies de herramientas, generador de corpus con verificador independiente,
63 aserciones chequeadas por máquina. El paper no se sostiene sin eso.

---

## v1 — congelada

Enero 2026. Documento largo (180k / 200k caracteres), bilingüe, con 110 diagramas y
fuente LaTeX para arXiv en `v1/arxiv/`.

**No consiguió aval para arXiv.** El motivo no fue el contenido: arXiv cambió la política
el 2026-01-21 y el correo institucional dejó de alcanzar. Pero la revisión posterior
encontró un problema propio y peor — el documento afirmaba mucho y medía poco. El v2
existe por eso, y de ahí sale la regla del `GATE.md`: cada afirmación citada, medida con
su n, o marcada como hipótesis.

Se conserva completa como referencia y para trazar qué ideas sobrevivieron.
