+++
title = "016 Shreevatsa R"

+++
[[Shreevatsa R	2011-10-12, 21:51:52 [Source](https://groups.google.com/g/samskrita/c/3JrEFDNIIrQ)]]



I am late to this thread.Coincidentally, I read two related papers just about four weeks ago. (Further coincidence: I read them because a friend posted on Google+ a remark by Prof. Huet about Panini, similar to the remark he has posted here!)

  

The papers are(both linked from the Wikipedia article, actually):

  

1\. Economy and the Construction of theŚivasūtras byPaul Kiparsky,Stanford University

<http://www.stanford.edu/~kiparsky/Papers/siva-t.pdf>

  

and

  

2.A Mathematical Analysis of Pāṇini’s Śiva sūtras, byWiebke Petersen, University of Düsseldorf

<http://user.phil-fak.uni-duesseldorf.de/~petersen/paper/petersen_jolli_proof.pdf>

  

Both of them explain how the*śivasūtra*s can be derived just from the list of*pratyāhāra*s that are used in the grammar, and that the*śivasūtra*s are optimal.Prof. Kiparsky's paper is very readable, and he uses a few additional assumptions that he justifies as he goes along. Petersen's paper does the same without any additional assumptions.Below is a very simplified outline; I hope it is helpful to someone.

  

  

The *śivasūtra*s go like:

1\. a i u Ṇ

2.ṛ ḷ K

3\. e oṄ

4\. ai au C

...

where in each *sūtra*, the last letter is merely a "marker", and the remaining letters are actually significant.

  

From these *sūtra*s are constructed *pratyāhāra*s, the convention being that a letter followed by a marker stands for the sequence of (actual) letters starting with that letter and up to the marker. Thus

\* aṆ stands for the set {a, i, u},

\* iK stands for the set {i, u, ṛ, ḷ},

\* uṄ(not used the grammar anywhere as far as I know) stands for the set {u,ṛ, ḷ, e, o}, etc.

  

So in his grammar, whenever Panini needs to refer to a set of letters, it happens to have a convenient *pratyāhāra* like aṆor iK or whatever.

  

Everything thus far is surely known to every member of the mailing list.

  

But we can work backwards (as the Indian grammarians—Panini or earlier ones—probably did). Given the sets of letters we need in the grammar, what should the *sūtra*s be like, so as to be as short as possible (as few markers as possible)?

  

For example, we need the set {a, i, u,ṛ, ḷ} in one place (6.1.101). This only implies that these letters must occur consecutively in the sūtras, in some order, like {u,ṛ,i, a,ḷ}, say.

But we also need the set {i, u,ṛ, ḷ} in another place (1.1.3). So we are forced to put 'a' immediately before\* the set {i, u,ṛ, ḷ} (which should correspondingly start with i), and a marker after the set.

Further, we need the set {a, i, u} in another place (1.1.51), so we are forced to put u next in the set:the sūtras must look like: 

a, i, u, \[marker\], {ṛ, ḷ} \[marker\].

\[\*There is another possibility: we can put'a' immediately after the set {ṛ, ḷ, u, i}, so that it looks like {ṛ, ḷ} \[marker\], u, i \[marker\] a \[marker\], but this already uses more markers than the other case.\]

  

To summarise, even if we are given only the facts that we need to represent the following sets:

\* {ṛ,i, a,ḷ, u}

\* {u,ḷ, i,ṛ}

\* {i, a, u}(I jumbled the letters to emphasize that these are just sets)

we can *derive* (assuming that no letter is repeated, and that no markers are used unnecessarily) that two of the sūtras must look like:

1\. a i u \[marker\]

2.ṛ, ḷ\[marker\]

 or

ṛ, ḷ\[marker\].

  

Continuing in this vein, **almost the entire set of*****śivasūtra*****s can be derived**(except the markers of course, which are arbitrary) just from the list of sets that need to be represented. Kiparsky does it with a case-by-case analysis and some additional (justified) assumptions, and Petersen does it automatically, using the machinery of graph theory.

  

Now for the question about the repeated "h".

  

Sometimes, the set of sets we need to represent may simply not be amenable to arranging in a line as the sūtras do. To take a contrived example, suppose that, in addition to the three sets above, we also needed the set {a,ḷ}. Then it is impossible to fit into the above *sūtra*s, and the only way around is to repeat a letter:

1\. a i u \[marker1\]

2.ṛ ḷ\[marker2\]

3\. a \[marker3\]

so that the *pratyāhāra*"ḷ\[marker3\]" would stand for the set {ḷ, a} that we want.

  

Something similar happens with the "h", which forces it to be repeated.

On the one hand, we need the sets {i, u,ṛ, ḷ, e, o, ai, au, h, y, v, r, l} (in 1.1.69) and {a, i, u,ṛ, ḷ, e, o, ai, au, h, y, v, r} (in 8.3.3), so 'h' must occur near the vowels, somewhere between 'a' and 'l'.

On the other hand, we also need the set {ś, ṣ, s, h}, so 'h' must occur adjacent to {ś, ṣ, s} also. The only way to arrange this is to repeat 'h'.

  

Rather amazingly, it turns out (as we know) thatthat is the only repetition needed to represent all the sets of letters that are needed in the grammar and are represented as*pratyāhāra*s.

  

Here we have proved directly that 'h' needs to be repeated, but Petersen uses graph theory (non-planarity of the corresponding Hasse diagram). The linked papers also prove that the shiva sutras use the least number of markers (and therefore are shortest overall). Petersen also considers the general question (how to optimally represent an arbitrary set of sets).

  

Hope this helps rather than confuses,

Shreevatsa

  









