# *Abstract:*
The goal of this project was to use unsupervised learning algorithms to create a model that is able to classify the type of story if it is suitable for children or not. We did web scraping on a site specializing in Arabic stories to get the data.
We applied several models to get the best results, and in the end, we got a model capable of making clusters with high accuracy.

# *Design:*
The project will help story sites to categorize stories that are appropriate for children, and will also help parents because they struggle to notice what their children are reading for fear that they will read stories that are not appropriate for their age, such as horror stories.

We used several types of stories, such as horror, police, wars, and children, and we built a model capable of collecting stories that are suitable for children in one cluster and not suitable for children in another cluster.

# *Data:*
It is an Arabic site specialized in publishing various and renewed stories. We decided to focus on children's stories, horror, police, and wars. The dataset consists of 1020 Rows and 1 feature, which is a text.

# *Algorithms:*
We did prepressing to convert unstructured text into structured text and included several steps, including removing unnecessary information, lemmatization and Construct document-terms matrix.
* Models:
Non-negative matrix factorization (NMF), Latent semantic analysis (LSA), Clustring with original data, Clustring with data after LSA, Clustring with data after NMF.
* Best model:
Clustring with data after NMF

Where he classified the test data with high accuracy and reached 100%.
# *Tools:*
* -Numpy and Pandas for Data Manipulation
* -Matplotlib and Seaborn and wordcloud ,ImageColorGenerator for Data Visualization,
qalsadi.lemmatizer,re,string ,nltk for preprocess
* -TfidfVectorizer for feature extraction-non-negative matrix factorization(NMF),KMeans ,Latent Semantic Analysis (LSA) for model
* -Program: Jupyter Notebook.
# *Communication:*
* Present a 5-minute slide presentation and a one-page report summarizing the project, beginning with an abstract and detailing the project, including the five major components. Also, my project will be included on my GitHub page.
* At the end of this project, we came up with a model that is able to classify stories into two clusters based on the texts and words contained in the stories: suitable stories for children and inappropriate stories for children, with high accuracy.
![clusters](https://user-images.githubusercontent.com/71223849/147696967-5f269882-5753-45c3-b195-3ee86e109d3a.png)
