# Word2Vec word embedding analysis on Autism Spectrum Disorder (ASD) articles abstracts available on Pubmed.
As my first experience with Natural Language Processing (NLP) I decided to explore word embeddings in abstracts related to my PhD research topic which is Autism Spectrum Disorder (ASD).
<br>
<br>
Briefly, Biopython Entrez module was used to fetch the abstracts from NCBI's database and after a series of preprocessing steps (unwanting characters removal, stop words removal and word stemming) the Word2Vec neural network was used for learning vector representations of words ("word embeddings").

## Files
```
- AutismArticlesRaw_v2.csv: dataset containing the abstracts, PMID of each article, article title and publication year.
- PreProcessedAbstracts_v2.csv: same as AutismArticlesRaw_v2.csv but with the preprocessed abstracts.
- autismPMIDlist.txt: PMID list used to fetch the abstracts from the NCBI's database.
- Part_1_ASD_papers_word2vec.ipynb: first analysis with 21148 abstracts.
- Part_2_ASD_papers_word2vec.ipynb: final analysis with improved dataset and 37518 abstracts.
- first_model.png: first model t-SNE plot.
- final_model.png: final model t-SNE plot.

```

## References
- Mikolov, T., Chen, K., Corrado, G., & Dean, J. (2013). Efficient estimation of word representations in vector space. arXiv preprint arXiv:1301.3781.
- [A Beginner's Guide to Word2Vec and Neural Word Embeddings.](https://skymind.ai/wiki/word2vec)
- [Using word2vec to analyze word relationships in Python](http://methodmatters.blogspot.com/2017/11/using-word2vec-to-analyze-word.html)
