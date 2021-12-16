# Who does really care about climate change ?
## A gender driven journey throughout environment related topics in the media

## Introduction

Dear ADAdventurer, 

We welcome you onboard a datatrip throughout ecology, environment and climate change. During this journey, you'll be following men and women speakers from a bunch of English newspapers and websites, from 2015 to 2020. 

Before diving in, let's pause for a second. Why did we join this ADAdventure ? It comes from some personal observations, that you might share, or not ! People around us, and more especially students, tend to feel more or less concerned and to involve themselves in a different way, regarding ecology and environment. Indeed, the proportion of women commited into reducing their wastes, buying second hand or avoiding meat seemed quite high to us. So we decided to read about it. A [study](https://onlinelibrary.wiley.com/doi/10.1111/jiec.13176#jiec13176-bib-0044) from Sweden suggested than men tend to have a larger carbon footprint. On the other hand, from studies( [here](https://onlinelibrary.wiley.com/doi/10.1111/jiec.13176#jiec13176-bib-0044) and [there](https://www.weforum.org/agenda/2015/12/climate-friendly-men-or-women/)) conducted in some of the industrialised countries came the conclusion that women tend to be more concerned about those environmental issues. Indeed, they make a big part into daily life tasks and show more willingness to take action against climate change. The [United Nation Development Program](https://www.undp.org/blog/climate-change-isnt-gender-neutral-climate-action-shouldnt-be-either?utm_source=EN&utm_medium=GSR&utm_content=US_UNDP_PaidSearch_Brand_English&utm_campaign=CENTRAL&c_src=CENTRAL&c_src2=GSR&gclid=Cj0KCQiA5OuNBhCRARIsACgaiqWJC_ANIcSFrJsHJ0c4TsNzz8cJAr3BkpdXir5XwvbpEqlVf4n593UaAofaEALw_wcB) highlights the fact that women tend to be more impacted by global warming consequences. However, a last [article](https://climatecommunication.yale.edu/publications/gender-differences-in-public-understanding-of-climate-change/) reported that even if women feeled concerned, they showed less scientific knowledge that men.

Therefore, men and women are expected to address those topics through different angles and with different rethoric tools. This has been highlighted several times when studying social media data such as reddit or tweet posts. However, here, we're dealing with reported speech. Indeed, what a quoted person said has been intentionnally selected by the journalist, taken out of context somehow and emphasized. 
Can we still find some clues from these quotes, supporting the hypothesis that each speaker approaches ecology and other environmental issues depending on his or her gender ?

_Side notes : we performed our analysis with binary gender (male or female) only for the sake of simplicity_.

And now, let's jump in !


## Our storyteller
### Quotebank processed dataset

Here is our raw storyteller ! From **21,470,292** quotes we extracted **335,250** quotes dealing with environment, so roughly **1.5 %**. Below we present the gender repartition per year on those quotes. Women tend to represent **one fifth** of the total number of speakers on the topic.
{% include statistics_quotes.html %}
_TODO : would be nice to add the same plot across all cleaned quotes_
Let's go further and analyse who is taking the floor...

## How do environment-linked topics evolve from 2015 to 2020 ? Among those quotes, what is the proportion of men and women speakers ?

*TODO Alix plot* + comments

## Show me what you're talking about and I'll tell you who you are

### Where LDA comes into play

Now that we've become acquainted with our speakers, let's have a look at what they're talking about, regardless of gender. We use as baseline Latent Dirichlet Allocation to extract topics from those bulk quotes. We extracted and processed **248211 quotes**, among which we have **47374 women and 200837 men**. So **20%** (only...) of our guests are women, and the **80%** left are men. 
LDA managed to extract **7 topics** that are presented in details below :

| Topic number | Topic main word | Second word       | Third word             | Fourth word      | Description interpretation |
|--------------|-----------------|-------------------|------------------------|------------------|----------------------------|
| 0            | 0.068*"climate" | 0.064*"change"    | 0.039*"climate_change" | 0.016*"emission" | climate change             |
| 1            | 0.030*"people"  | 0.022*"want"      | 0.016*"need"           | 0.011*"way"      | action                     |
| 2            | 0.028*"year"    | 0.028*"go"        | 0.022*"people"         | 0.021*"think"    | long term consequences     |
| 3            | 0.025*"long"    | 0.018*"term"      | 0.018*"level"          | 0.013*"air"      | long term consequences     |
| 4            | 0.014*"use"     | 0.011*"food"      | 0.011*"plant"          | 0.011*"year"     | resources                  |
| 5            | 0.015*"work     | 0.013*"community" | 0.012*"new"            | 0.012*"help"     | solutions                  |
| 6            | 0.023*"water"   | 0.012*"feel"      | 0.010*"number"         | 0.009*"warming"  | resources                  |

We can really explore each topic using pyLDAvis tool. We can manually extract the meaningful topics, and see how close the topics are (in the blob graph below). Moreover, each topic word is nicely detailed. 

{% include lda.html %}

### Can we infer the gender from the quote ? 

As a starter, we'll have a look at how each topic evolved for each gender across years. 

{% include topic_evolution_men.html %}
{% include topic_evolution_women.html %}





## Conclusion

## Appendix

### Our data

### Our methods

