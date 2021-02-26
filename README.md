# Project-4: What makes people happy?
## Description
This project used topic modeling and scattertext plots to explore what makes people happy by demographic and how families influence one another's happiness. 

## Data
I got my data from a company called [Megagon Labs](https://megagon.ai/projects/happydb-a-happiness-database-of-100000-happy-moments/). Megagon Labs is an innovation hub that decided to create an app where people write down what made them happy that day. They wanted to add in a chatbot that could ask follow-up questions or suggest other things that might make them happy.

In creating the chatbot, they realized that understanding happy moments is a challenging NLP problem, so to help solve that problem they collected 100,000 responses on Mechanical Turq where people were asked, ‘What made you happy in the past 24 hours?’ or ‘What made you happy in the past 3 months?’ They then made their data publicly available on [GitHub](https://github.com/megagonlabs/HappyDB).

## Tools Used
* Pandas and Numpy
* Seaborn and Matplotlib
* Wordcloud
* Nltk

## Data Cleaning and Preprocessing
* Dropped null values
* Removed punctuation, words with numbers, and specific stop words. 
* Made all words lower case
* Tokenized the responses by word
* Lemmatized words
* Added linguistic annotations
* Cleaned demographic information

## Data Exploration
How the source of happiness differs by:
* Countries
* Age
* Martial Status
* Mothers vs Fathers
* Parent vs Non-Parent

How families influence one another's happiness:
* How children make their parents happy
* How parents make their children happy
* How husbands and wives make one another happy

Other interesting findings:
* Mothers are mentioned more often than fathers
* Daughters are more likely than sons to mention their parents as a source of happiness
