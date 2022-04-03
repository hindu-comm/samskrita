+++
title = "022 Shreevatsa R"

+++
[[Shreevatsa R	2017-07-09, 19:57:26 [Source](https://groups.google.com/g/samskrita/c/sm-lW9qj0A8)]]



On Sun, Jul 9, 2017 at 3:00 AM, Pankajashree R \<[pankaj...@gmail.com]()\> wrote:  

> 
> > Thank you. I will try to use this and build a small app :)
> > 
> >   
> > 
> > 
> > Regarding the WebAPI -
> > 
> > 
> > <https://github.com/sanskrit-coders/dict-api#web-api> >
> 
> > 
> >   
> > 
> > [![](https://lh3.googleusercontent.com/-Bsq5XPnPB24/WWH9GXdbx_I/AAAAAAAAIck/yBo6zf4cfnYWAIM4Cb-yiebnxgNE8aw-QCLcBGAs/s320/Capture.PNG)](https://lh3.googleusercontent.com/-Bsq5XPnPB24/WWH9GXdbx_I/AAAAAAAAIck/yBo6zf4cfnYWAIM4Cb-yiebnxgNE8aw-QCLcBGAs/s1600/Capture.PNG) >
> 
> > Why am I not getting the characters properly for the entries on Chrome > (Version 58.54.3029.81)  
>   
> If I use Firefox, I get it properly.
> > 
> > 
> >   
> > 
> > [![](https://lh3.googleusercontent.com/-6OsdK-gRoWE/WWH-AE_4KqI/AAAAAAAAIcs/gndkL9IbNNQwCIFfwcnGz3lK79F-F75VQCLcBGAs/s320/Capturefirefox.PNG)](https://lh3.googleusercontent.com/-6OsdK-gRoWE/WWH-AE_4KqI/AAAAAAAAIcs/gndkL9IbNNQwCIFfwcnGz3lK79F-F75VQCLcBGAs/s1600/Capturefirefox.PNG) >
> 

  

It's just a character encoding issue; the bytes are there and will be usable when you parse the json.

  

The server sends its response asContent-Type:application/jsonto your browser (and indeed the response is valid JSON and intended to be consumed by programs, not read in your browser), then your browser has the task of interpreting those bytes and displaying them in the DOM. When it does that it tries to guess the character encoding, and in this case the server has returned UTF-8 but your browser has guessed ISO-8859-15. If you're writing a program you can specify the encoding and everything will be decoded into the proper Unicode characters.

  

Actually JSON strings are required to be Unicode, but the browser in this case isn't smart enough to realize that what it's seeing is JSON and factor that into its encoding-guessing. (For what it's worth, I get correct output in Chrome and similar to yours in Firefox.) I guess in this case if the server returnsContent-type: application/json; charset=utf-8then there's a greater chance of the browser guessing correctly. It should be a non-issue as the server responses aren't designed to be viewed in the browser. Or maybe the server could do that too, return either html or json depending on the request's "accept" headers.

