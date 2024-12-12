# IISC_GenAI
GenerativeAI project presentations

Data Preparation and Integration Challenges
Missing Critical Fields:
Initial Kaggle datasets lacked key fields (e.g., pricing, ratings, links)
Transition to live APIs for data enrichment
API Limitations:
API key constraints, rate limits, and restricted data retrieval
Chunking and Filtering:
Focused on cell phone data with 200+ records, rating > 3
Ensured mandatory fields: price, images, description
Embedding Challenges:
Complexity in chunking CSV files, storing embeddings
Difficulty connecting embeddings to LLMs for retrieval, especially with structured data
Multi-Agent Orchestration Challenges
Agent Coordination:
Difficulty integrating multiple agents for cohesive responses
Inconsistent results with frameworks (LangGraph, CrewAI, LlamaIndex Router)
Agent Type Issues:
Adjustments in agent types (Zero Shot → Conversational.React)
Temperature setting (0.3) improved performance but not optimal
Orchestration Bottlenecks:
Lack of effective collaboration among agents
Challenges in multi-step queries and summarization
![image](https://github.com/user-attachments/assets/baf65283-b2a3-42b9-a6a0-5a18b7efb97e)

