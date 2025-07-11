# Level 4 Agent - KnowledgeBase Agent

This project contains a Bedrock agent named **KnowledgeBase Agent**. The agent is designed to implement Retrieval Augmented Generation (RAG) by creating and utilizing a vector store for answering questions based on proprietary information.

## Overview

- **Agent Name**: KnowledgeBase Agent
- **Description**: An agent that uses a vector store to retrieve and answer questions based on ingested proprietary information.
- **Knowledge Base Name**: agenticai
- **Embedding Model**: Amazon Titan Embed Text v2
- **Foundation Model**: Amazon Nova Pro v1

## Key Features

- Ingests proprietary information into a vector store.
- Answers questions based on the ingested information.
- Utilizes OpenSearch Serverless for storage and retrieval.
- Embedding model configuration with 1024 dimensions and FLOAT32 data type.

## How to Use

1. Test the agent using the Bedrock console or API.
2. Ingest proprietary information (e.g., documents, text) into the vector store.
3. Interact with the agent by asking questions related to the ingested information.
4. The agent will retrieve relevant information from the vector store and provide accurate answers.

## Outputs

Below are some example outputs generated by the agent:

### Example Output
![Example Output](outputs/Screenshot%202025-06-03%20015816.png)



