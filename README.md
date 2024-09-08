# Quick Notes

An AI tool used by professors and students to organize and create summarized notes for studying, with extra help through a TA chatbot. 

## Summarized Notes
The professor has the ability to take an audio file of their lecture and upload it to the Quick Notes Site. From there, the Google-Speech-API can create a transcript from the audio file. That transcript is integrated into a BERT summarizer, which creates bulleted notes from the transcript that students can use to study for the class.

## ChatBot
The TA chatbot was created with a DialougeFlow API and a python library, sklearn, which analyzed the notes for the most important details that can be asked from the chatbot. Thus, the chatbot can answer class content questions without the student attending office hours.

 
