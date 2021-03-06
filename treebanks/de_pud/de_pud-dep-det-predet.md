---
layout: base
title:  'Statistics of det:predet in UD_German-PUD'
udver: '2'
---

## Treebank Statistics: UD_German-PUD: Relations: `det:predet`

This relation is a language-specific subtype of <tt><a href="de_pud-dep-det.html">det</a></tt>.

32 nodes (0%) are attached to their parents as `det:predet`.

32 instances of `det:predet` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.40625.

The following 2 pairs of parts of speech are connected with `det:predet`: <tt><a href="de_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_pud-pos-DET.html">DET</a></tt> (31; 97% instances), <tt><a href="de_pud-pos-PROPN.html">PROPN</a></tt>-<tt><a href="de_pud-pos-DET.html">DET</a></tt> (1; 3% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 5 det:predet	color:blue
1	In	in	ADP	APPR	_	3	case	_	_
2	dem	der	DET	ART	Case=Dat|Definite=Def|Gender=Neut|Number=Sing|Person=3	3	det	_	_
3	Mittelalter	_	NOUN	NN	Case=Dat|Gender=Neut|Number=Sing|Person=3	4	obl	_	_
4	hatten	_	VERB	VBC	Mood=Ind|Number=Plur|Person=3|Tense=Past	0	root	_	_
5	die	_	DET	PDT	Case=Nom|Definite=Def|Gender=Masc|Number=Plur|Person=3	7	det:predet	_	_
6	meisten	_	DET	DT	Case=Nom|Definite=Ind|Gender=Masc|Number=Plur|Person=3	7	det	_	_
7	Christen	_	NOUN	NN	Case=Nom|Gender=Masc|Number=Plur|Person=3	4	nsubj	_	Proper=True
8	keinen	_	DET	DT	Case=Acc|Definite=Ind|Gender=Masc|Number=Sing|Person=3	9	det	_	_
9	Zugang	_	NOUN	NN	Case=Acc|Gender=Masc|Number=Sing|Person=3	4	obj	_	_
10	zu	_	ADP	IN	_	12	case	_	_
11	einer	_	DET	DT	Case=Dat|Definite=Ind|Gender=Fem|Number=Sing|Person=3	12	det	_	_
12	Bibel	_	NOUN	NN	Case=Dat|Gender=Fem|Number=Sing|Person=3	9	nmod	_	_
13	in	_	ADP	IN	_	15	case	_	_
14	ihrer	_	PRON	DTP$	Case=Dat|Gender=Fem|Gender[psor]=Masc|Number=Sing|Number[psor]=Plur|Person=3|Person[psor]=3|PronType=Prs	15	nmod:poss	_	_
15	Muttersprache	_	NOUN	NN	Case=Dat|Gender=Fem|Number=Sing|Person=3	12	nmod	_	SpaceAfter=No
16	.	_	PUNCT	.	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 13	bgColor:blue
# visual-style 13	fgColor:white
# visual-style 13 11 det:predet	color:blue
1	Letzterer	_	NOUN	NNA	Case=Nom|Gender=Masc|Number=Sing|Person=3	2	nsubj	_	InflectionType=Strong
2	verbreitete	_	VERB	VBC	Mood=Ind|Number=Sing|Person=3|Tense=Past	0	root	_	_
3	den	_	DET	DT	Case=Acc|Definite=Def|Gender=Masc|Number=Sing|Person=3	4	det	_	_
4	Islam	_	PROPN	NNP	Case=Acc|Gender=Masc|Number=Sing|Person=3	2	obj	_	_
5	in	in	ADP	APPR	_	8	case	_	_
6	dem	der	DET	ART	Case=Dat|Definite=Def|Gender=Masc|Number=Sing|Person=3	8	det	_	_
7	küstennahen	_	ADJ	JJ	Case=Dat|Degree=Pos|Gender=Masc|Number=Sing|Person=3	8	amod	_	InflectionType=Weak
8	Gürtel	_	NOUN	NN	Case=Dat|Gender=Masc|Number=Sing|Person=3	2	obl	_	SpaceAfter=No
9	,	_	PUNCT	,	_	14	punct	_	_
10	doch	_	CCONJ	CC	_	14	cc	_	_
11	die	_	DET	PDT	Case=Nom|Definite=Def|Number=Plur|Person=3	13	det:predet	_	_
12	meisten	_	DET	DT	Case=Nom|Definite=Ind|Number=Plur|Person=3	13	det	_	_
13	Bantu	_	PROPN	NNP	Case=Nom|Number=Plur|Person=3	14	nsubj	_	_
14	kamen	_	VERB	VBC	Mood=Ind|Number=Plur|Person=3|Tense=Past	2	conj	_	_
15	nie	_	ADV	RB	Degree=Pos	14	advmod	_	_
16	in	_	ADP	IN	_	17	case	_	_
17	Kontakt	_	NOUN	NN	Case=Acc|Gender=Masc|Number=Sing|Person=3	14	obl	_	_
18	mit	_	ADP	IN	_	20	case	_	_
19	dem	_	DET	DT	Case=Dat|Definite=Def|Gender=Masc|Number=Sing|Person=3	20	det	_	_
20	Islam	_	PROPN	NNP	Case=Dat|Gender=Masc|Number=Sing|Person=3	14	obl	_	_
21	und	_	CCONJ	CC	_	23	cc	_	_
22	blieben	_	AUX	VBC	Mood=Ind|Number=Plur|Person=3|Tense=Past	23	cop	_	_
23	Anhänger	_	NOUN	NN	Case=Nom|Gender=Masc|Number=Plur|Person=3	14	conj	_	_
24	der	_	DET	DT	Case=Gen|Definite=Def|Gender=Fem|Number=Sing|Person=3	27	det	_	_
25	traditionellen	_	ADJ	JJ	Case=Gen|Degree=Pos|Gender=Fem|Number=Sing|Person=3	27	amod	_	InflectionType=Weak
26	afrikanischen	_	ADJ	JJ	Case=Gen|Degree=Pos|Gender=Fem|Number=Sing|Person=3	25	conj	_	InflectionType=Weak|Proper=True
27	Religion	_	NOUN	NN	Case=Gen|Gender=Fem|Number=Sing|Person=3	23	nmod	_	SpaceAfter=No
28	.	_	PUNCT	.	_	2	punct	_	_

~~~


