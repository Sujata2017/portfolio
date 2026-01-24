
## 🤖 Generative AI Skill Matrix

#### 1. Core GenAI Orchestration

Frameworks: LangChain, LangGraph (for multi-agent flows), CrewAI, or AutoGen.

Agentic Design: Multi-agent orchestration, Intent Classification, and Task Decomposition.

RAG Advanced Techniques: Semantic Search, Hybrid Search, Parent-Document Retrieval, and Re-ranking.

Advanced Features: Token Streaming (SSE), Asynchronous AI Workflows, and Tool/Function Calling.

#### 2. Models & LLM Engineering

Proprietary Models: Azure OpenAI (GPT-4o, GPT-4 Turbo), Gemini Pro.

Open Source: Llama 3, Mistral, Mixtral (implementation via Hugging Face or Ollama).

Optimization: Prompt Engineering (Chain-of-Thought, Few-Shot, ReAct), Context Window Management.

#### 3. Data & Infrastructure (The "AI Stack")

Vector Databases: Pinecone, ChromaDB, FAISS, or Azure AI Search.

Relational AI: Text-to-SQL generation, SQLAlchemy, and Database schema mapping for LLMs.

Cloud Ecosystem: Azure AI Studio, Azure Blob Storage (for logging), Azure SQL.

#### 4. AI Governance & Operations (LLMOps)

Reliability: Human-in-the-Loop (HITL) architecture design and feedback loop integration.

Evaluation: Building evaluation pipelines for hallucination detection and response accuracy.

Monitoring & Logging: Conversation tracing, and audit logging.




# Other Technical Skills

* Machine Learning:
Classification, Regression, Clustering, Regularization, Decision Tree, Random Forest, SVM, PCA,
Gradient Boosting, Feature importance methods, (k-means, DBSCAN), Dimension Reduction
(PCA, SVD), Ensemble techniques (XGBoost, CatBoost, LightGBM), LSTM, cross-validation,
hyperparameter tuning, error analysis

* Deep Learning: 
RNN, CNN, Transfer Learning, GAN, Faster RCNN, Mask RCNN, YOLO, SSD
NLP: Bag of words, tf-idf, Stemming, Lemmatization, Tokenization, POS tagging, Sequence modeling,
Attention mechanism, Transformers, BERT, GPT, Semantic similarity, Entity Extraction, Document
summarization, Question-Answering, Machine Translation\

* Tools: Python, MySQL, Anaconda, Flask, streamlit, AWS, JIRA, Tableau, PostgreSQL, Git, DVC, Docker,
Generative AI, Gemini Pro, Hugging Face

* Packages: NumPy, SciPy, Pandas, Statsmodels, Dask, scikit-learn, Matplotlib, Plotly, Seaborn, OpenCV,
TensorFlow, Pytorch, MLflow, YOLO, DagsHub, LangChain, OpenAI, SHAP

* OS: Windows, Linux





# Professional Experience

August 2025 - Present - Senior Consultant at Capgemini

o Technical Responsibilities:
- Developed a high-concurrency, multi-agent AI orchestrator for a major Telecom client to unify access to structured billing data (SQL) and unstructured technical documentation (RAG).

- Designed a "Master Orchestrator" using LangChain/LangGraph that acts as the brain, performing intent classification to route queries to either the SQL Expert Agent or the RAG Knowledge Agent.

- Built a SQL Agent using Azure OpenAI and SQLAlchemy to translate natural language into optimized SQL queries, enabling real-time billing and usage insights.

- Developed a RAG pipeline utilizing Vector Embeddings and Semantic Search to extract precise answers from complex telecom manuals.

- Implemented Server-Sent Events (SSE) to enable "ChatGPT-like" token streaming, significantly reducing perceived latency and improving user engagement metrics.

- Engineered a custom logging interceptor that captures full conversation traces (including intermediate agent reasoning) and archives them to Azure Blob Storage for compliance and RLHF (Reinforcement Learning from Human Feedback) fine-tuning.




March 2019 - July 2025 - Senior Software Engineer at HCL Technologies

o Technical Responsibilities:

- Worked on a generative AI project, a conversational chatbot, which will extract data from JIRA dashboard using RAG and answer to user's query.

- Fine-tuned open-source LLM models, customizing solutions to meet specific project requirements
- Developed a Langgraph Application for automating the workflow of Coding Peer Reviews using open source LLMmodels and debugged with the help of Langsmith.

- Worked on Dell EMC Avamar - a hardware and software data backup product.

- Created and maintained knowledge base articles, troubleshooting guides, and technical documentation to assist supportteams and customers.

- Participated in daily scrum meetings to provide technical insights and contribute to sprint planning.




July 2017 - February 2019 - Software Engineer at DELL EMC

o Technical Responsibilities:

- Worked on VPLEX – an enterprise storage solution

- Developed diagnostic tools for monitoring VPLEX system health and performance

- Analysed logs, system behavior to root cause and workaround customer raised problems

- Created and maintained knowledge base articles, troubleshooting guides, and technical documentation
to assist support teams and customers.

- Designed JIRA/Confluence queries, dashboards for metrics reporting for various teams

- Extracted different KPI data from JIRA server by hitting JIRA rest API's.

- Created and maintained dashboard using Tableau for visualization and understanding of various KPI measures.

- Built Python Scripts to develop EDA processes and transform into industry dashboards with plotly for internalstakeholders.







# Projects

o Project Title : AI-Powered-SDLC-Assistant

- Designed an intelligent SDLC automation suite that balances AI speed with human expertise. Unlike fully autonomous systems, this assistant utilizes a staged-gate architecture, where the AI performs heavy lifting (drafting code, tests, or requirements) but requires explicit human validation and feedback before progressing to the next stage of the lifecycle.

- Requirement Gatekeeping: The AI generates a PRD (Product Requirements Document) or User Stories. The system pauses for a Business Analyst to review, edit, and "thumbs-up" the output before the AI is permitted to begin the technical architecture phase.

- Iterative Prompt Refinement: Implemented a feedback loop where human corrections are fed back into the prompt context in real-time. If a developer rejects a code snippet, the AI asks for the reason and regenerates the code based on that specific feedback.

- Supervised Code Generation: Instead of direct commits, the AI creates "Draft Pull Requests." A Senior Developer must review the AI’s logic and security analysis, providing a human safety layer before the code enters the CI/CD pipeline.

- Strategic Impact
* Trust & Reliability: Solved the "Trust Gap" in AI by ensuring 100% human oversight for critical software artifacts.

* Error Reduction: Reduced AI hallucination impact to near zero by implementing mandatory human verification at the "Requirement to Code" transition.

* Upskilling: Positioned the tool as a "Co-pilot" that empowers developers rather than replacing them, facilitating smoother organizational adoption.

- [GitHub link](https://github.com/Sujata2017/AI-Powered-SDLC-Assistant)



o Project Title : Personal-Healthcare-Assistant

- Medical Knowledge RAG: Built a Retrieval-Augmented Generation (RAG) engine that allows users to upload medical reports (PDFs/Images) and receive simplified, jargon-free explanations of their health status.

- Multi-Modal Interaction: Integrated Whisper AI for speech-to-text, allowing elderly or visually impaired users to interact with the assistant via voice commands.

- Intelligent Symptom Checker: Leveraged LLMs to provide preliminary health guidance based on user symptoms, emphasizing a "Safe AI" approach by including medical disclaimers and urging professional consultation.

- Medication Reminders & Tracking: Developed a logic-based module to help users manage prescription schedules and track health vitals over time.

- User-Centric UI: Designed and deployed a responsive dashboard using Streamlit, ensuring a clean and intuitive interface for non-technical users.

- [GitHub link](https://github.com/Sujata2017/Personal-Healthcare-Assistant)




o Project Title : Invoice-Extractor-Gemini-APP

- This is and end-to-end project about Invoice Extractor using Gemini Pro LLM Model and
deployed in Streamlit. User can upload an image and provide input in the prompt. When the
"Tell me about the image" button is clicked, the app processes the input and image, calls the
Gemini model, and displays the response.

- [GitHub link](https://github.com/Sujata2017/Invoice-Extractor-Gemini-APP)





o Project Title : Kidney-Disease-Classification
- In this project, used kidney CT scan images containing both normal images and images with
tumor, and implemented end to end Kidney-Disease-Classification project using MLflow(MLOps
tool, for experiment tracking and model registration) and DVC(for pipeline tracking). Developed
these components: Data Ingestion, Data Transformation, Model Trainer, Model Evaluation,
Model Deployment, and deployed this end to end ML application using CI CD pipelines and
GitHub actions using ECR and EC2 instance.
- [GitHub link](https://github.com/Sujata2017/Kidney-Disease-Classification)




