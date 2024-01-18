# GPT-DB
DB

Strategies
------
    Typical RAG:
    Traditional method where the exact data indexed is the data retrieved.
    Parent retriever:
    Instead of indexing entire documents, data is divided into smaller chunks, referred to as Parent and Child documents.
    Child documents are indexed for better representation of specific concepts, while parent documents is retrieved to ensure context retention.
    Hypothetical Questions:
    Documents are processed to determine potential questions they might answer.
    These questions are then indexed for better representation of specific concepts, while parent documents are retrieved to ensure context retention.
    Summaries:
    Instead of indexing the entire document, a summary of the document is created and indexed.
    Similarly, the parent document is retrieved in a RAG application.
------

### [templates/neo4j-advanced-rag](https://github.com/langchain-ai/langchain/tree/master/templates/neo4j-advanced-rag?ref=blog.langchain.dev&source=post_page-----d95119a8c42e--------------------------------)
