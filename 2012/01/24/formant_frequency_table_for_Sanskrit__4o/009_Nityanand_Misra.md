+++
title = "009 Nityanand Misra"

+++
[[Nityanand Misra	2012-01-27, 11:41:51 [Source](https://groups.google.com/g/samskrita/c/4oGLpUXyjxI)]]



Herr Doktor Hellwig  
  
Two comments and a question.  
  
First the question. Is the frequency count in the .dat file based over all texts on the DCS? The total number seems a bit low at 7,567,475. A back of the envelope calculation shows that assuming VR, MBh and Bhagavata to contain only Anushtup verses would be half of that, ie ( 24 + 18 + 100 ) \* 1000 \* 32 = 4,544,000 syllables. And that's without any Puranas, Samhitas, et cetera.  
  
The comments now.  
  
1) The version of R script you pointed out does not work, as sums is undefined

-   Error: object 'sums' not found

 The following is what the script is missing before the "for" loop, you may want to make the changes online  

-   sums \<- colSums( data\[,2:6\] )

2\) As the page rightly mentions, linear regression analysis is flawed here as the time data is categorical and not continuous. So any conclusions drawn from regression are to be taken with a grain of salt. A better way would be to use the prop.test() method in R which uses the Chi-Square test to compare proportions in several groups. I do remember seeing chi-square tests for searches on DCS though.  
  
A matrix of p-values using a five-sample Chi-square test and four two-sample Chi-square tests between successive periods is below. From what I can see, the evidence against the null hypothesis of constant probability for a group is statistically significant for all five groups, even though he evidence is most extreme for Gutturals, Retroflexes and Labials which correspond to the significant linear regression F-stats. In fact, it is interesting to see that from Medieval to Later period, only Dentals have shown a significant change in Probability with p-value less than 0.1% (a justifiable critical value given the large sample sizes), while from Epic to Classic, evidence shows that probabilities for all five groups have changed. It is also interesting to observe that the frequency of Retroflexes did not change significantly between Early (Vedic/Upanishadic) and Epic periods, but it did in the post-Epic periods.  
  

\> matpvals

 All periods Ea & Ep Ep & Cl Cl & Me
Me & La

Gutturals 0.000000e+00 3.607401e-43 0.000000e+00 0.000000e+00 1.267108e-01

Palatals 1.175834e-246 8.720096e-51 1.598550e-161 9.514065e-01 2.303646e-02

Retroflexes 0.000000e+00 3.181280e-01 6.859133e-92 1.400428e-127 3.685050e-02

Dentals 3.114376e-48 1.022459e-08 6.671614e-07 2.707000e-14 3.677069e-34

Labials 0.000000e+00 2.611753e-01 4.399987e-35 1.750870e-106 6.592439e-01

  
Lastly, while using the frequentist approach, sometimes large sample sizes are more likely result in significant test-stats, so it would be useful to try a Bayesian alternative.  
  
Thanks, Nityanand  
  







> 
> > 
> > --  
> You received this message because you are subscribed to the Google > Groups "samskrita" group.  
> To post to this group, send email to [sams...@googlegroups.com]().  
> To unsubscribe from this group, send email to > [samskrita+...@googlegroups.com]().  
> For more options, visit this group at > <http://groups.google.com/group/samskrita?hl=en>.  
>   
> > 
> > 



