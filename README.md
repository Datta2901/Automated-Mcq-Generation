## Automated MCQ Generation

* In Automated MCQ Generator, questions are generated automatically with the help of NLP. The text of any domain is provided as input to the system which is then summarized using the BERT algorithm.
  
* BERT (Bidirectional Encoder Representation from Transformers) is a deep learning-based technique for natural language processing, a pre-trained model from Google.
  
* Now the keywords are selected from the summarized text using the python keyword extractor (PKE) and accordingly mapping of a keyword is done with a sentence. 
  
* This keyword will be one of the options of MCQ. Now the main task is generating relevant distractors. Distractors are generated using the word net approach. 
  
* Word net is an API used to get the correct sense of the word. So the good and relatable distractors are generated.
   
*  This system solves the problem of manual creation of questions and reduces time consumption.
  
## Flow Chat

![Image](https://github.com/Datta2901/Automated-Mcq-Generation/blob/master/workflow.png?raw=true)