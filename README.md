## The Bell Jar through Python magnifying glass

## Abstract
"The Bell Jar" by Sylvia Plath is a classic American coming of age novel. Set in the 1950s, shows an America shaped by conservative values and a patriarchic structures, a society that placed women under particular restraints.
The ideal of purity, chastity, the aspiration to live as suburban mother and homemaker, rather than pursuing their own career, mentally weighted on the author as well, as they are some of the main themes of book.
The goal of my project is to observe and analyse this novel through Python, and compare computational methods to a human analysis.
I decided to work on this topic as was interested in Sentiment Analysis and I believe a novel like this, which is able to portray depression, suicide and mental hospitalisation, could have been a very interesting fit.
## Research questions
Is Sentiment Analysis able to perceive the development of mental illness? Which method works best?
Is it possible to analyse a book in a detailed manner through Python?

## Dataset
The dataset used is the book "The Bell Jar" by Sylvia Plath, downloaded for free as it's of public domain, as a .txt file. This file was then cleaned: the book's header was removed, then has been converted to a csv file and split into chapters. Later on, was tokenized.
For the Sentiment Analysis with transformers (HuggingFace), it was split into chunks, as this operation is computationally heavy, and doing so made it possible to run it on my computer's CPU.

## A tentative list of milestones for the project
Week1 = Downloading the book, cleaning the data and get the csv file (cleaning_the_jar.ipynb)

Week2 = Working on the Sentiment Analysis (feeling_the_jar.ipynb)

Week3-4 = Working on the rest of the text's analysis (analysing_the_jar.ipynb)

Week5-6 = Writing the report, setting up the GitHub page, final checks and submitting the project

## Documentation
Downloading the book: 
https://www.fadedpage.com/showbook.php?pid=20160540

Tutorials:
https://www.youtube.com/watch?v=QpzMWQvxXWk (sentiment analysis)

https://www.youtube.com/playlist?list=PL2VXyKi-KpYttggRATQVmgFcQst3z6OlX (topic modeling)

https://www.youtube.com/watch?v=HcKUU5nNmrs (wordcloud)

https://www.youtube.com/watch?v=ollW8lwZxNE (networkX)

_These tutorials were used as learning material, doesn't mean the code in the project is a replica of those_

Websites:
https://www.nltk.org
https://scikit-learn.org/stable/
https://www.nltk.org/howto/concordance.html
https://medium.com/@onubachibuike/vader-vs-roberta-a-comparison-of-sentiment-analysis-models-72f8ceb1934b
https://pypi.org/project/wordcloud/
https://networkx.org/documentation/stable/reference/introduction.html
https://towardsdatascience.com/end-to-end-topic-modeling-in-python-latent-dirichlet-allocation-lda-35ce4ed6b3e0

Report material:
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9331452/
https://scholarworks.iu.edu/journals/index.php/plath/article/view/4714/4350
https://research.reading.ac.uk/research-blog/2018/02/05/people-with-depression-use-language-differently-heres-how-to-spot-it/
https://journals.sagepub.com/doi/full/10.1177/0261927X15589186
