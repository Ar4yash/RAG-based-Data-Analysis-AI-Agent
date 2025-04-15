
# AI-Powered Document Analysis System with RAG 🔍🤖

*A dual-workflow n8n automation that ingests documents and answers questions using Retrieval-Augmented Generation (RAG).*

## 🚀 Quick Start
1. **Import Workflows**:
   - [`Insert_Doc.json`](RAG_based_Data_Analysis_AI_Agent__Insert_Doc_.json) (Ingestion)
   - [`Retrieve_Doc.json`](RAG_based_Data_Analysis_AI_agent__Retrieve_Doc_.json) (Q&A)
2. **Configure**:
   ```bash
   # Insert Workflow:
   - OneDrive credentials
   - Pinecone index (my-ai-agents)
   - Gemini embeddings

   # Retrieve Workflow:
   - OpenRouter API key
   - Same Pinecone namespace (tesla-data)
