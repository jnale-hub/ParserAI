# ParserAI

A common task in natural language processing is parsing, the process of determining the structure of a sentence. This is useful for a number of reasons: knowing the structure of a sentence can help a computer to better understand the meaning of the sentence, and it can also help the computer extract information out of a sentence. In particular, it’s often useful to extract noun phrases out of a sentence to get an understanding for what the sentence is about.

This AI program utilizes Natural Language Toolkit (NLTK)

```
$ python parser.py sentences/2.txt

            S              
   _________|___            
  |             VP         
  |      _______|___        
  NP    |           NP     
  |     |        ___|___    
  N     V      Det      N  
  |     |       |       |   
holmes lit      a      pipe

Noun Phrase Chunks
holmes
a pipe
```

[View the full assignment description on CS50's OpenCourseWare](https://cs50.harvard.edu/ai/2024/projects/6/parser/)

## Usage:

## How to Use

1. **Install Dependencies** 

   `bash
   pip3 install -r requirements.txt
   `

2. **Run the Program:** Choose a text file from the sentences folder, or create your custom sentences by adding the words in `TERMINAL`.

   `bash
   python parser.py sentences/2.txt
   `
