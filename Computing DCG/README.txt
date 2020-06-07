Dataset : Microsoft Learning to Rank Datasets 
Link : https://www.microsoft.com/en-us/research/project/mslr/?from=http%3A%2F%2Fresearch.microsoft.com%2Fen-us%2Fprojects%2Fmslr%2Fdownload.aspx   or dataset is provided as "IR-assignment-3-data.txt" in the current repository

Computing_DCG Python file answers the following questions : 
        
        
        
       - a) Make a file having URLs in order of max DCG. State how many such files could be made.
       - b) Compute nDCG
                i. At 50
                ii. For the whole dataset
           For the above two questions, results have to be produced for qid:4 only and consider the
           relevance judgement labels as the relevance score.
       - c) Assume a model that simply ranks URLs on the basis of the value of feature 75 (sum of
           TF-IDF on the whole document) i.e. the higher the value, the more relevant the URL.
           Assume any non zero relevance judgment value to be relevant. Plot a Precision-Recall
           curve for query “qid:4”.
