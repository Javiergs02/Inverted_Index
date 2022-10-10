# Inverted_Index
Implement an inverted index by passing a collection of documents as parameters.
## Overview
The code performs the following functions:
1- Check if every file and folder we need is ready, and prepare them if they are not
2- Preprocesses the data in the text collection (stop words removal, stemming, removing punctuations etc.)
3- 
## Running the code  
*Python 3 and nlkt is required to run the code*

Ensure all the files from the repo are present in the same directory.

Open the project in any preferred IDE of your choice and run the Inverted_Index.py file passing as argument several documents, we have used the files stored in the Documents folder.

## Detailed List of Functionalities Implemented
### In the file Inverted_Index.py
#### 1. inverted_index_of

### In the file Document_normalizer.py
#### 1. Translator
This function gets rid of all the punctuations and special characters,
    it also converts the document to lowercase.
#### 2. StopWords_deleter
This function removes stopwords from the text file
### In the file Checker.py
#### 1. documents_checker
This functions checks if there are documents to invert index, and returns their names.
#### 2. IE_File_checker
This functions checks if there is an IE.json file so store our final inverted index
#### 3. Indices_Folder_checker
This function checks if there is a folder to store the indices of all the documents

## Built With

## Authors
* **Javier García**
* **Jesús Matos**
* **Liam Mahmud**
* **Krish Sadhwani**
