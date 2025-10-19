# Why Retrieval-Augmented Generation (RAG)?
Usually pre-trained LLM struggle to respond to tasks requiring prioprietary data because they are trained based on a static data set. 
You could fine-tune the model to train based on the new data, but that approach is both time-consuming and computationally intensive. 
Retrieval-Augmented Generation (RAG) enables LLMs to retrieve the relevant infromation within a vector store. 
We can obtain the relevant information for the task, without the expense and delay of constant model retraining

# Setting up the Environment
Make sure you download the [annaconda](https://www.anaconda.com/download) software 
## Settin up the Conda Environment
* conda create --name langchain_env python=3.10.10 
* conda activate langchain_env
* pip install openai python-dotenv ipykernel jupyterlab notebook
* python -m ipykernel install --user --name langchain_env
## Download after Enviroment setup 
* pip install langchain==0.2.8  <-- this will produce error.
* pip install langchain-openai
Make sure notebook, pdf, and env are with the same repository
## Additional installation based on the python notbooks
* pip install docx2txt
* pip install langchain-community
* pip install pypdf
* pip install chromadb

## (optional)
* pip install youtube-transcript-api
This installation is unnecessary for the 
