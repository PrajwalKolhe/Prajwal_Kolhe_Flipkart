#  Laptop Recommendation using LangChain, FAISS, and HuggingFace (Google Colab Compatible)

This project is a simple question-refinement and product search system built using LangChain and vector embeddings. It allows a user to input a vague query like _"I want a budget laptop for remote work"_ and returns a refined query and potentially more relevant matches from a CSV dataset (e.g., Flipkart laptop listings).

---

##  Features

- Load laptop product data from CSV
- Use LangChain to refine vague search queries using LLMs
- Split and embed product descriptions using HuggingFace embeddings
- Store and retrieve similar products using FAISS (vector database)
- Fully runnable in **Google Colab** (no API key required if using public Hugging Face models)

---

##  Tech Stack

- **LangChain**
- **HuggingFace Transformers & Hub**
- **FAISS** (for semantic search)
- **Google Colab** (runtime)
- **CSVLoader** for product data

---
