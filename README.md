# text-summarization

In this notebook, we will use Natural Language Processing for **Summarization Task**. 
In this task, a summary of a given article/document is generated when passed through a network. There are 2 types of summary generation mechanisms:

1. ***Extractive Summary:*** the network calculates the most important sentences from the article and gets them together to provide the most meaningful information from the article.

2. ***Abstractive Summary***: The network creates new sentences to encapsulate maximum gist of the article and generates that as output. The sentences in the summary may or may not be contained in the article. 

In this project, we will be generating ***Abstractive Summary*** (fine tune a Transformer) and  a bonus with ***Extractive Summary*** (Autoencoder).

Project done as part of the Machine Learning for Natural Language Processing course, taught during the third year of the engineering cycle at ENSAE Paris, supervised by Benjamin Muller (INRIA).

**Authors :** Ryan Boustany, Emma Sarfati

**April 24th, 2021**

# Note
Please download train model at the following link: https://drive.google.com/file/d/1t21ljrCFvc2YPboEao2f0wvpoyW9EcT3/view?usp=sharing

Or, the full repo on Google Drive (model + data): https://drive.google.com/drive/folders/11PJ9U4rm0N9lvyA4YXAabfAGuBj7yueh?usp=sharing
