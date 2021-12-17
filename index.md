<html>
<head>
<style>
div{
 text-align: justify}
 
  table{ 
  class="center"
  font-family: arial, sans-serif;
  border-collapse: collapse;
  width:100%
 }

img { width:100%
 }
 
 td, th {
  border: 1px solid #dddddd;
 text-align:left;
 padding:8px;
 }
</style>

 <h1>  Who does really care about climate change ?  </h1>
 <h1> A gender driven journey throughout environment related topics in the media </h1>
 </head>
 <body>
  
  <h2> Introduction </h2>

<div> 
Dear ADAdventurer, 
We welcome you onboard a datatrip throughout ecology, environment and climate change. During this journey, you'll be following men and women speakers from a bunch of English newspapers and websites, from 2015 to 2020. 

Before diving in, let's pause for a second. Why did we join this ADAdventure ? It comes from some personal observations, that you might share, or not ! People around us, and more especially students, tend to feel more or less concerned and to involve themselves in a different way, regarding ecology and environment. Indeed, the proportion of women commited into reducing their wastes, buying second hand or avoiding meat seemed quite high to us. So we decided to read about it.   

 <a href="https://onlinelibrary.wiley.com/doi/10.1111/jiec.13176#jiec13176-bib-0044">A study</a> from Sweden suggested than men tend to have a larger carbon footprint. On the other hand, from studies (<a href="https://onlinelibrary.wiley.com/doi/10.1111/jiec.13176#jiec13176-bib-0044">here</a> and <a href="https://www.weforum.org/agenda/2015/12/climate-friendly-men-or-women/">there</a>) conducted in some of the industrialised countries came the conclusion that women tend to be more concerned about those environmental issues. Indeed, they make a big part into daily life tasks and show more willingness to take action against climate change. The <a href="https://www.undp.org/blog/climate-change-isnt-gender-neutral-climate-action-shouldnt-be-either?utm_source=EN&utm_medium=GSR&utm_content=US_UNDP_PaidSearch_Brand_English&utm_campaign=CENTRAL&c_src=CENTRAL&c_src2=GSR&gclid=Cj0KCQiA5OuNBhCRARIsACgaiqWJC_ANIcSFrJsHJ0c4TsNzz8cJAr3BkpdXir5XwvbpEqlVf4n593UaAofaEALw_wcB">United Nation Development Program</a> highlights the fact that women tend to be more impacted by global warming consequences. However, a last <a href="https://climatecommunication.yale.edu/publications/gender-differences-in-public-understanding-of-climate-change/">there</a>) reported that even if women feeled concerned, they showed less scientific knowledge that men. 

Therefore, men and women are expected to address those topics through different angles and with different rethoric tools. This has been highlighted several times when studying social media data such as reddit or tweet posts. However, here, we're dealing with reported speech. Indeed, what a quoted person said has been intentionnally selected by the journalist, taken out of context somehow and emphasized. 
Can we still find some clues from these quotes, supporting the hypothesis that each speaker approaches ecology and other environmental issues depending on his or her gender ?

  <p style="font-style: italic;">Side notes : we performed our analysis with binary gender (male or female) only for the sake of simplicity.</p>

And now, let's jump in !
 
<h2> Our storyteller </h2>
<h3> Quotebank processed dataset </h3>

Here is our raw storyteller ! From <b>21,470,292</b> quotes we extracted <b>335,250</b> quotes dealing with environment, so roughly <b>1.5 %</b>. Below we present the gender repartition per year on those quotes. Women tend to represent <b>one fifth</b> of the total number of speakers on the topic.

{% include statistics_quotes.html %}

Let's go further and analyse who is taking the floor...

<h2> How do environment-linked topics evolve from 2015 to 2020 ? Among those quotes, what is the proportion of men and women speakers ? </h2>

<h3> Evolution of the proportion of men and women speakers </h3>
 
Let's start our journey by comparing the proportion of men and women speakers on the ecology topic between 2015 and 2020. The first obvious thing, but unfortunately not surprising, is that there are many more collected quotes from men than from women (around 80% and 20% respectively). However, the good news is that over the years there has been a slow evolution reversing this trend. Indeed, since 2018, the proportion of women talking about ecology is increasingly important!

{% include proportion_genders.html %}

<h3> Who are the most famous speakers ? </h3>
 
But aren't you curious to know more about the people who have received the most media attention on the subject of ecology? And here it is! The following barplot presents the 30 most famous speakers reported, and it appears that Donald Trump is by far the most popular on environmental issues, followed by Barack Obama and Pope Francis. In line with the previous observation, less than 20% are women. But among the most famous speakers, do men and women speakers share the same kind of profile? To make the comparison let’s analyse each gender separately. 

{% include most_famous.html %}

<p style="font-style: italic;">Side notes : The popularity of a person is defined as the number of times their quotes have been republished, the greater the number, the more popular the person.</p>
  
Starting with the men, a rather interesting observation can be made. Among the 30 most famous men, only one of them (who corresponds to 3% of the sample) is not a politician: Pope Francis. He is the third most famous speaker. 

{% include most_famous_men.html %}

On the other hand, the profiles of the 30 most famous women are much more varied: only <b>60%</b> of them are politicians (against <b>97%</b> on the men’s side). There is also a very famous climate activist: Greta Thunberg (who represents <b>3%</b> of the sample), two women are scientists specialized in environmental issues (<b>6%</b>) and the remaining 30% are public figures such as actresses, singers, writers, models etc... 

Attention! This does not mean that men have less varied profiles than women, but only that among the 30 most famous for each gender, there are half as many politicians among women as among men. 

{% include most_famous_women.html %}
 
If we now restrict ourselves to the three most famous men and three most famous women, how did their media coverage evolve during the 5 years? First, concerning political figures, we notice that the evolution of their popularity over the years is strongly correlated with the important stages of their political life. For example, Barack Obama's popularity decreases with the years, which correspond to the end of his mandate. On the other hand, for Hilary Clinton and Donald Trump, popularity increases in 2015 and 2016, during the US presidential campaign. For Trump, a peak is reached at the beginning of his mandate in 2017 and then decreases from year to year, while for Clinton, as soon as the presidential elections are over, her popularity rating drops. 
Concerning Pope Francis, one year out of the 5 seems to stand out: 2015, which corresponds to the year of the publication of "Laudato Si", his encyclical on ecology. It seems that Angela Merkel also had a popularity peak in 2017, the year of the COP23 in Bonn, Germany. Finally, the graph suggests that in 2019, Greta began to receive a lot of media attention, following its intervention at the COP24 in 2018.  

{% include evolution_famous.html %}

<h2> Show me what you're talking about and I'll tell you who you are </h2>

<h3> Topics broken down to words </h3>
 
We're reaching a cross road, and before following the path of topic analysis, let's try to predict, from simple words, whether a given quote speaker was a man or a woman. Each quotation was broken into words and embedded into a Term-frequency Inverse Document Frequency Matrix. Below we present the results from the two simple classifiers we used. We used a perfectly balanced dataset to predict the gender and our accuracy is a bit but not much above random chance (ie. 50%). Logistic regression performed slightly better than random forest on the train set. 

<table>
 <tr>
  <th> </th>
  <th> Random Forest </th>
  <th> Logistic regression </th>
 </tr>
 <tr>
  <td>  Accuracy on test set </td>
  <td> 0.556 </td>
  <td> 0.567 </td>
 </tr>
 <tr>
  <td> Precision  </td>
  <td> 0.561 </td>
  <td> 0.565  </td>
 </tr>
 <tr>
  <td> Recall </td>
  <td> 0.485  </td>
  <td> 0.564  </td>
 </tr>
</table>

 Given all the pieces of information coming from the words that we have at our disposal, across all quotes, we cannot make a very significative statement about the speaker gender. This can be explained by the following fact. Even if we artificially balanced the dataset, we have very few quotes attributed to women, and thus less diversity in the words. Therefore our classifiers weren't able to grasp a meaningful aspect linked to gender out of it. We can nevertheless explore how our more performant classifier made its choices, taking a look at each coefficient importance into the task of predicting whether the speaker is a woman or not. The more positive the coefficient, the more weight it gives towards predicting "woman", the more negative, the better it is to predict "man".

{% include coefs_logistic_gender_prediction.html %}

Two interesting facts can be highlighted there. First of all, the most prominent words are gender related, such as <i>girl, woman, guy,</i> or <i>husband</i>. Secondly, action verbs like <i>shall, execute</i> and <i>operate</i> are used to classify "man", while more diverse types of words are linked to predicting "woman". We managed to pick one interesting aspect from our guests !

We decide to turn left, and discover the topics landscapes. Don't loose the track, and follow us !
 
<h3> Where LDA comes into play </h3>
<i>Test bold text</i>
Now that we've become acquainted with our speakers, let's have a look at what they're talking about, regardless of gender. We use as baseline Latent Dirichlet Allocation to extract topics from those bulk quotes. We extracted and processed <b>248'211 quotes</b>, among which we have <b>47'374 women and 200'837 men</b>. So <b>20%</b> (only...) of our guests are women, and the <b>80%</b> left are men. 
LDA managed to extract <b>7 topics</b> that are presented in details below :

<table>
 <tr>
  <th> Topic number </th>
  <th> Topic main word </th>
  <th> Second word </th>
  <th> Third word  </th>
  <th> Fourth word </th>
  <th> Description interpretation </th>
 </tr>
 <tr>
  <td>  3 </td>
  <td> 0.068*"climate" </td>
  <td> 0.064*"change" </td>
  <td> 0.039*"climate_change" </td>
  <td> 0.016*"emission" </td>
  <td> climate change </td>
 </tr>
 <tr>
  <td>  2 </td>
  <td> 0.030*"people" </td>
  <td> 0.022*"want" </td>
  <td> 0.016*"need" </td>
  <td>  0.011*"way"  </td>
  <td> action </td>
 </tr>
 <tr>
  <td>  4  </td>
  <td> 0.028*"year" </td>
  <td> 0.028*"go" </td>
  <td> 0.022*"people" </td>
  <td>  0.021*"think"  </td>
  <td> long term consequences </td>
 </tr>
 <tr>
  <td>  7   </td>
  <td> 0.025*"long" </td>
  <td> 0.018*"term" </td>
  <td> 0.018*"level"  </td>
  <td>  0.013*"air"  </td>
  <td> long term consequences </td>
 </tr>
 <tr>
  <td>  5   </td>
  <td>  0.014*"use" </td>
  <td> 0.011*"food"</td>
  <td> 0.011*"plant" </td>
  <td>  0.011*"year"</td>
  <td> resources </td>
 </tr>
 <tr>
  <td>  1   </td>
  <td>  0.015*"work" </td>
  <td>0.013*"community"</td>
  <td> 0.012*"new" </td>
  <td>  0.012*"help"</td>
  <td> solutions </td>
 </tr>
 <tr>
  <td>  6  </td>
  <td> 0.023*"water" </td>
  <td> 0.012*"feel"</td>
  <td> 0.010*"number" </td>
  <td>  0.009*"warming"</td>
  <td> resources </td>
 </tr>
</table>
 
 
We can really explore each topic using pyLDAvis tool. We can manually extract the meaningful topics, and see how close the topics are (in the blob graph below). Moreover, each topic word is nicely detailed. 

As a side note, the size of the bubble represents the relevance of the topic in the corpus. The associate words are displayed on the left. 
The blue bars represent the overall frequency of each word in the corpus, while the red one the estimated frequency within the selected topic.
The numbering corresponds to the topic importance as well.

The three main topics are quite relevant for our analysis. We could describe the first one as the need to work together in order to bring sustainable solutions. 
The second could deal with the urge to act. The third one clearly presents global warming stakes and impacts. The fourth could be about long term consequences, and could
the seventh topic, the fifth about the waste management and the sixth about water. 

{% include lda.html %}

<h3> Can we infer the gender from the quote ?  </h3>

As a starter, we'll have a look at how each topic evolved for each gender across years. We'll omit the strange artefacts from 2016 in our analysis which are not representative. 
 
{% include topic_evolution_men.html %}

{% include topic_evolution_women.html %}

The words refer to the first most meaningful word for each topic.
We don’t learn much from a gender-split analysis, but we can still observe that the topic repartition and evolution is quite similar. “People” and “Work” topics seem quite popular among our speakers, and we see a small rise of  “Climate” and “Year” topic towards the end of our studied period.

Let's put on our hiking shoes, grab our camera and follow the track. Will logistic regression and random forest lead us to a clear gender distinction within topics ? We infer each quote topic multinomial distribution, and we write down the score for each topic to constitute our feature matrix. Then we make sure that we have 
as many quotes from men than women speakers. Finally, we took care of tuning random forest in order to select the best depth and number of estimators.  

 <table>
 <tr>
  <th> </th>
  <th> Random Forest </th>
  <th> Logistic regression </th>
 </tr>
 <tr>
  <td>  Accuracy on test set </td>
  <td> 0.741  </td>
  <td> 0.518  </td>
 </tr>
 <tr>
  <td> Precision  </td>
  <td> 0.741 </td>
  <td> 0.524  </td>
 </tr>
 <tr>
  <td> Recall </td>
  <td> 0.747   </td>
  <td> 0.463  </td>
 </tr>
</table>

Random Forest is quite good as catching the non linear relationships between features, and it might be a reason why it performed quite well for this task, 
compared to good old logistic regression. However, the feature importance analysis doesn't bring us much about the topic relevance for predicting the speaker gender.

{% include random_forest_feature_importance.html %}

We reached a summit but the view from there is a bit disappointed... There is a lot of fog. Let's go through the pass and down again in the next valley...

<h3> The path leads to Top2Vec </h3>

We'll turn to a more powerful tool to explore topics brought by the speakers, namely Top2Vec. Top2Vec provides meaningful embeddings for each of our quotes. We end up with a high dimensional vector space, 
from which we want to extract clusters and their centroid. Then, Top2Vec makes use of UMAP for dimensionality reduction, and finally applies HDBSCAN for clustering. 
Each topic vector is then computed as the centroid of the found clusters. 

We look up to the sky and here are the top 10 main topics in the clouds. The first one deals with hope and solutions, the second and third ones 
are much more pessimistic, and could present the disasters incurred by global warming along with the scarceness of the measures taken so far to prevent them. 
At the fourth position, water related issues are raised, then come again some disasters and we end on the fith one with a more optimistic note, namely all the solutions that
we have at our disposal. The sixth topic follows on the solutions, while the seventh brings forward recycling. The nineth points out pollution and polluters while the last one is more generally dealing with ecology.

  <table>
 <tr>
  <th> Top 10 topics...     </th>
  <th> ...for all genders </th>
 </tr>
 <tr>
  <td> <img src="assets/0_wc.jpg" alt="Trulli" width="300" height="300"> </td>
  <td> <img src="assets/1_wc.jpg" alt="Trulli" width="300" height="300">  </td>
 </tr>
 <tr>
  <td> <img src="assets/2_wc.jpg" alt="Trulli" width="300" height="300">  </td>
  <td> <img src="assets/3_wc.jpg" alt="Trulli" width="300" height="300"> </td>
 </tr>
 <tr>
  <td> <img src="assets/4_wc.jpg" alt="Trulli" width="300" height="300">  </td>
  <td> <img src="assets/5_wc.jpg" alt="Trulli" width="300" height="300"> </td>
 </tr>
 <tr>
  <td> <img src="assets/6_wc.jpg" alt="Trulli" width="300" height="300">  </td>
  <td> <img src="assets/7_wc.jpg" alt="Trulli" width="300" height="300"> </td>
 </tr>
 <tr>
  <td> <img src="assets/8_wc.jpg" alt="Trulli" width="300" height="300">  </td>
  <td> <img src="assets/9_wc.jpg" alt="Trulli" width="300" height="300"> </td>
 </tr>
</table>

Below you can explore and compare the top 20 topics brought by our speakers. Each topic name refers to the most weighted word in the given topic. Epa stands for the US Environmental Protection Agency and iot for the Internet of Things.

{% include topic_distrib_all_genders.html %}

Let's climb again, with our two mountain guides, Logistic Regression and Random Forest. We took the same number of quotes for men and women speakers
and we infer the top 20 topics for each quote. And here are the results ! We reached a new summit, and the clouds are starting to make way for the sunshine. 
We reached almost as good results as from word only predictions. Dear guest speaker, tell me what you are talking about and I can predict with 56% of chance whether you're
a man or a woman. Well, that is not amazing yet... 


 <table>
 <tr>
  <th> </th>
  <th> Random Forest </th>
  <th> Logistic regression </th>
 </tr>
 <tr>
  <td>  Accuracy on test set </td>
  <td> 0.562  </td>
  <td> 0.559  </td>
 </tr>
 <tr>
  <td> Precision  </td>
  <td> 0.557  </td>
  <td> 0.56  </td>
 </tr>
 <tr>
  <td> Recall </td>
  <td> 0.488    </td>
  <td> 0.541  </td>
 </tr>
</table>
 
 
Let's dwell for a second anyway, grab a pair of binoculars somewhere and inspect our logistic regression coefficients.
Again, we can find some similarities with the word only analysis from a few valleys ago, and it's quite interesting. Climate topics are pushed into the background, and more gender related
topics are brought to the foreground. Again, the most useful coefficient for predicting whether the speaker is a woman or not is simply the topic... "women" ! Some topics are very
clichées, such as "fashion" for women, or "gun", "markets" and "aviation" for men. Interestingly, more environment related topics are attributed to women, given
the topic keywords, but the classifier does not seem to base its main decisions on that. 


{% include coefs_logistic_gender_topic_prediction_top2vec.html %}

<h3> In the foreground for climate and environment </h3>

We can therefore try to be more specific and look at the main spokespersons for climate. At the beginning of our journey, we met the three main speakers for each gender.
Let's have a look at what they actually say and train a classifier to decide, from a mix of their quotes, whether the speaker is a man or a woman.

We'll walk part of the way with Hillary Clinton, Greta Thunberg and Angela Merkel. Here are the two main topics they brought into light about environment.
Unfortunately, we don't have many quotes available, so our algorithm was only able to infer two of three topics for each. We can nevertheless observe the emphasis
Greta puts on the "crisis" state we're in and the need to "act".

<img src="assets/Word_clouds_females.jpg" alt="Trulli" class=center width="800" height="800">

Now, we'll also join Donald Trump, Pope Francis and Barack Obama. Here are their three main contributions to our topics. Those are quite precise and reveal a lot
about their speaker occupation. Have you already spot the "hoax" word into Trump's word clouds... ?

<img src="assets/Word_clouds_males.jpg" alt="Trulli" class=center width="800" height="800">
 
For a last time, we predict with logistic regression and random forest classifier.

<table>
 <tr>
  <th> </th>
  <th> Random Forest </th>
  <th> Logistic regression </th>
 </tr>
 <tr>
  <td>  Accuracy on test set </td>
  <td> 0.883  </td>
  <td> 0.686  </td>
 </tr>
 <tr>
  <td> Precision  </td>
  <td> 0.938  </td>
  <td> 0.258   </td>
 </tr>
 <tr>
  <td> Recall </td>
  <td> 0.15    </td>
  <td> 0.697  </td>
 </tr>
</table>
 
 
Our dataset was quite imbalanced this time, and even if we have a higher accuracy for random forest classifier, it is not meaningful since it wasn't able to catch most of 
the women speaker quotes. Below are presented the results for logistic regression. It could guess correctly <b>95%</b> of all women and men speakers, which is quite nice ! 

<img src="assets/logistic_regression_confusion_matrix_famous_speakers.jpg" alt="Trulli">

Let's end up this little tour with a closer analysis of the logistic regression coefficients. Environmental topics are balanced between both gender, but we can still notice
that women tend to underline more the "crisis" and the "community" aspects. Note the prevalence of the topics "us" and "ourselves". 


{% include coefs_logistic_gender_topic_prediction_famous_speakers.html %}

This second trip has come to an end and we come back to our starting point with some interesting knowledge. 

<h2> Sentiment analysis of quotations </h2>
 
Now let’s move on to the exploration of the difference between the sentimental score of the quotes between men and women. For this purpose we used the ntlk library. 

First let’s have a look at the distribution of the sentimental score of the quotes. We have a huge peak for neutral sentiment. Of all the quotations on ecology, we have <b>81663</b> that have a score of 0, i.e <b>27%</b> of the total. But what does a score of 0 mean? It is for all the quotes that simply give a state, an information like for example "There are not only channel to us” or “less bleached than reefs further offshore”. 


{% include quotations_sentiment_all.html %}

So we looked at the differences between the two genders. We visualized the density between men and women of the sentimental score. In the plot we observe almost no difference between men and women. Moreover, by performing a t-test we do not obtain a significant difference between men and women. The p-value is equal to 0,99. 

{% include quotations_density.html %}


We therefore looked to see if there were differences between positive and negative quotes. Negative quotes are those with a score strictly below 0 and positive quotes are those with a score strictly above 0. You can find below examples of positive and negative quotes. 

 <table>
 <tr>
  <th> Examples quotations with negative score </th>
  <th> Score </th>
  <th> Examples quotations with positive score </th>
  <th> Score </th>
 </tr>
 <tr>
  <td>  "This is an awesome project in a whole bunch a ways " </td>
  <td> 0,6249 </td>
  <td> "It's indicative of a very worrying trend. If we don't  reign in global warming pollution,about a million species or 15 percent of species on earth are vulnerable to extinction  from climate change." </td>
  <td> -0,5267  </td>
 </tr>
 <tr>
  <td> "Our Planet and Environment is something we all  cherish greatly"  </td>
  <td>  0,9020 </td>
  <td> "It's just a technological engineering problem to solve on what  to do with the waste"   </td>
  <td>  -0,5719 </td>
 </tr>
 <tr>
  <td> "This is really a vote of no confidence  because we believe that the system has become captive" </td>
  <td>  0,2247   </td>
  <td> "This is not over. The state agencies have failed the  process."   </td>
  <td>  -0,250 </td>
 </tr>
  <tr>
  <td> "There are inspiring examples across Africa.  We must take the opportunity to share best practices  andlearn from each other." </td>
  <td>  0,9403  </td>
  <td> "There is anger, despair and horror amoung residents -  who fear further years of noise, dust, pollution and the spread of cancer."  </td>
  <td>  -0,9538  </td>
 </tr>
</table>

We can see that the positive quotes represent <b>half</b> of all quotes. And as seen previously, the proportion between men and women of positive and negative quotes is the same. 
{% include scorennp.html %}

To complete our study, we plotted the distribution of positive versus negative citations by making the absolute value of all negative scores. We thus observe in general more positive quotations than negative ones. But the most surprising thing is that we have a bigger difference for scores higher than 0,4. Thus for quotes with a score above 0.4, there are <b>2.4</b> times more positive quotes than negative ones, while for lower scores there are only <b>1.5</b> times more positive quotes. 

{% include evolutions_scores.html %}

We can therefore suppose that the speakers moderate themselves more to express negation. However ecology is a subject that worries a lot nowadays, the lexical fields of guilt and fear govern this topic. <a href="https://journals.sagepub.com/doi/full/10.1177/0539018421996264">This study</a> studied the emotions when talking about ecology and found that more negative emotions are expressed in this topic. Thus we have interesting and surprising results compared to what we had imagined. 

However, it is important to note here that the database only lists quotes from speakers listed in newspapers, so these quotes do not represent everyone's sentences. The quotation of newspapers are therefore maybe biased. 

<h2> What are the words most used by males and females? </h2>

Once we understand and recognize the major topics of our speakers, let's go on to understand how, that is, with which verbs, adjectives, adverbs, nouns, these speakers go forward in addressing and discussing the different topics!

<h3> Where and how WFA comes into play </h3>

We did a deep analysis to find out which are the most used words among the female and male speakers. We used a _Word Frequency Analysis_ tool just to count the occurrence of each noun, verb, adverb and adjective for all the speakers. 

For each study group of words considered (namely between verbs, nouns, adjectives and adverbs), we present a plot with the 30 most used words between male and female speakers. In the respective plots, it can be seen which verbs, adjectives, nouns and adverbs are most used by a male speaker and which by a female speaker and, furthermore, which are used almost equally between the two genders. Moreover we reported the <i>word clouds</i> visualization, which shows a random display of all the words (between verbs, nouns, adjectives and adverbs, respetively) in a source of quotations, where the size of each word is proportional to the number of times it has been counted in the set of all quotations. These visualisations are interesting, and they can be a quick and direct way to give an overview of how our speakers are talking.


<h4> Verbs </h4>

Which <i>verbs</i> are used most by men and which by women?

{% include verbs_freq.html %}
From the study of the verbs, it can be noticed that the three most used are <i>go, think</i> and <i>need</i>. In this study case, the difference between the genders is very slight, however it can be observed that there is a prevalence of the use of the verbs _go_ and _get_ by male speakers than female spekers. 

 <img src="assets/verbs_freq.jpg" alt="Trulli" class=center width="300" height="500">
 
<h4> Nouns </h4>

Which <i>nouns</i> are used most by men and which by women?

{% include nouns_freq.html %}

Regarding the nouns, the most three used, for both gender, are <i>people, climate, change</i>. However, all three of the latter seem to be utilized more by females speakers, which could confirm our hypothesis that females are probably more involved in ecology topic. In addition to this, it is interesting to underline how the nouns <i>health, life</i> and <i>science</i> seem only used from female speakers. On the other hand, we observe that the nouns <i>level, carbon, business</i> are only used from male speakers. 

 <img src="assets/nouns_freq.jpg" alt="Trulli" class=center width="300" height="500">
 
<h4> Adjectives </h4>
Which _adjectives_ are used most by men and which by women?

{% include adj_freq.html %}

Under the study of the adjectives, it can be seen that the three most used are <i>enviromental, good</i> and <i>important</i> for both gender. Furthermore, it can be noticed a greater use of the <i>global</i> and <i>high</i> adjectives from the side of the male speakers. 

 <img src="assets/adj_freq.jpg" alt="Trulli" class=center width="300" height="500">

<h4> Adverbs  </h4>

Which <i>adverbs</i> are used most by men and which by women?
 
{% include adverbs_freq.html %}

On the use of adverbs, it can be noted that the three most used by both genders are <i>forward, actutally</i> and <i>away</i> (with a majority from the female speakers), whereas <i>truly, hard, directly, exactly, way</i> seem to be used only by male speakers and <i>well, likely, highly, increasingly, obviously</i> only by female speakers.

 <img src="assets/adv_freq.jpg" alt="Trulli" class=center width="300" height="500">

<h2> Conclusion </h2>
 
What a nice adventure ! We hope you enjoyed this datatrip with the Panda team throughout ecology, environment and climate change. We made some beautiful discoveries. 

First of all, from a statistical point of view, speakers seem quite committed regarding the topics that were brought up. They present current issues such as pollution and carbon emissions along with their long term consequences which are clearly stated by each gender such as animal extinction, water shortage. They urge to take actions and some solutions are discussed : sustainability, involvement of government


Regarding our research on the topic of ecology through the genres, we didn’t have as many shades as expected.  

However, some elements can be noticed : 
<ul>
 <li> First of all, the most prevalent topics used to predict gender are gender-biased, such as "women" or "fashion", and environmental related topics come after. Nevertheless, both genders contribute to the environment field. </li>

 <li> Secondly, when studying the topics, nouns and adjectives, women tend to be focus on the community aspect and are aware of urgent actions to take. </li>

 <li> Thirdly, dealing with the word based analysis, to support the commitment of both gender, we can see than mainly action verbs and statement adverbs are used </li>
</ul>
  
However the quotes seem to be very politicized. Indeed, as mentioned above, most of the most important speakers are politicians. For instance, in the top 3 speakers for each gender, two out of three are involved in politics, in the United States or in Europe. As an improvement, it would have been interesting to study the occupation of each speaker and link it to what is said. As more speakers are politicians, we can infer that the gender bias tends to vanish towards a more neutral speech.

Moreover, quotations are mainly classified as neutral, and then positive, while we would have expected more negative components, given this has become a global world wide crisis. 

Thus the conclusions and observations we can make on our dataset should only be taken with great caution. Our dataframe of quotes on ecology has many biases. 

First of all, we can highlight some issues with the way data was collected : 
 <ul>
  <li> First, we used a greedy approach to select the environmental linked quotes and we might have missed some.

  <li> Secondly, the speakers were selected so that the probability is greater than 0.5. Thus we are not entirely sure of our results and this can lead to mistakes in the gender of the speakers. 
  <li> Finally some speakers could be wrongly attributed by the algorithm which can also lead to some errors. 
 </ul>
 
The nature of the data itseld leads to some biases
All the quotes are extracted from English speaking only newspapers. Thus, it’s not totally representative of the ecology. In fact, it concerns mostly modern world developed and rich countries. 
Moreover, quotes were first extracted and processed by journalists to support a reasoning , and might not fully express what the speaker intended. We're dealing here with reported speech, and not direct quotations.

In a nutshell, our road throughout those quotes sketched some gender trends and supported some of our hypotheses, and can be further refined with a speaker specific approach or taking into account much more context about the speaker and the media the quote comes from !

 
 
 <h2> The pandas team 🐼  </h2>

 <table>
 <tr>
  <th> Brognart Blanche </th>
  <th> Descourtils Philippine     </th>
  <th> Louvet Alix </th>
  <th> Petronio Stella    </th>
 </tr>
 <tr>
  <td> <img src="_includes/photo.jpg" alt="Trulli"> </td>
  <td> <img src="_includes/Philippine.jpg" alt="Trulli"> </td>
  <td> <img src="_includes/WhatsApp Image 2021-12-17 at 15.05.58.jpeg"> </td>
  <td> <img src="_includes/CV2.jpg" alt="Trulli">  </td>
 </tr>
</table>

<h3> Our data </h3>

<h3> Our methods </h3>
 
</div>
 </body>
 </html>
