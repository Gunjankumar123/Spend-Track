# Spend-Track

I developed an Intelligent Procurement Assistant to streamline data-driven decision-making within procurement processes. This assistant automates the retrieval of insights from large procurement datasets, enabling procurement teams to make faster and more informed purchasing decisions.

## The system allows users to ask procurement-related queries, such as:

Total number of orders within specified periods.
Identifying the quarter with the highest spending.
Analyzing frequently ordered line items.
Answering various other procurement-related inquiries.

The project uses a structured dataset containing order details, time periods, items and categories, and spending information, which provides insights into purchasing trends and spending patterns.

## Key technologies used in the project include:

Python 3.12 for data processing and query handling.
Docker and Docker Compose for containerization, ensuring consistent execution across environments.
pgvector, a PostgreSQL extension, for efficient full-text and similarity search.
Flask for creating an API that facilitates interaction between users and the assistant.
Multilingual-e5-small for generating high-quality embeddings, enabling accurate semantic search.
Qwen/Qwen2.5-1.5B model (via Hugging Face) for conversational intelligence in answering user queries.

This system improves efficiency by automating procurement analysis, reducing the need for manual data processing and supporting faster decision-making in procurement management.
