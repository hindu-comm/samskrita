+++
title = "007 Shreevatsa R"

+++
[[Shreevatsa R	2012-01-16, 15:38:27 [Source](https://groups.google.com/g/samskrita/c/ujcVw9y0T2M)]]



In fact, there is an even easier way with xelatex! Just \\usepackage{fontspec} and it should cover all the IAST characters. Also, it's a good idea to put\\tracinglostchars=2 in the document (this applies to my earlier examples too), so that warnings about missing characters go to the terminal also, instead of just the log file.

  

This method misses the "m with dot above", but the standard system of transliteration (IAST) has only "m with dot above", so if you're using transliterations according to that system, you should be fine.

  

For future reference, you can also ask TeX/LaTeX related questions on <http://tex.stackexchange.com> where I've found one gets good answers very quickly.  

  

Example document (also attached):

  

\\documentclass{article}

\\tracinglostchars=2

\\usepackage{fontspec}

\\begin{document}

  

ā ī ū ṛ ṝ ḷ ḹ ṃ ḥ ṁ ṅ ñ ṭ ḍ ṇ ś ṣ

  

Ā Ī Ū Ṛ Ṝ Ḷ Ḹ Ṃ Ḥ Ṁ Ṅ Ñ Ṭ Ḍ Ṇ Ś Ṣ

  

\\end{document}

  

  
  



