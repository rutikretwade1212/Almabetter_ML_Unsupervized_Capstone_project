# Almabetter_ML_Unsupervized_Capstone_project
Segmenting Netflix movies and TV shows is an unsupervised machine learning challenge. The initial goal is to prepare the dataset for analysis and clustering.

To begin, I imported the dataset and gathered basic information about it. I then planned the data wrangling and preprocessing steps. One of the initial tasks was converting a date feature, which was originally loaded as an object, into a Pandas datetime object. This conversion makes it easier to work with date-related functions and operations.

Regarding missing values, I chose not to handle them because they were sparse in certain features. These missing values could be useful for exploratory data analysis (EDA) and wouldn't significantly impact the overall analysis.

The next important step was text preprocessing. To prepare the "Description" feature for machine learning, I performed tasks like converting text to lowercase, removing punctuation, stopping words, and eliminating extra white spaces.

Once the text data was preprocessed, I used the TF-IDF vectorization technique to convert the text into numerical format. I set a maximum of 400 features to transform each review observation into a 400-dimensional feature vector.

After obtaining these numerical representations, I moved on to building clustering machine learning models. I experimented with three different models: K-means, Hierarchical Clustering, and DBSCAN algorithms. Each of these methods aimed to group similar movies and TV shows together based on their characteristics
