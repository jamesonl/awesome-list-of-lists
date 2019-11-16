# [Minds and machines: The art of forecasting in the age of artificial intelligence](https://www2.deloitte.com/us/en/insights/deloitte-review/issue-19/art-of-forecasting-human-in-the-loop-machine-learning.html)

This was inspired out of my interest in forecasting, and trying to figure out what is the best way to implement a system that combines experts on the ground with big data.

## Notes:
 - _"Though even simple algorithms commonly outperform unaided expert judgment, they do not “take humans out of the loop,” for several reasons. First, the domain experts for whom the models are designed (hiring managers, bank loan or insurance underwriters, physicians, fraud investigators, public-sector case workers, and so on) are the best source of information on what factors should be included in predictive models. These data features generally don’t spontaneously appear in databases that are used to train predictive algorithms. Rather, data scientists must hard-code them into the data being analyzed, typically at the suggestion of domain experts and end users. Second, expert judgment must be used to decide which historical cases in one’s data are suitably representative of the future to be included in one’s statistical analysis."_ - Rob Hyndman
 
 - **4 criteria for building a successful forecasting model:**
    1. We understand and can measure the causal factors.
    2. There is a lot of historical data available.
    3. The forecasts do not affect the thing we are trying to forecast.
    4. The future will somewhat resemble the past in a relevant way.
    
 - _"Finally, even after the model has been built and deployed, human judgment is typically required to assess the applicability of a model’s prediction in any particular case."_
 - **_"Figuratively speaking, the equation should be not “algorithms > experts” but instead, “experts + algorithms > experts.”_**
 - _"What about forecasting? Do big data and AI fundamentally change the rules or threaten to render human judgment obsolete? Unlikely."_
 - _"he computational social scientist David Lazer and his co-authors published a widely cited analysis of the episode, offering a twofold diagnosis23 of the algorithm’s ultimate failure:"_ - link to [study](https://gking.harvard.edu/files/gking/files/0314policyforumff.pdf)
    - Neglect of algorithm dynamics
    - Big Data Hubris
    
 - **_"The surprise came at the conclusion of the event. The winner was revealed to be not a grandmaster with a state-of-the-art PC but a pair of amateur American chess players using three computers at the same time. Their skill at manipulating and “coaching” their computers to look very deeply into positions effectively counteracted the superior chess understanding of their grandmaster opponents and the greater computational power of other participants. Weak human + machine + better process was superior to a strong computer alone and, more remarkably, superior to a strong human + machine + inferior process."_**
 - [Francis Galton](https://en.wikipedia.org/wiki/Francis_Galton) - the inventor of regression analysis
 - **_"rediction markets are another device for combining forecasts. The logic of prediction markets mirrors economist Friedrich Hayek’s view that a market mechanism’s primary function is not simply to facilitate buying and selling but, rather, to collect and aggregate information from individuals."_**
 - [Hollywood Stock Exchange](https://www.hsx.com/)
 - [Information Aggregation Mechanism (IAM)](http://www.its.caltech.edu/~mshum/papers/IAMField.pdf)
 - [Good Judgement Project](https://goodjudgment.com/)
    - "Each year, the GJP selects the consistently best 2 percent of the forecasters. These individuals—colloquially referred to as “superforecasters”—reportedly perform 30 percent better than intelligence officers with access to actual classified information."
 - **Traits of a Superforecaster:**
    - They are less likely than most to believe in fate or destiny and more likely to believe in probabilistic and chance events.
    - They are open-minded and willing to change their views in light of new evidence; they do not hold on to dogmatic or idealistic beliefs.
    - They possess above-average (but not necessarily extremely high) general intelligence and fluid intelligence.
    - They are humble about their forecasts and willing to revise them in light of new evidence.
    - While not necessarily highly mathematical, they are comfortable with numbers and the idea of assigning probability estimates to uncertain scenarios.
    
 - Books mentioned throughout the post:
    - Thinking, Fast and Slow
    - Superforecasting: The Art and Science of Prediction

 - **Conclusions:**
    - It is not necessary to intentionally build HIL systems for certain kinds of forecasting
    - Some types of individual and collective intelligence methods do outperform regression / AI, but this is highly dependent upon the problem, as well as the general workflow
    - There are some great examples of markets which have been created for the purpose of forecasting / predicting performance of bespoke markets (Hollywood Exchange)
    - The traits of a superforecaster aren't all that astounding
    
 - People I followed after reading this article:
    - Jim Guszcza
