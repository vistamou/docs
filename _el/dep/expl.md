---
layout: relation
title: 'expl'
shortdef: 'expletive'
udver: '2'
---

The `expl` relation is used in UD Greek for cases of clitic doubling.

~~~ sdparse
Της τον έδωσε της Καίτης τον αναπτήρα
expl(έδωσε, Της-1)
iobj(έδωσε, Καίτης)
expl(έδωσε, τον-2)
dobj(έδωσε, αναπτήρα)
~~~

But when clitics appear alone in the sentence, they are labeled as core arguments.

~~~ sdparse
Της τον έδωσε
iobj(έδωσε, Της)
dobj(έδωσε, τον)
~~~
<!-- Interlanguage links updated St lis 3 20:58:52 CET 2021 -->
