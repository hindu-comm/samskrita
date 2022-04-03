+++
title = "002 Nityanand Misra"

+++
[[Nityanand Misra	2013-09-10, 05:44:41 [Source](https://groups.google.com/g/samskrita/c/TmZerEH_Uj0)]]



  
  
On Sunday, September 8, 2013 8:00:30 PM UTC+8, Raama wrote:

> 
> > 
> > 
> > Namaste All,  
> I know this is not directly related to Sanskrit but it is driving me > crazy, so thought to ask here for some help.  
> > 
> > I am attaching a screenshot of devanagari text typed in Mac-Excel and > Mac-notepad.  
>   
> > 
> > First line text typed in Mac-Excel  
> > 
> > 
> > Second line typed in Mac-Notepad.  
>   
> > 
> > 
> > For some reason excel does not render half letters correctly, has > anybody saw this issues on their Mac-Excel. I hate to type first in > Notepad and then copy into excel.  
>   
> > 
> > 
> > 

  

Sri Rama Ji

  

How are you keying in (typing) the characters?

  

If I understood you correctly, when you type into Mac-Notepad and copy-paste from Mac-Notepad to Mac-Excel, the result is fine. If that is the case, my diagnosis isthat Mac-Excel is not be able to process the typed Devanagari "combining characters". For example a "laghu i maatra" typed after a consonant must be combined to the left of the consonant, not to the right as seen in your snapshot.

  

I have no way to check as I do not use a Mac. However, to be sure, you can try this - go to this weblink<http://rishida.net/tools/conversion/>- it is a Unicode \<-> Hex conversion utility.Copy and paste the words typed in both Mac-Notepad and Mac-Excel, one by one, into the Mixed Input box and click on convert. Then see theUnicode U+hex notation output (it should be something like U+0930 U+093E U+092E forराम). Then share the output of both here.

  

I suspect the hex output may be different for the same keystrokes typed into Mac-Notepad and Mac-Excel. If that is the case, it is a bug with Mac-Excel.

  

Thanks, Nityanand

