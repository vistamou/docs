---
layout: base
title:  'UD_Icelandic-IcePaHC'
udver: '2'
---

<!-- This page is automatically generated from the README file and from
     the data files in the latest release.

     Please do not edit this page directly. -->

# UD Icelandic IcePaHC

Language: [Icelandic](/is/index.html) (code: `is`)<br/>
Family: Indo-European, Germanic

This treebank has been part of Universal Dependencies since the UD v2.7 release.

The following people have contributed to making this treebank part of UD: Þórunn Arnardóttir, Hinrik Hafsteinsson, Einar Freyr Sigurðsson, Hildur Jónsdóttir, Kristín Bjarnadóttir, Anton Karl Ingason, Kristján Rúnarsson, Steinþór Steingrímsson, Joel C. Wallenberg, Eiríkur Rögnvaldsson.

Repository: [UD_Icelandic-IcePaHC](https://github.com/UniversalDependencies/UD_Icelandic-IcePaHC)<br />
Search this treebank on-line: [PML-TQ](https://lindat.mff.cuni.cz/services/pmltq/#!/treebank/udis_icepahc29)<br />
Download all treebanks: [UD 2.9](/#download)

License: CC BY-SA 4.0

Genre: fiction, bible, nonfiction, legal

Questions, comments?
General annotation questions (either Icelandic-specific or cross-linguistic) can be raised in the [main UD issue tracker](https://github.com/UniversalDependencies/docs/issues).
You can report bugs in this treebank in the [treebank-specific issue tracker on Github](https://github.com/UniversalDependencies/UD_Icelandic-IcePaHC/issues).
If you want to collaborate, please contact [thar&nbsp;(æt)&nbsp;hi&nbsp;•&nbsp;is, hinrik&nbsp;•&nbsp;hafst&nbsp;(æt)&nbsp;gmail&nbsp;•&nbsp;com, einar&nbsp;•&nbsp;freyr&nbsp;•&nbsp;sigurdsson&nbsp;(æt)&nbsp;arnastofnun&nbsp;•&nbsp;is].
Development of the treebank happens outside the UD repository.
If there are bugs, either the original data source or the conversion procedure must be fixed.
Do not submit pull requests against the UD repository.

| Annotation | Source |
|------------|--------|
| Lemmas | annotated manually in non-UD style, automatically converted to UD |
| UPOS | annotated manually in non-UD style, automatically converted to UD |
| XPOS | annotated manually |
| Features | assigned by a program, not checked manually |
| Relations | annotated manually in non-UD style, automatically converted to UD |

## Description

UD_Icelandic-IcePaHC is a conversion of the [Icelandic Parsed Historical Corpus (IcePaHC)](https://linguist.is/icelandic_treebank/Icelandic_Parsed_Historical_Corpus_(IcePaHC)) to the Universal Dependencies scheme.

The conversion was done using [UDConverter](https://github.com/thorunna/UDConverter).



The Icelandic Parsed Historical Corpus (IcePaHC) is a one-million-word, diachronic corpus which includes 61 texts from the 12th to 21st centuries. These texts were originally manually parsed according to the Penn Parsed Corpora of Historical English (PPCHE) annotation scheme. These parsed texts where then automatically converted to the Universal Dependencies scheme to create UD_Icelandic-IcePaHC.

## Text categories

UD_Icelandic-IcePaHC contains the following main genres:
- **NAR**: Narratives (sagas, fiction)
- **REL**: Religious texts (bible, sermons)
- **SCI**: Science (linguistics, natural sciences, history)
- **BIO**: Biographical material (biographies, travelogues)
- **LAW**: Law texts

Further subclassification is reflected in the extended genre label. For example **NAR-SAG** means narrative-saga and **REL-BIB** means religious text-bible

Each sentence ID in UD-Icelandic-IcePaHC carries the following information:

```
1150.FIRSTGRAMMAR.SCI-LIN,1.1
```
- Publication year of the text (`1150`)
- Name of the text (`FIRSTGRAMMAR`)
- Text genre (`SCI-LIN`)
- Index within text (`1`)
- Index within file (`1`)

Using the sentence IDs within UD_Icelandic-IcePaHC, specific genres or periods can be extracted or filtered from the treebank CoNLL-U files.

## Data split

For further info on each text, see the [IcePaHC documnentation](https://linguist.is/icelandic_treebank/Texts).

**TRAIN:**
- `1150.HOMILIUBOK.REL-SER`
- `1210.THORLAKUR.REL-SAG`
- `1250.STURLUNGA.NAR-SAG`
- `1260.JOMSVIKINGAR.NAR-SAG`
- `1270.GRAGAS.LAW-LAW`
- `1275.MORKIN.NAR-HIS`
- `1300.ALEXANDER.NAR-SAG`
- `1310.GRETTIR.NAR-SAG`
- `1325.ARNI.NAR-SAG`
- `1350.FINNBOGI.NAR-SAG`
- `1400.GUNNAR.NAR-SAG`
- `1400.VIGLUNDUR.NAR-SAG`
- `1450.ECTORSSAGA.NAR-SAG`
- `1450.JUDIT.REL-BIB`
- `1450.VILHJALMUR.NAR-SAG`
- `1480.JARLMANN.NAR-SAG`
- `1525.ERASMUS.NAR-SAG`
- `1540.NTJOHN.REL-BIB`
- `1593.EINTAL.REL-OTH`
- `1611.OKUR.REL-OTH`
- `1650.ILLUGI.NAR-SAG`
- `1659.PISLARSAGA.BIO-AUT`
- `1661.INDIAFARI.BIO-TRA`
- `1675.ARMANN.NAR-FIC`
- `1675.MAGNUS.BIO-OTH`
- `1675.MODARS.NAR-FIC`
- `1680.SKALHOLT.NAR-REL`
- `1725.BISKUPASOGUR.NAR-REL`
- `1790.FIMMBRAEDRA.NAR-SAG`
- `1791.JONSTEINGRIMS.BIO-AUT`
- `1830.HELLISMENN.NAR-SAG`
- `1835.JONASEDLI.SCI-NAT`
- `1859.HUGVEKJUR.REL-SER`
- `1861.ORRUSTA.NAR-FIC`
- `1882.TORFHILDUR.NAR-FIC`
- `1888.VORDRAUMUR.NAR-FIC`
- `1907.LEYSING.NAR-FIC`
- `1908.OFUREFLI.NAR-FIC`
- `1985.MARGSAGA.NAR-FIC`
- `1985.SAGAN.NAR-FIC`
- `2008.MAMMA.NAR-FIC`

**TEST:**
- `1150.FIRSTGRAMMAR.SCI-LIN`
- `1210.JARTEIN.REL-SAG`
- `1350.MARTA.REL-SAG`
- `1450.BANDAMENN.NAR-SAG`
- `1400.GUNNAR2.NAR-SAG`
- `1540.NTACTS.REL-BIB`
- `1628.OLAFUREGILS.BIO-TRA`
- `1745.KLIM.NAR-FIC`
- `1850.PILTUR.NAR-FIC`
- `1920.ARIN.REL-SER`

**DEV:**
- `1250.THETUBROT.NAR-SAG`
- `1350.BANDAMENNM.NAR-SAG`
- `1475.AEVINTYRI.NAR-REL`
- `1525.GEORGIUS.NAR-REL`
- `1630.GERHARD.REL-OTH`
- `1720.VIDALIN.REL-SER`
- `1888.GRIMUR.NAR-FIC`
- `1883.VOGGUR.NAR-FIC`
- `1902.FOSSAR.NAR-FIC`
- `2008.OFSI.NAR-SAG`


## Acknowledgments

This project is funded by The Strategic Research and Development Programme for Language Technology, grant no. 180020-5301. Thanks are due to Örvar Kárason, whose previous work was used as a basis for the conversion.

The Icelandic Parsed Historical Corpus (IcePaHC) is available at https://linguist.is/icelandic_treebank/Download.

Morphological features were generated using ABLTagger, a PoS tagger for Icelandic, developed by Steinþór Steingrímsson, Örvar Kárason and Hrafn Loftsson and available [here](https://github.com/steinst/ABLTagger).

## References

```
@inproceedings{arnardottir-etal-2020-universal,
title = "A {U}niversal {D}ependencies Conversion Pipeline for a {P}enn-format Constituency Treebank",
author = "Arnard{\'o}ttir, {\TH}{\'o}runn and
Hafsteinsson, Hinrik and
Sigur{\dh}sson, Einar Freyr and
Bjarnad{\'o}ttir, Krist{\'\i}n and
Ingason, Anton Karl and
J{\'o}nsd{\'o}ttir, Hildur and
Steingr{\'\i}msson, Stein{\th}{\'o}r",
booktitle = "Proceedings of the Fourth Workshop on Universal Dependencies (UDW 2020)",
month = dec,
year = "2020",
address = "Barcelona, Spain (Online)",
publisher = "Association for Computational Linguistics",
url = "https://www.aclweb.org/anthology/2020.udw-1.3",
pages = "16--25",
abstract = "The topic of this paper is a rule-based pipeline for converting constituency treebanks based on the Penn Treebank format to Universal Dependencies (UD). We describe an Icelandic constituency treebank, its annotation scheme and the UD scheme. The conversion is discussed, the methods used to deliver a fully automated UD corpus and complications involved. To show its applicability to corpora in different languages, we extend the pipeline and convert a Faroese constituency treebank to a UD corpus. The result is an open-source conversion tool, published under an Apache 2.0 license, applicable to a Penn-style treebank for conversion to a UD corpus, along with the two new UD corpora.",
}
```


# Statistics of UD Icelandic IcePaHC

## POS Tags

[ADJ](is_icepahc-pos-ADJ.html) – [ADP](is_icepahc-pos-ADP.html) – [ADV](is_icepahc-pos-ADV.html) – [AUX](is_icepahc-pos-AUX.html) – [CCONJ](is_icepahc-pos-CCONJ.html) – [DET](is_icepahc-pos-DET.html) – [INTJ](is_icepahc-pos-INTJ.html) – [NOUN](is_icepahc-pos-NOUN.html) – [NUM](is_icepahc-pos-NUM.html) – [PART](is_icepahc-pos-PART.html) – [PRON](is_icepahc-pos-PRON.html) – [PROPN](is_icepahc-pos-PROPN.html) – [PUNCT](is_icepahc-pos-PUNCT.html) – [SCONJ](is_icepahc-pos-SCONJ.html) – [VERB](is_icepahc-pos-VERB.html) – [X](is_icepahc-pos-X.html)

## Features

[Case](is_icepahc-feat-Case.html) – [Definite](is_icepahc-feat-Definite.html) – [Degree](is_icepahc-feat-Degree.html) – [Foreign](is_icepahc-feat-Foreign.html) – [Gender](is_icepahc-feat-Gender.html) – [Mood](is_icepahc-feat-Mood.html) – [Number](is_icepahc-feat-Number.html) – [NumType](is_icepahc-feat-NumType.html) – [Person](is_icepahc-feat-Person.html) – [PronType](is_icepahc-feat-PronType.html) – [Tense](is_icepahc-feat-Tense.html) – [VerbForm](is_icepahc-feat-VerbForm.html) – [Voice](is_icepahc-feat-Voice.html)

## Relations

[acl](is_icepahc-dep-acl.html) – [acl:relcl](is_icepahc-dep-acl-relcl.html) – [advcl](is_icepahc-dep-advcl.html) – [advmod](is_icepahc-dep-advmod.html) – [amod](is_icepahc-dep-amod.html) – [appos](is_icepahc-dep-appos.html) – [aux](is_icepahc-dep-aux.html) – [case](is_icepahc-dep-case.html) – [cc](is_icepahc-dep-cc.html) – [ccomp](is_icepahc-dep-ccomp.html) – [compound:prt](is_icepahc-dep-compound-prt.html) – [conj](is_icepahc-dep-conj.html) – [cop](is_icepahc-dep-cop.html) – [csubj](is_icepahc-dep-csubj.html) – [dep](is_icepahc-dep-dep.html) – [det](is_icepahc-dep-det.html) – [discourse](is_icepahc-dep-discourse.html) – [dislocated](is_icepahc-dep-dislocated.html) – [expl](is_icepahc-dep-expl.html) – [fixed](is_icepahc-dep-fixed.html) – [flat:foreign](is_icepahc-dep-flat-foreign.html) – [flat:name](is_icepahc-dep-flat-name.html) – [iobj](is_icepahc-dep-iobj.html) – [mark](is_icepahc-dep-mark.html) – [nmod](is_icepahc-dep-nmod.html) – [nmod:poss](is_icepahc-dep-nmod-poss.html) – [nsubj](is_icepahc-dep-nsubj.html) – [nummod](is_icepahc-dep-nummod.html) – [obj](is_icepahc-dep-obj.html) – [obl](is_icepahc-dep-obl.html) – [parataxis](is_icepahc-dep-parataxis.html) – [punct](is_icepahc-dep-punct.html) – [root](is_icepahc-dep-root.html) – [vocative](is_icepahc-dep-vocative.html) – [xcomp](is_icepahc-dep-xcomp.html)

<h2>Tokenization and Word Segmentation</h2>


<ul>
<li>This corpus contains 44029 sentences, 983678 tokens and 985057 syntactic words.</li>
</ul>

<ul>
<li>This corpus contains 109935 tokens (11%) that are not followed by a space.</li>
</ul>

<ul>
<li>This corpus does not contain words with spaces.</li>
</ul>

<ul>
<li>This corpus contains 592 types of words that contain both letters and punctuation. Examples: kap., kongl., W., Jóh., Mag., Matth., Efra-Fossi, Kór., Gull-Haraldur, N., Neðra-Fossi, hndr., mr., Skegg-Broddi, etc., Lúk., rd., Prov., Dr., Jer., m., st., Gen., Gull-Harald, Tím., Devt., Dönsku-húsum, Efes., Heb., III., Matt., Músa-Bölverkur, Pét., Tít., b., c., ix., rdr., Akt., D., Fiðlu-Hansa, Hörða-Knúts, II., Jesaj., Job., Kor., O-já, Róm., S., Sálm.</li>
</ul>

<ul>
<li>This corpus contains 1378 multi-word tokens. On average, one multi-word token consists of 2.00 syntactic words.</li>
<li>There are 243 types of multi-word tokens. Examples: skaltu, ertu, muntu, viltu, láttu, máttu, vertu, attú, veistu, áttu, sjáðu, heyrðu, farðu, þarftu, heldurðu, komdu, varstu, líttu, stattu, segðu, þeygi, gerðu, kanntu, geturðu, fórstu, hefurðu, gefðu, gættu, hafðu, manstu, sértu, sérðu, þars, þóttú, færðu, taktu, varastu, sendu, varaðu, Gakktu, Gjörðu, ferðu, fáðu, haltu, hugsaðu, hættu, koddu, minnstu, mundu, settu.</li>
</ul>

<h2>Morphology</h2>

<h3>Tags</h3>

<ul>
<li>This corpus uses 16 UPOS tags out of 17 possible: <a>ADJ</a>, <a>ADP</a>, <a>ADV</a>, <a>AUX</a>, <a>CCONJ</a>, <a>DET</a>, <a>INTJ</a>, <a>NOUN</a>, <a>NUM</a>, <a>PART</a>, <a>PRON</a>, <a>PROPN</a>, <a>PUNCT</a>, <a>SCONJ</a>, <a>VERB</a>, <a>X</a></li>
<li>This corpus does not use the following tags: SYM</li>
</ul>

<ul>
<li>This corpus contains 18 word types tagged as particles (PART): Einninn, Einungis, alleinasta, at, atð, að, aðeins, bara, ein, eina, einasta, einir, einkum, einmitt, einu, eitt, jafnvel, nema</li>
</ul>

<ul>
<li>This corpus contains 147 lemmas tagged as pronouns (PRON): _, allur, annar, annarr, annars, annarstaðar, annaðhvor, annaðhvort, annur, arkimagus, austfjörður, aðrur, báðir, eg, einar, einn, einnhver, eitthvað, ekkert, enginn, finnbogi, flestallur, grikki, hann, hans, henni, hinn, honum, hva-að, hvat, hvatki, hvað, hvaða, hver, hver-hver, hvergi, hverigu, hvern, hvert, hverur, hveða, hvor, hvorja, hvort, hvorttveggja, hvorugur, hví, hvílíkur, hvívetna, hvörri, hún, leyfi, lítill, maður, mer, mig, minn, minna, mit, miður, mér, món, neinn, nokkur, okkar, okkur, samur, sek, sig, sinn, sjá, sjálfaur, sjálfur, slíkur, sodan, sodda, soddan, soddann, soddur, sumur, svoddan, svoddann, sá, sér, sérhver, söðull, sýn, vera, vettugi, við, viðlíka, viðlíkur, vor, vora, vorra, vorrar, vorrur, vorur, vv, vá, vær, vér, ykkar, ykkra, ykkri, ykkrur, yðar, yðarri, yður, yðvar, yðvarn, álíka, ég, ér, ófeigur, öll, öllir, öðrumegin, ýmis, ýmiss, þ, þ., þann, þar, þat, þau, þaug, það, þeim, þeir, þeirra, þes, þess, þessi, þetta, þig, þinn, því, þvílíka, þvílíkur, þá, þær, þér, þín, þínn, þórólfur, þú</li>
</ul>

<ul>
<li>This corpus contains 245 lemmas tagged as determiners (DET): afarmikill, all, allfár, allir, alllítill, allmargur, allmikill, allnokkur, allralítill, allskonar, allskyns, allur, allur-allur, annarhvor, annaðhvor, annaðhvort, að, báðir, báðumegin, bæði, dráp, dálitill, dálítill, dálítið, ei, einar, einhver, einhverja, einhvernveginn, einhverskonar, einhversstaðar, einhvor, einhvörn, einhvörstaðar, einn, einn-einn, einnhver, einnhvern, einnri, eins, eirnri, eitt, eitthvað, eitthver, eitthverur, ekkert, ekki, en, engi, enginn, engur, enn, enni, fjölmargur, fleir, flestallur, flestir, flestur, fregn, fáeinir, fáeinn, fáir, fár, gera, gervallur, geysimikill, gjörvallur, hann, heldri, helgur, hin, hini, hinn, hinumeginn, hitt, hlutur, hotvetna, hvar, hvað, hvaða, hvaðvetna, hver, hveregur, hvergi, hverigra, hverigur, hverjur, hvernig, hverski, hverskonar, hverskyns, hversvetna, hvert, hveruga, hverur, hvetvetna, hvevetna, hvor, hvorgi, hvorigur, hvorki, hvorn, hvorngi, hvort, hvortki, hvorttveggi, hvorugur, hvorumeginn, hvurja, hvurur, hvílíkur, hvívetna, hvörja, hálf, hálfur, hár, hún, illur, ina, inn, inni, ins, inur, inventarium, jafnlítill, jafnmargur, jafnmikill, jafnmikið, jafnmikla, kvöld, langur, litlur, lítill, lítill-lítill, lítið, lítt, m, manngi, mannmarur, mara, marga, margt, margur, megn, meira, meiri, mestallur, mestur, mestöllur, meur, mikill, mikill-mikill, mikillur, mikinn, mikið, mikla, miklu, miklur, minna, minni, minnsti, mörgur, neinn, nekkver, nokkrur, nokkur, nokkura, nokkurntíma, nokkursstaðar, nokkurur, nokkuð, nátt, né, oflítill, ofmargur, ofmikill, ofurlitla, ofurlítill, sa, samlíkur, sanna, sinn, sitthver, sjá, skilmáli, slitinn, smár, snjámikill, stórmikill, suman, sumar, sumlegur, sumpart, sumur, svolítill, svolítið, sá, sér, sérhvað, sérhver, sérhvort, síst, síðri, síður, tal, um, varla, velflestur, velmargur, vettergi, vettugi, ást, ófár, ógnarmargur, óspart, ótalmargur, öllir, öllumegin, öngur, öngva, önnur, örfár, örlítill, örlítið, ýmis, ýmislegur, ýmiss, ýmsra, þann, þau, það, þeir, þenna, þennur, þerflegur, þess, þessa, þessháttar, þessi, þessi-þessi, þetta, því, þvílíkur, þá, þær</li>
</ul>

<ul>
<li>Out of the above, 50 lemmas occurred sometimes as PRON and sometimes as DET: allur, annaðhvor, annaðhvort, báðir, einar, einn, einnhver, eitthvað, ekkert, enginn, flestallur, hann, hinn, hvað, hvaða, hver, hvergi, hvert, hverur, hvor, hvort, hvorugur, hvílíkur, hvívetna, hún, lítill, minna, neinn, nokkur, sinn, sjá, sumur, sá, sér, sérhver, vettugi, öllir, ýmis, ýmiss, þann, þau, það, þeir, þess, þessi, þetta, því, þvílíkur, þá, þær</li>
</ul>

<ul>
<li>This corpus contains 11 lemmas tagged as auxiliaries (AUX): blífa, fá, geta, hafa, kunna, mega, munu, skulu, vera, verða, vilja</li>
</ul>

<ul>
<li>Out of the above, 11 lemmas occurred sometimes as AUX and sometimes as VERB: blífa, fá, geta, hafa, kunna, mega, munu, skulu, vera, verða, vilja</li>
</ul>

<ul>
<li>There are 4 <a href="../feat/VerbForm.html">(de)verbal forms:</a></li>
</ul>

<ul>
  <li>Fin
  <ul>
    <li>ADJ: verður, var, fær, nær, ríkir, sannast, átti, sanna, syndgir, varir</li>
    <li>ADP: á, fyr, nær, eptir, Meður, gegni, héreftir, næst, so, sér</li>
    <li>ADV: eigi, nær, heldur, snart, helst, fór, kann, aldri, braut, fyr</li>
    <li>AUX: var, er, hafði, voru, væri, eru, mun, hefði, sé, hefir</li>
    <li>CCONJ: eður, hverki, Hvörki, Né, efn, heldur</li>
    <li>DET: sá, engi, sjá, öngum, fá, eð, Nokkuru, inna, minna, Meir</li>
    <li>INTJ: Hei, Vei, duddu, Áví, Ó, Óhó</li>
    <li>NOUN: vilja, greinir, sakar, synda, syndir, engi, leið, hóf, mun, klæði</li>
    <li>NUM: Xii, fjörutigi, iiii, iiijr, vii</li>
    <li>PRON: voru, sér, vorum, eg, yðrum, vorar, yðrar, yðrir, órar, hvör</li>
    <li>PROPN: Vali, sankti, Valdi, Georgíus, Maii, Majst, guði, Beljus, Belíus, Brúni</li>
    <li>PUNCT: "</li>
    <li>SCONJ: er, eð, at, eru, hvörri, hvört</li>
    <li>VERB: sagði, segir, kom, mælti, fór, tók, varð, gekk, lét, hafði</li>
    <li>X: Majst, Edimus, Item, Sicut, beati, nostra, nostri, omnium, patri, sankti</li>
  </ul>
  </li>
</ul>

<ul>
  <li>Inf
  <ul>
    <li>ADJ: sanna, breiða, helga, fegra, fullkomna, margfalda, yðra, Verra, auðga, bera</li>
    <li>ADP: fyr, nema</li>
    <li>ADV: ske, framast, einast, fara, fá, skjótast, æfinlega, aldri, alloftast, fyrirkoma</li>
    <li>AUX: vera, hafa, verða, vilja, geta, mega, mundu, fá, hafast, hefi</li>
    <li>DET: sjá, engi, minna, sá, fá, meir, þenna, Margs, eð, ina</li>
    <li>NOUN: votta, synda, vilja, elska, ráða, búa, galdra, skaða, anda, herða</li>
    <li>PRON: yðra, sinna, Hina, hvörja, minna, óra, þeira</li>
    <li>PROPN: anda, Ótta, Antiokkia, Ermanus, Flegða, Loka, Mella, Pjatta, Syrpa, draga</li>
    <li>SCONJ: er</li>
    <li>VERB: fara, sjá, segja, taka, koma, láta, gera, ganga, halda, vita</li>
    <li>X: Ná, hyggja, libra, nostra, sigla, tertia</li>
  </ul>
  </li>
</ul>

<ul>
  <li>Part
  <ul>
    <li>ADJ: vænst, leitt, kunnigt, auðsýnt, skyldir, sýnt, auglýstur, beint, dælt, fallin</li>
    <li>ADP: útgefið</li>
    <li>ADV: háttað, minnst, predikað, einnin, gjör, hverninn, komnir, Einatt, beint, breitt</li>
    <li>AUX: haft, hafðir, hafður, verið, hafandi, höfð, skylduð, hafið, getið, hafðar</li>
    <li>CCONJ: annaðhvert, bæði, hvörki</li>
    <li>DET: minnst, engi, sjá, Ekkert, hitt, inir, nakkvað, nokkora, nökkvað</li>
    <li>NOUN: búandi, náð, orðið, gerð, liðið, talið, ráðið, sæmd, byggðir, fagnað</li>
    <li>NUM: sjö</li>
    <li>PRON: yðvart, eg, okkart, sér, vor, vorra</li>
    <li>PROPN: Refur, Fiður, Herjuð, Mundt, Móður</li>
    <li>SCONJ: hvört</li>
    <li>VERB: kominn, sagt, komið, orðinn, komnir, komin, kallaður, getið, gert, farið</li>
    <li>X: Majst, regent, regerandi</li>
  </ul>
  </li>
</ul>

<ul>
  <li>Sup
  <ul>
    <li>ADJ: áminnst, greint, hlýðið, hrært, kunnigt, kært, lagt, leitt, ljósan, mein</li>
    <li>ADP: fyr, þótt</li>
    <li>ADV: fengið, gerst, gjör, snarast, aldri, alltið, brutt, dárað, einnin, gengið</li>
    <li>AUX: verið, haft, getað, viljað, mátt, getið, munt, fengið, hafið, munuð</li>
    <li>DET: Sjá, hitt, engi, gerst, hvört, minnst, nakkvað, nökkut, slitið</li>
    <li>INTJ: Vei</li>
    <li>NOUN: náð, sótt, búið, brest, ráðið, talið, féið, varnað, klæði, mein</li>
    <li>PRON: hitt, hvör, yðart</li>
    <li>PROPN: Ríkilað, Majst</li>
    <li>PUNCT: "</li>
    <li>VERB: komið, séð, fengið, gert, sagt, farið, tekið, orðið, gjört, gefið</li>
  </ul>
  </li>
</ul>

<h3>Nominal Features</h3>


<ul>
  <li><a>Gender</a></li>
</ul>

<ul>
  <li>Fem
    <ul>
      <li>ADJ: sömu, fyrstu, góða, góð, hægri, góðar, vinstri, eigin, heilagri, heilagrar</li>
      <li>ADJ-Part: alklædd, brenndar, bölvuð, erfið, eygð, fallin, fegin, ferðbúnar, grafnar, haldin</li>
      <li>ADP: millum, sakir, eptir, fyr, handa, und, Kringum, ein, fraraan, héreftir</li>
      <li>ADV: þá, einnin, braut, hvörsu, einasta, mikla, fyrri, ein, þannin, Sannlega</li>
      <li>ADV-Part: einnin, festar, ofraðar, skorin, tíðkaðar</li>
      <li>AUX: skyldu, vera, vóru, megu, vilda, höfð, skylda, hefir, hafðar, skyldum</li>
      <li>AUX-Part: höfð, hafðar, meguð, hafða, máttuð</li>
      <li>CCONJ: eður, bæði, annaðhvurt, aða</li>
      <li>DET: sú, þessa, þessi, allar, þeirri, þá, alla, eina, þær, þessari</li>
      <li>INTJ: hana, bittinú, du, ææææææ</li>
      <li>NOUN: leið, hendur, dóttur, hendi, nótt, stund, von, höndum, kona, konu</li>
      <li>NOUN-Part: gerð, byggð, sæmd, festar, framkvæmdar, þegnar, Dagar, Dirfð, boðin, dáð</li>
      <li>NUM: tvær, þrjár, hvorirtveggju, sex, fimm, tveim, tólf, fjórar, sjö, tveggja</li>
      <li>PART: ein, eina</li>
      <li>PRON: hún, henni, hennar, hana, sér, sína, sinni, þær, mín, þeirra</li>
      <li>PRON-Part: vorra</li>
      <li>PROPN: Maríu, Gróa, Sigríður, María, Órækja, Jerúsalem, Gróu, Ragnhildur, bylgja, Sigríði</li>
      <li>PROPN-Part: Herjuð</li>
      <li>PUNCT: "</li>
      <li>SCONJ: hverja, hverjar, hver, hvorrar, hvaða, hvor, hvörju, hvörjum, hvörn</li>
      <li>VERB: komin, búin, orðin, leið, sett, kölluð, haldin, sagða, hætta, tekin</li>
      <li>VERB-Part: komin, orðin, kölluð, sett, haldin, tekin, farin, nefnd, gefin, komnar</li>
      <li>X: trinitatis, sankti, Exordium, Item, Jerúsalem, Martilla, Miraculum, Sicut, brevíaríum, sacramentum</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Masc
    <ul>
      <li>ADJ: góður, sama, gamall, sæla, dauður, góðan, sami, góðum, góðir, góða</li>
      <li>ADJ-Part: skyldir, auglýstur, genginn, mægður, ofsóttur, ráðinn, Lofaður, artaðir, auðmýktur, beinir</li>
      <li>ADP: fyr, millum, viður, eptir, ór, Milli, eftur, fyrirr, fyrur, fá</li>
      <li>ADV: þá, aldri, einn, hverninn, fyrri, allir, mikill, aptur, hvörninn, aldregi</li>
      <li>ADV-Part: gjör, hverninn, komnir, fyr, gerr, kominn, liðinn</li>
      <li>AUX: mun, vilja, var, skyli, muni, hafðir, hafður, mundi, vóru, munir</li>
      <li>AUX-Part: hafðir, hafður, mundu, hafinn, munduð, værir</li>
      <li>CCONJ: Eður, bæði, hvörki, hverki, Hvatki, báðir, hvegi, hvortki, nema</li>
      <li>CCONJ-Part: bæði</li>
      <li>DET: sá, einn, þann, allir, þeim, hinn, öllum, alla, þessum, þessi</li>
      <li>DET-Part: inir</li>
      <li>INTJ: damm, Heill, fjandi, maður, Óvei, óóóóó</li>
      <li>NOUN: menn, maður, konungur, manna, biskup, mönnum, dag, tíma, mann, stað</li>
      <li>NOUN-Part: byggðir, sóttir, gjörðir, heimtur, valinn, Kotungur, brunnar, felldir, fundinn, hlutir</li>
      <li>NUM: tveir, tvo, þrír, tólf, þrjá, fimm, sex, fjórir, sjö, tíu</li>
      <li>NUM-Part: sjö</li>
      <li>PART: Einninn, einasta, einir</li>
      <li>PRON: hann, þeir, honum, hans, sér, þeim, þeirra, sig, sínum, sinn</li>
      <li>PRON-Part: sér</li>
      <li>PROPN: guð, guðs, jesús, herra, guði, drottinn, jesú, Illugi, Jón, Finnbogi</li>
      <li>PROPN-Part: Refur, Fiður, Móður</li>
      <li>SCONJ: hvor, hver, hverjum, hvern, hverjir, hvorn, hvers, hvorum, er, hvatki</li>
      <li>VERB: kominn, orðinn, komnir, búinn, kallaður, segjandi, farinn, borinn, settur, sá</li>
      <li>VERB-Part: kominn, orðinn, komnir, kallaður, farinn, borinn, settur, tekinn, nefndur, sendur</li>
      <li>X: sankti, Ektor, Trankival, sanktus, Darii, Alexandrum, domini, Assyria, Vidfraktus, Alexandri</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Neut
    <ul>
      <li>ADJ: gott, sama, satt, betra, illt, góðu, nóg, sönnu, fyrsta, vísu</li>
      <li>ADJ-Part: vænst, leitt, kunnigt, auðsýnt, sýnt, beint, dælt, nýtt, stillt, Bezt</li>
      <li>ADP: millum, alls, fyr, fyri, ór, því, gagnvert, gögnum, kringis, það</li>
      <li>ADP-Part: útgefið</li>
      <li>ADV: hvað, mikið, langt, aldregi, því, hart, eitt, jafnsnart, allt, eina</li>
      <li>ADV-Part: háttað, minnst, predikað, Einatt, beint, breitt, flutt, greitt, hegat, hliðhalt</li>
      <li>AUX: em, haft, hafið, var, vilið, verið, myni, skylduð, vil, haf</li>
      <li>AUX-Part: haft, verið, skylduð, hafið, getið, höfð, munduð, Meguð, Skuluð, haf</li>
      <li>CCONJ: bæði, hvörki, hverki, annað, annaðhvert, g, hvatki, hvortki, hvörgi, ok</li>
      <li>CCONJ-Part: annaðhvert, hvörki</li>
      <li>DET: þetta, allt, það, þessu, því, öllu, eitt, mikið, ekkert, nokkuð</li>
      <li>DET-Part: minnst, engi, sjá, Ekkert, hitt, nakkvað, nokkora, nökkvað</li>
      <li>INTJ: fokk, bússí, Æ, óvei</li>
      <li>NOUN: orð, ráð, hjarta, landi, mál, ríki, skip, líf, nafni, orðum</li>
      <li>NOUN-Part: náð, orðið, liðið, talið, ráðið, fagnað, boðið, sótt, féið, gerð</li>
      <li>NUM: tvö, þrjú, sex, fimm, sjö, tólf, fjögur, hálft, hundrað, tíu</li>
      <li>PART: einu, eitt</li>
      <li>PRON: það, því, þess, hvað, þau, sitt, þeim, annað, sínu, þeirra</li>
      <li>PRON-Part: yðvart, eg, okkart, vor</li>
      <li>PROPN: Íslandi, Íslands, Skálholti, helvíti, alþingi, Barði, Kaupinhafn, helvítis, Englandi, Pálnatóki</li>
      <li>PROPN-Part: Mundt</li>
      <li>PUNCT: "</li>
      <li>SCONJ: það, hvert, hvort, hvört, hver, hverju, hvör, em, er, hvors</li>
      <li>SCONJ-Part: hvört</li>
      <li>VERB: sagt, komið, búið, orðið, getið, farið, gert, mælt, gjört, tekið</li>
      <li>VERB-Part: sagt, komið, getið, gert, farið, mælt, orðið, tekið, talað, gjört</li>
      <li>X: Trankival, domini, Majst, Vernakíus, kalendas, Holofernis, sanktus, Kapitulum, evangelium, nostri</li>
      <li>X-Part: Majst, regent</li>
    </ul>
  </li>
</ul>


<ul>
  <li><a>Number</a></li>
</ul>

<ul>
  <li>Plur
    <ul>
      <li>ADJ: góðum, góðir, góðar, góð, sömu, bestu, stór, góðra, heilagra, fyrstu</li>
      <li>ADJ-Fin: helga, syndgum, bera, blessuðu, göfgum, mæta, réttu, sanna, útvöldu, Nakið</li>
      <li>ADJ-Part: skyldir, artaðir, beinir, bilaðir, borin, brenndar, búin, drukknir, fallin, ferðbúnar</li>
      <li>ADP: við, millum, eptir, fyr, sakir, handa, gögnum, Kringum, eftir, héreftir</li>
      <li>ADP-Fin: yðrum</li>
      <li>ADV: þá, eigi, allir, fyrri, einnin, marga, margar, aldregi, fleiri, einir</li>
      <li>ADV-Fin: eigi, forðum, koma, fóru, hvörsu, skjótast, Hverru, berjast, enda, fengust</li>
      <li>ADV-Part: komnir, festar, flutt, fyr, ofraðar, tíðkaðar, þykkt</li>
      <li>AUX: voru, eru, hafa, höfðu, munu, skyldu, væru, vildu, skulum, mundu</li>
      <li>AUX-Fin: voru, eru, hafa, höfðu, munu, skyldu, væru, vildu, skulum, mundu</li>
      <li>AUX-Part: hafðir, skylduð, hafðar, höfð, munduð, mundu, Meguð, Skuluð, höfðuð, munuð</li>
      <li>CCONJ: bæði, hvörki, hverki, aða, báðir, hvörgi</li>
      <li>CCONJ-Fin: hverki</li>
      <li>CCONJ-Part: bæði</li>
      <li>DET: allir, öllum, þeim, alla, allra, öll, þau, margir, allar, þessi</li>
      <li>DET-Fin: engi, öngum, fá, inna, minna, sjá, Nokkuru, báðu, hvörjum, þenna</li>
      <li>DET-Part: inir, nokkora</li>
      <li>INTJ: du, Æ</li>
      <li>NOUN: menn, manna, mönnum, orð, bræður, orðum, hendur, hluti, höndum, daga</li>
      <li>NOUN-Fin: vilja, synda, komu, anda, klæðum, liðu, skyldu, sóttum, borðum, búa</li>
      <li>NOUN-Part: byggðir, sóttir, festar, framkvæmdar, gerð, gjörðir, rifin, sæmd, þegnar, Dagar</li>
      <li>NUM: tveir, tvo, tólf, fimm, sex, tvö, þrír, þrjá, sjö, tvær</li>
      <li>NUM-Fin: Xii, fjörutigi, iiii, vii</li>
      <li>PART: einir</li>
      <li>PRON: þeir, þeim, þeirra, vér, oss, þau, yður, þér, við, sínum</li>
      <li>PRON-Fin: voru, vorum, yðrum, eg, sinna, yðra, hvörjum, hvörra, hvorju, hvörja</li>
      <li>PRON-Part: sér, vor</li>
      <li>PROPN: gyðinga, gyðingar, Hólum, gyðingum, Hellismenn, grikkir, Georgíum, júðar, himnum, Bessastöðum</li>
      <li>PROPN-Fin: Guddu, Gálu, Senda, Snarinefja, Vamba, drottna</li>
      <li>PUNCT: "</li>
      <li>PUNCT-Fin: "</li>
      <li>SCONJ: hverjar, hverjir, hver, er, eru, hvaða, hverja, hvör, hvörjum</li>
      <li>SCONJ-Fin: eru</li>
      <li>VERB: komu, fóru, gengu, sögðu, tóku, urðu, koma, höfðu, komnir, sáu</li>
      <li>VERB-Fin: komu, fóru, gengu, sögðu, tóku, urðu, koma, höfðu, sáu, riðu</li>
      <li>VERB-Part: komnir, komin, kallaðir, settir, sendir, teknir, orðnir, farnir, sett, nefndir</li>
      <li>X: sankti, Georgíum, Kapitulum, Alexandrum, Miraculum, delictum, privilegium, sanctorum, Exordium, Taraskonum</li>
      <li>X-Fin: Item, nostra, omnium, statuta</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Sing
    <ul>
      <li>ADJ: sama, gott, satt, góða, góður, fyrsta, þriðja, heilaga, sæla, gamall</li>
      <li>ADJ-Fin: verður, var, fær, nær, ríkir, sannast, átti, syndgir, varir, fegri</li>
      <li>ADJ-Part: vænst, leitt, kunnigt, auðsýnt, sýnt, auglýstur, beint, dælt, genginn, mægður</li>
      <li>ADP: á, fyr, alls, viður, eptir, nær, ór, fyri, því, Meður</li>
      <li>ADP-Fin: á, fyr, nær, eptir, Meður, gegni, héreftir, næst, so, sér</li>
      <li>ADP-Part: útgefið</li>
      <li>ADV: eigi, hvað, aldri, þá, nær, einn, einnin, heldur, hverninn, einasta</li>
      <li>ADV-Fin: eigi, nær, heldur, snart, helst, fór, kann, aldri, braut, fyr</li>
      <li>ADV-Part: háttað, minnst, predikað, einnin, gjör, hverninn, Einatt, beint, breitt, gerr</li>
      <li>AUX: var, er, hafði, væri, mun, hefði, sé, hefir, hefur, skal</li>
      <li>AUX-Fin: var, er, hafði, væri, mun, hefði, sé, hefir, hefur, skal</li>
      <li>AUX-Part: haft, hafður, verið, höfð, hafið, getið, meguð, haf, hafinn, hafð</li>
      <li>CCONJ: eður, hvörki, hverki, bæði, annað, hvatki, hvortki, Né, annaðhvert, annaðhvurt</li>
      <li>CCONJ-Fin: eður, hverki, Hvörki, Né, efn, heldur</li>
      <li>CCONJ-Part: annaðhvert, hvörki</li>
      <li>DET: þetta, sá, allt, einn, það, þann, þessu, hinn, þessi, þessa</li>
      <li>DET-Fin: sá, engi, sjá, eð, Meir, Nokkuru, Sé, einkis, einnrar, engvan</li>
      <li>DET-Part: minnst, engi, sjá, Ekkert, hitt, nakkvað, nökkvað</li>
      <li>INTJ: bússí, fokk, hana, Hei, bittinú, damm, Óhó, óvei, Heill, Vei</li>
      <li>INTJ-Fin: Hei, Vei, duddu, Áví, Ó, Óhó</li>
      <li>NOUN: maður, konungur, biskup, dag, mann, stað, kóngur, tíma, herra, föður</li>
      <li>NOUN-Fin: greinir, sakar, syndir, leið, engi, hóf, mun, mætti, getur, friðar</li>
      <li>NOUN-Part: náð, orðið, liðið, talið, gerð, ráðið, fagnað, sótt, boðið, byggð</li>
      <li>NUM: hálft, hvorirtveggju, hvorttveggja, hálfan, hálfu, hundrað, hálfa, hvorutveggja, hálfs, iij</li>
      <li>NUM-Fin: iiijr</li>
      <li>NUM-Part: sjö</li>
      <li>PART: einu, Einninn, ein, eina, einasta, eitt</li>
      <li>PRON: hann, það, því, eg, ég, honum, hans, hún, þú, mér</li>
      <li>PRON-Fin: sér, eg, vorar, yðrar, yðrir, órar, hvör, hver, hvörja, hvörs</li>
      <li>PRON-Part: yðvart, eg, okkart, vorra</li>
      <li>PROPN: guð, guðs, jesús, herra, guði, drottinn, jesú, Illugi, Jón, Finnbogi</li>
      <li>PROPN-Fin: Vali, sankti, Valdi, Georgíus, Maii, Majst, guði, Beljus, Belíus, Brúni</li>
      <li>PROPN-Part: Refur, Fiður, Herjuð, Mundt, Móður</li>
      <li>PUNCT: "</li>
      <li>SCONJ: er, það, hvert, hvor, hvört, hvort, hver, eð, hverja, hverjum</li>
      <li>SCONJ-Fin: er, eð, at, hvörri, hvört</li>
      <li>SCONJ-Part: hvört</li>
      <li>VERB: sagði, segir, kom, mælti, fór, tók, varð, gekk, lét, hafði</li>
      <li>VERB-Fin: sagði, segir, kom, mælti, fór, tók, varð, gekk, lét, hafði</li>
      <li>VERB-Part: kominn, sagt, komið, orðinn, kallaður, komin, getið, gert, farið, mælt</li>
      <li>X: Trankival, domini, Majst, Ektor, sanktus, Vernakíus, sankti, Anno, Darii, trinitatis</li>
      <li>X-Fin: Majst, Edimus, Sicut, beati, nostri, patri, sankti</li>
      <li>X-Part: Majst, regent</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Case</a></li>
</ul>

<ul>
  <li>Acc
    <ul>
      <li>ADJ: sama, góða, gott, góðan, satt, sæla, þriðja, sömu, stóra, heilaga</li>
      <li>ADJ-Part: borin, bættan, endurleystan, fyrra, innifaldar, leifðan, léttan, nefnda, samlíkt, slétt</li>
      <li>ADP: fyr, sakir, eptir, ór, fyri, kringis, tíl, und, utanfyrir, þvert</li>
      <li>ADV: þá, fyrri, mikið, einasta, mikla, aldregi, hvað, mikinn, eina, marga</li>
      <li>ADV-Part: hverninn, létt</li>
      <li>AUX: skyldu, em, vilja, vóru, vera, vilda, mun, hafið, væra, hefir</li>
      <li>AUX-Part: mundu, hafða</li>
      <li>CCONJ: bæði, hvörki, hverki, annað, eður, hvortki, nema</li>
      <li>CCONJ-Part: hvörki</li>
      <li>DET: þetta, þann, alla, það, allt, þá, þessa, einn, eitt, allan</li>
      <li>DET-Part: engi</li>
      <li>INTJ: hana, damm, du, fokk, Æ, óvei</li>
      <li>NOUN: menn, dag, mann, orð, tíma, son, land, ráð, hendur, leið</li>
      <li>NOUN-Part: alin, fundinn, gerða, ráðið, vegana, vitið</li>
      <li>NUM: tvo, þrjá, tvö, þrjú, sex, tvær, fimm, tólf, fjóra, sjö</li>
      <li>PART: einasta, eitt</li>
      <li>PRON: það, hann, mig, sig, sína, sinn, hana, þig, sitt, þá</li>
      <li>PRON-Part: vorra</li>
      <li>PROPN: guð, jesúm, Þorlák, Illuga, Þorstein, drottin, herra, jesú, Jón, Finnboga</li>
      <li>PUNCT: "</li>
      <li>SCONJ: það, hverja, hvern, hvert, hvorn, em, hvaða, hverjar, hvört</li>
      <li>VERB: búið, veginn, orðið, sagða, lifandi, gjört, heitið, boðið, lagðan, lifanda</li>
      <li>VERB-Part: gert, sagða, gerða, birt, talað, getið, keypt, komna, ráðið, sendan</li>
      <li>X: trinitatis, Jesúm, Kristum, Anno, Bethaniam, Domini, Jerúsalem, sankti, Alexandríam, Apologiam</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Dat
    <ul>
      <li>ADJ: sama, góðum, góðu, sönnu, fyrstu, löngu, vísu, nýju, sömu, stórum</li>
      <li>ADP: millum, fyr, því, gögnum, ór, Kringum, eptir, fá, miðli, sinnum</li>
      <li>ADV: aldri, því, einum, hvörsu, miklu, aldregi, braut, stórum, einu, miklum</li>
      <li>AUX: mun, skyldu, vilja, vóru, vera, megu, muni, mætti, skyldum, vorum</li>
      <li>CCONJ: hvörki, hverki, hvatki, hvortki</li>
      <li>DET: þeim, öllum, þessu, þessum, því, öllu, þeirri, einu, einum, miklu</li>
      <li>NOUN: mönnum, landi, manni, nafni, orðum, hendi, sinni, máli, stað, konungi</li>
      <li>NUM: tveimur, tveim, fjórum, fimm, þremur, tólf, þrem, sex, hvorirtveggju, sjö</li>
      <li>PART: einu</li>
      <li>PRON: því, honum, mér, sér, þeim, þér, sínum, henni, oss, yður</li>
      <li>PROPN: guði, Íslandi, Noregi, Sturlu, jesú, kristi, Hólum, Jóni, Skálholti, Gissuri</li>
      <li>SCONJ: hverjum, hverju, hvorum, er, hvaða, hvörju, hvörjum, hvörn, hvörri</li>
      <li>VERB: sér, búnu, leið, liðnum, liðinni, mæltu, sóma, lifandi, göngum, liðnu</li>
      <li>X: sankti, domini, Alexandrum, Georgíum, Kapitulum, Anno, Miraculum, delictum, privilegium, sanctorum</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Gen
    <ul>
      <li>ADJ: heilagra, góðra, góðs, hægri, heilagrar, heilags, eilífs, ills, sæla, kristinna</li>
      <li>ADP: alls, fyr, handa, gagnvert, innar, jafnfram, sakir, Þá, ór</li>
      <li>ADV: eins, alls, forkunnar, samaleiðis, sæmiliga, aldregi, blíðliga, náliga, oftliga, ákafliga</li>
      <li>AUX: vóru, vera, skyldu, mátta, vilja, Má, hefir, mega, megu, munda</li>
      <li>CCONJ: eður, aða</li>
      <li>DET: allra, þess, þessa, hins, þeirra, alls, þeirrar, mikils, þessarar, margra</li>
      <li>NOUN: manna, konungs, biskups, kóngs, manns, föður, staðar, lífs, handa, guðs</li>
      <li>NUM: tveggja, þriggja, sex, tólf, fimm, níu, fimmtán, tíu, hundrað, sjö</li>
      <li>PRON: hans, þeirra, þess, hennar, síns, sín, sinna, yðar, mín, annars</li>
      <li>PROPN: guðs, drottins, jesú, Krists, herra, Jóns, Sturlu, Maríu, Þorláks, Íslands</li>
      <li>PUNCT: "</li>
      <li>SCONJ: hvers, hvorrar, hvors, hvör</li>
      <li>VERB: ganga, lifanda, ráða, launa, lifandi, gjörða, gerva, jarteina, leiða, liðna</li>
      <li>X: Holofernis, kalendas, Darii, Domini, Vernakíus, profundis, rupata, stadía, ANIMAE, Academísins</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Nom
    <ul>
      <li>ADJ: gott, góður, stór, gamall, góð, dauður, satt, sama, sami, góðir</li>
      <li>ADJ-Part: vænst, leitt, kunnigt, auðsýnt, skyldir, sýnt, auglýstur, beint, dælt, fallin</li>
      <li>ADP: við, fyr, viður, eptir, sakir, fyri, gagnvert, ór, það, Gagnvart</li>
      <li>ADP-Part: útgefið</li>
      <li>ADV: hvað, einnin, einn, allir, mikill, fyrri, hverninn, langt, aldregi, aptur</li>
      <li>ADV-Part: háttað, minnst, predikað, einnin, gjör, komnir, Einatt, beint, breitt, festar</li>
      <li>AUX: em, var, skyli, vera, haft, hafðir, hafður, mundi, verið, vilið</li>
      <li>AUX-Part: haft, hafðir, hafður, verið, höfð, skylduð, hafið, getið, hafðar, munduð</li>
      <li>CCONJ: bæði, eður, hvörki, hverki, annað, Hvatki, annaðhvert, annaðhvurt, báðir, g</li>
      <li>CCONJ-Part: annaðhvert, bæði</li>
      <li>DET: sá, þetta, allt, allir, þessi, einn, það, hinn, sú, enginn</li>
      <li>DET-Part: minnst, sjá, Ekkert, engi, hitt, inir, nakkvað, nokkora, nökkvað</li>
      <li>INTJ: bússí, bittinú, fokk, Heill, fjandi, maður, Æ, Óhó, Óvei, ææææææ</li>
      <li>NOUN: menn, maður, konungur, biskup, kóngur, faðir, herra, prestur, bræður, jarl</li>
      <li>NOUN-Part: náð, orðið, gerð, liðið, talið, sæmd, byggðir, fagnað, ráðið, sótt</li>
      <li>NUM: tveir, þrír, tólf, fjórir, tvö, fimm, tvær, sex, þrjár, þrjú</li>
      <li>NUM-Part: sjö</li>
      <li>PART: Einninn, ein, eina, einir</li>
      <li>PRON: hann, þeir, það, ég, eg, hún, þú, vér, hvað, þér</li>
      <li>PRON-Part: yðvart, eg, okkart, sér, vor</li>
      <li>PROPN: guð, jesús, drottinn, Illugi, herra, Finnbogi, Sturla, Grettir, Jón, Oddur</li>
      <li>PROPN-Part: Refur, Fiður, Herjuð, Mundt, Móður</li>
      <li>PUNCT: "</li>
      <li>SCONJ: það, hvor, hvert, hver, hvort, hvört, hverjar, hverjir, er, hvatki</li>
      <li>SCONJ-Part: hvört</li>
      <li>VERB: kominn, sagt, komið, orðinn, komnir, búinn, komin, kallaður, búið, orðið</li>
      <li>VERB-Part: kominn, sagt, komið, orðinn, komnir, komin, kallaður, getið, farið, gert</li>
      <li>X: Trankival, Ektor, sanktus, domini, sankti, Vernakíus, Majst, Darii, Dominus, Item</li>
      <li>X-Part: Majst, regent</li>
    </ul>
  </li>
</ul>


<ul>
  <li><a>Definite</a></li>
</ul>

<ul>
  <li>Def
    <ul>
      <li>ADJ: fyrsta, fyrstu, þriðja, næsta, betra, heilaga, sæla, góða, fyrri, gamla</li>
      <li>ADP: fraraan, fyr, fá</li>
      <li>ADV: fyrri, einnin, hverninn, einasta, eina, hvörnin, hvörninn, þannin, þanninn, næsta</li>
      <li>AUX: vilið, hafið, vóru, vilda, verðið, væra, megu, myni, mynið, séið</li>
      <li>CCONJ: hvörki, eður, hvortki</li>
      <li>DET: meira, meiri, fleiri, mesta, fleira, mikla, mesti, mestu, minna, eina</li>
      <li>NOUN: daginn, fólkið, keisarinn, veturinn, maðurinn, nóttina, borginni, málið, höfuðið, landið</li>
      <li>NUM: hvorntveggja, hálfa, hvortveggi, þrjátigi, 1., 11., 4., 8., 9., Hvortveggja</li>
      <li>PART: Einninn, eina, einasta</li>
      <li>PRON: minni, soddan, minna, þeirra, vorar, Sjálfan, min, okkarn, soddann, svoddan</li>
      <li>PROPN: drottins, Austvestan, sankti, Kýlan, gyðinganna, Norðsunnan, herrans, Kýlans, jólin, Jarlmann</li>
      <li>PUNCT: "</li>
      <li>VERB: orðið, veginn, heitið, liðið, boðið, kunni, orðin, svarið, blessaða, heita</li>
      <li>X: sankti, Academísins, Belina, Dominum, Lazari, Magdalum, Roddanum, Tígrin, Verluc, crimina</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ind
    <ul>
      <li>ADJ: gott, satt, góður, stór, góð, góðum, gamall, góða, dauður, góðan</li>
      <li>ADP: millum, fyr, eptir, viður, sakir, ór, fyri, gagnvert, handa, gögnum</li>
      <li>ADV: aldri, aldregi, mikið, langt, mikill, einn, braut, hart, jafnsnart, hvörsu</li>
      <li>AUX: mun, em, skyldu, vera, vóru, var, vilja, skyli, muni, vil</li>
      <li>CCONJ: hvörki, eður, hverki, hvatki, annaðhvurt, aða, g, hvegi, hvortki, hvörgi</li>
      <li>DET: mikið, mikill, margir, miklu, margt, mikil, mörgum, mikinn, marga, einn</li>
      <li>INTJ: bússí, fokk, bittinú, damm, Æ, óvei, Heill, fjandi, maður, Óhó</li>
      <li>NOUN: menn, maður, konungur, manna, biskup, mönnum, orð, dag, tíma, mann</li>
      <li>NUM: hálft, hvorirtveggju, hálfan, hálfum, ij, hálfu, iij, hálfa, hálfs, hálfur</li>
      <li>PART: einu, einir</li>
      <li>PRON: hönum, vor, hvör, sinni, mitt, vorum, soddan, vær, annað, þeira</li>
      <li>PROPN: guð, guðs, jesús, herra, guði, drottinn, jesú, Illugi, Jón, Finnbogi</li>
      <li>SCONJ: hvört, hvör, em, er, hvatki, hvörju, hvörjum, hvörn, hvörri, ið</li>
      <li>VERB: búið, búinn, segjandi, búin, búnir, höggur, fallinn, ganga, leið, kömur</li>
      <li>X: Trankival, domini, Ektor, sanktus, Vernakíus, Anno, Darii, trinitatis, Alexandrum, Georgíum</li>
    </ul>
  </li>
</ul>

<h3>Degree and Polarity</h3>


<ul>
  <li><a>Degree</a></li>
</ul>

<ul>
  <li>Cmp
    <ul>
      <li>ADJ: nær, betra, fyrri, betri, fyrra, eldri, stærri, lengra, yngri, æðri</li>
      <li>ADP: nær, fyrr, ór</li>
      <li>ADV: heldur, fyrr, síðar, betur, nær, framar, lengur, oftar, síður, fremur</li>
      <li>AUX: myni</li>
      <li>CCONJ: hvortki, hvörki</li>
      <li>DET: meir, meira, meiri, fleiri, fleira, minna, síður, minni, fleirum, innar</li>
      <li>NOUN: minni, síður, sakir, forvitri, allstaðar, bráðar, byggingarkúnstarinnar, engi, reiðara, réttara</li>
      <li>NUM: vi, xii, átján</li>
      <li>PRON: minni, minna, soddan, hvörra, sinna, yðvarra, þínni</li>
      <li>PROPN: saltara, GANGI, Hlymreksfari, Jaíri, Konáli, Mörukári, Teófíli, farisearanna, himnna, kristi</li>
      <li>VERB: heldur, endaðri, ver, betri, fremur, fá, nær, víprar, Kunni, Lýsi</li>
      <li>X: sankti, Lazari, seminarii</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Pos
    <ul>
      <li>ADJ: gott, satt, góða, góður, stór, góð, góðum, heilaga, þriðja, góðu</li>
      <li>ADP: fyr, eptir, Gagnvart, Kringum, eftur, ein, fá, innar, tilbeðin, ór</li>
      <li>ADV: mikið, einasta, langt, mikill, eina, einn, hart, eins, mikla, víst</li>
      <li>AUX: var, vilda, vóru, væra, vert, fær, hafða, fekk, megu, mætta</li>
      <li>CCONJ: Eður, hvörki</li>
      <li>DET: mikið, mikill, margir, miklu, margt, mikil, mikla, mörgum, mikinn, marga</li>
      <li>INTJ: Heill, ææææææ</li>
      <li>NOUN: dauða, heit, góða, búið, vísu, skyld, föstum, gott, synda, trúu</li>
      <li>NUM: hálft, hálfan, hálfum, hálfa, hálfs, hálfu, hálfur, hvorntveggja, ij, tvennum</li>
      <li>PART: einu, eina, einasta, einir</li>
      <li>PRON: soddan, mitt, vær, annað, svoddan, þvílíkan, yðvart, yðrum, vor, yðart</li>
      <li>PROPN: sankti, heilags, heilagur, Rauður, Ótta, Arkistratus, heilaga, helga, Konáll, Darius</li>
      <li>PUNCT: "</li>
      <li>SCONJ: hvört, er</li>
      <li>VERB: búið, búinn, lifandi, búin, búnir, fallinn, lifanda, þegjandi, búnu, grátandi</li>
      <li>X: sankti, Vidfraktus, Item, Alexandrum, sanktus, Aristandus, Sicut, Stadium, Vagau, Valbert</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Sup
    <ul>
      <li>ADJ: fyrsta, fyrstu, næsta, besta, bestu, best, næst, næstu, fyrstur, síðustu</li>
      <li>ADP: fyrst, næst</li>
      <li>ADV: fyrst, næst, helst, best, mest, oftast, síðast, fremst, síst, lengst</li>
      <li>AUX: vart, vildir, vorum</li>
      <li>DET: mest, mesta, flestir, mestu, mesti, flestum, mestur, minnsta, flest, minnst</li>
      <li>NOUN: tigu, Arkistratus, Mannanna, dýra, fyrstu, föstu, gæfastur, hjartans, háttu, kunnustu</li>
      <li>NUM: 1., þrjátigi</li>
      <li>PRON: oss, minna, slíkut, vora, þeirra, þvílík</li>
      <li>PROPN: Tósti, Austvestan, Georgíum, Imbrudaga, Mannsins</li>
      <li>VERB: helst, fanst, verst, Þóttust, minnst, réttast, sannast, Rifjaðist, fyrfarast, gleðist</li>
      <li>X: Majst, mest</li>
    </ul>
  </li>
</ul>



<h3>Verbal Features</h3>



<ul>
  <li><a>Mood</a></li>
</ul>

<ul>
  <li>Imp
    <ul>
      <li>ADJ-Fin: Heill, Hásu, Nakið, Skamt, Skjót, löstu, mildi, ofgóð, upprisu</li>
      <li>ADP-Fin: fyr</li>
      <li>ADV-Fin: hvörsu, hvört, takið</li>
      <li>AUX-Fin: hafið, mundu, megið, munuð, Skulu, verið, Vóru, megu, Höfu, Munt</li>
      <li>DET-Fin: sjá, engi, Nokkuru, engvan, fæstu, nökkut</li>
      <li>INTJ-Fin: duddu</li>
      <li>NOUN-Fin: hurðu, Furðu, Grið, Stundu, Sverð, Sverðið, dirfzku, eig, far, gæðsku</li>
      <li>PRON-Fin: hvörju, hvörs, yðru, þaug, þínun</li>
      <li>PROPN-Fin: Yxu</li>
      <li>PUNCT-Fin: "</li>
      <li>SCONJ-Fin: at</li>
      <li>VERB-Fin: lát, seg, gef, sjáið, sjá, komið, látið, takið, gerðu, settu</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ind
    <ul>
      <li>ADJ-Fin: verður, var, fær, nær, ríkir, sannast, átti, sanna, syndgir, varir</li>
      <li>ADP-Fin: á, fyr, nær, eptir, Meður, héreftir, næst, so, sér, yðrum</li>
      <li>ADV-Fin: nær, heldur, snart, helst, fór, eigi, kann, braut, fyr, mátti</li>
      <li>AUX-Fin: var, er, hafði, voru, eru, mun, hefir, hefur, skal, hafa</li>
      <li>CCONJ-Fin: eður, hverki, Né, efn, heldur</li>
      <li>DET-Fin: sá, engi, fá, öngum, eð, inna, minna, sjá, Meir, Nokkuru</li>
      <li>INTJ-Fin: Hei, Vei, Áví, Ó, Óhó</li>
      <li>NOUN-Fin: vilja, greinir, sakar, synda, syndir, leið, hóf, mun, engi, getur</li>
      <li>NUM-Fin: iiijr</li>
      <li>PRON-Fin: voru, sér, vorum, eg, vorar, yðrar, yðrum, yðrir, órar, hvör</li>
      <li>PROPN-Fin: Georgíus, Majst, Beljus, Belíus, Brúni, Guði, Gálu, Hrímgerður, Karatti, Kórmaks</li>
      <li>SCONJ-Fin: er, eð, eru, hvörri, hvört</li>
      <li>VERB-Fin: sagði, segir, kom, mælti, fór, tók, varð, gekk, lét, hafði</li>
      <li>X-Fin: Majst, Edimus, Item, Sicut, nostra, omnium, statuta</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Sub
    <ul>
      <li>ADJ-Fin: fegri, svarti, verðir, frómi, glaði, sæti, Elsti, fáum, hæsti, lítilsvirði</li>
      <li>ADP-Fin: gegni, uni</li>
      <li>ADV-Fin: eigi, aldri, Forðum, kynni, byrji, ei, fyndust, geysi, liggi, liði</li>
      <li>AUX-Fin: væri, hefði, sé, skyldi, mundi, hafi, mætti, væru, skyldu, vildi</li>
      <li>CCONJ-Fin: Hvörki</li>
      <li>DET-Fin: engi, Sé, einkis, meiri, öngum</li>
      <li>NOUN-Fin: færi, kosti, liði, mætti, verði, vilji, viti, hafi, mildi, skyldu</li>
      <li>NUM-Fin: Xii, fjörutigi, iiii, vii</li>
      <li>PRON-Fin: sé, hver, hvörjum, leifi, sinni, yðrum</li>
      <li>PROPN-Fin: Vali, Valdi, sankti, Maii, Guddu, Julii, Martii, Stefni, bausti, dragi</li>
      <li>VERB-Fin: ætti, kæmi, yrði, færi, verði, komi, þyki, þætti, fengi, þyrfti</li>
      <li>X-Fin: beati, nostri, patri, sankti</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Tense</a></li>
</ul>

<ul>
  <li>Past
    <ul>
      <li>ADJ-Fin: var, átti, sétti, blessuðu, laust, réttu, sæti, volaði, útvöldu, Elsti</li>
      <li>ADP-Fin: fyr</li>
      <li>ADV-Fin: snart, fór, braut, mátti, eigi, kunni, fóru, hvörsu, kynni, vildi</li>
      <li>AUX-Fin: var, hafði, voru, væri, hefði, skyldi, vildi, mundi, höfðu, mátti</li>
      <li>DET-Fin: sá, engi, Nokkuru, báðu, meiri</li>
      <li>NOUN-Fin: leið, engi, hóf, mætti, komu, færi, lifnaði, liði, skildi, birti</li>
      <li>PRON-Fin: voru, vorum, hver, vér, hvör, sér, hvorju, hvörja, hvörjum, hvörri</li>
      <li>PROPN-Fin: Brúni, Guddu, Guði, Gálu, Hrímgerður, Karatti, Pjatti, Skafti, Trankival, Vali</li>
      <li>SCONJ-Fin: hvörri, hvört</li>
      <li>VERB-Fin: sagði, kom, mælti, fór, tók, varð, gekk, lét, hafði, hét</li>
      <li>X-Fin: Edimus, Sicut, beati</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Pres
    <ul>
      <li>ADJ-Fin: verður, fær, nær, ríkir, sannast, sanna, syndgir, varir, fegri, göfgir</li>
      <li>ADP-Fin: á, fyr, nær, eptir, Meður, gegni, héreftir, næst, so, sér</li>
      <li>ADV-Fin: eigi, nær, heldur, helst, kann, aldri, fyr, næst, fer, kemur</li>
      <li>AUX-Fin: er, eru, mun, sé, hefir, hefur, skal, hafa, hafi, má</li>
      <li>CCONJ-Fin: eður, hverki, Hvörki, Né, efn, heldur</li>
      <li>DET-Fin: engi, sjá, öngum, fá, eð, inna, minna, Meir, Nokkuru, Sé</li>
      <li>INTJ-Fin: Hei, Vei, duddu, Áví, Ó, Óhó</li>
      <li>NOUN-Fin: vilja, greinir, sakar, synda, syndir, mun, klæði, getur, friðar, hjálpar</li>
      <li>NUM-Fin: Xii, fjörutigi, iiii, iiijr, vii</li>
      <li>PRON-Fin: sér, eg, yðrum, vorar, yðrar, yðrir, órar, sinna, yðra, hvörja</li>
      <li>PROPN-Fin: Vali, Valdi, sankti, Georgíus, Maii, Majst, Beljus, Belíus, Julii, Kórmaks</li>
      <li>PUNCT-Fin: "</li>
      <li>SCONJ-Fin: er, eð, at, eru</li>
      <li>VERB-Fin: segir, kemur, fer, verður, svarar, veit, heitir, gengur, þykir, tekur</li>
      <li>X-Fin: Majst, Item, nostra, nostri, omnium, patri, sankti, statuta</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Voice</a></li>
</ul>

<ul>
  <li>Act
    <ul>
      <li>ADJ-Fin: verður, var, fær, nær, ríkir, átti, sanna, syndgir, varir, fegri</li>
      <li>ADJ-Inf: sanna, breiða, helga, fegra, fullkomna, margfalda, yðra, Verra, auðga, bera</li>
      <li>ADJ-Part: leitt, kunnigt, auðsýnt, skyldir, sýnt, auglýstur, beint, dælt, fallin, genginn</li>
      <li>ADJ-Sup: greint, hlýðið, hrært, kunnigt, kært, lagt, leitt, ljósan, mein, mætt</li>
      <li>ADP-Fin: á, fyr, nær, eptir, Meður, gegni, héreftir, so, sér, uni</li>
      <li>ADP-Inf: fyr, nema</li>
      <li>ADP-Part: útgefið</li>
      <li>ADP-Sup: fyr, þótt</li>
      <li>ADV-Fin: eigi, nær, heldur, snart, fór, kann, aldri, braut, fyr, mátti</li>
      <li>ADV-Inf: ske, fara, fá, æfinlega, aldri, fyrirkoma, gefa, gjör, jafna, líka</li>
      <li>ADV-Part: háttað, predikað, einnin, gjör, hverninn, komnir, Einatt, beint, breitt, festar</li>
      <li>ADV-Sup: fengið, gjör, aldri, alltið, brutt, dárað, einnin, gengið, gerr, greitt</li>
      <li>AUX-Fin: var, er, hafði, voru, væri, eru, mun, hefði, sé, hefir</li>
      <li>AUX-Inf: vera, hafa, verða, vilja, geta, mega, mundu, fá, hefi, má</li>
      <li>AUX-Part: haft, hafðir, hafður, verið, hafandi, höfð, skylduð, hafið, getið, hafðar</li>
      <li>AUX-Sup: verið, haft, getað, viljað, mátt, getið, munt, fengið, hafið, munuð</li>
      <li>CCONJ-Fin: eður, hverki, Hvörki, Né, efn, heldur</li>
      <li>CCONJ-Part: annaðhvert, bæði, hvörki</li>
      <li>DET-Fin: sá, engi, sjá, öngum, fá, eð, Nokkuru, inna, minna, Meir</li>
      <li>DET-Inf: sjá, engi, minna, sá, fá, þenna, Margs, eð, ina, inna</li>
      <li>DET-Part: engi, sjá, Ekkert, hitt, inir, nakkvað, nokkora, nökkvað</li>
      <li>DET-Sup: Sjá, hitt, engi, hvört, nakkvað, nökkut, slitið</li>
      <li>INTJ-Fin: Hei, Vei, duddu, Áví, Ó, Óhó</li>
      <li>INTJ-Sup: Vei</li>
      <li>NOUN-Fin: vilja, greinir, sakar, synda, syndir, engi, leið, hóf, mun, klæði</li>
      <li>NOUN-Inf: votta, synda, vilja, elska, ráða, búa, galdra, skaða, anda, herða</li>
      <li>NOUN-Part: búandi, náð, orðið, gerð, liðið, talið, ráðið, sæmd, byggðir, fagnað</li>
      <li>NOUN-Sup: náð, sótt, búið, brest, ráðið, talið, féið, varnað, klæði, mein</li>
      <li>NUM-Fin: Xii, fjörutigi, iiii, iiijr, vii</li>
      <li>NUM-Part: sjö</li>
      <li>PRON-Fin: voru, sér, vorum, eg, yðrum, vorar, yðrar, yðrir, órar, hvör</li>
      <li>PRON-Inf: yðra, sinna, Hina, hvörja, minna, óra, þeira</li>
      <li>PRON-Part: yðvart, eg, okkart, sér, vor, vorra</li>
      <li>PRON-Sup: hitt, hvör, yðart</li>
      <li>PROPN-Fin: Vali, sankti, Valdi, Georgíus, Maii, guði, Beljus, Belíus, Brúni, Guddu</li>
      <li>PROPN-Inf: anda, Ótta, Antiokkia, Ermanus, Flegða, Loka, Mella, Pjatta, Syrpa, draga</li>
      <li>PROPN-Part: Refur, Fiður, Herjuð, Mundt, Móður</li>
      <li>PROPN-Sup: Ríkilað, Majst</li>
      <li>PUNCT-Fin: "</li>
      <li>SCONJ-Fin: er, eð, at, eru, hvörri, hvört</li>
      <li>SCONJ-Inf: er</li>
      <li>SCONJ-Part: hvört</li>
      <li>VERB-Fin: sagði, segir, kom, mælti, fór, tók, varð, gekk, lét, hafði</li>
      <li>VERB-Inf: fara, sjá, segja, taka, koma, láta, gera, ganga, halda, vita</li>
      <li>VERB-Part: kominn, sagt, komið, orðinn, komnir, komin, kallaður, getið, gert, farið</li>
      <li>VERB-Sup: komið, séð, fengið, gert, sagt, farið, tekið, orðið, gjört, gefið</li>
      <li>X-Fin: Edimus, Item, Sicut, beati, nostra, nostri, omnium, patri, sankti, statuta</li>
      <li>X-Inf: Ná, hyggja, libra, nostra, sigla, tertia</li>
      <li>X-Part: regent, regerandi</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Mid
    <ul>
      <li>ADJ-Fin: sannast, hentust, hreinsast, hreinst, nægst, snarast, þéttust</li>
      <li>ADJ-Inf: leiðast, líkur, sannast, snjallast</li>
      <li>ADJ-Part: vænst, Bezt, auðvíst, beinst, byrst, frægst, hægst, ragast, sýnst, þynnst</li>
      <li>ADJ-Sup: áminnst, skírst, vænst</li>
      <li>ADP-Fin: næst</li>
      <li>ADV-Fin: helst, næst, einast, skjótast, Geyst, Sicut, barðist, berjast, fengust, ferðast</li>
      <li>ADV-Inf: framast, einast, skjótast, alloftast, gerr, helst, skírast, snarast, takast, vandast</li>
      <li>ADV-Part: minnst</li>
      <li>ADV-Sup: gerst, snarast, kynst, minnst, nærst, þankalaust</li>
      <li>AUX-Fin: hafast, hafðist, munuð, sért, ert, fengust, hafist, hefðust, höfðust, mundi</li>
      <li>AUX-Inf: hafast, hafst</li>
      <li>DET-Fin: fæstu</li>
      <li>DET-Inf: meir</li>
      <li>DET-Part: minnst</li>
      <li>DET-Sup: gerst, minnst</li>
      <li>NOUN-Fin: prófast, bast, brest, drustdrust, veizlan</li>
      <li>NOUN-Inf: prófast, finnast, glest, snjókast</li>
      <li>PRON-Fin: eg, yðart</li>
      <li>PROPN-Fin: Majst</li>
      <li>PUNCT-Sup: "</li>
      <li>VERB-Fin: þóttist, kvaðst, fannst, kveðst, sýndist, komst, settist, gerðist, sagðist, sýnist</li>
      <li>VERB-Inf: komast, berjast, finnast, búast, setjast, takast, eignast, gefast, minnast, gerast</li>
      <li>VERB-Part: komist, minnst, búist, sestur, barist, eignast, áminnst, Barðist, aðhafst, búizt</li>
      <li>VERB-Sup: komist, tekist, gerst, fundist, öðlast, barist, búist, reynst, eignast, birst</li>
      <li>X-Fin: Majst</li>
      <li>X-Part: Majst</li>
    </ul>
  </li>
</ul>


<h3>Pronouns, Determiners, Quantifiers</h3>


<ul>
  <li><a>PronType</a></li>
</ul>

<ul>
  <li>Dem
    <ul>
      <li>ADJ: sama, sömu, sami, samri, sams, hvílíkur, samur, glöggvasta, hvílík, samt</li>
      <li>ADP: fyr, Þá, það</li>
      <li>ADV: þá, hvílík, sama, sjálfum, glöggvasta, hvorsu, hvílíka, sjálfa, öðruvís, því</li>
      <li>AUX: var, vóru</li>
      <li>DET: þetta, sá, þessi, þann, þessu, það, þessa, þeim, þessum, þá</li>
      <li>NOUN: sá, þetta, okurið, sjálfa, sjálfan, strendli, Þessir, þessi, þá</li>
      <li>NUM: þess</li>
      <li>PRON: sjálfur, það, þeim, þeir, sjálfum, slíkt, því, þeirra, sjálfan, þá</li>
      <li>PROPN: Þetta, Sjálfur, Sá, Sú, Þeir</li>
      <li>SCONJ: það, hverjar, hvílíkt</li>
      <li>VERB: sá, hét, sama, minni, Lét, bera, biðjum, hitt, kynni, sami</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ind
    <ul>
      <li>ADJ: annar, annan, annað, annars, einn, eins, öðru, vorri, aðra, sama</li>
      <li>ADP: alls, fyr, eptir, ór</li>
      <li>ADV: allir, allt, nokkuð, einn, hver, öll, alls, báðir, enginn, hvert</li>
      <li>AUX: mundi, vóru, Myndi</li>
      <li>CCONJ: bæði, annað, báðir, hverki</li>
      <li>DET: allt, allir, öllum, alla, öllu, ekkert, öll, allra, enginn, nokkuð</li>
      <li>NOUN: sumar, hver, vor, öllum, Engum, annan, einhverju, ekkert, engi, foldu</li>
      <li>NUM: hvorttveggja, hvorutveggja, hvorstveggja, Hvort, ein, eina, hver, nokkurt</li>
      <li>PART: ein</li>
      <li>PRON: annað, öðrum, annan, aðrir, annar, öðru, aðra, annars, önnur, hver</li>
      <li>PROPN: Enginn, Aðra, Aðrir, Bítlana, Hellismenn, Petrum, Reyðarmúla, Sumar</li>
      <li>SCONJ: hvor, hvert, hverja, hvort, hver, hverjum, hvern, hvorn, hvers, hvorrar</li>
      <li>VERB: vorar, báðum, ann, entri, forþént, hét, inntakast, kenndust, krafður, reifður</li>
      <li>X: Dominus, Tírus, regnum, sankti</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Int
    <ul>
      <li>ADJ: hver</li>
      <li>ADV: hvað, hvert, hvers</li>
      <li>AUX: vildi</li>
      <li>DET: hver, hvaða, hvað, hverju, hverjir, hvers, hvern, hverjar, hverja, hvert</li>
      <li>NOUN: hver, hold</li>
      <li>NUM: hvorutveggja, xij</li>
      <li>PRON: hvað, hver, hverju, hvers, hverjir, hverra, hvern, hverja, hverjar, vorar</li>
      <li>SCONJ: hver, hverjar, hverjir, hvert, hvaða, hverju, hvort</li>
      <li>VERB: hvað, vorar</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Prs
    <ul>
      <li>ADJ: mitt, H., Tóm, almáttkan, elskuligan, kunnigt, minna, sitt, sæt, sér</li>
      <li>ADP: við, fyr, því, eftir, Það</li>
      <li>ADV: þá, því, sér, mitt, það, þeir, þú, hann, þess, fyr</li>
      <li>AUX: sér, vorum, meguð, var</li>
      <li>DET: það, þeim, því, þeir, þess, þau, þeirra, þá, þær, minna</li>
      <li>INTJ: hana</li>
      <li>NOUN: sinn, sinni, Þú, ég, hann, mér, sér, eg, vorra, hún</li>
      <li>NUM: hvorttveggja, þeir, þess</li>
      <li>PRON: hann, það, þeir, því, ég, eg, honum, hans, hún, þú</li>
      <li>PROPN: Hann, Eg, Þú, Ég, Hans, Þér, Vér, Hún, Helga, Mér</li>
      <li>PUNCT: "</li>
      <li>SCONJ: það</li>
      <li>VERB: sér, minna, vora, ann, bannaða, brennanda, dansandi, fanst, fyltist, gerði</li>
      <li>X: Holofernis, Majst</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>NumType</a></li>
</ul>

<ul>
  <li>Card
    <ul>
      <li>ADJ: 5., 1., 7., 10., 4., 3., 9., átta, 16., 2.</li>
      <li>ADV: einn, tveir, einum, eitt, þrír, tvö, átta, ein, eins, einu</li>
      <li>DET: einn, eitt, einum, ein, eina, einu, einni, eins, einnar, 1</li>
      <li>INTJ: du</li>
      <li>NOUN: hundruð, hundrað, móti, þúsund, brautu, hndr, sex, vj, ד, Bræður</li>
      <li>NUM: tólf, tveir, tvo, fimm, sex, tvö, 3, sjö, þrír, 2</li>
      <li>PART: einu, eitt</li>
      <li>PRON: hvörri, ór</li>
      <li>PROPN: 1, 4., I, 3., Jesaja, Tyrkjaskipið</li>
      <li>PUNCT: ", —</li>
      <li>VERB: átta, firrði, hylmast, lifir, bera, hvella</li>
      <li>X: Item</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Frac
    <ul>
      <li>ADJ: almáttkan, vǫn</li>
      <li>NOUN: ui, xx</li>
      <li>NUM: ij</li>
      <li>PUNCT: "</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ord
    <ul>
      <li>DET: hvaða</li>
      <li>NOUN: hundruð, þúsund</li>
      <li>NUM: tvö, fjögur, þrjú, fimm, tólf, hundruð, tuttugu, þrjá, fjörutíu, níu</li>
      <li>PROPN: Tvö</li>
    </ul>
  </li>
</ul>



<ul>
  <li><a>Person</a></li>
</ul>

<ul>
  <li>1
    <ul>
      <li>ADJ-Fin: syndgum, göfgum, Vei, auðgum, blessuðum, fríum, fáum, heilum, helgum, kæri</li>
      <li>ADP: við, á, eftir, fyr, yðrum</li>
      <li>ADP-Fin: á, fyr, yðrum</li>
      <li>ADV-Fin: eigi, forðum, fer, fór, Nær, aldri, dvel, helst, kann, kem</li>
      <li>AUX-Fin: var, vil, er, hefi, mun, skal, skulum, erum, hef, höfum</li>
      <li>CCONJ-Fin: hverki, Né, efn</li>
      <li>DET: sá, öngum, engi, einkis, hvörjir, hvörjum, þeim</li>
      <li>DET-Fin: sá, öngum, engi, einkis, hvörjum</li>
      <li>INTJ-Fin: Hei, Áví, Ó, Óhó</li>
      <li>NOUN: ég, mér, eg, klæðum, sóttum, Vér, borðum, klæði, lyktum, syndum</li>
      <li>NOUN-Fin: klæðum, sóttum, borðum, klæði, lyktum, syndum, ættum, herinum, lýðum, meinum</li>
      <li>PRON: eg, ég, mér, vér, mig, oss, við, okkur, mín, okkar</li>
      <li>PRON-Fin: vorum, eg, yðrum, hvörja, hvörjum, Annaðhvört, hver, örðum, þeim</li>
      <li>PROPN: Eg, Ég, Vér, Georgíus, Mér, Vali</li>
      <li>PROPN-Fin: Georgíus, Vali</li>
      <li>PUNCT: "</li>
      <li>SCONJ-Fin: er</li>
      <li>VERB: veit, fór, segi, fékk, sá, ætla, kom, tók, sé, lét</li>
      <li>VERB-Fin: veit, fór, segi, fékk, sá, ætla, kom, tók, sé, lét</li>
      <li>X: Majst, omnium</li>
      <li>X-Fin: omnium</li>
    </ul>
  </li>
</ul>

<ul>
  <li>2
    <ul>
      <li>ADJ-Fin: verðir, Heill, Hásu, Nakið, Skamt, Skjót, heilagrar, hlýðið, löstu, mildi</li>
      <li>ADP: fyr, Nær</li>
      <li>ADP-Fin: fyr, Nær</li>
      <li>ADV: nær, þú, eigi, heldur, hvört, gerr, hvörsu, kemur, mætir, starfar</li>
      <li>ADV-Fin: nær, eigi, heldur, hvört, gerr, hvörsu, kemur, mætir, starfar, takið</li>
      <li>AUX-Fin: ert, hefir, hefur, eruð, hafið, skalt, vilt, munt, skuluð, viljið</li>
      <li>CCONJ-Fin: hverki</li>
      <li>DET: sjá, engi, Nokkuru, engvan, fæstu, meiri, nökkut, þeim</li>
      <li>DET-Fin: sjá, engi, Nokkuru, engvan, fæstu, meiri, nökkut</li>
      <li>INTJ-Fin: duddu</li>
      <li>NOUN: Þú, þér, sverð, hurðu, Furðu, Grið, Stundu, Sverðið, búið, dirfzku</li>
      <li>NOUN-Fin: sverð, hurðu, Furðu, Grið, Stundu, Sverðið, búið, dirfzku, eig, far</li>
      <li>PRON: þú, þér, yður, þig, yðar, þið, þín, ykkur, ykkar, eg</li>
      <li>PRON-Fin: eg, hvörju, hvörn, hvörs, hvörja, hvörra, yðru, þaug, þínun</li>
      <li>PROPN: Þú, Þér, Yxu, Þig</li>
      <li>PROPN-Fin: Yxu</li>
      <li>PUNCT: "</li>
      <li>PUNCT-Fin: "</li>
      <li>SCONJ-Fin: er, at</li>
      <li>VERB-Fin: sjáið, segið, lát, ætlar, segir, veist, vitið, átt, gef, seg</li>
    </ul>
  </li>
</ul>

<ul>
  <li>3
    <ul>
      <li>ADJ-Fin: verður, var, fær, nær, ríkir, sannast, átti, syndgir, varir, fegri</li>
      <li>ADP-Fin: á, fyr, nær, eptir, Meður, gegni, héreftir, næst, so, sér</li>
      <li>ADV-Fin: eigi, nær, heldur, snart, helst, fór, braut, fyr, kann, mátti</li>
      <li>AUX-Fin: var, er, voru, hafði, væri, eru, hefði, sé, mun, skyldi</li>
      <li>CCONJ-Fin: eður, Hvörki, heldur</li>
      <li>DET-Fin: sá, engi, fá, eð, inna, minna, sjá, Meir, Nokkuru, Sé</li>
      <li>INTJ-Fin: Vei</li>
      <li>NOUN-Fin: vilja, greinir, sakar, synda, syndir, engi, leið, mun, hóf, mætti</li>
      <li>NUM-Fin: Xii, fjörutigi, iiii, iiijr, vii</li>
      <li>PRON-Fin: voru, sér, vorar, yðrar, yðrir, órar, hvör, sinna, yðra, vér</li>
      <li>PROPN-Fin: Vali, sankti, Valdi, Maii, Majst, guði, Beljus, Belíus, Brúni, Guddu</li>
      <li>SCONJ-Fin: er, eð, eru, hvörri, hvört</li>
      <li>VERB-Fin: sagði, segir, kom, mælti, tók, varð, gekk, fór, hét, lét</li>
      <li>X-Fin: Majst, Edimus, Item, Sicut, beati, nostra, nostri, patri, sankti, statuta</li>
    </ul>
  </li>
</ul>




<h3>Other Features</h3>


<ul>
  <li><a>Foreign</a>
    <ul>
      <li>Yes
        <ul>
          <li>ADJ: Vant, Aum, Darius, Heil, iiii, Besti, Gamall, Heili, Italiani, Ofanvert</li>
          <li>ADP: fyr, of, umb, Und, intra, nama</li>
          <li>ADV: ei, sicut, so, ogsvo, Mart, item, fraMe, nu, Allvel, Brott</li>
          <li>AUX: Vil, man, myni, Munu, Vilda, emk, er, hefir, hefoi, séim</li>
          <li>CCONJ: oc, et</li>
          <li>DET: in, ins, þenna, engi, ina, inu, inum, mart, enu, inar</li>
          <li>INTJ: Hei, Jaaaá, hahaha, he, Vei, Bless, Blubbs, Eia, Hahahaha, O</li>
          <li>NOUN: son, anno, dal, kap, Majestets, hold, hertug, leon, von, eyxn</li>
          <li>NUM: ij, iij, iiij, iiii, xii, vii, ccc, e, ix, xi</li>
          <li>PRON: Oss, þaug, huer, þeira, Haun, Minn, Sitt, Soddan, Vor, Vort</li>
          <li>PROPN: Erasmus, Metternich, Darius, Vali, Dominus, Pelissier, Moyses, Menon, Petrus, Thiers</li>
          <li>PUNCT: —</li>
          <li>VERB: Bar, Tak, Gessovel, Ger, Vita, Heyr, Komu, Tel, talt, Seg</li>
          <li>X: anno, in, item, domini, et, Dominus, etc, de, Achior, corpus</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<h2>Syntax</h2>

<h3>Auxiliary Verbs and Copula</h3>

<ul>
<li>This corpus uses 2 lemmas as copulas (<a>cop</a>). Examples: vera, blífa.</li>
</ul>

<ul>
<li>This corpus uses 9 lemmas as auxiliaries (<a>aux</a>). Examples: hafa, munu, skulu, vilja, mega, geta, verða, fá, kunna.</li>
</ul>

<h3>Core Arguments, Oblique Arguments and Adjuncts</h3>

Here we consider only relations between verbs (parent) and nouns or pronouns (child).
<ul>
  <li><a>nsubj</a>
    <ul>
      <li>VERB--NOUN (92)</li>
      <li>VERB--NOUN-Acc (179)</li>
      <li>VERB--NOUN-Dat (181)</li>
      <li>VERB--NOUN-Gen (20)</li>
      <li>VERB--NOUN-Nom (1134)</li>
      <li>VERB--PRON (887)</li>
      <li>VERB--PRON-Acc (108)</li>
      <li>VERB--PRON-Dat (257)</li>
      <li>VERB--PRON-Gen (11)</li>
      <li>VERB--PRON-Nom (1993)</li>
      <li>VERB-Fin--NOUN (121)</li>
      <li>VERB-Fin--NOUN-Acc (651)</li>
      <li>VERB-Fin--NOUN-Dat (553)</li>
      <li>VERB-Fin--NOUN-Gen (78)</li>
      <li>VERB-Fin--NOUN-Nom (11848)</li>
      <li>VERB-Fin--PRON (255)</li>
      <li>VERB-Fin--PRON-Acc (842)</li>
      <li>VERB-Fin--PRON-Dat (2301)</li>
      <li>VERB-Fin--PRON-Gen (103)</li>
      <li>VERB-Fin--PRON-Nom (27150)</li>
      <li>VERB-Fin--PRON-Nom-ADP(hjá) (1)</li>
      <li>VERB-Fin--PRON-Nom-ADP(til) (1)</li>
      <li>VERB-Inf--NOUN (35)</li>
      <li>VERB-Inf--NOUN-Acc (463)</li>
      <li>VERB-Inf--NOUN-Dat (34)</li>
      <li>VERB-Inf--NOUN-Gen (26)</li>
      <li>VERB-Inf--NOUN-Nom (1043)</li>
      <li>VERB-Inf--PRON (455)</li>
      <li>VERB-Inf--PRON-Acc (486)</li>
      <li>VERB-Inf--PRON-Dat (330)</li>
      <li>VERB-Inf--PRON-Gen (13)</li>
      <li>VERB-Inf--PRON-Nom (4014)</li>
      <li>VERB-Part--NOUN (32)</li>
      <li>VERB-Part--NOUN-Acc (104)</li>
      <li>VERB-Part--NOUN-Dat (279)</li>
      <li>VERB-Part--NOUN-Gen (36)</li>
      <li>VERB-Part--NOUN-Nom (1585)</li>
      <li>VERB-Part--PRON (48)</li>
      <li>VERB-Part--PRON-Acc (51)</li>
      <li>VERB-Part--PRON-Dat (442)</li>
      <li>VERB-Part--PRON-Gen (54)</li>
      <li>VERB-Part--PRON-Nom (1551)</li>
      <li>VERB-Sup--NOUN (14)</li>
      <li>VERB-Sup--NOUN-Acc (65)</li>
      <li>VERB-Sup--NOUN-Dat (46)</li>
      <li>VERB-Sup--NOUN-Gen (10)</li>
      <li>VERB-Sup--NOUN-Nom (923)</li>
      <li>VERB-Sup--PRON (39)</li>
      <li>VERB-Sup--PRON-Acc (108)</li>
      <li>VERB-Sup--PRON-Dat (191)</li>
      <li>VERB-Sup--PRON-Gen (12)</li>
      <li>VERB-Sup--PRON-Nom (3183)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>obj</a>
    <ul>
      <li>VERB--NOUN (147)</li>
      <li>VERB--NOUN-Acc (669)</li>
      <li>VERB--NOUN-Dat (260)</li>
      <li>VERB--NOUN-Gen (113)</li>
      <li>VERB--NOUN-Nom (336)</li>
      <li>VERB--PRON (78)</li>
      <li>VERB--PRON-Acc (280)</li>
      <li>VERB--PRON-Dat (135)</li>
      <li>VERB--PRON-Gen (33)</li>
      <li>VERB--PRON-Nom (191)</li>
      <li>VERB-Fin--NOUN (288)</li>
      <li>VERB-Fin--NOUN-Acc (9709)</li>
      <li>VERB-Fin--NOUN-Acc-ADP(og) (1)</li>
      <li>VERB-Fin--NOUN-Dat (2044)</li>
      <li>VERB-Fin--NOUN-Dat-ADP(af) (1)</li>
      <li>VERB-Fin--NOUN-Dat-ADP(fyrir) (1)</li>
      <li>VERB-Fin--NOUN-Dat-ADP(með) (1)</li>
      <li>VERB-Fin--NOUN-Dat-ADP(í) (1)</li>
      <li>VERB-Fin--NOUN-Gen (633)</li>
      <li>VERB-Fin--NOUN-Nom (1461)</li>
      <li>VERB-Fin--PRON (356)</li>
      <li>VERB-Fin--PRON-Acc (3611)</li>
      <li>VERB-Fin--PRON-Dat (1491)</li>
      <li>VERB-Fin--PRON-Gen (294)</li>
      <li>VERB-Fin--PRON-Nom (1598)</li>
      <li>VERB-Inf--NOUN (123)</li>
      <li>VERB-Inf--NOUN-Acc (4451)</li>
      <li>VERB-Inf--NOUN-Dat (1044)</li>
      <li>VERB-Inf--NOUN-Dat-ADP(í) (2)</li>
      <li>VERB-Inf--NOUN-Gen (338)</li>
      <li>VERB-Inf--NOUN-Nom (339)</li>
      <li>VERB-Inf--PRON (79)</li>
      <li>VERB-Inf--PRON-Acc (2043)</li>
      <li>VERB-Inf--PRON-Dat (724)</li>
      <li>VERB-Inf--PRON-Dat-ADP(eftir) (1)</li>
      <li>VERB-Inf--PRON-Gen (185)</li>
      <li>VERB-Inf--PRON-Nom (329)</li>
      <li>VERB-Part--NOUN (9)</li>
      <li>VERB-Part--NOUN-Acc (123)</li>
      <li>VERB-Part--NOUN-Dat (63)</li>
      <li>VERB-Part--NOUN-Gen (20)</li>
      <li>VERB-Part--NOUN-Nom (159)</li>
      <li>VERB-Part--PRON (14)</li>
      <li>VERB-Part--PRON-Acc (55)</li>
      <li>VERB-Part--PRON-Dat (35)</li>
      <li>VERB-Part--PRON-Gen (12)</li>
      <li>VERB-Part--PRON-Nom (119)</li>
      <li>VERB-Sup--NOUN (31)</li>
      <li>VERB-Sup--NOUN-Acc (1421)</li>
      <li>VERB-Sup--NOUN-Dat (314)</li>
      <li>VERB-Sup--NOUN-Dat-ADP(af) (2)</li>
      <li>VERB-Sup--NOUN-Gen (74)</li>
      <li>VERB-Sup--NOUN-Nom (152)</li>
      <li>VERB-Sup--PRON (30)</li>
      <li>VERB-Sup--PRON-Acc (676)</li>
      <li>VERB-Sup--PRON-Dat (237)</li>
      <li>VERB-Sup--PRON-Gen (37)</li>
      <li>VERB-Sup--PRON-Nom (207)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>iobj</a>
    <ul>
      <li>VERB--NOUN (6)</li>
      <li>VERB--NOUN-Acc (3)</li>
      <li>VERB--NOUN-Dat (51)</li>
      <li>VERB--NOUN-Nom (5)</li>
      <li>VERB--PRON (24)</li>
      <li>VERB--PRON-Acc (21)</li>
      <li>VERB--PRON-Dat (203)</li>
      <li>VERB--PRON-Gen (2)</li>
      <li>VERB--PRON-Nom (1)</li>
      <li>VERB-Fin--NOUN (8)</li>
      <li>VERB-Fin--NOUN-Acc (90)</li>
      <li>VERB-Fin--NOUN-Dat (486)</li>
      <li>VERB-Fin--NOUN-Gen (17)</li>
      <li>VERB-Fin--NOUN-Nom (23)</li>
      <li>VERB-Fin--PRON (33)</li>
      <li>VERB-Fin--PRON-Acc (230)</li>
      <li>VERB-Fin--PRON-Dat (2610)</li>
      <li>VERB-Fin--PRON-Gen (12)</li>
      <li>VERB-Fin--PRON-Nom (38)</li>
      <li>VERB-Inf--NOUN (4)</li>
      <li>VERB-Inf--NOUN-Acc (30)</li>
      <li>VERB-Inf--NOUN-Dat (221)</li>
      <li>VERB-Inf--NOUN-Gen (9)</li>
      <li>VERB-Inf--NOUN-Nom (4)</li>
      <li>VERB-Inf--PRON (9)</li>
      <li>VERB-Inf--PRON-Acc (68)</li>
      <li>VERB-Inf--PRON-Dat (1226)</li>
      <li>VERB-Inf--PRON-Gen (10)</li>
      <li>VERB-Inf--PRON-Nom (10)</li>
      <li>VERB-Part--NOUN-Acc (2)</li>
      <li>VERB-Part--NOUN-Dat (37)</li>
      <li>VERB-Part--NOUN-Gen (2)</li>
      <li>VERB-Part--PRON-Acc (7)</li>
      <li>VERB-Part--PRON-Dat (67)</li>
      <li>VERB-Part--PRON-Gen (2)</li>
      <li>VERB-Part--PRON-Nom (1)</li>
      <li>VERB-Sup--NOUN (1)</li>
      <li>VERB-Sup--NOUN-Acc (8)</li>
      <li>VERB-Sup--NOUN-Dat (68)</li>
      <li>VERB-Sup--NOUN-Nom (1)</li>
      <li>VERB-Sup--PRON (2)</li>
      <li>VERB-Sup--PRON-Acc (35)</li>
      <li>VERB-Sup--PRON-Dat (535)</li>
      <li>VERB-Sup--PRON-Gen (3)</li>
      <li>VERB-Sup--PRON-Nom (4)</li>
    </ul>
  </li>
</ul>




<h3>Relations Overview</h3>

<ul>
<li>This corpus uses 5 relation subtypes: <a>acl:relcl</a>, <a>compound:prt</a>, <a>flat:foreign</a>, <a>flat:name</a>, <a>nmod:poss</a></li>
<li>The following 2 main types are not used alone, they are always subtyped: <a>compound</a>, <a>flat</a></li>
<li>The following 5 relation types are not used in this corpus at all: <a>clf</a>, <a>list</a>, <a>orphan</a>, <a>goeswith</a>, <a>reparandum</a></li>
</ul>
