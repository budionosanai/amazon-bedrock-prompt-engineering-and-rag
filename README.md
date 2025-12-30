## 📁 Repository Structure

| File / Notebook | Description |
| :--- | :--- |
| `promptEngineeringNova.ipynb` | Notebook of prompt engineering using **Amazon Nova** on **Amazon Bedrock**. |
| `knowledgebaseAgent.ipynb` | Notebook of RAG (retrieval augmented generation) using **Knowledge Base** and **Agent** on **Amazon Bedrock**, **AWS Secret Manager**, **Amazon Titan Embedding**, **Amazon S3** and **Pinecone**. |
| `pineconeandlangchain.ipynb` | Notebook of RAG (retrieval augmented generation) using **Amazon Nova**, **LangChain** and **Pinecone** for financial customer service use case. |
| `fcsdataset.csv` | Financial customer service dataset used in the `knowledgebaseAgent.ipynb` and `pineconeandlangchain.ipynb`. |
| `Always Winner CV.pdf` | Sample PDF file used in the `promptEngineeringNova.ipynb`. |
| `bedrock.png` and `receipts.jpg` | Sample image/photo file used in the `promptEngineeringNova.ipynb`. |

## ✅ Prerequisites

1.  **Amazon Web Services (AWS)**: Access to **Amazon Bedrock**, **AWS Secret Manager** and **Amazon S3**, you can sign up/sign in [here.](https://console.aws.amazon.com)

2.  **Pinecone**: Access to create vector database, you can sign up/sign in [here.](https://pinecone.io)

3.  **Langchain**: Access to create RAG (retrieval augmented generation) application.

## 🚀 Getting Started

1. Clone this repository
```bash
git clone https://github.com/budionosanai/amazon-bedrock-prompt-engineering-and-rag.git
cd amazon-bedrock-prompt-engineering-and-rag
```

2. Create Pinecone API key and Pinecone serverless index then store Pinecone API key in AWS Secret Manager, you can see this [link.](https://dev.to/budionosan/amazon-bedrock-knowledge-base-and-agent-hik)

3. Open, run and following this notebooks :

| Notebook | Using |
| :--- | :--- |
| **[promptEngineeringNova.ipynb](./promptEngineeringNova.ipynb)** | **Google Colab**. |
| **[knowledgebaseAgent.ipynb](./knowledgebaseAgent.ipynb)** | **Google Colab**. |
| **[pineconeandlangchain.ipynb](./pineconeandlangchain.ipynb)** | **Google Colab**. |

4. If notebook have Python environment that store such as `load_dotenv("....txt")`, create Python environment using python-dotenv, you can see this [link.](https://pypi.org/project/python-dotenv/) then write your AWS key and Pinecone API key in a Notepad file, then save the file with the name `....txt`.

## ⚠️ Warning

**Ensure securely API keys such as AWS key and Pinecone API key — DO NOT HARDCORE them in notebooks.**

## 📚 Resources

* [Prompt Engineering, Amazon Bedrock (Knowledge Base and Agent) and Amazon Nova documentation](https://docs.aws.amazon.com/bedrock/)
* [Integration between Pinecone and Amazon Bedrock documentation](https://docs.pinecone.io/integrations/amazon-bedrock/)
* [Pinecone in Langchain documentation](https://python.langchain.com/docs/integrations/vectorstores/pinecone/)
* [AWS in Langchain documentation](https://python.langchain.com/docs/integrations/providers/aws/)

## 🙏 Acknowledgments

**Amazon Web Services, Pinecone, Langchain and Google Colab**