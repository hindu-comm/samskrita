+++
title = "002 dhaval patel"

+++
[[dhaval patel	2016-06-25, 11:50:35 [Source](https://groups.google.com/g/samskrita/c/22Rds6ilNVk)]]



\> Can you please confirm what all senses are covered (प्रकृत्यां, सनि, णिचि, यङि,यङ्लुकि, etc)

Right now it is only प्रकृत्याम्. Code can generate and does generate सनादिs, but as they have not been checked, they are not included in the database. Can be added after validation. May take some 2-3 months or so.

\> Also, is there any estimate of the accuracy of the generated verb forms (e.g. 95% or 99%) or have they been cross-checked against a source like Dhaturupanandini?

This is a tricky question to answer. The methodology followed was - compare the generated verb forms against the combined database of UoHyd and INRIA.  
The forms which seemed OK to me were put in <https://github.com/drdhaval2785/SanskritVerb/blob/master/Data/okforms.txt> and verb forms which were wrong, but decided not to be handled were put in <https://github.com/drdhaval2785/SanskritVerb/blob/master/Data/notnow.txt>.  
Then the whole script was repeatedly reran until there were no forms which were not present in UoHyd, INRIA, okforms and notnow.

The logic presumes that no two data entry operators or algorithms created the same wrong forms.  
A cursory look into verb commentaries was made in specific verbs.

Not sure about accuracy though. As universe is large, some random samping of 1% may be tested and result extrapolated. Not on wishlist as of now though.

