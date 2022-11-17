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


Solution 2.28 (p. 420)
-------

The Commutative step mistakenly introduces ∩ which should be ∪. The last two steps should be

```
  ...
  = (A ∩ B) ∪ ∅  (Commutativity law)
  = A ∩ B        (Empty set law)
```


Example 2.17 (p.71)
------------

The first sentence states that Amanda invites **six** friends to her birthday party. This should be **five** friends.


Example 3.14 (p.98)
------------

The third bullet states

> x = bc

Which should be

> z = bc


Definition 7.11 (p. 191)
----------------
"anytisymmetric" is a typo, it should of course be "antisymmetric"


Solution 8.10 (p.443)
--------------
The general solution is

fₙ = fₙ₋₁ + fₙ₋₂
