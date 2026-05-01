# Restaurant Data Analytics and Finacnce Assistant

# AI-Powered Restaurant Data Analysis & Financial Query Workflow (Dify)

## Overview
This project showcases an AI-driven Assistant workflow built using Dify that intelligently processes user queries across multiple categories including dataset analysis financial queries and knowledge-based questions for a restaurant.
The workflow dynamically routes user inputs through different pipelines using LLMs document processing and retrieval-augmented generation to deliver accurate and business-friendly insights.
---

## Workflow Architecture
The system uses a Question Classifier to route queries into three main pipelines:
### 1. Data Analysis Pipeline
**Triggered when a user uploads a dataset**

**Flow:**  
Start → Question Classifier → Doc Extractor → Code → LLM → Answer

**Steps:**
- Extracts uploaded files  
- Processes and analyzes data using code logic  
- Generates structured insights  
- Converts results into easy-to-understand explanations using LLM  

---

### 2️. Knowledge Retrieval (RAG) Pipeline
**Triggered for financial or conceptual queries**

**Flow:**  
Start → Question Classifier → Knowledge Retrieval → LLM → Answer

**Steps:**
- Retrieves relevant information from knowledge base  
- Enhances responses using contextual grounding  
- Generates accurate and domain-specific answers  

---

### 3️. Fallback / Default Response
**Triggered for unrelated queries**

**Flow:**  
Start → Question Classifier → Default Answer

**Behavior:**
- Returns a controlled response  
- Prevents irrelevant or hallucinated outputs  

---

## Key Components

### Question Classifier
- Categorizes user queries into:
  - Dataset-related  
  - Financial or knowledge-based  
  - Other or unrelated  

---

### Doc Extractor
- Accepts uploaded datasets  
- Extracts structured data for further processing  

---

### Code Node
- Performs data transformations and calculations  
- Generates key metrics such as:
  - Revenue  
  - Cost  
  - Profit  
  - Trends  

---

### LLM (gpt-5-chat-latest)
- Converts structured outputs into natural language insights  
- Ensures responses are clear and business-friendly  

---

### Knowledge Retrieval
- Uses preloaded domain knowledge  
- Supports retrieval-augmented generation for better accuracy  

---

## Features

- Intelligent query routing  
- Multi-input handling including text and files  
- Data-driven insight generation  
- Retrieval-augmented responses  
- Controlled fallback mechanism  
- Modular and scalable workflow design  

---

## Tech Stack

- **Dify.ai** – Workflow orchestration  
- **LLM** – GPT-based model (gpt-5-chat-latest)  
- **Python (Code Node)** – Data processing  
- **RAG** – Knowledge retrieval integration  

---

## Use Cases

- Business data analysis from CSV or Excel files -- in this case for a Restaurant
- Financial insights and explanations  
- KPI and trend analysis  
- AI-powered decision support  

---

## Future Enhancements

- Adding advanced visualizations and chart outputs  
- Integrating dashboard-based UI  
- Expanding domain-specific knowledge base  
- Connecting external APIs for real-time data  

---

## Workflow Snapshot

<img width="1446" height="594" alt="image" src="https://github.com/user-attachments/assets/35ac4aed-b82e-4527-8475-5a599fd87153" />


---

## Contribution

Feel free to fork this repository and improve the workflow by adding new pipelines enhancing prompts or integrating advanced analytics features.

---

## Contact

**Shekhar Sahay**  
LinkedIn: https://www.linkedin.com/in/shekhar-sahay-25673742
