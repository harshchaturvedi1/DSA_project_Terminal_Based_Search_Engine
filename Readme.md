# TTerminal-Based Search Engine for Large Documents


## Reasons for choosing this project

-  File Handling in Java: I'm learning java , so this project will help me understanding file handling in Java.
-  DSA : This project will help me in understanding searching and sorting algorithms , which is a big topic for placements.


## Steps followed

### Document Processing :

- The DocumentProcessor reads each document from the specified(fixed) directory.
- It tokenizes the text of each document and builds an inverted index.
- The inverted index is stored in memory for fast search operations.

### Search Functionality :
- It receives search queries from the user via the terminal interface.
- The SearchEngine retrieves relevant document IDs or sections by looking up terms in the inverted index.
- It returns the matching documents to the terminal interface for display.

### HLD

Start --->  DocumentProcessor   -----> SearchEngine <----> search(query) <----> terminal / result
            processDocuments             
            tokenize                    
            buildInvertedIndex                 
            getInvertedIndex  
