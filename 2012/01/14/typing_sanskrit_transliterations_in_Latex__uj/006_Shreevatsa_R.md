+++
title = "006 Shreevatsa R"

+++
[[Shreevatsa R	2012-01-16, 14:27:56 [Source](https://groups.google.com/g/samskrita/c/ujcVw9y0T2M)]]



Dear Prof.Voevodsky,

  

Sorry for the incomplete answer last time. The problem is that the defaultfont does not contain theā character.

  

1\. So you have to set the default font to a font that covers the characters you need.

To do this you need the two lines "\\usepackage{xltxtra}" and "\\setmainfont{DejaVu Serif}" (or some other font that contains the characters).

I have attached a minimal example as example-1.tex.

  

2\. If you don't want to change the font for the entire document, you can change it for just the Sanskrit transliterations. I have attached an example as example-2.tex.

  

3\. Actually, because there are only a few letters with diacritics in the standard Sanskrit transliteration, you can just use plain LaTeX instead of xelatex; in place of the characters

  

ā ī ū ṛ ṝ ḷ ṃ ḥ ṅ ñ ṭ ḍ ṇ ś ṣ

  

use

  

\\={a} \\={\\i} \\={u} \\d{r} \\d{\\={r}} \\d{l} \\d{m} \\d{h} \\.{n} \\\~{n} \\d{t} \\d{d} \\d{n} \\'{s} \\d{s}

  

(note the \\={\\i} instead of \\={i}, so that you don't get a dot over i).

  

Out of these, the\\usepackage\[utf8\]{inputenc} helps only withñ andś, so it's not much useful.

  

I have attached this as example-3.tex. And to save you the trouble of converting from Unicode characters to LaTeX-appropriate input, I've just written<http://shreevatsa.appspot.com/transliteration/iast2tex.html>where you can enter the Unicode characters on the left and get the corresponding LaTeX input on the right.

  

Hope this helps,

Shreevatsa



