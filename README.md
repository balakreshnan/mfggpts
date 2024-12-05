# Manufacturing GPT's

Idea is to create a GPT model that can generate manufacturing related text. This can be used for generating manufacturing related text for various applications like chatbots, documentation, etc.

GPT is for Industry specific information and compliance and also OSHA, ISA 95, Cyber security information.

[Factory GPT](https://16292869-7313-5215-b42e-4b03d87c7d94.azurewebsites.net/)

![info](https://github.com/balakreshnan/mfggpts/blob/main/images/mfggpt1.jpg 'RagChat')

Intent of this project is to provide Standards and compliance for Manufacturing industry in your finger tips.

![info](https://github.com/balakreshnan/mfggpts/blob/main/images/mfgopsoutput4.jpg 'RagChat')

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
- Provide me details for cybersecurity framework for manufacturing plant floors?
- what are the best practices for supply chain security measures?
- what are the personal security measures?
- What are the best practices for  physical security?

## Future Enhancements

- Expand to different countries specific standards and compliance
- Enable Student and Faculty to use this for their research and projects
- Enable industry to colloborate and share their best practices
- Fine tune model to be more specific to manufacturing industry
- Provide options to expand into manufacturing companies to add their own data and make it their own GPT model
- Expand this to multi model to include images, videos, etc.
- Be the industry Hub for all manufacturing related information
