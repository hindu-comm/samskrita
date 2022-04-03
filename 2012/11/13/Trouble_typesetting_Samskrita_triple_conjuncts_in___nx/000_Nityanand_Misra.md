+++
title = "000 Nityanand Misra"

+++
[[Nityanand Misra	2012-11-13, 16:20:51 [Source](https://groups.google.com/g/samskrita/c/nxTM2Hh5T6M)]]



Namaste

  

I have typeset Samskrita documents in pdfLaTeX in the past using Charles Wikner's skt package. I recently shifted to XeLaTeX and love it so far since I can type Unicode straight into the document without bothering about any preprocessor.

  

I am on Windows using MikTeX 2.9 with TeXWorks 0.4.3. I find that triple conjuncts like त्र्य, ध्र्य and क्र्य are not rendered properly. So far I have only noted conjucts with 'r' in the middle but there may be others. Here is my xelatex file

  

\\documentclass{article}

\\usepackage{fontspec}

% \\setmainfont\[Script=Devanagari\]{Sanskrit 2003}

\\setmainfont\[Script=Devanagari\]{Arial Unicode MS}

\\begin{document}

\\fontsize{16}{18}\\selectfont

\\noindent आपदामपहर्तारं दातारं सर्वसम्पदाम् \\\\

लोकाभिरामं श्रीरामं भूयो भूयो नमाम्यहम् \\\\

\\\\

क्त क्य ङ्म ट्ट \\\\

ॐ त्र्य ध्र्य र्त्स्न्य क्र्य \\\\

\\end{document}

  

And the attached PDF is what I get after running XeLaTeX where the triple conjuncts in the last line are messed up.

  

Some Googling landed me at discussion which said that because there conjuncts are in the private area of Unicode, which creates some problems on Windows but works fine on Ubuntu. As a discussion is 3-year old, I guess many things may have changed.

  

Does anybody know of any Windows XeLaTeX setup (e.g. TeX Live) which can process these characters successfully? Or can anybody working on XeLaTeX on non-Windows platform try to see if their setup produces them correctly - I know several people on the forum use XeLaTeX. Can they help me with the OS and TeX distribution details which works for these?

  

Thanks, Nityanand  

  
--  
Nityānanda Miśra  
Member, Advisory Council, Jagadguru Rambhadracharya Handicapped University  
Chitrakoot, Uttar Pradesh, India  
<http://nmisra.googlepages.com>  
<http://jagadgururambhadracharya.org/donate.php>  
  
\|\| आत्मा तत्त्वमसि श्वेतकेतो \|\|  
(Thou art from/for/of/in That Ātman, O Śvetaketu)  
  - Ṛṣi Uddālaka to his son, Chāndogyopaniṣad 6.8.7, The Sāma Veda  

