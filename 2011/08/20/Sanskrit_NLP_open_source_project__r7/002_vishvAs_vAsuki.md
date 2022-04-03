+++
title = "002 vishvAs vAsuki"

+++
[[vishvAs vAsuki	2011-08-21, 02:39:00 [Source](https://groups.google.com/g/samskrita/c/r7-8msLu00c)]]



भवतः आशीर्वचनेभ्यः मम कार्तज्ञं, श्री-हरिनारायणभट्ट-वर्य। मयि एतत् आश्चर्यं जनयति यत् जगति एकं अपि सङ्गणकः नास्ति येन पाणिनेः सूत्राणि संपूर्णतया, सम्यक् उपयुज्यन्ते!एतत् केवलं वय्याकरण-मार्गदर्शणेन भवितुं शक्यते!अहं तु व्याकर्ण-शास्त्रं न जानामि।

  

Potential contributorsare welcome to join the[sanskrit-programmers](http://groups.google.com/group/sanskrit-programmers)mailing list I just created for this sort of work (currently it is empty). Below is my assessment of the current state of Sanskrit processing work, please give me any feedback/ corrections you may have.

Natural Language Processing in general is a thriving field, with open source projects such as[openNLP](http://incubator.apache.org/opennlp/).  

Several academics have done valuable work in Sanskrit NLP. Thanks to separate conversations, I gather the following impressions. Their current aims have been to develop tools and algorithms aimed at helping a reader comprehend Sanskrit text by doing the following:

Digitize dictionaries([1](http://sanskrit1.ccv.brown.edu/tomcat/sl/Cologne)), sUtras and thesarauses([1](http://sanskrit.uohyd.ernet.in/scl/amarakosha/index.html)) and enable online search([1](http://sanskrit1.ccv.brown.edu/tomcat/sl/Cologne),[2](http://sanskrit1.ccv.brown.edu/tomcat/sl/FunderburkInterface?type=1)).[Some](http://spokensanskrit.de/)online dictionaries enable collaborative editing. They do have the followinglimitations:

-   Collaborativelyupdateddictionaries are not publicly available for
    download. -   They don't currently provide an online API (application programming
    interface) to build on them easily.

Develop tools which model and illustrate application of various sandhi([1](http://sanskrit.inria.fr/DICO/grammar.html),[2](http://sanskrit.uohyd.ernet.in/scl/sandhi/index.html)) and inflection ([1](http://sanskrit.inria.fr/DICO/grammar.html),[2](http://sanskrit.uohyd.ernet.in/Heritage/DICO/grammar.html#roots),[3](http://sanskrit1.ccv.brown.edu/tomcat/sl/VerbalMorphology),[4](http://sanskrit1.ccv.brown.edu/tomcat/sl/NominalMorphology),[5](http://sanskrit1.ccv.brown.edu/Sanskrit/software/gshell/index2.html),[6](http://sanskrit.uohyd.ernet.in/scl/skt_gen/generators.html)) rules. These can in-turn be used to analyze inflected words ([1](http://sanskrit.uohyd.ernet.in/Heritage/DICO/index.html#stemmer),[2](http://sanskrit.inria.fr/DICO/index.html#stemmer),[3](http://sanskrit1.ccv.brown.edu/tomcat/sl/FunderburkInterface?type=2),[4](http://sanskrit.uohyd.ernet.in/scl/morph/index.html)), do sandhi analysis ([1](http://sanskrit.uohyd.ernet.in/Heritage/DICO/reader.html),[2](http://sanskrit.uohyd.ernet.in/scl/sandhi_splitter/index.html)) and to produce dictionaries of inflected words ([1](http://sanskrit.inria.fr/DATA/XML/)).

-   Inflected word generation is usually based on the 'word and
    paradigm' model, close to the work such as ruupa chandrikaa which
    gives the naamaruupaavalii for 'typical' words ending in different
    var.nas in different lingas.This is found to be very useful and
    accurate in the analysis of classical Sanskrit texts. -   Limitation: However, as a generative model the above is not perfect
    because, not being based firmly on pANini's rules (which separate
    saMskR^ita from apabhraMShA), they may generate wrong inflections.  

Mechanically parsing ([1](http://sanskrit.uohyd.ernet.in/Heritage/DICO/reader.html)) Sanskrit text, doing part of speech tagging([1](http://kjc-fs-cluster.kjc.uni-heidelberg.de/dcs/index.php)).

Translating Sanskrit into a more familiar language. ([1](http://sanskrit.uohyd.ernet.in/~anusaaraka/sanskrit/sampark/))

Tools to identify metre([1](http://sanskrit.sai.uni-heidelberg.de/Chanda/HTML/list_all.html), 2).

Tools to help understand grammer sUtras ([1](http://sanskrit.uohyd.ernet.in/scl/ashtadhyayi_simulator/index.html),[2](http://sanskrit1.ccv.brown.edu/tomcat/sl/Kramapatha),[3](http://sanskritdocuments.org/learning_tools/AshtadyaayiSuutrapaaThaHAlphabeticalandNumericalarrangement.xlsx),[4](http://www.taralabalu.org/panini/),[5](http://sanskrit.sai.uni-heidelberg.de/Panini/HTML/list_all_rules.html),[6](http://www.avg-sanskrit.org/avgupload/sutras/1-1-1.html)).

Transliteration tools([1](http://sanskrit1.ccv.brown.edu/tomcat/sl/TranscodeText),[2](http://sanskrit1.ccv.brown.edu/tomcat/sl/ScriptTable),[3](http://sanskrit1.ccv.brown.edu/Sanskrit/SanskritTransliterate/index2.html),[4](http://learnsanskrit.org/tools/sanscript),[5](http://sanskritdocuments.org/processing_tools/)...), formal attempts at encoding Indian scripts in unicode([1](http://sanskrit1.ccv.brown.edu/tomcat/sl/ScriptTable)).

Sanskrit optical character recognition (OCR) tools([1](http://learnsanskrit.org/tools/ocr)).

In rare cases above source code for Sanskrit tools are available; but they are mostly not open-source; and there is quite a bit of duplication of effort; the boundless-sharing culture is mostly absent. Besides the limitations noted above, what is conspicuously missing from the above are tools directed at meeting important needs of the popular spoken Sanskrit movement, especially as we increasingly interact with information through computers and the internet.  

1.  Consuming documents and webpages written in other languages in
    saMskRRita (There is no google-translate like device at present nor
    will there be one in the near future). 2.  Sanskrit UI versions of commonly used software don't exist (Unlike
    Arabic, Hebrew..). 3.  There are no good Sanskrit browser scripts or extensions to do
    common things like look up word meanings with a click or a
    mouse-over. 4.  No effort at generating Sanskrit content easily. Eg: Sanskrit
    wikipedia is nowhere close to the english version. Same goes for the
    wiktionary.

  
--  
vishvAs  
  
  
  





> 
> > 
> > 
> > 
> > 
> >   
> > 
> >   
> > --  
> You received this message because you are subscribed to the Google > Groups "samskrita" group.  
> To post to this group, send email to [sams...@googlegroups.com]().  
> To unsubscribe from this group, send email to > [samskrita+...@googlegroups.com]().  
> For more options, visit this group at > <http://groups.google.com/group/samskrita?hl=en>.  
> > 
> > 

  

