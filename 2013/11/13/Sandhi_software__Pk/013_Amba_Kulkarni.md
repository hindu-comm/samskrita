+++
title = "013 Amba Kulkarni"

+++
[[Amba Kulkarni	2013-11-13, 19:17:30 [Source](https://groups.google.com/g/samskrita/c/PkaUX9y5uWQ)]]



> 
> > 
> > 
> > 
> > Ma'am, I would be highly obliged if the source code can be shared.
> > 
> > 
> > 
> > 
> > 
> > > 
> > > > 
> > > > 
> > > > 
> > > > 
> > > > 
> > > > The same sandhi joiner is given to TDIL as a part of the consortium > > project, and is on TDIL website.  
> >   
> > > > 
> > > > There is another sandhi joiner developed by Prof. Gérard Huet > > <http://sanskrit.inria.fr>  
> >   
> > > > 
> > > > What is required is collaboration. In 2006 when I noticed that Prof > > Huet is also working in this direction, we started collaborating > > with each other to avoid any duplication of efforts. This also > > resulted in a consortium for Sanskrit Computational Linguistics, > > which has organised 5 conferences till now, and has led to many more > > collaborative efforts both at the national as well as international > > level.  
> >   
> > Prof Huet has already developed a very sophisticated practical > > sandhi splitter (segmenter), > > > > 
> > > > 
> > 
> >   
> > 
> > 
> > 
> > I would love to see the source code / algorithm for the same.
> > 
> > 
> > 
> > 

The algorithms are discussed in the published papers available at <http://yquem.inria.fr/~huet/bib.html>.  

> 
> > 
> > 
> > 
> > 
> >   
> > 
> > > 
> > > > 
> > > > and at the university of Hyderabad, we have developed a parser > > (sentential analyser). Further, these tools also interact with each > > other, i.e. I can use heritage segmenter to split the Sanskrit > > sentence into words, which then can be passed on my parser for > > kaaraka level analysis. > > > > 
> > > > 
> > 
> >   
> > 
> > 
> > 
> > I would love to see the source code / algorithm for both. >
> 
> > 
> > 
> > 
> > 
> > 
> > 
> > 

Again all the algorithms are available in the published papers available at <http://sanskrit.uohyd.ernet.in/faculty/amba>  

> 
> > 
> > 
> > 
> > 
> > 
> > 
> > > 
> > > > 
> > > > This is possible only through the collaboration.  
> >   
> > > > 
> > > > 
> > 
> >   
> > 
> > 
> > 
> > I Agree.
> > 
> > 
> > 
> > 
> > 
> > > 
> > > > 
> > > > 
> > > > 
> > > > On the one side there is a necessity to join the hands together, so > > that there are no duplication of efforts.  
> > > > 
> > > > 
> > > > On the other hand, the researchers may like to develop the same tool > > following different algorithms. For example, if we take English > > language, there are dozens of parsers for English being developed > > following different approaches. Many of them are available either > > under open source, or for reasearch purpose, or as an online tool.  
> >   
> > > > 
> > > > 
> > > > What I observe is many enthusiasts start the work on Sanskrit, but > > once they encounter the complexity the language poses, their > > enthusiasm dies.  
> >   
> > > > 
> > > > 
> > > 
> > > > 
> > > > 
> > > > 
> > > > Now coming back to Sri Dhaval Patel ji's efforts. I see that what he > > is trying to do is something different from the way I have done > > it.  
> > > > 
> > > > 
> > > > He is trying to develop an algorithm, where he is ordering the > > sandhi rules manually.  
> > > > 
> > > > 
> > > > The way I have implemented is just a simple ready-made matrix. This > > I needed to invert the rules quickly.  
> >   
> > > > 
> > > > 
> > 
> >   
> > 
> > 
> > 
> > Would you please elaborate what is meant by 'simple ready-made > matrix' ?
> > 
> > 
> > 
> > 

The sandhi process is represented as a matrix where the row heading represent the last character(s) of the first word and the column represents the first character(s) of the second word,and the corresponding cell represents the output along with the sandhi rules.  
  

If you look at the programme and the readme file which I had sent you,
it will be clear.  

  

> 
> > 
> > 
> > 
> > 
> > 
> > 
> > > 
> > > > 
> > > > 
> > > > 
> > > > But as a researcher I'll be more interested in knowing how the order > > in the Ashtadhyayi itself can trigger the order of the rules.  
> > > > 
> > > > 
> > 
> >   
> > 
> > 
> > 
> > Would you please elaborate this ordering issue ? This is interesting. >
> 
> > 
> > 
> > 

  

You may refer to Prof Paul Kiparsky's papers, especially
<http://www.stanford.edu/~kiparsky/Papers/hyderabad.pdf> and <http://www.stanford.edu/~kiparsky/Papers/siddha.new.pdf>.  
  

> 
> > 
> > 
> > 
> > 
> > 
> > 
> > > 
> > > > 
> > > > 
> > > > 
> > > > Is it necessary to use 'paribhaashaa's such as 'nitya-antaranga...' > > etc. > > > > 
> > > > 
> > 
> >   
> > 
> > 
> > 
> > Do you mean that the machine should be able to understand what is to > be done when we tell it 'iko yaNaci' ?
> > 
> > 
> > If yes, this is an interesting aspect. I have done a few functions in > the code which are in a way telling the comp the same thing. >
> 
> > 
> > e.g. prat('hl') will tell the computer that it has to take the whole > pratyAhAra starting from h and ending at l. >
> 
> > 
> > Similarly savarna (prat('Jl'),prat('cr')) will tell the computer to > give the savarna of the pratyAhAra झल्‌ from the pratyAhAra चर्‌. >
> 
> > 
> > 
> > 
> > 
> > 
> > 
> > 
> > 

Similar efforts are also done by Ananda Mishra and Peter Scharf earlier. Their papers are available in the proceedings of Sanskrit Computational Linguistics Symposium.  
  

  

> 
> > 
> > 
> > 
> > > 
> > > > 
> > > > So I myself will be implementing sandhi joiner in a different way.  
> > > > 
> > > > 
> > > >   
> > > > 
> > > > 
> > > 
> > > > 
> > > > 
> > > > 
> > > > I would welcome more such efforts, which will revive the Paninian > > tradition,and at the same time I also welcome the collaboration, and > > sharing of resources to avoid duplication of efforts.  
> >   
> > > > 
> > > > 
> > 
> >   
> > 
> > 
> > 
> > I would be sharing whatever I can do and keep the list posted about > it. >
> 
> > 
> > The code is in nascent stage. There are around 50 known issues. I am > trying to create a page where it will be proactively disclosed. >
> 
> > 
> > 
> > 
> > 
> > 
> > 

  

Thanks and regards,  
Amba Kulakarni  
  





