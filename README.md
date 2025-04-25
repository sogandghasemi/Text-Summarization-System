#This Python script uses the NLTK library to summarize content from Wikipedia or custom text files.

##Features:
Prompts user for two Wikipedia topics
Fetches and saves full articles as input_text1.txt and input_text2.txt
Summarizes each article using two methods:
Basic Summarization – adds sentences until the target length is reached
Cosine Similarity-based Summarization – selects sentences based on relevance and coherence using cosine similarity
Saves summaries as:
summarized_text1.txt, summarized_text2.txt (basic version)
Second_summarized_text1.txt, Second_summarized_text2.txt (cosine similarity version)
Generates a query based on the summaries
Option to use your own .txt files instead of Wikipedia articles
