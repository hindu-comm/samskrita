+++
title = "000 विश्वासो वासुकिजः (Vishvas Vasuki)"

+++
[[विश्वासो वासुकिजः (Vishvas Vasuki)	2017-08-06, 12:22:20 [Source](https://groups.google.com/g/samskrita/c/8F2fj9TdiMM)]]



bcc: sanskrit-programmers, samskrita and bvp groups.

  
TL;DR:[bit.ly/koshah](http://bit.ly/koshah) is a fair way to look up entries from most of the dictionaries available as part of the [stardict projects](https://github.com/sanskrit-coders?utf8=%E2%9C%93&q=stardict&type=&language=). Use it if you like.

  

\*\*\*\*\*\*\*\*\*\*\*\*\[People not interested in computer programming can stop reading now.\]\*\*\*\*\*\*\*\*\*

  

**Background**: I wanted to learn a web UI framework (mainly for my subhashita db dream project).

  

I went through some react+reflux tutorials before settling on [Polymer](https://www.polymer-project.org/) and the underlying <https://www.webcomponents.org> , since they are baked into the latest web standards and are likely to stick around for quite a while.

  

**Frameworks and Polymer**: Above all, modern UI frameworks let you write clean and clear code (no mess, better maintainability than ad-hoc js) and provide reusable components. This is quite true of polymer as well. In polymer you write a bunch of "web components" (think of them as html tags you define) which talk to each other through attributes and events. Most of what I wrote was just html-like tags, and little JS.

  

**Current status**: 

-   You'll find the code[on
    github](https://github.com/sanskrit-coders/dict-api/tree/master/docs/polymer-app). -   I tried to use "**literate programming**" (or what I understood of
    it) a concept from Donald Knuth I learned about by glancing at some
    post by shrIvatsa - so it should be slightly easy to read (or so I
    imagine). At the very least, it helped me feel more in control and
    not overwhelmed by this new technology with unsatisfactory tutorials
    and starters. -   You can **use this as a nice intro to polymer**.  

  

**Future outlook:**

-   There is no burning need for yet another multi-dictionary look up
    webapp. I only wrote this as a learning exercise, and might only add
    enhancements sporadically. But anyone interested is **welcome to
    contribute**. -   Polymer framework encourages more reuse, I think - it's a good idea
    to **separate out and publish components** from various such
    projects you might create on
    [webcomponents.org](http://webcomponents.org) .

  

---------- Forwarded message ----------  
From: **विश्वासो वासुकिजः (Vishvas Vasuki)** \<[vishvas...@gmail.com]()\>  
Date: Sat, Jun 3, 2017 at 10:16 PM  
Subject: REST-api for dictionary lookup + easily creating similar database-backed API-s.  
To: sanskrit-programmers \<[sanskrit-p...@googlegroups.com]()\>  
  
  

Copying a portion of<https://github.com/sanskrit-coders/dict-api> (see README there for other details) :

  

## Web API



-   Querying dictionary entries: use the dict_entries database and the
    index_headwords index
    -   Get a particular dictionary
        entry:[link](http://vedavaapi.org:5984/dict_entries/stardict-sanskrit__sa-head__sa-entries__amara-onto__amara-onto__0).
    -   Get a list of 10 entries starting with कटि :[get
        all](http://vedavaapi.org:5984/dict_entries/_design/index_headwords/_view/index_headwords?limit=10&reduce=false&inclusive_end=true&include_docs=true&start_key=%22%E0%A4%95%E0%A4%9F%E0%A4%BF%22)
        -   This also gives you the offset for the starting result
            (useful for randomizing, stats etc..).

### [](https://github.com/sanskrit-coders/dict-api#general-reference-and-tips)

## Motivations

(in decreasing order of importance)

-   Any web developer should be able to make simple REST-API calls to
    our backend to easily get entries for a lot of dictionaries (most of
    whom aren't already available in such manner).
    -   Imagine being able to highlight a word and use the context menu
        while reading a text to get it's meanings, grammatical info
        (linga, vibhakti, vachana, puruSha) etc..
    -   Imagine being able to make simple commentaries
        (like[this](http://www.valmikiramayan.net/utf8/baala/sarga3/bala_3_frame.htm))
        with a few mouse clicks per word (selecting the meaning most
        appropriate to the context). -   End users ( sanskrit students and scholars ) should be able to
    thoroughly investigate a term in the dictionaries using just a
    browser, without having to install any software. -   End users should be able to point out errors (eg. via a link). -   Users should be able to log in and submit new words to a "user
    dictionary" (as in
    \<[sanskritdictionary.de](http://sanskritdictionary.de)\> or
    wiktionary, but using convenience of openId and less fuss.)

## Database repilicas

-   You want to host a repilica and make things faster for folks in your
    geographical area? Just open an issue in this project and let us
    know. -   Ahmedabad, IN<http://vedavaapi.org:5984/dict_entries/_all_docs>

  

============

Postscript  
  
\* shrI kShIrasAgara is currently working on a UI which uses this API.

  
\* You have some application in mind which would benefit from a similar REST API? It's dead simple with couchdb. Please feel free to pitch your idea and design (use the README linked above as a template), we'll see if we can host it as well.

  
  

--  

--  
Vishvas /विश्वासः  
  

  
  

  

--  

--  
Vishvas /विश्वासः  
  

