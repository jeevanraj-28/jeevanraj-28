<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a5f,100:38bdf8&height=180&section=header&text=Jeevan%20Raj%20M&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Applied%20ML%20%2F%20LLM%20Engineer%20%E2%80%A2%20RAG%20%E2%80%A2%20NLP%20%E2%80%A2%20Computer%20Vision&descSize=17&descAlignY=58&descColor=cbd5e1" width="100%" />

<a href="mailto:jeevanrajm2882004@gmail.com"><img src="https://img.shields.io/badge/Email-jeevanrajm2882004%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
<a href="https://linkedin.com/in/jeevan-raj-m-5ba64a383"><img src="https://img.shields.io/badge/LinkedIn-Jeevan%20Raj%20M-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="https://jeevanraj-28.github.io"><img src="https://img.shields.io/badge/Portfolio-jeevanraj--28.github.io-38bdf8?style=flat-square&logo=googlechrome&logoColor=white" /></a>

</div>

I build applied ML systems and measure them: retrieval pipelines with recall@k evaluation, segmentation models judged on held-out mIoU, and NLP extractors scored against labelled test sets. I care about finding where a model fails, not just showing where it works.

- B.E. in Artificial Intelligence & Data Science, University of Mysore School of Engineering (2022–2026), CGPA 9
- AI Development Intern at Kinetrix Technologies (Oct 2025 – May 2026): built Hugging Face-based clinical speech-to-text (Whisper, BERT) and radiology image analysis (YOLO, ResNet) modules for CARE, an open-source healthcare platform, behind a FastAPI backend with OAuth2/JWT/RBAC and Celery workers
- Based in Mysuru, Karnataka, India

---

## Projects

| Project | What it is | Result |
| --- | --- | --- |
| **[Lumina RAG](https://github.com/jeevanraj-28/lumina-rag-assistant)** | Private, local document Q&A with citations. FastAPI, FAISS, local LLMs via Ollama, OCR for scanned PDFs, OpenAI-compatible API, Docker | Built a retrieval evaluation (recall@k, MRR). A coverage test found the chunker silently dropped about 13% of each document; fixed and covered by tests |
| **[Disaster Segmentation](https://github.com/jeevanraj-28/Disaster-segmentation)** | Pixel-level flood damage maps from drone images (FloodNet, 10 classes). U-Net with a ResNet34 encoder in PyTorch | 70.7% mean IoU on 448 held-out test images. Small objects (vehicles, pools) are the main error, analysed per class |
| **[Clinical NLP Demo](https://github.com/jeevanraj-28/Clinical-NLP-Demo)** | Turns synthetic doctor dictation into structured sections and a medication list, with negation handling and a summary checked for invented numbers | Micro F1 0.71 → 0.97 on 20 held-out labelled notes; negated findings listed as complaints 6 of 9 → 0 of 9 |
| **[CafeCritic](https://github.com/jeevanraj-28/cafecritic-recommender)** | Cafe recommender: TF-IDF similarity on cafe profiles combined with rating, in Streamlit | A data audit showed every reviewer had one rating, so collaborative filtering could not work; redesigned around what the data supports |

Every project has a README with setup steps, results, what failed and what I changed, plus tests that run on each push.

---

## Skills

**ML and data:** Python, PyTorch, scikit-learn, Hugging Face Transformers, pandas, NumPy, OpenCV, SQL

**LLMs and retrieval:** RAG, embeddings, FAISS, chunking, retrieval evaluation (recall@k, MRR), prompt design, Ollama

**Serving and tools:** FastAPI, Celery, Docker, Streamlit, PostgreSQL, Git, Linux, GitHub Actions

---

<div align="center">
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jeevanraj-28&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38bdf8&text_color=94a3b8&langs_count=6" />
</div>
