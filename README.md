# Eliiza Data Science Challenge

The challenge contains two exercises. Please complete it in Python. You are welcome to create a Jupyter notebook and use any Python packages. Please send your submission via email, including your code for both exercises and the slide for exercise 1.

## Data
We have compiled datasets for this challenge (can be found in the `./dataset/` folder), which are described below.

The data is compiled from [Stack Exchange data dump](https://archive.org/download/stackexchange), which is distributed under [Attribution-ShareAlike 4.0 International license](http://creativecommons.org/licenses/by-sa/4.0/). 
The content license of individual posts/comments is as indicated by the `ContentLicense` field (e.g. [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) or [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)).

Of the Stack Exchange forums, we have selected `beer.stackexchange.com` for Exercise 1, and `ai, astronomy, beer, coffee, computergraphics, martialarts, opendata, quantumcomputing, sports` for Exercise 2.

The schema for the data can be found [here](https://meta.stackexchange.com/questions/2677/database-schema-documentation-for-the-public-data-dump-and-sede/2678#2678).

Modifications: 
- Omitted irrelevant files apart from `Comments.xml` and `Posts.xml` for Exercise 1;
- Extracted question bodies for Exercise 2.

## Exercises

### Exercise #1

You are approached by an artisan brewer who is considering adding a new hoppy beer to their range - India pale ale (IPA).
The clients' marketing team would like to know how consumers feel about this product and how the attitude toward IPA beer has changed over time. They identified a question-answering website as a source of genuine opinions.
Use the XML datasets found in `./dataset/beer.stackexchange.com/` for this exercise. To read the XML data, you can use your own method or the `read_xml.py` script provided in this repo.

Please prepare a slide or two to describe your analysis and present your results for the client's marketing team.

### Exercise #2

Use the dataset in `./dataset/questions.csv` to develop a classifier to predict the forum based on the question body. Your objective is to maximise the model's performance. You are free to preprocess the data as you like and use any classification algorithms.
Produce a Jupyter Notebook that includes all code, details, and decisions made over the course of your model development.
