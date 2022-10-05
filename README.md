## Question Answering
The Question Answering task in NLP pertains to building a model which can answer questions posed in natural language. Many datasets (including SQuAD, the dataset we use in this notebook) pose this as a reading comprehension task i.e. given a question and a context, the goal is to predict the span within the context with a start and end position which indicates the answer to the question. For every word in the training dataset we predict:

1.likelihood this word is the start of the span
2.likelihood this word is the end of the span
The best place to get started with TAO Toolkit - Question Answering would be the TAO - Question Answering jupyter notebooks. This resource has two notebooks included.

**Training:** Sample workflow for training a question answering model and export the model to a .riva file
**Deployment:** Sample workflow to consume the .riva file and deploy it to Riva.

## About Quick Deploy
The quick deploy feature automatically sets up the Vertex AI instance with an optimal configuration, preloads the dependencies, runs the software from NGC without any need to set up the infrastructure.
