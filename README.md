# Financial_Assistant
This project is a simple tool that lets you ask questions about a company’s financial report in natural language. You can ask about things like the company name, the report name, the financial year, the quarter, revenue breakdown, risks, and forward-looking statements.
The system works by combining semantic search and a language model:

Sentence embeddings are used to understand the meaning of each sentence in the report.

FAISS is used to quickly find the most relevant sentences for a query.

Flan-T5 generates answers in natural language based on the retrieved sentences.

The tool is smart enough to handle factual questions (like “Which financial year is this report?”) and conceptual questions (like “What risks are mentioned?”).
