---
layout: feature
title: 'VerbForm'
shortdef: 'form of verb or deverbative'
udver: '2'
---

Principally, `VerbForm` is an inflectional feature of [verbs](VERB) and [auxiliaries](AUX), however, it is also used as a lexical feature of some [adjectives](ADJ) and [adverbs](ADV).

### <a name="Fin">`Fin`</a>: finite verb

Verbs that have a non-empty [Mood]() are considered finite.

#### Examples

* _študiram, študiraš, študira_ "I study, you study, he/she/it studies"
* _študiraj, študirajmo, študirajte_ "study!-sing, let's study!, study!-plur"
* _bom, boš, bo_ "I will, you will, he/she/it will"
* _bi_ "would"

### <a name="Inf">`Inf`</a>: infinitive

Infinitive is the citation form of verbs and it appears as the argument of modal and other verbs.

#### Examples

* _študirati_ "to study"
* _biti_ "to be"

### <a name="Sup">`Sup`</a>: supine

Supine is a rare verb form, which has disappeared from most of the other Slavic languages.
It is used instead of infinitive as the argument of motion verbs.

#### Examples

* _<b>Spat</b> je odšel prej kot navadno._ “He went to bed (lit. <b>to sleep</b) earlier than usual.”

### <a name="Part">`Part`</a>: participle

Participle is a non-finite verb form that shares properties of verbs and adjectives. We distinguish two groups of participles: l-participles that can either be classified as [verbs](VERB) or [adjectives](ADJ), and all other participles (usually ending in _-č_, _-n_, or _-t_) that are always classified as [adjectives](ADJ), regardless of whether they are used as attributes or predicates.

As verbs, _L-participles_ are used to form the past and future tense, and the conditional mood in present or past tense. As adjectives, both groups of participles can be used either as noun attributes (_ukradena denarnica_ "stolen wallet"), as subject complements (_denarnica je ukradena_ "the wallet is stolen") or in passive constructions (_denarnica je bila ukradena_ "the wallet has been stolen").

#### Examples

- _zgorel, zgorelo, zgorela, zgoreli_ “burned” (past participle in different genders and numbers)
- _zgorel, zgorelega, zgorelemu, zgorelega ..._ "burnt" (participial adjective in different genders, numbers and cases)
- _ukraden, ukradenega, ukradenemu, ukradenega_ ..."stolen” (participial adjective in different genders, numbers and cases)

### <a name="Conv">`Conv`</a>: converb / adverbial participle

The converb, also called adverbial participle, is a non-finite verb form that shares properties of verbs and adverbs. In Slovenian, `converbs` are always tagged as [adverbs](ADV).

#### Examples

* _rekoč_ "having said"
* _sodeč_ "judging"
* _upoštevaje_ "taking into account"
* _nevede_ "unknowingly"


### Conversion from JOS

All verbs with feature VForm=present, VForm=future, VForm=conditional and VForm=imperative are converted to UD `VerbForm=Fin`. All verbs with VForm=Infinitive are converted to UD `VerbForm=Inf`, all verbs with VForm=Supine are converted to UD `VerbForm=Sup`, and all verbs with VForm=Participle are converted to UD `VerbForm=Part`. Additionally, all adjectives with Type=participle are converted to UD `VerbForm=Part` and all adverbs with Type=participle are converted to UD `VerbForm=Conv`.

Note that `gerunds` are currently marked as [nouns](NOUN) and do not have a special `VerbForm` feature to distinguish them from other common nouns.
<!-- Interlanguage links updated St lis 3 20:58:32 CET 2021 -->
