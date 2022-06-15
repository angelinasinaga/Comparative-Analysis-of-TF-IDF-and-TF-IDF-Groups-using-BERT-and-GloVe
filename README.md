# Comparative Analysis of TF-IDF and TF-IDF Groups using Glove and GloveBERT
This repository is used to store artifacts for the 12S4055 - Information Retrieval course project at Del Institute of Technology.

## Abstract
Rigidity in finding information and a lot of noise are problems that often occur in knowledge management which has the concept of information retrieval in identifying, explaining and distributing information for use obtained from documents or collections. Currently the
development of information retrieval is very interesting to discuss and research, because the application of information retrieval can help over-
come some of the problems above. The use of TF-IDF has been widely used because it is simple in the process of calculating keywords or queries
and is easy to use in measuring content uniqueness, as well as low-cost computational processes. However, so far the implementation of the TF-
IDF Group on IR has not been implemented. **In this project, we compare the performance of TF-IDF with TF-IDF Group by using word embed-
ding method: GloVe and GloVeBERT, where the document grouping process is done using Minibatch K-Means (Cosine Sim). The first stage
is text preprocessing which consists of case folding, stopwords, tokenization and stemming stages, the second stage is weighting using TF-IDF
and TF-IDF Group, the third stage is applying the method used,thencalculate the cosine similarity and the last stage is evaluating.**

## Dataset
1. Spam Dataset
2. BBC News Dataset

## Main Contribution
1. Propose the Glove and GloveBERT models to make comparisons on the TF-IDF and TF-IDF Group.
2. Grouping documents using Mini batch to clustering or grouping document. 
3. Calculated cosine simiality to check similar from one document to another document.
4. Conducted experiments on two sets of data sets, namely Spam and BBC News to compare the results of the two applied methods.
## Conclusion
1. In the comparison of TF-IDF with TF-IDF Group the value of TF-IDF Group is higher than TF-IDF in the GloVe and GloVeBERT approach for Spam          datasets
2. In the comparison of TF-IDF with TF-IDF Group the value of TF-IDF Group has the same value with only TF-IDF on the GloVe approach and the            GloVeBERT approach for the BBC News dataset
3. Value Cosine Similarity in both datasets, is quite high, this indicates that one document is similar to another in the two datasets.
4. Combining Glove with BERT has a decreasing effect on both the cosine simialrity value and the model accuracy value.
5. In contrast to the accuracy values in the Spam dataset in both models, the accuracy values from the Glove and GloveBERT models in the BBC News
   dataset are low.
## Evaluation
![image](https://user-images.githubusercontent.com/60686944/173781962-6ad57097-5bd0-48df-a809-c215fe60bca3.png)

