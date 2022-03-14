

# Effect Sizes and Confidence Intervals {#effectsizesCI}

GRAB INTRO TEXT FROM MY EFFECT SIZE PAPER. UPDATE EXCERSIS TO CALCULATE EFFECT SIZES FROM SPREADSHEET TO MOTE. SPLIT OFF CONFIDENCE INTERVAL SECTION, and add BAYESIAN ESTIMATION to that section on confidence intervals



## Effect sizes

What is the most important outcome of an empirical study? You might be tempted to say it’s the *p*-value of the statistical test, given that it is practically always reported in articles, and determines whether we call something ‘significant’ or not. However, as Cohen @cohen_things_1990 writes in his 'Things I’ve learned (so far)':

>I have learned and taught that the primary product of a research inquiry is one or more measures of effect size, not *p*-values.

Although what you want to learn from your data is different in every study, and there rarely is any single thing you always want to know, effect sizes are a very important part of the information we gain from data collection. A measure of effect size is a quantitative description of the strength of a phenomenon. It is expressed as a number on a scale, and which scale is used depends on the effect size measure that is used. For **unstandardized effect sizes**, we can use a scale that people are very familiar with. For example, children grow on average 6 centimeters a year between the age of 2 and puberty. We can interpret 6 centimeters a year as an effect size. It is obvious an effect size has many benefits over a *p*-value. A *p*-value gives an indication that it is very unlikely children stay the same size as they become older – effect sizes tell us what size clothes we can expect children to wear when they are a certain age, and how long it will take before their new clothes are too small. 

Researchers often report **standardized effect sizes** because many psychological variables are not measured on a scale people are familiar with, or are often measured on different scales. If you ask people how happy they are, an answer of ‘5’ will mean something very different if you asked then on a scale from 1 to 5 than if you asked them on a scale from 1 to 9. Standardized effect sizes allow researchers to present the magnitude of the reported effects in a standardized metric. Therefore, standardized effect sizes can be understood and compared regardless of the scale that was used to measure the dependent variable. Such standardized effect sizes allow researchers to communicate the practical significance of their results (the practical consequences of the findings for daily life), instead of only reporting the statistical significance (how surprising is the data, given the assumption that there is no effect in the population).

Standardized effect sizes also allow researchers to draw **meta-analytic conclusions** by comparing standardized effect sizes across studies. In a meta-analysis, researchers look at the results of a large number of studies and calculate the average effect size across studies to draw more reliable conclusions. Finally, standardized effect sizes from previous studies can be used when planning a new study. An **a-priori power analysis** can provide an indication of the average sample size a study needs to observe a statistically significant result with a desired probability.

It is important to make a distinction between ‘**statistically significant**’ and ‘**substantially interesting**’. For example, we might be able to reliably measure that on average, men who are 19 years old will grow another 20 millimeters before they are 21. This difference might very well be statistically significant, but if you go shopping for clothes when you are a 19-year old man, it is not something you need to think about. The most important way to evaluate whether an effect is substantially interesting is to look at the effect size.

### The Facebook experiment

In the summer of 2014 there were some concerns about an experiment Facebook had performed on its users to examine ‘emotional mood contagion’, or the idea that people’s moods can be influenced by the mood of people around them. You can read the article [here](http://www.pnas.org/content/111/24/8788.full). For starters, there was substantial concern about the ethical aspects of the study, primarily because the researchers who performed the study had not asked **informed consent** from the participants in the study (you and me), nor did they ask for permission from the **institutional review board** (or ethics committee) of their university.

One of the other criticisms on the study was that it could be dangerous to influence people’s mood. As Nancy J. Smyth, dean of the University of Buffalo’s School of Social Work wrote on her [Social Work blog](https://njsmyth.wordpress.com/2014/06/29/did-facebooks-secret-mood-manipulation-experiment-create-harm/): “There might even have been increased self-harm episodes, out of control anger, or dare I say it, suicide attempts or suicides that resulted from the experimental manipulation. Did this experiment create harm? The problem is, we will never know, because the protections for human subjects were never put into place”.

If this Facebook experiment had such a strong effect on people’s mood that it made some people commit suicide who would otherwise not have committed suicide, this would obviously be problematic. So let us look at the effects the manipulation Facebook used had on people a bit more closely.

From the article, let’s see what the researchers manipulated:

>Two parallel experiments were conducted for positive and negative emotion: One in which exposure to friends’ positive emotional content in their News Feed was reduced, and one in which exposure to negative emotional content in their News Feed was reduced. In these conditions, when a person loaded their News Feed, posts that contained emotional content of the relevant emotional valence, each emotional post had between a 10% and 90% chance (based on their User ID) of being omitted from their News Feed for that specific viewing.

Then what they measured:

>For each experiment, two dependent variables were examined pertaining to emotionality expressed in people’s own status updates: the percentage of all words produced by a given person that was either positive or negative during the experimental period. In total, over 3 million posts were analyzed, containing over 122 million words, 4 million of which were positive (3.6%) and 1.8 million negative (1.6%).

And then what they found:

>When positive posts were reduced in the News Feed, the percentage of positive words in people’s status updates decreased by B = −0.1% compared with control [t(310,044) = −5.63, P \< 0.001, Cohen’s d = 0.02], whereas the percentage of words that were negative increased by B = 0.04% (t = 2.71, P = 0.007, d = 0.001). Conversely, when negative posts were reduced, the percent of words that were negative decreased by B = −0.07% [t(310,541) = −5.51, P \< 0.001, d = 0.02] and the percentage of words that were positive, conversely, increased by B = 0.06% (t = 2.19, P \< 0.003, d = 0.008).

Here, we will focus on the negative effects of the Facebook study (so specifically, the increase in negative words people used) to get an idea of whether there is a risk of an increase in suicide rates. Even though apparently there was a negative effect, it is not easy to get an understanding about the size of the effect from the numbers as mentioned in the text. Moreover, the number of posts that the researchers analyzed was really large. With a large sample, it becomes important to check if the size of the effect is such that the finding is substantially interesting, because with large sample sizes even
minute differences will turn out to be statistically significant (we will look at this in more detail below). For that, we need a better understanding of “effect sizes”.

Now that we realize why effect sizes are important, let us look more closely at the most commonly used effect sizes, and how these are calculated.

Effect sizes can be grouped into two families [@rosenthal_contrasts_2000]: The **d family** (based on standardized mean differences) and the **r family** (based on measures of strength of association). Conceptually, the *d* family effect sizes are based on a comparison between the difference between the observations, divided by the standard deviation of these observations. This means that a Cohen’s *d* = 1 means the standardized difference between two groups equals one standard deviation. The *r* family effect sizes are based on the proportion of variance that is explained by group membership (e.g., a correlation of *r* = 0.5 indicates 25% (*r*2) of the variance is explained by the difference between groups). Don’t worry if you do not exactly get what this means at this point. The crucial issue is that we need to understand how to interpret the size of an effect, and that there are different ways to express the size of this effect.

## Cohen’s *d* {#cohend}

The size of the effect in the Facebook study is given by the statistic Cohen’s *d* (which we will discuss in more detail below). Cohen’s *d* (the *d* is italicized) is used to describe the standardized mean difference of an effect. This value can be used to compare effects across studies, even when the dependent variables are measured in different ways, for example when one study uses 7-point scales to measure dependent variables, while the other study uses 9-point scales, or even when completely different measures are used, such as when one study uses self-report measures, and another study used physiological measurements.

Cohen’s *d* ranges from 0 to infinity. Before we get into the statistical details, let’s first visualize what a Cohen’s d of 0.001 (as was found in the Facebook study) means.

We will use a vizualization from <http://rpsychologist.com/d3/cohend/>, a website made by Kristoffer Magnusson, that allows you to visualize the differences between two measurements (such as the increase in negative words used by the Facebook user when the number of positive words on the timeline was reduced). 

<div class="figure" style="text-align: center">
<img src="images/rpsychd1.png" alt="A vizualization of 2 groups (although the difference is hardly visible) representing d = 0.001." width="100%" />
<p class="caption">(\#fig:rpsychd1)A vizualization of 2 groups (although the difference is hardly visible) representing d = 0.001.</p>
</div>

Below the vizualization on the website, you can read some ways to interpret Cohen’s d in non-mathematical terms (the summary is provided about a number of people, but in the Facebook study, we are examining numbers of words). It says "Moreover, in order to have one more favorable outcome in the treatment group compared to the control group, we need to treat 3570.4 people on average." This means in the Facebook study a person needs to type 3570 words before 1 word will be more negative instead of positive. I don't know how often you type this amount of words on Facebook, but I think we can agree this effect is not noticeable on an individual level.

This illustrates the difference between a statistical difference and practical significance (or substantial interest). The effect is so small that it is unlikely to be noticeable for a single individual. Hence, in this case, and without further evidence, we would not worry too much about the extra suicides the research could have caused. Nevertheless, even such small effects can matter in other kinds of research. If an intervention makes people spend more money with a *d* = 0.001, and you have millions of transactions a year, a very small effect might very well make you a lot of money.

A large meta-analytic effort by Richard, Bond, and Stookes-Zoota (2003) estimated the median effect size in psychological studies to have a Cohen’s d = 0.43. Let’s use the vizualization to get a feeling for this effect size.

<div class="figure" style="text-align: center">
<img src="images/rpsychd2.png" alt="A vizualization of 2 groups representing d = 0.43." width="100%" />
<p class="caption">(\#fig:rpsychd2)A vizualization of 2 groups representing d = 0.43.</p>
</div>

Assume we know that people are more likely to comply with a large request after an initial smaller request, than when you ask the large request directly (this is known as the foot-in-the-door effect), and that in a specific context this effect size is 0.43. Given this effect size, how likely is it that a random person drawn from the ‘small initial request condition’ will be more likely to agree with your larger request, compared to a person in the ‘no initial small request’ condition? We see in Figure \@ref(fig:rpsychd2) that this *probability of superiority* is 61.9%.

<div class="figure" style="text-align: center">
<img src="images/rpsychd3.png" alt="A vizualization of 2 groups representing d = 2." width="100%" />
<p class="caption">(\#fig:rpsychd3)A vizualization of 2 groups representing d = 2.</p>
</div>

Based on [this data](http://www.nature.com/pr/journal/v73/n3/full/pr2012189a.html), the difference between the height of 21-year old men and women in The Netherlands is approximately 13 centimeters (in an unstandardized effect size), or a standardized effect size of *d* = 2. If I pick a random man and a random woman walking down the street in my hometown of Rotterdam, how likely is it that the man will be taller than the woman? We see this is quite (92.1%) likely. But even with a huge effect size, which is much larger than most effects researchers study, there is still considerable overlap in the two distributions. If we conclude the length of people in one group is larger than the length of people in another group, this does not mean everyone in one group is larger than everyone in the other group! 

To understand Cohen’s *d*, let’s first look at the formula for the
*t*-statistic:

$$
t = \frac{{\overline{M}}_{1}{- \overline{M}}_{2}}{\text{SD}_{\text{pooled}} \times \sqrt{\frac{1}{n_{1}} + \frac{1}{n_{2}}}}
$$

Here $${\overline{M}}_{1}{- \overline{M}}_{2}$$ is the difference between the means, and $$\text{SD}_{\text{pooled}}$$ is the pooled standard deviation (see Lakens, 2013), and n1 and n2 are the sample sizes of the two groups you are comparing. The *t*-value (because it follows a known distribution) is used to determine whether the difference between two groups in a *t*-test is statistically significant. The formula for Cohen’s *d* is very similar:

Cohen’s *d* = $$\frac{{\overline{M}}_{1}{-\overline{M}}_{2}}{\text{SD}_{\text{pooled}}}$$

You can calculate Cohen’s *d* by hand from the independent samples *t*-value (which can often be convenient when the result section of the paper you are reading does not report effect sizes) through:

$$d = t ⨯ \sqrt{\frac{1}{n_{1}} + \frac{1}{n_{2}}}$$

As you can see, the sample size is part of the formula for a *t*-value, but it is not part of the formula for Cohen’s *d*. Let’s assume the difference between two means we observe is 1, and the pooled standard deviation is also 1. What, on average, happens to the *t*-value and Cohen’s *d*, as we would simulate studies, as a function of the sample size in these simulations? Given the mean difference and standard deviation, as the sample size becomes
bigger, the *t*-value become larger, and Cohen’s *d* gets closer to the true
value. That is, whereas the *t*-value (and the corresponding *p*-value) increase as a function of the sample size, Cohen's d only becomes more accurate. This makes *p*-values a function of the sample size, when there is a true effect, and this means *p*-values can not be used to make a statement about whether an effect is *practically significant*. Reporting and interpreting the effect size will inform you about the practical significance of an effect, and therefore it is almost always beneficial to report effect sizes alongside any statistical test.

### Correcting for Bias

Population effect sizes are almost always estimated on the basis of samples, and as a measure of the population effect size estimate based on sample averages, Cohen’s *d* overestimates the true population effect (when Cohen’s *d* refers to the population, the Greek letter δ is often used). Therefore, corrections for bias are used (even though these corrections do not always lead to a completely unbiased effect size estimate). In the *d* family of effect sizes, the correction for bias in the population effect size estimate of Cohen’s δ is known as Hedges’ *g* (although different people use different names – *d_unbiased* is also used). This correction for bias is only really noticeable in small sample sizes, but since we often use software to calculate effect sizes anyway, it makes sense to always report Hedge’s *g* instead of Cohen’s *d*.

A commonly used interpretation of Cohen’s *d* is to refer to effect sizes as small (*d* = 0.2), medium (*d* = 0.5), and large (*d* = 0.8) based on benchmarks suggested by Cohen (1988) – note, in the video I talk about d = 0.3 being a small effect size, but 0.2 is the benchmark for a small effect as specified by Cohen). However, these values are arbitrary and should not be interpreted too rigidly. Furthermore, small effect sizes can have large consequences, such as an intervention that leads to a reliable reduction in suicide rates with an effect size of *d* = 0.1. On the other hand, you have to start somewhere in getting a feeling for effect sizes, and these benchmarks are a good starting point.

An interesting, though not often used, interpretation of differences between groups can be provided by the common language effect size [@mcgraw_common_1992], also known as the probability of superiority. It expresses the probability that a randomly sampled person from one group will have a higher observed measurement than a randomly sampled person from the other group (for between designs) or the other measurement (for within-designs) the probability that an individual has a higher value on one measurement than the other. We used it earlier and it is provided by the website that visualizes Cohen’s d.

## *r* (correlations) 

The second effect size that is widely used is *r*. You might remember that *r* is used to refer to a correlation. The correlation of two continuous variables can range from 0 (completely unrelated) to 1 (perfect positive relationship) or -1 (perfect negative relationship). Obviously, given the flexibility of human behavior (free will has a lot to do with it) correlations between psychological variables are rarely 1. The median effect size *r* in psychology is (for what such an estimate is worth) .21 [@richard_one_2003]. As mentioned earlier, the *r* family effect sizes describe the proportion of variance that is explained by the independent variable, or $r^2$.

Earlier, I mentioned the average effect size in psychology is *d* = 0.43. You might, therefore, think a *d* = 0.43 and an *r* = .21 should be related somehow, and they are:

$r = \frac{d_s}{\sqrt{{d_s^{2}}^{+}\frac{N^{2} - 2N}{n_{1} \times n_{2}}}}$

The subscript s underneath Cohen’s *d* is used to specify this Cohen’s *d* is calculated based on the sample, not based on the population. This is almost always the case (except in simulation studies, where you can set the effect size in the population), and *N* is the total sample size of both groups, whereas n1 and n2 are the sample sizes of the two groups you are comparing. You can go to <http://rpsychologist.com/d3/correlation/> to look at a good visualization of the proportion of variance that is explained by group membership, and the relationship between *r* and *r*2. 

Effect sizes can be implausibly large. Let’s take a look at a study that actually examines the number of suicides – as a function of the amount of country music played on the radio. You can find the paper [here](http://sf.oxfordjournals.org/content/71/1/211.short) (for [a free PDF version, click here](http://www.fourcornersdailypost.com/UserFiles/File/2011/CountryMusicSuicide.pdf)). It won an [Ig Nobel prize for studies that first make you laugh, and then think](http://www.abc.net.au/science/articles/2004/10/01/1211441.htm). I guess in this case the study should make you think about the importance of interpreting effect sizes.

The authors predicted the following:

>We contend that the themes found in country music-foster a suicidal mood among people already at risk of suicide and that it is thereby associated with a high suicide rate.

Then they collected data:

> Our sample is comprised of 49 large metropolitan areas for which data on music were available. Exposure to country music is measured as the proportion of radio airtime devoted to country music. Suicide data were extracted from the annual Mortality Tapes, obtained from the Inter-University Consortium for Political and Social Research (ICPSR) at the University of Michigan. The dependent variable is the number of suicides per 100,000 population.

And they concluded:

>A significant zero-order correlation was found between white suicide rates and country music (r = .54, p \< .05). The greater the airtime given to country music, the greater the white suicide rate.

Cohen (1988) has provided benchmarks to define small (*r* = 0.1), medium (*r* = 0.3), and large (*r* = 0.5) effects. This means the effect of listening to country music on suicide rates is large. Remember that it is preferable to relate the effect size to other effects in the literature instead of to these benchmarks. What do you think of the likelihood that listening to country music is strongly associated with higher suicide rates? Is country music really that bad? Probably not - which demonstrates the importance of not just reporting, but also interpreting, the effect size. 

If you were doubtful about the possibility that this effect was real, you might not be surprised by the fact that [other researchers were not able to reproduce the analysis of the original authors](http://sf.oxfordjournals.org/content/74/1/327.short). It is likely that the results are spurious, or a Type 1 error.

Eta squared η² (part of the *r* family of effect sizes, and an extension of r that can be used for more than two sets of observations) measures the proportion of the variation in Y that is associated with membership of the different groups deﬁned by X, or the sum of squares of the effect divided by the total sum of squares:

$\eta^{2}$ = $\frac{\text{SS}_{\text{effect}}}{\text{SS}_{\text{total}}}$

An η² of .13 means that 13% of the total variance can be accounted for by group membership. Although η² is an efficient way to compare the sizes of effects within a study (given that every effect is interpreted in relation to the total variance, all η² from a single study sum to 100%), eta squared cannot easily be compared between studies, because the total variability in a study (SStotal) depends on the design of a study, and increases when additional variables are manipulated (e.g., when independent variables are added). Keppel (1991) has recommended partial eta squared ($\eta_{p}^{2}$) to improve the comparability
of effect sizes between studies, which expresses the sum of squares of the effect in relation to the sum of squares of the effect and the sum of squares of the error associated with the effect. Partial eta squared is calculated as:

$\eta_{p}^{2}$ = $\frac{\text{SS}_{\text{effect}}}{\text{SS}_{\text{effect}}
+ \text{SS}_{\text{error}}}$

For designs with fixed factors (manipulated factors, or factors that exhaust all levels of the independent variable, such as alive vs. dead), but not for designs with measured factors or covariates, partial eta squared can be computed from the *F*-value and its degrees of freedom [@cohen_statistical_1988]:   

$\eta_{p}^{2}$ =$\frac{F \times \text{df}_{\text{effect}}}{{F \times
\text{df}}_{\text{effect}} + \text{df}_{\text{error}}}$

For example, for an *F*(1, 38) = 7.21, $\eta_{p}^{2}$ = 7.21 ⨯ 1/(7.21 ⨯ 1 +
38) = 0.16.

Eta squared can be transformed into Cohen’s *d*:

*d* = 2$\times f$ where $f^{2} = \eta^{2}/(1 - \eta^{2})$

As with Cohen’s *d*, η² is a biased estimate of the true effect size in the
population. Two less biased effect size estimates have been proposed, epsilon
squared $\varepsilon^{2}$ and omega squared $\omega^{2}$. Because these
effect sizes are less biased, it is always better to use them. Partial epsilon
squared and partial omega squared can be calculated based on the *F*-value and
degrees of freedom.

$$
\omega_{p}^{2} = \frac{F - 1}{F + \ \frac{\text{df}_{\text{error}} + 1}{\text{df}_{\text{effect}}}}
$$

$$
\varepsilon_{p}^{2} = \frac{F - 1}{F + \ \frac{\text{df}_{\text{error}}}{\text{df}_{\text{effect}}}}
$$

For further reading about effect size estimates, see [this practical primer](http://journal.frontiersin.org/article/10.3389/fpsyg.2013.00863/full) I
have written [@lakens_calculating_2013].

## Effect Sizes and Statistical Power


Based on our recent [preprint](https://psyarxiv.com/baxsf/) explaining power analysis for ANOVA designs, in this post I want provide a step-by-step mathematical overview of power analysis for interactions. These details often do not make it into tutorial papers because of word limitations, and few good free resources are available (for a paid resource worth your money, see [Maxwell, Delaney, & Kelley, 2018](https://designingexperiments.com/)). This post is a bit technical, but nothing in this post requires more knowledge than multiplying and dividing numbers, and I believe that for anyone willing to really understand effect sizes and power in ANOVA designs digging in to these details will be quite beneficial. There are three take-home messages in this post. 

1) In power analyses for ANOVA designs, you should always think of the predicted pattern of means. 
2) Understanding how patterns of means relate to the effect you predict is essential to design an informative study.
3) Always perform a power analysis if your want to test a predicted interaction effect, and always calculate the effect size based on means, sd's, and correlations, instead of plugging in a 'medium' partial eta squared. 
4) Crossover interaction effects have large effects and can thus be studies with high power in smaller samples, and if your theory can predict crossover interactions, such experiments might be worthwhile to design.
5) There are some additional benefits of examining interactions (risky predictions, generalizability, efficiently examining multiple main effects) and it would be a shame if the field is turned away from examining interactions because they sometimes require large samples.

### Getting started: Comparing two groups

We are planning a two independent group experiment. We are using a validated measure, and we know the standard deviation of our measure is approximately 2. We are interested in observing a mean difference of 1 or more, because smaller effects would not be practically meaningful. We expect the mean in the conrol condition to be 0, and therefore want the mean in the intervention group to be 1 or higher.

This means the standardized effect size is the mean difference, divided by the standard deviation, or 1/2 = 0.5. This is the Cohen's d we want to be able to detect in our study:

\begin{equation}
d = \frac{m_1-m_2}{\sigma} =  \frac{1-0}{2} = 0.5.
\end{equation}

An independent *t*-test is mathematically identical to an *F*-test with two groups. For an *F*-test, the effect size used for power analyses is Cohen's *f*, which is a generalization
of Cohen’s d to more than two groups (Cohen, 1988). It is calculated based on the standard deviation of the population means divided by the population standard deviation which we know for our measure is 2), or: 

\begin{equation}
f = \frac{\sigma _{ m }}{\sigma}
\end{equation}
where for equal sample sizes,
\begin{equation}
\sigma _{ m } = \sqrt { \frac { \sum_ { i = 1 } ^ { k } ( m _ { i } - m ) ^ { 2 } } { k } }.
\end{equation}

In this formula *m* is the grand mean, k is the number of means, and m_i is the mean in each group. The formula above might look a bit daunting, but calculating Cohen's f is not that difficult for two groups. 

If we take the expected means of 0 and 1, and a standard deviation of 2, the grand mean (the *m* in the formula above) is (0 + 1)/2 = 0.5. The formula says we should subtract this grand mean from the mean of each group, square this value, and sum them. So we have (0-0.5)^2 and (1-0.5)^2, which are both 0.25. We sum these values (0.25 + 0.25 = 0.5), divide them by the number of groups (0.5/2 = 0.25) and take the square root, we find that $\sigma_{ m }$ = 0.5. We can now calculate Cohen's f (remember than we know $\sigma$ = 2 for our measure): 

\begin{equation}
f = \frac{\sigma _{ m }}{\sigma} = \frac{0.5}{2} = 0.25
\end{equation}

We see that for two groups Cohen's f is half as large as Cohen's d, or $f = \frac{1}{2}d$, which always holds for an *F-test with two independent groups. 

Although calculating effect sizes by hand is obviously an incredibly enjoyable thing to do, you might prefer using software that performs these calculations for you. Here, I will use our Superpower power analysis package (developed by Aaron Caldwell and me). The code below uses a function from the package that computes power analytically for a one-way ANOVA where all conditions are manipulated between participants. In addition to the effect size, the function will compute power for any sample size per condition you enter. Let's assume you have a friend who told you that they heard from someone else that you now need to use 50 observations in each condition (n = 50), so you plan to follow this trustworthy advice. We see the code below returns a Cohen's *f* of 0.25, and also tells us we would have 61.78% power if we use a preregistered alpha level of 0.03.


```r
design <- Superpower::ANOVA_design(
  design = "2b", 
  n = 50, 
  mu = c(1, 0), 
  sd = 2)
```

<img src="05-effectsizeCI_files/figure-html/unnamed-chunk-2-1.png" width="100%" style="display: block; margin: auto;" />

```r
Superpower::power_oneway_between(design, alpha_level = 0.03)$Cohen_f
```

```
## [1] 0.25
```

```r
Superpower::power_oneway_between(design, alpha_level = 0.03)$power
```

```
## [1] 61.78474
```

We therefore might want to increase our sample size for our planned study. Using the `plot_power` function, we can see we would pass 90% power with 100 observations per condition.


```r
Superpower::plot_power(design, alpha_level = 0.03, min_n = 45, max_n = 150)$plot_ANOVA
```

<img src="05-effectsizeCI_files/figure-html/unnamed-chunk-3-1.png" width="100%" style="display: block; margin: auto;" />

```
## Achieved Power and Sample Size for ANOVA-level effects
##   variable                  label  n achieved_power desired_power
## 1        a Desired Power Achieved 97          90.16            90
```

<img src="05-effectsizeCI_files/figure-html/unnamed-chunk-3-2.png" width="100%" style="display: block; margin: auto;" />

### Interaction Effects

So far we have explained the basics for effect size calculations (and we have looked at statistical power) for 2 group ANOVA designs. Now we have the basis to look at interaction effects.

One of the main points in this blog post is that it is better to talk about interactions in ANOVAs in terms of the pattern of means, standard deviations, and correlations, than in terms of a standarized effect size. The reason for this is that, while for two groups a difference between means directly relates to a Cohen's d, widely different patterns of means in an ANOVA will have the same Cohen's *f*. In my experience helping colleagues out their with power analyses for ANOVA designs, talking about effects in terms of a Cohen's *f* is rarely a good place to start when thinking about what your hypothesis predicts. Instead, you need to specify the predicted pattern of means, have some knowledge about the standard deviation of your measure, and then calculate your predicted effect size. 

There are two types of interactions, as visualized below. In an ordinal interaction, the mean of one group ("B1") is always higher than the mean for the other group ("B2"). Disordinal interactions are also known as 'cross-over' interactions, and occur when the group with the larger mean switches over. The difference is important, since another main takeaway of this blog post is that, in two studies where the largest simple comparison has the same effect size, a study with a disordinal interaction has much higher power than a study with an ordinal interaction. Thus, if possible, you will want to design experiments where an effect in one condition flips around in the other condition, instead of an experiment where the effect in the other condition just disappears. I personally never realized this before I learned how to compute power for interactions, and never took this simple but important fact into account. Let's see why it is important.

### Calculating effect sizes for interactions

<img src="05-effectsizeCI_files/figure-html/unnamed-chunk-4-1.png" width="100%" style="display: block; margin: auto;" />

Mathematically the interaction effect is computed as the cell mean minus the sum of the grand mean, the marginal mean in each condition of one factor minus the grand mean, and the marginal mean in each condition for the other factor minus grand mean (see Maxwell et al., 2017).

Let's consider two cases, one where we have a perfect disordinal interaction (the means of 0 and 1 flip around in the other condition, and are 1 and 0) or an ordinal interaction (the effect is present in one condtion, 0 and 1, but disappears in the other condition, with means 0 and 0). We can calcuate the interaction effect as follows. First, let's look at the interaction in a 2x2 matrix:

<img src="05-effectsizeCI_files/figure-html/unnamed-chunk-5-1.png" width="100%" style="display: block; margin: auto;" />

```
##    a1 a2
## b1  1  0
## b2  0  1
```

The grand mean is (1 + 0 + 0 + 1) / 4 = 0.5.

We can compute the marginal means for A1, A2, B1, and B2, which is simply averaging per row and column, which gets us for the A1 row (1+0)/2=0.5. For this perfect disordinal interaction, all marginal means are 0.5. This means there are no mean effects. There is no main effect of factor A (because the marginal means for A1 and A2 are both exactly 0.5), nor is there a main effect of B.

We can also calculate the interaction effect. For each cell we take the value in the cell (e.g., for a1b1 this is 1) and compute the difference between the cell mean and the additive effect of the two factors as:

1 - (the grand mean of 0.5 + (the marginal mean of a1 minus the grand mean, or 0.5 - 0.5 = 0) + (the marginal mean of b1 minus the grand mean, or 0.5 - 0.5 = 0)). Thus, for each cell we get:

a1b1: 1 - (0.5 + (0.5 -0.5) + (0.5 -0.5)) = 0.5

a1b2: 0 - (0.5 + (0.5 -0.5) + (0.5 -0.5)) = -0.5

a2b1: 0 - (0.5 + (0.5 -0.5) + (0.5 -0.5)) = -0.5

a2b2: 1 - (0.5 + (0.5 -0.5) + (0.5 -0.5)) = 0.5

Cohen's $f$ is then $f = \frac { \sqrt { \frac { 0.5^2 +-0.5^2 + -0.5^2 + 0.5^2 } { 4 } }}{ 2 } = 0.25$

or in R code: `sqrt(((0.5)^2 +(-0.5)^2 + (-0.5)^2 + (0.5)^2)/4)/2 = 0.25`.

For the ordinal interaction the grand mean is (1 + 0 + 0 + 0) / 4, or 0.25. The marginal means are a1: 0.5, a2: 0, b1: 0.5, and b2: 0.

Completing the calculation for all four cells for the ordinal interaction gives:

a1b1: 1 - (0.25 + (0.5 -0.25) + (0.5 -0.25)) = 0.25

a1b2: 0 - (0.25 + (0.5 -0.25) + (0.0 -0.25)) = -0.25

a2b1: 0 - (0.25 + (0.0 -0.25) + (0.5 -0.25)) = -0.25

a2b2: 0 - (0.25 + (0.0 -0.25) + (0.0 -0.25)) = 0.25

Cohen's $f$ is then $f = \frac { \sqrt { \frac { 0.25^2 +-0.25^2 + -0.25^2 + 0.25^2 } { 4 } }}{ 2 } = 0.125$.

or in R code: `sqrt(((0.25)^2 +(-0.25)^2 + (-0.25)^2 + (0.25)^2)/4)/2 = 0.125`.


We see the effect size of the cross-over interaction (*f* = 0.25) is twice as large as the effect size of the ordinal interaction (*f* = 0.125). 

If the math so far was a bit too much to follow, there is an easier way to think of why the effect sizes are halved. In the disordinal interaction we are comparing cells a1b1 and a2b2 against a1b2 and a2b1, or (1+1)/2 vs. (0+0)/2. Thus, if we see this as a *t*-test for a contrast, it is clear the mean difference is 1, as it was in the simple effect we started with. For the ordinal interaction, we have (1+0)/2 vs. (0+0)/2, so the mean difference is halved, namely 0.5. 

### Power for interactions

All of the above obviously matters for the statistical power we will have when we examine interaction effects in our experiments. Let's use Superpower to perform power analyses for the disordinal interaction first, if we would collect 50 participants in each condition. 


```r
design <- Superpower::ANOVA_design(
  design = "2b*2b", 
  n = 50, 
  mu = c(1, 0, 0, 1), 
  sd = 2)
```

<img src="05-effectsizeCI_files/figure-html/unnamed-chunk-6-1.png" width="100%" style="display: block; margin: auto;" />

```r
Superpower::ANOVA_exact(design, alpha_level = 0.03)
```

```
## Power and Effect sizes for ANOVA tests
##      power partial_eta_squared cohen_f non_centrality
## a    3.000                0.00  0.0000            0.0
## b    3.000                0.00  0.0000            0.0
## a:b 91.055                0.06  0.2525           12.5
## 
## Power and Effect sizes for pairwise comparisons (t-tests)
##                       power effect_size
## p_a_a1_b_b1_a_a1_b_b2 61.78        -0.5
## p_a_a1_b_b1_a_a2_b_b1 61.78        -0.5
## p_a_a1_b_b1_a_a2_b_b2  3.00         0.0
## p_a_a1_b_b2_a_a2_b_b1  3.00         0.0
## p_a_a1_b_b2_a_a2_b_b2 61.78         0.5
## p_a_a2_b_b1_a_a2_b_b2 61.78         0.5
```

```
## Power and Effect sizes for ANOVA tests
##      power partial_eta_squared cohen_f non_centrality
## a    3.000                0.00  0.0000            0.0
## b    3.000                0.00  0.0000            0.0
## a:b 91.055                0.06  0.2525           12.5
## 
## Power and Effect sizes for pairwise comparisons (t-tests)
##                       power effect_size
## p_a_a1_b_b1_a_a1_b_b2 61.78        -0.5
## p_a_a1_b_b1_a_a2_b_b1 61.78        -0.5
## p_a_a1_b_b1_a_a2_b_b2  3.00         0.0
## p_a_a1_b_b2_a_a2_b_b1  3.00         0.0
## p_a_a1_b_b2_a_a2_b_b2 61.78         0.5
## p_a_a2_b_b1_a_a2_b_b2 61.78         0.5
```

First let's look at the Power and Effect size for the pairwise comparisons. Not surprisingly, these are just the same as our original t-test, given that we have 50 observations per condition, and our mean difference is either 1, or a Cohen's d of 0.5 (in which case we have 61.78% power) or the mean difference is 0, and we have no power (because there is no true effect) but we wil observe significant results 3% of the time because we set our apha level to 0.03.

Then, let's look at the results for the ANOVA. Since there are no main effects in a perfect crossover interaction, we have a 3% Type 1 error rate. We see the power for the crossover interaction between factor a and b is 91.06%. This is much larger than the power for the simple effects. The reason is that the contrast that is equal to the test of the interaction is based on all 200 observations. Unlike the pairwise comparisons with 50 vs 50 observations, the contrast for the interaction has 100 vs 100 observations. Given that the effect size is the same (*f* = 0.25) we end up with much higher power. 

If you have heard that it is impossible to find a statistically significant interaction without huge sample size, you clearly see this is wrong. Power *can* be higher than for the simpe effect - but this depends on the pattern of means underlying the interaction. If possible, design studies where your theory predicts a perfect crossover interaction.


For the ordinal interaction, our statistical power does not look that good based on an a-priori power analysis. SUperpower tells us we have 33.99% power for the main effects and interaction (yes, we have exactly the same power for all three - if you think about the three contrasts that are tested, these have the same effect size). 


```r
design <- Superpower::ANOVA_design(
  design = "2b*2b", 
  n = 50, 
  mu = c(1, 0, 0, 0), 
  sd = 2)
```

<img src="05-effectsizeCI_files/figure-html/unnamed-chunk-7-1.png" width="100%" style="display: block; margin: auto;" />

```r
Superpower::ANOVA_exact(design, alpha_level = 0.03)
```

```
## Power and Effect sizes for ANOVA tests
##       power partial_eta_squared cohen_f non_centrality
## a   33.9869              0.0157  0.1263          3.125
## b   33.9869              0.0157  0.1263          3.125
## a:b 33.9869              0.0157  0.1263          3.125
## 
## Power and Effect sizes for pairwise comparisons (t-tests)
##                       power effect_size
## p_a_a1_b_b1_a_a1_b_b2 61.78        -0.5
## p_a_a1_b_b1_a_a2_b_b1 61.78        -0.5
## p_a_a1_b_b1_a_a2_b_b2 61.78        -0.5
## p_a_a1_b_b2_a_a2_b_b1  3.00         0.0
## p_a_a1_b_b2_a_a2_b_b2  3.00         0.0
## p_a_a2_b_b1_a_a2_b_b2  3.00         0.0
```

```
## Power and Effect sizes for ANOVA tests
##       power partial_eta_squared cohen_f non_centrality
## a   33.9869              0.0157  0.1263          3.125
## b   33.9869              0.0157  0.1263          3.125
## a:b 33.9869              0.0157  0.1263          3.125
## 
## Power and Effect sizes for pairwise comparisons (t-tests)
##                       power effect_size
## p_a_a1_b_b1_a_a1_b_b2 61.78        -0.5
## p_a_a1_b_b1_a_a2_b_b1 61.78        -0.5
## p_a_a1_b_b1_a_a2_b_b2 61.78        -0.5
## p_a_a1_b_b2_a_a2_b_b1  3.00         0.0
## p_a_a1_b_b2_a_a2_b_b2  3.00         0.0
## p_a_a2_b_b1_a_a2_b_b2  3.00         0.0
```

If you have heard people say you should be careful when designing studies predicting interaction patterns because you might have very low power, this is the type of pattern of means they are warning about. Maxwell, Delaney, and Kelley (2018) discuss why power for interactions is often smaller, and note interactions effects are often smaller in the real world, and we often examine ordinal interactions. This might be true. But in experimental psychology it might be possile to think about hypotheses that predict disordinal interactions. In addition to the fact that such predictions are often theoretically riskier and more impressive (after all, many things can make an effect go away, but without your theory it might be difficult to explain why an effect flips around) they also have larger effects and are easier to test with high power.

Some years ago other blog posts by [Uri Simonsohn](http://datacolada.org/17) and [Roger Giner-Sorolla](https://approachingblog.wordpress.com/2018/01/24/powering-your-interaction-2/) did a great job in warning researchers they need large sample sizes for ordinal interactions, and my post repeats this warning. But it would be a shame if researchers would stop examining interaction effects. There are some nice benefits studying interactions, such as 1) making riskier theoretical predictions, 2) greater generalizability (if there is no interaction effect, you might show a main effect operates across different conditions of a second factor) and 3) if you want to study two main effects it is more efficient to do this in a 2x2 design than in two seperate designs (Maxwell, Delaney, & Kelley, 2018). So maybe this blog post has been able to highlight some scenarios where examining interaction effects is still beneficial.



## Confidence Intervals{#confint}

As Kelley and Rausch @kelley_sample_2006 explain, it is misleading to report point estimates without illustrating the uncertainty surrounding that estimate. Pretending as if the outcome of your statistical test is the final and exact answer is misleading, and you should always communicate the remaining uncertainty when you report statistical analyses. Here, we will examine this question in detail by learning how to think about, calculate, and report confidence intervals around estimates from samples.

### Population vs. Samples

In statistics, we differentiate between the population and the sample. The population is everyone you are interested in, such as all people in the world, elderly who are depressed, or people who buy innovative products. Your sample is everyone you were able to measure from the population you are interested in. We similarly distinguish between a parameter and a statistic. A parameter is a characteristic of the population, while a statistic is a characteristic of a sample. Sometimes, you have data about your entire population. For example, we have measured the height of all the people who have ever walked on the moon. We
can calculate the average height of these twelve individuals, and so we know the true parameter. We do not need inferential statistics. However, we do not know the average height of all people who have ever walked on the earth. Therefore, we need to estimate this parameter, using a statistic based on a sample. 

In addition to the goal of observing a significant difference in a study (for example a *p* \< .05), researchers can have the goal of estimating a parameter accurately (regardless of whether this estimate differs from the null-hypothesis or not). Confidence intervals can be calculated around any statistic in your data.

Confidence intervals are a statement about the percentage of confidence intervals that contain the true parameter value. This behavior of confidence intervals is nicely visualized on this website by Kristoffer Magnusson: <http://rpsychologist.com/d3/CI/>. We see blue dots that represent means from a sample, fall around a red vertical line, which represents the true value of the parameter in the population. We see the blue dots do not always fall exactly on the red line. This illustrates the important fact that there is always variation in samples.

The horizontal lines around the blue dots are the confidence intervals. By default, the visualization shows 95% confidence intervals. Most of the lines are black, but some are red. In fact, in the long run, 95% of the horizontal bars will be black, and 5% will be red. 

We can now see what is meant by the sentence “Confidence intervals are a statement about the percentage of confidence intervals that contain the true parameter value“. For 95% of the samples, the red line (the population parameter) is contained within the 95% confidence interval around the sample mean.

As we will see when we turn to the formulas for confidence intervals, sample means and their confidence intervals depend on the sample size. The larger the sample size, the smaller the confidence intervals. 

### The relation between confidence intervals and *p*-values {#relatCIp}

There is a direct relationship between the CI of an effect size and the statistical difference from 0 of the effect. For example, if an effect is statistically different (*p* \< 0.05) from 0 in a two-sided *t*-test with an alpha of .05, the 95% CI for the mean difference between two groups will never include zero. Confidence intervals are usually said to be more informative than *p*-values, because they do not only provide information about the statistical difference from 0 of an effect but they also communicate the precision of the effect size estimate. If 0 is not contained in the confidence interval around the mean difference, the effect is statistically different from zero – it might be a false positive, but the *p*-value will be smaller than 0.05.

Confidence intervals are often used in forest plots that communicate the results from a meta-analysis. In the plot below, we see 4 rows. Each row shows the effect size estimate from one study (in Hedges’ g). For example, study 1 yielded an effect size estimate of 0.44, with a confidence interval around the effect size from 0.08 to 0.8. The horizontal black line, similarly to the visualization we played around with before, is the width of the confidence interval. When it does not touch the effect size 0 (indicated by a black vertical line) the effect is statistically significant.

![](images/metasmall.png)

We can see, based on the fact that the confidence intervals do not overlap with 0, that studies 1, 2, and 4 were statistically significant.The light blue diamond is the meta-analytic effect size. Instead of using a black horizontal line, the upper limit and lower limit of the confidence interval are indicated by the left and right points of the diamond. The center of the diamond is the meta-analytic effect size estimate. A meta-analysis calculates the effect size by combining and weighing all studies. The confidence interval for a meta-analytic effect size estimate is always narrower than that for a single study, because of the combined sample size of all studies included in the meta-analysis.

### The Standard Error and 95% Confidence Intervals

To calculate a confidence interval, we need the standard error. The standard error (SE) estimates the variability between sample means that would be obtained after taking several measurements from the same population. It is easy to confuse it with the standard deviation, which is the degree to which individuals within the sample differ from the sample mean. Formally, statisticians distinguish between σ and $\widehat{\sigma}$, where the hat means the value is estimated from a sample, and the lack of a hat means it is the population value – but I’ll leave out the hat, even when I’ll mostly talk about estimated values based on a sample in the formulas below. Mathematically (where σ is the standard
deviation),

Standard Error (SE) = σ/√n

The standard error of the sample will tend to zero with increasing sample size, because the estimate of the population mean will become more and more accurate. The standard deviation of the sample will become more and more similar to the population standard deviation as the sample size increases, but it will not become smaller. Where the standard deviation is a statistic that is descriptive of your sample, the standard error describes bounds on a random sampling process.

The Standard Error is used to construct confidence intervals (CI) around sample estimates, such as the mean, or differences between means, or whatever statistics you might be interested in. To calculate a confidence interval around a mean (indicated by the Greek letter mu: μ), we use the *t* distribution with the corresponding degrees of freedom (*df* : in a one-sample *t*-test, the degrees of freedom are n-1):

μ±*t*df, 1-(α/2) × SE

With a 95% confidence interval, the α = 0.05, and thus the critical *t*-value for the degrees of freedom for 1- α /2, or the 0.975th quantile is calculated. Remember that a *t*-distribution has slightly thicker tails than a Z-distribution. Where the 0.975th quantile for a Z-distribution is 1.96, the value for a *t*-distribution with for example df = 19 is 2.093. This value is multiplied by the standard error, and added (for the upper limit of the confidence interval) or subtracted (for the lower limit of the confidence
interval) from the mean.

### Overlapping Confidence Intervals

Confidence intervals are often used in plots. In the example below, you see three estimates (the dots), surrounded by three lines (the 95% confidence intervals). The left two dots (X and Y) represent the **means** of the independent groups X and Y on a scale from 0 to 7 (see the axis from 0-7 on the left side of the plot). The dotted lines between the two confidence intervals visualize the overlap between the confidence intervals around the means. The two confidence intervals around means in columns X and Y are commonly shown in a
figure in a scientific article. The third dot, slightly larger, is the **difference** between X and Y, and slightly thicker line visualizes the confidence interval of the difference. The difference score uses the axis on the right (from -3 to 3). In the plot below, the mean of group X is 3.3, the mean of group Y is 5.1, and the difference is 1.8.

The width of the confidence interval depends on the sample size, the confidence interval level, and the standard error, as you have seen before. In the plot on the left below, the sample size was 50 people in each group, while on the right, the sample size was 500 people in each group. The difference in the width of the confidence intervals is substantial. It is also clear that accurate estimates require large samples.

![](images/cismall.png)

![](images/cilarge.png)

As mentioned earlier, when a 95% confidence interval does not contain 0, the effect is statistically different from 0. For a *t*-test, this is true for the confidence interval around an effect size, or around a mean difference, because the mean difference, or the standardized mean difference (the effect size) are directly related to the significance test. In the plots above, the mean difference and the 95% confidence interval around it are visible on the right of each plot. When this 95% confidence interval does not contain 0, the t-test is significant at an alpha of 0.05. But the two confidence intervals around the
individual means can be more difficult to interpret in relation to whether the means differ enough to be statistically significant. Open CI_Overlap.R, and run the code. It will generate plots like the one above. Run the entire script as often as you want (notice the variability in the *p*-values due to the relatively low power in the test!), to answer the following question. The *p*-value in the plot will tell you if the difference is statistically significant, and what the *p*-value is.

Q6: How much do two 95% confidence intervals around individual means from
independent groups overlap when the effect is only just statistically
significant (*p* ≈ 0.05) at an alpha of 0.05?

A) When the 95% confidence interval around one mean does not contain the mean of
the other group, the groups differ significantly from each other.

B) When the 95% confidence interval around one mean does not overlap with the
95% confidence interval of the mean of the other group, the groups differ
significantly from each other.

C) When the overlap between two confidence intervals is approximately half of
one side of the confidence interval, the groups differ significantly from each
other.

D) There is no relationship between the overlap of the 95% confidence intervals
around two independent means, and the *p*-value for the difference between these
groups.

Note that this visual overlap rule can only be used when the comparison is made between independent groups, not between dependent groups! The 95% confidence interval around effect sizes is therefore typically more easily interpretable in relation to the significance of a test.

### Prediction Intervals

Even though 95% of future confidence intervals will contain the true parameter, a 95% confidence interval will not contain 95% of future individual observations. Sometimes, researchers want to predict the interval within which a single value will fall. This is called the prediction interval. It is always much wider than a confidence interval. The reason is that individual observations can vary substantially, but means of future samples (which fall within a normal confidence interval 95% of the time) will vary much less.

Open the file CI_mean.R. Run the entire script. This scripts will simulate a single sample with a population mean of 100 and standard deviation of 15, and calculate the mean (M) and standard deviation (sd) of the sample. The black dotted line illustrates the true mean. 95% of the CI should contain the true mean (100).

![](images/predict.png)

The orange background illustrates the 95% confidence interval, calculated as we did manually before. The lighter yellow background illustrates the 95% prediction interval (PI). To calculate it, we need a slightly different formula for the standard error, namely:

Standard Error (SE) = σ\*√(1+1/N)

When we rewrite the formula used for the confidence interval to σ\*√(1/N), we see the difference between a confidence interval and the prediction interval is in the “1+” which always leads to wider intervals. Prediction intervals are **wider**, because they are constructed so that they will contain **a future single value** 95% of the time.

### Capture Percentages

One thing people find difficult to understand is why a 95% confidence interval does not provide us with the interval where 95% of future means will fall. The % of means that falls within a single confidence interval is called the **capture percentage**. A 95% confidence interval is only a 95% capture percentage when the statistic (such as an effect size) you observe in a single sample happens to be exactly the same as the true parameter. This situation is illustrated in the picture below. The observed effect size (dot) falls exactly on the true effect size (vertical dotted line). In this case, and *only in this case*, 95% of future means will fall within this 95% confidence interval.

![](images/capture1.jpg)

However, you can’t know whether your observed effect size happens to be exactly the same as the population effect size. When this is not the case (and it is almost never exactly the case) less than 95% of future effect sizes will fall within the CI from your current sample. The right side of the figure illustrates this. Let’s assume we observed an effect size much lower to the true effect size. We know that effect sizes from the sample are randomly distributed around the true effect size. Very often, we should find effect size estimates in our sample that fall outside the 95% confidence interval of the single sample we happen to have observed. So, the percentage of future means that fall within a single confidence interval depends upon which single confidence interval you happened to observe! In the long run, a 95% CI has an 83.4% capture probability [@cumming_confidence_2006].

Let’s experience this through simulation. The simulation in the R script generates a large number of additional samples, after the initial one that was plotted. The simulation returns the number of CI that contains the mean (which should be 95% in the long run). The simulation also returns the % of means from future studies that fall within the 95% of the original study, or the capture percentage. It differs from (and is often lower, but sometimes higher, than) the confidence interval.

Q8: Run the simulations multiple times. Look at the output you will get in the R
console. For example: “95.077 % of the 95% confidence intervals contained the
true mean” and “The capture percentage for the plotted study, or the % of values
within the observed confidence interval from 88.17208 to 103.1506 is: 82.377 %”.
While running the simulations multiple times, look at the confidence interval
around the sample mean, and relate this to the capture percentage. Which
statement is true?

A) The farther the sample mean is from the true population mean, the lower the
capture percentage.

B) The farther the sample mean is from the true population mean, the higher the
capture percentage.

Q9: Simulations in R are randomly generated, but you can make a specific
simulation reproducible by setting the seed of the random generation process.
Copy-paste “set.seed(1000)” to the first line of the R script, and run the
simulation. The sample mean should be 94. What is the capture percentage? (Don’t
forget to remove the set.seed command if you want to generate more random
simulations!).

A) 95%

B) 42.1%

C) 84.3%

D) 89.2%

Capture percentages are rarely directly used to make statistical inferences. The
main reason we discuss them here is really to prevent the common
misunderstanding that 95% of future means fall within a single confidence
interval: Capture percentages clearly show that is not true. Prediction
intervals are also rarely used in psychology, but are more common in data
science.

In this assignment you have learned why it is important to provide a measure of the uncertainty of your estimates. We have discussed the correct interpretation of confidence intervals, the meaning of prediction intervals, and the difference between a confidence interval and a capture percentage. 

## Computing Confidence Intervals around Effect Sizes

### MOTE 

Currently the easiest and most complete solution to calculating effect sizes and confidence intervals is [MOTE](https://www.aggieerin.com/shiny-server/) made by Dr. Erin Buchanan and her lab. The website comes with a full collections of tutorials, comparisons with other software packages, and demonstration videos giving incredible accessible overviews of how to compute effect sizes for a wide range of tests. For example, the video below gives an overview for an independent *t*-test

<iframe width="560" height="315" src="https://www.youtube.com/embed/kH3UOoFh9Ng?start=9" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

MOTE is also available as an R package [@buchanan_mote_2017]. It contains many useful functions, such as ways to compute effect sizes from summary statistics, which provide output that can conveniently be embedded in an R Markdown document:


```r
library(MOTE)

res <- d.ind.t(m1 = 1.7, m2 = 2.1, sd1 = 1.01, sd2 = 0.96, n1 = 77, n2 = 78, a = .05)
res$statistic
```

```
## [1] "$t$(153) = -2.53, $p$ = .013"
```

```r
res$estimate
```

```
## [1] "$d_s$ = -0.41, 95\\% CI [-0.72, -0.09]"
```

Although many solutions exists to compute Cohen's d, MOTE sets itself apart by allowing researchers to compute effect sizes and confidence intervals for many additional effect sizes, such as (partial) omega squared for between subjects ANOVA ($\omega^{2}$ and $\omega^{2}_p$), generalized omega squared for ANOVA ($\omega^{2}_G$), Epsilon squared for ANOVA ($\varepsilon^{2}$) and (partial) generalized eta squared for ANOVA ($\eta^{2}_G$), as well as Hedges' g (bias corrected Cohen's d). If you are want to compute effect sizes and their confidence intervals, this is the first resource you should try. 

### JASP

Free statistical software [JAPS](https://jasp-stats.org/) is a strong alternative to SPSS that (unlike SPSS) allows users to compute Cohen's d and the confidence interval for both independent and dependent *t*tests.

<div class="figure" style="text-align: center">
<img src="images/jaspeffectci1.png" alt="JASP menu option allows you to select Cohen's d and a CI around it." width="100%" />
<p class="caption">(\#fig:jasp1)JASP menu option allows you to select Cohen's d and a CI around it.</p>
</div>

<div class="figure" style="text-align: center">
<img src="images/jaspeffectci2.png" alt="JASP output returns Cohen's d and the confidence interval around it." width="100%" />
<p class="caption">(\#fig:jasp2)JASP output returns Cohen's d and the confidence interval around it.</p>
</div>

JASP also allows you to compute omega squared $\omega^{2}$, the less biased version of $\varepsilon^{2}$ and 


### ESCI software

For people who prefer to use [ESCI software](https://thenewstatistics.com/itns/esci/) by Geoff Cumming, ESCI also has an option to provide 95% CI around Cohen's d, both for independent as for dependent *t*-tests. However, the option is slightly hidden - you need to scroll to the right, where you can check a box which is placed out of view.

<div class="figure" style="text-align: center">
<img src="images/esci1.png" alt="ESCI software has a somewhat hidden option to compute 95% CI around Cohen's d for within and between *t*-tests." width="100%" />
<p class="caption">(\#fig:esci)ESCI software has a somewhat hidden option to compute 95% CI around Cohen's d for within and between *t*-tests.</p>
</div>

### MBESS

MBESS is another R package that has a range of options to compute effect sizes and their confidence intervals [@kelley_confidence_2007]. The code below reproduces the example for MOTE above.


```r
library(MBESS)

# Cohen's d
smd(Mean.1 = 1.7, 
    Mean.2 = 2.1, 
    s.1 = 1.01, 
    s.2 = 0.96, 
    n.1 = 77, 
    n.2 = 78)
```

```
## [1] -0.406028
```

```r
# Hedges' g
smd(Mean.1 = 1.7, 
    Mean.2 = 2.1, 
    s.1 = 1.01, 
    s.2 = 0.96, 
    n.1 = 77, 
    n.2 = 78, 
    Unbiased = TRUE)
```

```
## [1] -0.4040338
```

To get the confidence interval for the proportion of variance (r², or η², or partial η²) in a fixed factor analysis of variance we need the ci.pvaf function. We need to specify the F-value, degrees of freedom,  the sample size, and the confidence level.


```r
ci.pvaf(F.value=5.72, df.1=1, df.2=198, N=200, conf.level=.90)
```

```
## $Lower.Limit.Proportion.of.Variance.Accounted.for
## [1] 0.002600261
## 
## $Probability.Less.Lower.Limit
## [1] 0.05
## 
## $Upper.Limit.Proportion.of.Variance.Accounted.for
## [1] 0.07563493
## 
## $Probability.Greater.Upper.Limit
## [1] 0.05
## 
## $Actual.Coverage
## [1] 0.9
```

For within designs, the MBESS package returns an error. For example:


```r
ci.pvaf(F.value = 25.73, df.1 = 2, df.2 = 28, N = 18, conf.level = 0.9)
```

```
## Error in ci.pvaf(F.value = 25.73, df.1 = 2, df.2 = 28, N = 18, conf.level = 0.9): N must be larger than df.1+df.2
```

This error is correct in between-subjects designs (where the sample size is larger than the degrees of freedom) but this is not true in within-designs (where the sample size is smaller than the degrees of freedom for many of the tests). Thankfully, Ken Kelley (who made the MBESS package) helped me out in an e-mail by pointing out you could just use the R Code within the ci.pvaf function and adapt it. Just change the F-value, confidence level, and the df.1 and df.2.


```r
Lims <- conf.limits.ncf(F.value = 7, conf.level = 0.90, df.1 <- 4, df.2 <- 50)
Lower.lim <- Lims$Lower.Limit/(Lims$Lower.Limit + df.1 + df.2 + 1)
Upper.lim <- Lims$Upper.Limit/(Lims$Upper.Limit + df.1 + df.2 + 1)
Lower.lim
```

```
## [1] 0.1418798
```

```r
Upper.lim
```

```
## [1] 0.4630716
```

### Why should you report 90% CI for eta-squared?

You will see that in the code above I used a 90% CI for effect sizes calculated for an *F*-test. The reason for this is explained by [Karl Wuensch](http://core.ecu.edu/psyc/wuenschk/StatHelp/StatHelp.htm), a leader in the field of applied statistics education, who has gone out of his way to explain this in a very clear document, including examples, [which you can find here](http://core.ecu.edu/psyc/wuenschk/docs30/CI-Eta2-Alpha.doc). If you don’t want to read it, you should know that while Cohen’s d can be both positive and negative, r² or η² are squared, and can therefore only be positive. This is related to the fact that *F*-tests (as commonly used in ANOVA) are one-sided. If you calculate a 95% CI, you can get situations where the confidence interval includes 0, but the test reveals a statistical difference with a *p* < .05 (for a more mathematical explanation, see @steiger_beyond_2004. This means that a 95% CI around Cohen's d equals a 90% CI around η² for exactly the same test. 

As a final detail, because eta-squared cannot be smaller than zero, the lower bound for the confidence interval can not be smaller than 0. This means that a confidence interval for an effect that is not statistically different from 0 has to start at 0. You report such a CI as 90% CI [.00; .XX]  where the XX is the upper limit of the CI. 