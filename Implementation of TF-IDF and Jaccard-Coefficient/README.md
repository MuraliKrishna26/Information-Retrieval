# Implementation of Jaccard-Coefficient , TF-IDF based on document retrieval and vector space document retrieval.

Dataset : Download stories dataset from http://archives.textfiles.com/stories.zip.


Preprocessing steps :

            -- Word Tokenization.
            -- Removal of stop words.
            -- Converting to lower cases.
            -- Removal of punctuation and apostrophes.
            -- Converting numbers into words
            
            
Methods Implemented :

 - ***Jaccard Coefficient based document retrieval*** : For each query, the model will output top k documents based on jaccard score.
 - ***Tf-Idf based document retrieval*** : For each query, the model will output top k documents based on tf-idf-matching-score. Here we have implemented all the versions of tf i.e natural,logarithmic,augmented,boolean,log average.
 - ***Tf-Idf based vector space document retrieval*** : For each query, the model will output top k documents based on a cosine similarity between query and document vector.
 - Given special attention to the terms in the document title.
 
 








