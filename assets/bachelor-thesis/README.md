# Extensions of Isometries between Subsets of Certain Banach Spaces

> Bachelor's Thesis · 2025 · Bachelor's Degree in Mathematics · University of Granada (UGR)

📄 **[Bachelor's Thesis (PDF, in Spanish)](bachelor-thesis.pdf)** · Original title: *Extensiones de isometrías entre subconjuntos de determinados espacios de Banach*

<code>Functional Analysis</code> · <code>Banach Spaces</code> · <code>Isometries</code> · <code>Mazur–Ulam Theorem</code> · <code>Tingley Problem</code>

## From the introduction

> Mathematics is not always born in classrooms or on blackboards. Sometimes it emerges in places as unexpected as a café. During the 1930s and 1940s, the Scottish Café, in the city of Lviv (then Lwów, Poland), was the meeting point of some of the most brilliant mathematicians of the 20th century: Stefan Banach, Stanisław Ulam, Stanisław Mazur, Hugo Steinhaus, Alfred Tarski and Kazimierz Kuratowski, among others. There they discussed problems for hours, writing in pencil directly on the marble tables. To keep their ideas from being lost at the end of the day, they began to write them down in a notebook: the famous *Scottish Book*, which collected 193 mathematical problems, many of them unsolved.
>
> In that singular setting of mathematical gatherings, where problems were rewarded with coffee, brandy or even a live goose, one of the most influential results of functional analysis was born: the Mazur–Ulam theorem. It was posed by Stanisław Mazur, and its solution was obtained in collaboration with Ulam in 1932. This theorem gave rise to the theory of isometries in Banach spaces and to a line of research, with many generalizations and applications, that is still active today.

<details>
<summary>Original (Spanish)</summary>

> Las matemáticas no siempre nacen en las aulas o en las pizarras. Hay veces que surgen en lugares tan inesperados como una cafetería. Durante las décadas del 1930 y 1940, el Café Escocés, en la ciudad de Lviv (entonces Lwów, Polonia), fue el punto de encuentro de algunos de los matemáticos más brillantes del siglo XX: Stefan Banach, Stanislaw Ulam, Stanislaw Mazur, Hugo Steinhaus, Alfred Tarski o Kazimierz Kuratowski, entre otros. Allí discutían problemas durante horas, escribiendo con lápiz directamente sobre las mesas de mármol. Para evitar que sus ideas se perdieran al final del día, comenzaron a anotarlas en un cuaderno: el famoso Libro Escocés, una obra que recogió 193 problemas matemáticos, muchos sin resolver.
>
> En ese ámbito singular de tertulia matemática, donde los problemas se premiaban con café, brandy o incluso un ganso vivo, surgió uno de los resultados más influyentes del análisis funcional: el teorema de Mazur-Ulam. Formulada por Stanislaw Mazur, cuya solución fue obtenida en colaboración con Ulam en 1932. Este teorema ha dado origen a la teoría de isometrías en el marco de espacios de Banach y a una línea de investigación con múltiples generalizaciones y aplicaciones que sigue activa hasta la actualidad.

</details>

## The question

**Does analysis determine algebra?** In other words: if a map preserves distances, must it also preserve the linear structure of the space?

The **Mazur–Ulam theorem (1932)** says yes: every surjective isometry between real normed spaces is affine, that is, linear up to a translation. A purely metric property is enough to recover the algebraic structure. The converse fails: an infinite-dimensional normed space always admits two non-equivalent norms, so the algebra alone does not determine the metric.

## Main ideas

The thesis follows one line of research, **Mazur–Ulam (1932) → Mankiewicz (1972) → Tingley (1987)**, in which each step needs a smaller part of the space to recover its linear structure: the whole space, then a ball, and finally just the unit sphere.

### Part I: the Mazur–Ulam theorem and its generalizations

- **Mazur–Ulam theorem.** Three modern proofs are analyzed, by Väisälä (2003), Nica (2012) and Hatori (2024), which use a reflection technique to prove in a few lines what originally took several pages. An example shows why surjectivity is essential, and the result does not hold for complex linearity: complex conjugation on $\mathbb{C}$ is an isometry that is not $\mathbb{C}$-linear.
- **Baker's theorem (1971).** It drops the surjectivity assumption in exchange for a strictly convex codomain, and every isometry is still affine.
- **Aleksandrov problem (1970).** If a map preserves a single distance, must it be an isometry? There are positive answers in specific cases, but the problem remains open in general.
- **g-isometries.** A recent framework by Zivari-Kazempour (2022) that extends the Mazur–Ulam theorem, Baker's theorem and the Aleksandrov problem under a single, more general setting. Because it is so recent, it has barely been studied, which makes it a promising research direction.
- **Mankiewicz's extension (1972).** A surjective isometry defined only on an open connected subset, or on a convex body, extends uniquely to an affine isometry of the whole space. In other words, **all the information we need about a normed space is in its unit ball**.

### Part II: the Tingley problem

- **Tingley's theorem (1987).** In finite-dimensional Banach spaces, a surjective isometry between unit spheres satisfies $f(-x) = -f(x)$, the key step to extending it to the whole space.
- **The Tingley problem.** Does the same hold in infinite dimensions? That is, is every surjective isometry between unit spheres the restriction of a linear or affine map? It has been studied in many Banach spaces and is still an active research topic.
- **Spaces of continuous functions $C_0(\Omega)$** (R. Wang, 1994). In the real case, a surjective isometry between unit spheres extends uniquely to a surjective isometry of the whole space. In the complex case, the extension is linear on one part of the space and conjugate-linear on the other, which shows the extra difficulties of changing the underlying field.
- **Hilbert spaces** (G. Ding, 2002). Two extension results: one for surjective 1-Lipschitz maps between unit spheres, and one without surjectivity under the symmetry condition $-V_0(S_H) \subset V_0(S_H)$.

The result is a rigorous and up-to-date overview, from a classical theorem like Mazur–Ulam's to problems that are still open like Tingley's, combining modern proofs, generalizations, new formulations and the analysis of specific cases.

---

[← Back to profile](https://github.com/greghgev)
