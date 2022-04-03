+++
title = "006 Taff Rivers"

+++
[[Taff Rivers	2016-03-07, 06:56:39 [Source](https://groups.google.com/g/samskrita/c/-jY1xl65ZUs)]]



shankara,

  

> 
> > 
> > Re. environment variables - a technical subject. >
> 
> > 
> > 
> > 
> >   
> > 
> > 
> > 
> > 
> >  %appdata%\\GoldenDict\\article-style.css >
> 
> > 
> > 
> > 
> >   
> > 
> > 
> > 
> > 
> > Simply doesn't work! >
> 
> > 



> 
> > 
> >   
> > 
> > 
> > 
> > 
> > This %appdata%, it is an environment variable. It is not a folder. >
> 
> > 
> > 
> > 
> >   
> > 
> > 
> > 
> > 
> >   
> > 
> > 
> > 
> > 
> > An environment variable, if present, will refer to a text string. >
> 
> > 
> > 
> > 
> > In this case, the string should be that of an actual directory path. >
> 
> > 
> > 
> > 
> > Looking something like this: >
> 
> > 
> > 
> > 
> >   "C:\\Users\\Eddie\\AppData\\Roaming\\GoldenDict\\". >
> 
> > 
> > 
> > 
> >   
> > 
> > 
> > 
> > 
> > under which the user is to place his "article-style.css" file. >
> 
> > 
> > 
> > 
> >   
> > 
> > 
> > 
> > 
> >   
> > 
> > 
> > 
> > 
> > But... >
> 
> > 
> > 
> > 
> >   
> > 
> > 
> > 
> > 
> > There are many 'applications' along with their individual data files. > 
> > 
> > 
> > 
> > 
> > Leading to a complex of directory paths... >
> 
> > 
> > 
> > 
> >   
> > 
> > 
> > 
> > 
> > Directory of C:\\Users\\Eddie\\AppData >
> 
> > 
> > 
> > 
> >   
> > 
> > 
> > 
> > 
> > 10/01/2016 15:00  \<DIR>     IObit >
> 
> > 
> > 
> > 
> > 06/03/2016 15:43  \<DIR>     Local >
> 
> > 
> > 
> > 
> > 27/01/2016 10:45  \<DIR>     LocalLow >
> 
> > 
> > 
> > 
> > 06/03/2016 12:19  \<DIR>     Roaming >
> 
> > 
> > 
> > 
> > 28/03/2014 00:12  \<DIR>     System >
> 
> > 
> > 
> > 
> >   
> > 
> > 
> > 
> > 
> > ... and subdirectories >
> 
> > 
> > 
> > 
> >   
> > 
> > 
> > 
> > 
> > C:\\Users\\Eddie\\AppData\\Roaming\\OpenOffice\\ >
> 
> > 
> > 
> > 
> >   
> > 
> > 
> > 
> > 
> > None of which depend on the long outated DOS environment variable > system. >
> 
> > 
> > 
> > 
> > The above directiores are all created by the Application's own > intstallation files. >
> 
> > 
> > 
> > 
> >   
> > 
> > 
> > 
> > 
> > I have an up to date GoldenDict, and an up to date Windows 2015 Pro, > 64-bit. >
> 
> > 
> > 
> > 
> >   
> > 
> > 
> > 
> > 
> > I see but three %appdata% environment variables in my environment: >
> 
> > 
> > 
> > 
> > (environment variables are not case sensitive)
> > 
> > 
> > 
> > 
> >   
> > 
> > 
> > 
> > 
> > C_GETSET_ENVAR_SAMPLE exists in User >
> 
> > 
> > 
> > 
> > MOZ_PLUGIN_PATH C:\\PROGRAM FILES (X86)\\FOXIT SOFTWARE\\FOXIT > READER\\plugins\\ >
> 
> > 
> > 
> > 
> > Path C:\\Users\\Eddie\\AppData\\Roaming\\OCamlPro\\OCPWin32\\bin >
> 
> > 
> > 
> > 
> > TEMP C:\\Users\\Eddie\\AppData\\Local\\Temp >
> 
> > 
> > 
> > 
> > TMP C:\\Users\\Eddie\\AppData\\Local\\Tmp >
> 
> > 

  

Not a GoldenDict in sight!

  

  

  Taff Rivers



