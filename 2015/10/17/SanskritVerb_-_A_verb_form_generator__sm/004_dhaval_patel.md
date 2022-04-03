+++
title = "004 dhaval patel"

+++
[[dhaval patel	2015-10-19, 11:18:38 [Source](https://groups.google.com/g/samskrita/c/sm-lW9qj0A8)]]



absolutely yes. I tested and posted the result as well.  

The issue was that the code is in the following sequence  
  

if (starts with halAdi and for 'liT')  

{ apply processes of liT in halAdi verbs }  

if (starts with ajAdi and for 'liT')  

{ apply processes of liT in ajAdi verbs }  
  

When it started with 'vac' -> it passed the first test and the processes of liT halAdi applied. But as its result it became 'u+vac' i.e. starting with ajAdi.  

So the next process of liT ajAdi applied erraneously.  
  

What I corrected was  
  

if (starts with halAdi and for 'liT')  
{ apply processes of liT in halAdi verbs }  
elseif (starts with ajAdi and for 'liT')  
{ apply processes of liT in ajAdi verbs }





