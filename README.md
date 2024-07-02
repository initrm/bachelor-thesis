# Hyper-minimizing deterministic finite state automata

This repository contains the code and the report for my bachelor's thesis "Hyper-minimizing deterministic finite state automata". The thesis places itself in the field of theoretical computer science and is about the hyper-minimization problem, a problem related to the minimization of deterministic finite state automata. The hyper-minimization problem consists in finding a deterministic finite state automaton with the smallest number of states that accepts a language finitely different from the language accepted by the starting automaton. More details can be found in the abstract below and in the report itself.

## Aknowledgements

Since this is a bachelor's thesis and my university is in Italy, the report is written in Italian. The abstract is reported below in English.

## Abstract

In the field of theoretical computer science, one of the most interesting topics is the
theory of automata. One of the most relevant problems in this field is the minimization
of deterministic finite state automata. Recently, a new problem related to the previous
one has been introduced, called hyper-minimization of deterministic finite state automata.
This problem consists in finding a deterministic finite state automaton with the smallest
number of states that accepts a language finitely different from the language accepted
by the starting automaton. In other words, given a hyper-minimal automaton, any other
automaton with fewer states recognizes a language infinitely different. This result is
of great theoretical and practical interest, and the search for efficient algorithms for
its resolution has been the subject of study in recent years. Over time, three main
algorithms have emerged for solving the hyper-minimization problem, each of which
refines the strategies used by improving the computational complexity of the previous
algorithm. The first algorithm presented capable of solving the hyper-minimization
problem in polynomial time was that of Badr, Geffert and Shipman, with computational
complexity equal to $\mathcal{O}(n^3 \cdot m)$, where $n$ is the number of states of the 
input automaton and $m$ is the cardinality of the alphabet of the automaton. Subsequently,
two new algorithms have been proposed, the Badr algorithm, with computational
complexity $\mathcal{O}(n^2)$, and the Holzer and Maletti algorithm, with computational
complexity equal to $\mathcal{O}(n \log n)$. In this thesis, the performance of these
algorithms are investigated in an attempt to establish a bridge between theory and practice.
The algorithms have been implemented and tests have been conducted to evaluate their
performances. The results of the experiments show that the Holzer and Maletti algorithm
is the most efficient among those proposed, in accordance with what is expected from
theory. More surprisingly, however, the Badr, Geffert and Shipman algorithm, despite
having a higher computational complexity than the Badr algorithm, behaves better in
practice on average as the worst case occurs very rarely.

## References

This thesis is based on the following papers:
- Andrew Badr, Viliam Geffert and Ian Shipman. ≪Hyper-minimizing minimized deterministic finite state automata≫. In: _RAIRO - Theoretical Informatics and Applications_ 43.1 (2009), pp. 69–94. DOI: [10.1051/ita:2007061](https://doi.org/10.1051/ita:2007061).
- Andrew Badr. ≪Hyper-Minimization in $\mathcal{O}(n^2)$≫. In: _Implementation and Applications of Automata_. Edited by Oscar H. Ibarra e Bala Ravikumar. Berlin, Heidelberg: Springer Berlin Heidelberg, 2008, pp. 223–231. ISBN: 978-3-540-70844-5
- Markus Holzer and Andreas Maletti. ≪An $n \log n$ algorithm for hyper-minimizing a (minimized) deterministic automaton≫. In: _Theoretical Computer Science_ 411.38 (2010). Implementation and Application of Automata
(CIAA 2009), pp. 3404–3413. ISSN: 0304-3975. DOI: [10.1016/j.tcs.201](https://doi.org/10.1016/j.tcs.2010.05.0290.05.029). URL: [https://www.sciencedirect.com/science/article/pii/S030439751000321X](https://www.sciencedirect.com/science/article/pii/S030439751000321X).