![thumbnail_original-1](https://user-images.githubusercontent.com/29679899/59774825-207b5900-927e-11e9-8560-f8c8c454ec25.png)
![thumbnail_original](https://user-images.githubusercontent.com/29679899/59774888-3852dd00-927e-11e9-812d-61dc8d47af1a.png)

Extracted over 300k text documents from consented Facebook Messenger 
users occupying the same group for 7 years. 

Cleaned, prepared and transformed semi-structured data into a dataset. 

Performed exploratory analysis and engineered features using dimensionality reduction techniques PCA and t-SNE. 

Used multiple frequentist, Bayesian and deep learning classification algorithms to identify 
unlabeled text weighted by Word2vec and pretrained word embeddings with GloVe. 

Derived topics and sentiment from unstructured data using semi-supervised and 
unsupervised latent dirichlet allocation. 

Preserved a global view of user topics and distilled each user into a mixture of topics using t-SNE.

Primarily based on discussion with mental health professionals and loosely based on dimensions of the Big Five OCEAN personality model[<a href="https://positivepsychology.com/big-five-personality-theory" rel="nofollow">1</a></li>] and other sources[<a href="https://www.ncbi.nlm.nih.gov/pubmed/10626371" rel="nofollow">2</a></li>][<a href="https://www.aclweb.org/anthology/W16-0307" rel="nofollow">3</a></li>][<a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.224.4752&rep=rep1&type=pdf" rel="nofollow">4</a></li>][<a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5902561/" rel="nofollow">5</a></li>], a combination of selected users’ final topics and phrases were used to determine interests and identify troubled language signaling distress and possible mental health crisis.


i. <b>Extraction and Exploration</b>

	i. Extraction, exploration, feature extraction, initial cleaning & common-word visualization
	ii. Zipf’s Law
	iii. Feature distributions by user and additional cleaning

ii. <b>Deep Learning</b>

	iv. Additional exploration with Word2vec and GloVe
	v. Softmax, LeakyReLU and Sigmoid visualizations 
	vi. Export Word2vec embeddings
	vii. Diagnosing text using edm
	viii. Attention based bidirectional lstm rnn

iii. <b>Shallow Learning and Topic Modeling</b>

	ix. tfidf-cv weighted embeddings trained on engineered features with: 

		i. logistic regression 
		ii. naive bayes 
		iii. xgboost 
		iv. support vector machines

	x. Topic modeling with vanilla-lda
	xi. Labeled-lda implementation with inference via Gibbs sampling
	xii. Defined l-lda seeds
	xiii. Compare distance of user probability distributions
