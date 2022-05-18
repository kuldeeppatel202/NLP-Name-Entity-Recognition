# NLP-Name-Entity-Recognition
## Import wikipedia and wikipediaapi library with the help of this we can scap data from web then we have created dictionary to store heading and description of the search results so that we can perform Name Entity Recognition. 
## After extracting data we perform some text processing to clean our text data and then perform tokenization to break that paragraph into sentenses.
## Then we use libary like ne_chunk and postag to divide it into entities and assign them tag of which category this entity belongs to then we combine them into set of (entitity , label) and created list of whole dataframe 
## Finally we converted our result list to dataframe and count the occurence of labels in that category. 
