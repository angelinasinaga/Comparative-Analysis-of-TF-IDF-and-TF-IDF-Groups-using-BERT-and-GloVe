# Comparative Analysis of TF-IDF and TF-IDF Groups using Glove and GloveBERT
This repository is used to store artifacts for the 12S4055 - Information Retrieval course project at Del Institute of Technology.

## Abstract
Rigidity in finding information and a lot of noise are problems that often occur in knowledge management which has the concept of information retrieval in identifying, explaining and distributing information for use obtained from documents or collections. Currently the development of information retrieval is very interesting to discuss and research, because the application of information retrieval can help overcome some of the problems above. The use of TF-IDF has been widely used because it is simple in the process of calculating keywords or queries and is easy to use in measuring content uniqueness, as well as low-cost computational processes. However, so far the implementation of the TF- IDF Group on IR has not been implemented. **In this project, we compare the performance of TF-IDF with TF-IDF Group by using word embedding method: GloVe and GloVeBERT, where the document grouping process is done using Minibatch K-Means (Cosine Sim). The first stage is text preprocessing which consists of case folding, stopwords, tokenization and stemming stages, the second stage is weighting using TF-IDF and TF-IDF Group, the third stage is applying the method used, then calculate the cosine similarity and the last stage is evaluating.**

## Dataset
1. Spam Dataset
2. BBC News Dataset

## Main Contribution
1. Propose the Glove and GloveBERT models to make comparisons on the TF-IDF and TF-IDF Group.
2. Grouping documents using Mini batch to clustering or grouping document. 
3. Calculated cosine simiality to check similar from one document to another document.
4. Conducted experiments on two sets of data sets, namely Spam and BBC News to compare the results of the two applied methods.

## Conclusion
1. In the comparison of TF-IDF with TF-IDF Group, the value of TF-IDF Group is higher than TF-IDF in the GloVe and GloVeBERT approaches for the Spam dataset. 
2. In the comparison of TF-IDF with TF-IDF Group the value of TF-IDF has the same value as TF-IDF Group on the GloVe approach and the GloVeBERT approach for the BBC News dataset. 
3. The value of Cosine Similarity in both datasets is quite high, this indicates that one document has similarities to the other in both datasets. 
4. Combining Glove with BERT has a decreasing effect on both the cosine similarity value and the model accuracy value. 
5. Unlike the accuracy values in the Spam dataset in both models, the accuracy values from the Glove and GloveBERT models in the BBC News dataset are low.
   
## Evaluation
![image](https://user-images.githubusercontent.com/60686944/173850143-4e14403a-99c5-4522-a710-097dcc7a2486.png)

## TF-IDF VS TF-IDF Group
1. Spam Dataset
![image](https://user-images.githubusercontent.com/60679993/173869488-3051c232-b323-487e-92f0-26f5fae48aa5.png)

2. BBC-News Dataset
![image](https://user-images.githubusercontent.com/60679993/173869735-32ee2652-1fd4-4840-8eca-8238cf4ed8a4.png)

