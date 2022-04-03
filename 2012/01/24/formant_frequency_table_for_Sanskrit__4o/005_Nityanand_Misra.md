+++
title = "005 Nityanand Misra"

+++
[[Nityanand Misra	2012-01-24, 18:16:19 [Source](https://groups.google.com/g/samskrita/c/4oGLpUXyjxI)]]



That is one option, but would involve a lot of manual counting (for all vowels and consonants), plus the below method may not count the ऋ in कृ as a ऋ, depending on the script.  
  
In my opinion, the right tool would be a lexer like flex on UNIX/Linux, run on the Velthuis/ITRANS/Howard Kyoto transliterated text. Some years ago I wrote one to detect typing errors of prosody in a large text by parsing the text a Velthuis transliteration as long and short syllables using the attached lex tokenizer. Something similar can be used here.



