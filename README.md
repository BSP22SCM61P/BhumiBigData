# BhumiBigData

Movie Search with Elasticsearch
This project demonstrates how to build a movie search engine using Elasticsearch. The project uses Python and Elasticsearch to create an index of movie data, and then allows users to search the index for movies using a search bar.

Prerequisites
Python 3.7 or higher
Elasticsearch 7.0 or higher

Setup
Clone the repository and navigate to the project directory.
Install the required Python packages by running pip install -r requirements.txt.
Download the MovieLens dataset and place the movies.csv file in the project directory.
Run the movie_search.py script to create the Elasticsearch index and start the search interface.

Usage
The search interface provides a text input box where users can enter search queries. As they type, the interface displays up to 10 movie titles that match the search query, highlighting the matching words in bold.

The search interface provides two functions for searching the Elasticsearch index:

search() - searches for movies that contain the given search query using the match_phrase_prefix operator.
search_prefix_index() - searches for movies that contain the given keyword or phrase using a combination of the prefix and match operators.
Acknowledgments
This project is based on the tutorial Building a movie search engine with Elasticsearch.





