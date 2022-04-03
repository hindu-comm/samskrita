+++
title = "005 Ambarish Sridharanarayanan"

+++
[[Ambarish Sridharanarayanan	2013-09-10, 14:50:54 [Source](https://groups.google.com/g/samskrita/c/TmZerEH_Uj0)]]





I'm afraid this is not going to help, but I can tell you why this happens. OSX provides two ways for programmers to write software on it (in software terms, two "API sets"), the old, Carbon, and the new, Cocoa. Carbon does not support correct rendering of Devanagari, and never will. Cocoa has been there for more than 10 years now, and has supported correct Devanagari text rendering for most of that time.

  

Unfortunately, most of Microsoft office still uses Carbon. Microsoft has committed to moving the software to Cocoa, and in Office for Mac 2011, Outlook already uses Cocoa and thus renders Devanagari correctly. I don't know when Microsoft will finally release an Excel written on Cocoa, but I speculate that'll be within 3 years.

  

