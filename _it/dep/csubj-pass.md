---
layout: relation
title: 'csubj:pass'
shortdef: 'clausal passive subject'
udver: '2'
---

A clausal passive subject is a clausal syntactic subject of a passive clause (or more generally, any voice where the proto-agent argument does not become the subject of the clause). 

~~~ sdparse
Ci viene spiegato come fossero fatti , in gran parte , da giovani ebrei 
csubj:pass(spiegato, fatti)
aux:pass(spiegato, viene)
iobj(spiegato, Ci)
aux(fatti, fossero)
mark(fatti, come)
~~~
~~~ sdparse
Gli venne chiesto se si ricordasse di Honoré
csubj:pass(chiesto, ricordasse)
~~~
~~~ sdparse
Mi è stato detto che il gruppo socialista vorrebbe che questo punto venisse ritirato
csubj:pass(detto, vorrebbe)
ccomp(vorrebbe, ritirato)
iobj(detto, Mi)
aux(detto, è)
aux:pass(detto, stato)
~~~
<!-- Interlanguage links updated St lis 3 20:58:49 CET 2021 -->
