---
title: Chapter 1
layout: page
permalink: /methods
---

### Why is my evil lecturer forcing me to learn statistics?

The majority of this chapter should be a review of material from your prior classes on research methods.  

#### 1. Theory, hypothesis, and operational definitions.

> *"Theories are nets cast to catch what we call the 'world': to rationalize, to explain, and to master it. We endeavor to make the mesh ever finer and finer."* - Karl Popper

Theory is essentially the story or narrative we tell about how particular phenomenon in the world are associated.  The phenomena we refer to are called *hypothetical constructs*.  The constructs can have an infinite number of specific definitions called *operational definitions*.  For example, depression is a construct and can defined as a DSM diagnosis, through a self-report measure, etc. 

**Reliability** speaks to the stability or internal consistency for each operational definition.  **Validity** speaks to how well operational definitions relate to other operational definitions they would be expected or not expected to be associated.  


    
<strong><center>Advanced Resources</center></strong>

    Meehl, P. E. (1967). Theory-testing in psychology and physics: A methodological paradox. Philosophy of Science, 34, 103-115.
    
    Wampold, B. E., Davis, B., & Gould, R. H. (1990). Hypothesis validity of clinical research. Journal of Consulting and Clinical Psychology, 58, 360-367


#### 2. Measurement Scales

The distinction between nominal, ordinal, interval, ratio scales in scales of measurement is something you learn quite early.  However, the importance of these scales is rarely made clear.  The reason why these scales are important to understand is that they will have an impact on how you summarize, visualize, and model (run statistics) on your data.  

At the same time, the scale of measurement is inherently limiting and can you fix your mind on thinking about a problem or issue in a particular way. A good exercise is to think about the variables in your study and consider how you might assess the same constructs on a different scale.  Consider 

**2a. Arbitrary Metrics**

You should consider and review the concept of *arbitrary metrics* as another type of measurement. The point here is pretty simply.  To what extent are the variables you are measuring practical and meaningful in a way that anyone could appreciate what you're studying.   

As an example, people don't often appreciate a 5-point change on, for example, a self-report measure of depression.  Instead, they often appreciate fewer days of unemployment, having a job or not having a job, number of social events attended, number of days out of bed, etc.  The difference between these metrics is pretty clear.  Arbitrary metrics have the distinct benefit of speaking more to the concept of *ecological validity*.

In summary, it is best to consider both arbitrary and non-arbitrary metrics.  The point being that hypothetical constructs are inexhaustible entities that can be approached in a variety, infinite number of ways.  If you care about the variables that you are measuring then in makes sense to assess as exhaustively as possible.   

Questions to Consider: 

1. On what scale(s) can you imagine arbitrary metrics being measured on.


<strong><center>Advanced Resources</center></strong>

    Kazdin, A. E. (2006). Arbitrary Metrics: Implications for Identifying Evidence-Based Treatments. American Psychologist,61(1), 42-49. doi:10.1037/0003-066X.61.1.42
    
    Baumeister, R. F., Vohs, K. D. & Funder, D. C. (2007).  Psychology as the science of self-reports and finger movements: Whatever happened to actual behavior? Perspectives on Psychological Science, 2, 396-403. 

#### 3. Null Hypothesis Significance Testing (NHST)

At the very end of this chapter, in section 1.7.4 & 1.7.5, the author begins a discussion of sampling distributions similar to our class discussion using the binomial distribution.  The basic idea being that there are expected frequencies of outcomes and these outcomes can have assigned probabilities.  Many of our variables fall along a normal distribution, many do not.  If we know the distribution of outcomes, then we can guess at the probability of those outcomes.  Every time we have a new outcome, we can see how consistent or inconsistent our data is with the established frequency table (and corresponding probabilities).

Although perhaps odd to think about, the tables in the back of your statistics textbooks are nothing more than expected outcomes of test statistics (t-test, chi-square, F-test, etc.) for different sample sizes.   You compare *your* results (i.e., test statistic) with the probability of it occurring in the table in the back.  Lastly, the tables are the frequency/probabilities of outcomes when you'd expect no relationship/no effect.  It's called the **null hypothesis distribution**.

We spend *a lot* of time talking about this, its strengths, limits, and solutions to those limits in this class.  There is nothing really inherently bad about NHST, the problem is simply that it's widely misunderstood and misapplied.  As we will see, NHST is more of a ritual that has replaced critical thinking. 

**What is NHST?**

Correct definition of a p-value is as follows:

> *The probability that the observed data is consistent (or more extreme) than the null hypothesis distribution assuming additional study assumptions are met*

Here is what a p value does not tell us:

  * The probability that the null is true
  * The probability that your hypothesis is true (wouldn't that be nice to say? Go Bayesian stats!)
  * A p value less than .05 does not tell us that the null should be rejected. It just means your results are odd. We do not know why it's odd. It could not fit the null distribution or some other study assumption could've been violated
  * A p value greater than .05 does not tell us that the null should be accepted (same as above but other direction)
  * A p value less than .05 does not mean that what we found is important.
  * A p value greater than .05 does not mean that there was no effect found. 
  * The p value is not the chance of our data occurring given the null.  It's what we observed and *more extreme*, again, given other study assumptions are met.
  * The p value is not the chance of a Type I error (false positive).  The 5% is how often you would be wrong over many studies, given all assumptions are met, including the null. 


<strong><center>Advanced Resources</center></strong>

    Gigerenzer, G. (2004). Mindless statistics. The Journal of Socio-Economics,33(5), 587-606. doi:10.1016/j.socec.2004.09.033
    
    Greenland, S., Senn, S. J., Rothman, K. J., Carlin, J. B., Poole, C., Goodman, S. N., & Altman, D. G. (2016). Statistical tests, P values, confidence intervals, and power: a guide to misinterpretations. European Journal of Epidemiology,31(4), 337-350. doi:10.1007/s10654-016-0149-3
    
    