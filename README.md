# MP4 Neural Ranking Methods

### Due Nov 11th,2022 at 11:59pm

In this MP you will explore how you can use Neural Network based methods for ranking for information retrieval. The goal of this assignment is to get you familiar with some popular approaches appling neural methods for information retrieval. 


## Retrieval Using Bi-Encoders/Dual Encoders
While term based retireval based methods are effective they are commonly not effective at understanding semantic differences which are common in text. A tutorial on how to use semantic retrieval can be found in the ANNSearch notebook.

In this portion of the assignment you will leverage the use of Bi encoder models to perform semantic search on the CS410 document corpus. Using sentence transformers and ANN indexes you will search semantically. Your outputed ranking should match the TREC format (#QUERY_ID\t0 DOCUMENTID\tRANK\tSCORE\trunid) and you can use the TRECEVAL notebook to explore how well diferent models perform. 

To avoid long inference times we have gone ahead and generate a few sets of embeddings for the document and query corpus. If you want to explore further and look for other models they can be found in the [sentence transformer library](https://huggingface.co/sentence-transformers)

### Tips and Suggestions
To learn more about the how to use ANN retrieval we suggest checking out [this demo](https://github.com/facebookresearch/faiss/wiki/Getting-started). Another great resource is [Pinecone](https://www.pinecone.io/learn/faiss-tutorial/)

To learn more about the models which can be used for semantic search check out [SBERT](https://www.sbert.net/)
 
## Reranking using Cross Encoders
https://github.com/castorini/pyserini
https://ir-measur.es/en/latest/getting-started.html#run-formats
### Tips and Suggestions
