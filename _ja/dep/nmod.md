---
layout: relation
title: 'nmod'
shortdef: 'nominal modifier'
udver: '2'
---

Prepositional/noun phrases modifying another phrase.

~~~ sdparse
明日 北海道 へ 行く 。 \n tomorrow Hokkaido TO go .
nmod(行く, 北海道)
case(北海道, へ)
nmod(行く, 明日)
punct(行く, 。)
~~~

~~~ sdparse
リンゴ の ジュース \n apple OF juice
nmod(ジュース, リンゴ)
case(リンゴ, の)
~~~

<!-- Interlanguage links updated St lis 3 20:58:58 CET 2021 -->
