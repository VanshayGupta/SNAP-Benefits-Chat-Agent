# SNAP-Benefits-Chat-Agent

This project utilizes Reddit data from the r/foodstamps subreddit to help users navigate questions related to SNAP benefits. Using the OpenAI API, it generates semantic embeddings for both posts and comments. To identify relevant information, the system supports semantic search through either FAISS indexing or direct cosine similarity comparisons. A GPT-4 powered assistant then synthesizes a clear, context-aware response based on the most relevant retrieved content.
