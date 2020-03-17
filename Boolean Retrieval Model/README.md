# Unigram Inverted Index

This python file has the implementaion of Unigram Inverted Index and Queries with bolean operator such as and,or,not.

Provide support for the following commands:



      - x OR y
      - x AND y
      - x AND NOT y
      - x OR NOT y
      
      
The queries can be of more than 2 words of the form: "x OP1 y OP2 z" where OP1, OP2 = AND, OR, NOT.

Given a query, the model outputs : 
      
      
      - the number of docs retrieved
      - the minimum number of total comparisons done (if any)
      - the list of documents retrieved.


Preprocessing used : 


                - Removal of stop words.
                - Removal of Block words(These are hand annotated).
                - Tokenization.
                - Lemmatization.
                - Tokens with less than length 2 are not considered.









