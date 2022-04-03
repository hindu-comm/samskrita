+++
title = "000 Sai Susarla (Google Drive)"

+++
[[Sai Susarla (Google Drive)	2014-04-01, 00:35:07 [Source](https://groups.google.com/g/samskrita/c/b1bZUZgkTnE)]]



Samskrit Language Processing (SLP) Hackathon 2014

``` If you have working knowledge of machine-learning, speech or image processing tools and techniques, are passionate about the Samskrit language, and are based in Bangalore, please come join our Samskrit Hackathon from April 6th 1.30pm to Apr 8, 5pm. See the announcement below for details and registration instructions. - Sai. ```

  

Snapshot of the item below:

Samskrit Language Processing Hackathon

April 6-8, 2014 at the Dept of Computer Science and Automation, IISc Bangalore

What is SLP Hackathon?

SLP stands for Samskrit Language Processing. SLP Hackathon a fun two-day, focused group-programming event to jump-start the creation of useful tools for processing Samskrit language using available computing technology. The objective is to kindle interest in this fertile area of innovation among the programming-savvy youth to benefit the Indian community and themselves both intellectually and culturally.

A focussed group effort such as a hackathon always produces something useful quickly, provides a much faster learning curve to its participants, and builds excellent teams.

Which Projects?

1.  i-vaktaa: Samskrit Audio Reader (Unicode text-to-speech) 2.  i-lekhak: Samskrit Dictation Tool (speech-to-unicode-text) 3.  Image-based Search Tool for Scanned Devanagari Text Documents

When?

-   Sunday April 6th, 1.30pm to Tuesday April 8th 4pm, 2014 Demo at 5pm.

Where (venue)?

Department of Computer Science and Automation (CSA), IISc Bangalore Prof. Gopinath’s office.

Prerequisites:

-   A laptop with Linux and Windows installed (preferably Ubuntu). Wi Fi
    Internet available. -   Proficiency in a modern scripting language (Perl or Python) and
    Java/C++. -   Basic knowledge of Indian alphabet (devanagari). -   Working experience with at least one of the following: 1)
    machine-learning techniques and tools like Matlab or R, 2) speech or
    image processing tools.

How to Register?

Fill up the [online registration form](https://docs.google.com/forms/d/1OgGTXL-9-XoMR2izwR4hriHPs7aaiKu7S9YaSnWnMT0/viewform)by Friday Apr 4th, 2014at 9pm. Only the first 6 people with the best available skills will be accepted to ensure good productivity. You’ll be notified by 9pm on April 5th. If accepted, show up at the venue by 1.30pm on Apr 6th for orientation, and the fun begins.

-   Prof. Gopinath, IISc CSA dept,

&nbsp;

-   Sai Susarla, NetApp ([sai.s...@gmail.com]()). -   Sri P. Ramanujan, Assoc. Director, CDAC, Samskrit scholar.

Logistics:

-   Juices and snacks served, will go out for lunch together (self-paid)

Why ILP? Why Samskrit?

Despite significant advances in computer-assisted natural language processing of English and other languages, the technology for Indian language processing has not matured due to lack of adequate attention by the scientific community. Several tools and methods have been developed for various aspects of handling Indian languages in various research institutes in India and elsewhere, including OCR, sentence parsing, conjunct analysis etc. But their unavailability and lack of interoperability in a reusable framework severely inhibits their mainstream use and further enhancement by the community. The dwindling number of scholars in Indian traditional shaastras is a looming threat to preserving and enhancing precious traditional knowledge in areas such as Ayurveda, eco-sciences and naturopathy. Samskrit is undoubtedly the key to this knowledge, and is highly amenable to automated processing due to its regular structure. Most Indian languages share the tech-friendly traits of Samskrit and hence can benefit from these processing tools as well.

The availability of reusable tools and technologies for large-scale automated processing of Samskrit and other Indian language texts has the following benefits:

-   it democratizes accessto the vast Indian knowledge base by
    employing the latest in information technology to lower the barrier
    to self-study significantly. -   it gives a fillip to widespread comparative studyof and research
    into the vast Indian literature in areas relevant to the present
    day. Govt statistics indicate at least half a million unpublished
    and unscrutinized manuscripts on various secular subjects in Indian
    languages, just in Samskrit. That illustrates the scale of the
    problem. Without modern tools to assist, exploration of these texts
    is a painstakingly slow and error-prone process that discourages
    many otherwise interested students. -   it opens up a largely unexplored area for innovation in computer
    science, namely, exploiting the regular structure of Indian
    Samskrit-based natural languages to significantly improve natural
    language processing and its applications in India.

# Hackathon Projects: Details

## Application 1: i-vaktaa: Samskrit Audio Reader (text-to-speech)

## Given Samskrit text in Unicode, produce an audio rendering of that text in popular sound formats. Should be usable both in batch mode and streaming mode. This application has two components:

1.  ## Grapheme (unicode string) to phoneme mapper (table or tool) for Samskrit language.

2.  ## A Text-To-Speech converter tool (open-source if available) for Indian language. There are several generic TTS engines already available and have been successfully used for up to 10 Indian languages.

### Application 2: i-lekhak: Samskrit Dictation Tool (speech-to-text)

## Given a Samskrit speech in audio, produce the corresponding Unicode text. This has several components:

1.  ## Generic Speech segmentation tool that produces phoneme sequence from human speech.

2.  ## Samskrit phoneme database build with phoneme-based fuzzy search facility.

3.  ## Phoneme to unicode text sequence mapper.

4.  ## Vedic accent (anusvara) tagger for Samskrit phonemes.

5.  ## Word segmentor from phonemes.

## Follow-on applications:

-   ## Veda ghana/pada/krama/jaTa paaTha identifier/checker.

-   ## Voice-based online search

### Application 3: viikshaa: Visual Search Tool for Scanned Text

## When user selects a portion of a scanned text image, this tool should return all the positions where similar image occurs in the entire scanned treatise. This tool forms the basis for a lipi tutor application that accelerates conversion of texts from unknown to known scripts as follows. Suppose an expert labels a portion of a scanned unknown script text with its Unicode text, the tool looks for similar occurrences elsewhere in the scanned text and auto-labels them.

## This application has several components:

1.  ## Text image segmentation tool. Split a single scanned text image into sub-images containing text snippets and their locations.

2.  ## Image locator. Build an index of locations where a given image occurs in a set of larger images after a given set of transformations (blurred, rotated, scaled).

3.  ## Captcha-style crowd-sourced text auto-labeling. Show the segmented text images for humans to identify. Seek and store the corresponding unicode text.

## Most of these tools are already available and widely used on the Internet today for old English text identification. We need to leverage them for Indian language text identification.

## Speech Recognition tool kit for Indian languages:

ilp_segment x.wav \| ilp_cluster \| ilp_label \> x.html

chops a given samskrit or Indian language speech into the tiny wav files for each of the aksharas uttered. Basically the logic introduces markers between aksharas in a continuous speech and outputs a delimited wav file. The ilp_label program then takes those segments and adds them to a dictionary of similar-sounding phonemes.

We will take several multi-hour-long speeches in Samskrit that I have by various scholars as input for testing this pipeline.

We can then have a program to label one of those phonemes in each cluster (samyuktaksharas) with the corresponding Unicode akshara text by a human. Once a phoneme is labelled, all the other phonemes in that cluster will also get the same label. We can use the LoadIQ-like technology here.

For each phoneme's audio clip, we need to also classify its pitch, amplitude and speed relative to others and output them along with the Unicode text.

## Simple speech synthesizer:

ilp_speak x.html \> x.wav

This program stitches together the individual audio clips corresponding to samyuktaksharas appearing in a unicode text stream to form an audio rendering of that stream. Clip selection might need to be context-sensitive. This is a barebones synthesizer. It can get a lot more sophisticated later.

  

|                                                                    |                                                                                                                                                                                                                                                                                                                            | |--------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:| | Google Drive: create, share, and keep all your stuff in one place. | [![Logo for Google Drive](https://ci3.googleusercontent.com/proxy/3yC1t60KzSyIrh21b2f21mUBA8MMJCsYsIoQohvM7H-ZJEurCz_g95QytNf1L0MLyjbSlA1BLngJF3W2nSCoxHfIzvGO7pIuZNnWGGVlFyDM0vczdWqO2G_w1O8OhfuhQg=s0-d-e1-ft#https://ssl.gstatic.com/docs/documents/share/images/services/google_logo-1.png)](https://drive.google.com) |

