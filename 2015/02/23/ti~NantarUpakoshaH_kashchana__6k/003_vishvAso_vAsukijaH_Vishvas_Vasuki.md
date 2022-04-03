+++
title = "003 विश्वासो वासुकिजः (Vishvas Vasuki)"

+++
[[विश्वासो वासुकिजः (Vishvas Vasuki)	2015-02-25, 21:22:20 [Source](https://groups.google.com/g/samskrita/c/6kvUHtJfzQE)]]



+sanskrit-programmers

  

2015-02-24 19:13 GMT-08:00 Sandeep Nangia \<[sandeep...@gmail.com]()\>:  

> 
> > Looks like the dictionary updater crashes with Android 4.4.4 on Nexus > 4. It would be great if this issue can be fixed. This would be so > useful! I downgraded recently from Lollipop version because I had too > many issues with Nexus 4.  
> > 



I know of this issue ( <https://github.com/sanskrit-coders/stardict-dictionary-updater/issues/1>), but am completely befuddled by it. I am [including all](https://github.com/sanskrit-coders/stardict-dictionary-updater/blob/master/app/build.gradle#L42) the recommended libraries, yet we have this missing class. Looking on the internet has not helped so far. If someone has any solution, please let me know.



> 
> >   
> Any pointers to an alternate way to install this dictionary file would > be useful too.  
> > 

  

Here are instructions I had written down earlier, which include a workaround

  



Ubuntu Linux:

Install goldendict with:  
sudo apt-get install goldendict .

  

Android:  
\* Install the goldendict app. (The paid version is worth it - you will be able to use as many dictionaries as you like. Further, it is more stable than colordict - as of 2015.)

\* To install dictionaries, there are several strategies:  
\*\* You can use an app such as<https://play.google.com/store/apps/details?id=sanskritcode.sanskritdictionaryupdater>to install some common dictionaries in one shot.



\*\* You can use the Colordict app to install dictionaries (instructions are provided here -<http://www.aupasana.com/software/stardict-android>). Sometimes, this method is known to fail. Goldendict will pick up dictionaries installed by this method.



\*\*You can install the dictionaries is by downloading the XYZ.tar.gz files, and extracting them (using an app like ZArchiver) to the corresponding SDCARD/dictdata/XYZ folder (which can be created using a file manager app such as TotalCommander).



