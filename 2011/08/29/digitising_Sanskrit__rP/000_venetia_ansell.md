+++
title = "000 venetia ansell"

+++
[[venetia ansell	2011-08-29, 14:16:19 [Source](https://groups.google.com/g/samskrita/c/rPHCGLXL0yE)]]



In light of the recent discussions on creating software tools for use in Sanskrit etc, this report on digitising classical texts has a good summary section on activities in thisarea in the Sanskrit domain. the full pdf is attached and the extract related to Sanskrit below. 

****

****

**Sanskrit**

The issues involved in the digitization of Sanskrit texts and the development of tools to study and

present them online are so complicated that an annual international Sanskrit computational linguistics

symposium was established in 2007. 59 This subsection provides an overview of some of the major

digital Sanskrit projects and current issues in digitization in that language.

The major digital Sanskrit project online is the Sanskrit Library, a “digital library dedicated to

facilitating education and research in Sanskrit by providing access to digitized primary texts in Sanskrit

and computerized research and study tools to analyze and maximize the utility of digitized Sanskrit

text.” 60 The Sanskrit Library is part of the International Digital Sanskrit Library Integration project,

which seeks to connect various Sanskrit digital archives and tool projects as well as to establish

encoding standards, enhance manuscript access, and develop OCR technology and display software for

Devanagari text. On an individual basis, the Sanskrit Library supports philological research and

education in Vedic and Classical Sanskrit language and literature and provides access to Sanskrit texts

in digital form. The Sanskrit Library currently contains independent-study Sanskrit readers,

grammatical literature, morphological software, instructional materials, and a digital version of W. D.

Whitney’s *The Roots, Verb-Forms, and Primary Derivatives of the Sanskrit Language*. The Library’s

current areas of research include “linguistic issues in encoding, computational phonology and

morphology, OCR for Indic scripts, and markup of digitized Sanskrit lexica.” Free access to this

library is provided, but users must register.

59 <http://www.springerlink.com/content/p665684g40h7/?p=967bbca4213c4cb6988c40c0e3ae3a95&pi=0>

60 <http://sanskritlibrary.org/>

21

Another major scholarly online collection of Sanskrit is the Digital Corpus of Sanskrit (DCS), 61 which

provides access to a searchable collection of lemmatized Sanskrit texts and to a partial version of the

database of the SanskritTagger software. SanskritTagger is a “part-of-speech (POS) and lexical tagger

for post-Vedic Sanskrit” and it is able to analyze unprocessed digital Sanskrit text both lexically and

morphologically. 62 The DCS was automatically created from the most recent version of the

SanskritTagger database with a corpus chosen by the software creator Oliver Hellwig (the website

notes that this corpus had made no attempt to be exhaustive). The DCS was designed to support

research in Sanskrit philology, and it is possible to search for lexical units and their collocations from a

corpus of 2,700,000 words.

A variety of research has been conducted into the development of tools for Sanskrit, and this

subsection reviews only some of it. The need for digitized Sanskrit lexicons 63 as part of a larger

computational linguistics platform is an area of research for the Sanskrit Library, an issue that receives

substantial attention in Huet (2004). Huet’s article provides an overview of work to develop both a

Sanskrit lexical database and various automatic-tagging tools to support a philologist:

The first level of interpretation of a Sanskrit text is its word-to-word segmentation, and our

tagger will be able to assist a philology specialist to achieve complete morphological mark-up

systematically. This will allow the development of concordance analysis tools recognizing

morphological variants, a task which up to now has to be performed manually (Huet 2004).

Huet also asserted that the classical Sanskrit corpus is extensive and presents computational linguistics

with many analytical challenges.

In addition to the challenges Sanskrit presents for developing computational tools, the features of the

language itself make the creation of critical editions difficult. As Csernel and Patte (2009) explain, a

“critical edition” must take “into account all the different known versions of the same text in order to

show the differences between any two distinct versions.” 64 The creation of critical editions is

challenging in any language, particularly if there are many manuscript witnesses, but Sanskrit presents

some unique problems. In this paper, Csernel and Patte present an approach based on paragraphs and

sentences extracted from a collection of manuscripts known as the “Banaras” gloss. This gloss was

written in the seventh century AD and is the most famous commentary on the “notorious” Panini

grammar, which was known as the first “generative” grammar and was written around the fifth century

BC. One major characteristic of Sanskrit described by Csernel and Patte is that it is “not linked to a

specific script,” and while the Brahmi script was used for a long time, Devanagari is now the most

common. The authors reported that they used the transliteration scheme of Sanskrit for Tex that was

developed by Frans Velthius 65 wherein each Sanskrit letter is written using between one and three

Latin characters.

An interesting insight provided by these authors was how one problematic feature of Sanskrit texts—

namely, text written without spaces—was also found in other ancient texts:

61 <http://kjc-fs-cluster.kjc.uni-heidelberg.de/dcs/>

62 For more details on this tagger, see Hellwig (2007); for one of its research uses in philology see Hellwig (2010).

63 The NEH has recently funded a first step in this direction. A project entitled “Sanskrit Lexical Sources: Digital Synthesis and Revision” will support an

“international partnership between the Sanskrit Library (Maharishi University of Management) and the Cologne Digital Sanskrit Lexicon (CDSL) project

(Institute of Indology and Tamil Studies, Cologne University) to establish a digital Sanskrit lexical reference work.”

<http://www.neh.gov/news/archive/201007200.html>

64 Further discussion of this issue can be found in the section on Digital Editions.

65 <http://www.ctan.org/tex-archive/language/devanagari/velthuis/>

22

In ancient manuscripts, Sanskrit is written without spaces, and from our point of view, this is an

important graphical specificity, because it increases greatly the complexity of text comparison

algorithms. One may remark that Sanskrit is not the only language where spaces are missing in

the text: Roman epigraphy and European Middle Age manuscripts are also good examples of

that (Csernel and Patte 2009).

The solution that the authors ultimately proposed for creating a critical edition of a Sanskrit text

involved the lemmatization by hand of one of the two texts, specifically, the text of the edition.

Alignments between this lemmatized text and other texts then made use of the longest common

subsequence (LCS) algorithm. The authors are still experimenting with their methodology, but pointed

out that the absence of a Sanskrit lexicon limited their approach.

The development of OCR tools that will process Sanskrit scripts is a highly sought-after goal. Very

little work has been done in this area, but Thomas Breuel recently reported not only on the use of

OCRopus to recognize the Devanagari script but also on its application both to primary texts in

classical languages and to secondary classical scholarship. As was discussed previously in Boschetti et

al. (2009), preliminary work with OCRopus produced promising results with Ancient Greek.

Breuel (2009) described OCRopus as an OCR system that is designed to be both omnilingual and

omniscript and that advances the state of the art in that new text-recognition and layout-analysis

modules can be easily plugged in and that it uses an adaptive and user-extensible character recognition

module. Breuel acknowledged that there are many challenges to recognizing Devanagari script,

including the large number of ligatures, complicated diacritics, and the “large and unusual vocabulary

used in academic and historical texts” (Breuel 2009). In addition to Sanskrit texts, Breuel made the

important point that historical scholarship about Sanskrit and other classical languages is frequently

multilingual and multiscript and can mix Devanagari and Latin as well as Greek. Breuel thus proposed

that OCRopus has a number of potential applications in the field of classical scholarship, including the

recognition of original documents (written records), original primary source texts (printed editions of

classical texts), and both modern and historical secondary scholarship, including commentaries and

textbooks, and reference works such as dictionaries and encyclopedias.

He also explained that OCRopus uses a “strictly feed-forward system,” an important feature that

supports the plug-in of other layout-analysis and text-recognition modules. Other features include the

use of only a small number of data types to support reuse, “weighted finite state transducers” (WFSTs)

to represent the output of text line recognition, and final output in the hOCR format, which “encodes

OCR information in completely standards-compliant HTML files.” This open-source system can be

hosted through a web service, run from the command line or shell scripts, and users can customize how

it performs by scripting “the OCR engine in Lua.”

The basic stages in using OCRopus are image preprocessing, layout analysis, text-line recognition, and

statistical language modeling. Each stage offers a variety of customization options that make it

particularly useful for historical languages. In terms of text-line recognition in historical texts, the fact

that OCRopus has both built-in text-line recognizers and the ability to add external text-line

recognizers for different scripts is very important, because as Breuel articulated:

Some historical texts may use different writing systems, since Devanagari is not the only script

in historical use for Sanskrit. Scholarly writing on Sanskrit almost always uses Latin script, and

Latin script is also used for writing Sanskrit itself, including extended passages. Sanskrit

written in Devanagari and Latin scripts also makes use of numerous diacritics that need to be

23

recognized. In addition, IPA may be used for pronunciation, Greek letters may be used for

classical Greek quotations, and Greek letters and other special characters may be used for

indicating footnotes or other references (Breuel 2009).

The challenge of multilingual document recognition is a significant one for classical scholarship that

has been reported by many digital classics projects. OCRopus has built-in line recognizers for Latin

scripts, and unlike those of many other OCR systems, these recognizers make few assumptions about

character sets and fonts and are instead “trained” on text-line input that is then aligned against ground

truth data and can be used to automatically train “individual character shape models.” For Devanagari,

OCRopus handled diacritics by treating “character+diacritic” combinations as novel characters.

The final processing stage of OCRopus is language modeling, which in the case of OCRopus is based

on WFSTs. WFSTs allow language models and character recognition alternatives to be “manipulated

algebraically” and such language models can be learned from training data or constructed manually.

One important use of such models for mixed-language classical texts is that they can be used to

automatically identify languages within a digital text. “We can take existing language models for

English and Sanskrit and combine them,” Breuel explicated. “As part of the combination, we can train

or specify the probable locations and frequencies of transitions between the two language models,

corresponding to, for example, isolated foreign words within one language, or long quotations” (Breuel

2009).

As this subsection has indicated, the computational challenges of processing Sanskrit are being

actively researched, and some of the technical solutions may be adaptable to other historical languages

as well.

This mail and/or attachments are confidential and may also be legally privileged. If you are not the intended recipient, any disclosure, copying, distribution or action taken relying on the contents is strictly prohibited and may be unlawful. If you have received this communication in error, please notify the sender immediately by responding to this email and deleting the contents of the email & related attachments from your system. Though MPS has taken reasonable steps to ensure no viruses are present in this email, it cannot accept responsibility for any loss or damage arising from the use of this email or attachments. No contracts may be concluded with MPS through e-mail communication. Please consider the environment before printing this mail

  

