# Data Science Challenge

Thank you for taking time to do the Mantel Group Data Science challenge. We're looking forward to hearing your thoughts and your approach to these common client asks we've recreated! 

The challenge contains two exercises. Because this is the tool we most commonly use across Mantel Group, our preference is that you complete exercise 2 in Python. You are welcome to create a Jupyter notebook and use any Python packages. Please send your submission via email, including your code for exercise 2 and any materials for exercise 1.

The purpose of this challenge is to allow us to kick off the conversation to dive a little deeper into your consulting and technical experience. This is a chance for you to demonstrate how you might approach business problems but we don't expect you to perform every possible variation and approach! Don't stress if you're tight on time - we get it, you have a life outside of applying for jobs - we're not expecting you to spend endless hours perfecting it, just make sure you do enough to demonstrate your abilities in data science. In exercise 1 we're looking to explore how you would approach solving business problems in a client setting, while exercise 2 focuses on some of the core data science skills.

## Exercises

### Exercise #1

Eliiza are approached by an artisan brewer who is considering adding a new hoppy beer to their range - India pale ale (IPA). The client's marketing team would like to know how consumers feel about this product and how the attitude toward IPA beer has changed over the past few years. They believe a question-answering website such as [beer.stackexchange.com](https://beer.stackexchange.com/) could be used as a source of genuine opinions.

Given this information, you are asked to prepare for the initial meeting with the prospective client where you will represent Eliiza as a domain expert and help with sourcing information to shape the engagement. 
It may help to think about:
- what approach could be recommended
- what further information do we need
- what the deliverables should be
- how can success be measured

No code is expected for this exercise, and a slide or two describing what you would present to the client's marketing team is sufficient to guide our conversation.

### Exercise #2

Use the dataset in `./dataset/questions.csv` to develop a classifier to predict the forum based on the question body. Your objective is to maximise the model’s performance, however, we encourage you to avoid spending time training multiple models. You are free to preprocess the data as you like and use any classification algorithms.
Produce a Jupyter Notebook that includes all code, details, and decisions made over the course of your model development.

#### Data
We have compiled a dataset for exercise 2 (can be found in the `./dataset/` folder), which is described below.

The data is compiled from [Stack Exchange data dump](https://archive.org/download/stackexchange), which is distributed under [Attribution-ShareAlike 4.0 International license](http://creativecommons.org/licenses/by-sa/4.0/). 

Of the Stack Exchange forums, we have selected `ai, astronomy, beer, coffee, computergraphics, martialarts, opendata, quantumcomputing, sports`.

The schema for the data can be found [here](https://meta.stackexchange.com/questions/2677/database-schema-documentation-for-the-public-data-dump-and-sede/2678#2678).

Modifications:
- Extracted question bodies for Exercise 2.
