# Manufacturing GPT's

Idea is to create a GPT model that can generate manufacturing related text. This can be used for generating manufacturing related text for various applications like chatbots, documentation, etc.

GPT is for Industry specific information and compliance and also OSHA and ISA 85 type of information.


## Architecture

![info](https://github.com/balakreshnan/mfggpts/blob/main/images/mfggpts1.jpg 'RagChat')

## pre-requisites

- Azure subscription
- Azure Open AI Studio
- Azure Blob Storage
- Azure AI Search
- Azure Web App
- Azure functions
- Azure cosmos DB
- Azure machine learning

## Data

- Data is collected from various sources like OSHA, ISA 85, etc.
- stored in docstouse folder
- Only for educational purpose for now

## Steps

- Upload data to Azure Open AI Studio
- Create vector index using talk to your data
- Publish UI from - https://github.com/balakreshnan/sample-app-aoai-chatGPT
- Need the vector name created

## Outputs

- Question: What are the measures to safe guard accidents in manufacturing floor?

![info](https://github.com/balakreshnan/mfggpts/blob/main/images/mfgopsoutput1.jpg 'RagChat')
![info](https://github.com/balakreshnan/mfggpts/blob/main/images/mfgopsoutput2.jpg 'RagChat')

- Question 2: What is DELS topology and can you explain where to use it?

![info](https://github.com/balakreshnan/mfggpts/blob/main/images/mfgopsoutput3.jpg 'RagChat')

- Question: What are the options for PPE in a plant floor?
- how to implement PPE in plant floor?
- what are the process if there is PPE incident?
- what are the ISO paper work needed for PPE incidents?
- What are the cyber security practicse to apply in factory floor for lines?
- What are the best practices for OEE?