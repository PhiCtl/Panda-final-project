# Who does really care about climate change ?
## A gender driven analysis to ecology related topics through the media from 2015 to 2020

Abstract: The idea of our project came from observing the people around us in their dailylife: women seem more involved in ecology than men. Indeed, among the people we meet, the proportion of women making ecological efforts seems to be higher than the proportion of men (vegetarianism, waste reduction, second hand, involvement in ecological associations etc...). %However, this observation is only the result of our subjective observations, in only one aspect of ecology: everyday actions. 

By reviewing scientific litterature, we found a study (1) which showed that men in Sweden have a larger carbon footprint than women. In line with the thesis that women are more involved in ecology than men, another study (2) conducted in 11 industrialised countries showed that women are more concerned about environmental issues and that a major difference between men and women is their willingness to take action against climate change. However, a final study (3) found that in 2010, women in the US had less scientific knowledge than men on the subject.

Therefore, the involvement of gender in ecology seems to differ from one field to another. Thus, it would be interesting to study this phenomenon in order to determine whether a link can really be established between gender and involvement in ecology. The idea is to identify sub-fields of ecology and to study whether some are more attributed to men or women. Finally, we want to study if men and women speakers use the same communication tools.

Study 1: [https://onlinelibrary.wiley.com/doi/10.1111/jiec.13176#jiec13176-bib-0044](https://onlinelibrary.wiley.com/doi/10.1111/jiec.13176#jiec13176-bib-0044)

Study 2: [https://www.pewresearch.org/fact-tank/2015/12/02/women-more-than-men-say-climate-change-will-harm-them-personally/](https://www.pewresearch.org/fact-tank/2015/12/02/women-more-than-men-say-climate-change-will-harm-them-personally/) 

and [https://www.weforum.org/agenda/2015/12/climate-friendly-men-or-women/](https://www.weforum.org/agenda/2015/12/climate-friendly-men-or-women/)

Study 3: [https://climatecommunication.yale.edu/publications/gender-differences-in-public-understanding-of-climate-change/](https://climatecommunication.yale.edu/publications/gender-differences-in-public-understanding-of-climate-change/)

Project structure :

```bash
.
├── Cleaning_data.ipynb     # Notebook containing data handling pipeline and initial analysis
├── gender_extraction.py    # python file to process speaker_attributes.parquet
└── README.md
```

The goal is to analyse our dataset in order to answer the following research questions: 

1. How has the topic of ecology evolved from 2015 to 2020? We want to underline the evolution of the theme of ecology within these 5 years. Furthermore, we want to see a change on the topic of ecology due to the awareness of individuals in recent years.
2. What is the proportion of men and women talking about ecology between 2015 and 2020? Is it possible to notice a significant difference?
3. Defining several sub-topics from the main ecology-topic (politics, daily life action etc...), we would like to study which "sub-topics" are more attributed to men speakers and which ones are more attributed to women speakers?
4. Focusing on the topic of ecology, do men and women share the same communication tools? Which types of words are used most by men and which by women (for example, we want to study: verbs, adjectives, pronouns, adverbs, ...)?
5. Which hypotheses can we make explaining the observations of the previous questions? (for example: women speakers are more involved in ecology of the "daily life" because they are more inolved than men in the housework).

Additional dataset: additionally, we used the speakers_attributes.parquet metadata files extracted from Wikipedia, as suggested in the project description. We simply filtered out all the speakers whose gender wasn’t either binary male or binary female, since the other genders amount to less than 1%. Finally, we merged that dataset with our filtered and cleaned quotes dataset.
