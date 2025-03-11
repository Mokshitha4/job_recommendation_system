# job_recommendation_system

Content based recommendation system is used to recommend jobs in this dataset.
A Content-Based Recommender works by the data that we take from the user, either explicitly or implicitly . By the data we create a user profile, which is then used to suggest to the user, as the user provides more input or take more actions on the recommendation, the engine becomes more accurate.
Data is tokenized and sum of the cosine distance over all tokens is calculated and used to find the cosine similarity.
Using sentence_transformers gave better results .
