---
layout: base
title:  'Statistics of obl:npmod in UD_English-GUMReddit'
udver: '2'
---

## Treebank Statistics: UD_English-GUMReddit: Relations: `obl:npmod`

This relation is a language-specific subtype of <tt><a href="en_gumreddit-dep-obl.html">obl</a></tt>.
There are also 1 other language-specific subtypes of `obl`: <tt><a href="en_gumreddit-dep-obl-tmod.html">obl:tmod</a></tt>.

40 nodes (0%) are attached to their parents as `obl:npmod`.

27 instances of `obl:npmod` (68%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.225.

The following 12 pairs of parts of speech are connected with `obl:npmod`: <tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt> (16; 40% instances), <tt><a href="en_gumreddit-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt> (8; 20% instances), <tt><a href="en_gumreddit-pos-ADV.html">ADV</a></tt>-<tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt> (3; 8% instances), <tt><a href="en_gumreddit-pos-ADV.html">ADV</a></tt>-<tt><a href="en_gumreddit-pos-ADJ.html">ADJ</a></tt> (2; 5% instances), <tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gumreddit-pos-ADJ.html">ADJ</a></tt> (2; 5% instances), <tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gumreddit-pos-DET.html">DET</a></tt> (2; 5% instances), <tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gumreddit-pos-PRON.html">PRON</a></tt> (2; 5% instances), <tt><a href="en_gumreddit-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gumreddit-pos-ADJ.html">ADJ</a></tt> (1; 3% instances), <tt><a href="en_gumreddit-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gumreddit-pos-PRON.html">PRON</a></tt> (1; 3% instances), <tt><a href="en_gumreddit-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_gumreddit-pos-PRON.html">PRON</a></tt> (1; 3% instances), <tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gumreddit-pos-ADV.html">ADV</a></tt> (1; 3% instances), <tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gumreddit-pos-PROPN.html">PROPN</a></tt> (1; 3% instances).


~~~ conllu
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 12 obl:npmod	color:blue
1	_	_	PRON	PRP	Case=Nom|Number=Sing|Person=1|PronType=Prs	2	nsubj	2:nsubj	Discourse=justify:82->80:2|Entity=(person-70-giv:inact-1-ana)|Lem=_|Len=1
2	_	_	VERB	VBP	Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	0	root	0:root	Lem=_|Len=4
3	_	_	PRON	DT	Number=Sing|PronType=Dem	2	obj	2:obj	Entity=(event-90-giv:act-1-coref)|Lem=_|Len=4
4	_	_	SCONJ	IN	_	7	mark	7:mark	Discourse=evidence:83->82:0|Lem=_|Len=7
5	_	_	PRON	PRP	Case=Nom|Number=Sing|Person=1|PronType=Prs	7	nsubj	7:nsubj	Entity=(person-70-giv:act-1-ana)|Lem=_|Len=1
6	_	_	AUX	VBP	Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	7	aux	7:aux	Lem=have|Len=3
7	_	_	VERB	VBN	Tense=Past|VerbForm=Part	2	advcl	2:advcl:because	Lem=see|Len=4
8	_	_	PRON	PRP	Case=Nom|Gender=Neut|Number=Sing|Person=3|PronType=Prs	9	nsubj	9:nsubj	Entity=(event-90-giv:act-1-ana)|Lem=_|Len=2
9	_	_	VERB	VB	VerbForm=Inf	7	ccomp	7:ccomp	Lem=_|Len=6
10	_	_	DET	DT	Definite=Ind|PronType=Art	11	det	11:det	Entity=(time-92-new-3-sgl|Lem=_|Len=1
11	_	_	NUM	CD	NumForm=Word|NumType=Card	12	compound	12:compound	Lem=_|Len=7
12	_	_	NOUN	NNS	Number=Plur	7	obl:npmod	7:obl:npmod	Entity=92)|Lem=time|Len=5|SpaceAfter=No
13	_	_	PUNCT	.	_	2	punct	2:punct	Lem=_|Len=1

~~~


~~~ conllu
# visual-style 27	bgColor:blue
# visual-style 27	fgColor:white
# visual-style 28	bgColor:blue
# visual-style 28	fgColor:white
# visual-style 28 27 obl:npmod	color:blue
1	_	_	DET	DT	Definite=Def|PronType=Art	3	det	3:det	Discourse=joint_m:145->133:5|Entity=(abstract-136-new-3-coref|Lem=*LOWER*|Len=3
2	_	_	NUM	CD	NumForm=Word|NumType=Card	3	nummod	3:nummod	Lem=*LOWER*|Len=3|XML=<hi rend:::"bold"></hi>
3	_	_	NOUN	NN	Number=Sing	15	nsubj	15:nsubj|30:nsubj:xsubj	Lem=_|Len=10
4	_	_	ADP	IN	_	6	case	6:case	Lem=_|Len=7
5	_	_	NOUN	NN	Number=Sing	6	compound	6:compound	Entity=(object-137-new-2-sgl|Lem=_|Len=5
6	_	_	NOUN	NN	Number=Sing	3	nmod	3:nmod:between	Entity=137)|Lem=_|Len=8
7	_	_	CCONJ	CC	_	8	cc	8:cc	Lem=_|Len=3
8	_	_	NOUN	NN	Number=Sing	6	conj	3:nmod:between|6:conj:and	Entity=(substance-98-giv:act-1-coref)136)|Lem=_|Len=4
9	_	_	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	15	cop	15:cop	Lem=be|Len=2
10	_	_	SCONJ	IN	_	15	mark	15:mark	Entity=(abstract-136-giv:act-6,19-coref|Lem=_|Len=4
11	_	_	SYM	SYM	_	15	nsubj	15:nsubj|30:nsubj:xsubj	Entity=(object-138-new-1-sgl|Lem=_|Len=1
12	_	_	NUM	CD	NumForm=Digit|NumType=Card	11	nummod	11:nummod	Lem=100000|Len=7
13	_	_	ADP	IN	_	14	case	14:case	Lem=_|Len=2
14	_	_	NOUN	NN	Number=Sing	11	nmod	11:nmod:in	Entity=(object-139-new-1-sgl)138)|Lem=_|Len=4
15	_	_	VERB	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	0:root	Lem=weigh|Len=6
16	_	_	DET	DT	Definite=Ind|PronType=Art	17	det	17:det	Lem=_|Len=1
17	_	_	NOUN	NN	Number=Sing	18	obl:npmod	18:obl:npmod	Lem=_|Len=3
18	_	_	ADV	RBR	Degree=Cmp	21	advmod	21:advmod	Lem=_|Len=4
19	_	_	ADP	IN	_	18	fixed	18:fixed	Lem=_|Len=4
20	_	_	SYM	SYM	_	15	obj	15:obj	Entity=(substance-140-new-1-sgl|Lem=_|Len=1
21	_	_	NUM	CD	NumForm=Digit|NumType=Card	20	nummod	20:nummod	Lem=100000|Len=7
22	_	_	ADP	IN	_	23	case	23:case	Lem=_|Len=2
23	_	_	NOUN	NN	Number=Sing	20	nmod	20:nmod:in	Entity=(substance-98-giv:act-1-coref)140)|Lem=_|Len=4
24	_	_	CCONJ	CC	_	28	cc	28:cc	Discourse=joint_m:146->145:0|Lem=_|Len=3
25	_	_	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	28	cop	28:cop	Lem=be|Len=2
26	_	_	DET	DT	Definite=Ind|PronType=Art	27	det	27:det	Lem=_|Len=1
27	_	_	NOUN	NN	Number=Sing	28	obl:npmod	28:obl:npmod	Lem=_|Len=3
28	_	_	ADJ	JJR	Degree=Cmp	15	conj	15:conj:and	Lem=easy|Len=6
29	_	_	PART	TO	_	30	mark	30:mark	Lem=_|Len=2
30	_	_	VERB	VB	VerbForm=Inf	28	xcomp	28:xcomp	Lem=_|Len=4
31	_	_	ADV	RB	Degree=Pos	28	advmod	28:advmod	Entity=136)|Lem=_|Len=3|SpaceAfter=No
32	_	_	PUNCT	.	_	15	punct	15:punct	Lem=_|Len=1

~~~


~~~ conllu
# visual-style 17	bgColor:blue
# visual-style 17	fgColor:white
# visual-style 18	bgColor:blue
# visual-style 18	fgColor:white
# visual-style 18 17 obl:npmod	color:blue
1	_	_	DET	DT	Definite=Def|PronType=Art	3	det	3:det	Discourse=joint_m:145->133:5|Entity=(abstract-136-new-3-coref|Lem=*LOWER*|Len=3
2	_	_	NUM	CD	NumForm=Word|NumType=Card	3	nummod	3:nummod	Lem=*LOWER*|Len=3|XML=<hi rend:::"bold"></hi>
3	_	_	NOUN	NN	Number=Sing	15	nsubj	15:nsubj|30:nsubj:xsubj	Lem=_|Len=10
4	_	_	ADP	IN	_	6	case	6:case	Lem=_|Len=7
5	_	_	NOUN	NN	Number=Sing	6	compound	6:compound	Entity=(object-137-new-2-sgl|Lem=_|Len=5
6	_	_	NOUN	NN	Number=Sing	3	nmod	3:nmod:between	Entity=137)|Lem=_|Len=8
7	_	_	CCONJ	CC	_	8	cc	8:cc	Lem=_|Len=3
8	_	_	NOUN	NN	Number=Sing	6	conj	3:nmod:between|6:conj:and	Entity=(substance-98-giv:act-1-coref)136)|Lem=_|Len=4
9	_	_	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	15	cop	15:cop	Lem=be|Len=2
10	_	_	SCONJ	IN	_	15	mark	15:mark	Entity=(abstract-136-giv:act-6,19-coref|Lem=_|Len=4
11	_	_	SYM	SYM	_	15	nsubj	15:nsubj|30:nsubj:xsubj	Entity=(object-138-new-1-sgl|Lem=_|Len=1
12	_	_	NUM	CD	NumForm=Digit|NumType=Card	11	nummod	11:nummod	Lem=100000|Len=7
13	_	_	ADP	IN	_	14	case	14:case	Lem=_|Len=2
14	_	_	NOUN	NN	Number=Sing	11	nmod	11:nmod:in	Entity=(object-139-new-1-sgl)138)|Lem=_|Len=4
15	_	_	VERB	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	0:root	Lem=weigh|Len=6
16	_	_	DET	DT	Definite=Ind|PronType=Art	17	det	17:det	Lem=_|Len=1
17	_	_	NOUN	NN	Number=Sing	18	obl:npmod	18:obl:npmod	Lem=_|Len=3
18	_	_	ADV	RBR	Degree=Cmp	21	advmod	21:advmod	Lem=_|Len=4
19	_	_	ADP	IN	_	18	fixed	18:fixed	Lem=_|Len=4
20	_	_	SYM	SYM	_	15	obj	15:obj	Entity=(substance-140-new-1-sgl|Lem=_|Len=1
21	_	_	NUM	CD	NumForm=Digit|NumType=Card	20	nummod	20:nummod	Lem=100000|Len=7
22	_	_	ADP	IN	_	23	case	23:case	Lem=_|Len=2
23	_	_	NOUN	NN	Number=Sing	20	nmod	20:nmod:in	Entity=(substance-98-giv:act-1-coref)140)|Lem=_|Len=4
24	_	_	CCONJ	CC	_	28	cc	28:cc	Discourse=joint_m:146->145:0|Lem=_|Len=3
25	_	_	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	28	cop	28:cop	Lem=be|Len=2
26	_	_	DET	DT	Definite=Ind|PronType=Art	27	det	27:det	Lem=_|Len=1
27	_	_	NOUN	NN	Number=Sing	28	obl:npmod	28:obl:npmod	Lem=_|Len=3
28	_	_	ADJ	JJR	Degree=Cmp	15	conj	15:conj:and	Lem=easy|Len=6
29	_	_	PART	TO	_	30	mark	30:mark	Lem=_|Len=2
30	_	_	VERB	VB	VerbForm=Inf	28	xcomp	28:xcomp	Lem=_|Len=4
31	_	_	ADV	RB	Degree=Pos	28	advmod	28:advmod	Entity=136)|Lem=_|Len=3|SpaceAfter=No
32	_	_	PUNCT	.	_	15	punct	15:punct	Lem=_|Len=1

~~~


