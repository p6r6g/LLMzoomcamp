#LLM zoomcamp
Using Large Language Models (LLM) to build and deploy real-world applications like a chatbot using LangChain, RAG, and vector databases.

![rag llm](https://github.com/user-attachments/assets/2f4205cc-4472-4644-a422-f2a9aeeb2525)


Objective: To build LLM-powered applications, from raw prompts to full-stack LLM deployments:

RAG systems (i.e. chatbot over long custom documents)
Document search and Q&A tools
AI assistants with memory
Custom APIs powered by LLMs
Interactive LLM app
 


docker run -p 6333:6333 -p 6334:6334 \
   -v "$(pwd)/qdrant_storage:/qdrant/storage:z" \
   qdrant/qdrant 



Check for stuck containers:
docker ps -a


Remove all stopped containers:
docker container prune -f