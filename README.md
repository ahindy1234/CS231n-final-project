# CS231n-final-project
CS231n Final Project (Ali and Will)

## Abstract
In this paper, we extend the commonly used text-based Retrieval Augmented Generation (RAG) architecture to the problem of downstream vision in the context of instruction manual understanding. We use a multimodal text and image embedding hybrid model for the retrieval task that outperforms vanilla RAG. We build a custom dataset for this task and introduce a contrastive learning framework for better retrieval results. We compare these results to baseline retrieval models, and discuss the implications in our overall question-answering RAG pipeline. Our learned retrieval system achieves \bm{$25$}\textbf{\% top-1} accuracy and \bm{$83$}\textbf{\% top-5} accuracy on our custom dataset, significantly outperforming vanilla RAG.


## Steps to Run
- data\_augmentation/embeddings.ipynb - Generate image embeddings
- data\_augmentation/data\_augmentation.ipynb - Generate data augmentation 
- retriever.ipynb - Run retriever and generator model
