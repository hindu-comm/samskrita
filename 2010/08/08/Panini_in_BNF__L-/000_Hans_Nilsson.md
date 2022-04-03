+++
title = "000 Hans Nilsson"

+++
[[Hans Nilsson	2010-08-08, 13:00:38 [Source](https://groups.google.com/g/samskrita/c/L-Lm-bnKdVE)]]



Having started to study Panini’s grammer, and being a former IT professional, I wanted to make a structured description of his word classes and concepts. I have therefore refreshed my old knowledge of Backus-Naur grammar, (now also known as Panini-Backus, hooray!).I have written a first attempt at such a description (below and also attached as a Word doc). I would be very happy for all kinds of comments and corrections, big and small.

References to Astadhyayi is given where I could find them. English comparable terms are sometimes given in (). Question marks symbolizes questions about the correct Sanskrit term. Notes marked with; give further explanations.

Note: It seems like base, stem and root are used as synonyms in English descriptions of sanskrit. I have therefore decided to use the term base, which does not contain any botanical connotation...

If the text below is not readable, you can also find the document here: <http://www.hansnilsson.se/BNF.doc> and here: <http://www.hansnilsson.se/BNF.pdf>

Hans Nilsson  
  

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

; P does not clearly differentiate between adjectives (viśeṣaṇa) and nouns. Only in A 2.1.57 does he talk about viśeṣaṇa (qualifying) and viśeṣya (qualified). Adjectives were not recognized as a separate lexical category until 1747 (ref. Wikipedia).

; According to Gombrich (”He cooks softly”: Adverbs in Sanskrit Grammar), «words which appear to as to be adverbs, or used adverbially, are heterogeneously classified by P. All come into the category of *subanta*. Certain simple adverbs are listed as *avyaya* in the *Gaṇapāṭha*.» The term *kriyā-viśeṣana* is first used by Patanjali, and seems to be referring to derived words.

***2. Morphology***

\<pada> ::= \<subanta> \| \<tiṅanta> ; A 1.4.14

\<vibhakti> ::= \<sUP> \| \<tiN> ; A 1.3.104

\<prakṛti (base word)> ::= \<dhātu> \| \<prātipadika>

\<pada> ::= \<prakṛti> \[\<pratyaya>\] \[\<vibhakti>\]

; prakṛti + vibhakti => inflected primitive verb or inflected primitive nominal  
; prakṛti + pratyaya => derived avyaya, e.g. adverb  
  

\<pratyaya (affix)> ::= ; A 3.1.1  
 \<kṛt (primary)> 
; A 3.1.93  
 \| \< taddhita (secondary)>  ; A 4.1.76  
 \| \<vikaraṇa (infix)>  
 \| \<sanādi (verb derivation)>  
 \| \<strī (feminine)>  ; uncertain if it belongs here or not

; I have excluded sUP and tiN from the list of pratyayas, even though they can be argued to also be pratyayas. Everything gets clearer this way.

; Yāska gives the following general morphology:

\<pada> ::= \<śabda (basic word)> \<pratyaya> \<vibhakti>

; This means that \<śabda> == \<prakṛti> ??

*2.1 Tinanta morphology*

\<tiṅanta \> ::= \<dhātu> \<tiN>

\<tiN> ::= "tiP" \| … \| "mahiN" ; A 3.4.77

\<dhātu (verbal base)> ::= \< mūla? dhātu (primitive)> \| \<vyutpanna? dhātu (derived)>

\< mūla dhātu> ::= \<bhūvādayaḥdhātu> ; from dhātupāṭha, A 1.3.1

\<vyutpanna dhātu> ::=  
 \<sanādyantāḥ dhātu>  
 \| \<dhātu>\<vikaraṇa>

\<sanādyantāḥ dhātu> ::=  
 \<sannanta (desiderative)> \| \<yaṇanta (intensive)>  
 \| \<nijanta (causative)> \| \<nāmadhatū (verbal noun)>

*2.2 Subanta morphology*

\<subanta> ::= \< prakṛti> \[\<pratyaya>\] \[\<sUP>\]

; A few examples:  
; prātipadika + sUP => inflected noun  
; prātipadika + pratyaya + sUP => inflected derived noun  
; prātipadika + pratyaya => adverb (kriyā-viśeṣana)  
; dhātu + kṛt + sUP => inflected krdanta

\<sUP> ::= "sU" \| ... \| "suP" ; A 4.1.2

\< prātipadika (nominal base)> ::= \< mūla? prātipadika (primitive nom.base)>  
 \| \<vyutpanna? prātipadika (derived nom.base)>

\< mūla prātipadika)>::= \< gaṇapāṭha prātipadika> ; A 1.2.45  
 \| \<sarvanāman (pronouns)
 ; A1.1.27  
 \| \<saṅkhyā (numbers)>

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
 \| \<tatpurusa (case-determining) ; A 2.1.22  
 \| \<dvandva (pair) ; A 2.2.59

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

\<lakārāḥ>::= \<lAṬ> ; varttamāna (present tense)A 3.2.123  
 \| \<lIṬ> ; bhūta-anadyatana parokṣa ( perfect) A 3.2.115  
 \| \<lUṬ> ; bhaviṣya-anadyatana (periph. future) A 3.3.15  
 \| \<lŖṬ>  ; bhaviṣyati (simple future) A 3.3.13  
 \| \<lOṬ> ; (imperative) A 3.3.162  
 \| \<lAṄ> ; anadyatana-bhūta (imperfect) A 3.2.111  
 \| \<lIṄ> ;(optative) A 3.3.161  
 \| \<lUṄ> ; bhūta (aorist) A 3.2.110  
 \| \<lŖṄ>  ; (conditional)A 3.3.139

\<kāraka (case)> ::= ; A 1.4.23  
 \<kartā (agent)>  ; A 1.4.54-55  
 \| \<karma (object)> ; A 1.4.49-53  
 \| \<karaṇa (instrument)>  ; A 1.4.42-44  
 \| \<sampradāna (purpose)>  ; A 1.4.32-41  
 \| \<apādāna (separation)> ; A 1.4.24-31  
 \| \<adhikaraṇa (location)> ; A 1.4.45-48

; \*\*\* The End \*\*\*\*\*





