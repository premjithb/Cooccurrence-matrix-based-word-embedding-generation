# Cooccuurence-matrix-based-word-embedding-generation
Word embedding for each word in the corpus is implemented as follows
<br> 1. Created the cooccurrence matrix
<br> 2. Computed the positive point wise mutual information (PPMI) matrix
<br> 3. Take the svd of the PPMI matrix as, **u,sv = SVD(PPMI)**
<br> 4. Word embedding for a word is computed as **embedding = us** and columns of **v** contains the context vectors
