# Hi, I'm Andi 👋

**Software Engineer · Applied AI & Machine Learning · [M.S. field] @ [University], Dec 2027**

I'm a first-generation college graduate who loves building new tools and apps. I still build full-stack applications regularly, because AI only delivers value when it lives inside well-engineered software. I got into AI because it's already shaping everyone's lives, and I want to help companies adopt it responsibly so the benefits reach everyone, not just a few.

My focus is on what makes AI trustworthy: rigorous evaluation to confirm it actually works, thoughtful guardrails to keep it safe, and systems people can rely on with sensitive data.

🔍 Open to [AI / ML / backend] engineering roles &nbsp;·&nbsp; 📍 Indianapolis, IN · Chicago, IL · New York, NY · Remote · Open to relocation

[![LinkedIn](https://img.shields.io/badge/LinkedIn-andi--castillo-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andi-castillo/)
[![Email](https://img.shields.io/badge/Email-Contact_me-D14836?logo=gmail&logoColor=white)](mailto:[your-email])

---

## 🔧 Featured Projects

### 🔐 [Secure Multi-Technique RAG](https://github.com/Andi-Cast/RAG_Implementations) &nbsp;`in progress`

A RAG system over ~92K chunks of synthetic medical records, built around one question: **what happens when different users are legally allowed to see different parts of the same data?**

- Benchmarks a retrieval ladder (dense → hybrid RRF → cross-encoder rerank → contextual compression) with hand-implemented Recall@k, MRR, and nDCG. Hybrid + reranking lifted MRR from 0.38 to 0.61 on the pilot gold set.
- Security layer: role-based access control enforced *inside* the vector query (fail-closed, never a post-filter), PII redaction, and prompt-injection defense, each measured with its own metrics.
- No LangChain; orchestration is hand-rolled so every step stays inspectable.

**Stack:** Python · PostgreSQL + pgvector · sentence-transformers · Docker · pytest

---

### 🌧️ [Rain Tomorrow Classifier](https://github.com/Andi-Cast/LogisticRegressionWeatherClassifier)

Predicts next-day rain at Australian weather stations, then tests whether the model generalizes to an independent Bureau of Meteorology dataset.

- Chronological train/validation/test split to prevent leakage; class imbalance handled with a weighted loss.
- Decision threshold tuned for recall rather than defaulting to 0.5.
- Out-of-source validation reached 0.79 ROC-AUC and showed how same-source metrics overstate real-world performance.

**Stack:** Python · PyTorch · scikit-learn · pandas · TensorBoard

---

### 👁️ Facial Feature Detection (Capstone)

Object detectors for eyes, mouths, faces, and hands trained on 27,000+ video frames with custom-labeled datasets.

- Achieved IoU > 50 on 4 of 5 target features.

**Stack:** MATLAB · Faster R-CNN

---

## 🛠️ Tech Stack

[![Tech stack](https://skillicons.dev/icons?i=py,pytorch,sklearn,matlab,postgres,docker,aws,java,spring,js,ts,react,nodejs,mysql,mongodb,git&perline=8)](https://skillicons.dev)

**AI/ML:** RAG · pgvector · hybrid search · cross-encoder reranking · retrieval evaluation · object detection · classification
**AWS:** EC2 · S3 · Lambda · SageMaker · CloudWatch · IAM

---

## 🎓 Education & Certifications

- **M.S. AI and ML**, Purdue University (expected December 2027)
- **B.S. Computer Science**, Purdue University
- **AWS Certified Cloud Practitioner**
- **AWS Certified AI Practitioner**

---

<sub>First-gen CS grad · Always happy to talk shop, collaborate, or get feedback on my work.</sub>
