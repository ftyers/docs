---
layout: relation
title:  'nmod:poss'
shortdef : 'TODO'
---

`nmod:poss` is used for the nominal modifier in an izafet construction. It is not
used for noun-noun compounds where there is no possessive/izafet construction. For 
that relation `compound` is used.

The genitive modifier may be indefinite as in:

~~~ sdparse
Дүниежүзілік экономикалық дағдарыс Иран экономикасын тұралатып тастады . \n Global economic depression Iran-of economy declining threw .
nmod:poss(экономикасын-5, Иран-4)
obj(тастады-7, экономикасын-5)
~~~

or definite, as in:
