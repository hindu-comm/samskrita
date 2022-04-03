+++
title = "005 कार्त्तिकेयः"

+++
[[कार्त्तिकेयः	2021-07-08, 22:13:54 [Source](https://groups.google.com/g/samskrita/c/swlJvnJjIL4)]]



  

16x-15y = 0 has solutions x = k.15, y = k.16 for any integer k. There are no other solutions.

  

Now what if he has r flowers left over at the end?  
16x - 15y = r

  

This can be rearranged as (15y + r)/16 = x

  

This is a case of an indeterminate equation (ay + r)/b = x that can be solved by Aryabhata's कुट्टक  

  

Using the कुट्टक , we get the solutions as y = r + k.16 and x = r + k.15 for any integer k in this case (we're helped by the fact that b=a+1, so it simplifies a bit).

  

The general case is harder, but straightforward using कुट्टक. ‌I'll describe Bhaskaracharya's simplified form:  

  

भाज्यो हारः क्षेपकश्चापवर्त्यः केनाप्यादौ सम्भवे कुट्टकार्थम् ।

येनच्छिन्नौ भाज्यहारौ न तेन क्षेपश्चेत् तद्दुष्टमुद्दिष्टमेव ॥

First divide the dividend, divisor and remainder by their common factors. If both the dividend and divisor have a common factor that does not divide the remainder, then the equation cannot be solved

In (ax + r)/b=y, Bhaskaracharya calls a as the dividend, b as the divisor, and r as the remainder. What we see is that the common factor of a and b must divide r for this to have integral solutions (as is evident by inspection)

परस्परं भाजितयोः ययोर्यः शेषस्तयोस्स्यादपवर्तनं सः ।

तेनापवर्तेन विभाजितौ यौ तौ भाज्यहारौ दृढसंज्ञितौ स्तः ॥

Find the common factor of the dividend and divisor by repeated division, first of the dividend by divisor, then by the division of the divisor by the remainder received, and then of the remainder of that division by the previous divisor. Divide the dividend and divisor by the penultimate remainder before a zero is obtained. Such dividend and divisor are called “reduced”

This is the same as is taught in schools as “Euclid’s Algorithm”, to find the Greatest Common Divisor (GCD) - also called Highest Common Factor (HCF) - of two numbers. We find the GCD of a and b, and divide a, b, and r by that GCD. If it does not divide r, we stop here and declare that the equation has no solution. We call this the reduced form of the equation.

  

मिथो भजेत्तौ दृढभाज्यहारौ यावद्विभाज्ये भवतीह रूपम् ।

फलान्यधोऽधस्तदधो निवेश्यः क्षेपस्तथान्ते खमुपान्तिमेन ॥

स्वोर्ध्वे हतेऽन्त्येन युते तदन्त्यं त्यजेन्मुहुः स्यादिति राशियुग्मम् ।

ऊर्ध्वो विभाज्येन दृढेन तष्टः फलं गुणः स्यादधरो हरेण ॥

एवं तदैवात्र यदा समास्ताः स्युर्लब्धयश्चेद्विषमास्तदानीम् ।

यथागतौ लब्धिगुणौ विशोध्यौ स्वतक्षणाच्छेषमितौ तु तौ स्तः ॥

  

Divide repeatedly the dividend and divisor, then the divisor of each division by the remainder of that until 1 is obtained as a remainder. Place the quotients of division in a column, write the remainder below, and zero below that.

Reduce this column of numbers by the following process. Multiply the penultimate number by the one above it, add the last number, and place the result in place of the number above the penultimate number. Delete the last number. Repeat the process till two numbers remain.   
Take the top number, abrade by the dividend (abrade = divide and take the remainder). This is the factor of the divisor. Take the number below, and abrade by the divisor. This is the factor of the dividend.

If the number of quotients is odd, subtract the two results from their respective abraders.  

इष्टाहतस्वस्वहरेण युक्ते ते वा भवेतां बहुधा गुणाप्ती ॥

By adding desired multiples of the respective abraders, any number of solutions may be generated

There are more simplifications, tricks, examples etc. in Līlāvatī



