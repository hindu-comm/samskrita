+++
title = "021 Shreevatsa R"

+++
[[Shreevatsa R	2011-09-27, 18:33:07 [Source](https://groups.google.com/g/samskrita/c/HnH0157MGVE)]]



On Tue, Sep 27, 2011 at 3:56 PM, Anunad Singh \<[anu...@gmail.com]()\> wrote:  

> Eddie Hadley mahodayaH,  
>   
> Do you mean following three lines (statements) are redundant for > offline use?  
>   
> \<script type="text/javascript" charset=UTF-8 > src="json2.js">\</script>  
> \<script type="text/javascript" charset=UTF-8 > src="convert-data-sa.js">\</script>  
> \<script type="text/javascript" charset=UTF-8 > src="convert-in.js">\</script>  
>   
> Then I do not see the statements which are responsible for all the > great conversions in this 'small' html file? I tested the program > with these three lines and without. It works with but not without (It > looks strange to me).  
>   
> Can you (or somebody else) explain the real purpose of these lines?  
>   
> -- Anunad

  

Dear Anunad,

  

I am the "author" of the transliterator in question ( <http://shreevatsa.appspot.com/sanskrit/transliterate.html> ) and I can tell you those files are very much needed (in the same directory as the HTML file, if you want to use it offline). That's where all the data and code for transliteration are.

(The first file, json2.js will not be needed once modern browsers support JSON natively. Of course it's extremely unwise to load code from servers you don't control; that's why I made a copy of the file (which is fine because it's in the public domain) and put it on the same server as the code.If you use it offline, of course, it won't load code from any server.)

  

I made this transliterator for my personal use. I did not expect others would want to use it, so I have not bothered adding instructions, testing it on browsers like IE, etc. If there is interest in using it, I can make the code available under GPL (well, it's already "available" in the sense that you can just copy it, but I mean officially add a license permitting reuse!), add a link to a download to an offline version, etc.

  

R. Ishida's converter is unrelated to mine. I just mentioned it at the top as a handy link, useful especially for characters like avagraha and danda, not covered in my transliterator.

  

Shreevatsa

