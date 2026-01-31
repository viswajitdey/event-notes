# Future of Enterprise AI
**📍OpsTree Global (Noida) | 31st January 2026**

## Semantic Search for Enterprise Data: Revolutionizing Knowledge Discovery by [Rishabh Bohra](https://www.linkedin.com/in/rishabh96b/)

- The Google Evolution is a great example of how fast the world is moving.
- Vector Representations can help in redefining Enterprise AI Data.
- Embedding Model can be used for data in vector format which cannot be handled by SQL.
- Embeddings capture relationships > Indexing concepts, not just words > Works for Code, Images or Videos
- ANN (Approximate Nearest Neighbor): A piece of information surrounded by another piece of information.
- Vector DBs can be futher classified into two types - Specialized and Integrated.
- Sparse Vectors - Keyword Match; Dense Vectors - Semantic Match
- Organizations are now using Hybrid Search which is a combination of both Sparse and Dense Vectors.
- Enterprises have a lot of cluttered and unstructured data which makes it more tough to vectorize and embed for search. It leads to "The Silo Problem".
- Since Embedding are sensitive to noise, there is a "Garbage In" challenge which makes preprocessing of data one of the most important aspects.
- Security and Access Control Lists (ACLs) makes it more difficult as users have different set of permissions. This can be solved using Post-filtering and Pre-filtering.
- RAG (Retrieval Augmented Generation): `User Questions > Saerch Knowledge Base > Retrieve Context > Send to LLM > Answer`
- A standard pattern of Enterprise AI Search: `Ingest > Chunk > Embed > Store> Retreive`
- Chunking Strategy determins what context gets retrieved.
- Metadata can be really helpful for filtering if used with vector data.
- Re-Ranking can be done for boosting the accuracy in the results. There are re-ranking algorithms which can be implemented in the ETL pipelines.
- Evaulating the Pipelines is important for grounding of LLMs. RAGAS is one of the tools used for evaluation and measuring KPIs.
- Latency Engineering can be done in many ways, the most common is Caching.
- For Cost Management, try to use mid-sized embeddings.
- PII data shouldn't be sent to any of the LLMs; If it is really important, use local embedding models like Ollama, HuggingFace for sensitive data.
- To mitigate Hallucination, try to say "I don't know" if the the distance score is too low.
- Citations should be there like footnotes having link to documentation/website.
- GraphRAG is coming into the picture soon; we can see it as the next frontier. It combines structured relationships with unestructured semantic meanings.
- LLMs + Tools which help in a certain task --> Agentic Search

## AI Progress: Past, Present & Future by [Nazia Naved](https://www.linkedin.com/in/nazia-naved/)

- With time, a lot of things has changed and we have created a lot of dependency on AI. Imaging life without AI Tools is becoming tough as the time passes.
- In 1956, Dartmouth College emerged as the home to founding fathers of AI with Dartmouth Conference. But, the limitations and lack of expertise in the systems led to "1st AI Winter".
- In 1980s, the same set of people started working on expert systems which means it'll have more rules and more intelligence. Then happened the crash, the "2nd AI Winter".
- 1990s emerged as an era of Nueral Networks. They started believing that "Intelligence isn't logical rules. It's pattern recogination built from experience.".
- In the future, we might reach a threshold where AI doesn't just help us think, it thinks better than us. If it happens, the recursive loop of machines making more intelligent machines will led to intelligent explosion. We as humans must be intelligent enough to survive that.

## Reading Material (From Internet)

- [Semantic Chunking](https://www.multimodal.dev/post/semantic-chunking-for-rag)
- [BM25 Keyword Search](http://docs.opensearch.org/latest/search-plugins/keyword-search/)
- [Rerankers](https://www.mongodb.com/resources/basics/artificial-intelligence/reranking-models)
- [A2A vs MCP](https://www.koyeb.com/blog/a2a-and-mcp-start-of-the-ai-agent-protocol-wars)
