+++
title = "003 Ramakrishna Upadrasta"

+++
[[Ramakrishna Upadrasta	2010-08-09, 15:08:00 [Source](https://groups.google.com/g/samskrita/c/L-Lm-bnKdVE)]]



Namaste Hans,

2010/8/8 Hans Nilsson \<[ha...@hansnilsson.se]()\>:

  
\> Having started to study Panini’s grammer, and being a former IT  
\> professional, I wanted to make a structured description of his word classes  
\> and concepts. I have therefore refreshed my old knowledge of Backus-Naur

This indeed is a good work! It is very nice to read sanskrit in  
Panini-Backus form, with well known Panini rules.

You may want to know that Prof. Gerard Huet's tool Zen toolkit has  
rules in OCAML to tag sanskrit language, though it is an independent  
generic Finite State machinery to tag any language.

One can write rule in that toolkit like the following, which gives the  
rules for declension of masculine stems in -a:

value build_mas_a stem entry =  
let decline case suff = (case,fix stem suff) in  
enter entry (  
\[ Decli Mas  
\[ (Singular,if entry = "ubha" (\* dual only \*)  
\|\| entry = "g.rha" (\* plural only \*)  
\|\| entry = "daara" then \[\] else  
\[ decline Voc "a"  
; decline Nom "as"  
; decline Acc "am"  
; decline Ins "ena"  
; decline Dat "aaya"  
; decline Abl "aat"  
; decline Gen "asya"  
; decline Loc "e"  
\])  
; (Dual, if entry = "g.rha"  
\|\| entry = "daara" then \[\] else  
\[ decline Voc "au"  
; decline Nom "au"  
; decline Acc "au"  
; decline Ins "aabhyaam"  
; decline Dat "aabhyaam"  
; decline Abl "aabhyaam"  
; decline Gen "ayos"  
; decline Loc "ayos"  
\])  
; (Plural, if entry = "ubha" then \[\] else  
let l =  
\[ decline Voc "aas"  
; decline Nom "aas"  
; decline Acc "aan"  
; decline Ins "ais"  
; decline Dat "ebhyas"  
; decline Abl "ebhyas"  
; decline Gen "aanaam"  
; decline Loc "esu"  
\] in  
if pronominal_usage entry then \[ decline Nom "e" :: l \] else l)  
\]  
\] @ (if a_iic entry then \[ Inicpd (rev \[ 1 :: stem \]) \] else \[\])  
@ (if a_iiv entry then \[ Inivcpd (rev \[ 4 :: stem \]) \] else \[\]))

The above are suggested by Shri Huet himself (in private  
correspondence to me), showing the power of the existing toolkit.

In this aspect, you may want to have a look at the following page  
<http://sanskrit.inria.fr/huet/ZEN/index.html>

as well as the following page too, where I believe the declensions and  
sandhi-samaasaa-s have been automatically generated.  
<http://sanskrit.inria.fr/~anusaaraka/>

Hope this helps!  
namaste  
Ramakrishna  

