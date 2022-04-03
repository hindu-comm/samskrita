+++
title = "000 विश्वासो वासुकिजः (Vishvas Vasuki)"

+++
[[विश्वासो वासुकिजः (Vishvas Vasuki)	2021-07-21, 16:16:25 [Source](https://groups.google.com/g/samskrita/c/ur6Wdio79gM)]]



TO: 3 mailing lists whence rule contributions are sought  
CC: People with prior open source grammer engine creation experience, whose special review and technical comments are sought.  
BCC: Other interested people.

  

I've created a new github org and repo at <https://github.com/sandhiH/sa-rules> with the following goal:  
  
A repository of sanskrit sandhi rules (as standardized by the pANini-patanjali-kAtyAyana tradition), for shared use in sandhi-engines implemented in various programming languages. Various sandhi engines may read these toml files and construct*regular expression substitution rules*.

We anticipate that similar repositories may be constructed for sandhi rules of other languages, and other sanskrit grammatical traditions.

  

I seek technical comments (at [sankrit-programmersmailing list](https://groups.google.com/g/sanskrit-programmers)or [github issues](https://github.com/sandhiH/sa-rules/issues)) and contributions (via github pull requests) from people competent at programming and (vyAkaraNa+ regular expressions) respectively.

  

Please read <https://github.com/sandhiH/sa-rules/blob/master/README.md> and look at the comments at<https://github.com/sandhiH/sa-rules/blob/master/vowel/iko_yaN_achi__i.toml> .

  

  

  

  

  

Context: proposal in the forwarded message below (link <https://groups.google.com/g/sanskrit-programmers/c/x_K7MZi5oKI/m/js04BoW_AAAJ>) and the thread at<https://groups.google.com/g/sanskrit-programmers/c/G2PjqBmKQFw/m/ZFyayO2nAQAJ>

  

  

  

  

---------- Forwarded message ---------  
From: **विश्वासो वासुकिजः (Vishvas Vasuki)**  
Date: Thu, Jul 15, 2021 at 6:08 PM  
Subject: Transliteration and internal representation of svara-s: RFC  
To: sanskrit-programmers \<[sanskrit-p...@googlegroups.com]()\>  

PS: RFC meaning [here](https://en.wikipedia.org/wiki/Request_for_Comments).  
  
A relatively unsolved problem is one of transliterating accented texts from one scheme to another. Also allied is the problem of doing sandhi-s WHILE ALSO taking care of accents, which involves settling on a good scheme for internally representing accents.

  

Since I had to deal with (transliterating and presenting) western notation for my studies, I've made some small headway.  
  
Main idea for internal representation:

  

1\. Use devanAgarI rather than slp wx or whatever. In this day and age, programming languages can quite easily deal with devanAgarI concisely and directly despite the clumsy unicode "a" mark absence. It works well with \[2\] below (given the wide variety of accentmarking supported for that script).

2\. Use unicode sAmaveda superscript 1 to represent udAtta, 2 to represent general svarita, atharvavedic markर्यं᳡ to represent jAtya svarita, sAmaveda superscript 3 to represent sannatara, somethingelse (or nothing) for ekashruti.

  

I haven't actually tried this representation yet, but it seems quite logical and sensible (given the semantics of the symbols used).

  

This could be a good standard to adapt - so treat this as an RFC. Comments welcome.

  

  

I have used such a representation in transliterating western svara notation (without resorting to the harder problem of converting to popular sannatara-svarita-marking system - vide <https://github.com/virtualvinodh/aksharamukha/issues/86> )though - See code at this [permalink](https://github.com/sanskrit-coders/indic_transliteration/blob/d3f53444ee613e59489bca8bdddf2d64e89a0d4f/tests/data/transliterationTests.json#L116), where"tuvé asuryàṃ vásavo ní r̥ṇvan ókaso agna āja" is rendered as"तुवे꣡ असुर्यं᳡ व꣡सवो नि꣡ ऋण्वन् ओ꣡कसो अग्न आज" . Besides that python transliteration module, I've implemented it in [sanscript.js](https://github.com/sanskrit/sanscript.js/blob/d51a83abe1b8b75e6cea7eaa8abc67e6d5c6aff4/test/tests.js#L610) as well.

  

  

--  

--  
Vishvas /विश्वासः  
  

  

  

--  

--  
Vishvas /विश्वासः  
  

