# NLP and Text_Mining


In this notebook I will be adressing NLP and text mining tasks, starting off with the basics and then moving on to implementing some ideas from NLP articles into working codes. then some higher level concepts like Transformers,BERT and attention etc...
 
 
 
# first project : Scientific Articles' abstract text mining.s

- This project is comprised of 3 parts:
1. Textuel Analysis 
2. EDA ( Exploratory Data Analysis )
3. Clustering.


# Second project : Dimensionality Reduction and clustering + interprability.

## This project is comprised of 2 parts:
### PART1:
1. Tokenizing the text using:
    * Word2Vec
    * GloVe 
2. Clustering on orignal data (Classic 4 data which comprises of scientific articles' abstracts , and BBC data which contains headlines from the bbc news channel )
    * This is done on the data without any dimensionality reduction technique
    * We will be using this to benchmark against later methods
3. Using Tandem methods, this is done by using :
    * dimensionality reduction technique ( PCA , t-SNE , UMAP , Autoencoders)
    * Followed by a clustering technique ( Kmeans, Spherical Kmeans , factorial Kmeans , Hierarchal clustering(WARD , Complete , Linkage and Single Metrics), and HDBSCAN 
5. Clustering using combined methods ( where the dimension reduction and clustering are done at the same time ):
    * Reduced kmeans
    * Factorial kmeans  
    * Deep Clustering Network
    * deep KMeans
 
### PART2:
1. Tokenizing the text using :
    * BERT
    * RoBERTa 
2. Clustering on orignal data (Classic 4 data which comprises of scientific articles' abstracts ,  BBC data which contains headlines from the bbc news channel ,article1 data which comprises of news headlines , article2 data which comprises of wikipedia summaries.)
    * This is done on the data without any dimensionality reduction technique
    * We will be using this to benchmark against later methods.
3. Using Tandem methods, this is done by using :
    * dimensionality reduction technique ( PCA , t-SNE , UMAP , Autoencoders)
    * Followed by a clustering technique ( Kmeans, Spherical Kmeans , factorial Kmeans , Hierarchal clustering(WARD , Complete , Linkage and Single Metrics), and HDBSCAN.
5. Clustering using combined methods ( where the dimension reduction and clustering are done at the same time ):
    * Reduced kmeans
    * Factorial kmeans
    * Deep Clustering Network
    * deep KMeans
