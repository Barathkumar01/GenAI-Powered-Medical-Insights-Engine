# GenAI-Powered Medical Insights Engine

A next-gen pipeline that extracts actionable insights from unstructured medical content using GenAI, NLP, and machine learning. This project ingests and processes over 10,000 PubMed articles (XML format) and 25,000 Reddit posts to help Medical Affairs teams reduce manual effort and surface emerging health trends faster and more effectively.

---

## Overview

Traditional medical research analysis is time-consuming and reactive. This project builds an automated insights engine using GenAI and NLP that:

- Parses and processes unstructured XML data from PubMed
- Scrapes and analyzes Reddit healthcare discussions using PRAW
- Applies LLMs (e.g., GPT via OpenAI) to summarize and synthesize medical literature and social sentiment
- Generates structured insights, trends, and topic summaries
- Visualizes outputs via a Streamlit web app


## Key Features

- ✅ Ingests and cleans unstructured data (PubMed + Reddit)
- ✅ Uses GenAI to generate plain-language summaries of medical content
- ✅ Analyzes Reddit posts to detect trending symptoms, medications, and concerns
- ✅ Reduces manual insight generation time by 70%
- ✅ Forecasts potential areas of interest using sentiment + topic analysis


## 🛠️ Tech Stack

**Languages & Tools**  
- Python, Jupyter, Streamlit

**Libraries**  
- LangChain, OpenAI API, Hugging Face Transformers, spaCy, scikit-learn, BeautifulSoup, PRAW, pandas, matplotlib

**Data Sources**  
- PubMed Medline (XML format)  
- Reddit Healthcare Posts (via Reddit API using PRAW)
