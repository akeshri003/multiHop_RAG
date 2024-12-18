## Multihop RAG
This repository contains an attempt at implementation of Multihop RAG. The implementation is done by creating an agentic workflow using *LangGraph*.

Among the multiple ways of implementing Multihop RAG, I have primarily used the method of Query Decomposition, to generate answers for questions with multiple hops. 

Below is a graphical diagram showing the workflow: 

![Workflow Diagram](workflow.png)

The final task submission notebook is named - **`Multi-Hop_RAG.ipynb`**

As a part of the task, I have added sample repository files to the repository. To insert your your pdf file, add the path of input .pdf file to `file_path` variable in the notebook. 
To ask, questions, add your question in the following form in the last cell of the notebook - 
```
inputs = {"questions": ["What is the name of the state having Alluvial Soil and also have oil fields?"]}
```
 
