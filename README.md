## Amazon Bedrock Prompt Engineering

**[promptEngineeringNova.ipynb](./promptEngineeringNova.ipynb)** : prompt engineering using **Amazon Nova Lite**.

## Amazon Bedrock Knowledge Base and Agent

**[knowledgebaseAgent.ipynb](./knowledgebaseAgent.ipynb)** : RAG (Retrieval Augmented Generation) using **Amazon Bedrock** features such as **Bedrock Knowledge Base** and **Bedrock Agent**, **AWS Secret Manager** to store Pinecone host key, **Amazon Titan Embedding** to embedding, **Amazon S3** to store knowledge base and **Pinecone** to vector storage.

**NOTE :** Before try this repository, get Pinecone host key to can connect to Amazon Bedrock, then store Pinecone host key to AWS Secret Manager.

## Amazon Bedrock x Pinecone x Langchain

**[pineconeandlangchain.ipynb(./pineconeandlangchain.ipynb)** : RAG (retrieval augmented generation) using **Amazon Nova Lite** with financial customer service use case based [this dataset](./fcsdataset.csv)

**Reference :** 

1. https://docs.pinecone.io/integrations/amazon-bedrock

2. https://python.langchain.com/docs/integrations/vectorstores/pinecone

3. https://python.langchain.com/docs/integrations/providers/aws