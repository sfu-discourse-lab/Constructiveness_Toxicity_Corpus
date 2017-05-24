# constructiveness_toxicity_annotations

The CSV file contains annotations for constructiveness and toxicity in news comments.

# Paper
This work is described in a paper to appear in the Proceedings of the First Workshop on Abusive Language Online, at the Meeting of the Association for Computational Linguistics in Vancouver, August 2017. https://sites.google.com/site/abusivelanguageworkshop2017/

Kolhatkar, Varada and Maite Taboada (2017) Constructive language in news comments. *Proceedings of the First Workshop on Abusive Language Online, Association for Computational Linguistics.* Vancouver, August 2017. 

# Data
A collection of 1,121 comments posted in response to opinion articles, on the website of the newspaper The Globe and Mail (https://www.theglobeandmail.com/). Comments were responses to 10 different articles covering a variety of subjects: technology, immigration, terrorism, politics, budget, social issues, religion, property, and refugees. For half of the articles, we included only top-level comments. For the other half, we included both top-level comments and responses. 

# Annotations
We used CrowdFlower (https://www.crowdflower.com/) as our crowdsourcing annotation platform and annotated the comments for constructiveness. We asked the annotators to first read the articles, and then to tell us whether the displayed comment was constructive or not using the above definition of constructiveness. For quality control, 100 units were marked as gold: Annotators were allowed to continue with the annotation task only when their answers agreed with our answers to the gold questions. As we were interested in the verdict of native speakers of English, we limited the allowed demographic region to English-speaking countries. We asked for three judgments per instance and paid 5 cents per annotation unit. 

Percentage agreement for the constructiveness question was 87.88, suggesting that constructiveness can be reliably annotated. (Other measures of agreement, such as kappa, are not easily computed with CrowdFlower data, because many different annotators are involved.). Constructiveness seemed to be equally distributed in our dataset: Out of the 1,121 comments, 603 comments (53.79\%) were classified as constructive, 517 (46.12\%) as non-constructive, and the annotators were not sure in only one case. 

For toxicity, we asked annotators a multiple-choice question: 

How toxic is the comment? Four answers were possible:

  - Very toxic
  - Toxic
  - Mildly toxic
  - Not toxic

The definition for Very toxic included comments which use harsh, offensive or abusive language; comments which include personal attacks or insults; or which are derogatory or demeaning. Toxic comments were sarcastic, containing ridicule or aggressive disagreement. Mildly toxic comments were described as those which may be considered toxic only by some people, or which express anger and frustration.

Percentage agreement for this task was 81.82. The most important result of this annotation experiment is that there were no significant differences in toxicity levels between constructive and non-constructive comments, i.e., constructive comments were as likely to be toxic (in its three categories) as non-constructive comments.


