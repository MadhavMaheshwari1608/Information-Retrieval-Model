# Information-Retrieval-Model

Demonstrated creative problem-solving skills by exploring prompt engineering strategies, experimenting with open-source language models, and achieving competitive results in a natural language processing assignment with a focus on data structures and algorithms.

Download model_parent_directory, Corpora1, Corpora2, Corpora3 folders.
Unzip and extract them,
Put all files from Corpora1, Corpora2, Corpora3 into model_parent_directory folder.

## Libraries to be Included for ChatGPT:
sudo apt install python3-pip             
pip install openai                 
pip show openai        (to confirm the installation)

## Libraries to be Included for HugChat:
pip3 install hugchat

## Compilation and Running Details 

Open Terminal or PowerShell at model_parent_directory folder

To compile your program, use the following commands: 
$ (LINUX)   g++ tester.cpp node.cpp dict.cpp search.cpp qna_tool.cpp -o m.out
$ (WINDOWS) g++ tester.cpp node.cpp dict.cpp search.cpp qna_tool.cpp -o m.exe

To execute:
$ (LINUX)   ./m.out 
$ (WINDOWS) m.exe

You must provide an input which would be a query to be processed by the code. The answer to the query would be returned on the terminal and will also be printed in the query.txt file. The code will keep asking for queries until you input “quit”.

### Example:
Query:
Who was Mahatma Gandhi?

.....answer would be printed....

continue for further queries.

Query:
quit (typing quit ends the program)
The program terminates after this step.
