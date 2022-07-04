# NLP_Tom_Sawyer_Word
What are the most frequent words in Tom Sawyer, by Mark Twain novel, and how often do they occur?

In this notebook, we'll scrape the novel Tom Sawyer from the website Project Gutenberg (which contains a large corpus of books) using the Python package requests. 
Then we'll extract words from this web data using BeautifulSoup. 
Finally, we'll dive into analyzing the distribution of words using the Natural Language ToolKit (nltk) and Counter.

The Data Science pipeline we'll build in this notebook can be used to visualize the word frequency distributions of any novel that you can find on Project Gutenberg. 
The natural language processing tools used here apply to much of the data that data scientists encounter as a vast proportion of the world's data is unstructured data and includes a great deal of text.

Let's start by loading in the three main Python packages we are going to use.
