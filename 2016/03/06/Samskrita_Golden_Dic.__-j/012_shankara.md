+++
title = "012 shankara"

+++
[[shankara	2016-03-07, 12:17:37 [Source](https://groups.google.com/g/samskrita/c/-jY1xl65ZUs)]]



Murthyji,

  

Giving below the steps that I followed in Windows 7 to change font and layout of Goldendict. I don't know about other versions of Windows or Mac.  

  

1. Paste the following into a notepad (text file).

  

body  
{  
 margin-top: 1px;  
 margin-right: 3px;  
 margin-left: 2px;  
 margin-bottom: 3px;  
 background: white;  
 font-family: Siddhanta;  
 font-size:18px;  
}  
  

2. Paste the following in the 'save as' field and save the file.  
%appdata%\\GoldenDict\\article-style.css  
  
3. Open the following folder (replace \*\*\*\* with your Windows username).  
C:\\Users\\\*\*\*\*\\AppData\\Roaming\\GoldenDict  
  
4. You will find a text file named 'article-style.css' in this folder. Rename it to 'article-style'.  
  
5. In Windows folder options, disable 'hide known file extensions'.  

Now, change the file extension of the text file to css. i.e. article-style.txt to article-style.css.  
  
6. Now, restart goldendict and the new setting will come into effect.



regards  
shankara

  
  

------------------------------------------------------------------------

**From:** G S S Murthy \<[murt...@gmail.com]()\>  
**To:** "[sams...@googlegroups.com]()" \<[sams...@googlegroups.com]()\>  
**Sent:** Monday, 7 March 2016 11:57 AM





