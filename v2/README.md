# v2 — activa (agosto 2026)

## Orden de lectura

1. **`GATE.md`** — antes que nada. Ocho criterios binarios y el veredicto actual. Dice
   qué falta y, sobre todo, qué **no** se puede afirmar todavía.
2. **`paper-en.md`** — el paper. Canónico, en inglés, destino arXiv cs.LG.
   `paper-es.md` es la traducción para leer.
3. **`PATTERNS.md`** — el catálogo. Es el producto separable: sirve sin el paper.
4. **`ANALYSIS.md`** — dónde falla cada paradigma y por qué, con la traza.
5. **`PLAN.md`** — sólo si interesa por qué la tesis cambió dos veces.

## Estado

**El gate no tiene bloqueantes** desde el 2026-08-23 (G1 cerrado; ver §8ter de `GATE.md`).
Quedan dos condicionales que no impiden correr pero sí submitir: **G2** (releer
Select-then-Solve y SCL completos — seis cesiones de novedad se hicieron sobre abstracts, y
es el único riesgo rojo vivo) y **G3** (soporte de afirmaciones).

Todo número empírico es **n=1 por celda**, sobre un corpus sintético, con un modelo. La
varianza entre réplicas medida sobre la topología más elaborada llegó a 3,93× en costo,
así que las magnitudes son indicativas. Los **mecanismos** son más firmes que las
magnitudes, porque descansan en trazas de uso de herramientas y no en tamaños de efecto.

**La amenaza de validez más grande, y está declarada en el paper**: en el corpus que
sostiene los resultados todo entra en un prompt, y en ese régimen leer todo es óptimo y
el orden es casi tautológico. Los corpus de 135k, 483k y 1.272k tokens están generados y
verificados; no están corridos.

## Figuras

Las 6 de `diagrams/` están sólo en inglés (`_en`). Las dos de resultados llevan una banda
roja **PRELIMINARY** con la n adentro del SVG, para que la advertencia no se pueda separar
de la figura al copiarla.
