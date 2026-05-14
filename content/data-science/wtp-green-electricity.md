---
title: "What drives willingness to pay for renewable electricity in Slovakia?"
date: 2026-01-15
categories: ["data-science", "climate-and-environment"]
tags: ["machine-learning", "green-electricity", "BSc"]
draft: false
cover:
  image: "/images/hero-bsc-thesis.jpg"
  alt: "Landscape with wind turbines"
  relative: true
  hidden: false
---

As the climate crisis intensifies, shifting electricity generation to renewable sources has become critical. While engineering solutions continue advancing, understanding consumer preferences and pricing strategies is equally vital for accelerating this transition. As part of my bachelor's thesis at Erasmus University Rotterdam, I investigated what Slovaks are willing to pay for renewable electricity and which factors influence these preferences.

## The Challenge
Slovakia faces a unique situation: the country has substantial potential for renewable energy production (24.4 TWh technical potential vs. 30 TWh current consumption), yet only 23% of electricity comes from renewable sources. With recent energy market crises driven by geopolitical instability, understanding consumer willingness to pay (WTP) for renewable electricity became more urgent than ever.
The research posed a central question: Can we quantify what Slovaks are willing to pay for renewable electricity, and can we predict these preferences to enable better pricing strategies?

## Data & Methodology
I conducted a choice experiment survey with 112 respondents, presenting them with 12 pairs of electricity contracts that varied across five attributes:

* Monthly payment (personalized based on their current bill: -€5, €0, +€2, +€5)
* Energy source (all renewables, wind, solar, hydro, biomass, or all available sources)
* Origin (local vs. international production)
* Contract flexibility (cancelable vs. fixed term)
* Supplier (current vs. requires switching)

Using conjoint analysis and conditional logistic regression, I extracted utility values and converted them to monetary willingness to pay. I also tested whether machine learning models could predict individual preferences from sociodemographic variables and pro-environmental behavior.

## Key Findings
The average willingness to pay for renewable electricity is €5.75 per month—significantly higher than the €2-€3 found in neighboring Poland and Czech Republic, and above the expected €2 threshold.

<image>

Breaking this down further:

* Solar energy commanded the highest premium at €6.49/month
* Local production nearly doubled WTP, adding €6.05/month
* Combined, local solar electricity could justify a €12.54/month premium
* Biomass showed minimal appeal (€0.13), likely due to air pollution concerns
* Wind and hydro showed positive but statistically insignificant effects

Behavioral factors matter more than demographics. Counter to expectations, income showed no significant positive effect on WTP. Instead, the strongest predictors were:

* Pro-environmental attitudes, concerns, and behavior (all positive effects)
* Market awareness (mixed effects—knowing green providers increased WTP, but knowing more providers overall decreased it)

Prediction proved challenging. Machine learning models (random forest) achieved only 62-65% accuracy in predicting individual choices—insufficient for practical implementation. This suggests either that the factors driving individual decisions are more complex than captured, or that the sample size (112 respondents) was too small for the number of variables involved.

## What This Means
**For electricity suppliers:** The research suggests room exists for renewable electricity products priced €5-€6 above standard contracts, with potential for higher premiums when offering locally-produced solar energy certificates. Current market offerings (mostly €2-€4 additions) may be underpricing renewable electricity.

**For policymakers:** Slovaks demonstrate willingness to invest in renewable solutions. Subsidies could trigger substantial market shifts, particularly for local production. The 2022 energy crisis and war in Ukraine have likely strengthened this willingness further. However, consumer rights around contract switching need improvement—the hassle of switching providers significantly affects choices.

**For researchers:** A larger, more representative study using multinomial logit models could provide better insights. The prediction challenge suggests that willingness to pay for renewable electricity may require more sophisticated modeling approaches or different experimental designs that better capture the complexity of real-world decision-making.

## Limitations and Looking Forward
This study faced several constraints: non-probabilistic sampling through social media, relatively small sample size, and the artificial nature of survey choice experiments versus real purchasing decisions. The prediction accuracy issue deserves deeper investigation—whether through larger datasets, different algorithms, or entirely different approaches to capturing preferences.

Despite these limitations, the findings provide encouraging evidence that Slovak consumers value renewable electricity and local production, creating opportunities for both market-based and policy-driven acceleration of the renewable energy transition.

Study Details: This research was conducted as a Bachelor's thesis in International Business Economics at Erasmus School of Economics, supervised by Marco Gregori, MSc. Data collection occurred in May 2022 through an online survey promoted via social media and Facebook advertising (€40 budget, 152 clicks, 2.5% CTR).

Feel free to read the study [here](/pdf/1-8-22-Final-Version-BachelorThesis-Mecko-539056.pdf). 