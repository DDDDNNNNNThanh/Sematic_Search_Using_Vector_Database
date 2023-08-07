# Sematic_Search_Using Vector_Databases

## About
This endeavor involves the creation of a sophisticated search capability utilizing the power of natural language processing and semantic similarity methodologies. It empowers users to input queries in a manner akin to human conversation, enabling the retrieval of pertinent search outcomes grounded in the semantic essence of the query. The central objective of this initiative is to enhance the search encounter by transcending conventional keyword-dependent searches, thereby furnishing outcomes that are not only more precise but also attuned to the contextual nuances. This uses Open AI so you have to  [create an OpenAI Key](https://gptforwork.com/help/gpt-for-docs/setup/create-openai-key) I highly recommend a paid OpenAI account. 

## Installation

To run the Semantic Search project locally, follow these steps:

1. Clone the repository:

```
gh repo clone deepanshululla/SemanticSearch
cd SemanticSearch
```
2. Install the required dependencies:
```
conda env create -f environment.yml
```
3. Run Docker-compose up for elasticsearch
```
docker-compose up -d
```
4. Create a file called openai in the secrets folder:
```
❯ ls secret
openai
```
5. Paste your OpenAI key into the openai file.

6. You may also need to setup kaggle key and download the dataset from Kaggle.

## Technologies Used
- Python
- Gradio (for the web interface)
- Hugging Face Transformers (for NLP models)
- Langchain
- Chromio
- ElasticSearch
