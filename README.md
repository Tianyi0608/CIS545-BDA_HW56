# CIS545-BDA_HW56
Use gensim dictionary to do amazon review analysis and classification (NLP)
1. Create corpora.Dictionary and doc2bow (spares)
2. Create dense matrix
3. Create word-context matrix and use PCA to decomposition, then sppmi
4. PCA to decomposition on dense doc2bow: doc-vecs, vecs-word
5. Create doc-vecs matrix use decomposed word-context matrix with or without sppmi
6. Scale the doc-vecs matrix (minmax, standard, log, exponential, binary)
7. Use different models to do classification: decision tree, random forest, linear regression, svm, nn

First: generate dict and bow use gensim; second: matrix decomposition to doc-vecs matrix use PCA, word-context and other formulas(sppmi) and PCA; third: do classification use different doc-vecs (scaled) and different models

Results: 1.NN with four layer and 12-14 nodes each layer has best performance 2. different ways of scaling data may works for different models well
