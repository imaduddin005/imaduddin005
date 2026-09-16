<h1 align="center">Hi, I'm Imad ud Din </h1>
<h3 align="center">AI Engineer · Generative AI · Agentic AI · RAG Systems</h3>

<p align="center">
  <a href="https://imaduddin005.github.io/portfolio/"><img src="https://img.shields.io/badge/Portfolio-Visit-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/imad-u-2463a6318"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:imadkhann005@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

### About

AI Engineer specializing in **Generative AI, Agentic AI, and RAG-based systems**, with hands-on experience developing LLM-powered applications, AI agents with tool integration, and intelligent pipelines using **LangChain, LangGraph, and vector databases**. Brings strong Machine Learning and Deep Learning foundations — spanning CNNs, RNNs, transfer learning, and model optimization — applied across real-world computer vision and medical imaging projects to deliver scalable, production-ready AI solutions.

I design and build **Retrieval-Augmented Generation systems from the ground up** — document ingestion, chunking, embedding generation, vector store integration, and retrieval-grounded response generation — engineered to cut hallucinations and keep LLM outputs accurate, current, and traceable to real source data. I take the same systems-first approach to **Agentic AI**: building LLM agents that reason in multi-step chains, call external tools and APIs autonomously, and verify their own outputs, using LangChain, LangGraph, and MCP for orchestration.

Recent Computer Science graduate (BS, Pak-Austria Institute of Applied Sciences & Technology, 2026) with three industry internships across AI/ML engineering, LLM/RAG development, and government IT, completed alongside full-time academic studies.

- 🔭 Currently building **agentic AI pipelines** with LangChain & LangGraph, including multi-agent research systems with tool-grounded reasoning
- 🧠 Strong foundation in **Deep Learning** — CNNs, RNNs/LSTMs/GRUs, transfer learning, model explainability (Grad-CAM++)
- 🧩 Building **production-grade RAG systems** end-to-end: ingestion → embeddings → retrieval → grounded generation
- 🩻 Applied AI to real-world domains: **medical imaging, veterinary ML, voice assistants**
- 🎓 Recent graduate, open to AI Engineering opportunities

---

### Experience

**AI Engineering Intern** — ATS, UK (Remote) · *Apr 2025 – Jun 2025*
Designed and built stateful multi-agent workflows in LangGraph, using conditional routing and checkpointed memory to
handle multi-step reasoning tasks reliably across sessions.
• Standardized how agents connected to external tools by adopting MCP (Model Context Protocol), cutting down on ad-hoc
integration code and making tool access consistent across agents.
• Added structured output validation and human-in-the-loop approval steps at key decision points — a deliberate tradeoff to keep
agents fast without giving up control over high-stakes actions.
• Built a RAG pipeline for grounding agent responses in real documents, which noticeably cut down on hallucinated answers
compared to plain LLM prompting.
• Used LangSmith to trace and debug multi-step agent workflows, quickly identifying where failures occurred.

**AI Engineering Intern** — Comrex Pvt Ltd · *Jul 2024 – Sep 2024*
• Built end-to-end RAG pipelines using LangChain, integrating vector databases and document embeddings to deliver
context-aware LLM responses.
• Developed multi-step reasoning workflows using LangChain agents for complex question-answering and task automation.
• Designed and experimented with Agentic AI systems enabling LLMs to autonomously interact with external tools and APIs.
• Applied advanced prompt engineering and tuning techniques to enhance contextual understanding and significantly reduce
hallucinations.
• Integrated Generative AI solutions into production-style applications: chatbots, Q&A systems, and knowledge-based assistants.

**AI Intern** — Ministry of IT & Telecom, Pakistan · *Aug 2023 – Oct 2023*
Conducted data preprocessing and exploratory data analysis (EDA) on structured government datasets to extract actionable
insights.
• Developed Python-based data visualizations using Pandas, NumPy, and Matplotlib to identify trends, patterns, and KPIs.
• Applied foundational ML techniques for prediction and classification; gained exposure to government IT infrastructure and
digital transformation initiatives.
• Optimized ML models via hyperparameter tuning and PCA-based feature engineering, improving accuracy across regression
and classification tasks.
• Applied transfer learning with pre-trained CNNs (ResNet, DenseNet, EfficientNet, YOLOv9) and LSTM/GRU models,
along with data augmentation to boost robustness on limited datasets.
• Explored deep learning-based document classification using CNN architectures to automatically categorize scanned
government documents, supporting digital record-keeping initiatives.
---

### Featured Projects

#### 🩻 [Spine Disease Detection from X-Ray Images](https://github.com/imaduddin005)
`PyTorch` `YOLOv9` `DenseNet` `Grad-CAM++` `Pydicom` `OpenCV`
A deep learning pipeline for automated spinal pathology detection, combining **YOLOv9** for object detection with **DenseNet** for classification on annotated medical X-ray datasets. Used **Pydicom** to handle DICOM medical imaging formats and **Grad-CAM++** to make model predictions visually explainable — critical for any clinical-adjacent AI system. Applied transfer learning and advanced augmentation to maintain accuracy despite limited medical training data.

#### 🤖 [Multi-Agent Research System](https://github.com/imaduddin005/multi-agent-research-system)
`LangChain` `LangGraph` `Gemini` `Tavily` `RAG` `Agentic AI`
A fully agentic research pipeline built from scratch: a **Search Agent** retrieves live information via the Tavily API, a **Reader Agent** autonomously selects and scrapes the most relevant source (with PDF-aware extraction, including auto-following arXiv papers to full text), a **Writer chain** synthesizes a structured report grounded in that retrieved evidence, and a **Critic chain** self-reviews the output and scores it. Every tool call is logged and traced to verify the agents are genuinely grounding answers in retrieved data rather than hallucinating from memory — a real implementation of retrieval-grounded, multi-agent reasoning with LCEL (LangChain Expression Language) pipelines.

#### 🎙️ AI Video Assistant (https://github.com/imaduddin005)
Whisper · Mistral AI · RAG · LangSmith · Streamlit · GitHub
Built an end-to-end pipeline that transcribes YouTube videos or local audio/video files using Whisper and runs summarization,
action-item, and key-decision extraction in parallel using Mistral AI.
• Implemented a RAG-based chatbot over each transcript using a Chroma vector store, rebuilt per session to keep answers
grounded strictly in the correct video’s content.
• Integrated LangSmith tracing to monitor prompts, token usage, and latency, and built both a Streamlit web interface and a
command-line version for running the pipeline.

####  [Pakistan AI Company Discovery Agent](https://github.com/imaduddin005)
Python · Streamlit · BeautifulSoup · SQLite · Ollama (Gemma 3) · GitHub
Built an autonomous discovery agent that finds software houses and tech companies across major Pakistani cities that
genuinely work with AI, using automated web search, scraping, and deterministic keyword classification.
• Designed a hybrid classification pipeline: fast rule-based keyword matching handles most companies, with a cached, local LLM
(Ollama + Gemma 3) call used only for ambiguous cases to minimize token cost.
• Implemented SQLite-backed caching for scraped domains and LLM classifications, avoiding redundant network requests and
re-classification on repeated searches.
• Shipped both a Streamlit web interface and a CLI, letting users filter results by city and AI domain (Machine Learning, GenAI,
Agentic AI, RAG, NLP, etc.).
---

### Tech Stack

**Languages:** Python · C++

**GenAI & LLM:** LangChain · LangGraph · MCP (Model Context Protocol) · RAG Pipelines · Prompt Engineering · Vector Databases

**AI Automation** n8n . Claude Code . Open AI Api . Workflow Automation . Agentic Ai pipline 

**ML / DL Frameworks:** PyTorch · TensorFlow · Keras · Scikit-learn

**Computer Vision:** YOLOv9 · ResNet · DenseNet · EfficientNet · OpenCV · Transfer Learning · Grad-CAM++

**Data & Visualization:** Pandas · NumPy · Matplotlib · Feature Engineering · PCA · Data Augmentation

**Backend & APIs:** FastAPI · Flask · REST APIs

**Databases:** MySQL · PostgreSQL

**Tools:** Git · GitHub · Jupyter Notebook · Google Colab · Kaggle · VS Code

**Methods:** Supervised & Unsupervised Learning · Hyperparameter Tuning · LSTM/GRU · Transformer Models

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=imaduddin005&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=imaduddin005&layout=compact&theme=tokyonight&hide_border=true" height="165" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=imaduddin005&theme=tokyonight&hide_border=true" height="165" />
</p>

---

<p align="center"><i>Open to AI Engineering roles, research collaboration, and challenging agentic AI / RAG problems.</i></p>
