---
layout: relation
title:  'nmod:caus'
shortdef : 'TODO'
---

`nmod:caus` is used for the causee in causative verb constructions, such as:

X made Y do W to Z

Here X is the causer (subject), with `nsubj` relation, Y is the causee (causative 
subject) with `nmod:caus` relation and Z is the direct object `dobj`. Note that 
these may be nested. In the current revision of the standard all causee's, even
nested ones get `nmod:caus`.

~~~ sdparse
Апам мені хатты көршіге оқытқызды . \n My-aunt me letter neighbour made-made-read .
nsubj(оқытқызды-5, Апам-1)
nmod:caus(оқытқызды-5, көршіге-4)
dobj(оқытқызды-5, хатты-3)
nmod:caus(оқытқызды-5, мені-2)
punct(оқытқызды-5, .-6)
~~~
