---
layout: post
title:  "Bra-ket notation"
date:   2022-03-06 13:20:28 -0500
categories: math, quantum mechanics 
usemathjax: true
---

Bra-ket notation provides a convenient way to denote quantum states. It takes the form $$\langle f\vert v \rangle$$, where $$\langle f\vert$$ refers to the "bra" and $$\vert v\rangle$$ refers to the "ket". 

Let V be an abstract complex vector space with inner product.

A ket describes a vector $$v$$, in V. With regard to the Stern-Gerlach experiment, it is the reason for the notations |+z> and |-z> to write the two possible states. 

A bra describes a linear functional on C, that is, a linear map f:V -> C. It is also known as a covector: the set of all linear functionals of a space V to its "base field" (in this case, the complex numbers) is itself a vector space. It is referred to as the "dual space", and it is frequently written as V*. 

When a bra acts on a ket, the resultant value is a complex scalar, and it is denoted <f|v>. Now suppose that V is a vector space with inner product: a map (,): V x V -> K (K denoting the base field, and K = C for the example above) that satisfies the axioms of conjugate symmetry, positive-definiteness, and linearity in at least one argument. The last condition is written generally because in terms of linearity, physicists tend to use the opposite convention as mathematicians: they suppose linearity in the second argument rather than the first. This convention shall be adopted hereafter in this blog. 

Consider the vector space C^n. Vectors in C^n can be identified by writing them in columns; these are the kets. Similarly, bras are written as row vectors. More specifically, the correspondence between bra and ket vectors is given by conjugate transposition. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/pjsXMwmWwyM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
