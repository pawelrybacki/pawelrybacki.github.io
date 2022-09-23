---
date: "2020-05-11T00:00:00Z"
external_link: ""
image:
  caption: Photo by <a href="https://unsplash.com/@benwhitephotography?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Ben White</a> on <a href="https://unsplash.com/s/photos/joyful?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  focal_point: Smart

summary: The recipe for happiness and life satisfaction is hard to obtain using scientific methods. However, the more careful the statistical analysis, the better chance that we understand what makes people across the globe feel better. My <a href="wvs_happiness.pdf">project</a> makes the first step in this process by performing a quantitative analysis of the World Values Survey data.

tags:
- Data Science
title: Predicting Happiness and Life Satisfaction Globally
url_code: "https://github.com/pawelrybacki/wvs_happiness_life_satisfaction"
url_pdf: "wvs_happiness.pdf"
url_dataset: "https://github.com/pawelrybacki/wvs_happiness_life_satisfaction/blob/main/wvs_life_satisfaction.dta"
url_slides: ""
url_video: ""
---

## From the Conclusion
Perhaps the largest surprise of my <a href="wvs_happiness.pdf">paper</a> is that there is only a weak correlation between happiness and life satisfaction. As I discussed in the results section of the <a href="wvs_happiness.pdf">paper</a>, it could be because these two concepts are truly distinct and perhaps represent a "heart-reason" divergence. 

Regardless of the weak correlation, there is no estimate that would change its sign from model to model. The only differences between the outcomes pertain to the magnitudes or, in few cases, the significance levels of the
results.

Another interesting result is that men are significantly less happy and
less satisfied with their lives than women, even after controlling for
many other factors. This is contrary to my hypothesis. It may have to do
either with genes and metabolism or with cultural norms. Perhaps men's
well-known lower risk aversion leads them to doing things that have
seriously negative consequences, and the individuals who face these
consequences drive the coefficients down. Alternatively, male hormones
make men feel less happy and optimistic. This would be a fascinating
topic for further investigation.

Metabolism and homeostasis impact our spirits, not just our bodies.
Health is the largest predictor of happiness and the third largest
predictor of life satisfaction (yielding to financial satisfaction and
the feeling of freedom). A part of this effect may be a comorbidity of
physical health deficiency with mental health diseases. However, it is
also important to remember that this is self-assessed health, so general
pessimism may influence both answers. Regardless, a takeaway is that
there are few things that can compensate health.

The relationship between the dependent variables of interest and age is
negative. Interestingly, in regressions without fixed effects (not
reported), it seemed that age was positively correlated with happiness
and life satisfaction. Perhaps that effect was driven by richer and
older societies. The final outcome could be interpreted as a reflection
of the possibility that people care a lot about aspects of being young,
such as appearance or having more energy.

Married people are the happiest and the most satisfied with their lives,
holding the number of children constant. The effect is particularly high
for happiness. Those who "live as married" are not far behind in both
categories. As expected, being divorced, separated, and widowed makes
you less happy or satisfied with your life even compared to being
single. Interestingly, being separated, rather than divorced, makes you
the saddest. Overall, with the strongest effect of all, marriage seems a
worthwhile risk. When it comes to children, they do bring satisfaction,
but surprisingly little of it. Although many moms and dads claim to be
the happiest people on Earth, the AIC algorithm challenged their
declarations to some extent by deleting the variable.

If you do not work, you can as happy as a student, to whom college
brings as many positive feelings as religion to the religious people; as
sad as an unemployed, for whom their situation is even worse than for
those separated; or somewhere in-between, as the retired who are not
statistically significantly different than the fully employed.
Housewives (or househusbands) are generally happier and more satisfied
with their lives than the fully employed, although without enough
statistical evidence for the latter feeling.

When looking at financial satisfaction and the scale of incomes, it
seems that money is everything. The former beats every other variable,
except for health, by a lot in both models. Or, people who generally
feel better about everything have more energy to earn more. Since the
scale of incomes is represented by a squared term, I could infer that
its positive coefficient tells us that being average is the saddest and
least satisfying position in society. If you have not made it to the
top, you may be better off by giving away everything like St. Francis.

Speaking of religion, being religious and going to church often is
associated with higher happiness and life satisfaction, although the
effects are not enormous. Reflecting on the sense of your life makes 
sense when you do it in moderation; too little or too much contemplation
seems to make you less happy and less satisfied with your life.  
Similarly, the importance of God has a quadratic
relationship with happiness and life satisfaction, which means that it
is worth being decided in the spiritual realm. This reminds me of the
biblical quote: "So, because you are lukewarm, neither hot nor cold, I
will spit you out of my mouth." (Revelation 3, 16).

Trusting in God makes you feel good, and so does trusting in other
people. Or, feeling good makes you trust more in both. In any case, the
association is moderately strong for happiness and life satisfaction,
with emphasis on the former.

Last but not least, the feeling of freedom of choice and control over
your life is one of the most important things for happiness and life
satisfaction. According to my model, freedom brings more satisfaction
than marriage, children, health, or religion. As I am writing this from
home abroad, this makes me miss the Land of Freedom even more.

In conclusion, the recipe for happiness and life satisfaction is hard to
obtain using scientific methods. However, the more careful the
statistical analysis, the better chance that we understand what makes
people across the globe feel better. My project is just the first step
in this process, and there are still more things I did not consider than
those I took into account. From data collection, through data cleaning,
to data analysis, my outcomes rely and numerous assumptions. However, I
hope that the imperfections of my study and the preliminary results can
serve as an inspiration for future investigation. As of now, the WVS
data suggest that the *average* key to happiness and life satisfaction
is being a healthy married young woman with a few children, who is a
pious and religious student, trusts other people, and enjoys has lots of
freedom as well as good economic conditions.

## The Full Paper:
Read the full paper in a PDF format <a href="wvs_happiness.pdf">here</a>.

## The Code:
The code that cleans the dataset and the code that analyzes the data and produces the paper is [here, on my GitHub](https://github.com/pawelrybacki/wvs_happiness_life_satisfaction)

## The Dataset:
The dataset is [here, on my GitHub](https://github.com/pawelrybacki/wvs_happiness_life_satisfaction/blob/main/wvs_life_satisfaction.dta).


