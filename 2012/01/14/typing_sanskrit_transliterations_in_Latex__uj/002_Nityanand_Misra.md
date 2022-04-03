+++
title = "002 Nityanand Misra"

+++
[[Nityanand Misra	2012-01-15, 11:57:43 [Source](https://groups.google.com/g/samskrita/c/ujcVw9y0T2M)]]



Vladimir  
  
You chose wisely to post here. I have gone through many painful nights while typesetting Sanskrit in LaTeX and can help you with this \[and hopefully any more issues\].  
  
Latex can only process ASCII so even if you save the doc in Unicode format, it would not help. To type ā, simply enter the sequence \\={a}. All diacritics, be it IAST or French or German can be accomplished in LaTeX using similar commands. For an example with several diacritics, see the attached input LaTeX file and output PDF generated using pdflatex.  
  
If you have to type IAST many times over in LaTeX, this could be very annoying. In that case, you may want to use the "skt" package for LaTeX. Refer [this page](http://www.tex.ac.uk/tex-archive/language/sanskrit/ps-type1/sktdoc.pdf) for more details. Essentially you type in blocks which begin with tags like "{\\skt " et cetera, and then pass this document to a preprocessor which outputs a tex file which can be processed using pdflatex or latex. Personally I find the skt package good for IAST rendition, but the devnagari rendition is not very pretty - the glyphs are nowehere near print quality fonts like APS DV Priyanka.  
  
For any other hiccups, feel free to follow up.  
  
Thanks, Nityanand  
  





> --  
> You received this message because you are subscribed to the Google > Groups "samskrita" group.  
> To post to this group, send email to [sams...@googlegroups.com]().  
> To unsubscribe from this group, send email to > [samskrita+...@googlegroups.com]().  
> For more options, visit this group at > <http://groups.google.com/group/samskrita?hl=en>.  
>   

  
  
  
--  
Nityānanda Miśra  
<http://nmisra.googlepages.com>  
  
\|\| आत्मा तत्त्वमसि श्वेतकेतो \|\|  
(Thou art from/for/of/in That Ātman, O Śvetaketu)  
  - Ṛṣi Uddālaka to his son, Chāndogyopaniṣad 6.8.7, The Sāma Veda  

