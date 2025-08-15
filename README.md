# 🚀 Ansar Afsar | AI Innovator & Data/ML Player 🌌

👋 Hey there! I'm **Ansar Afsar**, a Master’s in Computer Science grad (Government Arts College, Salem, 2025, 8.01 GPA) driven by a passion for building AI-driven, privacy-first solutions. From multilingual NLP pipelines to scalable cloud deployments, I craft tools that solve real-world problems with precision and impact.  
**My mantra?** Turn complex data into actionable insights using Python, PyTorch, and a sprinkle of DevOps magic.

---

## 🌟 About Me

- 🔭 **Current Focus**: Developing AI/ML pipelines for content moderation and personalization, with a focus on privacy and scalability.  
- 🌱 **Learning Edge**: Deepening expertise in NLP (transformers, embeddings), MLOps, and AWS cloud orchestration.  
- 🎓 **Education**:  
  - M.S. Computer Science (2025)  
  - B.S. Computer Science (2023)  
  - Government Arts College, Salem  
- 🏆 **Certifications**:  
  - Google Data Analytics  
  - IBM Data Analyst  
  - Cisco Networking  
  - Microsoft Business Analytics  
- 📫 **Connect**:  
  - 📧 ansarafsar001@gmail.com  
  - [LinkedIn](https://www.linkedin.com/)  
  - [X (Twitter)](https://x.com/ansar_afsar_)

---

## 🛠️ Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### AI/ML
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD43B?style=for-the-badge&logo=python&logoColor=black)

### Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

### Computer Vision
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![YOLOv5](https://img.shields.io/badge/YOLOv5-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)
![Roboflow](https://img.shields.io/badge/Roboflow-000000?style=for-the-badge&logo=roboflow&logoColor=white)

### Data & Visualization
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

### Web Dev
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Blockchain
![AlgoKit](https://img.shields.io/badge/AlgoKit-FF6F61?style=for-the-badge&logo=algorand&logoColor=white)

### Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=black)


---

## 🏆 Notable Projects

### 🚨 Multilingual Hate Speech Detection Pipeline
A GPU-accelerated microservices pipeline for real-time content moderation on professional platforms.  

**Processes JSON inputs** (e.g., `"Ami kal party te jabo"`) with:
- **Translation**: `easynmt` (m2m_100_418M) for non-English to English
- **Hate Speech Detection**: Ensemble (fasttext, MuRIL, IndicBERT, XLMR, DistilBERT) with rule-based boosts; flags >0.7 scores
- **Tagging**: `intfloat/e5-large-v2` embeddings for personalized curation

**Tech**: Docker, PyTorch 2.1.2, AWS EC2 `g4dn.xlarge` (NVIDIA T4, CUDA 12.8), Nginx proxy  
**Impact**: Sub-0.8s inference, fault-tolerant with backup models, logs to `flagged_hate_speech.jsonl` for retraining  
**Privacy**: Self-hosted to bypass external APIs like GPT, ensuring data security  

---

### 📈 Retail Sales Prediction Dashboard
A **Streamlit** app forecasting retail trends using **Scikit-learn** and **Pandas**.  
**Impact**: Optimized inventory planning with predictive analytics.  
**Demo**: *[GIF TBD]*

---

### 💬 Smart Retail BI Chatbot
AI-driven Q&A for retail analytics using **LangChain** and **Streamlit**.  
**Impact**: Instant insights from complex datasets for business users.

---

### 🔗 Web3 Supply Chain Solution
Blockchain-based logistics tracking on **Algorand testnet** with **AlgoKit**.  
**Impact**: Enhanced transparency in supply chain workflows.

---

### 📊 Sentiment Analysis Dashboard
NLP-driven social media trend visualization using **NLTK** and **Seaborn**.  
**Impact**: Empowered marketing teams with sentiment insights.

---

## 🌟 Achievements

- 💼 **Internships**: Contributed to AI/ML projects at ZEEX AI, Tienext, BOOKDIO, and Unified Mentor (2024–2025)  
- 🛠️ **Open Source**: Fixed bugs and improved docs for Python ML libraries  
- 👨‍🏫 **Mentorship**: Guided 15+ undergrads in CS projects, focusing on AI and data science  
- ✍️ **Blogging**: Published 10+ Medium articles on AI trends, NLP, and cloud computing  

---

## 💡 Why This Matters

My work focuses on **privacy-first AI**, leveraging **self-hosted models** to avoid data leaks (unlike GPT-based APIs).  
The hate speech pipeline showcases:

- **Scalability**: Modular microservices for easy scaling on AWS  
- **Efficiency**: GPU-accelerated inference (<0.8s) for real-time apps  
- **Impact**: Safer digital platforms through robust moderation and curation

---

## 🌍 Let’s Connect

<a href="https://www.linkedin.com/in/ansar-afsar/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/>
</a>
<a href="https://x.com/yourhandle](https://x.com/ansar_afsar_">
  <img src="https://img.shields.io/badge/X-000000?style=flat&logo=x&logoColor=white"/>
</a>


---

## 🎮 Fun Facts

- 🚴 Cycling trails keep my code sharp and spirit high  
- 🎲 Strategy games are my jam—love outsmarting AI opponents  
- 📚 Always reading: AI papers, tech blogs, or a thrilling sci-fi novel  

---

⭐ **Star my repos if you find them inspiring! Let’s build the future of AI together!**

✍️ [Portfolio Website](https://ansarafsar.github.io/portfolio/)

<!--
**Ansarafsar/Ansarafsar** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
