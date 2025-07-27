# IBM RAG and Agentic AI Professional Certificate - Course Materials

This GitHub repository contains the lab exercises, experiments, and assignments for the [IBM RAG and Agentic AI Professional Certificate](https://www.coursera.org/professional-certificates/ibm-rag-and-agentic-ai) course.

### Setting up your development environment

Install chromadb, embeddings and AI models

```  bash
pip install numpy==2.3.1
pip install scipy==1.16.0
pip install chromadb==1.0.12
pip install sentence-transformers==4.1.0
pip install ibm-watsonx-ai==1.3.24
```

Download the food dataset

``` bash
wget https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/sN1PIR8qp1SJ6K7syv72qQ/FoodDataSet.json
```

Run and compare the tools:

``` bash
# Interactive Search
python3.11 interactive_search.py

# Advanced Search
python3.11 advanced_search.py

# Enhanced RAG chatbot
python3.11 enhanced_rag_chatbot.py

# System Comparison
python3.11 system_comparison.py

# Calorie Checker
python3.11 calorie_checker.py

# Result Limiter
python3.11 result_limiter.py
```
