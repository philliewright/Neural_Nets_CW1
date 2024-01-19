## Toxic Comment Classification

## Introduction


In the modern, internet driven world, the threat landscape seen in online comments has grown increasingly worrysome and harmful. Polarisation in thinking is increasing and online harrassment for peoples opinions, beliefs and facets of their identity is a huge problem. These comments which can be harmful, offensive and disruptive can have sever impacts on the individuals and communities. We must tackle this problem in order to preserve the integrity and inclusivity of online spaces, in the form of content moderation.

We are looking to help takle this problem by using Neural Networks to find and classify toxic comments of different types. Neural Netwroks have the ability to process and learn from huge datasets of text and will be a promising place to come at a solution from. We will be using multilabel classification to attempt to label the comments as either Toxic, Severely Toxic, Obscene, Threat, Insult and Identity hate. We hope this model will be a good start for a tool to maintain healthy online interactions.

The origional source of the data is a collection of comments from Wikipedia's talk page edits. The dataset is the Toxic Comment Classification dataset from Kaggle, obtained using the following link:
https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge
Given the extensive nature of the dataset we feel it is a realistic cross section of the challenges which we'd expect to encouner in moderating real time online discussions.

We are going to follow the methodical approach of Francois Chollet's universal workflow of Deep Learning which we detail below.[1] We want to build a functional model but also fully understand the details of how the neural networks work in the context of NLP.


