

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Portuguese)

This relation is universal.

995 nodes (0%) are attached to their parents as `iobj`.

739 instances of `iobj` (74%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.79396984924623.

The following 8 pairs of parts of speech are connected with `iobj`: [pt-pos/VERB]()-[pt-pos/NOUN]() (487; 49% instances), [pt-pos/VERB]()-[pt-pos/PRON]() (386; 39% instances), [pt-pos/VERB]()-[pt-pos/PROPN]() (107; 11% instances), [pt-pos/VERB]()-[pt-pos/ADJ]() (5; 1% instances), [pt-pos/VERB]()-[pt-pos/NUM]() (4; 0% instances), [pt-pos/VERB]()-[pt-pos/ADV]() (2; 0% instances), [pt-pos/VERB]()-[pt-pos/DET]() (2; 0% instances), [pt-pos/VERB]()-[pt-pos/SYM]() (2; 0% instances).


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 6 iobj	color:blue
1	Eu	eu	PRON	pron-pers|M|1S|NOM	Case=Nom|Gender=Masc|Number=Sing|Person=1|PronType=Prs	4	nsubj	_	_
2	não	não	ADV	adv	_	4	neg	_	_
3	me	eu	PRON	pron-pers|<refl>|M|1S|ACC	Case=Acc|Gender=Masc|Number=Sing|Person=1|PronType=Prs|Reflex=Yes	4	dobj	_	_
4	associo	associar	VERB	v-fin|PR|1S|IND	Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	0	root	_	_
5	com	com	ADP	prp	AdpType=Prep	6	case	_	_
6	moda	moda	NOUN	n|F|S	Gender=Fem|Number=Sing	4	iobj	_	_
7	.	.	PUNCT	punc	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 iobj	color:blue
1	«	«	PUNCT	punc	_	3	punct	_	_
2	Me	eu	PRON	pron-pers|<refl>|M|1S|DAT	Case=Dat|Gender=Masc|Number=Sing|Person=1|PronType=Prs|Reflex=Yes	3	iobj	_	_
3	pergunto	perguntar	VERB	v-fin|PR|1S|IND	Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	0	root	_	_
4	sempre	sempre	ADV	adv	_	3	advmod	_	_
5	quem	quem	PRON	pron-indp|<rel>|M|S	Gender=Masc|Number=Sing|PronType=Rel	3	nsubj	_	_
6	podia	poder	AUX	v-fin|IMPF|3S|IND	Mood=Ind|Number=Sing|Person=3|Tense=Imp|VerbForm=Fin	7	aux	_	_
7	ter	ter	VERB	v-inf	VerbForm=Inf	3	xcomp	_	_
8	sido	ser	VERB	v-pcp	VerbForm=Part	11	cop	_	_
9	aquele	aquele	DET	pron-det|<dem>|M|S	Gender=Masc|Number=Sing|PronType=Dem	11	det	_	_
10	jovem	jovem	ADJ	adj|M|S	Gender=Masc|Number=Sing	11	amod	_	_
11	alemão	alemão	NOUN	n|M|S	Gender=Masc|Number=Sing	7	ccomp	_	_
12	.	.	PUNCT	punc	_	3	punct	_	_
13	»	»	PUNCT	punc	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 8 iobj	color:blue
1	O	o	DET	art|<artd>|M|S	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	2	det	_	_
2	PSD	PSD	PROPN	prop|M|S	Gender=Masc|Number=Sing	3	nsubj	_	_
3	decidiu	decidir	VERB	v-fin|PS|3S|IND	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	0	root	_	_
4	deixar	deixar	VERB	v-inf	VerbForm=Inf	3	xcomp	_	_
5	hoje	hoje	ADV	adv	_	4	advmod	_	_
6	pronta	pronto	ADJ	adj|F|S	Gender=Fem|Number=Sing	4	xcomp	_	_
7	a	o	DET	art|<artd>|F|S	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	8	det	_	_
8	Lei	Lei	PROPN	prop|F|S	_	4	iobj	_	MWE=Lei_da_Greve|MWEPOS=PROPN
9	de	de	ADP	prp|<sam->	AdpType=Prep	11	case	_	_
10	a	o	DET	art|<-sam>|<artd>|F|S	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	11	det	_	_
11	Greve	Greve	PROPN	PROPN	_	8	name	_	_
12	.	.	PUNCT	punc	_	3	punct	_	_

~~~




--------------------------------------------------------------------------------

## Treebank Statistics (UD_Portuguese-Bosque)

This relation is universal.

231 nodes (0%) are attached to their parents as `iobj`.

146 instances of `iobj` (63%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.23376623376623.

The following 4 pairs of parts of speech are connected with `iobj`: [pt-pos/VERB]()-[pt-pos/PRON]() (226; 98% instances), [pt-pos/ADJ]()-[pt-pos/PRON]() (2; 1% instances), [pt-pos/NOUN]()-[pt-pos/PRON]() (2; 1% instances), [pt-pos/ADV]()-[pt-pos/PRON]() (1; 0% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 iobj	color:blue
1	Depois	depois	ADV	ADV|@ADVL>	_	2	advmod	_	_
2	rasgou-	rasgar	VERB	<mv>|<first-cjt>|<hyphen>|V|PS|3S|IND|@FS-STA	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	0	root	_	_
3	lhe	ela	PRON	PERS|F|3S|DAT|@<DAT	Case=Dat|Gender=Fem|Number=Sing|Person=3|PronType=Prs	2	iobj	_	_
4	a	o	DET	<artd>|ART|F|S|@>N	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	5	det	_	_
5	roupa	roupa	NOUN	<np-def>|N|F|S|@<ACC	Gender=Fem|Number=Sing	2	dobj	_	_
6	e	e	CONJ	<co-fcl>|<co-fmc>|<co-vfin>|KC|@CO	_	2	cc	_	_
7	tentou	tentar	VERB	<mv>|<cjt>|V|PS|3S|IND|@FS-STA	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	2	conj	_	_
8	consumar	consumar	VERB	<mv>|V|INF|@ICL-<ACC	VerbForm=Inf	7	xcomp	_	_
9	a	o	DET	<artd>|ART|F|S|@>N	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	10	det	_	_
10	violação	violação	NOUN	<np-def>|N|F|S|@<ACC	Gender=Fem|Number=Sing	8	dobj	_	_
11	.	.	PUNCT	PU|@PU	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 54	bgColor:blue
# visual-style 54	fgColor:white
# visual-style 58	bgColor:blue
# visual-style 58	fgColor:white
# visual-style 58 54 iobj	color:blue
1	Voltando	voltar	VERB	<mv>|V|GER|@ICL-ADVL>	VerbForm=Ger	17	advcl	_	_
2	a	a	ADP	<sam->|PRP|@<SA	_	4	case	_	_
3	a	o	DET	<-sam>|<artd>|ART|@>N	Definite=Def|PronType=Art	4	det	_	_
4	rua	rua	NOUN	<np-def>|N|F|S|@P<	Gender=Fem|Number=Sing	1	nmod	_	_
5	que	que	PRON	<rel>|INDP|F|S|@SUBJ>	Gender=Fem|Number=Sing|PronType=Rel	8	nsubj	_	_
6	durante	durante	ADP	PRP|@ADVL>	_	7	case	_	_
7	décadas	década	NOUN	<np-idf>|N|F|P|@P<	Gender=Fem|Number=Plur	8	nmod	_	_
8	evocou	evocar	VERB	<mv>|V|PS|3S|IND|@FS-N<	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	4	acl:relcl	_	_
9	o	o	DET	<artd>|ART|M|S|@>N	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	11	det	_	_
10	talentoso	talentoso	ADJ	ADJ|M|S|@>N	Gender=Masc|Number=Sing	11	amod	_	_
11	marido	marido	NOUN	<np-def>|N|M|S|@<ACC	Gender=Masc|Number=Sing	8	dobj	_	_
12	de	de	ADP	PRP|@N<	_	13	case	_	_
13	D.	D.	PROPN	PROP|F|S|@P<	Gender=Fem|Number=Sing	11	nmod	_	MWE:D.=Maria=II
14	Maria	Maria	PROPN	PROP|@N<	Number=Sing	13	name	_	_
15	II	II	PROPN	PROP|@N<	Number=Sing	13	name	_	_
16	,	,	PUNCT	PU|@PU	_	8	punct	_	_
17	citemos	citar	VERB	<mv>|V|PR|1P|SUBJ|@FS-STA	Mood=Sub|Number=Plur|Person=1|Tense=Pres|VerbForm=Fin	0	root	_	_
18	mais	mais	ADV	<setop>|ADV|@>A	_	19	advmod	_	_
19	um	um	NUM	<card>|NUM|M|S|@>N	_	20	nummod	_	_
20	passo	passo	NOUN	<np-def>|N|M|S|@<ACC	Gender=Masc|Number=Sing	17	dobj	_	_
21	de	de	ADP	<sam->|PRP|@N<ARG	_	25	case	_	_
22	o	o	DET	<-sam>|<artd>|ART|M|S|@>N	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	25	det	_	_
23	já	já	ADV	ADV|@>A	_	24	advmod	_	_
24	referido	referir	VERB	<mv>|V|PCP|M|S|@ICL-N<	Gender=Masc|Number=Sing|VerbForm=Part	25	acl	_	_
25	relatório	relatório	NOUN	<np-idf>|N|M|S|@P<	Gender=Masc|Number=Sing	20	nmod	_	_
26	de	de	ADP	<sam->|PRP|@N<	_	28	case	_	_
27	a	o	DET	<-sam>|<artd>|ART|@>N	Definite=Def|PronType=Art	28	det	_	_
28	Câmara	Câmara	PROPN	PROP|F|S|@P<	Gender=Fem|Number=Sing	25	nmod	_	MWE:Câmara=do=Porto
29	de	de	ADP	<sam->|PRP|@N<	_	31	case	_	_
30	o	o	DET	<artd>|<-sam>|DET|M|S|@>N	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	31	det	_	_
31	Porto	Porto	PROPN	PROP|@P<	Number=Sing	28	nmod	_	_
32	,	,	PUNCT	PU|@PU	_	24	punct	_	_
33	que	que	PRON	<rel>|INDP|M|S|@SUBJ>	Gender=Masc|Number=Sing|PronType=Rel	35	nsubj	_	_
34	nos	nós	PRON	<refl>|PERS|M/F|1P|ACC|@ACC>	Case=Acc|Gender=Unsp|Number=Plur|Person=1|PronType=Prs	35	dobj	_	_
35	permite	permitir	VERB	<mv>|V|PR|3S|IND|@FS-N<PRED	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	25	acl:relcl	_	_
36	avaliar	avaliar	VERB	<mv>|V|INF|@ICL-<ACC	VerbForm=Inf	35	xcomp	_	_
37	até	até	ADP	PRP|@ADVL>	_	39	case	_	_
38	que	que	DET	<interr>|DET|M|S|@>N	Gender=Masc|Number=Sing|PronType=Int	39	det	_	_
39	ponto	ponto	NOUN	<np-idf>|N|M|S|@P<	Gender=Masc|Number=Sing	48	nmod	_	_
40	a	o	DET	<artd>|ART|F|S|@>N	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	41	det	_	_
41	concretização	concretização	NOUN	<np-def>|N|F|S|@SUBJ>	Gender=Fem|Number=Sing	48	nsubj	_	_
42	de	de	ADP	<sam->|PRP|@N<ARG	_	44	case	_	_
43	a	o	DET	<-sam>|<artd>|ART|@>N	Definite=Def|PronType=Art	44	det	_	_
44	Rua	Rua	PROPN	PROP|F|S|@P<	Gender=Fem|Number=Sing	41	nmod	_	MWE:Rua=de=D.=Fernando
45	de	de	ADP	PRP|@N<	_	46	case	_	_
46	D.	D.	PROPN	PROP|@P<	Number=Sing	44	nmod	_	MWE:D.=Fernando
47	Fernando	Fernando	PROPN	PROP|@N<	Number=Sing	46	name	_	_
48	ficou	ficar	VERB	<mv>|V|PS|3S|IND|@FS-<ACC	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	36	ccomp	_	_
49	aquém	aquém	ADV	ADV|@<SA	_	48	advmod	_	MWE:aquém=de
50	de	de	ADP	PRP|@A<	_	52	case	_	_
51	as	o	DET	<-sam>|<artd>|ART|@>N	Definite=Def|PronType=Art	52	det	_	_
52	intenções	intenção	NOUN	<np-def>|N|F|P|@P<	Gender=Fem|Number=Plur	49	nmod	_	_
53	que	que	PRON	<rel>|INDP|F|P|@SUBJ>	Gender=Fem|Number=Plur|PronType=Rel	58	nsubj	_	_
54	lhe	ela	PRON	PERS|F|3S|DAT|@DAT>	Case=Dat|Gender=Fem|Number=Sing|Person=3|PronType=Prs	58	iobj	_	_
55	estiveram	estar	VERB	<mv>|V|PS|3P|IND|@FS-N<	Mood=Ind|Number=Plur|Person=3|Tense=Past|VerbForm=Fin	58	cop	_	_
56	em	em	ADP	<sam->|PRP|@<SA	_	58	case	_	_
57	a	o	DET	<-sam>|<artd>|ART|@>N	Definite=Def|PronType=Art	58	det	_	_
58	origem	origem	NOUN	<np-def>|N|F|S|@P<	Gender=Fem|Number=Sing	52	nmod	_	_
59	.	.	PUNCT	PU|@PU	_	17	punct	_	_

~~~


~~~ conllu
# visual-style 20	bgColor:blue
# visual-style 20	fgColor:white
# visual-style 23	bgColor:blue
# visual-style 23	fgColor:white
# visual-style 23 20 iobj	color:blue
1	«	«	PUNCT	PU|@PU	_	23	punct	_	_
2	Um	um	DET	<arti>|ART|M|S|@>N	Definite=Ind|Gender=Masc|Number=Sing|PronType=Art	4	det	_	_
3	outro	outro	DET	<diff>|DET|M|S|@>N	Gender=Masc|Number=Sing	4	det	_	_
4	poder	poder	NOUN	<np-idf>|N|M|S|@SUBJ>	Gender=Masc|Number=Sing	23	nsubj	_	_
5	,	,	PUNCT	PU|@PU	_	6	punct	_	_
6	aliado	aliar	VERB	<mv>|<first-cjt>|V|PCP|M|S|@ICL-N<PRED	Gender=Masc|Number=Sing|VerbForm=Part	4	acl	_	_
7	mas	mas	CONJ	<co-pred>|KC|@CO	_	6	cc	_	_
8	diferente	diferente	ADJ	ADJ|M|S|@ICL-N<PRED	Gender=Masc|Number=Sing	6	dep	_	_
9	,	,	PUNCT	PU|@PU	_	6	punct	_	_
10	como	como	ADV	<rel>|ADV|@ADVL>	_	14	advmod	_	_
11	pode	poder	AUX	<aux>|V|PR|3S|IND|@FS-N<PRED	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	14	aux	_	_
12	vir	vir	AUX	<aux>|V|INF|@ICL-AUX<	VerbForm=Inf	14	aux	_	_
13	a	a	ADP	PRP|@PRT-AUX<	_	14	nmod	_	_
14	ser	ser	VERB	<mv>|V|INF|@ICL-AUX<	VerbForm=Inf	4	acl:relcl	_	_
15	a	o	DET	<artd>|ART|F|S|@>N	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	16	det	_	_
16	União	União	PROPN	PROP|F|S|@<SUBJ	Gender=Fem|Number=Sing	14	nsubj	_	MWE:União=Europeia
17	Europeia	Europeia	PROPN	PROP|@N<	Number=Sing	16	name	_	_
18	,	,	PUNCT	PU|@PU	_	14	punct	_	_
19	só	só	ADV	ADV|@ADVL>	_	23	advmod	_	_
20	lhes	eles	PRON	PERS|M|3P|DAT|@DAT>	Case=Dat|Gender=Masc|Number=Plur|Person=3|PronType=Prs	23	iobj	_	_
21	pode	poder	AUX	<aux>|V|PR|3S|IND|@FS-STA	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	23	aux	_	_
22	ser	ser	VERB	<mv>|V|INF|@ICL-AUX<	VerbForm=Inf	23	cop	_	_
23	útil	útil	ADJ	ADJ|M|S|@<SC	Gender=Masc|Number=Sing	0	root	_	_
24	»	»	PUNCT	PU|@PU	_	23	punct	_	_
25	.	.	PUNCT	PU|@PU	_	23	punct	_	_

~~~




--------------------------------------------------------------------------------

## Treebank Statistics (UD_Portuguese-BR)

This relation is universal.

516 nodes (0%) are attached to their parents as `iobj`.

427 instances of `iobj` (83%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.95348837209302.

The following 11 pairs of parts of speech are connected with `iobj`: [pt-pos/VERB]()-[pt-pos/NOUN]() (274; 53% instances), [pt-pos/VERB]()-[pt-pos/PROPN]() (119; 23% instances), [pt-pos/VERB]()-[pt-pos/PRON]() (112; 22% instances), [pt-pos/ADP]()-[pt-pos/NOUN]() (2; 0% instances), [pt-pos/PROPN]()-[pt-pos/PROPN]() (2; 0% instances), [pt-pos/VERB]()-[pt-pos/X]() (2; 0% instances), [pt-pos/NOUN]()-[pt-pos/NOUN]() (1; 0% instances), [pt-pos/NOUN]()-[pt-pos/PRON]() (1; 0% instances), [pt-pos/PROPN]()-[pt-pos/NOUN]() (1; 0% instances), [pt-pos/VERB]()-[pt-pos/ADP]() (1; 0% instances), [pt-pos/VERB]()-[pt-pos/PART]() (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 5 iobj	color:blue
1	O	_	DET	DET	_	2	det	_	_
2	veículo	_	NOUN	NOUN	_	3	nsubj	_	_
3	pertence	_	VERB	VERB	_	0	root	_	_
4	ao	_	ADP	ADP	_	5	case	_	_
5	sogro	_	NOUN	NOUN	_	3	iobj	_	_
6	de	_	ADP	ADP	_	7	case	_	_
7	Roniere	_	PROPN	PNOUN	_	5	nmod	_	_
8	.	_	PUNCT	.	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 8 iobj	color:blue
1	Em	_	ADP	ADP	_	2	case	_	_
2	nota	_	NOUN	NOUN	_	6	nmod	_	_
3	,	_	PUNCT	.	_	2	punct	_	_
4	o	_	DET	DET	_	5	det	_	_
5	Google	_	PROPN	PNOUN	_	6	nsubj	_	_
6	informou	_	VERB	VERB	_	0	root	_	_
7	ao	_	ADP	ADP	_	8	case	_	_
8	G1	_	PROPN	PNOUN	_	6	iobj	_	_
9	que	_	CONJ	CONJ	_	11	mark	_	_
10	vai	_	AUX	AUX	_	11	aux	_	_
11	recorrer	_	VERB	VERB	_	6	ccomp	_	_
12	da	_	ADP	ADP	_	13	case	_	_
13	decisão	_	NOUN	NOUN	_	11	nmod	_	_
14	.	_	PUNCT	.	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 8 iobj	color:blue
1	Não	_	ADV	ADV	_	2	neg	_	_
2	faria	_	VERB	VERB	_	0	root	_	_
3	isso	_	PRON	PRON	_	2	dobj	_	_
4	com	_	ADP	ADP	_	6	case	_	_
5	um	_	DET	DET	_	6	det	_	_
6	clube	_	NOUN	NOUN	_	2	nmod	_	_
7	que	_	PRON	PRON	_	9	nsubj	_	_
8	me	_	PRON	PRON	_	9	iobj	_	_
9	deu	_	VERB	VERB	_	6	acl:relcl	_	_
10	tanto	_	PRON	PRON	_	9	dobj	_	_
11	.	_	PUNCT	.	_	2	punct	_	_

~~~


