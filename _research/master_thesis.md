---
title: "Master's thesis: Abelian varieties in the Theta model and applications to cryptography"
collection: research
category: theses
# permalink: /research/master-thesis
excerpt: 'Arithmetic on abelian varieties via the use of algebraic theta functions. Algorithms describing the group law, $(2,\dots,2)$-isogenies, pairings. Application of these algorithms on SQIsign2D verification.'
# venue:  'University of Pisa'
when: 2024
date: 2024-09-27
urls:
    slides: 'http://sferl.github.io/files/slides_master_thesis.pdf'
    pdf: 'http://sferl.github.io/files/pdf_master_thesis.pdf'
---
This is the final thesis submitted in view of my Master's degree in Mathematics at the University of Pisa.

It was mainly written under the supervision of [Benjamin Smith](https://www.lix.polytechnique.fr/~smith/) -- as I was anintern in the research team GRACE at Inria Saclay -- and co-supervised by [Davide Lombardo](https://people.dm.unipi.it/lombardo/).

## Abstract

Isogenies of principally polarised abelian varieties have been used in
recent years to build cryptographic protocols that are secure against quan-
tum computers. Though abelian varieties are classical objects in algebraic
geometry, from a computational perspective they present some challenges
that have been addressed only recently.
An algorithmic framework to work with abelian varieties of any di-
mension is provided by theta models. These are projective realisations of
polarised abelian varieties defined by algebraic theta functions.
This thesis presents an introduction to the arithmetic of abelian vari-
eties via the theory of theta models. It concerns itself with the compu-
tation of the group law on abelian varieties and the differential addition
law on their Kummer varieties, and includes some recent algorithms to
efficiently compute chains of $$(2, ..., 2)$$-isogenies and pairings. Algorithms
for pairing computation also make use of the algebraic theory of biex-
tensions. Original contributions include implementations for some of the
algorithms presented.
Finally, as a cryptographic application, the recent isogeny-based dig-
ital signature scheme SQIsign2D-West is studied, with a focus on the
applicability of the higher-dimensional isogeny algorithms to signature
verification in small devices.