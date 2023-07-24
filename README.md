
# Hyphen Senior ML Engineer Coding Challenge

Hey 👋! Congratulations on getting to coding challenge stage.

The purpose is to allow you to get hands-on and write some actual code, which we will review and discuss during your technical interview.

The objective of this challenge is to develop a rudimentary Python script that generates a knowledge graph from a given text snippet. The task will require you to implement Natural Language Processing techniques such as Named Entity Recognition (NER) and Relationship Extraction (RE) for the generation of the knowledge graph.

## Task Description

### Input
You will be provided with a short text paragraph containing multiple sentences (`input.txt`). The text will contain various named entities and their relationships which would be required for the generation of a knowledge graph.

### Process

Your task is to write a Python script that does the following:

1. **Text Preprocessing:** Implement basic preprocessing tasks like lower casing, punctuation removal, tokenization etc.

2. **Entity Recognition:** Identify the named entities present in the text.

3. **Relationship Extraction:** Implement a strategy to determine the relationships between the entities identified in the previous step. This might involve rule-based methods, dependency parsing, or even a simpler co-occurrence strategy depending on what you see fit.

4. **Knowledge Graph Generation:** Use the recognized entities and relationships to construct a knowledge graph. This could be a simple network diagram where nodes represent entities and edges represent relationships between them. Libraries like NetworkX, graph-tool or PyGraphviz can be used for this.

### Output
The final output should be a visual representation of the knowledge graph generated from the given text. This can be displayed as a plot in a Jupyter notebook or saved as an image file.

### Evaluation
There are no specific 

## Technical Requirements
* The challenge should be done in Python, and you may use any Python libraries you find appropriate, as well as Jupyter if you like. However, remember to include a requirements.txt file for any external libraries used.
* You may use any models that you see fit for the challenge
* There are no performance requirements or evaluation metrics defined. Give it your best shot, and let's discuss performance and evaluation of different approaches at the interview.

## Practical

* Please don't spend more than 90 minutes on this exercise. This is meant to be a starting point for our technical discussion and does not need to be a fully polished, production-ready application. We are more interested in your approach and problem-solving skills. You can note the things you would have done if you had more time and we can discuss it during the interview if you like.

* Share with us your git repo link, at the latest 24 hours before your interview (Github usernames: @simonwh @pax-k @Volland)

Have fun!
