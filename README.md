# AmazonML24

This repo consists of the working solution of the Amazon ML hackathon 2024

We were required to extract text info from the image. 
OCR , Pyteserract were used to extract text and BLIP models from salesforce were used to perform image captioning and 
provide a desciption for the image.

The extracted image text and the description is processed using LLama to generate a meaningful text which is tokenized and fed to a 
BERT model with linear layers after using the CLS tokens. 
Max , mean or last pooling can be done and while using other LLMs

In this way the required image labels were prediced.
