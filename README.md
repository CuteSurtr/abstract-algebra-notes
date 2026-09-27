# Abstract Algebra Notes

Notes on abstract algebra, from the group axioms up through Galois theory and Dedekind domains. The compiled book is [abstract-algebra-notes.pdf](abstract-algebra-notes.pdf).

## Chapters

1. Introduction to Groups
2. Subgroups
3. Quotient Groups and Homomorphisms
4. Group Actions
5. Direct and Semidirect Products and Abelian Groups
6. Further Topics in Group Theory
7. Introduction to Rings
8. Euclidean Domains, PIDs, and UFDs
9. Polynomial Rings
10. Introduction to Module Theory
11. Vector Spaces
12. Modules over Principal Ideal Domains
13. Field Theory
14. Galois Theory
15. Commutative Rings and Algebraic Geometry
16. Artinian Rings, Discrete Valuation Rings, and Dedekind Domains

Each section gives the definitions and theorems with proofs, then a run of worked examples. Commutative diagrams come with a short explanation of what each arrow is and why the square commutes. Sections end with exercises, and every chapter closes with a problem bank split into easy, medium and hard.

## Building the PDF

Everything is in `abstract-algebra-notes.tex`; the macros and theorem styles are in `preamble.tex`. Any recent TeX Live works (it uses amsmath, amsthm, tikz, tikz-cd, enumitem and hyperref). Run pdflatex three times so the contents and cross-references settle:

```
pdflatex abstract-algebra-notes.tex
pdflatex abstract-algebra-notes.tex
pdflatex abstract-algebra-notes.tex
```
