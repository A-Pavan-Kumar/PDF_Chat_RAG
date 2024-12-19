# PDF_Chat_RAG
## TASK__1

This directory contains the 2 Solutions for completing Task 1, files:

* **RAG.ipynb** (Colab notebook): This notebook outlines the workflow for Task 1. It likely includes steps like data preparation, model selection, and training.
* **Vector Store RAG.json** (Langflow module): This JSON file defines the configuration for a Langflow flow designed to complete Task 1. It likely specifies the components used in the flow, their connections, and the parameters for each component. 

The Langflow flow likely utilizes various components for:

  * **Prompts & Chat Input:** These components might handle user prompts and conversation history for context.
  * **Huggingface Model for Embeddings:** This component could be used to generate vector representations of text data from the Hugging Face library.
  * **AstraDB as Vector Datastore:** AstraDB might be used to store and retrieve the generated embeddings efficiently.
  * **Text Parsing:** A component might be responsible for parsing the data into text format.
  * **Context & Question Passing:** This step likely involves passing the combined context and question to the Google AI LLM model.
  * **Google AI LLM as LLM Model:** This Langflow uses Google gemini-1.5-pro LLM model for generating the final response.
  * **IJSREM-Early detection of Alzheimer’s Disease using Deep Learning** , article used for Embedding the information and Prompted to get the information from document as Needed.
