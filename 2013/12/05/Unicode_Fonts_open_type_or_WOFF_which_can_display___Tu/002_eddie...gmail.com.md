+++
title = "002 eddie...@gmail.com"

+++
[[eddie...@gmail.com	2013-12-06, 05:18:24 [Source](https://groups.google.com/g/samskrita/c/Tu__p8HE0TI)]]



  

Karan,

  

 WOFF is not any kind of font, legacy or otherwise.

  

A far as I can tell, it is simply a new(ish) data file compression format, specifically designed to compress web pages.

  

I quote from the official WOFF docs: (search for WOFF)

  

"This document specifies a simple compressed file format for fonts, designed primarily for use on the Web and known as WOFF (Web Open Font Format).

Despite this name, WOFF should be regarded as a container format or "wrapper" for font data in already-existing formats rather than an actual font format in its own right."

  

  

If thedata so wrapped, is already Unicode savvy, I would assume its ready to go.

  

But material, in legacy fonts (XDVNG, Times_CSX+ etc. etc.)requirestherecipient tohave the exact samefont manually installedon his machine. It wouldstill be ready to go, butwithquite a high probabilityof on-page garbage characters!

  

  

Legacy font conversion utilities.

  

To this end, many free software packages are available to use, on and off line, to makethe conversion from old to new.

However, eachlegacy font has to be individually remapped to the UTF standard (UCSTransformation Format)

whereUSC= Universal Character Set

  

It's theUniversal Character Set,that makes all things garbage free, readable to all men, anywhere.

  

Now,another however: Legacy font conversion utilities are a mixed bag.

  

A whileago Iwrote two-way conversions for my own use (using .NET C#),for the aforementioned, including one toautomatically distinguish the one from the other and thus do such jobs in one go.

  

Now, these things are tricky, they can have their quirks (i.e. they can be buggy).

Theso called professionalpackages, likewise, have their limitations, re. accents, ligatures, etc. (and bugs . . .).

  

I would therefore suggest that you gather a fewrecommendations fromother publishers andevaluate themagainst your particular requirements

(the packages, not the publishers (:-)

  

As for howto WOOF the universalisedproduct . . ..

  

 Taff Rivers  

