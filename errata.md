Errata of Modelling Computing Systems (Moller & Struth)
======

1.12.3
-------
(answer) the root of the tree should be ∧ instead of ∨

1.26
-----

(answer)

"However, the formulae p and q are equivalent, ...", this should be "However,
the formulae p and r are equivalent, ..."

1.27.1
-------

(answer)

* When the Commutativity rule is applied, ∨ is accidentally changed to ∧
* The last rule should be the _Contradiction_ law instead of _Tautology_

It should be:

```
...
<=> (p ∧ q) ∨ false  (Commutativity)
<=> p ∧ q            (Contradiction)
```


2.28
-------
(answer)

The Commutative step mistakenly introduces ∩ which should be ∪. The last two steps should be

```
  ...
  = (A ∩ B) ∪ ∅  (Commutativity law)
  = A ∩ B        (Empty set law)
```


