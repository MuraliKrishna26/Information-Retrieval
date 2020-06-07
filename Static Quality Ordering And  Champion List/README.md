Dataset : 20newsgroup 
Data for Authoritative score : https://drive.google.com/file/d/1MJqyUr4Olus8AKJ_ecbeMMH6dEb5zGC1/view?usp=sharing

Desccription of Authoritative Score Data : 


     - The file containing the number of favourable reviews for each of the documents in the corpus.
     - The first column of this file denotes the doc no. and the second column denotes the corresponding number of favourable reviews.


The following concepts are implemented in the python program :

(a) You need to implement static quality ordering on the above corpus. You have to extract
a static quality score for each document from the number of favourable reviews as provided
above. Maintain a global champion list for each term sorted by a common ordering (i.e. static
quality score). This champion list for a term ‘t’ is made up of two posting lists consisting of a
disjointed set of documents. The first list is the high list containing documents with highest tf
values for ‘t’ and the second list is the low list containing other documents having term ‘t’. You
need to define a suitable heuristic to select the minimal efficient value of ‘r’ where ‘r’ is the
number of documents to be contained in the high list.

(b) You need to return K documents (where K will be given at runtime). During query
processing, only the high lists of query terms are scanned first to compute net scores and return
as output. If less than K documents are returned then go for low lists. Report proper analysis for
all the values of ‘r’ that you tried and the reason behind choosing that value of ‘r’.

