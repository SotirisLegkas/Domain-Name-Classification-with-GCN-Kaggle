Classification is a very popular task with multidisciplinary applications among which are bioinformatics, computer vision and natural language processing.

In this challenge, you are given a subgraph of the Greek web graph where nodes correspond to domain names (~65K domains). A directed edge between two nodes indicates that there exists a hyperlink from at least one page of the source domain to at least one page of the target domain. Furthermore, your are provided with the textual content of webpages crawled from a subset of these domain names (~40K domains).

A subset of these domains were manually classified into 10 categories and split into a training and a test set.

Your task is to predict the categories to which the domain names of the test set belong using graph-theoretical, textual, and other information. You are being provided with starting code that displays this task as a classification problem.

For each domain name of the test set, your model should predict the category to which this domain name belongs.

The evaluation metric for this competition is the logarithmic loss. This metric is defined as the negative log-likelihood of the true class labels given a probabilistic classifier's predictions.
