+++
title = "002 Karthik Raman"

+++
[[Karthik Raman	2012-11-17, 20:54:27 [Source](https://groups.google.com/g/samskrita/c/nxTM2Hh5T6M)]]



Thanks a lot. This works. What are the differences (bugs!) in the MikTeX version that cause the issue? It would be great if we can fix that too. TeXLive was a painful download!

  

Further, I have another issue, w.r.t typesetting swara marks, for example a word ending in "an", and swaritam typesets incorrectly as in the attachment. Similar problems also occur with some other swara combinations.

  

It pastes correctly in word from ITranslator etc, but not in TeXworks. Some glyph issue? Am I missing something here?

  

Best,

Karthik  
  

On Thu, Nov 15, 2012 at 8:13 PM, Nityanand Misra \<[nmi...@gmail.com]()\> wrote:  

>   
> Update on this - I tried by installing TexLive 2012 today on my > Windows machine and the TexLive version of XeLaTeX successfully > printed the conjuncts. Attached is the output with Sanskrit 2003 font > for the following file.  
>   
> \\documentclass{article} >
> \\usepackage{fontspec} >
> \\setmainfont\[Script=Devanagari\]{Sanskrit 2003} >
> % \\setmainfont\[Script=Devanagari\]{Arial Unicode MS}

> 
> > \\begin{document} >
> \\fontsize{16}{18}\\selectfont >
> \\noindent आपदामपहर्तारं दातारं सर्वसम्पदाम्। \\\\ >
> लोकाभिरामं श्रीरामं भूयो भूयो नमाम्यहम्॥\\\\ >
> क्त क्य ङ्म ट्ट \\\\ >
> ॐ त्र्य ध्र्य र्त्स्न्य क्र्य \\\\ >
> \\end{document} >
>   
> > 

> Good thing is I do not need to switch to Ubuntu since all my setup > (ScanTailor, Sanskrit OCR, Jagdeep Dangi's font converters and Adobe > Acrobat) is on Windows.  
>   
> Those facing this problem on Windows, please upgrade to TeXLive 2012. > Anybody needing help with the TeXLive installation and making it work, > please feel free to contact me. I have still retained mikTeX 2.9.  
>   
> Thanks to all who responded personally and on the forum. >
> 
> >   
>   
> On Thursday, November 15, 2012 1:01:20 PM UTC+8, Parjánya wrote: >
> > Hello,  
> >   
> > Could you sent the successful PDF file?  
> >   
> > The font in the PDF you have attached isn't Sanskrit 2003, and I > > would guess it doesn't render the ligatures just because it doesn't > > have them. I would recommend you using either Sanskrit 2003 or the > > Siddhanta font, which you can find here: > > [http://svayambhava.org/index.php/en/fonts](http://svayambhava.org/index.php/en/fonts) > > .  
> >   
> > Edgard >
> 





> 
> > 
> > To view this discussion on the web visit > <https://groups.google.com/d/msg/samskrita/-/5z3-6ghgEkcJ>.



