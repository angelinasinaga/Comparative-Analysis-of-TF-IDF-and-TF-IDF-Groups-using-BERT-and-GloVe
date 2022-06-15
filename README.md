# Comparative-Analysis-of-TF-IDF-and-TF-IDF-Groups-using-Glove-and-GloveBERT
This repository is used to store artifacts for the 12S4055 - Information Retrieval course project at Del Institute of Technology.

## Abstract
Rigidity in finding information and a lot of noise are problems that often occur in knowledge management which has the concept of information retrieval in identifying, explaining and distributing information for use obtained from documents or collections. Currently the development of information retrieval is very interesting to discuss and research, because the application of information retrieval can help overcome some of the problems above. The use of TF-IDF has been widely used because it is simple in the process of calculating keywords or queries and is easy to use in measuring content uniqueness, as well as low-cost computational processes. However, so far the implementation of the TF-IDF group on IR has not been implemented. **In this project, we compare the performance of TF-IDF with TF-IDF Group by using word embedding method: BERT and GloVe, where the document grouping process is done using Minibatch K-Means (Cosine Sim).** The first stage is text preprocessing which consists of case folding, stopword, tokenization and stemming stages, the second stage is weighting using TF-IDF and TF-IDF Group, the third stage is applying the method used and the last stage is evaluating. 

## Dataset
1. Spam Dataset
2. BBC News Dataset

## Main Contribution
1. Propose BERT and Glove models to be used as comparisons for TFIDF and TF-IDF Group.
2. Grouping documents using Mini batch K-Means (Cosine Sim). Before grouping documents, perform document expansion (following the query expansion concept)
3. Conducting experiments on two datasets, namely Spam and BBC News to compare the results of the two methods applied.

## Conclusion
1. From the results of our experiments on two datasets, the cosine similarity and accuracy values are quite high.
2. Combining Glove with BERT gives the effect of decreasing the value of cosine similarity and decreasing the value of accuracy on the model.
3. To get a higher yield, we propose a comparison of TF-IDF with TF-IDF Group preferably using the Glove method
