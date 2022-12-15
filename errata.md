Errata of Modelling Computing Systems (Moller & Struth)
======

Solution 1.12.3 (p. 408)
-------
There are two mistakes:
* the root of the tree should be ∧ instead of ∨
* the right sub-tree should be P instead of Q

Solution 1.26 (p. 414)
-----

"However, the formulae p and q are equivalent, ...", this should be "However,
the formulae p and r are equivalent, ..."

Solution 1.27.1 (p. 415)
-------
There are two mistakes:

* When the Commutativity rule is applied, ∨ is accidentally changed to ∧
* The last rule should be the _Contradiction_ law instead of _Tautology_

It should be:

```
...
<=> (p ∧ q) ∨ false  (Commutativity)
<=> p ∧ q            (Contradiction)
```


Example 2.17 (p.71)
------------

The first sentence states that Amanda invites **six** friends to her birthday party. This should be **five** friends.


Solution 2.28 (p. 420)
-------

The Commutative step mistakenly introduces ∩ which should be ∪. The last two steps should be

```
  ...
  = (A ∩ B) ∪ ∅  (Commutativity law)
  = A ∩ B        (Empty set law)
```

Exercise 2.30.2
---
The subformula $P \Leftrightarrow Q$ should have parentheses around it, so the complete formula should be:

$(P \Leftrightarrow Q) ~ \Leftrightarrow ~ (P \Rightarrow Q) \wedge (Q \Rightarrow P)$

Example 3.14 (p.98)
------------

The third bullet states

> x = bc

Which should be

> z = bc

Solution 4.7.2
---

Remember that $\forall$ and $\exists$ bind stronger than other logical connectives when there are no parentheses. So the given solution actually has a free variable, written here in bold:

$\forall x ~ (\exists y ~ Mother(x, y) \Rightarrow Parent(x, \textbf{y}) \wedge Female(x))$

Instead, one correct solution is:

$\forall x ~ (\exists y ~ Mother(x, y) \Rightarrow \mathbf{\exists y} Parent(x, y) \wedge Female(x))$

Note that the following formula is not a good answer to the question:

$\forall x ~ (\exists y ~ (Mother(x, y) \Rightarrow Parent(x, y) \wedge Female(x)))$

Why? It states that for every person $x$, there exists a person $y$, such that the implication is true. That is true: for any person $x$, you can choose $y$ to be that same person, and the implication will hold (a person can never be their own mother). However, the sentence does not really express the intended property about mothers anymore.

Example 7.8
----------------
The definition of grandfather should be:

$Grandfather = Father \circ Parent $


Definition 7.11 (p. 191)
----------------
"anytisymmetric" is a typo, it should of course be "antisymmetric"


Solution 8.10 (p.443)
--------------
The general solution is

fₙ = fₙ₋₁ + fₙ₋₂
