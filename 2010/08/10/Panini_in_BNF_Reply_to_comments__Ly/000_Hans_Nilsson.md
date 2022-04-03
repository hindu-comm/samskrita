+++
title = "000 Hans Nilsson"

+++
[[Hans Nilsson	2010-08-10, 15:19:42 [Source](https://groups.google.com/g/samskrita/c/LyC_mFiODXw)]]



Dear Mr Abhyankar and Mr Vaidya,



Thank you for the valuable comments. Here are a few replies:



1. Regarding karakas, I have tried to make a distinction between karaka = syntactic categorisation and vibhakti = morphological case endings. I have now added a statement for sup-vibhakti. I have however changed the English term form sampradana to ”indirect object”. I have also added \<upasarga-vibhakti> which is the only term I can find for posession (genitive).



2\. Regarding base, root and stem: OK, in order to avoid confusion, I will go back to the conventional terminology as follows:



Dhatu = verbal *root* (both primitive and derived??)

Pratipadika = nominal *stem* (both primitive and derived ??)



Very often, I see mentioned both ”verbal root” AND ”verbal stem” as two different concepts. Is the difference then the following ??

- verbal root (dhatu) = bhU

- verbal stem (???) = bhav (i.e. dhatu+ vikarana )

If so, what is then the correct sanskrit term for this second concept of «verbal stem»?



This actually leads me to the following more detailed description of the derivation of a tinanta:



\<tiṅanta \> ::= {\<upasarga>} \<dhātu> \<vikaraṇa> (\<lakāra\> =>
\<tiN>)

; According to Panini’s derivation method, lakāra is first added, and then later replaced by tiN



where \<vikarana> is a marker of insertion for conjugation class, tense or mood (for more details, see the updated document.)



Furthermore, I have tried to incorporate the term dhātu-sādhita (verbal derivate). I am not sure I have got it right



3\. I have added the karaka lET (subjunctive)



4\. Trying to analyze your example, I come to the following response:

pat: verbal root (dhatu)  
paat : verbal *stem*, with added vikarana causing guna/vrddhi

pranipaat: new *stem* containing two added upasargas (?)

pranipaatena : verbal derivative (dhAtu-sAdhita)



5\. I have added back sup, tin and vikarana to the list of pratyayas. After all, they ARE pratyayas. Butt hen I can not any longer use these statements since sup and tin are pratyayas:



\<pada> ::= \<prakṛti> \[\<pratyaya>\] \[\<vibhakti>\]

\<subanta> ::= \< prakṛti> \[\<pratyaya>\] \[\<sUP>\]



Instead I have avoided the use of the term pratyaya, and made more explicit definitions as follows:



\<tiṅanta \> ::= {\<upasarga>} \<dhātu> \<vikaraṇa> \<tiN>  
\<subanta> ::= \<prātipadika \> \[\<sUP>\]



which should be fine, since both dhātu and prātipadika can themselves both be primitive and derived. Please also note that I have introduced upasarga as an optional prefix.



6. Regarding derivatives, I have illustrated it with the following table. Please correct me if something is wrong.  
  

|                 |                       |               | |-----------------|-----------------------|---------------| | **Derivation**  | ****                 | ****         | | **From:**       | **To: prātipadika**   | **To: dhātu** | | **prātipadika** | taddhitanta, strīanta | nāmadhatū     | | **dhātu**       | kṛdanta               | sannanta etc  |



7. Regarding the relation to modern/English categories: I just wanted to show the correspondence between Panini word classes and modern terminology. Please note: I am only talking about “Lexical categories” like noun, verb, adverb etc. I am NOT talking about “phrasal categories” like subject, predicate, adverbial etc (which according to modern grammatical terminology are called Noun Phrase, Verb Phrase, Adverb Phrase etc).



From this point of view, adverb is a lexical category. So there is one “tomorrow” which is an adverb, and another homonym “tomorrow” which is a noun, just like the adverb “hard” is homonymous with the adjective “hard”.



In sanskrit, as I understand it, an adverb is always a subanta, but belonging to one of several sub-categories. It can be contained as a primitive in the list \<svaradi> or be derived through as \<taddhitanta>. However, I had difficulties expressing this in BNF, and so I wrote the following, which is a bit misleading (it looks like all svaradi can be adverbs):



\<ADVERB>::= \< svarādi \> ; as listed in gaṇapāṭha  
 \| \<kriyā-viśeṣana>  ; derived, e.g. by taddhita



I would be happy for any suggestion of better expressing this. Or maybe it should be left out altogether, regarding it not as “lexical category” but a “phrasal category”, which is not covered in this description.



The new BNF version is inserted below. The real document, which is more nicely formatted can be found at the following addresses:
[http://www.hansnilsson.se/BNF.doc](http://www.hansnilsson.se/BNF.doc) and here: [http://www.hansnilsson.se/BNF.pdf](http://www.hansnilsson.se/BNF.pdf)



Hans Nilsson

---------------------------------------------------------------------------------------------------------------------------------

***1. Lexical categories***

*1.1 Paninian view*

\<pada (word)> ::= \<subanta (nominal)> \| \<tiṅanta(verb)> ; A 1.4.14

\<avyaya (indeclinable)> ::= \<svarādi (sun etc.)> ; A 1.1.37-41  
 \| \< nipāta (particles) \> ; A 1.1.56  
 \| \<upasarga (preverb)> ; A 1.4.58  
 \| \<gati \> ; A 1.4.60 (=upasarga)

\<subanta> ::= \<prātipadika> \[\<sUP>\]

; Panini has only two main word classes. He includes avyayas in subanta, adding endings and then deleting them again in A 2.4.82! This is described above by \<sUP> being optional.

; Yāska, who preceded Panini, made the following categorization of word classes:

\<padajāta> ::= \<ākhyāta (finite verb)> \| \<nāman (nominal> \| \< nipāta \> \| \<upasarga (preverb)>

*1.2. Relation to modern/English lexical categories*

\<subanta>::= \<NOUN> \| \<ADJECTIVE> \| \<PRONOUN>  
 \| \<ADVERB> \| \<CONJUNCTION> \| \<PREPOSITION>

\< nipāta>::= \<CONJUNCTION> \| \<PREPOSITION>

\<ADVERB>::= \< svarādi \> ; as listed in gaṇapāṭha  
 \| \<kriyā-viśeṣana>  ; derived, e.g. by taddhita

; P does not clearly differentiate between adjectives (viśeṣaṇa) and nouns. Only in A 2.1.57 does he talk about viśeṣaṇa (qualifying) and viśeṣya (qualified). Adjectives were not recognized as a separate lexical category until very late. Even in latin, they were not really separated.

; According to Gombrich (”He cooks softly”: Adverbs in Sanskrit Grammar), «words which appear to as to be adverbs, or used adverbially, are heterogeneously classified by P. All come into the category of *subanta*. Certain simple adverbs are listed as *avyaya* in the *Ga**ṇapāṭha*.» The term *kriyā-viśeṣana* is first used by Patanjali, and seems to be referring to derived words.

***  
***

***2. Morphology***

\<pada> ::= \<subanta> \| \<tiṅanta> ; A 1.4.14

\<prakṛti (base word)> ::= \<dhātu> \| \<prātipadika>

\<vibhakti> ::= \<sUP> \| \<tiN> ; A 1.3.104

\<pada> ::= \<prakṛti> \[\<pratyaya>\] \[\<vibhakti>\]

\<pratyaya (affix)> ::= ; A 3.1.1  
 \<kṛt (primary)> 
; A 3.1.93  
 \| \< taddhita (secondary)>  ; A 4.1.76  
 \| \<sanādi (verb derivation)>  
 \| \<strī (feminine)>  
 \| \<sUP>\| \<tiN> \| \<vikaraṇa>

; tiN, sUP and vikaraṇa are formally pratyayas according to Panini.

\<dhātu-pratyaya (verbal affix)> ::= \<kṛt> \| \<tiN> \| \<vikaraṇa> ; can be added to verbs

\<prātipadika-pratyaya (nominal affix)> ::= \<taddhita> \| \<sUP>\| \<strī\> ; can be added to nominals

\< dhātu-sādhita (verbal derivative)> ::=
 ; can be derived from verbs  
 \<kṛdanta>\| \<sannanta> \| \<yaṇanta> \| \<nijanta>

\< prātipadika-sādhita (nominal derivative)> ::=  ; can be derived from nominals  
 \<taddhitanta> \| \<strīanta>\| \<nāmadhatū \>

|                 |                       |               | |-----------------|-----------------------|---------------| | **Derivation**  | ****                 | ****         | | **From:**       | **To: prātipadika**   | **To: dhātu** | | **prātipadika** | taddhitanta, strīanta | nāmadhatū     | | **dhātu**       | kṛdanta               | sannanta etc  |



; Yāska gives the following general morphology:

\<pada> ::= \<śabda (basic word)> \<pratyaya> \<vibhakti>

; This means that \<śabda> == \<prakṛti> ??

*  
*

*2.1 Tinanta morphology*

\<tiṅanta \> ::= {\<upasarga>} \<dhātu> \<vikaraṇa> (\<lakāra\> =>
\<tiN>)

; According to Panini’s derivation method, lakāra is first added, and then later replaced by tiN

\<dhātu (verbal base)> ::= \< mūla dhātu (primitive)> \| \< sanādyanta dhātu (derived)>

\< mūla dhātu> ::= \<bhūvādayaḥdhātu> ; from dhātupāṭha, A 1.3.1

\<sanādyantāḥ dhātu> ::=  
 \<sannanta (desiderative)> \| \<yaṇanta (intensive)>  
 \| \<nijanta (causative)> \| \<nāmadhatū (verbal noun)>

\<upasarga> ::= 
; A 1.4.59  
 “pra” \| “parā” \| “apa” \| “sam” \| “anu” \| “ava”  
 \| “niḥ” \| “duḥ” \| “vi” \| “ā” \| “ni” \| “adhi” \| “api”  
 \| “ati” \| “su” \| “ut” \| “abhi” \| “prati”
\| “pari” \| “upa”

\<vikaraṇa (infix)> ::=  ; conjugation class, tense and mood markers  
 \| ”ŚaP” \| ”LUK”\| ”ŚLU” \| ”ŚyaN” \| ”Śnu” \| ”Śa” \| ”ŚnaM” \| ”u” \| ”Śnā” \| ”NiC” ; A.3.1.68 ff  
 \| ”CLI” \| ”sIC”\| ”sya”\| ”yaK” \| ”yāsUṬ”\| ; for lUṄ, lŖṄ etc

\<tiN> ::= "tiP" \| … \| "mahiN" ; A 3.4.77

\<lakāra\>::= \<lAṬ\> ; varttamāna (present tense)A 3.2.123  
 \| \<lIṬ\> ; bhūta-anadyatana parokṣa ( perfect) A 3.2.115  
 \| \<lUṬ> ; bhaviṣya-anadyatana (periph. future) A 3.3.15  
 \| \<lŖṬ>  ; bhaviṣyati (simple future) A 3.3.13  
 \| \<lOṬ> ; (imperative) A 3.3.162  
 \| \<lAṄ> ; anadyatana-bhūta (imperfect) A 3.2.111  
 \| \<lIṄ> ; (optative) A 3.3.161  
 \| \<lUṄ> ; bhūta (aorist) A 3.2.110  
 \| \<lŖṄ>  ; (conditional)A 3.3.139  
 \| \<lEṬ> ; subjunctive

*2.2 Subanta morphology*

\<subanta> ::= \<prātipadika \> \[\<sUP>\]

\<sUP> ::= "sU" \| ... \| "suP" ; A 4.1.2

\< prātipadika (nominal base)> ::= \< mūla prātipadika (primitive nom.base)>  
 \| \<vyutpanna prātipadika (derived nom.base)>

\< mūla prātipadika)>::= \< gaṇapāṭha prātipadika> ; A 1.2.45  
 \| \<sarvanāman (pronouns)
 ; A1.1.27  
 \| \<saṅkhyā (numbers)\>

\<vyutpanna prātipadika>::=
; A 1.2.46  
 \<kṛdanta>  
 \| \<taddhitanta>  
 \| \<samāsa (compounds)>

\<kṛdanta> ::= \<dhatū> \<kṛt>

\<taddhitanta> ::= \<prātipadika> \<taddhita>

\<kṛt> ::=

; A 3.1.93  
 ”a” \| ”ā” \| ”ana” \| ”man” \| ”as” \| ”ti” ; forming noun/adjectives  
 \| \<kṛtya (gerundive)> ; yaT, anīyaR, tavya, tavyaT, KyaP ; A 3.1.96  
 \| \<tvanta/lyabanta (gerund)> ; Ktvā ; A 5.1.119  
 \| \<tumanta (infinitive)> ; tumUN ; A 3.3.10  
 \| \<niṣṭhā (past participles)> ; Kta, KtavatU ; A 1.1.26  
 \| \<sat (present participles)> ; ŚatŖ, ŚānaC (active, passive)  ; A 3.2.124-127  
 \| \<māna (pres. middle part)>
 ; A 7.2.82

\<taddhita> ::=

; A 4.1.76  
 ”mat” \| ”vat” \| ”in” \| ”vin” ; indicating posession  
 \| ”ya” \| ”tva” \| ”tā” ; abstraction  
 \| ”eya” ; descent, pertaining to  
 \| ”ka” \| ”ika” ; relating to, dimunitive  
 \| ”maya” \| ”mayī” ; made of, filled with  
 \| ”tara” \| ”tama” ; comparative, superlative  
 \| ”vat”
; adverb: like as  
 \| ”tas”
; adverb: from  
 \| ”śas” \| ”śaḥ” ; adverb: manner

\<samāsa \> ::=

; A 2.1.3  
 \<avyayibhāva (indecliable)> ; A 2.1.5  
 \| \<bahuvrīhi (unmentioned)> ; A 2.3.23  
 \| \<tatpurusa (case-determining)> ; A 2.1.22  
 \| \<dvandva (pair)> ; A 2.2.59

\<tatpurusa> ::= \<dvigu>  ; A 2.1.52  
 \| \<karmadhārya (descriptive)>

***  
***

***3. Other grammatical elements***

\<purusa (person>::=  ; A 1.4.101  
 \| \<prathama (third)>  
 \| \<madhyama (second)>  
 \| \<uttama (first)>

\<vacana (number)> ::= ; A 1.4.102-3  
 \| \<ekavacana>  
 \| \<dvivacana>  
 \| \<bahuvacana>

\<vyakti/liṅga (gender)> ::=  
 \| \<puṃlinga (masc.)>  
 \| \<strīliṅga (fem.)>  
 \| \<napuṃsakaliṅga (neut.)>

\<kāraka \> ::= ; A 1.4.23 syntactic-semantic categories  
 \<kartā (agent)>
 ; A 1.4.54-55  
 \| \<karma (object)> ; A 1.4.49-53  
 \| \<karaṇa (instrument)>
 ; A 1.4.42-44  
 \| \<sampradāna (indir.object)>
 ; A 1.4.32-41  
 \| \<apādāna (separation)> ; A 1.4.24-31  
 \| \<upapada-vibhakti (posession)>  
 \| \<adhikaraṇa (location)>
 ; A 1.4.45-48

\<sUP-vibhakti>::= ; corresponding subanta case  
  \<prathamā> ; nominative  
 \|\<dvitīyā> ; accusative  
 \|\<tṛtīyā> ; instrumental  
 \|\<caturthī> ; dative  
 \|\<paṇcamī> ; ablative  
 \|\<ṣaṣṭhī> ; genitive  
 \|\<saptamī> ; locative













  
  

