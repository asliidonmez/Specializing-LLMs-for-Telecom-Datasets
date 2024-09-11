# Specializing-LLMs-for-Telecom-Datasets
This project was based on a zindi.com competition https://zindi.africa/competitions/specializing-large-language-models-for-telecom-networks

In the project, first a Retrieval Augmented Generation Module is created. This is done by using 3GPP Release 18 documents.
Using this external source, the final combined source is splitted into chunks of size 1000.
This results in 46K chunks. These are then embedded and stored in Chromadb.

After, Phi-2 model and its tokenizer is initialized
Dataset which consists of multiple choice questions and is a part of TeleQnA dataset is loaded from txt files.

Then, RAG and LLM modules are integrated by defining a series of functions.
Answer generation is automated and accuracy is calculated in the end.
