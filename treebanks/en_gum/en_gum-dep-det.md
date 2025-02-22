---
layout: base
title:  'Statistics of det in UD_English-GUM'
udver: '2'
---

## Treebank Statistics: UD_English-GUM: Relations: `det`

This relation is universal.
There are 1 language-specific subtypes of `det`: <tt><a href="en_gum-dep-det-predet.html">det:predet</a></tt>.

10987 nodes (8%) are attached to their parents as `det`.

10969 instances of `det` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.62564849367434.

The following 11 pairs of parts of speech are connected with `det`: <tt><a href="en_gum-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_gum-pos-DET.html">DET</a></tt> (9671; 88% instances), <tt><a href="en_gum-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_gum-pos-DET.html">DET</a></tt> (1076; 10% instances), <tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gum-pos-DET.html">DET</a></tt> (157; 1% instances), <tt><a href="en_gum-pos-NUM.html">NUM</a></tt>-<tt><a href="en_gum-pos-DET.html">DET</a></tt> (30; 0% instances), <tt><a href="en_gum-pos-ADV.html">ADV</a></tt>-<tt><a href="en_gum-pos-DET.html">DET</a></tt> (16; 0% instances), <tt><a href="en_gum-pos-PRON.html">PRON</a></tt>-<tt><a href="en_gum-pos-DET.html">DET</a></tt> (16; 0% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-DET.html">DET</a></tt> (9; 0% instances), <tt><a href="en_gum-pos-X.html">X</a></tt>-<tt><a href="en_gum-pos-DET.html">DET</a></tt> (8; 0% instances), <tt><a href="en_gum-pos-INTJ.html">INTJ</a></tt>-<tt><a href="en_gum-pos-DET.html">DET</a></tt> (2; 0% instances), <tt><a href="en_gum-pos-PART.html">PART</a></tt>-<tt><a href="en_gum-pos-DET.html">DET</a></tt> (1; 0% instances), <tt><a href="en_gum-pos-SYM.html">SYM</a></tt>-<tt><a href="en_gum-pos-DET.html">DET</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 8 det	color:blue
1	In	in	ADP	IN	_	3	case	3:case	Discourse=elaboration:70->65:3
2	his	his	PRON	PRP$	Gender=Masc|Number=Sing|Person=3|Poss=Yes|PronType=Prs	3	nmod:poss	3:nmod:poss	Entity=(abstract-96-new-2-sgl(person-90-giv:act-1-ana)
3	memory	memory	NOUN	NN	Number=Sing	5	obl	5:obl:in	Entity=96)
4	Byron	Byron	PROPN	NNP	Number=Sing	5	nsubj	5:nsubj	Entity=(person-3-giv:act-1-coref-Lord_Byron)
5	composed	compose	VERB	VBD	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	0	root	0:root	_
6	Thyrza	Thyrza	PROPN	NNP	Number=Sing	5	obj	5:obj	Entity=(abstract-97-new-1-coref)|SpaceAfter=No|XML=<hi rend:::"italic"></hi>
7	,	,	PUNCT	,	_	9	punct	9:punct	_
8	a	a	DET	DT	Definite=Ind|PronType=Art	9	det	9:det	Entity=(abstract-97-giv:act-2-appos
9	series	series	NOUN	NN	Number=Sing	6	appos	6:appos	_
10	of	of	ADP	IN	_	11	case	11:case	_
11	elegies	elegy	NOUN	NNS	Number=Plur	9	nmod	9:nmod:of	Entity=97)|SpaceAfter=No
12	.	.	PUNCT	.	_	5	punct	5:punct	_
13	[	[	PUNCT	-LRB-	_	14	punct	14:punct	Discourse=evidence:71->70:0|SpaceAfter=No
14	25	25	NUM	CD	NumForm=Digit|NumType=Card	5	dep	5:dep	Entity=(abstract-98-new-1-sgl)|SpaceAfter=No
15	]	]	PUNCT	-RRB-	_	14	punct	14:punct	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 7 det	color:blue
1	—	—	PUNCT	:	_	2	punct	2:punct	Discourse=attribution:60->54:1
2	NORTON	Norton	PROPN	NNP	Number=Sing	0	root	0:root	Entity=(abstract-102-new-1,4-coref(person-1-giv:act-1-coref-Emperor_Norton
3	I	I	NUM	CD	NumForm=Roman|NumType=Card	2	dep	2:dep	Entity=1)|SpaceAfter=No
4	,	,	PUNCT	,	_	5	punct	5:punct	_
5	Emperor	Emperor	PROPN	NNP	Number=Sing	2	appos	2:appos	Entity=(person-1-giv:act-1,4,5-appos-Emperor_Norton
6	of	of	ADP	IN	_	9	case	9:case	_
7	the	the	DET	DT	Definite=Def|PronType=Art	9	det	9:det	Entity=(place-8-giv:act-2,3-coref-United_States
8	United	Unite	VERB	NNP	Tense=Past|VerbForm=Part	9	amod	9:amod	_
9	States	State	PROPN	NNPS	Number=Plur	5	nmod	5:nmod:of	Entity=8)1)102)|SpaceAfter=No
10	.	.	PUNCT	.	_	2	punct	2:punct	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 3 det	color:blue
1	By	by	ADP	IN	_	2	case	2:case	Discourse=elaboration:68->65:1
2	far	far	ADV	RB	Degree=Pos	10	nmod	10:nmod:by	_
3	the	the	DET	DT	Definite=Def|PronType=Art	5	det	5:det	Entity=(abstract-121-new-3-coref
4	most	most	ADV	RBS	Degree=Sup	5	advmod	5:advmod	_
5	successful	successful	ADJ	JJ	Degree=Pos	10	nsubj	10:nsubj	_
6	of	of	ADP	IN	_	8	case	8:case	_
7	the	the	DET	DT	Definite=Def|PronType=Art	8	det	8:det	Bridge=115<122|Entity=(abstract-122-acc:inf-2-sgl
8	operas	opera	NOUN	NNS	Number=Plur	5	obl	5:obl:of	Entity=122)121)
9	is	be	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	10	cop	10:cop	_
10	Rusalka	Rusalka	PROPN	NNP	Number=Sing	0	root	0:root	Entity=(abstract-121-giv:act-1-coref-Rusalka_%28opera%29)|SpaceAfter=No|XML=<hi rend:::"italic"><ref target:::"https://en.wikipedia.org/wiki/Rusalka_(opera)"></ref></hi>
11	.	.	PUNCT	.	_	10	punct	10:punct	_

~~~


