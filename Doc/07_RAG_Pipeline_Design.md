
7.1 RAG Workflow

User query

Embed query

Retrieve relevant:

Patient history

Clinical guidelines

Context pruning

Send minimal context to LLM

Generate grounded response

7.2 Retrieval Strategy

Top-k semantic search

Filter by condition

Time-weighted retrieval

7.3 Prompt Template
Patient Profile:
{compressed_summary}

Relevant Clinical Knowledge:
{retrieved_docs}

User Query:
{question}

Provide:
- Risk level
- Personalized advice
- Evidence-based reasoning
