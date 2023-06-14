**This is market strategist chatbot use market insight articles published on internet from may-2023, and use langchain and OpenAI embedding to extend OpenAI Chat LLM to answer investor's questions related to debt ceiling, recession, and investment allocation for 2023**

**Instruction to run**
1. use createjson4langchain.jpnyb to create the json message for langchain
   - you can collect more articles and put them in the postings directory
2. use marketstrategistchatbot.jpynb to build the chatbot using langchain vector store, chain, and OpenAI embedding model to build a query with context and get answers from the openAI or dolly LLM
   - To use OpenAI Chat LLM, you  need to do the following : 
   ```
   export OPENAI_API_KEY='your_open_ai_license_key'
   jupyter-lab
   ```
   - For Dolly, you need to spin up a cluster to run the Dolly model
