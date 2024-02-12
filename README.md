##**Book Recommendation System**

####**Overview**
This content-based recommending system is aimed at providing personalized book recommendations to users based on a book they enter. Leveraging the power of Latent Dirichlet Allocation (LDA) topic modeling, this system extracts meaningful topics from a large collection of books and matches them with the topic representation of the input book to recommend the most similar books.

####**Latent Dirichlet Allocation(LDA)**
LDA is a probabilistic model used in natural language processing and machine learning. It is commonly used for topic modeling, where it discovers abstract topics within a collection of documents. Each document is represented as a distribution over topics, and each topic is represented as a distribution over words. LDA is widely used in text analysis tasks such as document classification, information retrieval, and recommendation systems.

####**Dataset**
The dataset is available in the 'data' directory. It is sourced from [Amazon Books Reviews dataset](https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews) . It contains books' metadata such as authors, categories, description, cover image and so on.

####**Models**
Trained LDA models for 30 topics and 50 topics are stored in the models directory. These models are used for generating topic representations of books and for making recommendations as in notebooks/recommendation.ipynb

####**LDA Visualization**
Please note that the LDA visualization in the model training notebook may not render properly on GitHub. You can view the dynamic visualization [here]([link-to-nbviewer](https://nbviewer.org/github/Sajidha777/Book-Recommendation-System/blob/main/notebooks/model_building.ipynb#topic=0&lambda=1&term=)https://nbviewer.org/github/Sajidha777/Book-Recommendation-System/blob/main/notebooks/model_building.ipynb#topic=0&lambda=1&term=). This visualization provides insights into the topics discovered by the LDA models and can help to understand the underlying structure of the book corpus.

####**Notebooks**
- **Cleaning and Preprocessing:** Before training the LDA models, the dataset undergoes extensive preprocessing including stopwords removal, lemmatization and more.
- **Model Training:** To train the LDA models on the preprocessed data.
- **Search:** To search up specific books within the dataset.
- **Recommendations:** Generate personalized book recommendations based on user input using this notebook.

