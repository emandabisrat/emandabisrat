
<img width="1400" height="350" alt="image" src="https://github.com/user-attachments/assets/72c715da-8e06-43c5-9f98-cd72d0f6cb33" />


## Hi there I'm Emanda! 👋🏾

I love learning about anything Data Science! I hope to use this profile to showcase my projects and skills, while also collaborating with others. I am looking forward to applying my knowledge and experience in building intelligent solutions to impact people’s lives and industries.


## About me:

- 😄 I’m an Applied Data Science Master's student at University of Chicago through the 4+1 Scholar's Program
- 👩🏾‍💻 I have a Bachelor's degree in Data Science from the University of Chicago with a minor in Statistics
- 📫 How to reach me: [Linkedin](www.linkedin.com/in/emanda-bisrat), emandabisrat@uchicago.edu
- 🛍️ Fun fact: I love thrifting. 2 hours and a latte is all I need :)

## Projects:

I've worked on various projects where I've applied machine learning, NLP, and data analysis to real-world problems, with a focus on interpretability and impact. 

### 🔹 [Multimodal Ecommerce Product Chatbot](https://github.com/emandabisrat/Ecommerce-RAG) 
  Built a multimodal Retrieval-Augmented Generation (RAG) chatbot that answers ecommerce product questions using both text and image 
  inputs with CLIP embeddings, ChromaDB vector search, and Claude-based response generation.
  - Built a chatbot that answers ecommerce product questions using both text and image inputs with CLIP embeddings, ChromaDB, and LLaVA.
  - Processed and cleaned Amazon product data, including downloading and organizing product images
  - Used CLIP to generate embeddings for product descriptions and images for similarity-based search
  - Built a ChromaDB vector database to support text, image, and hybrid product retrieval
  - Integrated LLaVA to generate product answers and recommendations using retrieved product information
  - Evaluated retrieval performance using Recall@1, Recall@5, and Recall@10 metrics

Tech: Python, CLIP, ChromaDB, LLaVA, PyTorch, Vector Search, NLP

Tech: Python, CLIP, ChromaDB, Claude API, PyTorch, Multimodal RAG, Vector Search, Prompt Engineering, NLP

### 🔹 [RAG Assistant for Technical Papers: Retrieval-Augmented QA System](https://github.com/emandabisrat/RAG_Implementation) 

  Built an end-to-end Retrieval-Augmented Generation (RAG) pipeline to answer questions over dense AI research papers and evaluate the   
  tradeoff between retrieval quality and LLM reasoning performance.

  - Engineered a document processing pipeline using LangChain to ingest PDFs and split them into semantically meaningful overlapping chunks
  - Implemented a vector search system using all-MiniLM-L6-v2 embeddings and ChromaDB for efficient similarity retrieval
  - Designed a top-k retrieval layer with filtering to remove noisy chunks (e.g., citations and references) and improve context quality
  - Developed a local generation module using FLAN-T5-base with prompt engineering to enforce grounded, concise, and non-hallucinated
    responses
  - Built an evaluation framework using RAGAS to measure faithfulness, answer relevancy, context precision, and context recall
  - Analyzed system failures, identifying that generation quality—not retrieval—was the primary bottleneck in performance
  - Compared retrieval vs. synthesis behavior across conceptual vs. descriptive queries to evaluate model limitations under real-world
    constraints
  - Derived insights on how small LLMs struggle with reasoning even when provided with high-quality retrieved context

  Tech: Python, LangChain, ChromaDB, SentenceTransformers, FLAN-T5, RAGAS, PyTorch, NLP

### 🔹 [Illinois SafeZone: End-to-End Data Engineering Pipeline](https://github.com/emandabisrat/Illinois-Safe-Zones) 

  Engineered a reproducible data pipeline integrating Illinois crime data with external datasets (business licensing, median income, and       weather) to analyze public safety patterns.

  - Built an ETL pipeline to extract and unify data from multiple heterogeneous sources
  - Designed and implemented a relational schema in Snowflake, including DDL and automated DML workflows
  - Performed data cleaning, transformation, and batch ingestion at scale
  - Integrated weather data and contextual features to enrich analysis
  - Conducted exploratory data analysis (EDA) to identify trends in crime and environmental factors
  - Deployed an interactive Streamlit dashboard for data visualization and user exploration
  - Incorporated modular pipeline components (MCP) for scalable and maintainable workflows

  Tech: Python, Snowflake, SQL, Streamlit, Pandas

### 🔹 [AI Bias in Resume Screening](https://github.com/emandabisrat/AI-Discrimination-) 

  Investigated algorithmic bias in AI-driven hiring by evaluating how an LLM makes resume screening decisions.

  - Generated a synthetic dataset of resumes with controlled variations in gender, education, and experience
  - Used GPT-4o to simulate real-world hiring decisions in a standardized evaluation setup
  - Measured disparities in selection outcomes across demographic groups
  - Analyzed how feature representation (skills, experience) influences model decisions
  - Provided insights into fairness risks and limitations of LLM-based hiring systems

  Tech: Python, Pandas, Scikit-learn, LLM APIs

### 🔹 [Student Performance & Alcohol Consumption Analysis](https://github.com/emandabisrat/Academic-Performance-Predictive-Modeling-)

  Developed machine learning models to analyze and predict student academic performance based on alcohol consumption patterns.

  - Applied K-Means clustering to identify behavioral patterns among student groups
  - Built Random Forest and predictive models to estimate academic outcomes
  - Performed feature analysis to understand the impact of alcohol consumption on performance
  - Created visualizations to effectively communicate trends and model insights

  Tech: Python, Scikit-learn, Pandas, Matplotlib

### 🔹 [Dialect Classification Using NLP](https://github.com/emandabisrat/Dialect-Classification-)

  Built a model to classify regional dialects based on textual patterns.

  - Generated embeddings using SBERT
  - Trained a Random Forest classifier with class balancing (SMOTE)
  - Evaluated model performance across dialect groups
  - Explored linguistic patterns driving classification decisions

  Tech: Python, SentenceTransformers, Scikit-learn, Imbalanced-learn

### 🔹 [Flight Delay Prediction (Classification & Regression)](https://github.com/anisadye-portfolio/Predicting-U.S.-Domestic-Flight-Delays)

  Developed machine learning models to predict both the likelihood and magnitude of U.S. flight delays using 30 million records of  
  historical flight data.

  - Built a classification model to predict whether a flight is delayed (15+ minutes)
  - Developed a regression model to estimate total delay time (in minutes)
  - Implemented models including Logistic Regression, Random Forest, and Gradient Boosting
  - Applied feature engineering and model evaluation to improve predictive performance
  - Compared model types to understand trade-offs between accuracy and interpretability

  Tech: Python, Scikit-learn, Pandas


<!--
**emandabisrat/emandabisrat** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
